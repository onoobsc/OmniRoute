# Authorization Guide (Lietuvių)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Tiesos šaltinis:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Paskutinį kartą atnaujinta:** 2026-09-22 — aprėpties vardų sritys nurodo į MCP-SERVER.md

OmniRoute turi maršrutą atpažįstančią autorizacijos sistemą, kuri kontroliuoja kiekvieną API užklausą. Klasifikacija yra **deterministinė** ir **uždaroma gedimo atveju** — viskas, kas negali būti klasifikuota, tampa `MANAGEMENT` ir reikalauja sesijos arba valdymo lygio prieigos rakto. Šiame puslapyje paaiškinamas modelis inžinieriams, prižiūrintiems maršrutus arba kuriantiems naujus galinius taškus.

![Autorizacijos sistema (3 maršrutų klasės + politikos vertinimas)](../diagrams/exported/authz-pipeline.svg)

> Šaltinis: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Du autentifikavimo režimai

### 1. API raktas (nešiklis)

Naudojamas OpenAI/Anthropic/Gemini-compatible klientui APIs ir keliems valdymo maršrutams, kai raktas turi `manage` taikymo sritį.

```
Authorization: Bearer <api-key>
```

Patvirtino `isValidApiKey()` / `extractApiKey()` `src/sse/services/auth.ts` ir reeksportavo per `src/shared/utils/apiAuth.ts`. Tikrinimo priemonė taip pat priima `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars kaip nuolatinius perdavimo raktus ( #1350 problema).

### 2. Prietaisų skydelio seansas (auth_token slapukas)

Prietaisų skydelio puslapiams ir administratoriaus operacijoms.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Slapukas yra seansas tik tada, kai JWT patvirtina** ir** neša `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Kiekvienas slapuko vartotojas (prietaisų skydelio maršruto apsauga (`isDashboardSessionAuthenticated()`), autentifikavimo dujotiekio atnaujinimas, WebSocket rankos paspaudimas, tiesioginis serveris, `/api/settings/require-login`, `/api/auth/status`) eina per tą pagalbininką. Kiti JWTs pasirašyti su `JWT_SECRET` egzistuoja — the Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` žetonus raktų turėtojams — ir niekada nėra sesijos (#13298).

Patvirtino `isDashboardSessionAuthenticated()` in `src/shared/utils/apiAuth.ts`. Dujotiekis automatiškai atnaujina JWT kai jam liko mažiau nei 7 dienos per 30 dienų.

Sesija taip pat gali baigtis nepasibaigus 30 dienų, nes kiekvienas kaltuvas pereina `mintDashboardSessionToken` (išdavimo laikas `iat` ir ID `jti`), o tikrintojas patikrina du nustatymus: `sessionsValidAfter`, nustatytas pakeitus slaptažodį, kad kiekviena sesija, išleista prieš nustodama tikrinti (slaptažodį pakeitusi naršyklė gauna naują slapuką), ir `revokedDashboardSessions`-g-out seansai, prie kurių pridedamas `POST /api/auth/logout` `jti`. Seansai, sukurti naudojant senesnį leidimą, nekelia jokių pretenzijų ir galioja iki pirmojo slaptažodžio pakeitimo. Jei nustatymų negalima nuskaityti, seansas nepasitiki.

Kai kurie valdymo maršrutai priimami** arba** režimas: slapukas OR `Bearer <key>` kai API klavišas turi `manage` (arba `admin`) taikymo sritį. Tai įgalina darbo eigą „konfigūruojama naudojant API skambučius“, pridėtą 3.8 versijoje.

#### Pasirenkami OIDC prisijungimo vartai (#6973)

Prietaisų skydelio administratoriaus prisijungimas taip pat palaiko** pasirinkti** OIDC (OpenID Connect) srautas kartu su numatytuoju prisijungimo slaptažodžiu — slaptažodžio prisijungimas niekada nepašalinamas, tik papildomas:

- Išjungtas, nebent `settings.oidcEnabled === true`** ir** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` yra sukonfigūruoti (nustatymai → Auth). `GET /api/auth/oidc/login` grąžina `400` kitaip.
- `GET /api/auth/oidc/login` atranda `authorization_endpoint` iš leidėjo `/.well-known/openid-configuration` (grąžina į `<issuer>/authorize`), sukuria peradresavimo URI iš gaunamos užklausos (`x-forwarded-proto` -aware) ir nukreipia į IdP su atsitiktiniu `state` saugomu `httpOnly` `oidc_state` slapuke.
- `GET /api/auth/oidc/callback` patvirtina `state`, pakeičia autorizacijos kodą ir patikrina ID prieigos rakto parašą per emitento JWKS (`jose`'s `createRemoteJWKSet`, talpykloje per JWKS URI) su `issuer`/`audience` patikrinimais. Norint patekti į prietaisų skydelį, reikia turėti tuščią `oidcAllowedSubjects` sąrašą, `oidcAdmissionClaim` politiką arba abu. Temų sąrašas atitinka `sub` arba `email` tik tada, kai `email_verified === true`. Pasirenkama paraiškos politika naudoja taškais atskirtą ID-žetono paraiškos kelią (pvz., `realm_access.roles`) ir priimtų verčių masyvą; išspręstas reikalavimas turi būti eilučių masyvas, turintis bent vieną priimtą reikšmę. Jei sukonfigūruotos abi strategijos, abi turi atitikti. Missing/malformed pretenzijos nepavyksta uždaryti, o be jokių taisyklių atgalinis skambutis atsisako prisijungti (`not_configured`). Esamos tik temų konfigūracijos išlieka nepakitusios.
- Keycloak paprastai susieja srities vaidmenis į prieigos prieigos raktus, nebūtinai ID prieigos raktus. Norėdami reikalauti srities vaidmens `admin`, sukonfigūruokite šio kliento protokolo atvaizdavimo priemonę, į kurią įtrauktas `realm_access.roles`**ID tokenas** , tada nustatykite `oidcAdmissionClaim` į `{ "path": "realm_access.roles", "values": ["admin"] }`. Prieš įgalindami tik vaidmenų priėmimą, patikrinkite faktinę šio kliento ID-žetono paraišką; programa neskaito prieigos rakto vaidmenų. IdP pusės prieigos rakto atsisakymas gali papildyti, bet nepakeičia šį programos pusės patikrinimą.
- Apie sėkmę ji numato** lygiai tas pats** 30 dienų `auth_token` JWT slaptažodžio prisijungimo problemos (`src/app/api/auth/login/route.ts`), todėl likusi informacijos suvestinės seanso dalis (automatinis atnaujinimas, slapukų žymos) nesikeičia. — OIDC pakeičia tik tai, kaip slapukas sukuriamas, o ne tai, ką jis suteikia. IdP roles/groups pakeitimai nepanaikina esamų OmniRoute seansų; Atsijungimas, slaptažodžio kaitaliojimas arba seanso galiojimo laikas vis tiek priklauso nuo jų veikimo laiko.
- Kiekvienas `oidc*` nustatymas (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) yra `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` atsako `400 PASSWORD_REQUIRED` nebent korpusas neša valdymo slaptažodį (kai neteisingas `currentPassword` `401 PASSWORD_MISMATCH`. `oidcDisablePasswordLogin` atsisako slaptažodžio _login_ (`POST /api/auth/login`), bet išsaugo saugomą slaptažodžio maišą, o pakartotinis autentifikavimas vis tiek tikrina `currentPassword`.
- `corsOrigins` ir `bruteForceProtection` taip pat yra `SECURITY_IMPACTING_SETTINGS_KEYS` : atlaisvinus arba susilpnėja prisijungimo apsauga, todėl jie atlieka tą patį `currentPassword` re-auth (saugumo skirtukas to prašo), o JSON importas jas atmeta.
- Kiekvienas saugos politikos raktas — `SECURITY_IMPACTING_SETTINGS_KEYS` įrašus, kiekvienas `oidc*` raktas ir prietaisų skydelio seanso būsena — yra** tik operatoriui** `PATCH /api/settings`: valdymo apimties API raktas arba `oma_` prieigos raktas atmetamas naudojant `403` net kai jis siunčia tinkamą `currentPassword`, o atsisakymas tikrinamas kaip `settings.update_failed` su `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`). Įprastus nustatymus (temą, rodymo nuostatas) galima įrašyti naudojant `manage` raktą arba `admin` prieigos raktą. Kiekvienai pačiai `/api/settings` (ir `/api/settings/require-login`) mutacijai taip pat reikalinga `admin` prieigos rakto apimtis (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, tikslios kelio atitiktis); `GET` lieka `read`, o kiti `/api/settings/*` antriniai maršrutai (tarpiniai serveriai, kombinuoti numatytieji nustatymai, modelio slapyvardžiai, glaudinimas, išvalymas...) išlaiko metodu nuvestą `write` apimtį.
- `POST /api/settings/import-json` praleidžia tą pakartotinį autentifikavimą, todėl prieš rašydamas atmeta kiekvieną `IMPORT_STRIPPED_SETTINGS_KEYS` (tame pačiame faile) esantį klavišą: slaptažodį ir `currentPassword`, kiekvieną `SECURITY_IMPACTING_SETTINGS_KEYS` įrašą ir prietaisų skydelio seanso būseną (`sessionsValidAfter`, `revokedDashboardSessions`). Todėl senesnės atsarginės kopijos importavimas negali atgaivinti seanso, kai buvo pakeistas slaptažodis arba atsijungimas jau baigėsi.

#### Pasirenkamas TOTP dviejų faktorių prisijungimas (#16619)

Užsiregistravote iš „Settings → Security“; išjungti, kol operatorius jį įjungs (`src/server/auth/dashboardMfa.ts`).

- **Ką jis apima:** prisijungimo slaptažodžiu (`POST /api/auth/login`, kuriam tada reikia `POST /api/auth/mfa/verify`) ir `omniroute connect` (`POST /api/cli/connect`, kuris atsisako keisti tik slaptažodį ir paima kodą kaip `totp`).
- **Kas neapima:** OIDC / SSO prisijungimas (`/api/auth/oidc/callback`) neprašo OmniRoute TOTP. Jis priklauso nuo paties tapatybės teikėjo antruoju veiksniu, todėl IdP įjunkite MFA jei OIDC įjungtas.
- **Atsigavimas** (pamestas įrenginys, neliko atkūrimo kodų arba veiksnys, kurio nebegalima patikrinti, pavyzdžiui, pakeitus `STORAGE_ENCRYPTION_KEY` ):
  1. Iš naujo paleiskite serverį naudodami `OMNIROUTE_DISABLE_MFA=true`.
  2. Pačiame priegloboje (angl. loopback peer ir loopback `Host`, pvz., `http://localhost:20128`) prisijunkite naudodami slaptažodį. Antrasis veiksnys praleidžiamas tik tai kilmei; kiekvienai kitai kilmei vis tiek reikia kodo.
  3. Nustatymuose → Security → Disable įveskite slaptažodį ir palikite kodą tuščią. `POST /api/auth/mfa/disable` priima kūną be `code` tik tada, kai nustatytas kintamasis ir užklausa gaunama iš pagrindinio kompiuterio; jai vis tiek reikalinga prietaisų skydelio sesija ir dabartinis slaptažodis, be to, jis tikrinamas kaip `auth.mfa.disabled` su `secondFactor: "recovery_switch"`.
  4. Atšaukite `OMNIROUTE_DISABLE_MFA` nustatymą, paleiskite iš naujo ir, jei reikia, vėl užsiregistruokite.

## Maršrutų klasės

`src/server/authz/types.ts` apibrėžia tris klases. Bet koks maršrutas, kurio nepavyksta deterministiškai priskirti klasei, numatytai patenka į `MANAGEMENT`.

| Klasė        | Aprašymas                                                                                                                                                               | Reikalingas autentifikavimas                                    |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| `PUBLIC`     | Aiškiai saugūs maršrutai: prisijungimas, atsijungimas, būsena, inicializavimas, sveikatos patikra ir pradinės sąrankos paleidimas.                                      | Nėra                                                            |
| `CLIENT_API` | Modelių aptarnavimo galiniai taškai: `/api/v1/*`, `/api/v1beta/*`, taip pat pseudonimai `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer raktas, kai įjungta funkcijos vėliava `REQUIRE_API_KEY`  |
| `MANAGEMENT` | Valdymo skydelio puslapiai, nustatymai, teikėjai, raktai, administravimo ir diagnostikos galiniai taškai.                                                               | Valdymo skydelio sesija ARBA Bearer su `manage` taikymo sritimi |

Kai kurie `MANAGEMENT` veiksmai yra **tik operatoriui**: vien `manage` raktas nepakanka. Saugomų prisijungimo duomenų eksportas (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), atsarginės kopijos atkūrimas virš dabartinių duomenų (`POST /api/db-backups/import`, įskaitant `dryRun=true`, `POST /api/db-backups` atkūrimas pagal id, `POST /api/settings/import-json`) ir atkūrimo taškų naikinimas (`DELETE /api/db-backups` valymas ir `PATCH /api/db-backups`, nes išsaugota saugojimo trukmė valdo automatinį išvalymą po kiekvienos atsarginės kopijos) reikalauja valdymo skydelio sesijos, vietinio CLI tapatybės arba kad prisijungimas būtų išjungtas. Sinchronizavimo žetono išdavimas (`POST /api/sync/tokens`) ir `admin` taikymo srities CLI prieigos žetono kūrimas (`POST /api/cli/tokens`) reikalauja valdymo skydelio sesijos arba vietinio CLI tapatybės visuose prisijungimo režimuose. API raktai bet kurios taikymo srities ir `oma_` prieigos žetonai nėra operatoriaus prisijungimo duomenys: kai jų reikia, jie gauna `403`. Patikra yra faile `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Prisijungimo nustatymų keitimas taip pat tik operatoriui: `POST /api/settings/require-login` (nustatyti administravimo slaptažodį / perjungti `requireLogin`) priima tik šiuos prisijungimo duomenis, kai slaptažodis jau yra. Pirminio paleidimo bootstrap langas (slaptažodžio dar nėra) lieka nepakitęs, o valdymo skydelio sesija, norėdama pakeisti slaptažodį, turi pateikti `currentPassword` (`403`, kai jo nėra arba jis neteisingas, įrašoma kaip `settings.update_failed`). Vietinis CLI ir egzempliorius su išjungtu prisijungimu išlaiko atkūrimo kelią ir gali nustatyti slaptažodį be jo, nes abu susieti su duomenų katalogą valdančiu serveriu.

## Dujotiekis

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

Patikimos vidinės antraštės (apibrėžtos `src/server/authz/headers.ts`) yra** atimta nuo gaunamų užklausų** prieš klasifikuodami — klientai negali iš anksto užpildyti `x-omniroute-auth-*` kad galėtų apsimesti subjektu.

### Politikos sutartys

Kiekviena maršruto klasė turi `src/server/authz/policies/` politiką:

- **`publicPolicy`** (`policies/public.ts`) — visada grąžina `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ekstraktai Nenešėjas, patvirtina per `validateApiKey()`. Patenka į anoniminį tik tada, kai išjungta efektyvi `REQUIRE_API_KEY` funkcijos vėliavėlė. Veiksminga vėliavėlė išsprendžiama naudojant `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), todėl prietaisų skydelio funkcijų vėliavėlės ir aplinkos kintamieji nuosekliai valdo `/api/v1/*`, `/api/v1beta/*` ir slapyvardžius; sprendiklio gedimai nepavyksta uždaryti. Leidžia pateikti informacijos suvestinės seanso užklausas kliento API maršrutuose (įskaitant `/api/v1/models`, naudojamą prietaisų skydelio modelių kataloge). Kai Entra ID SSO yra įjungtas, nešėją, kuri struktūriškai yra Entra prieigos raktas (trys base64url segmentai, `RS*` alg, `kid`), tvarko SSO šaka.** prieš** `validateApiKey()` ir jo sprendimas yra galutinis. — jis niekada nepatenka į API rakto kelią arba į anoniminį atšaką, todėl tapatybės teikėjo gedimas negali tapti atvira prieiga. Statiniai API klavišai neturi įtakos. Žr. [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — priima prietaisų skydelio seansą, vidinio modelio sinchronizavimo užklausas (atitinka `/api/providers/[name]/(sync-models|models)`) arba visiškai praleidžia, jei `isAuthRequired()` grąžina false. Grąžina 403 (`AUTH_001`), kai yra nešiklio ženklas, bet jis negalioja, 401 kitu atveju. Taip pat įgyvendina maršruto apsaugos pakopas (LOCAL_ONLY / ALWAYS_PROTECTED) prieš bet kurią autentifikavimo šaką — see [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY keliai `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (šiandien: `/api/mcp/`) gali būti pasiekiami be kilpos, kai nešiklio raktas turi `manage` sritį; visi kiti LOCAL_ONLY keliai išlieka griežti atgal, nepaisant taikymo srities.

Sėkminga politika grąžina `AuthSubject` su `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Tolesni tvarkytojai gali jį nuskaityti naudodami `assertAuth(request, "CLIENT_API")` `src/server/authz/assertAuth.ts` o ne pakartotinai paleisti autentifikavimo logiką.

## Viešųjų maršrutų sąrašas

`src/shared/constants/publicApiRoutes.ts` yra aiškus leidimų sąrašas:

Sąrašas suskirstytas pagal** forma** , o padalijimas yra nešantis (GHSA-74g9-q8f6-793h): priešdėlis suderinamas su `startsWith()`, taigi jis taip pat atitinka kiekvieną gretimą kelią, dalijantį pagrindinius simbolius. `/api/usage/om-usage` kaip priešdėlis pažymėtas `/api/usage/om-usage<anything>` PUBLIC, o Next išsprendžia, kad `/api/usage/[connectionId]` — tvarkytojas, neturintis savo autentifikavimo.

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

Tik skaitomi maršrutai yra vieši** tik** saugiems metodams. Pastaba: `classifyRoute()` neįtraukia `/api/v1/*` ir `/api/v1beta/*` į PUBLIC kritimo — jie visada yra `CLIENT_API` todėl nešiklio rakto politika vis tiek taikoma.

## Naujo maršruto pridėjimas

### 1 šablonas — viešasis kliento API galinis taškas (Bearer autentifikavimas)

Maršrutai, esantys `/api/v1/` ir `/api/v1beta/`, automatiškai klasifikuojami kaip `CLIENT_API`. Tarpinė programinė įranga užtikrina Bearer patikrą; maršrutų apdorojimo funkcijoms nereikia jos kartoti, tačiau prireikus jos gali nuskaityti subjektą.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... apdorojimo funkcijos logika
}
```

### 2 šablonas — valdymo galinis taškas (seansas arba Bearer + manage)

Naudokite `requireManagementAuth()` iš `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... apdorojimo funkcijos logika
}
```

Sėkmės atveju `requireManagementAuth()` grąžina `null`, o klaidos atveju — JSON klaidos objektą `Response`:

- 401 `AUTH_001` "Būtina autentifikuotis" — visiškai nėra prisijungimo duomenų
- 403 — netinkamas Bearer **arba** Bearer pateiktas, tačiau raktas neturi `manage` / `admin` aprėpties

`hasManageScope(scopes)` grąžina „true“, jei yra `"manage"` arba `"admin"`.

### 3 šablonas — įtraukimas į viešąjį leidžiamų maršrutų sąrašą

Rinkinį pasirinkite pagal formą, o ne pagal patogumą. Vienas maršrutas įtraukiamas į `PUBLIC_API_ROUTES_EXACT` (arba į `PUBLIC_READONLY_CORS_API_ROUTES`, jei jis skirtas tik GET); į `PUBLIC_API_ROUTE_PREFIXES` įtraukiamas tik tikras pomedis, ir jis **privalo baigtis `/`**. Į prefiksų sąrašą įtraukus vieną maršrutą, taip pat paviešinamas kiekvienas gretimas kelias, turintis tuos pačius pradinius simbolius, įskaitant vėliau pridėtus giminingus maršrutus su dinaminiais segmentais (GHSA-74g9-q8f6-793h). Atnaujinkite vienetinius testus failuose `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ir `tests/unit/authz/classify.test.ts`.

