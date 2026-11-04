# Authorization Guide (Eesti)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Tõe allikas:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Viimati uuendatud:** 2026-09-22 — skoobi nimeruumid viitavad MCP-SERVER.md

OmniRoute'il on marsruuditundlik autoriseerimistorustik, mis valvab iga API päringut. Klassifikatsioon on **deterministlik** ja **fail-closed** — kõik, mida ei saa klassifitseerida, lõpeb `MANAGEMENT`ina ja nõuab seanssi või haldustaseme tokenit. See leht selgitab mudelit inseneridele, kes hooldavad marsruute või kujundavad uusi lõpp-punkte.

![AuthZ torustik (3 marsruudiklassi + poliitika hindamine)](../diagrams/exported/authz-pipeline.svg)

> Allikas: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Kaks autentimisrežiimi

### 1. API võti (kandja)

Kasutatakse OpenAI/Anthropic/Gemini-compatible kliendi APIs ja mõne haldusmarsruudi jaoks, kui võtmel on `manage` ulatus.

```
Authorization: Bearer <api-key>
```

Kinnitatud `isValidApiKey()` / `extractApiKey()` poolt `src/sse/services/auth.ts` ja uuesti eksporditud `src/shared/utils/apiAuth.ts` kaudu. Validaator aktsepteerib püsivate läbipääsuvõtmetena ka `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env varie (probleem #1350).

### 2. Juhtpaneeli seanss (auth_token küpsis)

Armatuurlaua lehtede ja administraatoritoimingute jaoks.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Küpsis on seanss ainult siis, kui JWT kinnitab** ja** kannab `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Iga küpsise tarbija (armatuurlaua marsruudi valvur (`isDashboardSessionAuthenticated()`), autentimiskonveieri värskendamine, WebSocket käepigistus, reaalajas server, `/api/settings/require-login`, `/api/auth/status`) läbib selle abistaja. Muud `JWT_SECRET` ga allkirjastatud JWTs d on olemas — Cursor CLI läbipääs rahastab `iss "omniroute" / aud "cursor-cli"` märke võtmehoidjatele — ja need ei ole kunagi seansid (#13298).

Kinnitanud `isDashboardSessionAuthenticated()` in `src/shared/utils/apiAuth.ts`. Torujuhe värskendab JWT automaatselt, kui selle 30-päevasest elueast on jäänud vähem kui 7 päeva.

Seanss võib lõppeda ka enne selle 30 päeva möödumist, sest iga rahapaja läbib `mintDashboardSessionToken` (väljastusaeg `iat` ja ID `jti`) ja kontrollija kontrollib kahte seadet: `sessionsValidAfter`, mis on määratud paroolivahetusega, nii et iga seanss, mis väljastatakse enne kontrollimise lõpetamist (parooli muutnud brauser saab uue küpsise) ja `revokedDashboardSessions`-g-out seanss, millele lisatakse `POST /api/auth/logout` `jti`. Vanema versiooniga vermitud seanssidele ei esitata ühtegi nõuet ja need kehtivad kuni esimese parooli muutmiseni. Kui sätteid ei saa lugeda, ei ole seanss usaldusväärne.

Mõned juhtimismarsruudid aktsepteerivad** kas** režiim: küpsis OR `Bearer <key>` kui API -klahvil on `manage` (või `admin`) ulatus. See võimaldab versioonis 3.8 lisatud töövoogu "konfigureeritav API kõnede kaudu".

#### Valikuline OIDC sisselogimisvärav (#6973)

Armatuurlaua administraatori sisselogimine toetab ka** opt-in** OIDC (OpenID Connect) voogu koos vaikeparooliga sisselogimisega — parooli sisselogimist ei eemaldata kunagi, vaid täiendatakse:

- Keelatud, välja arvatud juhul, kui `settings.oidcEnabled === true`** ja** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` on kõik konfigureeritud (Seaded → Auth). `GET /api/auth/oidc/login` tagastab `400` muidu.
- `GET /api/auth/oidc/login` avastab väljaandja `authorization_endpoint` -st `/.well-known/openid-configuration` (langeb tagasi `<issuer>/authorize`), koostab sissetulevast päringust ümbersuunamise URI (`x-forwarded-proto` -aware) ja suunab IdP -sse juhusliku `state`, mis on salvestatud `httpOnly` `oidc_state` küpsisesse.
- `GET /api/auth/oidc/callback` kinnitab `state`, vahetab autoriseerimiskoodi ja kontrollib ID märgi allkirja väljaandja JWKS (`jose` s `createRemoteJWKSet`, vahemällu JWKS URI) kaudu `issuer`/`audience` kontrollidega. Armatuurlauale pääsemiseks on vaja tühja `oidcAllowedSubjects` loendit, `oidcAdmissionClaim` -poliitikat või mõlemat. Teemade loend sobib `sub` või `email` ainult siis, kui `email_verified === true`. Valikuline nõudepoliitika kasutab punktidega eraldatud ID-märgi nõudetee (nt `realm_access.roles`) ja aktsepteeritud väärtuste massiivi; lahendatud nõue peab olema stringide massiiv, mis sisaldab vähemalt ühte aktsepteeritud väärtust. Kui mõlemad reeglid on konfigureeritud, peavad mõlemad läbima. Missing/malformed nõuded ebaõnnestuvad ja ilma kummagi poliitikata keeldub tagasihelistamine sisselogimisest (`not_configured`). Olemasolevad ainult teema konfiguratsioonid jäävad muutumatuks.
- Keycloak kaardistab tavaliselt valdkonna rollid juurdepääsulubadeks, mitte tingimata ID lubadeks. Valdkonnarolli `admin` nõudmiseks seadistage selle kliendi jaoks protokolli kaardistaja, mis sisaldab `realm_access.roles` d**ID märk** , seejärel määrake `oidcAdmissionClaim` väärtuseks `{ "path": "realm_access.roles", "values": ["admin"] }`. Enne ainult rollipõhise juurdepääsu lubamist kontrollige selle kliendi tegelikku ID-märgi nõuet; rakendus ei loe juurdepääsulubade rolle. IdP-poolse loa keeldumine võib seda rakendusepoolset kontrolli täiendada, kuid ei asenda.
- On edu see rahapaja** täpselt sama** 30-päevane `auth_token` JWT parooli sisselogimisprobleemid (`src/app/api/auth/login/route.ts`), nii et ülejäänud armatuurlaua seansi konveier (automaatne värskendamine, küpsisemärgid) on muutumatu. — OIDC asendab ainult küpsise vermimise viisi, mitte seda, mida see annab. IdP roles/groups muudatused ei muuda olemasolevaid OmniRoute seansse kehtetuks; väljalogimine, parooli vahetamine või seansi aegumine reguleerivad endiselt nende eluiga.
- Iga `oidc*` seadistus (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) on `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` vastab `400 PASSWORD_REQUIRED` välja arvatud juhul, kui keha kannab haldusparooli (vale `401 PASSWORD_MISMATCH` `currentPassword`. `oidcDisablePasswordLogin` keeldub parooli _login_ (`POST /api/auth/login`) andmisest, kuid säilitab salvestatud parooliräsi ja uuesti autentimine kontrollib siiski `currentPassword` selle vastu.
- `corsOrigins` ja `bruteForceProtection` on ka `SECURITY_IMPACTING_SETTINGS_KEYS` : kummagi lõdvendamine nõrgendab sisselogimise kaitset, nii et nad võtavad sama `currentPassword` uuesti autentimise (seda küsib vahekaart Turvalisus) ja JSON import tühistab need.
- Iga turvapoliitika võti — `SECURITY_IMPACTING_SETTINGS_KEYS` -kirjed, iga `oidc*` -võti ja armatuurlaua seansi olek — on** ainult operaatorile** `PATCH /api/settings` puhul: hallatava ulatusega API võti või `oma_` juurdepääsuluba keeldutakse `403` isegi siis, kui see saadab õige `currentPassword` ja keeldumist auditeeritakse kui `settings.update_failed` koos `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`). Tavalised sätted (teema, kuvaeelistused) jäävad `manage` klahvi või `admin` pääsuloa jaoks kirjutatavaks. Iga `/api/settings` enda (ja `/api/settings/require-login`) mutatsioon vajab ka `admin` juurdepääsuluba ulatust (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, täpne tee vaste); `GET` jääb `read` ja teised `/api/settings/*` -alammarsruudid (puhverserverid, kombineeritud vaikesätted, mudeli pseudonüümid, tihendamine, tühjendamine jne) säilitavad meetodist tuletatud `write` ulatuse.
- `POST /api/settings/import-json` jätab selle uuesti autentimise vahele, seega jätab enne kirjutamist kõik `IMPORT_STRIPPED_SETTINGS_KEYS` (sama faili) võtmed: parool ja `currentPassword`, iga `SECURITY_IMPACTING_SETTINGS_KEYS` kirje ja armatuurlaua seansi olek (`sessionsValidAfter`, `revokedDashboardSessions`). Seetõttu ei saa vanema varukoopia importimine taaselustada seanssi, mille paroolivahetus või väljalogimine on juba lõppenud.

#### Valikuline TOTP kahefaktoriline sisselogimine (#16619)

Registreeritud jaotisest Settings → Security; välja, kuni operaator selle sisse lülitab (`src/server/auth/dashboardMfa.ts`).

- **Mida see hõlmab:** parooli sisselogimine (`POST /api/auth/login`, mis vajab siis `POST /api/auth/mfa/verify`) ja `omniroute connect` (`POST /api/cli/connect`, mis keeldub ainult parooli vahetamisest ja võtab koodi `totp`).
- **Mida see ei hõlma:** OIDC / SSO sisselogimine (`/api/auth/oidc/callback`) ei küsi OmniRoute TOTP. See tugineb identiteedipakkuja enda teisele tegurile, seega jõustage MFA IdP, kui OIDC on lubatud.
- **Taastumine** (seade on kadunud, taastekoode pole alles või tegur, mida ei saa enam kontrollida, näiteks pärast `STORAGE_ENCRYPTION_KEY` muutmist):
  1. Taaskäivitage server `OMNIROUTE_DISABLE_MFA=true`.
  2. Logige sisse parooliga hostis endas (peer ja loopback `Host`, nt `http://localhost:20128`). Teine tegur jäetakse vahele ainult selle päritolu puhul; iga teine päritolu vajab ikka koodi.
  3. Sisestage jaotises Seaded → Security → Disable parool ja jätke kood tühjaks. `POST /api/auth/mfa/disable` aktsepteerib keha ilma `code` ainult siis, kui muutuja on seatud ja päring tuleb hostilt; see nõuab endiselt armatuurlaua seanssi ja praegust parooli ning seda auditeeritakse kui `auth.mfa.disabled` koos `secondFactor: "recovery_switch"`.
  4. Tühista `OMNIROUTE_DISABLE_MFA` seadistus, taaskäivitage ja vajadusel registreeruge uuesti.

## Marsruudiklassid

`src/server/authz/types.ts` määratleb kolm klassi. Iga marsruut, mida ei saa deterministlikult klassifitseerida, langeb vaikimisi klassi `MANAGEMENT`.

| Klass        | Kirjeldus                                                                                                                                             | Nõutav autentimine                                            |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| `PUBLIC`     | Selgesõnaliselt ohutud marsruudid: sisselogimine, väljalogimine, olek, lähtestamine, tervisekontroll ja onboarding-bootstrap.                         | Puudub                                                        |
| `CLIENT_API` | Mudeliteenuse lõpp-punktid: `/api/v1/*`, `/api/v1beta/*` ning aliased `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer-võti, kui funktsioonilipp `REQUIRE_API_KEY` on lubatud |
| `MANAGEMENT` | Armatuurlaua lehed, seaded, pakkujad, võtmed, admin- ja diagnostikalõpp-punktid.                                                                      | Armatuurlaua seanss VÕI Bearer `manage`-ulatusega             |

Mõned `MANAGEMENT` toimingud on **ainult operaatorile**: `manage`-võti ei ole piisav. Salvestatud mandaatide eksportimine (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), varukoopia taastamine praegusete andmete peale (`POST /api/db-backups/import`, sh `dryRun=true`, `POST /api/db-backups` taastamine ID järgi, `POST /api/settings/import-json`) ning taastepunktide hävitamine (`DELETE /api/db-backups` puhastus ja `PATCH /api/db-backups`, sest salvestatud säilitusaeg juhib automaatset puhastamist iga varukoopia järel) nõuavad armatuurlaua seanssi, kohalikku CLI-identiteeti või seda, et sisselogimine on keelatud. Sünkroonimistokeni väljastamine (`POST /api/sync/tokens`) ja `admin`-ulatusega CLI juurdepääsutokeni loomine (`POST /api/cli/tokens`) nõuavad armatuurlaua seanssi või kohalikku CLI-identiteeti igas sisselogimisrežiimis. API-võtmed igas ulatuses ja `oma_` juurdepääsutokenid ei ole operaatori mandaadid: need saavad vastuseks `403`, kui see on nõutav. Kontroll asub failis `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Sisselogimisseadete muutmine on samuti ainult operaatorile: `POST /api/settings/require-login` (haldusparooli määramine / `requireLogin` lülitamine) aktsepteerib neid mandaate pärast seda, kui parool on olemas. Esmase käivituse bootstrap-aken (parooli veel pole) on muutumatu ning armatuurlaua seanss peab parooli asendamiseks saatma `currentPassword`-i (`403`, kui see puudub või on vale, logitud kui `settings.update_failed`). Kohalik CLI ja instants, kus sisselogimine on keelatud, säilitavad taastamistee ning võivad parooli seada ilma selleta, sest mõlemad on seotud andmekataloogi omava hostiga.

## Konveier

```
Saabuv päring → src/proxy.ts
  → runAuthzPipeline() failis src/server/authz/pipeline.ts
    1. Usaldusväärsete sisemiste päiste eemaldamine (x-omniroute-auth-*, x-omniroute-route-class)
    2. Päringu ID genereerimine, marsruudi klassifitseerimine funktsiooni classifyRoute() kaudu
    3. Kui pathname == "/" → suuna ümber aadressile /dashboard
    4. Kui toimub tühjendus (sujuv sulgemine) ja tegemist on /api/* päringuga → 503
    5. Kui /api/* päring ei ole GET → kontrolli checkBodySize() kaitset
    6. Kui OPTIONS → CORS-i eelkontroll 204
    7. Kui options.enforce == false → edasta koos route-class päistega
    8. Muul juhul: POLICIES[routeClass].evaluate(ctx)
       - allow  → lisa x-omniroute-auth-{kind,id,label,scopes} → NextResponse.next()
       - reject → JSON-i viga koos correlation_id-ga (juhtpaneeli lehed → 302 /login)
```

Usaldusväärsed sisemised päised (määratletud failis `src/server/authz/headers.ts`) **eemaldatakse sissetulevatest päringutest** enne klassifitseerimist — kliendid ei saa subjekti kehastamiseks eeltäita päiseid `x-omniroute-auth-*`.

### Poliitikalepped

Igal marsruudiklassil on poliitika asukohas `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — tagastab alati `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — eraldab Beareri, valideerib selle funktsiooni `validateApiKey()` kaudu. Läheb anonüümseks üle ainult siis, kui tegelik `REQUIRE_API_KEY` funktsioonilipp on keelatud. Tegelik lipp lahendatakse funktsiooni `isRequireApiKeyEnabled()` kaudu (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), mistõttu juhtpaneeli funktsioonilipud ja keskkonnamuutujad juhivad järjepidevalt marsruute `/api/v1/*`, `/api/v1beta/*` ja nende aliaseid; lahendaja tõrked sulgevad juurdepääsu. Lubab juhtpaneeli seansi päringud kliendi API marsruutidel, sealhulgas marsruudil `/api/v1/models`, mida kasutatakse juhtpaneeli mudelikataloogis.
  Kui Entra ID SSO on lubatud, käsitletakse struktuurilt Entra tokenina olevat Bearerit (kolm base64url-segmenti, `RS*` algoritm, `kid`) SSO-harus **enne** funktsiooni `validateApiKey()` ning selle otsus on lõplik — see ei lähe kunagi üle API-võtme teele ega anonüümseks taandumise harusse, mistõttu identiteedipakkuja katkestus ei saa muutuda avatud juurdepääsuks. Staatilisi API-võtmeid see ei mõjuta. Vt [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — aktsepteerib juhtpaneeli seansi, sisemisi mudelite sünkroonimise päringuid (sobitatud mustriga `/api/providers/[name]/(sync-models|models)`) või jätab kontrolli täielikult vahele, kui `isAuthRequired()` tagastab väärtuse `false`. Tagastab väärtuse 403 (`AUTH_001`), kui Beareri token on olemas, kuid kehtetu, muul juhul 401. Samuti jõustab marsruudivalve tasemed (LOCAL_ONLY / ALWAYS_PROTECTED) enne mis tahes autentimisharu — vt [Marsruudivalve tasemed](../security/ROUTE_GUARD_TIERS.md). `LOCAL_ONLY`-i teed prefiksis `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (praegu: `/api/mcp/`) võivad olla mitte-loopback-aadressilt juurdepääsetavad, kui Beareri võti sisaldab ulatust `manage`; kõik muud `LOCAL_ONLY`-i teed jäävad ulatusest olenemata rangelt loopback-põhiseks.

Edukalt lõpetanud poliitika tagastab `AuthSubject`-i, mille `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Alamjärgu töötlejad saavad seda lugeda funktsiooni `assertAuth(request, "CLIENT_API")` kaudu failis `src/server/authz/assertAuth.ts`, selle asemel et autentimisloogikat uuesti käivitada.

## Avalike marsruutide loend

`src/shared/constants/publicApiRoutes.ts` on selgesõnaline lubatud loend:

Loend on jagatud** kuju** , ja jaotus on kandev (GHSA-74g9-q8f6-793h): eesliide sobitatakse `startsWith()`, seega sobib see ka iga külgneva teega, mis jagab oma juhtmärke. `/api/usage/om-usage` eesliitena märgitakse `/api/usage/om-usage<anything>` PUBLIC ja Next lahendab selle `/api/usage/[connectionId]` — töötleja, millel puudub oma autentimine.

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

Kirjutuskaitstud marsruudid on avalikud** ainult** ohutute meetodite jaoks. Märkus. `classifyRoute()` välistab `/api/v1/*` ja `/api/v1beta/*` läbilangemise PUBLIC hulgast — need on alati `CLIENT_API` seega kehtib endiselt võtme kandja poliitika.

## Uue marsruudi lisamine

### Muster 1 — Avalik kliendi API otspunkt (Bearer-autentimine)

Marsruudid `/api/v1/` ja `/api/v1beta/` all liigitatakse automaatselt tüübiks `CLIENT_API`. Vahevara jõustab Bearer-kontrolli; marsruuditöötlejad ei pea seda kordama, kuid võivad vajaduse korral subjekti lugeda.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... töötleja loogika
}
```

### Muster 2 — Haldusotspunkt (seanss või Bearer + manage)

Kasutage funktsiooni `requireManagementAuth()` failist `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... töötleja loogika
}
```

`requireManagementAuth()` tagastab õnnestumise korral `null` või JSON-vormingus veavastuse `Response`:

- 401 `AUTH_001` „Autentimine on nõutav“ — identimisteave puudub täielikult
- 403 — Bearer on kehtetu **või** Bearer on olemas, kuid võtmel puudub ulatus `manage` / `admin`

`hasManageScope(scopes)` tagastab väärtuse true ulatuse `"manage"` või `"admin"` korral.

### Muster 3 — Avalikku lubatud marsruutide loendisse lisamine

Valige kogum kuju, mitte mugavuse järgi. Üks marsruut lisatakse kogumisse `PUBLIC_API_ROUTES_EXACT` (või ainult GET-i jaoks kogumisse `PUBLIC_READONLY_CORS_API_ROUTES`); kogumisse `PUBLIC_API_ROUTE_PREFIXES` lisatakse üksnes tegelik alampuu ning see **peab lõppema märgiga `/`**. Üksiku marsruudi lisamine prefiksiloendisse avalikustab ka kõik külgnevad teed, mille algusmärgid on samad — sealhulgas hiljem lisatud dünaamilise segmendiga sõsarmarsruudid (GHSA-74g9-q8f6-793h). Uuendage ühikteste failides `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ja `tests/unit/authz/classify.test.ts`.

## Skoobid

Kolm nimeruumi. Iga kontrollija loeb ainult oma stringe. Kõrvuti võrdlus,
sealhulgas miks `manage` ebaõnnestub `scopeMatches` puhul `read:compression` jaoks ja miks `read`
ligipääsutoken ei saa `PATCH /api/keys/{id}`, on
[Kolm skoobi nimeruumi](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API võtmed sisaldavad `scopes` massiivi (salvestatud JSON-ina `api_keys.scopes` all, vt `src/lib/db/apiKeys.ts`).

### Halduse skoop

- `manage` / `admin` — `hasManageScope`. Kandja ligipääs halduse API marsruutidele.
- `mcp:connect`, `self:usage`, `self:account-quota` ja
  `policy:bypass-provider-quota` on aditiivsed täpselt vastavad skoobid. Need
  asuvad väljaspool `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` avab ainult
  `/api/mcp/` mitte-tagasiside erandi.

### MCP tööriista skoobid

Kataloog ja vastavusreeglid (identne string või antud skoop, mis lõpeb `*`-ga):
[MCP tööriista skoobid](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` failis `src/shared/constants/mcpScopes.ts` on algne tüübitud
alamhulk, mitte see täielik kataloog. Jõustamine toimub
`open-sse/mcp-server/scopeEnforcement.ts` pärast seda, kui `resolveCallerScopeContext()`
lahendab skoobid MCP autentimisteabest, päringu metaandmetest või `OMNIROUTE_MCP_SCOPES`-ist.
See jääb välja lülitatuks, välja arvatud juhul, kui `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Ligipääsutokeni skoobid

`read` / `write` / `admin` `oma_live_…` tokenitel, järjestatud `scopeSatisfies`
järgi (`src/lib/accessTokens/scopes.ts`). See järjestus kehtib ainult
ligipääsutokeni mandaadile. Vt [Halduse autentimine](../guides/MANAGEMENT-AUTH.md).

## Autentimise nõudmise lüliti

`isAuthRequired()` failis `src/shared/utils/apiAuth.ts` otsustab, kas päringu puhul rakendatakse **üldse** mingit autentimist:

- `settings.requireLogin === false` → autentimine on globaalselt välja lülitatud, välja arvatud alati kaitstud tase (vt [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) ja kutsed, mis väljastavad mandaadi, mida see aktsepteerib. Need nõuavad sama mandaati, mis sisselogimise sisselülitamisel: sünkroonimistokenite väljastamine, CLI juurdepääsutokenite väljastamine mis tahes ulatuses ning `manage`/`admin`-ulatusega API-võtme loomine, selle ulatuse andmine võtmele või sellise võtme taasgenereerimine või kuvamine (`requireCredentialForManagementScopedKey()` failis `src/lib/api/requireManagementAuth.ts`). Ainult järeldamise võtmed jäävad avatuks.
- Parooli pole seadistatud **ja** keskkonnamuutujat `INITIAL_PASSWORD` pole → bootstrap-režiim lubab seadistusviisardi ja loopback-päringud, kuid avalikud võrgupäringud nõuavad endiselt mandaate.
- Mis tahes andmebaasi viga → keeldub ligipääsust (vaikimisi turvaline).

Kliendi API-võtme jõustamine kasutab funktsiooni `isRequireApiKeyEnabled()` failis `src/shared/utils/featureFlags.ts`, mitte otsest lugemist `process.env.REQUIRE_API_KEY`-st. See on juurutatud instantsside puhul oluline: `REQUIRE_API_KEY` lülitamine menüüs Dashboard → Feature Flags salvestab andmebaasi alistuse ning mõjutab kohe marsruute `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ja teisi kliendi API autentimiskontrolle, mis jagavad seda abifunktsiooni. Kui funktsioonilippude salvestust ei saa lugeda, keeldub kliendi API autentimine ligipääsust ja nõuab võtit.

## Ühilduvust katkestav muudatus — v3.8.0

Lõpp-punktid `/api/v1/agents/tasks/*` ja `/api/resilience/model-cooldowns` **nõuavad nüüd haldusautentimist** (commit `588a0333`). Kliendid, mis saatsid varem tavalise API-võtme ilma ulatuseta `manage`, saavad vastuseks `403`. Üleviimine: määrake võtmele API Keys juhtpaneelil ulatus `manage` või kasutage sisselogitud juhtpaneeliseanssi.

## Käitumise muudatus — v3.8.2

`/api/mcp/*` (MCP kaugserver) on endiselt vaikimisi LOCAL_ONLY, kuid aktsepteerib nüüd mitte-loopback-päringuid, kui päis `Authorization: Bearer <api-key>` sisaldab ulatust `manage`. Erand lubatakse iga tee jaoks eraldi konstandi `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` kaudu failis `src/server/authz/routeGuard.ts`; sama taseme LOCAL_ONLY prefiksist `/api/cli-tools/runtime/*` ei saa tahtlikult mööda minna, sest see võib käivitada suvalisi alamprotsesse. Mitte-loopback-aadressidelt pärit anonüümsed päringud teele `/api/mcp/*` saavad jätkuvalt vastuseks `403 LOCAL_ONLY` — iga uue LOCAL_ONLY tee vaikekäitumiseks jääb range loopback-piirang. Vt [Marsruudikaitse tasemed](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testimine

- Ühiktestid: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Avalik lubatud loend: `tests/unit/public-api-routes.test.ts`.
- Sihttesti käivitamine: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Silumine

Konveier lisab vastustele alati järgmised päised:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Autenditud päringute korral sisaldavad ülesvoolu (käsitlejapoolsed) päringupäised samuti järgmist:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Kasutage käsitlejates `assertAuth(req, expectedClass)` — see väljastab `AuthzAssertionError`i koodiga `AUTHZ_NOT_INITIALIZED`, kui vahevara jäeti vahele (see on kasulik konfiguratsiooni regressioonide tuvastamiseks testides).

## Vaata ka

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — autentimismärgis iga lõpp-punkti kohta
- [COMPLIANCE.md](../security/COMPLIANCE.md) — auditi logi autentimissündmuste jaoks
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — kolm skoobi nimeruumi ja MCP tööriista-skoobi kataloog
- Allikas: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
