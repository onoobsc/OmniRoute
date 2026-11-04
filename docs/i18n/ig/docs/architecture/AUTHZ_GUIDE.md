# Authorization Guide (Igbo)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Isi iyi nke eziokwu:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Emelitere ikpeazụ:** 2026-09-22 — oghere aha oghere na-atụ aka na MCP-SERVER.md

OmniRoute nwere usoro ikike nwere ike ịmata ụzọ nke na-echebe arịrịọ API ọ bụla. Nchịkọta bụ **nke doro anya** na **nke na-ada ada** — ihe ọ bụla a na-apụghị ịhazi na-ejedebe dị ka `MANAGEMENT` ma na-achọ nnọkọ ma ọ bụ akara ngosi ọkwa njikwa. Ibe a na-akọwa ụdị maka ndị injinia na-elekọta ụzọ ma ọ bụ na-emepụta ebe njedebe ọhụrụ.

![AuthZ pipeline (3 ụdị ụzọ + nyocha amụma)](../diagrams/exported/authz-pipeline.svg)

> Isi iyi: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Ụdị nkwenye abụọ

### 1. igodo API (onye na-ebu)

Ejiri ya maka OpenAI/Anthropic/Gemini-compatible ahịa APIs yana ụzọ njikwa ole na ole mgbe igodo nwere oke `manage`.

```
Authorization: Bearer <api-key>
```

