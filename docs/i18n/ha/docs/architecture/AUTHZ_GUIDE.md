# Authorization Guide (Hausa)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Tushen gaskiya:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **An sabunta ta ƙarshe:** 2026-09-22 — sararin samaniya na iyakoki suna nuni zuwa MCP-SERVER.md

OmniRoute yana da tsarin izini mai sanin hanya wanda ke hana kowane buƙatar API. Rarraba yana da **ƙayyadaddun** kuma **mai rufe-kuskure** — duk abin da ba za a iya rarraba shi ba yana ƙarewa a matsayin `MANAGEMENT` kuma yana buƙatar zama ko alamar matakin gudanarwa. Wannan shafin yana bayyana tsarin ga injiniyoyi masu kula da hanyoyi ko masu tsara sabbin wuraren ƙarshe.

![Tsarin AuthZ (ajiye hanyoyi 3 + kimanta manufofi)](../diagrams/exported/authz-pipeline.svg)

> Tushe: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Halayen Tabbatarwa Biyu

### 1. API Key (Bearer)

Ana amfani da OpenAI/Anthropic/Gemini-compatible abokin ciniki APIs da ƴan hanyoyin gudanarwa lokacin da maɓalli yana da iyakar `manage`.

```
Authorization: Bearer <api-key>
```

