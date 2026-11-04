# Authorization Guide (한국어)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **신뢰할 수 있는 출처:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **최종 업데이트:** 2026-09-22 — 스코프 네임스페이스는 MCP-SERVER.md를 가리킵니다.

OmniRoute는 모든 API 요청을 제어하는 경로 인식 권한 부여 파이프라인을 가지고 있습니다. 분류는 **결정론적**이며 **실패 시 닫힘(fail-closed)**입니다. 분류할 수 없는 모든 것은 `MANAGEMENT`로 처리되어 세션 또는 관리 등급 토큰을 요구합니다. 이 페이지는 경로를 유지 관리하거나 새로운 엔드포인트를 설계하는 엔지니어를 위한 모델을 설명합니다.

![AuthZ 파이프라인 (3가지 경로 클래스 + 정책 평가)](../diagrams/exported/authz-pipeline.svg)

> 출처: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## 두 가지 인증 모드

### 1. API 키(전달자)

키에 `manage` 범위가 있는 경우 OpenAI/Anthropic/Gemini-compatible 클라이언트 APIs 및 몇 가지 관리 경로에 사용됩니다.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` 에서 `isValidApiKey()` / `extractApiKey()` 에 의해 검증되고 `src/shared/utils/apiAuth.ts` 통해 다시 내보냅니다. 유효성 검사기는 또한 `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env 변수를 영구 통과 키로 허용합니다( #1350 발행).

### 2. 대시보드 세션(auth_token 쿠키)

대시보드 페이지 및 관리 작업용.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

쿠키는 JWT 확인할 때만 세션입니다.** 그리고** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`)를 운반합니다. 쿠키의 모든 소비자(대시보드 경로 가드(`isDashboardSessionAuthenticated()`), 인증 파이프라인 새로 고침, WebSocket 핸드셰이크, 라이브 서버, `/api/settings/require-login`, `/api/auth/status`)는 해당 도우미를 통과합니다. `JWT_SECRET` 로 서명된 다른 JWTs zql에 존재합니다 — Cursor CLI 패스스루는 키 보유자 — 에 대한 `iss "omniroute" / aud "cursor-cli"` 토큰을 발행하며 절대 세션(#13298)이 아닙니다.

`src/shared/utils/apiAuth.ts` 의 `isDashboardSessionAuthenticated()` 에 의해 확인되었습니다. 파이프라인은 30일 수명 중 남은 시간이 7일 미만인 경우 JWT 를 자동으로 새로 고칩니다.

모든 minter가 `mintDashboardSessionToken` (발행 시간 `iat` 및 ID `jti`)를 통과하고 검증자가 두 가지 설정을 확인하기 때문에 세션은 30일이 끝나기 전에 종료될 수도 있습니다. `sessionsValidAfter` 비밀번호 변경으로 설정되어 확인을 중지하기 전에 발행된 모든 세션(비밀번호를 변경한 브라우저는 새로운 쿠키를 얻음)과 `POST /api/auth/logout` 로그아웃된 세션의 `jti` 추가하는 `revokedDashboardSessions` 입니다. 이전 릴리스에서 생성된 세션은 소유권을 주장하지 않으며 첫 번째 비밀번호가 변경될 때까지 유효한 상태로 유지됩니다. 설정을 읽을 수 없으면 세션을 신뢰할 수 없는 것입니다.

일부 관리 경로는 허용됩니다.** 어느 하나** 모드: API 키에 `manage` (또는 `admin`) 범위가 있는 경우 쿠키 OR `Bearer <key>`. 이것이 v3.8에 추가된 " API 호출을 통해 구성 가능" 워크플로를 활성화하는 것입니다.

#### 선택적 OIDC 로그인 게이트(#6973)

대시보드 관리자 로그인은 다음도 지원합니다.** 선택** 기본 비밀번호 로그인과 함께 OIDC (OpenID Connect) 흐름 — 비밀번호 로그인은 제거되지 않으며 보완만 됩니다.

- `settings.oidcEnabled === true` 아니면 비활성화됨** 그리고** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` 모두 구성되어 있습니다 ( → Auth 설정). 그렇지 않으면 `GET /api/auth/oidc/login` `400` 반환합니다.
- `GET /api/auth/oidc/login` 발급자의 `/.well-known/openid-configuration` 에서 `authorization_endpoint` 발견하고( `<issuer>/authorize` 로 폴백), 들어오는 요청(`x-forwarded-proto` -aware)에서 리디렉션 URI 구축하고, `httpOnly` `oidc_state` 쿠키에 저장된 임의의 `state` 사용하여 IdP 로 리디렉션합니다.
- `GET /api/auth/oidc/callback` `state` 검증하고 인증 코드를 교환하며 `issuer`/`audience` 검사를 통해 발급자의 JWKS (`jose` 의 `createRemoteJWKSet`, JWKS URI 별로 캐시됨)를 통해 ID 토큰의 서명을 확인합니다. 대시보드 승인에는 비어 있지 않은 `oidcAllowedSubjects` 목록, `oidcAdmissionClaim` 정책 또는 둘 다가 필요합니다. 주제 목록은 `email_verified === true` 경우에만 `sub` 또는 `email` 과 일치합니다. 선택적 클레임 정책은 점으로 구분된 ID 토큰 클레임 경로(예: `realm_access.roles`)와 허용되는 값 배열을 사용합니다. 해결된 클레임은 하나 이상의 허용된 값을 포함하는 문자열 배열이어야 합니다. 두 정책이 모두 구성된 경우 두 정책 모두 통과해야 합니다. Missing/malformed 클레임은 실패 시 종료되며 두 정책 중 하나도 없으면 콜백이 로그인을 거부합니다(`not_configured`). 기존의 주제 전용 구성은 변경되지 않고 계속됩니다.
- Keycloak은 일반적으로 영역 역할을 반드시 ID 토큰이 아닌 액세스 토큰에 매핑합니다. 영역 역할 `admin` 요구하려면 해당 클라이언트에 `realm_access.roles` 포함하는 프로토콜 매퍼를 구성하십시오.**ID 토큰** 을 선택한 다음 `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` 로 설정합니다. 역할 전용 승인을 활성화하기 전에 이 클라이언트에 대한 실제 ID 토큰 청구를 확인하세요. 애플리케이션은 액세스 토큰 역할을 읽지 않습니다. IdP 측 토큰 거부는 보완할 수 있지만 이 애플리케이션 측 확인을 대체하지는 않습니다.
- 성공하면 민트를 발행합니다.** 똑같다** 30일 `auth_token` JWT 비밀번호 로그인 문제(`src/app/api/auth/login/route.ts`)가 있으므로 나머지 대시보드 세션 파이프라인(자동 새로 고침, 쿠키 플래그)은 변경되지 않습니다. — OIDC 는 쿠키가 부여되는 것이 아니라 쿠키가 생성되는 방식만 대체합니다. IdP roles/groups 에 대한 변경 사항은 기존 OmniRoute 세션을 무효화하지 않습니다. 로그아웃, 비밀번호 교체 또는 세션 만료는 여전히 수명을 좌우합니다.
- 모든 `oidc*` 설정(`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`)은 `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`)에 있습니다. 본문이 관리 비밀번호를 `currentPassword` (잘못된 경우 `401 PASSWORD_MISMATCH` )로 전달하지 않는 한 `PATCH /api/settings` `400 PASSWORD_REQUIRED` 응답합니다. `oidcDisablePasswordLogin` 비밀번호 _login_ (`POST /api/auth/login`)을 거부하지만 저장된 비밀번호 해시를 유지하고 재인증은 계속해서 이에 대해 `currentPassword` 확인합니다.
- `corsOrigins` 및 `bruteForceProtection` 도 `SECURITY_IMPACTING_SETTINGS_KEYS` 에 있습니다. 둘 중 하나를 느슨하게 하면 로그인 방어가 약화되므로 동일한 `currentPassword` 재인증(보안 탭에서 요청)을 수행하고 JSON 가져오기가 이를 삭제합니다.
- 모든 보안 정책 키 — `SECURITY_IMPACTING_SETTINGS_KEYS` 항목, 모든 `oidc*` 키 및 대시보드 세션 상태 — 는** 운영자 전용** `PATCH /api/settings` 에서: 관리 범위의 API 키 또는 `oma_` 액세스 토큰은 올바른 `currentPassword` 보내는 경우에도 `403` 로 거부되며, 거부는 `reason: OPERATOR_REQUIRED` ( `src/lib/api/operatorCredential.ts` 의 `requireOperatorCredential()` )로 `settings.update_failed` 로 감사됩니다. 일반 설정(테마, 디스플레이 기본 설정)은 `manage` 키 또는 `admin` 액세스 토큰에 대해 쓰기 가능한 상태로 유지됩니다. `/api/settings` 자체(및 `/api/settings/require-login`)의 모든 변형에는 `admin` 액세스 토큰 범위(`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, 정확한 경로 일치)도 필요합니다. `GET` `read` 유지하고 다른 `/api/settings/*` 하위 경로(프록시, 콤보 기본값, 모델 별칭, 압축, 제거…)는 메서드에서 유추된 `write` 범위를 유지합니다.
- `POST /api/settings/import-json` 재인증을 건너뛰므로 쓰기 전에 `IMPORT_STRIPPED_SETTINGS_KEYS` (동일 파일)의 모든 키(비밀번호 및 `currentPassword`, 모든 `SECURITY_IMPACTING_SETTINGS_KEYS` 항목 및 대시보드 세션 상태(`sessionsValidAfter`, `revokedDashboardSessions`))를 삭제합니다. 따라서 이전 백업을 가져오면 비밀번호 변경이나 로그아웃이 이미 종료된 세션을 다시 시작할 수 없습니다.

#### 선택적 TOTP 2단계 로그인(#16619)

설정 → 보안에서 등록되었습니다. 운영자가 이를 켤 때까지 꺼집니다(`src/server/auth/dashboardMfa.ts`).

- **다루는 내용:** 비밀번호 로그인(`POST /api/auth/login`, `POST /api/auth/mfa/verify` 필요 ) 및 `omniroute connect` (`POST /api/cli/connect`, 비밀번호 전용 교환을 거부하고 코드를 `totp` 로 사용).
- **다루지 않는 내용:** OIDC / SSO 로그인(`/api/auth/oidc/callback`)은 OmniRoute TOTP 를 요청하지 않습니다. 이는 ID 공급자의 자체 두 번째 요소에 의존하므로 OIDC 활성화된 경우 IdP 에서 MFA 적용하십시오.
- **회복** (분실된 장치, 남은 복구 코드가 없거나 더 이상 확인할 수 없는 요소(예: `STORAGE_ENCRYPTION_KEY` 변경 후)):
  1. `OMNIROUTE_DISABLE_MFA=true` 로 서버를 다시 시작하십시오.
  2. 호스트 자체(루프백 피어 및 루프백 `Host`, 예: `http://localhost:20128`)에서 비밀번호로 로그인합니다. 두 번째 요소는 해당 원점에 대해서만 건너뜁니다. 다른 모든 출처에는 여전히 코드가 필요합니다.
  3. 설정 → Security → 비활성화에서 비밀번호를 입력하고 코드를 비워 두세요. `POST /api/auth/mfa/disable` 변수가 설정되고 요청이 호스트에서 오는 동안에만 `code` 없이 본문을 허용합니다. 여전히 대시보드 세션과 현재 비밀번호가 필요하며 `secondFactor: "recovery_switch"` 사용하여 `auth.mfa.disabled` 로 감사됩니다.
  4. `OMNIROUTE_DISABLE_MFA` 설정을 해제하고 다시 시작한 후 필요한 경우 다시 등록하세요.

## 라우트 클래스

`src/server/authz/types.ts`는 세 가지 클래스를 정의합니다. 결정론적으로 분류할 수 없는 라우트는 모두 `MANAGEMENT`로 대체됩니다.

| Class        | Description                                                                                                                                      | Auth required                                                  |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------- |
| `PUBLIC`     | 명시적으로 안전한 라우트 — 로그인, 로그아웃, 상태, 초기화, 헬스 체크, 온보딩 부트스트랩.                                                         | 없음                                                           |
| `CLIENT_API` | 모델 서빙 엔드포인트 — `/api/v1/*`, `/api/v1beta/*`, 그리고 별칭 `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | 유효한 `REQUIRE_API_KEY` 기능 플래그가 활성화된 경우 Bearer 키 |
| `MANAGEMENT` | 대시보드 페이지, 설정, 프로바이더, 키, 관리 및 진단 엔드포인트.                                                                                  | 대시보드 세션 또는 `manage` 스코프의 Bearer                    |

일부 `MANAGEMENT` 작업은 **운영자 전용**입니다. `manage` 키만으로는 충분하지 않습니다. 저장된 자격 증명 내보내기(`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), 라이브 데이터 위에 백업 복원(`dryRun=true`를 포함한 `POST /api/db-backups/import`, ID 기준 `POST /api/db-backups` 복원, `POST /api/settings/import-json`), 복원 지점 삭제(`DELETE /api/db-backups` 정리, 그리고 `PATCH /api/db-backups` — 여기서 저장되는 보존 설정이 백업 후 자동 정리를 결정하기 때문입니다)에는 대시보드 세션, 로컬 CLI 주체, 또는 로그인 비활성화 상태가 필요합니다. 동기화 토큰 발급(`POST /api/sync/tokens`)과 `admin` CLI 액세스 토큰 발급(`POST /api/cli/tokens`)은 모든 로그인 모드에서 대시보드 세션 또는 로컬 CLI 주체가 필요합니다. 어떤 스코프의 API 키와 `oma_` 액세스 토큰도 운영자 자격 증명이 아니므로, 이런 자격 증명이 요구되는 곳에서는 항상 `403`을 받습니다. 이 검사는 `src/lib/api/operatorCredential.ts`(`resolveOperatorCredential()` / `requireOperatorCredential()`)에 있습니다. 로그인 설정 변경도 운영자 전용입니다. `POST /api/settings/require-login`(관리 비밀번호 설정, `requireLogin` 토글)은 비밀번호가 한 번 만들어진 뒤에는 이 자격 증명만 받아들입니다. 최초 실행 부트스트랩 기간(아직 비밀번호가 없는 상태)은 그대로 유지됩니다. 대시보드 세션으로 비밀번호를 교체하려면 `currentPassword`를 보내야 하며(누락되거나 틀리면 `403`, `settings.update_failed`로 감사 기록), 로컬 CLI와 로그인이 비활성화된 인스턴스는 복구 경로를 유지하여 이것 없이도 비밀번호를 설정할 수 있습니다. 둘 다 데이터 디렉터리를 소유한 호스트에 묶여 있기 때문입니다.

## 관로

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

신뢰할 수 있는 내부 헤더( `src/server/authz/headers.ts` 에 정의됨)는 다음과 같습니다.** 들어오는 요청에서 제거됨** 분류 전에 — 클라이언트는 주제를 가장하기 위해 `x-omniroute-auth-*` 미리 채울 수 없습니다.

### 정책 계약

각 경로 클래스에는 `src/server/authz/policies/` 정책이 있습니다.

- **`publicPolicy`** (`policies/public.ts`) — 항상 `allow({ kind: "anonymous", id: "anonymous" })` 반환합니다.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — Bearer를 추출하고 `validateApiKey()` 통해 유효성을 검사합니다. 유효한 `REQUIRE_API_KEY` 기능 플래그가 비활성화된 경우에만 익명으로 전환됩니다. 유효 플래그는 `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`)를 통해 확인되므로 대시보드 기능 플래그와 환경 변수는 `/api/v1/*`, `/api/v1beta/*` 및 별칭을 일관되게 관리합니다. 해결 프로그램 오류가 실패로 종료되었습니다. 클라이언트 API 경로(대시보드 모델 카탈로그에서 사용되는 `/api/v1/models` 포함)에 대한 대시보드 세션 요청을 허용합니다. Entra ID SSO 활성화되면 구조적으로 Entra 토큰(3개의 base64url 세그먼트, `RS*` alg, `kid`)인 Bearer가 SSO 분기에 의해 처리됩니다.** ~ 전에** `validateApiKey()` 및 해당 평결은 최종 — 입니다. 이는 API 키 경로 또는 익명으로 저하 분기를 통과하지 않으므로 ID 제공자 중단은 공개 액세스가 될 수 없습니다. 정적 API 키는 영향을 받지 않습니다. [Entra ID SSO](../security/ENTRA_SSO.md) 참조하세요.
- **`managementPolicy`** (`policies/management.ts`) — 대시보드 세션, 내부 모델 동기화 요청( `/api/providers/[name]/(sync-models|models)` 와 일치)을 수락하거나 `isAuthRequired()` false를 반환하는 경우 완전히 건너뜁니다. Bearer 토큰이 있지만 유효하지 않은 경우 403(`AUTH_001`)을 반환하고, 그렇지 않으면 401을 반환합니다. 또한 인증 분기 — 이전에 경로 보호 계층(LOCAL_ONLY / ALWAYS_PROTECTED)을 적용합니다. [경로 보호 계층을](../security/ROUTE_GUARD_TIERS.md) 참조하세요. Bearer 키가 `manage` 범위를 전달하는 경우 `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (현재: `/api/mcp/`)의 LOCAL_ONLY 경로는 비루프백에서 액세스할 수 있습니다. 다른 모든 LOCAL_ONLY 경로는 범위에 관계없이 엄격한 루프백을 유지합니다.

성공적인 정책은 `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` 와 함께 `AuthSubject` 반환합니다. 다운스트림 핸들러는 인증 로직을 다시 실행하는 대신 `src/server/authz/assertAuth.ts` 의 `assertAuth(request, "CLIENT_API")` 통해 이를 읽을 수 있습니다.

## 공용 경로 목록

`src/shared/constants/publicApiRoutes.ts` 는 명시적인 허용 목록입니다.

목록은 다음과 같이 나뉩니다.** 모양** , 분할은 로드 베어링(GHSA-74g9-q8f6-793h)입니다. 접두사는 `startsWith()` 와 일치하므로 선행 문자를 공유하는 모든 인접한 경로와도 일치합니다. `/api/usage/om-usage` `/api/usage/om-usage<anything>` PUBLIC 로 표시된 접두사로 사용되며 Next는 이를 자체 인증이 없는 처리기인 `/api/usage/[connectionId]` — 로 확인합니다.

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

읽기 전용 경로는 공개입니다.** 오직** 안전한 방법을 위해. 참고: `classifyRoute()` PUBLIC fall-through — 에서 `/api/v1/*` 및 `/api/v1beta/*` 제외합니다. 이들은 항상 `CLIENT_API` 이므로 Bearer-key 정책이 계속 적용됩니다.

## 새 라우트 추가하기

### 패턴 1 — 공개 클라이언트 API 엔드포인트(Bearer 인증)

`/api/v1/` 및 `/api/v1beta/` 아래의 라우트는 자동으로 `CLIENT_API`로 분류됩니다. 미들웨어가 Bearer 검사를 적용하므로 라우트 핸들러에서 이를 다시 수행할 필요는 없지만, 필요한 경우 주체를 읽을 수 있습니다.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... 핸들러 로직
}
```

### 패턴 2 — 관리 엔드포인트(세션 또는 Bearer + manage)

`src/lib/api/requireManagementAuth.ts`의 `requireManagementAuth()`를 사용합니다.

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... 핸들러 로직
}
```

`requireManagementAuth()`는 성공 시 `null`을 반환하고, 실패 시 JSON 오류 `Response`를 반환합니다.

- 401 `AUTH_001` "인증 필요" — 자격 증명이 전혀 없음
- 403 — 유효하지 않은 Bearer이거나, Bearer가 있지만 키에 `manage` / `admin` 범위가 없음

`hasManageScope(scopes)`는 `"manage"` 또는 `"admin"`에 대해 true를 반환합니다.

### 패턴 3 — 공개 허용 목록에 추가하기

편의성이 아니라 형태에 따라 세트를 선택하세요. 단일 라우트는 `PUBLIC_API_ROUTES_EXACT`에 추가하고(GET 전용인 경우 `PUBLIC_READONLY_CORS_API_ROUTES`), 실제 하위 트리만 `PUBLIC_API_ROUTE_PREFIXES`에 추가해야 하며 반드시 `/`로 끝나야 합니다. 단일 라우트를 접두사 목록에 넣으면 선행 문자가 같은 모든 인접 경로도 공개됩니다. 여기에는 나중에 추가되는 동적 세그먼트 형제 라우트도 포함됩니다(GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts`, `tests/unit/authz/classify.test.ts`의 단위 테스트를 업데이트하세요.

## 스코프

세 가지 네임스페이스. 각 검사기는 자체 문자열만 읽습니다. `manage`가 `read:compression`에 대해 `scopeMatches`에 실패하는 이유와 `read` 액세스 토큰이 `PATCH /api/keys/{id}`를 수행할 수 없는 이유를 포함한 비교 설명은 [세 가지 스코프 네임스페이스](../frameworks/MCP-SERVER.md#three-scope-namespaces)를 참조하십시오.

API 키는 `scopes` 배열을 가집니다 (`api_keys.scopes`에 JSON으로 저장되며, `src/lib/db/apiKeys.ts` 참조).

### 관리 스코프

- `manage` / `admin` — `hasManageScope`. 관리 API 경로에 대한 베어러 액세스.
- `mcp:connect`, `self:usage`, `self:account-quota`, 및 `policy:bypass-provider-quota`는 추가적인 정확 일치 스코프입니다. 이들은 `MANAGEMENT_API_KEY_SCOPES` 외부에 있습니다. `mcp:connect`는 `/api/mcp/` 비-루프백 carve-out만 엽니다.

### MCP 도구 스코프

카탈로그 및 일치 규칙(동일한 문자열 또는 `*`로 끝나는 부여된 스코프): [MCP 도구 스코프](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `src/shared/constants/mcpScopes.ts`의 `MCP_SCOPE_LIST`는 전체 카탈로그가 아닌 원래의 타입 지정된 서브셋입니다. `resolveCallerScopeContext()`가 MCP 인증 정보, 요청 메타데이터 또는 `OMNIROUTE_MCP_SCOPES`에서 스코프를 해결한 후 `open-sse/mcp-server/scopeEnforcement.ts`에서 강제가 실행됩니다. `OMNIROUTE_MCP_ENFORCE_SCOPES=true`가 아닌 한 비활성화됩니다.

### 액세스 토큰 스코프

`oma_live_…` 토큰에 대한 `read` / `write` / `admin`은 `scopeSatisfies`(`src/lib/accessTokens/scopes.ts`)에 의해 순위가 매겨집니다. 이 순위는 액세스 토큰 자격 증명에만 적용됩니다. [관리 인증](../guides/MANAGEMENT-AUTH.md)을 참조하십시오.

## 인증 필요 토글

`src/shared/utils/apiAuth.ts`의 `isAuthRequired()`는 요청에 대해 **어떤** 인증이라도 강제할지 결정합니다:

- `settings.requireLogin === false` → 인증이 전역적으로 비활성화됩니다. 단, 항상 보호되는 계층([Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md) 참조)과, 로그인이 켜져 있을 때와 같은 자격 증명이 필요한 자격 증명 발급 호출은 예외입니다. 동기화 토큰 발급, 모든 스코프의 CLI 액세스 토큰 발급, `manage`/`admin` 스코프 API 키 생성, 해당 스코프를 키에 부여하기, 그런 키를 재생성하거나 표시하기가 여기에 해당합니다(`src/lib/api/requireManagementAuth.ts`의 `requireCredentialForManagementScopedKey()`). 추론 전용 키는 계속 열려 있습니다.
- 비밀번호가 설정되어 있지 않고 **동시에** `INITIAL_PASSWORD` 환경 변수도 없으면 → 부트스트랩 모드에서는 온보딩 마법사와 루프백 요청을 허용하지만, 외부 네트워크 요청은 여전히 자격 증명이 필요합니다.
- 모든 DB 오류 → 닫힘(fail closed, 보안 기본값).

클라이언트 API 키 강제는 `process.env.REQUIRE_API_KEY`를 직접 읽는 대신 `src/shared/utils/featureFlags.ts`의 `isRequireApiKeyEnabled()`를 사용합니다. 이는 배포된 인스턴스에서 중요합니다. 대시보드 → Feature Flags에서 `REQUIRE_API_KEY`를 전환하면 DB 오버라이드가 저장되어 즉시 `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` 및 이 헬퍼를 공유하는 다른 클라이언트 API 인증 검사에 영향을 줍니다. 기능 플래그 저장소를 읽을 수 없으면 클라이언트 API 인증은 닫힘 상태가 되어 키를 요구합니다.

## 호환성을 깨는 변경 사항 — v3.8.0

`/api/v1/agents/tasks/*` 및 `/api/resilience/model-cooldowns` 엔드포인트는 **이제 관리 인증이 필요합니다**(커밋 `588a0333`). 이전처럼 `manage` 범위가 없는 일반 API 키를 보내는 클라이언트는 `403`을 받습니다. 마이그레이션: API Keys 대시보드에서 해당 키에 `manage` 범위를 부여하거나, 로그인된 대시보드 세션을 사용하세요.

## 동작 변경 사항 — v3.8.2

`/api/mcp/*`(원격 MCP 서버)는 여전히 기본적으로 LOCAL_ONLY이지만, 이제 `Authorization: Bearer <api-key>` 헤더에 `manage` 범위가 포함된 경우 비루프백 요청을 허용합니다. 이 예외는 `src/server/authz/routeGuard.ts`의 `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES`를 통해 경로별로 명시적으로 제한됩니다. 같은 계층의 LOCAL_ONLY 접두사인 `/api/cli-tools/runtime/*`는 임의의 하위 프로세스를 생성할 수 있으므로 의도적으로 우회할 수 없습니다. 비루프백에서 `/api/mcp/*`로 보내는 익명 요청은 계속 `403 LOCAL_ONLY`를 반환하며, 새로운 LOCAL_ONLY 경로의 기본값은 엄격한 루프백 전용으로 유지됩니다. [라우트 가드 계층](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)을 참조하세요.

## 테스트

- 단위 테스트: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- 공개 허용 목록: `tests/unit/public-api-routes.test.ts`.
- 집중 실행: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## 디버깅

파이프라인은 항상 다음을 사용하여 응답에 스탬프를 찍습니다.

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

인증된 요청의 경우 업스트림(처리기 측) 요청 헤더에는 다음도 포함됩니다.

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

핸들러 `assertAuth(req, expectedClass)` 내에서 — 를 사용하면 미들웨어가 우회된 경우 코드 `AUTHZ_NOT_INITIALIZED` 와 함께 `AuthzAssertionError` 발생합니다(테스트에서 구성 회귀를 포착하는 데 도움이 됨).

## 관련 항목

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — 엔드포인트별 인증 마커
- [COMPLIANCE.md](../security/COMPLIANCE.md) — 인증 이벤트에 대한 감사 로그
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — 세 가지 스코프 네임스페이스 및 MCP 도구 스코프 카탈로그
- 소스: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