## Aprėptys

Trys vardų sritys. Kiekvienas tikrintojas skaito tik savo eilutes. Palyginimas,
įskaitant tai, kodėl `manage` nepavyksta `scopeMatches` dėl `read:compression` ir kodėl `read` prieigos raktas negali `PATCH /api/keys/{id}`, yra
[Trys aprėpties vardų sritys](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API raktai turi `scopes` masyvą (saugomą kaip JSON `api_keys.scopes`, žr. `src/lib/db/apiKeys.ts`).

### Valdymo aprėptis

- `manage` / `admin` — `hasManageScope`. Nešėjo prieiga prie valdymo API maršrutų.
- `mcp:connect`, `self:usage`, `self:account-quota` ir
  `policy:bypass-provider-quota` yra adityvios tikslios atitikties aprėptys. Jos yra už `MANAGEMENT_API_KEY_SCOPES` ribų. `mcp:connect` atidaro tik
  `/api/mcp/` negrįžtamojo ryšio išpjovą.

### MCP įrankio aprėptys

Katalogas ir atitikimo taisyklės (identiška eilutė arba suteikta aprėptis, besibaigianti `*`):
[MCP įrankio aprėptys](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` faile `src/shared/constants/mcpScopes.ts` yra originalus tipizuotas
poaibis, o ne visas katalogas. Vykdymas vyksta
`open-sse/mcp-server/scopeEnforcement.ts` po to, kai `resolveCallerScopeContext()`
išsprendžia aprėptis iš MCP autentifikavimo informacijos, užklausos metaduomenų arba `OMNIROUTE_MCP_SCOPES`.
Jis lieka išjungtas, nebent `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Prieigos rakto aprėptys

`read` / `write` / `admin` ant `oma_live_…` žetonų, reitinguojamų pagal `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Šis reitingas taikomas tik prieigos rakto
kredencialui. Žr. [Valdymo autentifikavimas](../guides/MANAGEMENT-AUTH.md).

## Reikalaujamo autentifikavimo jungiklis

`isAuthRequired()` faile `src/shared/utils/apiAuth.ts` nusprendžia, ar užklausai apskritai taikomas **koks nors** autentifikavimas:

- `settings.requireLogin === false` → autentifikavimas visame pasaulyje išjungtas, išskyrus visada apsaugotą lygmenį (žr. [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) ir iškvietimus, kurie išduoda prisijungimo duomenis, kuriuos jis priima. Šie iškvietimai reikalauja tų pačių prisijungimo duomenų, kaip ir įjungus prisijungimą: sinchronizavimo žetonų išdavimas, CLI prieigos žetonų išdavimas bet kurios taikymo srities, API rakto su `manage`/`admin` taikymo sritimi kūrimas, tos srities suteikimas raktui arba tokio rakto perkūrimas ar rodymas (`requireCredentialForManagementScopedKey()` faile `src/lib/api/requireManagementAuth.ts`). Raktai tik išvadoms lieka atviri.
- Slaptažodis nesukonfigūruotas **ir** nėra aplinkos kintamojo `INITIAL_PASSWORD` → bootstrap režimas leidžia pradinės sąrankos vedlį ir loopback užklausas, tačiau viešosios tinklo užklausos vis tiek reikalauja prisijungimo duomenų.
- Bet kuri DB klaida → uždaro prieigą (saugu pagal numatytuosius nustatymus).

Kliento API raktų vykdymui naudojama `isRequireApiKeyEnabled()` iš `src/shared/utils/featureFlags.ts`, o ne tiesioginis `process.env.REQUIRE_API_KEY` nuskaitymas. Tai svarbu įdiegtiems egzemplioriams: `REQUIRE_API_KEY` perjungimas Dashboard → Feature Flags išsaugo DB perrašymą ir iš karto veikia `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ir kitus kliento API autentifikavimo patikrinimus, kurie naudoja šią pagalbinę funkciją. Jei funkcijų vėliavų saugyklos nepavyksta perskaityti, kliento API autentifikavimas uždaro prieigą ir reikalauja rakto.

## Nesuderinamas pakeitimas — v3.8.0

Galiniams taškams `/api/v1/agents/tasks/*` ir `/api/resilience/model-cooldowns` **dabar reikalingas valdymo autentifikavimas** (įsipareigojimas `588a0333`). Klientai, anksčiau siuntę įprastą API raktą be `manage` aprėpties, gauna `403`. Migravimas: API Keys valdymo skydelyje suteikite raktui `manage` aprėptį arba naudokite prisijungto valdymo skydelio seansą.

## Veikimo pakeitimas — v3.8.2

`/api/mcp/*` (nuotolinis MCP serveris) pagal numatytąją nuostatą tebėra LOCAL_ONLY, tačiau dabar priima užklausas ne iš vietinio grįžtamojo ryšio adreso, kai antraštėje `Authorization: Bearer <api-key>` pateiktas raktas turi `manage` aprėptį. Ši išimtis kiekvienam keliui aiškiai valdoma per `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` faile `src/server/authz/routeGuard.ts`; susijusio LOCAL_ONLY prefikso `/api/cli-tools/runtime/*` tyčia negalima apeiti, nes jis gali paleisti bet kokius antrinius procesus. Anoniminėms užklausoms į `/api/mcp/*` ne iš vietinio grįžtamojo ryšio adreso ir toliau grąžinama `403 LOCAL_ONLY` — bet kuriam naujam LOCAL_ONLY keliui pagal numatytąją nuostatą tebėra taikomas griežtas vietinio grįžtamojo ryšio adreso reikalavimas. Žr. [Maršrutų apsaugos lygiai](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testavimas

- Vienetų testai: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Viešasis leidžiamų elementų sąrašas: `tests/unit/public-api-routes.test.ts`.
- Tikslinis paleidimas: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Derinimas

Dujotiekis visada antspauduoja atsakymus su:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Autentifikuotų užklausų užklausų antraštės taip pat apima:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Jei tarpinė programinė įranga buvo apeinama, naudokite `assertAuth(req, expectedClass)` viduje tvarkyklės — ji išmeta `AuthzAssertionError` su kodu `AUTHZ_NOT_INITIALIZED` (padeda užfiksuoti konfigūracijos regresijas testuose).

## Taip pat žr.

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — autentifikavimo žymė kiekvienam galiniam taškui
- [COMPLIANCE.md](../security/COMPLIANCE.md) — audito žurnalas autentifikavimo įvykiams
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — trys apimties vardų sritys ir MCP įrankių apimties katalogas
- Šaltinis: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
