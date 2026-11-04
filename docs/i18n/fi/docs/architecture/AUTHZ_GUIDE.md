# Authorization Guide (Suomi)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Totuuden lähde:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Viimeksi päivitetty:** 2026-09-22 — laajuuden nimiavaruudet osoittavat tiedostoon MCP-SERVER.md

OmniRoutessa on reittitietoinen valtuutusputki, joka valvoo jokaista API-pyyntöä. Luokittelu on **deterministinen** ja **fail-closed** — kaikki, mitä ei voida luokitella, päätyy `MANAGEMENT`-luokkaan ja vaatii istunnon tai hallintatason tunnuksen. Tämä sivu selittää mallin insinööreille, jotka ylläpitävät reittejä tai suunnittelevat uusia päätepisteitä.

![Valtuutusputki (3 reittiluokkaa + käytäntöjen arviointi)](../diagrams/exported/authz-pipeline.svg)

> Lähde: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Kaksi todennustilaa

### 1. API avain (kantolaite)

Käytetään OpenAI/Anthropic/Gemini-compatible -asiakasohjelmalle APIs ja muutamille hallintareiteille, kun avaimella on `manage` -alue.

```
Authorization: Bearer <api-key>
```

Vahvistanut `isValidApiKey()` / `extractApiKey()` `src/sse/services/auth.ts` :ssä ja viety uudelleen `src/shared/utils/apiAuth.ts` kautta. Validaattori hyväksyy myös `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars pysyvinä läpivientiavaimina (ongelma #1350).

### 2. Hallintapaneelin istunto (auth_token-eväste)

Kojelautasivuille ja järjestelmänvalvojan toiminnoille.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Eväste on istunto vain, kun JWT vahvistaa** ja** kantaa `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Jokainen evästeen kuluttaja (kojelaudan reitin vartija (`isDashboardSessionAuthenticated()`), authz-putkilinjan päivitys, WebSocket kättely, live-palvelin, `/api/settings/require-login`, `/api/auth/status`) käy tämän apuohjelman läpi. Muita `JWT_SECRET` llä allekirjoitettuja JWTs itä on olemassa — Cursor CLI -läpivienti tekee `iss "omniroute" / aud "cursor-cli"` tokeneita avaimenhaltijoille —, eivätkä ne ole koskaan istuntoja (#13298).

Tarkistanut `isDashboardSessionAuthenticated()` in `src/shared/utils/apiAuth.ts`. Liukulinja päivittää JWT automaattisesti, kun sen 30 päivän käyttöikää on jäljellä alle 7 päivää.

Istunto voi myös päättyä ennen kuin sen 30 päivää on kulunut, koska jokainen mintaaja käy läpi `mintDashboardSessionToken` (julkaisuaika `iat` ja id `jti`) ja todentaja tarkistaa kaksi asetusta: `sessionsValidAfter`, joka on asetettu salasanan vaihdolla, joten jokainen istunto ennen kuin se lopettaa vahvistamisen (salasanan vaihtanut selain saa uuden evästeen) ja `revokedDashboardSessions` istunto, johon kirjautuneena `POST /api/auth/logout` - `jti` lisää. Vanhemmalla julkaisulla lyödyt istunnot eivät aiheuta vaatimuksia ja ovat voimassa ensimmäiseen salasanan vaihtoon asti. Jos asetuksia ei voida lukea, istuntoon ei luoteta.

Jotkut hallintareitit hyväksyvät** joko** tila: eväste OR `Bearer <key>` kun API -näppäimellä on `manage` (tai `admin`) -alue. Tämä mahdollistaa v3.8:ssa lisätyn "konfiguroitavan API -kutsujen kautta" -työnkulun.

#### Valinnainen OIDC -kirjautumisportti (#6973)

Kojelaudan järjestelmänvalvojan kirjautuminen tukee myös** opt-in** OIDC (OpenID Connect) -virtaus oletussalasanakirjautumisen rinnalla — -salasanakirjautumista ei koskaan poisteta, vain täydennetään:

- Pois käytöstä, ellei `settings.oidcEnabled === true`** ja** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` on kaikki määritetty (Asetukset → Auth). `GET /api/auth/oidc/login` palauttaa `400` muuten.
- `GET /api/auth/oidc/login` löytää `authorization_endpoint` :n myöntäjän `/.well-known/openid-configuration` stä (putoaa takaisin arvoon `<issuer>/authorize`), muodostaa uudelleenohjauksen URI saapuvasta pyynnöstä (`x-forwarded-proto` -aware) ja uudelleenohjaa IdP hen `httpOnly` `oidc_state` -evästeeseen tallennetun satunnaisen `state` :n avulla.
- `GET /api/auth/oidc/callback` vahvistaa `state`, vaihtaa valtuutuskoodin ja varmistaa ID -tunnuksen allekirjoituksen myöntäjän JWKS kautta (`jose`'s `createRemoteJWKSet`, välimuistissa per JWKS URI) `issuer`/`audience` -tarkistuksilla. Hallintapaneeliin pääsy vaatii tyhjän `oidcAllowedSubjects` luettelon, `oidcAdmissionClaim` -käytännön tai molemmat. Aiheluettelo vastaa `sub` tai `email` vain, kun `email_verified === true`. Valinnainen vaatimuskäytäntö ottaa pisteillä erotetun ID-tunnuksen vaatimuspolun (esimerkiksi `realm_access.roles`) ja joukon hyväksyttyjä arvoja; ratkaistun vaatimuksen on oltava merkkijonojoukko, joka sisältää vähintään yhden hyväksytyn arvon. Jos molemmat käytännöt on määritetty, molempien on läpäistävä. Missing/malformed -vaatimukset epäonnistuvat, ja ilman kumpaakaan käytäntöä takaisinsoitto kieltäytyy kirjautumisesta (`not_configured`). Olemassa olevat vain aiheen määritykset jatkuvat ennallaan.
- Keycloak yhdistää yleensä valtakunnan roolit käyttöoikeuksiksi, ei välttämättä ID -tokeneiksi. Jos haluat vaatia alueroolin `admin`, määritä tälle asiakkaalle protokollakartoitin, joka sisältää `realm_access.roles` n**ID -tunnus** ja aseta sitten `oidcAdmissionClaim` arvoon `{ "path": "realm_access.roles", "values": ["admin"] }`. Tarkista tämän asiakkaan todellinen ID-tunnus ennen kuin otat käyttöön vain roolin. sovellus ei lue käyttöoikeusrooleja. IdP-puolen tunnuksen hylkääminen voi täydentää, mutta ei korvaa tätä sovelluspuolen tarkistusta.
- Onnistuessaan se lyö** aivan sama** 30 päivää `auth_token` JWT salasanan kirjautumisongelmia (`src/app/api/auth/login/route.ts`), joten loput kojelaudan istuntoputkesta (automaattinen päivitys, evästeiden liput) on ennallaan. — OIDC korvaa vain evästeen lyömisen, ei sen myöntämän. Muutokset IdP roles/groups hen eivät mitätöi olemassa olevia OmniRoute istuntoja; uloskirjautuminen, salasanan kierto tai istunnon vanheneminen vaikuttavat edelleen niiden käyttöikään.
- Jokainen `oidc*` asetus (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) on `SECURITY_IMPACTING_SETTINGS_KEYS` :ssa (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` vastaa `400 PASSWORD_REQUIRED` `401 PASSWORD_MISMATCH` `currentPassword`. `oidcDisablePasswordLogin` hylkää salasanan _login_ (`POST /api/auth/login`), mutta säilyttää tallennetun salasanan hajautusarvon, ja uudelleenauth tarkistaa silti `currentPassword` sen suhteen.
- `corsOrigins` ja `bruteForceProtection` ovat myös `SECURITY_IMPACTING_SETTINGS_KEYS` ssä: jommankumman löystäminen heikentää sisäänkirjautumissuojauksia, joten ne ottavat saman `currentPassword` uudelleenauth-tunnistuksen (Suojaus-välilehti pyytää sitä) ja JSON -tuonti pudottaa ne.
- Jokainen suojauskäytäntöavain — `SECURITY_IMPACTING_SETTINGS_KEYS` -merkinnät, jokainen `oidc*` avain ja kojelaudan istunnon tila — on** vain operaattorille** `PATCH /api/settings` ssä: hallintalaajuinen API avain tai `oma_` -käyttöoikeus evätään `403` lla, vaikka se lähettää oikean `currentPassword`, ja kieltäytyminen auditoidaan `settings.update_failed` :ksi `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`). Tavalliset asetukset (teema, näyttöasetukset) pysyvät kirjoitettavina `manage` -näppäimelle tai `admin` -käyttötunnisteelle. Jokainen `/api/settings` n (ja `/api/settings/require-login`:n) mutaatio tarvitsee myös `admin` pääsytunnisteen laajuuden (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, tarkka polun haku); `GET` pysyy `read`:nä ja muut `/api/settings/*` -alireitit (välityspalvelimet, yhdistelmäoletukset, mallialiakset, pakkaus, tyhjennys…) säilyttävät menetelmästä päätellyn `write` alueen.
- `POST /api/settings/import-json` ohittaa tämän uudelleentodennuksen, joten se pudottaa jokaisen `IMPORT_STRIPPED_SETTINGS_KEYS` -avaimen (sama tiedosto) ennen kirjoittamista: salasanan ja `currentPassword`, jokaisen `SECURITY_IMPACTING_SETTINGS_KEYS` merkinnän ja kojelaudan istunnon tilan (`sessionsValidAfter`, `revokedDashboardSessions`). Vanhemman varmuuskopion tuominen ei siis voi elvyttää istuntoa, jossa salasanan vaihto tai uloskirjautuminen on jo päättynyt.

