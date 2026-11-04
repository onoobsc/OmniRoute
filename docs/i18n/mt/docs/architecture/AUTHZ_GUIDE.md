# Authorization Guide (Malti)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Sors ta' verità:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Aġġornat l-aħħar:** 2026-09-22 — in-namespaces tal-iskop jindikaw MCP-SERVER.md

OmniRoute għandu pipeline ta' awtorizzazzjoni konxju mir-rotta li jikkontrolla kull talba tal-API. Il-klassifikazzjoni hija **deterministika** u **fail-closed** — kull ħaġa li ma tistax tiġi kklassifikata tispiċċa bħala `MANAGEMENT` u teħtieġ sessjoni jew token ta' grad ta' ġestjoni. Din il-paġna tispjega l-mudell għall-inġiniera li jżommu rotot jew jiddisinjaw endpoints ġodda.

![Pipeline ta' AuthZ (3 klassijiet ta' rotta + evalwazzjoni tal-politika)](../diagrams/exported/authz-pipeline.svg)

> Sors: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Żewġ Modi Awth

### 1. API Key (Bearer)

Użat għall-klijent OpenAI/Anthropic/Gemini-compatible APIs u ftit rotot ta 'ġestjoni meta ċ-ċavetta għandha l-ambitu `manage`.

```
Authorization: Bearer <api-key>
```

Ivvalidat minn `isValidApiKey()` / `extractApiKey()` `src/sse/services/auth.ts` u esportat mill-ġdid permezz ta' `src/shared/utils/apiAuth.ts`. Il-validatur jaċċetta wkoll il-vars `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env bħala ċwievet passthrough persistenti (ħarġa #1350).

### 2. Dashboard Sessjoni (auth_token cookie)