An inganta ta `isValidApiKey()` / `extractApiKey()` a cikin `src/sse/services/auth.ts` kuma an sake fitar dashi ta hanyar `src/shared/utils/apiAuth.ts`. Mai inganci kuma yana karɓar `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars azaman maɓallan wucewa na dindindin (fitilar #1350).

### 2. Dashboard Sesion (auth_token kuki)

Don shafukan dashboard da ayyukan gudanarwa.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Kuki zama zama ne kawai lokacin da JWT ta tabbatar** kuma** yana ɗauke `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Kowane mabukaci na kuki (mai gadin dashboard hanya (`isDashboardSessionAuthenticated()`), authz bututun refresh, WebSocket musafiha, live uwar garken, `/api/settings/require-login`, `/api/auth/status`) ya bi ta wannan mataimaki. Sauran JWTs da aka rattaba hannu tare da `JWT_SECRET` sun wanzu — da Cursor CLI wucewar mints `iss "omniroute" / aud "cursor-cli"` alamun don maɓalli na — kuma ba zaman zama ba (#13298).

Tabbatar da `isDashboardSessionAuthenticated()` a cikin `src/shared/utils/apiAuth.ts`. Bututun yana sabunta JWT kai tsaye lokacin da ya rage ƙasa da kwanaki 7 a rayuwar sa ta kwanaki 30.

Haka nan zaman yana iya ƙarewa kafin kwanaki 30 ɗinsa su cika, domin kowane minter yana wucewa ta hanyar `mintDashboardSessionToken` (lokacin fitowar `iat` da id `jti`) sai mai tantancewa ya duba saitin guda biyu: `sessionsValidAfter`, saita canza kalmar sirri ta yadda kowane zaman da aka yi kafin ya daina tantancewa (marar binciken da ya canza kalmar sirri yana samun sabon kuki), da `revokedDashboardSessions`, wanda `POST /api/auth/logout` ya ƙara zaman `jti`. Zaɓuɓɓukan da tsofaffin saki suka yi ba su ɗaukar da'awar kuma suna ci gaba da aiki har sai an canza kalmar sirri ta farko. Idan ba za a iya karanta saitunan ba, ba a amince da zaman ba.

Wasu hanyoyin gudanarwa suna karɓa** ko dai** yanayin: kuki OR `Bearer <key>` lokacin da maɓallin API yana da iyakar `manage` (ko `admin`). Wannan shine abin da ke ba da damar "mai daidaitawa ta hanyar kiran API " da aka ƙara a cikin v3.8.

#### Ƙofar shiga OIDC na zaɓi (#6973)

Shigar dashboard admin kuma yana goyan bayan wani** ficewa** OIDC (OpenID Connect) yana gudana tare da tsohowar kalmar sirri shiga — kalmar shiga kalmar sirri ba a taɓa cirewa ba, an ƙara kawai:

- An kashe sai dai idan `settings.oidcEnabled === true`** kuma** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` duk an daidaita su (Saituna → Auth). `GET /api/auth/oidc/login` ya dawo da `400` in ba haka ba.
- `GET /api/auth/oidc/login` yana gano `authorization_endpoint` daga `/.well-known/openid-configuration` mai bayarwa (ya koma `<issuer>/authorize`), yana gina URI turawa daga buƙatun mai shigowa (`x-forwarded-proto` -aware), kuma yana tura IdP tare da `state` bazuwar da aka adana a cikin kuki `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` yana inganta `state`, yana musayar lambar izini, kuma yana tabbatar da sa hannun alamar ID ta hanyar JWKS mai bayarwa (`jose`'s `createRemoteJWKSet`, cached per JWKS URI) tare da cache `issuer`/`audience`. Shigar da dashboard yana buƙatar jerin `oidcAllowedSubjects` mara komai, manufar `oidcAdmissionClaim`, ko duka biyun. Jerin jigo ya yi daidai da `sub` ko `email` kawai lokacin da `email_verified === true`. Manufar da'awar zaɓin tana ɗaukar hanyar da'awar alamar ID-digi-digi (misali, `realm_access.roles`) da ɗimbin ƙima mai ƙima; da'awar da aka warware dole ne ta zama tsararrun igiyoyi masu ɗauke da aƙalla ƙima ɗaya da aka karɓa. Idan an tsara manufofin biyu, duka biyu dole ne su wuce. da'awar Missing/malformed ta kasa rufe, kuma ba tare da ko wanne manufa ba, sake kiran ya ƙi shiga (`not_configured`). Saitunan batu-kawai da ke wanzu suna ci gaba da canzawa.
- Kyawun maɓalli yakan tsara taswirorin daula zuwa alamun samun dama, ba lallai ba ne alamun ID. Don buƙatar aikin `admin`, saita taswirar yarjejeniya don wannan abokin ciniki wanda ya haɗa da `realm_access.roles` a cikin sa.**ID alamar** , sannan saita `oidcAdmissionClaim` zuwa `{ "path": "realm_access.roles", "values": ["admin"] }`. Bincika ainihin da'awar alamar ID na wannan abokin ciniki kafin ba da damar shigar da rawar-kawai; aikace-aikacen ba ya karanta ayyukan alamar shiga. Ƙin alamar alamar IdP na iya ƙarawa amma baya maye gurbin wannan rajistan-gefen aikace-aikacen.
- A nasara shi mints da** daidai daidai** 30-day `auth_token` JWT abubuwan shigar da kalmar sirri (`src/app/api/auth/login/route.ts`), don haka sauran bututun zaman dashboard (sake sabuntawa ta atomatik, tutocin kuki) ba ya canzawa — OIDC kawai ya maye gurbin yadda ake sarrafa kuki, ba abin da yake bayarwa ba. Canje-canje zuwa IdP roles/groups ba sa lalata zaman OmniRoute na yanzu; alamar fita, jujjuya kalmar sirri, ko ƙarewar zaman har yanzu suna gudanar da rayuwarsu.
- Kowane saitin `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) yana cikin `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` yana amsa `400 PASSWORD_REQUIRED` sai dai idan jiki yana ɗaukar kalmar sirrin gudanarwa azaman `currentPassword` (`401 PASSWORD_MISMATCH` lokacin da ba daidai ba). `oidcDisablePasswordLogin` ya ƙi kalmar sirri _login_ (`POST /api/auth/login`) amma yana adana hash ɗin kalmar sirri da aka adana, kuma sake-auth yana bincika `currentPassword` akan sa.
- `corsOrigins` da `bruteForceProtection` suna cikin `SECURITY_IMPACTING_SETTINGS_KEYS` suma: sassautawa ko dai yana raunana garkuwar shiga, don haka sai su ɗauki `currentPassword` ɗin sake sake rubutawa (Tambarin Tsaro ya nemi shi) kuma shigo da JSON ya sauke su.
- Kowane maɓalli-manufofin tsaro — shigarwar `SECURITY_IMPACTING_SETTINGS_KEYS`, kowane maɓallin `oidc*` da zaman dashboard jihar — ne.** ma'aikaci-kawai** akan `PATCH /api/settings`: ana ƙi maɓallin API mai sarrafa-scoped ko alamar samun damar `oma_` tare da `403` ko da ya aiko da `currentPassword` daidai , kuma ƙididdige shi a matsayin `settings.update_failed` tare da `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` a `src/lib/api/operatorCredential.ts`). Saitunan yau da kullun (jigo, zaɓin nuni) zama masu iya rubutawa don maɓallin `manage` ko alamar samun damar `admin`. Kowane maye gurbi na `/api/settings` kanta (da na `/api/settings/require-login`) yana buƙatar madaidaicin ikon isa ga `admin` (`ADMIN_MUTATION_EXACT_PATHS` a cikin `src/server/authz/accessScopes.ts`, daidai-daidaitaccen hanyar); `GET` yana tsayawa `read`, da sauran ƙananan hanyoyin `/api/settings/*` (proxies, combo Predefinicións, laƙabin ƙira, matsawa, sharewa…) kiyaye hanyar-ƙimar `write`.
- `POST /api/settings/import-json` ya tsallake wanda ya sake tabbatarwa, don haka yana sauke kowane maɓalli a cikin `IMPORT_STRIPPED_SETTINGS_KEYS` (fayil iri ɗaya) kafin rubuta: kalmar sirri da `currentPassword`, kowane shigarwar `SECURITY_IMPACTING_SETTINGS_KEYS`, da yanayin zaman dashboard (`sessionsValidAfter`, `revokedDashboardSessions`). Shigo da tsofaffin madadin don haka ba zai iya farfado da zaman da an riga an gama canza kalmar sirri ko fita ba.