#### Valinnainen TOTP -kaksivaiheinen kirjautuminen (#16619)

Ilmoittautunut asetuksista → Security; pois päältä, kunnes käyttäjä kytkee sen päälle (`src/server/auth/dashboardMfa.ts`).

- **Mitä se kattaa:** salasanan sisäänkirjautuminen (`POST /api/auth/login`, joka sitten tarvitsee `POST /api/auth/mfa/verify`) ja `omniroute connect` (`POST /api/cli/connect`, joka kieltäytyy vain salasanan vaihdosta ja ottaa koodin `totp`: ksi ).
- **Mitä se ei kata:** OIDC / SSO kirjautuminen (`/api/auth/oidc/callback`) ei kysy OmniRoute TOTP. Se perustuu identiteetintarjoajan omaan toiseen tekijään, joten pakota MFA IdP ssä, jos OIDC on käytössä.
- **Toipuminen** (kadonnut laite, palautuskoodeja ei ole jäljellä tai tekijä, jota ei voida enää varmistaa, esimerkiksi `STORAGE_ENCRYPTION_KEY` muuttamisen jälkeen):
  1. Käynnistä palvelin uudelleen komennolla `OMNIROUTE_DISABLE_MFA=true`.
  2. Kirjaudu sisään salasanalla itse isännässä (peer ja loopback `Host`, kuten `http://localhost:20128`). Toinen tekijä ohitetaan vain tämän alkuperän osalta; joka toinen alkuperä tarvitsee edelleen koodin.
  3. Syötä salasana kohdassa Asetukset → Security → Disable ja jätä koodi tyhjäksi. `POST /api/auth/mfa/disable` hyväksyy rungon ilman `code` vain, kun muuttuja on asetettu ja pyyntö tulee isännältä; se vaatii edelleen kojelautaistunnon ja nykyisen salasanan, ja se auditoidaan nimellä `auth.mfa.disabled` ja `secondFactor: "recovery_switch"`.
  4. Poista `OMNIROUTE_DISABLE_MFA` asetus, käynnistä uudelleen ja rekisteröidy tarvittaessa uudelleen.

