# Authorization Guide (Filipino)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Pinagmulan ng katotohanan:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Huling na-update:** 2026-09-22 — ang mga namespace ng saklaw ay tumuturo sa MCP-SERVER.md

Ang OmniRoute ay may pipeline ng awtorisasyon na may kamalayan sa ruta na nagbabantay sa bawat kahilingan ng API. Ang klasipikasyon ay **deterministic** at **fail-closed** — anumang hindi maiklasipika ay nagtatapos bilang `MANAGEMENT` at nangangailangan ng session o token na pang-pamamahala. Ipinaliliwanag ng pahinang ito ang modelo para sa mga inhinyero na nagpapanatili ng mga ruta o nagdidisenyo ng mga bagong endpoint.

![AuthZ pipeline (3 klase ng ruta + pagsusuri ng patakaran)](../diagrams/exported/authz-pipeline.svg)

> Pinagmulan: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dalawang Auth Mode

### 1. API Key (Tagapagdala)

Ginagamit para sa OpenAI/Anthropic/Gemini-compatible client APIs at ilang mga ruta ng pamamahala kapag ang susi ay may saklaw na `manage`.

```
Authorization: Bearer <api-key>
```

Na-validate ng `isValidApiKey()` / `extractApiKey()` sa `src/sse/services/auth.ts` at muling na-export sa pamamagitan ng `src/shared/utils/apiAuth.ts`. Tinatanggap din ng validator ang `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars bilang mga persistent passthrough key (isyu #1350).

### 2. Dashboard Session (auth_token cookie)

Para sa mga pahina ng dashboard at mga pagpapatakbo ng admin.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Ang cookie ay isang session lamang kapag nag-verify ang JWT** at** nagdadala ng `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Ang bawat consumer ng cookie (dashboard route guard (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, live server, `/api/settings/require-login`, `/api/auth/status`) ay dumadaan sa helper na iyon. Ang iba pang JWTs na nilagdaan ng `JWT_SECRET` ay umiiral — ang Cursor CLI passthrough na minnts `iss "omniroute" / aud "cursor-cli"` token para sa mga may hawak ng key — at hindi kailanman mga session (#13298).

Na-verify ni `isDashboardSessionAuthenticated()` sa `src/shared/utils/apiAuth.ts`. Awtomatikong nire-refresh ng pipeline ang JWT kapag wala pang 7 araw ang natitira sa 30-araw na buhay nito.

Ang isang session ay maaari ding matapos bago matapos ang 30 araw nito, dahil ang bawat tagapagturo ay dumadaan sa `mintDashboardSessionToken` (isang oras ng isyu `iat` at isang id `jti`) at sinusuri ng verifier ang dalawang setting: `sessionsValidAfter`, itinakda ng pagbabago ng password upang ang bawat session na inilabas bago ito huminto sa pag-verify (ang browser na nagpapalitan ng password ay makakakuha ng bagong cookie), at `revokedDashboardSessions`, kung saan idinaragdag ng `POST /api/auth/logout` ang session na nilagdaan ng `jti`-out. Ang mga session na ginawa ng isang mas lumang release ay walang claim at mananatiling wasto hanggang sa unang pagbabago ng password. Kung hindi mabasa ang mga setting, hindi mapagkakatiwalaan ang session.

Tinatanggap ang ilang ruta ng pamamahala** alinman** mode: cookie OR `Bearer <key>` kapag ang API key ay may `manage` (o `admin`) na saklaw. Ito ang nagbibigay-daan sa workflow na "nako-configure sa pamamagitan ng mga API na tawag" na idinagdag sa v3.8.

#### Opsyonal OIDC login gate (#6973)

Sinusuportahan din ng dashboard admin login ang isang** mag-opt-in** OIDC (OpenID Connect) na daloy sa tabi ng default na password login — password login ay hindi kailanman inaalis, dinadagdagan lamang:

- Naka-disable maliban kung `settings.oidcEnabled === true`** at** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` ay na-configure lahat (Mga Setting → Auth). `GET /api/auth/oidc/login` ay nagbabalik `400` kung hindi man.
- Natuklasan `GET /api/auth/oidc/login` ang `authorization_endpoint` mula sa `/.well-known/openid-configuration` ng issuer (bumabalik sa `<issuer>/authorize`), binubuo ang redirect URI mula sa papasok na kahilingan (`x-forwarded-proto` -aware), at nagre-redirect sa IdP na may random `state` na nakaimbak sa isang `httpOnly` `oidc_state` cookie.
- bini-validate `GET /api/auth/oidc/callback` `state`, pinapalitan ang authorization code, at bini-verify ang pirma ng ID token sa pamamagitan ng JWKS ng issuer (`jose` ng `createRemoteJWKSet`, naka-cache sa bawat JWKS URI) gamit ang `issuer`/`audience` na tseke. Nangangailangan ang pagpasok sa dashboard ng walang laman na listahan `oidcAllowedSubjects`, patakaran `oidcAdmissionClaim`, o pareho. Ang listahan ng paksa ay tumutugma `sub` o `email` kapag `email_verified === true`. Ang opsyonal na patakaran sa pag-claim ay tumatagal ng isang tuldok na pinaghihiwalay ng ID-token na landas ng claim (halimbawa, `realm_access.roles`) at isang hanay ng mga tinatanggap na halaga; ang nalutas na claim ay dapat na isang hanay ng mga string na naglalaman ng hindi bababa sa isang tinatanggap na halaga. Kung ang parehong mga patakaran ay na-configure, ang parehong ay dapat pumasa. Ang mga claim Missing/malformed ay nabigo sa pagsasara, at nang walang alinman sa patakaran ang callback ay tumanggi sa pag-login (`not_configured`). Ang mga kasalukuyang configuration na paksa lamang ay patuloy na hindi nagbabago.
- Ang Keycloak ay karaniwang nagmamapa ng mga tungkulin sa realm sa mga token ng pag-access, hindi kinakailangang mga ID token. Upang hingin ang realm role `admin`, i-configure ang isang protocol mapper para sa client na ito na may kasamang `realm_access.roles` sa nito**ID token** , pagkatapos ay itakda `oidcAdmissionClaim` sa `{ "path": "realm_access.roles", "values": ["admin"] }`. Suriin ang aktwal na ID-token claim para sa kliyenteng ito bago i-enable ang role-only admission; ang application ay hindi nagbabasa ng mga tungkulin ng access-token. Ang pagtanggi sa token sa panig ng IdP ay maaaring dagdagan ngunit hindi pinapalitan ang pagsusuri sa panig ng application na ito.
- On success it mints the **exact same** 30-day `auth_token` JWT the password login issues (`src/app/api/auth/login/route.ts`), so the rest of the dashboard session pipeline (auto-refresh, cookie flags) is unchanged — OIDC only replaces how the cookie gets minted, not what it grants. Changes to IdP roles/groups do not invalidate existing OmniRoute sessions; logout, password rotation, or session expiry still govern their lifetime.
- Ang bawat setting `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) ay nasa `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): sinasagot `PATCH /api/settings` `400 PASSWORD_REQUIRED` maliban kung ang katawan ay nagdadala ng password ng pamamahala bilang `currentPassword` (`401 PASSWORD_MISMATCH` kapag mali). `oidcDisablePasswordLogin` ay tumatanggi sa password na _login_ (`POST /api/auth/login`) ngunit pinapanatili ang nakaimbak na password hash, at muling i-auth ay sinusuri pa rin ang `currentPassword` laban dito.
- `corsOrigins` at `bruteForceProtection` ay nasa `SECURITY_IMPACTING_SETTINGS_KEYS` din: ang pag-loosening ay nagpapahina sa mga panlaban sa pag-login, kaya't sila ay kukuha ng parehong `currentPassword` re-auth (hinihiling ito ng tab na Seguridad) at ang JSON import ay bumababa sa kanila.
- Ang bawat security-policy key — ang `SECURITY_IMPACTING_SETTINGS_KEYS` entries, bawat `oidc*` key at ang dashboard session na estado — ay** operator-lamang** on `PATCH /api/settings`: ang isang API key na nasasakupan ng pamamahala o isang token ng pag-access `oma_` ay tinanggihan ng `403` kahit na ipinadala nito ang tamang `currentPassword`, at ang pagtanggi ay na-audit bilang `settings.update_failed` na may `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` sa `src/lib/api/operatorCredential.ts`). Ang mga karaniwang setting (tema, mga kagustuhan sa display) ay mananatiling maisusulat para sa isang `manage` key o isang `admin` access token. Ang bawat mutation ng `/api/settings` mismo (at ng `/api/settings/require-login`) ay nangangailangan din ng `admin` access-token scope (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, exact-path match); nananatili `GET` `read`, at ang iba pang mga sub-ruta `/api/settings/*` (mga proxy, mga default ng combo, mga alias ng modelo, compression, purges...) ay pinapanatili ang saklaw `write` na hinuha ng pamamaraan.
- Nilaktawan `POST /api/settings/import-json` ang muling pag-auth, kaya ibinabagsak nito ang bawat key sa `IMPORT_STRIPPED_SETTINGS_KEYS` (parehong file) bago isulat: ang password at `currentPassword`, bawat `SECURITY_IMPACTING_SETTINGS_KEYS` entry, at ang estado ng session ng dashboard (`sessionsValidAfter`, `revokedDashboardSessions`). Ang pag-import ng mas lumang backup samakatuwid ay hindi maaaring muling buhayin ang isang session na ang isang pagbabago ng password o isang pag-sign out ay natapos na.

#### Opsyonal TOTP two-factor login (#16619)

Naka-enroll mula sa Mga Setting → Security; patayin hanggang sa i-on ito ng operator (`src/server/auth/dashboardMfa.ts`).

- **Ano ang saklaw nito:** password login (`POST /api/auth/login`, na pagkatapos ay nangangailangan ng `POST /api/auth/mfa/verify`) at `omniroute connect` (`POST /api/cli/connect`, na tumatanggi sa isang password-only exchange at kinuha ang code bilang `totp`).
- **Ano ang hindi saklaw nito:** OIDC / SSO sign-in (`/api/auth/oidc/callback`) ay hindi humihingi ng OmniRoute TOTP. Umaasa ito sa sariling pangalawang salik ng tagapagbigay ng pagkakakilanlan, kaya ipatupad MFA sa IdP kung pinagana ang OIDC.
- **Pagbawi** (nawalang device, walang natitirang code sa pagbawi, o isang salik na hindi na ma-verify, halimbawa pagkatapos baguhin `STORAGE_ENCRYPTION_KEY` ):
  1. I-restart ang server gamit ang `OMNIROUTE_DISABLE_MFA=true`.
  2. Sa mismong host (loopback peer at loopback `Host`, gaya ng `http://localhost:20128`), mag-sign in gamit ang password. Ang pangalawang salik ay nilaktawan para sa pinanggalingan lamang; kailangan pa rin ng code ang bawat ibang pinanggalingan.
  3. Sa Mga Setting → Security → I-disable, ipasok ang password at iwanang blangko ang code. `POST /api/auth/mfa/disable` ay tumatanggap ng isang katawan na walang `code` lamang habang ang variable ay nakatakda at ang kahilingan ay mula sa host; kailangan pa rin nito ang session ng dashboard at ang kasalukuyang password, at sinusuri bilang `auth.mfa.disabled` na may `secondFactor: "recovery_switch"`.
  4. I-unset `OMNIROUTE_DISABLE_MFA`, i-restart, at mag-enroll muli kung kinakailangan.

## Mga Uri ng Route

`src/server/authz/types.ts` ay nagtatakda ng tatlong uri. Anumang route na hindi maiuuri nang tiyak ay babalik sa `MANAGEMENT`.

| Uri          | Paglalarawan                                                                                                                                                      | Kinakailangang auth                                                           |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| `PUBLIC`     | Tahasang ligtas na mga route: login, logout, status, init, health, onboarding bootstrap.                                                                          | Wala                                                                          |
| `CLIENT_API` | Mga model-serving endpoint: `/api/v1/*`, `/api/v1beta/*`, kasama ang mga alias na `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer key kapag naka-enable ang epektibong feature flag na `REQUIRE_API_KEY` |
| `MANAGEMENT` | Mga dashboard page, settings, provider, key, admin at diagnostics endpoint.                                                                                       | Dashboard session O Bearer na may `manage` scope                              |

Ilang aksyon ng `MANAGEMENT` ay **operator-only**: hindi sapat ang `manage` key. Ang pag-export ng nakaimbak na credential (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ang pagbabalik ng backup sa ibabaw ng live na data (`POST /api/db-backups/import` kasama ang `dryRun=true`, `POST /api/db-backups` na restore ayon sa id, `POST /api/settings/import-json`), at ang pagsira ng restore point (`DELETE /api/db-backups` na cleanup, at `PATCH /api/db-backups` dahil ang retention na isinasave nito ang nagpapatakbo ng awtomatikong pruning pagkatapos ng bawat backup) ay nangangailangan ng dashboard session, ng lokal na CLI subject, o ng naka-disable na login. Ang pag-isyu ng sync token (`POST /api/sync/tokens`) at ang pag-mint ng `admin` CLI access token (`POST /api/cli/tokens`) ay nangangailangan ng dashboard session o ng lokal na CLI subject sa bawat login mode. Ang mga API key ng anumang scope at ang mga `oma_` access token ay hindi operator credential: nakakakuha sila ng `403` tuwing kailangan ang isa. Nasa `src/lib/api/operatorCredential.ts` ang check (`resolveOperatorCredential()` / `requireOperatorCredential()`). Operator-only din ang pagbabago ng login settings: tinatanggap lamang ng `POST /api/settings/require-login` (magtakda ng management password / i-toggle ang `requireLogin`) ang mga credential na iyon kapag may password na, hindi nagbabago ang first-run bootstrap window (walang password pa), at dapat magpadala ng `currentPassword` ang dashboard session para palitan ang password (`403` kapag nawawala o mali ito, at ina-audit bilang `settings.update_failed`). Pinananatili ng lokal na CLI at ng instance na naka-disable ang login ang recovery path at maaaring magtakda ng password nang wala nito, dahil parehong nakatali ang dalawa sa host na nagmamay-ari ng data directory.

## Pipeline

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

Ang mga pinagkakatiwalaang panloob na header (tinukoy sa `src/server/authz/headers.ts`) ay** inalis sa mga papasok na kahilingan** bago ang pag-uuri — client ay hindi maaaring pre-populate `x-omniroute-auth-*` upang gayahin ang isang paksa.

### Mga kontrata sa patakaran

Ang bawat klase ng ruta ay may patakaran sa `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) palaging nagbabalik ng `allow({ kind: "anonymous", id: "anonymous" })` —.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — extracts Bearer, nagpapatunay sa pamamagitan ng `validateApiKey()`. Nahulog sa anonymous lamang kapag ang epektibong `REQUIRE_API_KEY` feature flag ay hindi pinagana. Ang epektibong flag ay nareresolba sa pamamagitan ng `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) kaya ang Dashboard Feature Flags at environment variable ay patuloy na namamahala `/api/v1/*`, `/api/v1beta/*`, at mga alias; Ang mga pagkabigo sa solver ay nabigo na sarado. Pinapayagan ang mga kahilingan sa dashboard-session sa mga ruta API ng kliyente (kabilang ang `/api/v1/models`, na ginagamit ng catalog ng modelo ng dashboard). Kapag ang Entra ID SSO ay pinagana, ang isang Bearer na structurally ay isang Entra token (tatlong base64url segment, `RS*` alg, `kid`) ay pinangangasiwaan ng SSO branch** dati** `validateApiKey()` at ang hatol nito ay pangwakas na — hindi ito nahuhulog sa API-key path o sa degrade-to-anonymous na sangay, kaya hindi maaaring maging bukas na access ang pagkawala ng identity-provider. Ang mga static API key ay hindi naaapektuhan. Tingnan [ang Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) tumatanggap ang — ng sesyon ng dashboard, mga kahilingan sa panloob na pag-sync ng modelo (itinugma laban sa `/api/providers/[name]/(sync-models|models)`), o ganap na lumalaktaw kung nagbabalik ng false `isAuthRequired()`. Ibinabalik ang 403 (`AUTH_001`) kapag may Bearer token ngunit invalid, 401 kung hindi. Ipinapatupad din ang mga tier ng route-guard (LOCAL_ONLY / ALWAYS_PROTECTED) bago ang anumang auth branch — tingnan [ang Mga Tier ng Route Guard](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY path sa `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (ngayon: `/api/mcp/`) ay maaaring ma-access mula sa non-loopback kapag ang Bearer key ay nagdadala ng `manage` scope; lahat ng iba pang mga LOCAL_ONLY path ay nananatiling mahigpit-loopback anuman ang saklaw.

Ang isang matagumpay na patakaran ay nagbabalik `AuthSubject` na may `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Mababasa ito ng mga humahawak sa downstream sa pamamagitan ng `assertAuth(request, "CLIENT_API")` sa `src/server/authz/assertAuth.ts` sa halip na muling patakbuhin ang logic ng auth.

## Listahan ng mga Pampublikong Ruta

`src/shared/constants/publicApiRoutes.ts` ay ang tahasang allowlist:

Ang listahan ay hinati ng** hugis** , at ang split ay load-bearing (GHSA-74g9-q8f6-793h): ang isang prefix ay itinutugma sa `startsWith()`, kaya tumutugma din ito sa bawat katabing path na nagbabahagi ng mga nangungunang character nito. `/api/usage/om-usage` bilang prefix na may markang `/api/usage/om-usage<anything>` PUBLIC, at ang Susunod ay niresolba iyon sa `/api/usage/[connectionId]` — isang handler na walang sariling auth.

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

Pampubliko ang mga read-only na ruta** lamang** para sa mga ligtas na pamamaraan. Tandaan: ibinubukod `classifyRoute()` `/api/v1/*` at `/api/v1beta/*` mula sa PUBLIC fall-through — ang mga iyon ay palaging `CLIENT_API` kaya nalalapat pa rin ang patakaran sa Bearer-key.

## Pagdaragdag ng Bagong Route

### Pattern 1 — Pampublikong client API endpoint (Bearer-auth)

Awtomatikong inuuri bilang `CLIENT_API` ang mga route sa ilalim ng `/api/v1/` at `/api/v1beta/`. Ipinapatupad ng middleware ang Bearer check; hindi na ito kailangang ulitin ng mga route handler, ngunit maaari nilang basahin ang subject kung kapaki-pakinabang.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... lohika ng handler
}
```

### Pattern 2 — Management endpoint (session o Bearer + manage)

Gamitin ang `requireManagementAuth()` mula sa `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... lohika ng handler
}
```

Nagbabalik ang `requireManagementAuth()` ng `null` kapag matagumpay, o ng JSON error na `Response`:

- 401 `AUTH_001` "Kailangan ang pagpapatotoo" — walang anumang credential
- 403 — hindi wastong Bearer **o** may Bearer ngunit walang `manage` / `admin` scope ang key

Nagbabalik ng true ang `hasManageScope(scopes)` para sa `"manage"` o `"admin"`.

### Pattern 3 — Pagdaragdag sa pampublikong allowlist

Piliin ang set ayon sa hugis, hindi ayon sa kaginhawaan. Ang isang route ay inilalagay sa `PUBLIC_API_ROUTES_EXACT` (o sa `PUBLIC_READONLY_CORS_API_ROUTES` kung GET-only); isang tunay na subtree lamang ang inilalagay sa `PUBLIC_API_ROUTE_PREFIXES`, at **dapat itong magtapos sa `/`**. Kapag naglagay ng isang indibidwal na route sa listahan ng prefix, nailalantad din sa publiko ang bawat katabing path na may kaparehong mga panimulang character — kabilang ang mga kapatid na dynamic-segment na idadagdag sa hinaharap (GHSA-74g9-q8f6-793h). I-update ang mga unit test sa `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts`, at `tests/unit/authz/classify.test.ts`.

## Mga Saklaw

Tatlong namespace. Bawat checker ay nagbabasa lamang ng sarili nitong string. Ang paghahambing, kasama ang dahilan kung bakit nabigo ang `manage` sa `scopeMatches` para sa `read:compression` at kung bakit ang isang `read` access token ay hindi maaaring `PATCH /api/keys/{id}`, ay [Tatlong namespace ng saklaw](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Ang mga API key ay nagdadala ng `scopes` array (nakaimbak bilang JSON sa `api_keys.scopes`, tingnan ang `src/lib/db/apiKeys.ts`).

### Saklaw ng Pamamahala

- `manage` / `admin` — `hasManageScope`. Bearer access sa mga ruta ng management API.
- Ang `mcp:connect`, `self:usage`, `self:account-quota`, at `policy:bypass-provider-quota` ay mga additive exact-match scope. Ang mga ito ay nasa labas ng `MANAGEMENT_API_KEY_SCOPES`. Binubuksan lamang ng `mcp:connect` ang `/api/mcp/` non-loopback carve-out.

### Mga saklaw ng tool ng MCP

Katalogo at mga panuntunan sa pagtutugma (magkaparehong string, o isang ibinigay na scope na nagtatapos sa `*`): [Mga saklaw ng tool ng MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes). Ang `MCP_SCOPE_LIST` sa `src/shared/constants/mcpScopes.ts` ay ang orihinal na typed subset, hindi ang buong katalogo. Ang pagpapatupad ay tumatakbo sa `open-sse/mcp-server/scopeEnforcement.ts` pagkatapos ma-resolve ng `resolveCallerScopeContext()` ang mga scope mula sa MCP auth info, request metadata, o `OMNIROUTE_MCP_SCOPES`. Mananatili itong naka-off maliban kung `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Mga saklaw ng access-token

`read` / `write` / `admin` sa `oma_live_…` na mga token, na niraranggo ng `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`). Ang ranggong ito ay nalalapat lamang sa credential ng access-token. Tingnan ang [Pagpapatunay ng Pamamahala](../guides/MANAGEMENT-AUTH.md).

## Toggle ng Kinakailangang Auth

Ang `isAuthRequired()` sa `src/shared/utils/apiAuth.ts` ang nagpapasya kung **anumang** auth ang ipapatupad para sa isang request:

- `settings.requireLogin === false` → naka-disable ang auth sa buong sistema, maliban sa always-protected tier (tingnan ang [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) at sa mga tawag na nagbibigay ng credential na tinatanggap nito, na nangangailangan ng parehong credential gaya kapag naka-on ang login: pag-isyu ng sync token, pag-mint ng CLI access token sa anumang scope, at paggawa ng API key na may `manage`/`admin` scope, pagbibigay ng scope na iyon sa isang key, o pag-regenerate o pagpapakita ng ganoong key (`requireCredentialForManagementScopedKey()` sa `src/lib/api/requireManagementAuth.ts`). Nananatiling bukas ang mga inference-only key.
- Walang password na naka-configure **at** walang `INITIAL_PASSWORD` env var → bootstrap mode: pinapayagan ng onboarding wizard at ng loopback request, pero kailangan pa rin ng credential ng mga request mula sa nakalantad na network.
- Anumang DB error → nagfa-fail closed (secure-by-default).

Ang client API key enforcement ay gumagamit ng `isRequireApiKeyEnabled()` sa `src/shared/utils/featureFlags.ts`, hindi ng direktang pagbasa sa `process.env.REQUIRE_API_KEY`. Mahalaga ito para sa mga naka-deploy na instance: ang pagpapalit ng `REQUIRE_API_KEY` sa Dashboard → Feature Flags ay nag-iimbak ng DB override at agad na nakaaapekto sa `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, at iba pang client-API auth check na gumagamit ng parehong helper. Kung hindi mabasa ang feature flag store, nagfa-fail closed ang client API auth at humihingi ng key.

## Breaking Change — v3.8.0

Ang mga endpoint na `/api/v1/agents/tasks/*` at `/api/resilience/model-cooldowns` ay **nangangailangan na ngayon ng management auth** (commit `588a0333`). Ang mga client na dati ay nagpapadala ng karaniwang API key na walang `manage` scope ay makatatanggap ng `403`. Pag-migrate: italaga sa key ang `manage` scope sa API Keys dashboard, o gumamit ng naka-log-in na dashboard session.

## Pagbabago sa Gawi — v3.8.2

Ang `/api/mcp/*` (ang remote MCP server) ay LOCAL_ONLY pa rin bilang default ngunit tumatanggap na ngayon ng mga non-loopback request kapag ang `Authorization: Bearer <api-key>` header ay may `manage` scope. Tahasang nililimitahan ang eksepsiyon sa bawat path sa pamamagitan ng `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` sa `src/server/authz/routeGuard.ts`; sadyang HINDI maaaring i-bypass ang kapatid na LOCAL_ONLY prefix na `/api/cli-tools/runtime/*` dahil maaari itong magsimula ng anumang subprocess. Patuloy na magbabalik ng `403 LOCAL_ONLY` ang mga anonymous na request sa `/api/mcp/*` mula sa non-loopback — nananatiling strict-loopback ang default para sa anumang bagong LOCAL_ONLY path. Tingnan ang [Mga Antas ng Route Guard](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Pagsubok

- Mga unit test: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Pampublikong allowlist: `tests/unit/public-api-routes.test.ts`.
- Patakbuhin nang nakatuon: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Pag-debug

Palaging tinatatak ng pipeline ang mga tugon ng:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Para sa mga napatunayang kahilingan, kasama rin sa upstream (handler-side) na mga header ng kahilingan ang:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Gumamit `assertAuth(req, expectedClass)` inside handlers — it throws `AuthzAssertionError` with code `AUTHZ_NOT_INITIALIZED` if the middleware was bypassed (helpful for catching configuration regressions in tests).

## Tingnan Din

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — pananda ng pagpapatunay bawat endpoint
- [COMPLIANCE.md](../security/COMPLIANCE.md) — audit log para sa mga kaganapan ng pagpapatunay
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tatlong scope namespace at MCP tool-scope catalog
- Pinagmulan: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