`isValidApiKey()` / `extractApiKey()` kwadoro na `src/sse/services/auth.ts` wee bugharịa ya ọzọ site na `src/shared/utils/apiAuth.ts`. Onye nkwado ahụ na-anabatakwa `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars dị ka igodo ngafe na-adịgide adịgide ( mbipụta #1350).

### 2. Oge dashboard (kuki auto_token)

Maka ibe dashboard na ọrụ nchịkwa.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Kuki bụ nnọkọ naanị mgbe JWT gosipụtara** na** na-ebu `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Onye ọ bụla na-eji kuki (dashboard ụzọ nche (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, live server, `/api/settings/require-login`, `/api/auth/status`) na-agafe onye inyeaka ahụ. JWTs ndị ọzọ bịanyere aka na `JWT_SECRET` dị — Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` token maka isi ji — na ọ dịghị mgbe nnọkọ (#13298).

Kwadoro site na `isDashboardSessionAuthenticated()` na `src/shared/utils/apiAuth.ts`. Pipeline akpaaka na-enye ume ọhụrụ JWT mgbe ọ nwere ihe na-erughị ụbọchị 7 fọdụrụ na ndụ ụbọchị 30 ya.

Otu nnọkọ nwekwara ike kwụsị tupu ụbọchị 30 ya agwụ, n'ihi na onye ọ bụla minter na-agafe `mintDashboardSessionToken` (oge okwu `iat` na id `jti`) na onye nyocha na-enyocha ntọala abụọ: `sessionsValidAfter`, nke edobere site na mgbanwe paswọọdụ ka oge ọ bụla ewepụtara tupu ya akwụsị ịchọpụta (ihe nchọgharị ahụ gbanwere paswọọdụ na-enweta kuki ọhụrụ), na `revokedDashboardSessions`, nke `POST /api/auth/logout` na-agbakwụnye nnọkọ `jti`'s. Ọgbakọ ndị ntọhapụ megoro mere anaghị ebu nkwupụta ma na-adị irè ruo mgbe mgbanwe paswọọdụ mbụ. Ọ bụrụ na enweghị ike ịgụ ntọala ahụ, atụkwasịghị obi nnọkọ ahụ.

Ụfọdụ ụzọ njikwa na-anabata** ma** ụdịdị: kuki OR `Bearer <key>` mgbe igodo API nwere oke `manage` (ma ọ bụ `admin`). Nke a bụ ihe na-enyere aka "configurable site na oku API " agbakwunyere na v3.8.

#### Ọnụ ụzọ nbanye OIDC nhọrọ (#6973)

Nbanye nchịkwa dashboard na-akwadokwa otu** Nwepu** OIDC (OpenID Connect) na-asọ n'akụkụ ndabara paswọọdụ nbanye — paswọọdụ nbanye adịghị ewepụ ya, naanị agbakwunyere:

- Agbanyụrụ belụsọ `settings.oidcEnabled === true`** na** Ahaziri `oidcIssuer` / `oidcClientId` / `oidcClientSecret` niile (Ntọala → Auth). `GET /api/auth/oidc/login` na-alaghachi `400` ọzọ.
- `GET /api/auth/oidc/login` na-achọpụta `authorization_endpoint` site na `/.well-known/openid-configuration` onye wepụtara (dabere azụ na `<issuer>/authorize`), wulite redirect URI site na arịrịọ mbata (`x-forwarded-proto` -aware), wee bugharịa IdP na `state` random echekwara na kuki `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` kwadoro `state`, gbanwee koodu ikike, wee nyochaa akara akara ID site na JWKS onye wepụtara (`jose`'s `createRemoteJWKSet`, cached per JWKS URI) na ndenye `issuer`/`audience`. Nbanye dashboard chọrọ ndepụta `oidcAllowedSubjects` na-adịghị efu, amụma `oidcAdmissionClaim`, ma ọ bụ ha abụọ. Ndepụta isiokwu dabara `sub` ma ọ bụ `email` naanị mgbe `email_verified === true`. Amụma nkwuputa nhọrọ na-ewere ụzọ nkwuwapụta akara ngosi ID-ntụpọ (dịka ọmụmaatụ, `realm_access.roles`) yana ọtụtụ ụkpụrụ anabatara; nkwuputa nke edoziri ga-abụrịrị ọtụtụ eriri nwere opekata mpe otu uru anabatara. Ọ bụrụ na ha abụọ atumatu, ha abụọ ga-agafe. Missing/malformed na-ekwu na-ada mechiri, na-enweghị nke ọ bụla amụma, oku na-aga na-ajụ nbanye (`not_configured`). Nhazi naanị isiokwu dị adị na-aga n'ihu anaghị agbanwe agbanwe.
- Keycloak na-ejikarị maapụ mpaghara ọrụ iji nweta akara ngosi, ọ bụchaghị ID token. Iji chọọ ọrụ `admin`, hazie mapper protocol maka onye ahịa a nke gụnyere `realm_access.roles` na ya.**ID akara** , wee tọọ `oidcAdmissionClaim` ka ọ bụrụ `{ "path": "realm_access.roles", "values": ["admin"] }`. Lelee ihe nrịbama akara ngosi ID maka onye ahịa a tupu ị nwee ike nnabata naanị ọrụ; ngwa anaghị agụ ọrụ ohere-token. Ọjụjụ token n'akụkụ IdP nwere ike ịgbakwunye mana ọ naghị edochi nlele n'akụkụ ngwa a.
- Na ihe ịga nke ọma ọ mints na** kpọmkwem otu** 30-ụbọchị `auth_token` JWT okwu nbanye okwuntughe (`src/app/api/auth/login/route.ts`), yabụ ndị fọdụrụ na pipeline nnọkọ dashboard (akpaaka-refresh, kuki flags) adịghị agbanwe agbanwe — OIDC na-anọchi anya ka esi eme kuki ahụ, ọ bụghị ihe ọ na-enye. Mgbanwe na IdP roles/groups anaghị emebi oge OmniRoute dị adị; ọpụpụ, ntụgharị okwuntughe, ma ọ bụ ngwụcha nnọkọ ka na-achịkwa oge ndụ ha.
- Ntọala `oidc*` ọ bụla (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) dị na `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` na-aza `400 PASSWORD_REQUIRED` belụsọ ma anụ ahụ na-ebu paswọọdụ njikwa dịka `currentPassword` (`401 PASSWORD_MISMATCH` mgbe ọ na-ezighi ezi). `oidcDisablePasswordLogin` jụrụ paswọọdụ _login_ (`POST /api/auth/login`) mana ọ na-edobe hash okwuntughe echekwara, na nyochagharị ka na-enyocha `currentPassword` megide ya.
- `corsOrigins` na `bruteForceProtection` nọkwa na `SECURITY_IMPACTING_SETTINGS_KEYS` : ịtọpụ ma ọ bụ na-ebelata ihe nchebe nbanye, ya mere, ha na-ewere otu `currentPassword` re-auth (Taabụ Nche na-arịọ ya) na mbubata JSON tụfuru ha.
- Igodo nchekwa ọ bụla — ndenye `SECURITY_IMPACTING_SETTINGS_KEYS`, igodo `oidc*` ọ bụla na nnọkọ dashboard steeti — bụ** onye ọrụ naanị** na `PATCH /api/settings`: a na-ajụ igodo API nke njikwa-scoped ma ọ bụ akara ohere `oma_` na `403` ọbụlagodi mgbe ọ na-eziga `currentPassword` ziri ezi, a na-enyocha ọjụjụ ahụ dị ka `settings.update_failed` na `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` na `src/lib/api/operatorCredential.ts`). Ntọala nkịtị (isiokwu, mmasị ngosi) ka enwere ike ịdere maka igodo `manage` ma ọ bụ akara ohere `admin`. Mgbanwe ọ bụla nke `/api/settings` n'onwe ya (na nke `/api/settings/require-login`) chọkwara ohere ohere-token `admin` (`ADMIN_MUTATION_EXACT_PATHS` na `src/server/authz/accessScopes.ts`, egwuregwu egwuregwu ziri ezi); `GET` na-anọ `read`, na nke ọzọ `/api/settings/*` ụzọ ụzọ (proxies, combo defaults, model aliases, compression, purges...) dowe usoro-echere `write`.
- `POST /api/settings/import-json` na-awụgharị nke ahụ, ya mere ọ na-atụba igodo ọ bụla na `IMPORT_STRIPPED_SETTINGS_KEYS` (otu faịlụ) tupu ịde: paswọọdụ na `currentPassword`, ntinye `SECURITY_IMPACTING_SETTINGS_KEYS` ọ bụla, na ọnọdụ nnọkọ dashboard (`sessionsValidAfter`, `revokedDashboardSessions`). Ya mere, ibubata nkwado ndabere na mpaghara enweghị ike ịtụte nnọkọ nke mgbanwe paswọọdụ ma ọ bụ ọpụpụ akwụsịla.

#### Nhọrọ TOTP nbanye ihe abụọ (#16619)

Debanye aha site na Ntọala → Nche; gbanyụọ ruo mgbe onye ọrụ gbanyere ya (`src/server/auth/dashboardMfa.ts`).

- **Ihe ọ na-ekpuchi:** nbanye paswọọdụ (`POST /api/auth/login`, nke ga-achọ `POST /api/auth/mfa/verify`) na `omniroute connect` (`POST /api/cli/connect`, nke na-ajụ mgbanwe naanị paswọọdụ wee were koodu dị ka `totp`).
- **Ihe ọ na-adịghị ekpuchi:** nbanye OIDC / SSO (`/api/auth/oidc/callback`) anaghị arịọ maka OmniRoute TOTP. Ọ na-adabere na ihe nke abụọ nke onye na-eweta njirimara, yabụ manye MFA na IdP ma ọ bụrụ na agbanyere OIDC.
- **Iweghachite** (ngwaọrụ furu efu, enweghị koodu mgbake fọdụrụ, ma ọ bụ ihe na-enweghị ike ịchọpụta ọzọ, dịka ọmụmaatụ mgbe `STORAGE_ENCRYPTION_KEY` gbanwere):
  1. Jiri `OMNIROUTE_DISABLE_MFA=true` malitegharịa ihe nkesa ahụ.
  2. Na onye ọbịa n'onwe ya (loopback peer and loopback `Host`, dị ka `http://localhost:20128`), jiri paswọọdụ banye. A na-amafe ihe nke abụọ maka mmalite ahụ naanị; mmalite ọ bụla ka chọrọ koodu ahụ.
  3. Na Ntọala → Nche → Gbanyụọ, tinye paswọọdụ wee hapụ koodu ahụ oghere. `POST /api/auth/mfa/disable` na-anabata ahụ na-enweghị `code` naanị mgbe agbanwere mgbanwe na arịrịọ sitere n'aka onye ọbịa; ọ ka na-achọ nnọkọ dashboard na okwuntughe dị ugbu a, ma na-enyocha ya dị ka `auth.mfa.disabled` na `secondFactor: "recovery_switch"`.
  4. Wepụ `OMNIROUTE_DISABLE_MFA`, malitegharịa, wee debanye aha ọzọ ma ọ bụrụ na achọrọ ya.

## Ụdị Route

`src/server/authz/types.ts` kọwapụtara klas atọ; route ọ bụla a na-enweghị ike ịkpebi ya nke ọma na-adabata na `MANAGEMENT`.

| Klas         | Nkọwa                                                                                                                                                          | Ntinye a chọrọ                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| `PUBLIC`     | Route nchekwa doro anya: ịbanye, ịpụ, ọnọdụ, init, health, onboarding bootstrap.                                                                               | Enweghị                                                          |
| `CLIENT_API` | Ọnụ ụzọ na-ejere ozi ihe ngosi: `/api/v1/*`, `/api/v1beta/*`, yana aha ndị ọzọ `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer key mgbe feature flag `REQUIRE_API_KEY` dị irè na-arụ ọrụ |
| `MANAGEMENT` | Peeji dashboard, ntọala, ndị na-enye ọrụ, igodo, ọnụ ụzọ admin na nyocha.                                                                                      | Dashboard session MA ọ bụ Bearer nwere ókè `manage`              |

Omume `MANAGEMENT` ụfọdụ bụ **naanị maka operator**: igodo `manage` adịghị ezu. Ibupu credentials echekwara (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), iweghachi backup n'elu data dị ndụ (`POST /api/db-backups/import` gụnyere `dryRun=true`, `POST /api/db-backups` restore site na id, `POST /api/settings/import-json`), na ibibi ebe iweghachi (`DELETE /api/db-backups` cleanup, na `PATCH /api/db-backups` n'ihi na retention ọ na-echekwa bụ ihe na-eme pruning akpaaka mgbe backup ọ bụla gasịrị) chọrọ dashboard session, onye CLI nke ime ụlọ, ma ọ bụ login akwụsịla. Inye sync token (`POST /api/sync/tokens`) na imepụta `admin` CLI access token (`POST /api/cli/tokens`) chọrọ dashboard session ma ọ bụ onye CLI nke ime ụlọ n'ọnọdụ ịbanye ọ bụla. Igodo API nke ókè ọ bụla na `oma_` access tokens abụghị credentials nke operator: ha na-anata `403` mgbe ọ bụla a chọrọ ya. Nyocha a dị na `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Mgbanwe ntọala ịbanye bụkwa naanị maka operator: `POST /api/settings/require-login` (tọọ paswọọdụ njikwa / gbanwee `requireLogin`) na-anabata credentials ndị a naanị mgbe paswọọdụ dịrị. Oge bootstrap nke mbụ (paswọọdụ adịghị ugbu a) anọghị n'agbanwe, dashboard session ga-ezipụkwa `currentPassword` iji dochie paswọọdụ (`403` mgbe ọ dịghị ma ọ bụ ọ dị njọ, a na-edekọ ya dị ka `settings.update_failed`). CLI nke ime ụlọ na instance nke login akwụsịrị na-ejigide ụzọ nweghachi ma nwee ike itọ paswọọdụ na-enweghị ya, n'ihi na ha abụọ jikọtara na host nwere data directory.

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

Ndị nkụnye eji isi mee ntụkwasị obi (akọwapụtara na `src/server/authz/headers.ts`) bụ** wepụrụ arịrịọ mbata** tupu nhazi — ndị ahịa enweghị ike ibu ụzọ buo `x-omniroute-auth-*` ka ha yie isiokwu.

### Nkwekọrịta iwu

Klas ụzọ ọ bụla nwere amụma na `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — na-alaghachi `allow({ kind: "anonymous", id: "anonymous" })` mgbe niile.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — wepụ ihe na-ebu, kwadoro site na `validateApiKey()`. Ọ ga-adaba na onye na-amaghị aha naanị mgbe enwere nkwarụ njirimara `REQUIRE_API_KEY` dị irè. A na-edozi ọkọlọtọ dị irè site na `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ya mere Dashboard Njirimara ọkọlọtọ na mgbanwe gburugburu ebe obibi na-achịkwa `/api/v1/*`, `/api/v1beta/*`, na aliases mgbe niile; Ọdịda nke solver ada emechie. Na-enye ohere arịrịọ dashboard na ụzọ API onye ahịa (gụnyere `/api/v1/models`, nke katalọgụ ụdị dashboard na-eji). Mgbe etinyere Entra ID SSO, ngalaba SSO na-elekọta onye na-ebu nke bụ ahaziri aha Entra token (ngalaba base64url atọ, `RS*` alg, `kid`).** mbụ** `validateApiKey()` na mkpebi ya bụ — ikpeazụ ọ dịghị mgbe ọ ga-adaba na ụzọ igodo API ma ọ bụ ngalaba na-eweda ya na-amaghị aha, yabụ nkwụsị onye na-enye njirimara enweghị ike ịghọ oghere mepere emepe. Igodo API kwụ ọtọ emetụtaghị ya. Lee [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — na-anabata nnọkọ dashboard, arịrịọ imekọrịta ihe n'ime ime (dakọtara na `/api/providers/[name]/(sync-models|models)`), ma ọ bụ na-amafe kpamkpam ma ọ bụrụ na `isAuthRequired()` lọghachite ụgha. Na-eweghachi 403 (`AUTH_001`) mgbe ihe nrịbama onye na-ebu dị ugbu a mana adịghị mma, 401 ma ọ bụghị. Na-amanyekwa usoro ndị nche ụzọ (LOCAL_ONLY / ALWAYS_PROTECTED) tupu alaka ụlọ ọrụ auth — hụ [Tiers Nchekwa okporo ụzọ](../security/ROUTE_GUARD_TIERS.md). ụzọ LOCAL_ONLY na `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ( taa: `/api/mcp/`) nwere ike ịnweta site na-abụghị loopback mgbe igodo bearer na-ebu oke `manage` ; Ụzọ LOCAL_ONLY ndị ọzọ na-anọgidesi ike-loopback n'agbanyeghị oke.

Amụma na-aga nke ọma na-eji `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` weghachi `AuthSubject`. Ndị na-ahụ maka mgbada nwere ike ịgụ ya site na `assertAuth(request, "CLIENT_API")` na `src/server/authz/assertAuth.ts` kama ịmegharị mgbagha nyocha.

## Ndepụta Ụzọ Ọha

`src/shared/constants/publicApiRoutes.ts` bụ ndepụta ikike doro anya:

E kewara ndepụta ahụ site na** udi** , na nkewa ahụ na-ebu ibu (GHSA-74g9-q8f6-793h): prefix dakọtara na `startsWith()`, ya mere ọ dakọtara na ụzọ ọ bụla dị n'akụkụ na-ekerịta ihe odide ya. `/api/usage/om-usage` dị ka prefix akara `/api/usage/om-usage<anything>` PUBLIC, na-esote kpebiri na `/api/usage/[connectionId]` — onye njikwa na-enweghị nyocha nke ya.

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

Ụzọ na-agụ naanị bụ ọha** naanị** maka ụzọ nchekwa. Mara: `classifyRoute()` na-ewepu `/api/v1/*` na `/api/v1beta/*` na PUBLIC ọdịda-site na — ndị ahụ na-abụkarị `CLIENT_API` yabụ amụma igodo bearer ka na-emetụta.

## Ịgbakwunye Ụzọ Ọhụrụ

### Ụkpụrụ 1 — Endpoint API client nke ọha (Bearer-auth)

A na-ekewa ụzọ ndị dị n’okpuru `/api/v1/` na `/api/v1beta/` dịka `CLIENT_API` na-akpaghị aka. Middleware na-amanye nyocha Bearer; route handlers adịghị mkpa imegharị ya, mana ha nwere ike ịgụ subject ma ọ bụrụ na ọ bara uru.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... loojik handler
}
```

### Ụkpụrụ 2 — Endpoint njikwa (session ma ọ bụ Bearer + manage)

Jiri `requireManagementAuth()` sitere na `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... loojik handler
}
```

`requireManagementAuth()` na-eweghachi `null` mgbe ọ gara nke ọma, ma ọ bụ `Response` njehie JSON:

- 401 `AUTH_001` "Achọrọ nkwenye njirimara" — enweghị credentials ọ bụla
- 403 — Bearer adịghị irè **ma ọ bụ** Bearer dị, mana key enweghị scope `manage` / `admin`

`hasManageScope(scopes)` na-eweghachi true maka `"manage"` ma ọ bụ `"admin"`.

### Ụkpụrụ 3 — Ịgbakwunye na ndepụta nnabata ọha

Họrọ set dịka ọdịdị si dị, ọ bụghị dịka mfe si dị. Otu ụzọ ga-abanye na `PUBLIC_API_ROUTES_EXACT` (ma ọ bụ `PUBLIC_READONLY_CORS_API_ROUTES` ma ọ bụrụ na ọ bụ naanị GET); naanị ezigbo subtree ga-abanye na `PUBLIC_API_ROUTE_PREFIXES`, ọ **ga-ejedebekwa na `/`**. Itinye otu ụzọ na ndepụta prefix na-emekwa ka ụzọ niile dị ya n’akụkụ nke nwere mkpụrụedemede mmalite ndị ahụ bụrụ nke ọha — gụnyere dynamic-segment siblings ndị a ga-agbakwunye n’ọdịnihu (GHSA-74g9-q8f6-793h). Melite unit tests dị na `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` na `tests/unit/authz/classify.test.ts`.

## Scopes

Oghere aha atọ. Nyocha ọ bụla na-agụ naanị eriri nke ya. N'akụkụ,
gụnyere ihe mere `manage` ji ada `scopeMatches` maka `read:compression` na ihe mere
akara ngosi nnweta `read` enweghị ike `PATCH /api/keys/{id}`, bụ
[Oghere aha atọ](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Igodo API na-ebu usoro `scopes` (echekwara dị ka JSON na `api_keys.scopes`, lee `src/lib/db/apiKeys.ts`).

### Oghere njikwa

- `manage` / `admin` — `hasManageScope`. Nnweta onye na-ebu ụzọ na ụzọ API njikwa.
- `mcp:connect`, `self:usage`, `self:account-quota`, na
  `policy:bypass-provider-quota` bụ oghere mgbakwunye kwekọrọ kpọmkwem. Ha nọ ọdụ
  na mpụga `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` na-emepe naanị
  `/api/mcp/` ihe osise na-abụghị loopback.

### Oghere ngwaọrụ MCP

Ndepụta na iwu dakọtara (eriri yiri ya, ma ọ bụ oghere enyere na-ejedebe na `*`):
[Oghere ngwaọrụ MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` na `src/shared/constants/mcpScopes.ts` bụ obere ụdị mbụ,
ọ bụghị ndepụta zuru ezu ahụ. Mmejuputa iwu na-agba ọsọ na
`open-sse/mcp-server/scopeEnforcement.ts` mgbe `resolveCallerScopeContext()`
doziri oghere site na ozi nkwenye MCP, metadata arịrịọ, ma ọ bụ `OMNIROUTE_MCP_SCOPES`.
Ọ na-anọgide na-agbanyụ ma ọ bụrụ na `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Oghere akara ngosi nnweta

`read` / `write` / `admin` na akara ngosi `oma_live_…`, nke `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) depụtara. Ọkwa a na-emetụta naanị
asambodo akara ngosi nnweta. Lee [Nkwenye Njikwa](../guides/MANAGEMENT-AUTH.md).

## Ihe Mgbanwe Chọrọ Ntinye

`isAuthRequired()` na `src/shared/utils/apiAuth.ts` bụ ihe na-ekpebi ma a ga-achịkwa **ntinye ọ bụla** maka ịrịọ:

- `settings.requireLogin === false` → ntinye akwụsịrị n'ozuzu ya, ma e wezụga ọkwa nchekwa mgbe niile (lee [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) na oku ndị na-enye credential ọ na-anabata, nke chọrọ otu credential ahụ dị ka mgbe ịbanye dị na-arụ ọrụ: inye sync tokens, imepụta CLI access tokens n'ókè ọ bụla, na ịmepụta igodo API nwere ókè `manage`/`admin`, ikenye ókè ahụ n'igodo, ma ọ bụ imegharị ma ọ bụ igosi igodo dị otu a (`requireCredentialForManagementScopedKey()` na `src/lib/api/requireManagementAuth.ts`). Igodo inference naanị na-anọ n'emeghe.
- Enweghị paswọọdụ edobere **na** enweghị env var `INITIAL_PASSWORD` → ọnọdụ bootstrap: na-ekwe onboarding wizard na ịrịọ loopback, mana ịrịọ netwọk e kpughere ka chọrọ credentials.
- Njehie DB ọ bụla → na-ada n'ihe mgbochi (secure-by-default).

Ntinye igodo API nke ahịa na-eji `isRequireApiKeyEnabled()` na `src/shared/utils/featureFlags.ts`, ọ bụghị ịgụ `process.env.REQUIRE_API_KEY` kpọm kpọm. Nke a dị mkpa maka instances e debere: ịgbanwe `REQUIRE_API_KEY` na Dashboard → Feature Flags na-echekwa DB override ma nwee mmetụta ozugbo na `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, na nyocha ntinye client-API ndị ọzọ na-ekekọrịta onye enyemaka a. Ọ bụrụ na enweghị ike ịgụ feature flag store, ntinye client API na-ada n'ihe mgbochi ma chọrọ igodo.

## Mgbanwe Na-emebi Ndakọrịta — v3.8.0

Ebe njedebe `/api/v1/agents/tasks/*` na `/api/resilience/model-cooldowns` **chọrọ ugbu a nyocha njirimara njikwa** (commit `588a0333`). Ndị ahịa na-ezibu igodo API nkịtị na-enweghị oke ikike `manage` ga-enweta `403`. Mbugharị: nye igodo ahụ oke ikike `manage` na dashboard API Keys, ma ọ bụ jiri session dashboard nke abanyela.

## Mgbanwe Omume — v3.8.2

`/api/mcp/*` (sava MCP dịpụrụ adịpụ) ka bụ LOCAL_ONLY na ndabara mana ugbu a ọ na-anabata arịrịọ na-abụghị loopback mgbe header `Authorization: Bearer <api-key>` nwere oke ikike `manage`. A na-achịkwa mwepu a kpọmkwem n'ụzọ ọ bụla site na `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` dị na `src/server/authz/routeGuard.ts`; a kpachaara anya mee ka prefix LOCAL_ONLY ibe ya `/api/cli-tools/runtime/*` ghara inwe ike ịgafe mmachi n'ihi na ọ nwere ike ịmalite subprocess ọ bụla. Arịrịọ na-enweghị njirimara e zigara `/api/mcp/*` site na ebe na-abụghị loopback ka ga-enwetakwa `403 LOCAL_ONLY` — ndabara maka ụzọ LOCAL_ONLY ọhụrụ ọ bụla ka bụ naanị-loopback siri ike. Lee [Ọkwa Nchekwa Ụzọ](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Nnwale

- Nnwale unit: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Ndepụta ohere ọha: `tests/unit/public-api-routes.test.ts`.
- Gbaa nnwale lekwasịrị anya: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Ndozigharị

Pipeline na-eji stampụ nzaghachi mgbe niile:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Maka arịrịọ ekwenyesiri ike ndị isi arịrịọ nke elu (handler-side) gụnyekwara:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Jiri `assertAuth(req, expectedClass)` n'ime njikwa — ọ na-atụba `AuthzAssertionError` na koodu `AUTHZ_NOT_INITIALIZED` ma ọ bụrụ na agafere middleware (na-enyere aka ijide nhazi nhazi na ule).

## Hụkwa

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — akara nkwenye maka njedebe ọ bụla
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ndekọ nyocha maka ihe omume nkwenye
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — oghere aha atọ na katalọgụ ngwaọrụ MCP
- Isi mmalite: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