## Reittiluokat

`src/server/authz/types.ts` määrittelee kolme luokkaa. Jokainen reitti, jota ei voi luokitella deterministisesti, palautuu oletuksena luokkaan `MANAGEMENT`.

| Luokka       | Kuvaus                                                                                                                                                 | Todennus vaaditaan                                                |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------- |
| `PUBLIC`     | Nimenomaisesti turvalliset reitit: kirjautuminen, uloskirjautuminen, tila, alustus, terveystarkistus ja onboarding-bootstrap.                          | Ei mitään                                                         |
| `CLIENT_API` | Mallipalvelun päätepisteet: `/api/v1/*`, `/api/v1beta/*` sekä aliakset `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer-avain, kun `REQUIRE_API_KEY`-ominaisuusliput ovat käytössä |
| `MANAGEMENT` | Dashboard-sivut, asetukset, palveluntarjoajat, avaimet, ylläpito- ja diagnostiikkapäätepisteet.                                                        | Dashboard-istunto TAI Bearer, jolla on `manage`-laajuus           |

Osa `MANAGEMENT`-toiminnoista on **vain operaattorille**: `manage`-avain ei riitä. Tallennettujen tunnistetietojen vieminen (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), varmuuskopion palauttaminen nykyisen datan päälle (`POST /api/db-backups/import` mukaan lukien `dryRun=true`, `POST /api/db-backups` palautus tunnuksella, `POST /api/settings/import-json`) ja palautuspisteiden tuhoaminen (`DELETE /api/db-backups` siivous sekä `PATCH /api/db-backups`, koska tallennettu säilytysaika ohjaa jokaisen varmuuskopioinnin jälkeisen automaattisen siivouksen) vaativat dashboard-istunnon, paikallisen CLI-identiteetin tai sen, että kirjautuminen on poistettu käytöstä. Synkronointitunnuksen myöntäminen (`POST /api/sync/tokens`) ja `admin`-laajuuden CLI-käyttötunnuksen luominen (`POST /api/cli/tokens`) vaativat dashboard-istunnon tai paikallisen CLI-identiteetin kaikissa kirjautumistiloissa. API-avaimet millä tahansa laajuudella ja `oma_`-käyttötunnukset eivät ole operaattorin tunnistetietoja: ne saavat `403`-virheen aina, kun sellainen vaaditaan. Tarkistus on tiedostossa `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Kirjautumisasetusten muuttaminen on myös vain operaattorille: `POST /api/settings/require-login` (aseta hallintasalasana / vaihda `requireLogin`) hyväksyy nämä tunnistetiedot vain, kun salasana on jo olemassa. Ensimmäisen käynnistyksen bootstrap-ikkuna (ei vielä salasanaa) on ennallaan, ja dashboard-istunnon on lähetettävä `currentPassword`, jotta salasana voidaan korvata (`403`, kun se puuttuu tai on väärä, kirjattu tilaan `settings.update_failed`). Paikallinen CLI ja instanssi, jossa kirjautuminen on pois käytöstä, säilyttävät palautusreitin ja saavat asettaa salasanan ilman sitä, koska molemmat on sidottu isäntään, joka omistaa datahakemiston.

