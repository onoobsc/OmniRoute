# Authorization Guide (中文 (繁體))

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md)

---

> **真實來源：** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **上次更新：** 2026-09-22 — 範圍命名空間指向 MCP-SERVER.md

OmniRoute 具有一個路由感知授權管道，用於把關每個 API 請求。分類是**確定性**且**故障關閉**的 — 任何無法分類的內容最終都會歸類為 `MANAGEMENT`，並要求會話或管理級別的令牌。本頁解釋了供維護路由或設計新端點的工程師使用的模型。

![授權管道（3 種路由類別 + 策略評估）](../diagrams/exported/authz-pipeline.svg)

> 來源：[diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## 兩種認證模式

### API密鑰（承載）

當金鑰具有`manage`範圍時，用於OpenAI/Anthropic/Gemini-compatible客戶端APIs和一些管理路由。

```
Authorization: Bearer <api-key>
```

由`src/sse/services/auth.ts`中的`isValidApiKey()` / `extractApiKey()`驗證並透過`src/shared/utils/apiAuth.ts`重新導出。驗證器也接受`OMNIROUTE_API_KEY` / `ROUTER_API_KEY`環境變數作為持久直通金鑰（問題#1350）。

### 2. 儀表板會話（auth_token cookie）

用於儀表板頁面和管理操作。

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

只有當JWT驗證時cookie才是會話**和**攜帶`authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`)。 cookie 的每個使用者（儀表板路由保護 (`isDashboardSessionAuthenticated()`)、authz 管道刷新、 WebSocket握手、即時伺服器、 `/api/settings/require-login`、 `/api/auth/status`）都會經過此幫助程式。其他使用`JWT_SECRET`簽名的JWTs存在— Cursor CLI直通為密鑰持有者—鑄造`iss "omniroute" / aud "cursor-cli"`代幣，且絕不是會話 (#13298)。

由`isDashboardSessionAuthenticated()`在`src/shared/utils/apiAuth.ts`驗證。當管道的 30 天生命週期只剩下不到 7 天時，管道會自動刷新JWT 。

會話也可以在 30 天結束之前結束，因為每個鑄幣者都會經過`mintDashboardSessionToken` （發佈時間`iat`和 id `jti`），並且驗證者會檢查兩個設定： `sessionsValidAfter`，由密碼更改設置，以便在停止驗證之前發出的每個會話（更改密碼的瀏覽器會獲得一個新的 cookie），以及`revokedDashboardSessions`，其中的`POST /api/auth/logout` `jti`將添加到最終的刪除階段。由舊版本建立的會話不包含任何聲明，並且在第一次密碼變更之前保持有效。如果無法讀取設置，則會話不可信。

一些管理路線接受**任何一個**模式：當API鍵具有`manage` （或`admin`）範圍時，cookie OR `Bearer <key>` 。這就是啟用 v3.8 中新增的「可透過API呼叫配置」工作流程的原因。

#### 可選的OIDC登入門 (#6973)

儀表板管理員登入也支持**選擇加入**OIDC (OpenID Connect) 與預設密碼登入一起流動—密碼登入永遠不會被刪除，只會被補充：

- 禁用，除非`settings.oidcEnabled === true`**和**`oidcIssuer` / `oidcClientId` / `oidcClientSecret`皆已配置（設定→ Auth）。否則`GET /api/auth/oidc/login`返回`400` 。
- `GET /api/auth/oidc/login`從發行者的`/.well-known/openid-configuration`中發現`authorization_endpoint` （回退到`<issuer>/authorize`），根據傳入請求 (`x-forwarded-proto` -aware) 建構重定向URI ，並使用儲存在`httpOnly` `oidc_state` cookie 中的隨機`state`重定向到IdP 。
- `GET /api/auth/oidc/callback`驗證`state`，交換授權碼，並透過發行者的JWKS （`jose`的`createRemoteJWKSet`，根據JWKS URI快取）和`issuer`/`audience`檢查來驗證ID令牌的簽章。儀表板准入需要非空`oidcAllowedSubjects`列表、 `oidcAdmissionClaim`策略或兩者。只有當`email_verified === true`時，主題清單才會符合`sub`或`email` 。可選的宣告策略採用點分隔的 ID 令牌宣告路徑（例如`realm_access.roles`）和接受值的陣列；已解決的宣告必須是包含至少一個接受值的字串陣列。如果配置了兩個策略，則兩個策略都必須通過。 Missing/malformed聲明失敗關閉，如果沒有任何策略，回呼將拒絕登入 (`not_configured`)。現有的僅主題配置繼續保持不變。
- Keycloak 通常將領域角色對應到存取令牌，不一定是ID令牌。要需要領域角色`admin`，請為此客戶端配置協定映射器，其中包含`realm_access.roles`**ID代幣**，然後將`oidcAdmissionClaim`設定為`{ "path": "realm_access.roles", "values": ["admin"] }`。在啟用僅角色准入之前，檢查該客戶端的實際 ID 令牌聲明；應用程式不會讀取存取令牌角色。 IdP 端令牌拒絕可以補充但不能取代此應用程式端檢查。
- 成功後，它會鑄成**完全相同**30 天`auth_token` JWT密碼登入問題 (`src/app/api/auth/login/route.ts`)，因此儀表板會話管道的其餘部分（自動刷新、cookie 標誌）保持不變— OIDC僅取代 cookie 的產生方式，而不是它授予的內容。對IdP roles/groups更改不會使現有OmniRoute會話失效；註銷、密碼輪換或會話過期仍然控制著它們的生命週期。
- 每個`oidc*`設定（`oidcEnabled`、 `oidcDisablePasswordLogin`、 `oidcIssuer`、 `oidcClientId`、 `oidcClientSecret`、 `oidcAllowedSubjects`、 `oidcAdmissionClaim`、 `oidcRedirectPath`、 `oidcScopes`）都在`SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) 中： `PATCH /api/settings`回答`400 PASSWORD_REQUIRED`除非主體攜帶管理密碼為`currentPassword` （錯誤時為`401 PASSWORD_MISMATCH` ）。 `oidcDisablePasswordLogin`拒絕密碼_login_ (`POST /api/auth/login`)，但保留儲存的密碼哈希，並且重新驗證仍會檢查`currentPassword` 。
- `corsOrigins`和`bruteForceProtection`也在`SECURITY_IMPACTING_SETTINGS_KEYS`中：放鬆會削弱登入防禦，因此它們會採用相同的`currentPassword`重新驗證（「安全性」標籤要求這樣做），並且JSON匯入會刪除它們。
- 每個安全性策略金鑰— `SECURITY_IMPACTING_SETTINGS_KEYS`條目、每個`oidc*`鑰和儀表板會話狀態—是**限運營商**在`PATCH /api/settings`上：管理範圍的API金鑰或`oma_`存取權杖即使發送正確的`currentPassword`也會被`403`拒絕，並且拒絕將被審核為`settings.update_failed`和`reason: OPERATOR_REQUIRED` （ `src/lib/api/operatorCredential.ts`中的`requireOperatorCredential()` ）。 `manage`密鑰或`admin`存取權杖的普通設定（主題、顯示首選項）保持可寫入。 `/api/settings`本身（和`/api/settings/require-login`）的每個突變也需要`admin`存取令牌範圍（ `src/server/authz/accessScopes.ts`中的`ADMIN_MUTATION_EXACT_PATHS` ，精確路徑匹配）； `GET`保留`read`推斷的`/api/settings/*`子路由（代理、組合預設值、模型別名、壓縮、清除...）保留方法推斷的`write`範圍。
- `POST /api/settings/import-json`會跳過重新驗證，因此它會在寫入之前刪除`IMPORT_STRIPPED_SETTINGS_KEYS` （同一檔案）中的每個金鑰：密碼和`currentPassword`、每個`SECURITY_IMPACTING_SETTINGS_KEYS`條目以及儀表板會話狀態（`sessionsValidAfter`、 `revokedDashboardSessions`）。因此，匯入較舊的備份無法恢復密碼變更或登出已結束的會話。

#### 可選的TOTP雙重登入 (#16619)

從設定→ Security 註冊；關閉直到操作員將其開啟（`src/server/auth/dashboardMfa.ts`）。

- **它涵蓋的內容：**密碼登入（`POST /api/auth/login`，然後需要`POST /api/auth/mfa/verify`）和`omniroute connect` （`POST /api/cli/connect`，拒絕僅密碼交換並將代碼作為`totp`）。
- **它不涵蓋的內容：** OIDC / SSO登入 (`/api/auth/oidc/callback`) 不要求提供OmniRoute TOTP。它依賴於身分提供者自己的第二個因素，因此如果啟用了OIDC ，則在IdP中強制執行MFA 。
- **恢復**（遺失設備、沒有留下恢復代碼或無法再驗證的因素，例如在`STORAGE_ENCRYPTION_KEY`更改後）：
  1. 使用`OMNIROUTE_DISABLE_MFA=true`重新啟動伺服器。
  2. 在主機本身（環回對等點和環回`Host`，例如`http://localhost:20128`）上，使用密碼登入。僅針對該原點跳過第二個因素；所有其他來源仍然需要該程式碼。
  3. 在「設定→安全性→停用」中，輸入密碼並將代碼留空。只有當設定了變數且請求來自主機時， `POST /api/auth/mfa/disable`才接受不帶`code`的主體；它仍然需要儀表板會話和當前密碼，並被審核為`auth.mfa.disabled`和`secondFactor: "recovery_switch"`。
  4. 取消設定`OMNIROUTE_DISABLE_MFA`，重新啟動，然後根據需要再次註冊。

## 路由類別

`src/server/authz/types.ts` 定義了三種類別；任何無法被確定性分類的路由都會退回為 `MANAGEMENT`。

| 類別         | 說明                                                                                                                                  | 所需認證                                                  |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| `PUBLIC`     | 明確安全的路由：登入、登出、狀態、初始化、健康檢查、新手引導啟動。                                                                    | 無                                                        |
| `CLIENT_API` | 模型服務端點：`/api/v1/*`、`/api/v1beta/*`，以及別名 `/v1/*`、`/v1beta/*`、`/chat/completions`、`/responses`、`/models`、`/codex/*`。 | 當有效的 `REQUIRE_API_KEY` 功能旗標啟用時需要 Bearer 金鑰 |
| `MANAGEMENT` | 儀表板頁面、設定、提供者、金鑰、管理與診斷端點。                                                                                      | 儀表板工作階段，或具有 `manage` 範圍的 Bearer             |

部分 `MANAGEMENT` 操作是**僅限操作員**的：只有 `manage` 金鑰是不夠的。匯出已儲存的憑證（`GET /api/settings/export-json`、`GET /api/db-backups/export`、`GET /api/db-backups/exportAll`）、將備份還原到現有資料之上（`POST /api/db-backups/import`，包括 `dryRun=true`；依 id 進行的 `POST /api/db-backups` 還原；`POST /api/settings/import-json`）、銷毀還原點（`DELETE /api/db-backups` 的清理，以及 `PATCH /api/db-backups`，因為它持久化的保留策略會驅動每次備份後的自動修剪）時，需要儀表板工作階段、本機 CLI 主體，或已停用登入。核發同步權杖（`POST /api/sync/tokens`）以及核發 `admin` CLI 存取權杖（`POST /api/cli/tokens`）在所有登入模式下都需要儀表板工作階段或本機 CLI 主體。任何範圍的 API 金鑰與 `oma_` 存取權杖都不是操作員憑證：在需要操作員憑證的地方，它們會收到 `403`。檢查邏輯位於 `src/lib/api/operatorCredential.ts`（`resolveOperatorCredential()` / `requireOperatorCredential()`）。變更登入設定同樣僅限操作員：一旦存在密碼，`POST /api/settings/require-login`（設定管理密碼 / 切換 `requireLogin`）只接受這些憑證。首次執行的引導視窗（尚無密碼）維持不變；儀表板工作階段必須傳送 `currentPassword` 才能取代密碼（缺少或錯誤時回傳 `403`，並記錄為 `settings.update_failed`）。本機 CLI 以及已停用登入的執行個體保留復原路徑，可以在不提供密碼的情況下設定密碼，因為兩者都綁定到擁有資料目錄的主機。

## 管道

```
Incoming request → src/proxy.ts
  → runAuthzPipeline() in src/server/authz/pipeline.ts
    1. Strip trusted internal headers (x-omniroute-auth-*, x-omniroute-route-class)
    2. Generate request id, classify route via classifyRoute()
    3. If pathname == "/" → redirect /dashboard
    4. If draining (graceful shutdown) and /api/* → 503
    5. If non-GET /api/* → checkBodySize() guard
    6. If OPTIONS → CORS preflight 204
    7. If options.enforce == false → pass-through with route-class headers
    8. Otherwise: POLICIES[routeClass].evaluate(ctx)
       - allow  → stamp x-omniroute-auth-{kind,id,label,scopes} → NextResponse.next()
       - reject → JSON error w/ correlation_id (dashboard pages → 302 /login)
```

可信內部標頭（在`src/server/authz/headers.ts`中定義）是**從傳入請求中剝離**分類之前—客戶端無法預先填入`x-omniroute-auth-*`來模擬主題。

### 保單合約

每個路由類別在`src/server/authz/policies/`中都有一個策略：

- **`publicPolicy`** (`policies/public.ts`) —總是回傳`allow({ kind: "anonymous", id: "anonymous" })`。
- **`clientApiPolicy`** (`policies/clientApi.ts`) —提取 Bearer，透過`validateApiKey()`進行驗證。只有當有效`REQUIRE_API_KEY`功能標誌被停用時才會轉為匿名。有效標誌透過`isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) 解析，因此儀表板功能標誌和環境變數一致地管理`/api/v1/*`、 `/api/v1beta/*`和別名；解析器故障無法關閉。允許客戶端API路由（包括儀表板模型目錄使用的`/api/v1/models`）上的儀表板會話請求。當啟用 Entra ID SSO時，結構上是 Entra 令牌的 Bearer（三個 base64url 段、 `RS*` alg、 `kid`）由SSO分支處理**前**`validateApiKey()`及其判決是最終的—它永遠不會落入 API 金鑰路徑或降級為匿名分支，因此身分提供者中斷不能成為開放存取。靜態API密鑰不受影響。參見[Entra ID SSO](../security/ENTRA_SSO.md) 。
- **`managementPolicy`** (`policies/management.ts`) —接受儀表板會話、內部模型同步請求（與`/api/providers/[name]/(sync-models|models)`匹配），或者如果`isAuthRequired()`返回 false，則完全跳過。當不記名令牌存在但無效時傳回 403 (`AUTH_001`)，否則傳回 401。在任何 auth 分支—也查看[Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)之前強制執行路由保護層 (LOCAL_ONLY / ALWAYS_PROTECTED)。當 Bearer key 攜帶`manage`範圍時，可以從非環回訪問`LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES`中的LOCAL_ONLY路徑（今天： `/api/mcp/`）；無論範圍如何，所有其他LOCAL_ONLY路徑都保持嚴格環回。

成功的策略會回到`AuthSubject`和`kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`。下游處理程序可以透過`src/server/authz/assertAuth.ts`中的`assertAuth(request, "CLIENT_API")`讀取它，而不是重新運行身份驗證邏輯。

## 公共路線列表

`src/shared/constants/publicApiRoutes.ts`是明確允許列表：

此列表分為**形狀**，且分割是承載的（GHSA-74g9-q8f6-793h）：前綴與`startsWith()`匹配，因此它也匹配共享其前導字元的每個相鄰路徑。 `/api/usage/om-usage`作為標記為`/api/usage/om-usage<anything>` PUBLIC前綴，Next 將其解析為`/api/usage/[connectionId]` —一個沒有自己的身份驗證的處理程序。

```ts
// Genuine subtrees. Every entry MUST end in "/" (asserted by a unit test).
PUBLIC_API_ROUTE_PREFIXES = [
  "/api/auth/oidc/",
  "/api/v1/", // treated as CLIENT_API in classify, not as "no-auth public"
  "/api/oauth/",
  "/api/codex/connect/",
  "/api/telegram/",
  "/api/cursor-cli/",
];

// Single routes, matched EXACTLY (with or without a trailing slash).
PUBLIC_API_ROUTES_EXACT = new Set([
  "/api/auth/login",
  "/api/auth/logout",
  "/api/auth/status",
  "/api/auth/mfa/verify", // login step 2 for opt-in TOTP; needs the MFA-pending cookie
  "/api/init",
  "/api/sync/bundle",
  "/api/cli/connect",
  "/api/usage/om-usage",
  "/api/skills/collect/chaos",
]);

// Read-only single routes that also take the CORS origin relaxation.
PUBLIC_READONLY_CORS_API_ROUTES = [
  "/api/health/ping",
  "/api/monitoring/health",
  "/api/settings/require-login",
];

// Read-only single route WITHOUT the CORS relaxation.
PUBLIC_READONLY_API_ROUTES_EXACT = new Set(["/api/health"]);

PUBLIC_READONLY_METHODS = new Set(["GET", "HEAD", "OPTIONS"]);
```

只讀路由是公開的**僅有的**以獲得安全的方法。注意： `classifyRoute()`從PUBLIC失敗的—中排除`/api/v1/*`和`/api/v1beta/*`它們總是`CLIENT_API`因此承載金鑰策略仍然適用。

## 新增路由

### 模式 1——公開用戶端 API 端點（Bearer 驗證）

位於 `/api/v1/` 和 `/api/v1beta/` 下的路由會自動分類為 `CLIENT_API`。中介軟體會強制執行 Bearer 檢查；路由處理常式不需要再次執行，但可在有需要時讀取主體。

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... 處理常式邏輯
}
```

### 模式 2——管理端點（工作階段或 Bearer + manage）

使用 `src/lib/api/requireManagementAuth.ts` 中的 `requireManagementAuth()`：

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... 處理常式邏輯
}
```

`requireManagementAuth()` 成功時會傳回 `null`，失敗時則會傳回包含 JSON 錯誤的 `Response`：

- 401 `AUTH_001`「需要驗證」——完全沒有憑證
- 403——Bearer 無效，**或**已提供 Bearer，但金鑰缺少 `manage` / `admin` 範圍

對於 `"manage"` 或 `"admin"`，`hasManageScope(scopes)` 會傳回 true。

### 模式 3——新增至公開允許清單

請根據形狀選擇集合，而非貪圖方便。單一路由應放入 `PUBLIC_API_ROUTES_EXACT`（若僅限 GET，則放入 `PUBLIC_READONLY_CORS_API_ROUTES`）；只有真正的子樹才能放入 `PUBLIC_API_ROUTE_PREFIXES`，且它**必須以 `/` 結尾**。將單一路由放入前綴清單，也會一併公開所有開頭字元相同的相鄰路徑——包括日後新增的動態區段同層路由（GHSA-74g9-q8f6-793h）。請更新 `tests/unit/public-api-routes.test.ts`、`tests/unit/authz/public-route-exact-match.test.ts` 和 `tests/unit/authz/classify.test.ts` 中的單元測試。

## 範圍

三個命名空間。每個檢查器只讀取其自身的字串。關於為什麼 `manage` 會使 `read:compression` 的 `scopeMatches` 失敗，以及為什麼 `read` 存取權杖無法 `PATCH /api/keys/{id}` 的並排說明，請參閱[三個範圍命名空間](../frameworks/MCP-SERVER.md#three-scope-namespaces)。

API 金鑰帶有一個 `scopes` 陣列（以 JSON 格式儲存在 `api_keys.scopes` 中，請參閱 `src/lib/db/apiKeys.ts`）。

### 管理範圍

- `manage` / `admin` — `hasManageScope`。對管理 API 路由的 Bearer 存取。
- `mcp:connect`、`self:usage`、`self:account-quota` 和
  `policy:bypass-provider-quota` 是附加的精確匹配範圍。它們位於
  `MANAGEMENT_API_KEY_SCOPES` 之外。`mcp:connect` 僅開啟
  `/api/mcp/` 非迴路（non-loopback）的劃分。

### MCP 工具範圍

目錄和匹配規則（相同字串，或以 `*` 結尾的已授予範圍）：
[MCP 工具範圍](../frameworks/MCP-SERVER.md#mcp-tool-scopes)。
`src/shared/constants/mcpScopes.ts` 中的 `MCP_SCOPE_LIST` 是原始的類型化
子集，而非完整的目錄。在 `resolveCallerScopeContext()` 從 MCP 驗證資訊、請求中繼資料或 `OMNIROUTE_MCP_SCOPES` 解析範圍後，執行會在
`open-sse/mcp-server/scopeEnforcement.ts` 中進行。除非 `OMNIROUTE_MCP_ENFORCE_SCOPES=true`，否則它會保持關閉。

### 存取權杖範圍

`oma_live_…` 權杖上的 `read` / `write` / `admin`，按 `scopeSatisfies` 排序
（`src/lib/accessTokens/scopes.ts`）。此排序僅適用於存取權杖憑證。請參閱
[管理驗證](../guides/MANAGEMENT-AUTH.md)。

## 認證需求開關

`src/shared/utils/apiAuth.ts` 中的 `isAuthRequired()` 決定某個請求是否需要**任何**認證：

- `settings.requireLogin === false` → 全域停用認證，但以下情況除外：始終受保護的層級（參見 [路由守衛層級](../security/ROUTE_GUARD_TIERS.md)），以及核發其所接受憑證的呼叫。這些呼叫需要與開啟登入時相同的憑證：核發同步權杖、以任何範圍核發 CLI 存取權杖、建立具有 `manage`/`admin` 範圍的 API 金鑰、把該範圍授予某個金鑰，或重新產生、顯示此類金鑰（`src/lib/api/requireManagementAuth.ts` 中的 `requireCredentialForManagementScopedKey()`）。僅用於推論的金鑰仍保持開放。
- 未設定密碼**且**未設定 `INITIAL_PASSWORD` 環境變數 → 引導模式允許使用新手引導精靈與回送（loopback）請求，但暴露在網路上的請求仍需要憑證。
- 任何資料庫錯誤 → 失敗時預設拒絕（fail closed，即預設安全）。

用戶端 API 金鑰的強制執行使用 `src/shared/utils/featureFlags.ts` 中的 `isRequireApiKeyEnabled()`，而非直接讀取 `process.env.REQUIRE_API_KEY`。這對已部署的執行個體很重要：在儀表板 → 功能旗標中切換 `REQUIRE_API_KEY` 會儲存一個資料庫覆寫值，並立即影響 `/v1/*`、`/v1beta/*`、`/models`、`/responses`、`/chat/completions`、`/codex/*` 以及其他共用此輔助函式的用戶端 API 認證檢查。若無法讀取功能旗標儲存區，用戶端 API 認證會失敗時預設拒絕，並要求提供金鑰。

## 破壞性變更 — v3.8.0

`/api/v1/agents/tasks/*` 與 `/api/resilience/model-cooldowns` 端點**現在需要管理驗證**（提交 `588a0333`）。先前傳送不含 `manage` 範圍之一般 API 金鑰的用戶端會收到 `403`。遷移方式：在 API Keys 儀表板中將 `manage` 範圍授予該金鑰，或使用已登入的儀表板工作階段。

## 行為變更 — v3.8.2

`/api/mcp/*`（遠端 MCP 伺服器）預設仍為 LOCAL_ONLY，但現在當 `Authorization: Bearer <api-key>` 標頭所帶的金鑰具有 `manage` 範圍時，會接受非迴路位址請求。此例外會透過 `src/server/authz/routeGuard.ts` 中的 `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES`，明確地依各路徑加以控管；同屬 LOCAL_ONLY 的前綴 `/api/cli-tools/runtime/*` 刻意不允許略過此限制，因為它可以產生任意子行程。來自非迴路位址、對 `/api/mcp/*` 發出的匿名請求仍會傳回 `403 LOCAL_ONLY`——任何新的 LOCAL_ONLY 路徑預設仍會嚴格限制為僅允許迴路位址。請參閱[路由防護層級](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)。

## 測試

- 單元測試：`tests/unit/authz/` — `classify.test.ts`、`pipeline.test.ts`、`client-api-policy.test.ts`、`management-policy.test.ts`、`public-policy.test.ts`。
- 公開允許清單：`tests/unit/public-api-routes.test.ts`。
- 執行特定測試：`node --import tsx/esm --test tests/unit/authz/classify.test.ts`。

## 偵錯

管道始終使用以下標記標記回應：

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

對於經過身份驗證的請求，上游（處理程序端）請求標頭還包括：

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

在處理程序—中使用`assertAuth(req, expectedClass)`如果中間件被繞過，它會拋出帶有代碼`AUTHZ_NOT_INITIALIZED`的`AuthzAssertionError` （有助於在測試中捕獲配置回歸）。

## 參閱

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — 每個端點的身份驗證標記
- [COMPLIANCE.md](../security/COMPLIANCE.md) — 身份驗證事件的稽核日誌
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — 三個範圍命名空間和 MCP 工具範圍目錄
- 來源：`src/server/authz/`、`src/lib/api/requireManagementAuth.ts`