Għal paġni tad-dashboard u operazzjonijiet amministrattivi.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Cookie hija sessjoni biss meta JWT tivverifika** u** iġorr `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Kull konsumatur tal-cookie (dashboard route guard (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, live server, `/api/settings/require-login`, `/api/auth/status`) jgħaddi minn dak l-helper. Oħrajn JWTs iffirmati `JWT_SECRET` jeżistu — the Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` tokens for key holders — and are never sessions (#13298).

Verifikat minn `isDashboardSessionAuthenticated()` fi `src/shared/utils/apiAuth.ts`. Il-pipeline jġedded awtomatikament iż- JWT meta fadal inqas minn 7 ijiem fil-ħajja tiegħu ta' 30 jum.

Sessjoni tista' wkoll tispiċċa qabel ma jispiċċaw it-30 jum tagħha, għaliex kull minter jgħaddi minn `mintDashboardSessionToken` (ħin tal-ħruġ `iat` u id `jti`) u l-verifikatur jiċċekkja żewġ settings: `sessionsValidAfter`, stabbilit b'bidla fil-password sabiex kull sessjoni maħruġa qabel ma tieqaf tivverifika (il-browser li biddel il-password jieħu cookie ġdida), u `revokedDashboardSessions`, li `POST /api/auth/logout` iżid is-sessjonijiet ffirmati `jti`-out . Sessjonijiet maħduma minn rilaxx antik ma jġorru l-ebda pretensjoni u jibqgħu validi sakemm tinbidel l-ewwel password. Jekk is-settings ma jistgħux jinqraw, is-sessjoni mhix fdata.

Xi rotot ta 'ġestjoni jaċċettaw** jew** mod: cookie OR `Bearer <key>` meta ċ-ċavetta API għandha l-ambitu `manage` (jew `admin`). Dan huwa dak li jippermetti l-fluss tax-xogħol "konfigurabbli permezz ta 'sejħiet API " miżjud f'v3.8.

#### Gejt tal-login OIDC mhux obbligatorju (#6973)

Il-login tal-amministratur tad-dashboard jappoġġja wkoll an** opt-in** OIDC (OpenID Connect) fluss flimkien mal-login tal-password default — password login qatt ma titneħħa, supplimentata biss:

- Disabled sakemm `settings.oidcEnabled === true`** u** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` huma kollha kkonfigurati (Settings → Auth). `GET /api/auth/oidc/login` jirritorna `400` mod ieħor.
- `GET /api/auth/oidc/login` jiskopri ż- `authorization_endpoint` miż `/.well-known/openid-configuration` tal-emittent (taqa' lura għal `<issuer>/authorize`), jibni r-ridirezzjonar URI mit-talba deħlin (`x-forwarded-proto` -aware), u tidderieġi mill-ġdid lejn iż- IdP `state` każwali maħżun f'cookie `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` jivvalida `state`, jiskambja l-kodiċi tal-awtorizzazzjoni, u jivverifika l-firma tat-token ID permezz taż JWKS tal-emittent (`jose`'s `createRemoteJWKSet`, cached per JWKS URI) b'kontrolli `issuer`/`audience`. L-ammissjoni tad-dashboard teħtieġ lista `oidcAllowedSubjects` mhux vojta, politika `oidcAdmissionClaim`, jew it-tnejn. Il-lista tas-suġġetti taqbel `sub` jew `email` biss meta `email_verified === true`. Il-politika tal-pretensjoni fakultattiva tieħu mogħdija tal-pretensjoni ID-token separata minn punti (per eżempju, `realm_access.roles`) u firxa ta 'valuri aċċettati; it-talba riżolta għandha tkun firxa ta' kordi li jkun fihom mill-inqas valur wieħed aċċettat. Jekk iż-żewġ politiki huma kkonfigurati, it-tnejn għandhom jgħaddu. Missing/malformed claims fail closed, u mingħajr ebda politika r-callback jirrifjuta l-login (`not_configured`). Konfigurazzjonijiet eżistenti tas-suġġett biss jibqgħu mhux mibdula.
- Keycloak normalment jimmappa r-rwoli tal-isfera f'tokens ta 'aċċess, mhux neċessarjament tokens ID. Biex tirrikjedi r-rwol tar-realm `admin`, ikkonfigura protokoll mapper għal dan il-klijent li jinkludi `realm_access.roles` fil-**ID token** , imbagħad issettja `oidcAdmissionClaim` għal `{ "path": "realm_access.roles", "values": ["admin"] }`. Iċċekkja t-talba attwali tat-token tal-ID għal dan il-klijent qabel ma tippermetti l-ammissjoni tar-rwol biss; l-applikazzjoni ma taqrax ir-rwoli tat-token tal-aċċess. Ir-rifjut tat-token min-naħa tal-IdP jista’ jissupplimenta iżda ma jissostitwixxix dan il-kontroll min-naħa tal-applikazzjoni.
- Fuq is-suċċess mints il** eżatt l-istess** 30 jum `auth_token` JWT il-kwistjonijiet tal-login tal-password (`src/app/api/auth/login/route.ts`), għalhekk il-bqija tal-pipeline tas-sessjoni tad-dashboard (awto-aġġornament, bnadar tal-cookies) ma nbidlux — OIDC biss jissostitwixxi kif il-cookie tiġi nħadmet, mhux dak li tagħti. Bidliet għal IdP roles/groups ma jinvalidawx is-sessjonijiet eżistenti OmniRoute ; il-logout, ir-rotazzjoni tal-password, jew l-iskadenza tas-sessjoni għadhom jirregolaw il-ħajja tagħhom.
- Kull setting `oidc*` `401 PASSWORD_MISMATCH` `oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) huwa fi `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` iwieġeb `400 PASSWORD_REQUIRED` sakemm il-korp ma jġorrx il-password tal-maniġment meta hija żbaljata bħala `currentPassword`. `oidcDisablePasswordLogin` jirrifjuta l-password _login_ (`POST /api/auth/login`) iżda jżomm il-hash tal-password maħżuna, u re-auth xorta jiċċekkja `currentPassword` kontriha.
- `corsOrigins` u `bruteForceProtection` huma `SECURITY_IMPACTING_SETTINGS_KEYS` ukoll: it-tnaqqis jew idgħajjef id-difiżi tal-login, għalhekk jieħdu l-istess `currentPassword` re-auth (it-tab tas-Sigurtà titlobha) u l-importazzjoni JSON twaqqahom.
- Kull ċavetta tal-politika tas-sigurtà — l-entrati `SECURITY_IMPACTING_SETTINGS_KEYS`, kull ċavetta `oidc*` u l-istat tas-sessjoni tad-dashboard — huwa** operatur biss** fuq `PATCH /api/settings`: ċavetta API b'ambitu ta' ġestjoni jew token ta' aċċess `oma_` tiġi rrifjutata `403` anki meta tibgħat il- `currentPassword` dritt , u r-rifjut jiġi vverifikat bħala `settings.update_failed` bi `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` `src/lib/api/operatorCredential.ts`). Is-settings ordinarji (tema, preferenzi tal-wiri) jibqgħu miktuba għal ċavetta `manage` jew token ta 'aċċess `admin`. Kull mutazzjoni ta' `/api/settings` innifsu (u ta' `/api/settings/require-login`) teħtieġ ukoll l-ambitu tat-token ta' aċċess `admin` (`ADMIN_MUTATION_EXACT_PATHS` `src/server/authz/accessScopes.ts`, match exact-path); `GET` jibqa `read`, u s-subrotot `/api/settings/*` l-oħra (proxies, defaults combo, psewdonimi tal-mudell, kompressjoni, purges...) iżommu l-ambitu `write` dedott mill-metodu.
- `POST /api/settings/import-json` taqbeż dik ir-ri-awth, u għalhekk twaqqa' kull ċavetta `IMPORT_STRIPPED_SETTINGS_KEYS` (l-istess fajl) qabel ma tikteb: il-password u `currentPassword`, kull dħul `SECURITY_IMPACTING_SETTINGS_KEYS`, u l-istat tas-sessjoni tad-dashboard (`sessionsValidAfter`, `revokedDashboardSessions`). L-importazzjoni ta' backup eqdem għalhekk ma tistax terġa' tqajjem sessjoni li bidla fil-password jew ħruġ diġà ntemmet.