## Putkilinja

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

Luotetut sisäiset otsikot (määritelty muodossa `src/server/authz/headers.ts`) ovat** poistettu saapuvista pyynnöistä** ennen luokitusta — asiakkaat eivät voi esitäyttää `x-omniroute-auth-*` esiintyäkseen aiheena.

### Vakuutussopimukset

Jokaisella reittiluokalla on käytäntö `src/server/authz/policies/`:ssa:

- **`publicPolicy`** (`policies/public.ts`) — palauttaa aina `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — poimii siirtotiestä, vahvistaa `validateApiKey()` kautta. Menee nimettömäksi vain, kun tehokas `REQUIRE_API_KEY` -ominaisuuden lippu on poistettu käytöstä. Tehokas lippu ratkaistaan `isRequireApiKeyEnabled()` :n (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) avulla, joten hallintapaneelin ominaisuusliput ja ympäristömuuttujat hallitsevat `/api/v1/*`, `/api/v1beta/*` ja aliaksia johdonmukaisesti. Ratkaisijavika epäonnistuu suljettu. Sallii kojelauta-istuntopyynnöt asiakkaan API reiteillä (mukaan lukien `/api/v1/models`, jota käytetään kojelautamalliluettelossa). Kun Entra ID SSO on käytössä, SSO -haara käsittelee siirtotietä, joka on rakenteellisesti Entra-tunnus (kolme base64url-segmenttiä, `RS*` alg, `kid`).** ennen** `validateApiKey()` ja sen tuomio on lopullinen — se ei koskaan putoa API-avaimen polulle tai degrade-anonyymiksi haaralle, joten identiteetintarjoajan katkosta ei voi tulla avointa pääsyä. Staattiset API -näppäimet eivät muutu. Katso [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — hyväksyy kojelautaistunnon, sisäiset mallisynkronointipyynnöt (verrataan `/api/providers/[name]/(sync-models|models)`) tai ohittaa kokonaan, jos `isAuthRequired()` palauttaa epätosi. Palauttaa 403 (`AUTH_001`), kun siirtotie on olemassa, mutta virheellinen, 401 muussa tapauksessa. Pakottaa myös reittivartijatasot (LOCAL_ONLY / ALWAYS_PROTECTED) ennen todennushaaraa — katso [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` :n LOCAL_ONLY polkuja (tänään: `/api/mcp/`) voidaan käyttää ei-paluupalkin kautta, kun siirtotieavain kantaa `manage` aluetta; kaikki muut LOCAL_ONLY polut pysyvät tiukkana takaisinkytkentäisinä laajuudesta riippumatta.

Onnistunut käytäntö palauttaa `AuthSubject` ja `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Alavirran käsittelijät voivat lukea sen `assertAuth(request, "CLIENT_API")` kautta `src/server/authz/assertAuth.ts` ssä sen sijaan, että he suorittaisivat todennuslogiikkaa uudelleen.

## Julkisten reittien luettelo

`src/shared/constants/publicApiRoutes.ts` on selkeä sallittu luettelo:

Lista on jaettu** muoto** , ja jako on kantava (GHSA-74g9-q8f6-793h): etuliite yhdistetään `startsWith()` lle, joten se vastaa myös kaikkia viereisiä polkuja, jotka jakavat johtavat merkit. `/api/usage/om-usage` etuliitteenä merkitty `/api/usage/om-usage<anything>` PUBLIC, ja Next ratkaisee sen `/api/usage/[connectionId]` — -käsittelijäksi, jolla ei ole omaa todennusta.

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

Vain luku -reitit ovat julkisia** vain** turvallisia menetelmiä varten. Huomautus: `classifyRoute()` sulkee pois `/api/v1/*` ja `/api/v1beta/*` PUBLIC fall-through —, ne ovat aina `CLIENT_API` joten siirtoavaimen käytäntö on edelleen voimassa.

## Uuden reitin lisääminen

### Malli 1 — Julkinen asiakas-API:n päätepiste (Bearer-todennus)

Reitit `/api/v1/`- ja `/api/v1beta/`-polkujen alla luokitellaan automaattisesti `CLIENT_API`-reiteiksi. Väliohjelmisto suorittaa Bearer-tarkistuksen; reittikäsittelijöiden ei tarvitse tehdä sitä uudelleen, mutta ne voivat tarvittaessa lukea subjektin.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... käsittelijän logiikka
}
```

### Malli 2 — Hallinnan päätepiste (istunto tai Bearer + manage)

Käytä `requireManagementAuth()`-funktiota tiedostosta `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... käsittelijän logiikka
}
```

`requireManagementAuth()` palauttaa onnistuessaan arvon `null` tai virhetilanteessa JSON-virheen sisältävän `Response`-vastauksen:

- 401 `AUTH_001` "Todennus vaaditaan" — tunnistetietoja ei ole lainkaan
- 403 — virheellinen Bearer **tai** Bearer on annettu, mutta avaimelta puuttuu `manage`- / `admin`-käyttöalue

`hasManageScope(scopes)` palauttaa arvon true, jos käyttöalue on `"manage"` tai `"admin"`.

### Malli 3 — Lisääminen julkisten reittien sallittujen luetteloon

Valitse joukko muodon, älä helppouden perusteella. Yksittäinen reitti lisätään joukkoon `PUBLIC_API_ROUTES_EXACT` (tai vain GET-pyynnöille joukkoon `PUBLIC_READONLY_CORS_API_ROUTES`); vain aito alipuu lisätään joukkoon `PUBLIC_API_ROUTE_PREFIXES`, ja sen **täytyy päättyä merkkiin `/`**. Yksittäisen reitin lisääminen etuliiteluetteloon julkaisee myös kaikki viereiset polut, joilla on samat alkumerkit — mukaan lukien myöhemmin lisättävät dynaamisten segmenttien sisarreitit (GHSA-74g9-q8f6-793h). Päivitä yksikkötestit tiedostoissa `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ja `tests/unit/authz/classify.test.ts`.

## Laajuudet

Kolme nimiavaruutta. Jokainen tarkistaja lukee vain omat merkkijononsa. Vertailu,
mukaan lukien miksi `manage` epäonnistuu `scopeMatches`-tarkistuksessa `read:compression`-kohdalla ja miksi `read`-käyttöoikeustunnus ei voi `PATCH /api/keys/{id}`, löytyy
[Kolme laajuuden nimiavaruutta](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API-avaimet sisältävät `scopes`-taulukon (tallennetaan JSON-muodossa `api_keys.scopes`-kenttään, katso `src/lib/db/apiKeys.ts`).

### Hallintalaajuus

- `manage` / `admin` — `hasManageScope`. Bearer-pääsy hallinnan API-reitteihin.
- `mcp:connect`, `self:usage`, `self:account-quota` ja
  `policy:bypass-provider-quota` ovat additiivisia tarkkoja vastaavuuslaajuuksia. Ne ovat
  `MANAGEMENT_API_KEY_SCOPES`-ulkopuolella. `mcp:connect` avaa vain
  `/api/mcp/`-reitin, joka on ei-loopback-poikkeus.

### MCP-työkalun laajuudet

Luettelo ja vastaavuussäännöt (identtinen merkkijono tai myönnetty laajuus, joka päättyy `*`):
[MCP-työkalun laajuudet](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` tiedostossa `src/shared/constants/mcpScopes.ts` on alkuperäinen tyypitetty
osajoukko, ei koko luettelo. Täytäntöönpano tapahtuu
`open-sse/mcp-server/scopeEnforcement.ts`-tiedostossa sen jälkeen, kun `resolveCallerScopeContext()`
ratkaisee laajuudet MCP-todennustiedoista, pyynnön metatiedoista tai `OMNIROUTE_MCP_SCOPES`-muuttujasta.
Se pysyy poissa käytöstä, ellei `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Käyttöoikeustunnuksen laajuudet

`read` / `write` / `admin` `oma_live_…`-tunnuksissa, järjestetty `scopeSatisfies`-funktion mukaan
(`src/lib/accessTokens/scopes.ts`). Tämä järjestys koskee vain käyttöoikeustunnuksen
tunnistetietoja. Katso [Hallinnan todennus](../guides/MANAGEMENT-AUTH.md).

## Todennuksen pakollisuuden kytkin

`isAuthRequired()` tiedostossa `src/shared/utils/apiAuth.ts` ratkaisee, pakotetaanko pyynnölle **mitään** todennusta:

- `settings.requireLogin === false` → todennus on kytketty globaalisti pois päältä, lukuun ottamatta aina suojattua tasoa (ks. [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) ja kutsuja, jotka antavat ulos tunnistetiedon, jonka se hyväksyy. Nämä vaativat saman tunnistetiedon kuin kirjautumisen ollessa päällä: synkronointitunnusten myöntäminen, CLI-käyttötunnusten myöntäminen millä tahansa laajuudella sekä `manage`/`admin`-laajuuden API-avaimen luominen, tuon laajuuden myöntäminen avaimelle tai sellaisen avaimen uudelleengenerointi tai näyttäminen (`requireCredentialForManagementScopedKey()` tiedostossa `src/lib/api/requireManagementAuth.ts`). Pelkkiä päättelyavaimia varten jäävät avoimiksi.
- Salasanaa ei ole määritetty **eikä** `INITIAL_PASSWORD`-ympäristömuuttujaa ole → bootstrap-tila sallii käyttöönottotoimet ja loopback-pyynnöt, mutta verkkoon avatut pyynnöt vaativat edelleen tunnistetiedot.
- Mikä tahansa tietokantavirhe → estää pääsyn (oletusarvoisesti turvallinen).

Asiakas-API:n avainten pakottaminen käyttää `isRequireApiKeyEnabled()`-funktiota tiedostossa `src/shared/utils/featureFlags.ts`, ei suoraan `process.env.REQUIRE_API_KEY`-lukua. Tällä on merkitystä käyttöönotetuille instansseille: `REQUIRE_API_KEY`-arvon vaihtaminen kohdassa Dashboard → Feature Flags tallentaa tietokantaan ohituksen ja vaikuttaa välittömästi reitteihin `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ja muihin asiakas-API:n todennustarkistuksiin, jotka jakavat tämän apufunktion. Jos feature flag -varastoa ei voi lukea, asiakas-API:n todennus estää pääsyn ja vaatii avaimen.

## Rikkova muutos — v3.8.0

Päätepisteet `/api/v1/agents/tasks/*` ja `/api/resilience/model-cooldowns` **edellyttävät nyt hallinnan todennusta** (commit `588a0333`). Asiakkaat, jotka aiemmin lähettivät tavallisen API-avaimen ilman `manage`-käyttöoikeusaluetta, saavat vastauksen `403`. Siirtyminen: myönnä avaimelle `manage`-käyttöoikeusalue API Keys -hallintapaneelissa tai käytä sisäänkirjautunutta hallintapaneeli-istuntoa.

## Toiminnan muutos — v3.8.2

`/api/mcp/*` (MCP-etäpalvelin) on edelleen oletusarvoisesti LOCAL_ONLY, mutta hyväksyy nyt muut kuin loopback-pyynnöt, kun `Authorization: Bearer <api-key>` -otsake sisältää `manage`-käyttöoikeusalueen. Poikkeus sallitaan eksplisiittisesti reittikohtaisesti tiedoston `src/server/authz/routeGuard.ts` määrityksellä `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES`; rinnakkaista LOCAL_ONLY-etuliitettä `/api/cli-tools/runtime/*` ei tarkoituksella voi ohittaa, koska se voi käynnistää mielivaltaisia aliprosesseja. Anonyymit pyynnöt reitille `/api/mcp/*` muista kuin loopback-osoitteista saavat edelleen vastauksen `403 LOCAL_ONLY` — uusien LOCAL_ONLY-reittien oletuksena säilyy tiukka loopback-rajoitus. Katso [Reittisuojauksen tasot](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testaus

- Yksikkötestit: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Julkisten reittien sallittujen luettelo: `tests/unit/public-api-routes.test.ts`.
- Kohdennetun testin suorittaminen: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Virheenkorjaus

Liukulinja leimaa aina vastaukset seuraavasti:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Todennettujen pyyntöjen ylävirran (käsittelijän puolen) pyyntöotsikot sisältävät myös:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Käytä `assertAuth(req, expectedClass)` käsittelijöiden sisällä — se heittää `AuthzAssertionError` koodilla `AUTHZ_NOT_INITIALIZED` jos väliohjelmisto ohitettiin (apua konfiguraatioregressioiden havaitsemiseen testeissä).

## Katso myös

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — todennusmerkintä päätepistettä kohti
- [COMPLIANCE.md](../security/COMPLIANCE.md) — tarkastusloki todennustapahtumille
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — kolme laajuusnimiavaruutta ja MCP-työkalun laajuuskatalogi
- Lähde: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
