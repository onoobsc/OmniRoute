# Authorization Guide (日本語)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **信頼できる情報源:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **最終更新日:** 2026-09-22 — スコープの名前空間はMCP-SERVER.mdを参照

OmniRouteには、すべてのAPIリクエストをゲートするルート認識型認可パイプラインがあります。分類は**決定論的**であり、**フェイルクローズ**です。分類できないものはすべて`MANAGEMENT`として扱われ、セッションまたは管理グレードのトークンを要求します。このページでは、ルートを保守するエンジニアや新しいエンドポイントを設計するエンジニア向けにモデルを説明します。

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> ソース: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## 2 つの認証モード

### 1. APIキー (ベアラー)

キーが`manage`スコープを持つ場合、 OpenAI/Anthropic/Gemini-compatibleクライアントAPIsおよびいくつかの管理ルートに使用されます。

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts`の`isValidApiKey()` / `extractApiKey()`によって検証され、 `src/shared/utils/apiAuth.ts`を通じて再エクスポートされます。バリデーターは、 `OMNIROUTE_API_KEY` / `ROUTER_API_KEY`環境変数を永続的なパススルー キーとして受け入れます ( #1350を発行します)。

### 2. ダッシュボード セッション (auth_token cookie)

ダッシュボード ページと管理操作用。

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Cookie は、 JWT検証した場合にのみセッションになります。**そして**`authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) を運びます。 Cookie のすべてのコンシューマー (ダッシュボード ルート ガード (`isDashboardSessionAuthenticated()`)、authz パイプライン更新、 WebSocketハンドシェイク、ライブ サーバー、 `/api/settings/require-login`、 `/api/auth/status`) はそのヘルパーを通過します。 `JWT_SECRET`で署名された他のJWTs — Cursor CLIパススルー、キーホルダー—の`iss "omniroute" / aud "cursor-cli"`トークンを作成し、セッション (#13298) ではありません。

`src/shared/utils/apiAuth.ts`の`isDashboardSessionAuthenticated()`によって検証されました。パイプラインは、30 日間の有効期間のうち残り 7 日未満になると、 JWTを自動更新します。

セッションは 30 日が経過する前に終了することもあります。これは、すべての minter が`mintDashboardSessionToken` (発行時刻`iat`と ID `jti`) を通過し、検証者が 2 つの設定をチェックするためです。 `sessionsValidAfter`パスワード変更によって設定され、検証を停止する前に発行されるすべてのセッション (パスワードを変更したブラウザーは新しい Cookie を取得します) と、 `POST /api/auth/logout`サインアウトしたセッションの`jti`を追加する`revokedDashboardSessions`です。古いリリースによって作成されたセッションには要求はなく、最初のパスワードが変更されるまで有効です。設定を読み取れない場合、セッションは信頼されていません。

一部の管理ルートは受け入れます**どちらか**モード: cookie OR `Bearer <key>` APIキーが`manage` (または`admin`) スコープを持つ場合)。これにより、v3.8 で追加された「 API呼び出し経由で設定可能」ワークフローが有効になります。

#### オプションのOIDCログイン ゲート (#6973)

ダッシュボード管理者ログインでは、**オプトイン**OIDC (OpenID Connect) フローはデフォルトのパスワード ログインとともに実行されます—パスワード ログインは削除されることはなく、追加されるだけです。

