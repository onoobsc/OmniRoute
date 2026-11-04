# Authorization Guide (Gaeilge)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Foinse na fírinne:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Nuashonraithe go deireanach:** 2026-09-22 — dírithe ar MCP-SERVER.md

Tá píblíne údaraithe atá feasach ar bhealaí ag OmniRoute a chuireann bac ar gach iarratas API. Tá an aicmiú **cinntitheach** agus **teip-dúnta** — críochnaíonn aon rud nach féidir a aicmiú mar `MANAGEMENT` agus éilíonn sé seisiún nó comhartha grád bainistíochta. Míníonn an leathanach seo an tsamhail d'innealtóirí a chothabhálann bealaí nó a dhearann críochphointí nua.

![Píblíne AuthZ (3 aicme bealaigh + meastóireacht beartais)](../diagrams/exported/authz-pipeline.svg)

> Foinse: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dhá Mhodh Údar

### 1. API Eochair (Iompróir)

Úsáidtear é don OpenAI/Anthropic/Gemini-compatible cliant APIs agus cúpla bealach bainistíochta nuair a bhíonn an raon feidhme `manage` ag an eochair.

```
Authorization: Bearer <api-key>
```

Bailíochtaithe ag `isValidApiKey()` / `extractApiKey()` in `src/sse/services/auth.ts` agus ath-onnmhairithe trí `src/shared/utils/apiAuth.ts`. Glacann an bailíochtóir freisin leis na `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars mar eochracha leanúnacha pastrí (eisiúint #1350).

### 2. Seisiún Deais (fianán auth_token)

Le haghaidh leathanaigh deais agus oibríochtaí riaracháin.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Ní seisiún é fianán ach amháin nuair a fhíoraíonn an JWT** agus** iompraíonn `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Téann gach tomhaltóir den fhianán (garda bealaigh painéal (`isDashboardSessionAuthenticated()`), athnuachan píblíne authz, croitheadh láimhe WebSocket, freastalaí beo, `/api/settings/require-login`, `/api/auth/status`) tríd an gcúntóir sin. Tá JWTs eile sínithe le `JWT_SECRET` ann — an Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` comharthaí do shealbhóirí eochrach — agus ní seisiúin iad riamh (#13298).

Deimhnithe ag `isDashboardSessionAuthenticated()` in `src/shared/utils/apiAuth.ts`. Déanann an phíblíne an JWT a athnuachan go huathoibríoch nuair a bhíonn níos lú ná 7 lá fágtha aige ina shaolré 30 lá.

Is féidir le seisiún críochnú freisin sula mbeidh a 30 lá suas, mar go dtéann gach minter trí `mintDashboardSessionToken` (am eisiúna `iat` agus id `jti`) agus seiceálann an fíoraitheoir dhá shocrú: `sessionsValidAfter`, socraithe ag athrú pasfhocal agus mar sin gach seisiún a eisítear sula stopann sé ag fíorú (faigheann an brabhsálaí a d'athraigh an focal faire fianán úr), agus `revokedDashboardSessions`, a gcuireann `POST /api/auth/logout` na seisiúin sínithe- `jti` leis. Ní bhíonn éileamh ar sheisiúin a mbíonn eisiúint níos sine acu agus ní fhanann siad bailí go dtí go n-athraítear an chéad phasfhocal. Mura féidir na socruithe a léamh, ní chuirtear muinín sa seisiún.

Glacann roinnt bealaí bainistíochta** ach an oiread** mód: fianán OR `Bearer <key>` nuair a bhíonn an scóip `manage` (nó `admin`) ag an eochair API. Is é seo a chuireann ar chumas an sreabhadh oibre “configurable via API calls” a chuirtear leis in v3.8.

#### Geata logáil isteach roghnach OIDC (#6973)

Tacaíonn logáil isteach admin an deais freisin le** rogha an diúltaithe** sreabhadh OIDC (OpenID Connect) taobh le logáil isteach an phasfhocail réamhshocraithe ní bhaintear logáil isteach pasfhocail — riamh, ní chuirtear leis ach:

- Díchumasaithe mura `settings.oidcEnabled === true`** agus** Tá `oidcIssuer` / `oidcClientId` / `oidcClientSecret` uile cumraithe (Socruithe → Auth). filleann `GET /api/auth/oidc/login` `400` ar shlí eile.
- aimsíonn `GET /api/auth/oidc/login` an `authorization_endpoint` ó `/.well-known/openid-configuration` an eisitheora (titeann sé ar ais go `<issuer>/authorize`), tógann sé an URI athsheolaidh ón iarratas isteach (`x-forwarded-proto` -aware), agus atreoraíonn sé chuig an IdP le `state` randamach atá stóráilte i bhfianán `httpOnly` `oidc_state`.
- bailíochtaíonn `GET /api/auth/oidc/callback` `state`, malartaíonn sé an cód údaraithe, agus fíoraíonn sé síniú an chomhartha ID trí JWKS an eisitheora (`jose`'s `createRemoteJWKSet`, i dtaisce in aghaidh JWKS URI) le seiceálacha `issuer`/`audience`. Teastaíonn liosta `oidcAllowedSubjects` neamhfholamh, polasaí `oidcAdmissionClaim`, nó an dá cheann chun ligean isteach ar an bpainéal. Ní mheaitseálann an liosta ábhar `sub` nó `email` ach amháin nuair a `email_verified === true`. Glacann an beartas um éileamh roghnach cosán éilimh idirscartha poncanna aitheantais (mar shampla, `realm_access.roles`) agus raon de luachanna glactha; caithfidh an t-éileamh réitithe a bheith ina shraith teaghráin ina bhfuil luach inghlactha amháin ar a laghad. Má tá an dá pholasaí cumraithe, caithfidh an dá cheann pas a fháil. Teipeann ar éilimh Missing/malformed dúnta, agus gan ceachtar polasaí diúltóidh an glao ar ais logáil isteach (`not_configured`). Níl aon athrú ar na cumraíochtaí ábhair atá ann cheana féin.
- Go hiondúil mapálann Keycloak róil fearainn ina chomharthaí rochtana, ní gá gur comharthaí ID iad. Chun an ról fearainn `admin` a éileamh , cumraigh mapálaí prótacail don chliant seo a chuimsíonn `realm_access.roles` ina** comhartha ID** , ansin socraigh `oidcAdmissionClaim` go `{ "path": "realm_access.roles", "values": ["admin"] }`. Seiceáil an t-éileamh dearbhán aitheantais don chliant seo sula gceadaítear ligean isteach ról-amháin; ní léann an feidhmchlár róil chomhartha rochtana. Is féidir le diúltú comharthaí IdP-taobh a fhorlíonadh ach ní thagann sé in ionad an tseiceáil taobh iarratais seo.
- Ar rath miontaíonn sé an** cruinn céanna** 30-lá `auth_token` JWT eisíonn an logáil isteach pasfhocal (`src/app/api/auth/login/route.ts`), mar sin níl aon athrú ar an gcuid eile den phíblíne seisiúin deais (uath-athnuachan, bratacha fianán) — Ní thagann OIDC ach in ionad an chaoi a ndéantar an fianán a bhualadh, ní cad a dheonaíonn sé. Ní dhéanann athruithe ar IdP roles/groups seisiúin OmniRoute atá ann cheana féin ó bhail; rialaíonn logáil amach, rothlú pasfhocail, nó dul in éag seisiún a saolré fós.
- Tá gach socrú `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) i `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): freagraíonn `PATCH /api/settings` `400 PASSWORD_REQUIRED` mura n-iompraíonn an comhlacht an focal faire bainistíochta mar `currentPassword` (`401 PASSWORD_MISMATCH` nuair atá sé mícheart). diúltaíonn `oidcDisablePasswordLogin` do phasfhocal _login_ (`POST /api/auth/login`) ach coinníonn sé an hash phasfhocal stóráilte, agus seiceálann re-auth `currentPassword` ina choinne fós.
- Tá `corsOrigins` agus `bruteForceProtection` i `SECURITY_IMPACTING_SETTINGS_KEYS` freisin: má scaoiltear ceachtar lagaíonn sé na cosaintí logáil isteach, mar sin glacann siad an t-athúdar `currentPassword` céanna (iarrann an cluaisín Slándála é) agus titeann an t-allmhairiú JSON orthu.
- Tá gach eochair bheartais slándála — na hiontrálacha `SECURITY_IMPACTING_SETTINGS_KEYS`, gach eochair `oidc*` agus staid an tseisiúin deais —** oibreoir-amháin** ar `PATCH /api/settings`: diúltaítear eochair API bainistithe nó comhartha rochtana `oma_` le `403` fiú nuair a sheolann sé an `currentPassword` ceart , agus déantar iniúchadh ar an diúltú mar `settings.update_failed` le `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`). Fanann gnáthshocruithe (téama, sainroghanna taispeána) inscríofa le haghaidh eochair `manage` nó comhartha rochtana `admin`. Ní mór do gach sóchán de `/api/settings` féin (agus de `/api/settings/require-login`) freisin an `admin` rochtain-chomhartha scóip (`ADMIN_MUTATION_EXACT_PATHS` i `src/server/authz/accessScopes.ts`, cruinn-cosán mheaitseáil); fanann `GET` `read`, agus coimeádann na fobhealaí `/api/settings/*` eile (seachfhreastalaí, mainneachtainí teaglama, ailiasanna múnla, comhbhrú, purgóidí ...) an raon feidhme `write` modh-tátail.
- scipeann `POST /api/settings/import-json` an ath-auth sin, mar sin titeann sé gach eochair i `IMPORT_STRIPPED_SETTINGS_KEYS` (comhad céanna) sula scríobhtar: an focal faire agus `currentPassword`, gach iontráil `SECURITY_IMPACTING_SETTINGS_KEYS`, agus staid an tseisiúin deais (`sessionsValidAfter`, `revokedDashboardSessions`). Ní féidir, mar sin, má dhéantar cúltaca níos sine a iompórtáil, seisiún a tháinig deireadh le hathrú pasfhocal nó síniú amach cheana féin.

#### Logáil isteach roghnach dhá fhachtóir TOTP (#16619)

Arna chlárú ó Socruithe → Security; as go dtí go gcuireann an t-oibreoir ar siúl é (`src/server/auth/dashboardMfa.ts`).

- **Cad a chlúdaíonn sé:** logáil isteach pasfhocal (`POST /api/auth/login`, a bhfuil gá ansin `POST /api/auth/mfa/verify`) agus `omniroute connect` (`POST /api/cli/connect`, a dhiúltóidh malartú pasfhocal amháin agus a thógann an cód mar `totp`).
- **Rud nach gclúdaíonn sé:** Ní iarrann síniú isteach OIDC / SSO (`/api/auth/oidc/callback`) an OmniRoute TOTP. Braitheann sé ar dhara fachtóir an tsoláthraí aitheantais féin, mar sin cuir MFA i bhfeidhm sa IdP má tá OIDC cumasaithe.
- **Aisghabháil** (feiste caillte, gan aon cóid aisghabhála fágtha, nó fachtóir nach féidir a fhíorú a thuilleadh, mar shampla tar éis `STORAGE_ENCRYPTION_KEY` athrú):
  1. Atosaigh an freastalaí le `OMNIROUTE_DISABLE_MFA=true`.
  2. Ar an ósta féin ( piaraí loopback agus loopback `Host`, mar shampla `http://localhost:20128`), sínigh isteach leis an bhfocal faire. Léirítear an dara fachtóir don tionscnamh sin amháin; tá an cód fós ag teastáil ó gach tionscnamh eile.
  3. I Socruithe → Security → Díchumasaigh, cuir isteach an focal faire agus fág an cód bán. glacann `POST /api/auth/mfa/disable` comhlacht gan `code` ach amháin cé go bhfuil an athróg socraithe agus tagann an iarraidh ón ósta; tá an seisiún deais agus an pasfhocal reatha de dhíth air fós, agus déantar é a iniúchadh mar `auth.mfa.disabled` le `secondFactor: "recovery_switch"`.
  4. Díshocraigh `OMNIROUTE_DISABLE_MFA`, atosú, agus cláraigh arís más gá.

## Catagóirí Bealaí

Sainíonn `src/server/authz/types.ts` trí chatagóir; titeann aon bhealach nach féidir a aicmiú go cinntitheach ar ais go `MANAGEMENT`.

| Catagóir     | Cur síos                                                                                                                                                  | Fíordheimhniú riachtanach                                                          |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `PUBLIC`     | Bealaí atá sábháilte go sainiúil: logáil isteach, logáil amach, stádas, init, sláinte, bootstrap onboarding.                                              | Dada                                                                               |
| `CLIENT_API` | Críochphointí freastail samhla: `/api/v1/*`, `/api/v1beta/*`, agus ailias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Eochair Bearer nuair a bhíonn bratach gné `REQUIRE_API_KEY` éifeachtach cumasaithe |
| `MANAGEMENT` | Leathanaigh dashboard, socruithe, soláthraithe, eochracha, críochphointí riaracháin agus diagnóisicí.                                                     | Seisiún dashboard NÓ Bearer le scóip `manage`                                      |

Is **gníomhartha oibreora-amháin** cuid de ghníomhartha `MANAGEMENT`: ní leor eochair `manage`. Éilíonn easpórtáil creidiúintí stóráilte (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), cúltaca a athchur os cionn na sonraí beo (`POST /api/db-backups/import` lena n-áirítear `dryRun=true`, `POST /api/db-backups` athchóiriú de réir aitheantais, `POST /api/settings/import-json`), agus pointí athchóirithe a scriosadh (`DELETE /api/db-backups` glanadh, agus `PATCH /api/db-backups` toisc go dtiomáineann an coinneáil a shábhálann sé an glanadh uathoibríoch tar éis gach cúltaca) seisiún dashboard, ábhar CLI áitiúil, nó logáil isteach díchumasaithe. Éilíonn tocán sioncrónaithe a eisiúint (`POST /api/sync/tokens`) agus tocán rochtana CLI `admin` a bhathú (`POST /api/cli/tokens`) seisiún dashboard nó ábhar CLI áitiúil i ngach modh logála isteach. Ní creidiúintí oibreora iad eochracha API de scóip ar bith ná tocáin rochtana `oma_`: faigheann siad `403` aon uair a éilítear ceann. Tá an seiceáil i `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Is oibreora-amháin freisin athrú ar shocruithe logála isteach: glacann `POST /api/settings/require-login` (pasfhocal riaracháin a shocrú / `requireLogin` a scor/a chasadh) leis na creidiúintí sin amháin a luaithe a bhíonn pasfhocal ann. Fanann fuinneog bootstrap na chéad rite (gan pasfhocal fós) gan athrú, agus caithfidh seisiún dashboard `currentPassword` a sheoladh chun an pasfhocal a athsholáthar (`403` nuair a bhíonn sé ar iarraidh nó mícheart, agus iniúchtar mar `settings.update_failed` é). Coinníonn an CLI áitiúil agus ocáid a bhfuil logáil isteach díchumasaithe aici an bealach athshlánúcháin agus féadfaidh sí pasfhocal a shocrú gan é, toisc go bhfuil an bheirt acu faoi cheangal leis an óstach a bhfuil an data directory aige.

## Píblíne

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

Is iad ceanntásca inmheánacha iontaofa (arna sainmhíniú in `src/server/authz/headers.ts`).** bainte ó iarratais ag teacht isteach** roimh rangú ní féidir le cliaint — `x-omniroute-auth-*` a réamhdhaonra chun aithris a dhéanamh ar ábhar.

### Conarthaí beartais

Tá polasaí ag gach rang bealaigh i `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) Filleann — `allow({ kind: "anonymous", id: "anonymous" })` i gcónaí .
- **`clientApiPolicy`** (`policies/clientApi.ts`) sleachta — Iompróir, bailíochtaíonn sé trí `validateApiKey()`. Ní thagann sé gan ainm ach amháin nuair atá an bhratach gné `REQUIRE_API_KEY` éifeachtach díchumasaithe. Réitítear an bhratach éifeachtach trí `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) agus mar sin rialaíonn Bratacha Gné an Deais agus athróga timpeallachta `/api/v1/*`, `/api/v1beta/*`, agus ailiasanna go comhsheasmhach; teipeanna réititheora dúnta. Ceadaíonn sé iarratais ar sheisiún deais ar bhealaí API cliant (lena n-áirítear `/api/v1/models`, a úsáideann catalóg mhúnla an deais). Nuair atá Entra ID SSO cumasaithe, láimhseálann an brainse SSO Iompróir atá ina chomhartha Entra go struchtúrach (trí dheighleog base64url, `RS*` alg, `kid`)** roimhe** `validateApiKey()` agus is é an fíorasc deiridh — ní thiteann sé riamh go dtí an cosán API-eochair nó an brainse díghrádaithe go anaithnid, mar sin ní féidir briseadh soláthraí aitheantais a bheith ina rochtain oscailte. Níl aon tionchar ar eochracha statach API. Féach [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) glacann — le seisiún deais, iarratais ar shioncronú múnla inmheánach (mar a mheaitseáiltear le `/api/providers/[name]/(sync-models|models)`), nó scipeann sé go hiomlán má fhilleann `isAuthRequired()` bréagach. Filleann sé 403 (`AUTH_001`) nuair a bhíonn comhartha Iompróra i láthair ach neamhbhailí, 401 murach é. Chomh maith leis sin cuireann sé i bhfeidhm na sraitheanna garda bealaigh (LOCAL_ONLY / ALWAYS_PROTECTED) roimh aon bhrainse údaráis — féach [Sraitheanna Garda Bealaigh](../security/ROUTE_GUARD_TIERS.md). Is féidir cosáin LOCAL_ONLY i `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (lá atá inniu ann: `/api/mcp/`) a rochtain ó neamh-lúb nuair a iompraíonn an eochair Iompróir an raon feidhme `manage` ; fanann gach cosán LOCAL_ONLY eile docht-lúb beag beann ar raon feidhme.

Tugann polasaí rathúil `AuthSubject` le `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Is féidir le láimhseálaithe iartheachtacha é a léamh trí `assertAuth(request, "CLIENT_API")` in `src/server/authz/assertAuth.ts` in ionad loighic an údair a athrith.

## Liosta Bealaí Poiblí

Is é `src/shared/constants/publicApiRoutes.ts` an ceadliosta sainráite:

Tá an liosta roinnte de réir** cruth** , agus tá an scoilt ualachiompartha (GHSA-74g9-q8f6-793h): déantar réimír a mheaitseáil le `startsWith()`, mar sin de réir mar a mheaitseálann sé gach cosán in aice láimhe agus na príomhcharachtair á roinnt aige. `/api/usage/om-usage` mar réimír marcáilte `/api/usage/om-usage<anything>` PUBLIC, agus socraíonn Next go `/api/usage/[connectionId]` — láimhseálaí gan aon údarás dá chuid féin.

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

Tá bealaí inléite amháin poiblí** amháin** le haghaidh modhanna sábháilte. Nóta: ní áirítear `classifyRoute()` `/api/v1/*` agus `/api/v1beta/*` ón PUBLIC titim-trí — iad siúd atá i gcónaí `CLIENT_API` agus mar sin tá feidhm fós ag an mbeartas Iompróra-eochair.

## Bealach Nua a Chur Leis

### Patrún 1 — Críochphointe poiblí API cliaint (fíordheimhniú Bearer)

Aicmítear bealaí faoi `/api/v1/` agus `/api/v1beta/` mar `CLIENT_API` go huathoibríoch. Forfheidhmíonn an lárearraí an tseiceáil Bearer; ní gá do láimhseálaithe bealaigh í a dhéanamh arís, ach is féidir leo an t-ábhar a léamh más úsáideach é.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... loighic an láimhseálaí
}
```

### Patrún 2 — Críochphointe bainistíochta (seisiún nó Bearer + manage)

Úsáid `requireManagementAuth()` ó `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... loighic an láimhseálaí
}
```

Filleann `requireManagementAuth()` `null` ar éirigh leis, nó `Response` earráide JSON:

- 401 `AUTH_001` "Authentication required" — níl aon dintiúir ann ar chor ar bith
- 403 — Bearer neamhbhailí **nó** Bearer i láthair ach níl an raon feidhme `manage` / `admin` ag an eochair

Filleann `hasManageScope(scopes)` true i gcás `"manage"` nó `"admin"`.

### Patrún 3 — Cur leis an liosta ceada poiblí

Roghnaigh an tacar de réir crutha, ní de réir áisiúlachta. Cuirtear bealach aonair in `PUBLIC_API_ROUTES_EXACT` (nó in `PUBLIC_READONLY_CORS_API_ROUTES` más bealach GET-amháin é); ní chuirtear ach fíorfhochraobh in `PUBLIC_API_ROUTE_PREFIXES`, agus **ní mór di críochnú le `/`**. Má chuirtear bealach aonair sa liosta réimíreanna, foilsítear gach cosán cóngarach a bhfuil na carachtair thosaigh chéanna aige freisin — lena n-áirítear siblíní deighleoige dinimiciúla a chuirfear leis níos déanaí (GHSA-74g9-q8f6-793h). Nuashonraigh na tástálacha aonaid ag `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` agus `tests/unit/authz/classify.test.ts`.

## Scóip

Trí spásainm. Ní léann gach seiceálaí ach a shreanga féin. Tá an taobh le taobh,
lena n-áirítear cén fáth a dteipeann ar `manage` `scopeMatches` do `read:compression` agus cén fáth nach féidir le comhartha rochtana `read` `PATCH /api/keys/{id}`, le fáil anseo:
[Trí spásainm scóip](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Bíonn eochracha API ag iompar eagar `scopes` (stóráilte mar JSON i `api_keys.scopes`, féach `src/lib/db/apiKeys.ts`).

### Scóip bhainistíochta

- `manage` / `admin` — `hasManageScope`. Rochtain iompróra ar bhealaí API bainistíochta.
- `mcp:connect`, `self:usage`, `self:account-quota`, agus
  `policy:bypass-provider-quota` is scóip bhreise, chomhfhreagracha iad. Tá siad
  lasmuigh de `MANAGEMENT_API_KEY_SCOPES`. Ní osclaíonn `mcp:connect` ach an
  gearradh amach neamh-lúbchúlaithe `/api/mcp/`.

### Scóip uirlisí MCP

Catalóg agus rialacha meaitseála (sreangán comhionann, nó scóip deonaithe ag críochnú le `*`):
[Scóip uirlisí MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
Is é `MCP_SCOPE_LIST` i `src/shared/constants/mcpScopes.ts` an fochuid chlóscríofa bhunaidh,
ní an chatalóg iomlán sin. Ritheann forfheidhmiú i
`open-sse/mcp-server/scopeEnforcement.ts` tar éis do `resolveCallerScopeContext()`
scóip a réiteach ó fhaisnéis fíordheimhnithe MCP, meiteashonraí iarratais, nó `OMNIROUTE_MCP_SCOPES`.
Fanann sé múchta mura bhfuil `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Scóip chomhartha rochtana

`read` / `write` / `admin` ar chomharthaí `oma_live_…`, rangaithe de réir `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Ní bhaineann an rang seo ach leis an dintiúr
comhartha rochtana. Féach [Fíordheimhniú Bainistíochta](../guides/MANAGEMENT-AUTH.md).

## Aistriú Fíordheimhnithe Riachtanach

Socraíonn `isAuthRequired()` i `src/shared/utils/apiAuth.ts` an ndéanfar **aon** fhíordheimhniú a fhorfheidhmiú d'iarratas:

- `settings.requireLogin === false` → díchumasaítear fíordheimhniú go domhanda, ach amháin an leibhéal cosanta buan (féach [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) agus na glaonna a thugann creidiúint a nglacann sé léi, a éilíonn an creidiúint chéanna mar a éilítear nuair a bhíonn logáil isteach cumasaithe: tocáin sioncrónaithe a eisiúint, tocáin rochtana CLI a mhint ar scóip ar bith, agus eochair API le scóip `manage`/`admin` a chruthú, an scóip sin a thabhairt d'eochair, nó eochair den sórt sin a athghiniúint nó a nochtadh (`requireCredentialForManagementScopedKey()` i `src/lib/api/requireManagementAuth.ts`). Fanann eochracha inference-amháin oscailte.
- Gan pasfhocal cumraithe **agus** gan athraitheach comhshaoil `INITIAL_PASSWORD` → mód bootstrap: ceadaíonn sé an draoi onboarding agus iarratais loopback, ach éilíonn iarratais líonra nochtaithe creidiúintí fós.
- Aon earráid DB → teipeann sé ar dhúnadh (secure-by-default).

Úsáideann forfheidhmiú eochair API an chliaint `isRequireApiKeyEnabled()` i `src/shared/utils/featureFlags.ts`, ní léamh dhíreach ar `process.env.REQUIRE_API_KEY`. Tá sé seo tábhachtach d'ionstraimí a imscaoileadh: nuair a athraítear `REQUIRE_API_KEY` i Dashboard → Feature Flags, stórálann sé forshárú DB agus dar ndóigh bíonn tionchar aige ar `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, agus ar sheiceálacha fíordheimhnithe eile client-API a roinneann an cúntóir seo. Mura féidir stór na mbratach gné a léamh, teipeann ar fhíordheimhniú client API ar dhúnadh agus éilíonn sé eochair.

## Athrú Bristeach — v3.8.0

Teastaíonn fíordheimhniú bainistíochta **anois** ó na críochphointí `/api/v1/agents/tasks/*` agus `/api/resilience/model-cooldowns` (tiomantas `588a0333`). Faigheann cliaint a sheol eochair API ghnáth gan an scóip `manage` roimhe seo freagra `403`. Aistriú: tabhair an scóip `manage` don eochair i ndeais na nEochracha API, nó úsáid seisiún deaise ina bhfuil tú logáilte isteach.

## Athrú Iompraíochta — v3.8.2

Tá `/api/mcp/*` (an cianfhreastalaí MCP) fós LOCAL_ONLY de réir réamhshocraithe, ach glacann sé anois le hiarratais neamh-loopback nuair a bhíonn an scóip `manage` sa cheanntásc `Authorization: Bearer <api-key>`. Geataítear an díolúine go sainráite de réir conair trí `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` in `src/server/authz/routeGuard.ts`; ní féidir dul timpeall ar an réimír ghaolmhar LOCAL_ONLY `/api/cli-tools/runtime/*` d’aon ghnó toisc gur féidir léi fophróisis threallacha a thosú. Leanann iarratais anaithnide chuig `/api/mcp/*` ó fhoinsí neamh-loopback de `403 LOCAL_ONLY` a thabhairt ar ais — is é dian-loopback an réamhshocrú i gcónaí d’aon chonair nua LOCAL_ONLY. Féach [Sraitheanna Garda Bealaigh](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Tástáil

- Tástálacha aonaid: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Liosta ceada poiblí: `tests/unit/public-api-routes.test.ts`.
- Rith dírithe: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Dífhabhtaithe

Stampálann an píblíne freagraí i gcónaí le:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

I gcás iarratais fhíordheimhnithe, áirítear na ceannteidil iarratais in aghaidh an tsrutha (taobh láimhseálaí):

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Bain úsáid as `assertAuth(req, expectedClass)` láimhseálaithe taobh istigh — caitheann sé `AuthzAssertionError` le cód `AUTHZ_NOT_INITIALIZED` má seachnaítear an lárearraí (cabhrach chun aischéimnithe cumraíochta a ghabháil i dtrialacha).

## Féach Freisin

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — marcóir fíordheimhnithe in aghaidh an cheannphointe
- [COMPLIANCE.md](../security/COMPLIANCE.md) — logáil iniúchta d'imeachtaí fíordheimhnithe
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — trí spásainm scóip agus catalóg scóip uirlise MCP
- Foinse: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