#### Zabi TOTP shiga abubuwa biyu (#16619)

Shiga daga Saituna → Tsaro; kashe har sai mai aiki ya kunna shi (`src/server/auth/dashboardMfa.ts`).

- **Abin da ya ƙunshi:** login kalmar sirri (`POST /api/auth/login`, wanda sannan yana buƙatar `POST /api/auth/mfa/verify`) da `omniroute connect` (`POST /api/cli/connect`, wanda ya ƙi musayar kalmar sirri kawai kuma yana ɗaukar lambar azaman `totp`).
- **Abin da ba ya rufe:** shiga OIDC / SSO (`/api/auth/oidc/callback`) baya neman OmniRoute TOTP. Ya dogara da abu na biyu na mai ba da shaida, don haka tilasta MFA a cikin IdP idan an kunna OIDC.
- **Farfadowa** (na'urar da ta ɓace, babu lambobin dawo da da suka rage, ko abin da ba za a iya tabbatar da shi ba, misali bayan an canza `STORAGE_ENCRYPTION_KEY` ):
  1. Sake kunna uwar garken tare da `OMNIROUTE_DISABLE_MFA=true`.
  2. Akan mai masaukin kansa (kwangin madauki da madauki `Host`, kamar `http://localhost:20128`), shiga tare da kalmar wucewa. Abu na biyu an tsallake shi don asalin wannan kawai; kowane asali har yanzu yana buƙatar lambar.
  3. A cikin Saituna → Tsaro → Kashe, shigar da kalmar wucewa kuma bar lambar babu komai. `POST /api/auth/mfa/disable` yana karɓar jiki ba tare da `code` kawai yayin da aka saita mai canzawa kuma buƙatar ta fito daga mai masaukin; har yanzu yana buƙatar zaman dashboard da kalmar sirri na yanzu, kuma ana duba shi azaman `auth.mfa.disabled` tare da `secondFactor: "recovery_switch"`.
  4. Cire `OMNIROUTE_DISABLE_MFA`, sake farawa, kuma sake yin rajista idan an buƙata.

## Nau'ikan Route

`src/server/authz/types.ts` yana bayyana azuzuwa uku; duk route da ba za a iya rarraba shi da tabbaci ba yana komawa zuwa `MANAGEMENT`.

| Aji          | Bayani                                                                                                                                                         | Tabbatarwar da ake buƙata                                           |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| `PUBLIC`     | Hanyoyi masu aminci a bayyane: shiga, fita, matsayi, init, health, bootstrap na onboarding.                                                                    | Babu                                                                |
| `CLIENT_API` | Ƙarshen hidimar samfuri: `/api/v1/*`, `/api/v1beta/*`, tare da sunayen madadin `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer key idan feature flag na `REQUIRE_API_KEY` mai aiki ya kunna |
| `MANAGEMENT` | Shafukan dashboard, saituna, masu bayarwa, maɓalli, ƙarshen admin da bincike.                                                                                  | Zaman dashboard KO Bearer mai iyakar `manage`                       |

Wasu ayyukan `MANAGEMENT` **na operator ne kawai**: maɓallin `manage` bai isa ba. Fitar da credentials da aka adana (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), mayar da backup a kan live data (`POST /api/db-backups/import` har da `dryRun=true`, `POST /api/db-backups` restore ta id, `POST /api/settings/import-json`), da lalata wuraren mayarwa (`DELETE /api/db-backups` cleanup, da `PATCH /api/db-backups` domin retention ɗin da yake ajiyewa shi ne ke tafiyar da pruning na atomatik bayan kowane backup) suna buƙatar zaman dashboard, asusun CLI na gida, ko shiga da aka kashe. Bayar da sync token (`POST /api/sync/tokens`) da ƙirƙirar `admin` CLI access token (`POST /api/cli/tokens`) suna buƙatar zaman dashboard ko asusun CLI na gida a kowane yanayin shiga. Maɓallan API na kowane iyaka da `oma_` access tokens ba credentials na operator ba ne: suna samun `403` duk lokacin da ake buƙatar ɗaya. Ana duba haka a `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Canza saitunan shiga ma na operator ne kawai: `POST /api/settings/require-login` (saita kalmar sirrin gudanarwa / kunna ko kashe `requireLogin`) yana karɓar waɗannan credentials ne kawai da zarar kalmar sirri ta wanzu. Taga bootstrap na farkon gudu (babu kalmar sirri tukuna) ba ta canzawa, kuma zaman dashboard dole ne ya aika `currentPassword` don maye gurbin kalmar sirri (`403` idan ba ta nan ko ba daidai ba ce, kuma ana rubuta ta a matsayin `settings.update_failed`). CLI na gida da instance mai shiga da aka kashe suna riƙe hanyar dawowa kuma suna iya saita kalmar sirri ba tare da ita ba, domin dukkansu an ɗaure su da host ɗin da ke mallakar data directory.

## Bututu

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

Amintattun masu kai na ciki (wanda aka bayyana a cikin `src/server/authz/headers.ts`) sune** cire daga buƙatun masu shigowa** kafin rarraba — abokan ciniki ba za su iya riga-kafin `x-omniroute-auth-*` don kwaikwayi wani batu ba.

### Kwangilolin siyasa

Kowane ajin hanya yana da manufa a cikin `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — kullum yana dawowa `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — yana fitar da Mai ɗaukar nauyi, yana inganta ta hanyar `validateApiKey()`. Faɗuwa zuwa ga wanda ba a san sunansa ba kawai lokacin da aka kashe ingantaccen tutar fasalin `REQUIRE_API_KEY`. Tuta mai inganci ana warware ta ta hanyar `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) don haka Tutoci Siffofin Dashboard da masu canjin yanayi suna sarrafa `/api/v1/*`, `/api/v1beta/*`, da laƙabi akai-akai; gazawar warwarewa ta kasa rufe. Yana ba da damar buƙatun-zaman dashboard akan hanyoyin API abokin ciniki (ciki har da `/api/v1/models`, ke amfani da kundin ƙirar dashboard). Lokacin da aka kunna Entra ID SSO, reshen SSO ne ke kula da mai ɗaukar kaya wanda shine tsarin Entra token (bangaren tushe64url uku, `RS*` alg, `kid`).** kafin** `validateApiKey()` kuma hukuncinsa shine — na ƙarshe ba zai taɓa shiga hanyar API-key ba ko reshe-zuwa-wanda ba a san shi ba, don haka ƙaddamarwar mai ba da shaida ba zai iya zama buɗe hanyar shiga ba. Maɓallan API na tsaye ba su shafa ba. Duba [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — yana karɓar zaman dashboard, buƙatun ƙirar ƙira na ciki (wanda ya dace da `/api/providers/[name]/(sync-models|models)`), ko kuma ya tsallake gaba ɗaya idan `isAuthRequired()` ya dawo ƙarya. Yana dawo da 403 (`AUTH_001`) lokacin da alamar Mai ɗauka ta kasance amma bata aiki, 401 in ba haka ba. Hakanan yana tilasta matakan tsaro na hanya (LOCAL_ONLY / ALWAYS_PROTECTED) kafin kowane reshe na auth — duba [Tiers Guard Route](../security/ROUTE_GUARD_TIERS.md). hanyoyin LOCAL_ONLY a cikin `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (yau: `/api/mcp/`) ana iya samun dama daga waɗanda ba a dawo da su ba lokacin da maɓalli na Bearer ke ɗauke da iyakar `manage` ; duk sauran hanyoyin LOCAL_ONLY sun kasance masu tsattsauran ra'ayi ba tare da la'akari da iyaka ba.

Manufar nasara tana mayar da `AuthSubject` da `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Masu kula da ƙasa za su iya karanta ta ta `assertAuth(request, "CLIENT_API")` a cikin `src/server/authz/assertAuth.ts` maimakon sake gudanar da dabaru na gaskiya.

## Jerin Hanyoyi na Jama'a

`src/shared/constants/publicApiRoutes.ts` shine fiyayyen lissafin izini:

An raba lissafin ta** siffa** , kuma tsaga yana ɗaukar kaya (GHSA-74g9-q8f6-793h): prefix yana daidaita da `startsWith()`, don haka kuma ya dace da kowace hanya kusa da raba manyan haruffa. `/api/usage/om-usage` a matsayin prefix mai alamar `/api/usage/om-usage<anything>` PUBLIC, kuma Na gaba yana ƙulla wannan don `/api/usage/[connectionId]` — mai sarrafa ba tare da ingantaccen nasa ba.

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

Hanyoyin karantawa kawai jama'a ne** kawai** don hanyoyin aminci. Lura: `classifyRoute()` ta keɓance `/api/v1/*` da `/api/v1beta/*` daga faɗuwar PUBLIC ta hanyar — waɗanda koyaushe suke `CLIENT_API` don haka har yanzu manufar maɓalli na Bearer tana aiki.

## Ƙara Sabuwar Hanya

### Tsari na 1 — Endpoint na API na abokin ciniki na jama'a (Bearer-auth)

Hanyoyin da ke ƙarƙashin `/api/v1/` da `/api/v1beta/` ana rarraba su a matsayin `CLIENT_API` ta atomatik. Middleware yana tilasta binciken Bearer; route handlers ba sa buƙatar sake yin sa, amma za su iya karanta subject idan hakan yana da amfani.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... dabarun handler
}
```

### Tsari na 2 — Endpoint na gudanarwa (session ko Bearer + manage)

Yi amfani da `requireManagementAuth()` daga `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... dabarun handler
}
```

`requireManagementAuth()` yana mayar da `null` idan an yi nasara ko kuma kuskuren JSON `Response`:

- 401 `AUTH_001` "Ana buƙatar tantancewa" — babu bayanan tantancewa kwata-kwata
- 403 — Bearer mara inganci **ko** Bearer yana nan amma key ba shi da scope na `manage` / `admin`

`hasManageScope(scopes)` yana mayar da true ga `"manage"` ko `"admin"`.

### Tsari na 3 — Ƙarawa cikin jerin izinin jama'a

Zaɓi set bisa ga siffa, ba bisa ga sauƙi ba. Hanya guda tana shiga `PUBLIC_API_ROUTES_EXACT` (ko `PUBLIC_READONLY_CORS_API_ROUTES` idan GET-kawai ce); babban reshen hanyoyi na ainihi ne kawai zai shiga `PUBLIC_API_ROUTE_PREFIXES`, kuma **dole ne ya ƙare da `/`**. Sanya hanya guda a jerin prefix yana kuma wallafa kowace hanya da ke kusa wadda take da haruffan farko iri ɗaya — har da 'yan'uwan dynamic-segment da za a ƙara daga baya (GHSA-74g9-q8f6-793h). Sabunta gwaje-gwajen unit a `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` da `tests/unit/authz/classify.test.ts`.

## Fadukan Aiki

Fadukan suna uku. Kowane mai dubawa yana karanta nasa zaren ne kawai. Kwatancen,
ciki har da dalilin da yasa `manage` ke kasa `scopeMatches` don `read:compression` da kuma dalilin da yasa alamar shiga `read` ba zai iya `PATCH /api/keys/{id}` ba, yana nan a
[Fadukan suna uku](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Mabudan API suna ɗauke da jeri na `scopes` (an adana su a matsayin JSON a `api_keys.scopes`, duba `src/lib/db/apiKeys.ts`).

### Fadukan Aiki na Gudanarwa

- `manage` / `admin` — `hasManageScope`. Samun damar shiga hanyoyin API na gudanarwa.
- `mcp:connect`, `self:usage`, `self:account-quota`, da
  `policy:bypass-provider-quota` fadukan aiki ne masu ƙari, masu daidai-daidai. Suna waje da `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` yana buɗe kawai `/api/mcp/` wanda ba na madauki ba.

### Fadukan Aiki na Kayan Aikin MCP

Katalog da ka'idojin daidaitawa (zaren daidai, ko fadukan aiki da aka bayar wanda ya ƙare da `*`):
[Fadukan Aiki na Kayan Aikin MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` a `src/shared/constants/mcpScopes.ts` shine ainihin ƙaramin saitin da aka rubuta, ba cikakken katalog ɗin ba. Aiwatarwa yana gudana a
`open-sse/mcp-server/scopeEnforcement.ts` bayan `resolveCallerScopeContext()` ya warware fadukan aiki daga bayanan shiga na MCP, metadata na buƙata, ko `OMNIROUTE_MCP_SCOPES`.
Yana kashe sai dai idan `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Fadukan Aiki na Alamar Shiga

`read` / `write` / `admin` akan alamomin `oma_live_…`, an jera su ta `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Wannan matsayi yana aiki ne kawai ga takardar shaidar alamar shiga. Duba [Tabbatar da Gudanarwa](../guides/MANAGEMENT-AUTH.md).

## Maɓallin Buƙatar Tabbatarwa

`isAuthRequired()` a cikin `src/shared/utils/apiAuth.ts` ne ke yanke shawara ko ana tilasta **kowane** tabbatarwa ga buƙata:

- `settings.requireLogin === false` → an kashe tabbatarwa gaba ɗaya, sai dai matakin kariya koyaushe (duba [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) da kiran da ke ba da takardar shaidar da yake karɓa, waɗanda ke buƙatar takardar shaida ɗaya kamar yadda ake yi lokacin da shiga ke kunne: bayar da sync tokens, ƙirƙirar CLI access tokens a kowane iyaka, da ƙirƙirar maɓallin API mai iyakar `manage`/`admin`, ba da wannan iyaka ga maɓalli, ko sake samar ko nuna irin wannan maɓalli (`requireCredentialForManagementScopedKey()` a `src/lib/api/requireManagementAuth.ts`). Maɓallan inference kawai suna zama a buɗe.
- Babu kalmar sirri da aka saita **kuma** babu env var na `INITIAL_PASSWORD` → yanayin bootstrap: yana barin onboarding wizard da buƙatun loopback, amma buƙatun hanyar sadarwa da aka fallasa har yanzu suna buƙatar takardun shaida.
- Duk kuskuren DB → yana gazawa a rufe (secure-by-default).

Tilasta maɓallin API na abokin ciniki yana amfani da `isRequireApiKeyEnabled()` a `src/shared/utils/featureFlags.ts`, ba karanta `process.env.REQUIRE_API_KEY` kai tsaye ba. Wannan yana da muhimmanci ga instances da aka tura: canza `REQUIRE_API_KEY` a Dashboard → Feature Flags yana adana DB override kuma nan take yana shafar `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, da sauran duba tabbatarwar client-API da ke raba wannan mataimaki. Idan ba a iya karanta feature flag store ba, tabbatarwar client API tana gazawa a rufe kuma tana buƙatar maɓalli.

## Sauyin da ke Karya Daidaituwa — v3.8.0

Wuraren ƙarshen `/api/v1/agents/tasks/*` da `/api/resilience/model-cooldowns` **yanzu suna buƙatar tantancewar gudanarwa** (commit `588a0333`). Abokan ciniki waɗanda a baya suke aika maɓallin API na yau da kullum ba tare da iyakar izinin `manage` ba za su karɓi `403`. Ƙaura: ko dai a bai wa maɓallin iyakar izinin `manage` a cikin dashboard na API Keys, ko kuma a yi amfani da zaman dashboard da aka shiga.

## Sauyin Halayya — v3.8.2

`/api/mcp/*` (uwar garken MCP mai nisa) har yanzu LOCAL_ONLY ne ta tsohuwa, amma yanzu yana karɓar buƙatun da ba na loopback ba idan header na `Authorization: Bearer <api-key>` yana ɗauke da iyakar izinin `manage`. An kayyade wannan keɓancewar a sarari ga kowace hanya ta hanyar `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` a cikin `src/server/authz/routeGuard.ts`; da gangan ba za a iya tsallake ƙawancen prefix na LOCAL_ONLY mai suna `/api/cli-tools/runtime/*` ba, saboda yana iya ƙaddamar da subprocesses na kowace iri. Buƙatun da ba a tantance ba zuwa `/api/mcp/*` daga wajen loopback za su ci gaba da dawo da `403 LOCAL_ONLY` — tsohon ƙa'ida ga kowace sabuwar hanyar LOCAL_ONLY ita ce tsauraran loopback kawai. Duba [Matakan Tsaron Hanya](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Gwaji

- Gwaje-gwajen unit: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Jerin hanyoyin jama'a da aka amince da su: `tests/unit/public-api-routes.test.ts`.
- Gudanar da gwaji takamaimai: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Gyara kurakurai

Bututun yana yin tambari koyaushe tare da:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Don ingantattun buƙatun masu kan buƙatun buƙatun na sama (handler-gefen) suma sun haɗa da:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Yi amfani da `assertAuth(req, expectedClass)` a cikin masu kula da — yana jefa `AuthzAssertionError` tare da lambar `AUTHZ_NOT_INITIALIZED` idan an ketare na'urar tsakiya (taimaka don kama koma bayan daidaitawa a cikin gwaje-gwaje).

## Duba Kuma

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — alama ta izini ga kowane maƙasudi
- [COMPLIANCE.md](../security/COMPLIANCE.md) — rajistan bincike na abubuwan izini
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — sararin suna mai iyakoki uku da kundin kayan aikin MCP
- Tushe: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