- `settings.oidcEnabled === true`でない限り無効**そして**`oidcIssuer` / `oidcClientId` / `oidcClientSecret`はすべて設定されています (設定→認証)。それ以外の場合、 `GET /api/auth/oidc/login` `400`返します。
- `GET /api/auth/oidc/login` 、発行者の`/.well-known/openid-configuration`から`authorization_endpoint`検出し ( `<issuer>/authorize`にフォールバック)、受信リクエスト (`x-forwarded-proto` -aware) からリダイレクトURIを構築し、 `httpOnly` `oidc_state` Cookie に格納されたランダムな`state`を使用してIdPにリダイレクトします。
- `GET /api/auth/oidc/callback` `state`を検証し、認可コードを交換し、発行者のJWKS (`jose`の`createRemoteJWKSet`、 JWKS URIごとにキャッシュ) を介して`issuer`/`audience`チェックでIDトークンの署名を検証します。ダッシュボードの許可には、空ではない`oidcAllowedSubjects`リスト、 `oidcAdmissionClaim`ポリシー、またはその両方が必要です。件名リストは、 `email_verified === true`の場合にのみ`sub`または`email`と一致します。オプションのクレーム ポリシーは、ドットで区切られた ID トークン クレーム パス (たとえば、 `realm_access.roles`) と受け入れられる値の配列を受け取ります。解決されたクレームは、少なくとも 1 つの受け入れられた値を含む文字列の配列である必要があります。両方のポリシーが設定されている場合は、両方が合格する必要があります。 Missing/malformedクレームはフェールクローズされ、どちらのポリシーもないとコールバックはログインを拒否します (`not_configured`)。既存のサブジェクトのみの構成は変更されずに継続されます。
- Keycloakは通常、レルムの役割をアクセス・トークンにマップしますが、必ずしもIDトークンである必要はありません。レルム ロール`admin`を要求するには、そのクライアントに`realm_access.roles`を含むプロトコル マッパーを構成します。**IDトークン**次に、 `oidcAdmissionClaim`を`{ "path": "realm_access.roles", "values": ["admin"] }`に設定します。ロールのみのアドミッションを有効にする前に、このクライアントの実際の ID トークン要求を確認してください。アプリケーションはアクセス トークンのロールを読み取りません。 IdP 側のトークン拒否は、このアプリケーション側のチェックを補足するものではありますが、これに代わるものではありません。
- 成功すると、**全く同じ**30 日間`auth_token` JWTパスワード ログインが発行される (`src/app/api/auth/login/route.ts`)。そのため、ダッシュボード セッション パイプラインの残りの部分 (自動更新、Cookie フラグ) は変更されません。 — OIDC 、Cookie の付与内容ではなく、Cookie の作成方法のみを置き換えます。 IdP roles/groupsを変更しても、既存のOmniRouteセッションは無効になりません。ログアウト、パスワードのローテーション、またはセッションの有効期限が依然として有効期間を決定します。
- すべての`oidc*`設定 (`oidcEnabled`、 `oidcDisablePasswordLogin`、 `oidcIssuer`、 `oidcClientId`、 `oidcClientSecret`、 `oidcAllowedSubjects`、 `oidcAdmissionClaim`、 `oidcRedirectPath`、 `oidcScopes`) は`SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) にあります。本体に管理パスワードが`currentPassword` (間違っている場合は`401 PASSWORD_MISMATCH` ) として含まれていない限り、 `PATCH /api/settings` `400 PASSWORD_REQUIRED`と応答します。 `oidcDisablePasswordLogin`パスワード _login_ (`POST /api/auth/login`) を拒否しますが、保存されたパスワード ハッシュは保持し、再認証では引き続き`currentPassword`それと照合します。
- `corsOrigins`と`bruteForceProtection`も`SECURITY_IMPACTING_SETTINGS_KEYS`内にあります。どちらかを緩めるとログイン防御が弱くなるため、同じ`currentPassword`再認証が行われ ([セキュリティ] タブで要求されます)、 JSONインポートによってそれらが削除されます。
- すべてのセキュリティ ポリシー キー— `SECURITY_IMPACTING_SETTINGS_KEYS`エントリ、すべての`oidc*`キー、およびダッシュボード セッション状態—は次のとおりです。**オペレータのみ**`PATCH /api/settings`の場合: 管理スコープのAPIキーまたは`oma_`アクセス トークンは、正しい`currentPassword`を送信した場合でも`403`で拒否され、拒否は`reason: OPERATOR_REQUIRED` ( `src/lib/api/operatorCredential.ts`の`requireOperatorCredential()` ) で`settings.update_failed`として監査されます。通常の設定 (テーマ、表示設定) は、 `manage`キーまたは`admin`アクセス トークンに対して書き込み可能なままです。 `/api/settings`自体 (および`/api/settings/require-login`) のすべての変更には、 `admin`アクセス トークン スコープ ( `src/server/authz/accessScopes.ts`内の`ADMIN_MUTATION_EXACT_PATHS` 、正確なパス一致) も必要です。 `GET` `read`ままで、他の`/api/settings/*`サブルート (プロキシ、コンボデフォルト、モデルエイリアス、圧縮、パージなど) はメソッド推論された`write`スコープを保持します。
- `POST /api/settings/import-json`その再認証をスキップするため、パスワードと`currentPassword`、すべての`SECURITY_IMPACTING_SETTINGS_KEYS`エントリ、およびダッシュボード セッション状態 (`sessionsValidAfter`、 `revokedDashboardSessions`) を書き込む前に`IMPORT_STRIPPED_SETTINGS_KEYS` (同じファイル) 内のすべてのキーを削除します。したがって、古いバックアップをインポートしても、パスワードの変更またはサインアウトがすでに終了したセッションを復活させることはできません。

#### オプションのTOTP 2 要素ログイン (#16619)

設定→セキュリティから登録。オペレータがオンにするまでオフになります (`src/server/auth/dashboardMfa.ts`)。

- **対象となる内容:**パスワード ログイン (`POST /api/auth/login`、その後`POST /api/auth/mfa/verify`が必要) と`omniroute connect` (`POST /api/cli/connect`、パスワードのみの交換を拒否し、コードを`totp`として受け取ります)。
- **対象外となるもの:** OIDC / SSOサインイン (`/api/auth/oidc/callback`) は、 OmniRoute TOTPを要求しません。これはアイデンティティ プロバイダー自身の 2 番目の要素に依存するため、 OIDCが有効な場合はIdPでMFA強制します。
- **回復**(デバイスの紛失、リカバリコードが残っていない、または検証できなくなった要因、たとえば`STORAGE_ENCRYPTION_KEY`変更された後):
  1. `OMNIROUTE_DISABLE_MFA=true`を使用してサーバーを再起動します。
  2. ホスト自体 (ループバック ピアおよびループバック`Host`、 `http://localhost:20128`など) で、パスワードを使用してサインインします。 2 番目の要素は、その原点に対してのみスキップされます。他のすべてのオリジンには依然としてコードが必要です。
  3. [設定→セキュリティ→無効化] で、パスワードを入力し、コードを空白のままにします。 `POST /api/auth/mfa/disable` 、変数が設定されており、リクエストがホストから来ている間のみ、 `code`なしで本文を受け入れます。引き続きダッシュボード セッションと現在のパスワードが必要で、 `secondFactor: "recovery_switch"`を使用した`auth.mfa.disabled`として監査されます。
  4. `OMNIROUTE_DISABLE_MFA`設定を解除し、再起動し、必要に応じて再度登録します。

## ルートのクラス

`src/server/authz/types.ts` は 3 つのクラスを定義します。決定的に分類できないルートはすべて `MANAGEMENT` にフォールバックします。

| Class        | Description                                                                                                                                                  | Auth required                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| `PUBLIC`     | 明示的に安全なルート — ログイン、ログアウト、ステータス、初期化、ヘルスチェック、オンボーディングのブートストラップ。                                        | なし                                                                  |
| `CLIENT_API` | モデル提供エンドポイント — `/api/v1/*`、`/api/v1beta/*`、およびエイリアスの `/v1/*`、`/v1beta/*`、`/chat/completions`、`/responses`、`/models`、`/codex/*`。 | 有効な `REQUIRE_API_KEY` フィーチャーフラグが有効な場合は Bearer キー |
| `MANAGEMENT` | ダッシュボードのページ、設定、プロバイダー、キー、管理者および診断エンドポイント。                                                                           | ダッシュボードセッション、または `manage` スコープの Bearer           |

一部の `MANAGEMENT` 操作は **オペレーター専用** です。`manage` キーだけでは不十分です。保存済みの認証情報のエクスポート（`GET /api/settings/export-json`、`GET /api/db-backups/export`、`GET /api/db-backups/exportAll`）、ライブデータへのバックアップの復元（`dryRun=true` を含む `POST /api/db-backups/import`、ID による `POST /api/db-backups` の復元、`POST /api/settings/import-json`）、復元ポイントの破棄（`DELETE /api/db-backups` のクリーンアップ、および `PATCH /api/db-backups`。このエンドポイントで永続化される保持期間設定は、バックアップのたびに実行される自動削除を制御するためです）には、ダッシュボードセッション、ローカル CLI のサブジェクト、またはログインが無効であることが必要です。同期トークンの発行（`POST /api/sync/tokens`）と `admin` の CLI アクセストークンの発行（`POST /api/cli/tokens`）には、すべてのログインモードでダッシュボードセッションまたはローカル CLI のサブジェクトが必要です。どのスコープの API キーも、`oma_` アクセストークンも、オペレーターの認証情報ではありません。これらが必要とされる場合は、常に `403` が返されます。このチェックは `src/lib/api/operatorCredential.ts`（`resolveOperatorCredential()` / `requireOperatorCredential()`）にあります。ログイン設定の変更もオペレーター専用です。`POST /api/settings/require-login`（管理パスワードの設定、`requireLogin` の切り替え）は、パスワードが存在すると、これらの認証情報のみを受け付けます。最初の実行時のブートストラップ期間（パスワードがまだない状態）は変更されません。ダッシュボードセッションでパスワードを置き換えるには `currentPassword` の送信が必要です（欠落または誤りの場合は `403` で、`settings.update_failed` として監査ログに記録されます）。ローカル CLI とログインが無効なインスタンスは復旧パスを維持し、このパラメーターなしでパスワードを設定できます。どちらもデータディレクトリを所有するホストに紐づけられているためです。

## パイプライン

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

信頼できる内部ヘッダー ( `src/server/authz/headers.ts`で定義) は次のとおりです。**受信リクエストから削除される**分類の前に、 —クライアントは、サブジェクトになりすますために`x-omniroute-auth-*`事前に設定することはできません。

### 保険契約

各ルート クラスには`src/server/authz/policies/`にポリシーがあります。

- **`publicPolicy`** (`policies/public.ts`) —常に`allow({ kind: "anonymous", id: "anonymous" })`を返します。
- **`clientApiPolicy`** (`policies/clientApi.ts`) — Bearer を抽出し、 `validateApiKey()`経由で検証します。有効な`REQUIRE_API_KEY`機能フラグが無効になっている場合にのみ、匿名に移行します。有効なフラグは`isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) によって解決されるため、ダッシュボード機能フラグと環境変数によって`/api/v1/*`、 `/api/v1beta/*`、およびエイリアスが一貫して制御されます。リゾルバ障害がフェールクローズされる。クライアントAPIルート (ダッシュボード モデル カタログで使用される`/api/v1/models`を含む) でのダッシュボード セッション リクエストを許可します。 Entra ID SSOが有効な場合、構造的に Entra トークンであるベアラー (3 つの Base64url セグメント、 `RS*` alg、 `kid`) はSSOブランチによって処理されます。**前に**`validateApiKey()`とその判定は最終的な—であり、API キー パスや匿名ブランチへの劣化は決して通過しないため、アイデンティティ プロバイダーの停止がオープン アクセスになることはありません。静的APIキーは影響を受けません。 [「エントラID SSOを](../security/ENTRA_SSO.md)参照してください。
- **`managementPolicy`** (`policies/management.ts`) — 、ダッシュボード セッション、内部モデル同期リクエスト ( `/api/providers/[name]/(sync-models|models)`と照合) を受け入れるか、 `isAuthRequired()` false を返した場合は完全にスキップします。 Bearer トークンが存在するが無効な場合は 403 (`AUTH_001`) を返し、それ以外の場合は 401 を返します。また、認証ブランチ—の前にルート ガード層 (LOCAL_ONLY / ALWAYS_PROTECTED) を適用します。 [「ルート ガード層」](../security/ROUTE_GUARD_TIERS.md)を参照してください。 `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (現在: `/api/mcp/`) のLOCAL_ONLYパスは、Bearer キーが`manage`スコープを保持している場合、非ループバックからアクセスできます。他のすべてのLOCAL_ONLYパスは、スコープに関係なく厳密なループバックのままです。

ポリシーが成功すると、 `AuthSubject`と`kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`が返されます。ダウンストリーム ハンドラーは、認証ロジックを再実行する代わりに、 `src/server/authz/assertAuth.ts`の`assertAuth(request, "CLIENT_API")`を介してそれを読み取ることができます。

## パブリックルートリスト

`src/shared/constants/publicApiRoutes.ts`は明示的な許可リストです。

リストは次のように分割されます**形**、分割は負荷に耐えます (GHSA-74g9-q8f6-793h)。プレフィックスは`startsWith()`と一致するため、先頭文字を共有するすべての隣接パスとも一致します。 `/api/usage/om-usage` `/api/usage/om-usage<anything>` PUBLICとマークされたプレフィックスとして使用され、 Next はそれを`/api/usage/[connectionId]` —という独自の認証を持たないハンドラーに解決します。

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

読み取り専用ルートはパブリックです**のみ**安全な方法のために。注: `classifyRoute()` 、 PUBLICフォールスルー—から`/api/v1/*`と`/api/v1beta/*`を除外します。これらは常に`CLIENT_API`あるため、Bearer-key ポリシーが引き続き適用されます。

## 新しいルートの追加

### パターン 1 — 公開クライアント API エンドポイント（Bearer 認証）

`/api/v1/` および `/api/v1beta/` 配下のルートは、自動的に `CLIENT_API` として分類されます。ミドルウェアが Bearer チェックを強制するため、ルートハンドラーで再度実行する必要はありませんが、必要に応じてサブジェクトを読み取ることができます。

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... ハンドラーのロジック
}
```

### パターン 2 — 管理エンドポイント（セッション、または Bearer + manage）

`src/lib/api/requireManagementAuth.ts` の `requireManagementAuth()` を使用します。

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... ハンドラーのロジック
}
```

`requireManagementAuth()` は、成功時には `null`、エラー時には JSON エラーの `Response` を返します。

- 401 `AUTH_001`「認証が必要です」— 認証情報がまったくない
- 403 — Bearer が無効、**または** Bearer は存在するものの、キーに `manage` / `admin` スコープがない

`hasManageScope(scopes)` は、`"manage"` または `"admin"` の場合に true を返します。

### パターン 3 — 公開許可リストへの追加

利便性ではなく、形状に基づいて追加先のセットを選択してください。単一ルートは `PUBLIC_API_ROUTES_EXACT`（GET 専用の場合は `PUBLIC_READONLY_CORS_API_ROUTES`）に追加します。真のサブツリーのみを `PUBLIC_API_ROUTE_PREFIXES` に追加でき、エントリは**必ず `/` で終わる必要があります**。単一ルートをプレフィックスリストに追加すると、先頭文字列が共通するすべての隣接パスも公開されます。これには、後から追加される動的セグメントの兄弟ルートも含まれます（GHSA-74g9-q8f6-793h）。`tests/unit/public-api-routes.test.ts`、`tests/unit/authz/public-route-exact-match.test.ts`、`tests/unit/authz/classify.test.ts` の単体テストも更新してください。

## スコープ

3つの名前空間があります。各チェッカーは自身の文字列のみを読み取ります。`manage`が`read:compression`に対して`scopeMatches`で失敗する理由や、`read`アクセストークンが`PATCH /api/keys/{id}`を実行できない理由を含む、並列の比較については、[3つのスコープ名前空間](../frameworks/MCP-SERVER.md#three-scope-namespaces)を参照してください。

APIキーには`scopes`配列が含まれています（`api_keys.scopes`にJSONとして保存されます。`src/lib/db/apiKeys.ts`を参照）。

### 管理スコープ

- `manage` / `admin` — `hasManageScope`。管理APIルートへのベアラーアクセス。
- `mcp:connect`、`self:usage`、`self:account-quota`、および`policy:bypass-provider-quota`は、追加的な完全一致スコープです。これらは`MANAGEMENT_API_KEY_SCOPES`の範囲外にあります。`mcp:connect`は、`/api/mcp/`の非ループバックの切り出しのみを開放します。

### MCPツールスコープ

カタログとマッチングルール（同一文字列、または`*`で終わる付与されたスコープ）：[MCPツールスコープ](../frameworks/MCP-SERVER.md#mcp-tool-scopes)。`src/shared/constants/mcpScopes.ts`にある`MCP_SCOPE_LIST`は、完全なカタログではなく、元の型付きサブセットです。`resolveCallerScopeContext()`がMCP認証情報、リクエストメタデータ、または`OMNIROUTE_MCP_SCOPES`からスコープを解決した後、`open-sse/mcp-server/scopeEnforcement.ts`で強制が実行されます。`OMNIROUTE_MCP_ENFORCE_SCOPES=true`でない限り、これは無効のままです。

### アクセストークンスコープ

`oma_live_…`トークンに対する`read` / `write` / `admin`は、`scopeSatisfies`（`src/lib/accessTokens/scopes.ts`）によってランク付けされます。このランクはアクセストークン資格情報にのみ適用されます。[管理認証](../guides/MANAGEMENT-AUTH.md)を参照してください。

## 認証必須トグル

`src/shared/utils/apiAuth.ts` の `isAuthRequired()` は、リクエストに対して **いかなる** 認証を適用するかを決定します：

- `settings.requireLogin === false` → 認証はグローバルに無効になります。ただし、常に保護される階層（[Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md) を参照）と、認証情報を発行する操作は例外です。これらの操作では、ログインが有効な場合と同じ認証情報が必要です。具体的には、同期トークンの発行、任意のスコープでの CLI アクセストークンの発行、`manage`/`admin` スコープを持つ API キーの作成、そのスコープのキーへの付与、そのようなキーの再生成または表示（`src/lib/api/requireManagementAuth.ts` の `requireCredentialForManagementScopedKey()`）です。推論専用のキーは引き続きオープンです。
- パスワードが設定されておらず **かつ** `INITIAL_PASSWORD` 環境変数もない → ブートストラップモードでは、オンボーディングウィザードとループバックからのリクエストを許可しますが、外部ネットワークからのリクエストには引き続き認証情報が必要です。
- DB エラーが発生した場合 → フェイルクローズ（セキュアバイデフォルト）。

クライアント API キーの強制には、`process.env.REQUIRE_API_KEY` を直接読み取るのではなく、`src/shared/utils/featureFlags.ts` の `isRequireApiKeyEnabled()` を使用します。これは本番環境のインスタンスで重要です。ダッシュボード → Feature Flags で `REQUIRE_API_KEY` を切り替えると DB オーバーライドが保存され、即座に `/v1/*`、`/v1beta/*`、`/models`、`/responses`、`/chat/completions`、`/codex/*` および、このヘルパーを共有する他のクライアント API 認証チェックに影響します。フィーチャーフラグストアを読み取れない場合、クライアント API 認証はフェイルクローズし、キーを要求します。

## 破壊的変更 — v3.8.0

`/api/v1/agents/tasks/*` および `/api/resilience/model-cooldowns` エンドポイントは、**管理認証が必須**になりました（コミット `588a0333`）。以前のように `manage` スコープを持たない通常の API キーを送信するクライアントには、`403` が返されます。移行方法：API Keys ダッシュボードでキーに `manage` スコープを付与するか、ログイン済みのダッシュボードセッションを使用してください。

## 動作変更 — v3.8.2

`/api/mcp/*`（リモート MCP サーバー）は引き続きデフォルトで LOCAL_ONLY ですが、`Authorization: Bearer <api-key>` ヘッダーに `manage` スコープが含まれている場合、ループバック以外からのリクエストも受け付けるようになりました。この例外は、`src/server/authz/routeGuard.ts` の `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` を介してパスごとに明示的に制御されます。同じく LOCAL_ONLY プレフィックスである `/api/cli-tools/runtime/*` は、任意のサブプロセスを起動できるため、意図的にバイパスできないようになっています。ループバック以外から `/api/mcp/*` に送信された匿名リクエストには、引き続き `403 LOCAL_ONLY` が返されます。新しい LOCAL_ONLY パスのデフォルトは、今後も厳格なループバック限定です。[ルートガードの階層](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)を参照してください。

## テスト

- ユニットテスト：`tests/unit/authz/` — `classify.test.ts`、`pipeline.test.ts`、`client-api-policy.test.ts`、`management-policy.test.ts`、`public-policy.test.ts`。
- パブリック許可リスト：`tests/unit/public-api-routes.test.ts`。
- 対象を絞って実行：`node --import tsx/esm --test tests/unit/authz/classify.test.ts`。

## デバッグ

パイプラインは常に応答に次のスタンプを付けます。

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

認証されたリクエストの場合、上流 (ハンドラー側) リクエスト ヘッダーには次のものも含まれます。

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ハンドラー—内で`assertAuth(req, expectedClass)`使用します。ミドルウェアがバイパスされた場合、コード`AUTHZ_NOT_INITIALIZED`で`AuthzAssertionError`をスローします (テストで構成のリグレッションを検出するのに役立ちます)。

## 関連項目

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — エンドポイントごとの認証マーカー
- [COMPLIANCE.md](../security/COMPLIANCE.md) — 認証イベントの監査ログ
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — 3つのスコープ名前空間とMCPツールスコープカタログ
- ソース: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