#### Login TOTP b'żewġ fatturi mhux obbligatorju (#16619)

Irreġistrat minn Settings → Security; mitfi sakemm l-operatur jixgħelha (`src/server/auth/dashboardMfa.ts`).

- **Dak li jkopri:** login tal-password (`POST /api/auth/login`, li mbagħad jeħtieġ `POST /api/auth/mfa/verify`) u `omniroute connect` (`POST /api/cli/connect`, li jirrifjuta skambju ta' password biss u jieħu l-kodiċi bħala `totp`).
- **Dak li ma jkoprix:** OIDC / SSO sign-in (`/api/auth/oidc/callback`) ma jitlobx għall- OmniRoute TOTP. Jiddependi fuq it-tieni fattur tal-fornitur tal-identità stess, għalhekk infurza MFA fiż IdP jekk OIDC huwa attivat.
- **Irkupru** (apparat mitluf, ma fadal l-ebda kodiċi ta' rkupru, jew fattur li ma jistax jibqa' jiġi vverifikat, pereżempju wara li nbidel `STORAGE_ENCRYPTION_KEY` ):
  1. Ibda mill-ġdid is-server `OMNIROUTE_DISABLE_MFA=true`.
  2. Fuq il-host innifsu (loopback peer u loopback `Host`, bħal `http://localhost:20128`), idħol bil-password. It-tieni fattur jinqabeż għal dik l-oriġini biss; kull oriġini oħra għadha teħtieġ il-kodiċi.
  3. F'Settings → Sigurtà → Iddiżattiva, daħħal il-password u ħalli l-kodiċi vojt. `POST /api/auth/mfa/disable` jaċċetta korp mingħajr `code` biss waqt li l-varjabbli tkun issettjata u t-talba tiġi mill-host; xorta teħtieġ is-sessjoni tad-dashboard u l-password attwali, u hija vverifikata bħala `auth.mfa.disabled` `secondFactor: "recovery_switch"`.
  4. Itfi `OMNIROUTE_DISABLE_MFA`, ibda mill-ġdid, u erġa' irreġistra jekk meħtieġ.

## Klassijiet tar-Rotot

`src/server/authz/types.ts` jiddefinixxi tliet klassijiet; kull rotta li ma tistax tiġi kklassifikata b'mod determinat tirrikorri għal `MANAGEMENT`.

| Klassi       | Deskrizzjoni                                                                                                                                                           | Awtentikazzjoni meħtieġa                                               |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `PUBLIC`     | Rotot tassew sikuri: login, logout, status, init, health, bootstrap tal-onboarding.                                                                                    | Xejn                                                                   |
| `CLIENT_API` | Endpoints għas-servizz tal-mudelli: `/api/v1/*`, `/api/v1beta/*`, flimkien mal-aliases `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer key meta l-feature flag effettiv `REQUIRE_API_KEY` ikun attivat |
| `MANAGEMENT` | Paġni tad-dashboard, settings, providers, ċwievet, endpoints tal-amministrazzjoni u d-dijanjostika.                                                                    | Sessjoni tad-dashboard JEW Bearer bl-iskop `manage`                    |

Xi azzjonijiet ta' `MANAGEMENT` huma **tal-operatur biss**: ċavetta `manage` ma tibqax biżżejjed. L-esportazzjoni ta' credentials maħżuna (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ir-restawr ta' backup fuq id-dejta ħajja (`POST /api/db-backups/import` inkluż `dryRun=true`, `POST /api/db-backups` restore permezz tal-id, `POST /api/settings/import-json`), u l-qerda ta' punti ta' restawr (`DELETE /api/db-backups` cleanup, u `PATCH /api/db-backups` għax ir-retention li jippersisti hija dik li tmexxi l-pruning awtomatiku wara kull backup) jeħtieġu sessjoni tad-dashboard, is-suġġett tas-CLI lokali, jew login diżattivat. Il-ħruġ ta' sync token (`POST /api/sync/tokens`) u l-minting ta' token ta' aċċess CLI `admin` (`POST /api/cli/tokens`) jeħtieġu sessjoni tad-dashboard jew is-suġġett tas-CLI lokali f'kull modalità ta' login. Iċ-ċwievet tal-API ta' kull skop u t-tokens ta' aċċess `oma_` mhumiex credentials tal-operatur: jirċievu `403` kull meta jkun meħtieġ wieħed. Il-verifika tinsab f'`src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Il-bidla tas-settings tal-login hija wkoll tal-operatur biss: `POST /api/settings/require-login` (issettja l-password tal-ġestjoni / ittoggle `requireLogin`) jaċċetta biss dawk il-credentials ladarba jkun hemm password. It-tieqa tal-bootstrap tal-ewwel tmexxija (għadha m'hemmx password) ma tinbidilx, u sessjoni tad-dashboard trid tibgħat `currentPassword` biex tissostitwixxi l-password (`403` meta tkun nieqsa jew ħażina, u tiġi awditjata bħala `settings.update_failed`). Is-CLI lokali u istanza b'login diżattivat iżommu r-rotta tar-rkupru u jistgħu jissettjaw password mingħajrha, għax it-tnejn huma marbuta mal-host li jippossjedi d-data directory.

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

Headers interni affidabbli (definiti `src/server/authz/headers.ts`) huma** imqaxxar minn talbiet deħlin** qabel il-klassifikazzjoni — klijenti ma jistgħux jimtlew minn qabel `x-omniroute-auth-*` biex jippersonaw suġġett.

### Kuntratti ta' politika

Kull klassi tar-rotta għandha politika fi `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — dejjem jirritorna `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — estratti Bearer, jivvalida permezz ta `validateApiKey()`. Jaqa' għal anonimu biss meta l-bandiera effettiva tal-karatteristika `REQUIRE_API_KEY` tkun diżattivata. Il-bandiera effettiva tiġi solvuta permezz ta' `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) għalhekk il-Bnadar tal-Karatteristiċi tad-Dashboard u l-varjabbli tal-ambjent jirregolaw `/api/v1/*`, `/api/v1beta/*`, u psewdonimi b'mod konsistenti; fallimenti tas-solvent ifallu magħluqa. Jippermetti talbiet għal sessjoni tad-dashboard fuq rotot API tal-klijenti (inkluż `/api/v1/models`, użat mill-katalgu tal-mudell tad-dashboard). Meta Entra ID SSO hija attivata, Bearer li strutturalment huwa token Entra (tliet segmenti base64url, `RS*` alg, `kid`) jiġi mmaniġġjat mill-fergħa SSO** qabel** `validateApiKey()` u l-verdett tiegħu huwa finali — qatt ma jaqa 'fil-mogħdija taċ-ċavetta API jew il-fergħa ta' degradazzjoni għal anonima, għalhekk qtugħ tal-fornitur tal-identità ma jistax isir aċċess miftuħ. Iċ-ċwievet API statiċi mhumiex affettwati. Ara [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — jaċċetta sessjoni tad-dashboard, talbiet interni ta' sinkronizzazzjoni tal-mudell (imqabbla ma' `/api/providers/[name]/(sync-models|models)`), jew jaqbeż kompletament jekk `isAuthRequired()` jirritorna falza. Jirritorna 403 (`AUTH_001`) meta token Bearer ikun preżenti iżda mhux validu, 401 mod ieħor. Jinforza wkoll il-livelli tal-gwardja tar-rotot (LOCAL_ONLY / ALWAYS_PROTECTED) qabel kwalunkwe fergħa ta' awtorizzazzjoni — ara [Livell tal-Gwardja tar-Rotot](../security/ROUTE_GUARD_TIERS.md). Il-mogħdijiet LOCAL_ONLY `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (illum: `/api/mcp/`) jistgħu jiġu aċċessati minn non-loopback meta ċ-ċavetta Bearer iġorr l-ambitu `manage` ; il-mogħdijiet LOCAL_ONLY l-oħra kollha jibqgħu stretta-loopback irrispettivament mill-ambitu.

Poliza ta suċċess tirritorna `AuthSubject` ma `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Maniġers downstream jistgħu jaqrawha permezz ta' `assertAuth(request, "CLIENT_API")` `src/server/authz/assertAuth.ts` minflok ma jerġgħu jħaddmu l-loġika tal-awtentikazzjoni.

## Lista tar-Rotot Pubbliċi

`src/shared/constants/publicApiRoutes.ts` hija l-lista ta' permessi espliċita:

Il-lista hija maqsuma minn** forma** , u l-qasma hija li ġġorr it-tagħbija (GHSA-74g9-q8f6-793h): prefiss huwa mqabbel ma ' `startsWith()`, għalhekk jaqbel ukoll ma' kull mogħdija adjaċenti li taqsam il-karattri ewlenin tagħha. `/api/usage/om-usage` bħala prefiss immarkat `/api/usage/om-usage<anything>` PUBLIC, u Sussegwentement isolvi li biex `/api/usage/[connectionId]` — handler mingħajr awtorizzazzjoni tiegħu stess.

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

Ir-rotot li jinqraw biss huma pubbliċi** biss** għal metodi sikuri. Nota: `classifyRoute()` jeskludi `/api/v1/*` u `/api/v1beta/*` miż- PUBLIC fall-through — dawk huma dejjem `CLIENT_API` għalhekk il-politika Bearer-key għadha tapplika.

## Kif Iżżid Rotta Ġdida

### Mudell 1 — Endpoint pubbliku tal-API tal-klijent (awtentikazzjoni Bearer)

Ir-rotot taħt `/api/v1/` u `/api/v1beta/` jiġu kklassifikati awtomatikament bħala `CLIENT_API`. Il-middleware jinforza l-verifika Bearer; il-handlers tar-rotta m’għandhomx għalfejn jerġgħu jagħmluha, iżda jistgħu jaqraw is-suġġett jekk ikun utli.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... il-loġika tal-handler
}
```

### Mudell 2 — Endpoint ta’ ġestjoni (sessjoni jew Bearer + manage)

Uża `requireManagementAuth()` minn `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... il-loġika tal-handler
}
```

`requireManagementAuth()` tirritorna `null` meta tirnexxi jew `Response` ta’ żball JSON:

- 401 `AUTH_001` "Awtentikazzjoni meħtieġa" — ebda kredenzjali
- 403 — Bearer invalidu **jew** Bearer preżenti iżda ċ-ċavetta m’għandhiex l-ambitu `manage` / `admin`

`hasManageScope(scopes)` tirritorna true għal `"manage"` jew `"admin"`.

### Mudell 3 — Żieda mal-lista pubblika ta’ permessi

Agħżel is-sett skont il-forma, mhux skont il-konvenjenza. Rotta waħda tidħol f’`PUBLIC_API_ROUTES_EXACT` (jew f’`PUBLIC_READONLY_CORS_API_ROUTES` jekk hija GET-only); sottosiġra ġenwina biss tidħol f’`PUBLIC_API_ROUTE_PREFIXES`, u **trid tispiċċa b’`/`**. Jekk tpoġġi rotta individwali fil-lista tal-prefissi, tkun qiegħed tippubblika wkoll kull mogħdija biswitu li taqsam magħha l-karattri inizjali — inklużi rotot aħwa b’segmenti dinamiċi li jiżdiedu aktar tard (GHSA-74g9-q8f6-793h). Aġġorna t-testijiet tal-unità f’`tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` u `tests/unit/authz/classify.test.ts`.

## Scopes

Tliet namespaces. Kull checker jaqra biss is-strings tiegħu stess. Il-paragun, inkluż għaliex `manage` ifalli `scopeMatches` għal `read:compression` u għaliex access token ta' `read` ma jistax `PATCH /api/keys/{id}`, jinsab f'[Tliet namespaces ta' scope](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API keys iġorru array ta' `scopes` (maħżun bħala JSON f'`api_keys.scopes`, ara `src/lib/db/apiKeys.ts`).

### Scope tal-ġestjoni

- `manage` / `admin` — `hasManageScope`. Aċċess bearer għar-rotot tal-API tal-ġestjoni.
- `mcp:connect`, `self:usage`, `self:account-quota`, u `policy:bypass-provider-quota` huma scopes addittivi ta' tqabbil eżatt. Dawn jinsabu barra `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` jiftaħ biss il-`/api/mcp/` carve-out mhux loopback.

### Scopes tal-għodda MCP

Katalogu u regoli ta' tqabbil (string identika, jew scope mogħti li jispiċċa b'`*`): [Scopes tal-għodda MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `MCP_SCOPE_LIST` f'`src/shared/constants/mcpScopes.ts` huwa s-subsett oriġinali tat-tip, mhux dak il-katalogu sħiħ. L-infurzar jaħdem f'`open-sse/mcp-server/scopeEnforcement.ts` wara li `resolveCallerScopeContext()` jsolvi l-scopes mill-informazzjoni tal-awtentikazzjoni tal-MCP, il-metadata tat-talba, jew `OMNIROUTE_MCP_SCOPES`. Jibqa' mitfi sakemm `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Scopes tal-access-token

`read` / `write` / `admin` fuq tokens `oma_live_…`, ikklassifikati minn `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`). Din il-klassifikazzjoni tapplika għall-kredenzjali tal-access token biss. Ara [Awtentikazzjoni tal-Ġestjoni](../guides/MANAGEMENT-AUTH.md).

## Toggle tal-Awtentikazzjoni Meħtieġa

`isAuthRequired()` f'`src/shared/utils/apiAuth.ts` hija dik li tiddeċiedi jekk awtentikazzjoni **kwalunkwe** tiġix infurzata għal talba:

- `settings.requireLogin === false` → l-awtentikazzjoni hija diżattivata globalment, ħlief għall-livell dejjem protett (ara [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) u s-sejħiet li jagħtu credential li hija taċċetta, li jeħtieġu l-istess credential bħal meta l-login ikun attivat: il-ħruġ ta' sync tokens, il-minting ta' tokens ta' aċċess CLI fi kwalunkwe skop, u l-ħolqien ta' ċavetta API bl-iskop `manage`/`admin`, l-għoti ta' dak l-iskop lil ċavetta, jew l-iġġenerar mill-ġdid jew l-uri ta' ċavetta bħal din (`requireCredentialForManagementScopedKey()` f'`src/lib/api/requireManagementAuth.ts`). Iċ-ċwievet inference biss jibqgħu miftuħa.
- Ebda password ma hi kkonfigurata **u** ebda varjabbli tal-ambjent `INITIAL_PASSWORD` → modalità bootstrap: tippermetti l-onboarding wizard u t-talbiet loopback, iżda t-talbiet tan-network esposti xorta jeħtieġu credentials.
- Kull DB error → jifalli fil-mod sikur (secure-by-default).

L-infurzar tač-ċavetta tal-API tal-klijent juża `isRequireApiKeyEnabled()` f'`src/shared/utils/featureFlags.ts`, mhux qari dirett ta' `process.env.REQUIRE_API_KEY`. Dan huwa importanti għal istanzi mqiegħda f'produzzjoni: it-tibdil ta' `REQUIRE_API_KEY` fid-Dashboard → Feature Flags jaħżen DB override u immedjatament jaffettwa `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, u l-kontrolli l-oħra tal-awtentikazzjoni tal-client-API li jaqsmu dan l-helper. Jekk il-feature flag store ma jkunx jista' jinqara, l-awtentikazzjoni tal-client API tifalli fil-mod sikur u titlob ċavetta.

## Bidla li Tkisser il-Kompatibbiltà — v3.8.0

L-endpoints `/api/v1/agents/tasks/*` u `/api/resilience/model-cooldowns` **issa jeħtieġu awtentikazzjoni tal-ġestjoni** (commit `588a0333`). Klijenti li qabel kienu jibagħtu ċavetta tal-API normali mingħajr l-ambitu `manage` jirċievu `403`. Migrazzjoni: jew assenja l-ambitu `manage` liċ-ċavetta fid-dashboard API Keys, jew uża sessjoni tad-dashboard illoggjata.

## Bidla fl-Imġiba — v3.8.2

`/api/mcp/*` (is-server remot tal-MCP) għadu LOCAL_ONLY b’mod awtomatiku, iżda issa jaċċetta talbiet mhux loopback meta l-header `Authorization: Bearer <api-key>` ikun fih l-ambitu `manage`. L-eċċezzjoni hija kkontrollata espliċitament għal kull path permezz ta’ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` f’`src/server/authz/routeGuard.ts`; il-prefiss LOCAL_ONLY relatat `/api/cli-tools/runtime/*` intenzjonalment ma jistax jiġi bypassed għax jista’ jniedi subproċessi arbitrarji. Talbiet anonimi lejn `/api/mcp/*` minn konnessjonijiet mhux loopback jibqgħu jirritornaw `403 LOCAL_ONLY` — l-imġiba awtomatika għal kull path LOCAL_ONLY ġdid tibqa’ strict-loopback. Ara [Livelli tal-Gwardja tar-Rotot](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Ittestjar

- Testijiet tal-unità: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Lista ta’ permessi pubbliċi: `tests/unit/public-api-routes.test.ts`.
- Ħaddem test speċifiku: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Debugging

Il-pipeline dejjem ittimbra t-tweġibiet bi:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Għal talbiet awtentikati l-intestaturi tar-rikjesti upstream (min-naħa tal-handler) jinkludu wkoll:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Uża `assertAuth(req, expectedClass)` ġewwa handlers — tarmi `AuthzAssertionError` bil-kodiċi `AUTHZ_NOT_INITIALIZED` jekk il-middleware ġie bypassed (tgħajjef biex taqbad ir-rigressjonijiet tal-konfigurazzjoni fit-testijiet).

## Ara wkoll

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — markatur tal-awtentikazzjoni għal kull endpoint
- [COMPLIANCE.md](../security/COMPLIANCE.md) — reġistru tal-awditjar għall-avvenimenti tal-awtentikazzjoni
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tliet spazji tal-ismijiet tal-ambitu u katalgu tal-ambitu tal-għodda tal-MCP
- Sors: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
