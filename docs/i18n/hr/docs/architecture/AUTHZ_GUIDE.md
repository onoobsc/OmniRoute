# Authorization Guide (Hrvatski)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Izvor istine:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Zadnje ažurirano:** 2026-09-22 — prostori naziva opsega upućuju na MCP-SERVER.md

OmniRoute ima autorizacijski cjevovod svjestan ruta koji štiti svaki API zahtjev. Klasifikacija je **deterministička** i **zatvorena u slučaju kvara** — sve što se ne može klasificirati završava kao `MANAGEMENT` i zahtijeva sesiju ili token upravljačke razine. Ova stranica objašnjava model za inženjere koji održavaju rute ili dizajniraju nove krajnje točke.

![AuthZ cjevovod (3 klase ruta + evaluacija politike)](../diagrams/exported/authz-pipeline.svg)

> Izvor: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dva načina autentifikacije

### 1. API ključ (nositelj)

Koristi se za OpenAI/Anthropic/Gemini-compatible klijent APIs i nekoliko upravljačkih ruta kada ključ ima opseg `manage`.

```
Authorization: Bearer <api-key>
```

Potvrđeno od strane `isValidApiKey()` / `extractApiKey()` u `src/sse/services/auth.ts` i ponovno izvezeno kroz `src/shared/utils/apiAuth.ts`. Validator također prihvaća `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars kao trajne prolazne ključeve (problem #1350).

### 2. Sesija nadzorne ploče (kolačić auth_token)

Za stranice nadzorne ploče i administratorske operacije.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Kolačić je sesija samo kada JWT potvrdi** i** nosi `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Svaki potrošač kolačića (čuvar rute nadzorne ploče (`isDashboardSessionAuthenticated()`), osvježavanje authz cjevovoda, WebSocket rukovanje, živi poslužitelj, `/api/settings/require-login`, `/api/auth/status`) prolazi kroz tog pomoćnika. Ostali JWTs potpisani sa `JWT_SECRET` postoje — Cursor CLI prolaz kuje `iss "omniroute" / aud "cursor-cli"` tokene za nositelje ključeva — i nikada nisu sesije (#13298).

Ovjerio `isDashboardSessionAuthenticated()` u `src/shared/utils/apiAuth.ts`. Cjevovod automatski osvježava JWT kada mu je preostalo manje od 7 dana u 30-dnevnom vijeku trajanja.

Sesija također može završiti prije isteka 30 dana, jer svaki minter prolazi kroz `mintDashboardSessionToken` (vrijeme izdanja `iat` i id `jti`) i verifikator provjerava dvije postavke: `sessionsValidAfter`, postavljenu promjenom lozinke tako da svaka sesija izdana prije nego što prestane s provjerom (preglednik koji je promijenio lozinku dobiva svježi kolačić), i `revokedDashboardSessions`, kojem `POST /api/auth/logout` dodaje `jti` odjavljene sesije. Sesije iskovane starijim izdanjem ne nose niti jedan zahtjev i ostaju važeće do prve promjene lozinke. Ako se postavke ne mogu pročitati, sesija nije pouzdana.

Neki načini upravljanja prihvaćaju** ili** način: kolačić OR `Bearer <key>` kada ključ API ima opseg `manage` (ili `admin`). To je ono što omogućuje tijek rada "konfigurabilan putem API poziva" dodan u v3.8.

#### Dodatna OIDC vrata za prijavu (#6973)

Administratorska prijava nadzorne ploče također podržava** uključiti se** OIDC (OpenID Connect) teče uz zadanu prijavu lozinke — prijava lozinke nikada se ne uklanja, samo se nadopunjuje:

- Onemogućeno osim ako `settings.oidcEnabled === true`** i** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` svi su konfigurirani (Postavke → Auth). `GET /api/auth/oidc/login` vraća `400` inače.
- `GET /api/auth/oidc/login` otkriva `authorization_endpoint` iz `/.well-known/openid-configuration` izdavatelja (vraća se na `<issuer>/authorize`), gradi preusmjeravanje URI iz dolaznog zahtjeva (`x-forwarded-proto` -aware) i preusmjerava na IdP sa nasumičnim `state` pohranjenim u `httpOnly` `oidc_state` kolačiću.
- `GET /api/auth/oidc/callback` potvrđuje `state`, razmjenjuje autorizacijski kod i provjerava potpis ID tokena putem JWKS izdavatelja (`jose`-ov `createRemoteJWKSet`, predmemorirano po JWKS URI) sa `issuer`/`audience` provjerama. Pristup nadzornoj ploči zahtijeva neprazan `oidcAllowedSubjects` popis, `oidcAdmissionClaim` pravilo ili oboje. Popis predmeta odgovara `sub` ili `email` samo kada `email_verified === true`. Izborna politika zahtjeva uzima putanju zahtjeva za ID-tokenom odvojenu točkama (na primjer, `realm_access.roles`) i niz prihvaćenih vrijednosti; riješeni zahtjev mora biti niz nizova koji sadrže barem jednu prihvaćenu vrijednost. Ako su oba pravila konfigurirana, oba moraju proći. Missing/malformed zahtjevi nisu uspjeli zatvoriti, a bez bilo koje politike povratni poziv odbija prijavu (`not_configured`). Postojeće konfiguracije samo za predmet ostaju nepromijenjene.
- Keycloak obično preslikava uloge područja u pristupne tokene, ne nužno ID tokene. Da biste zahtijevali ulogu područja `admin`, konfigurirajte maper protokola za ovog klijenta koji uključuje `realm_access.roles` u svom**ID token** , zatim postavite `oidcAdmissionClaim` na `{ "path": "realm_access.roles", "values": ["admin"] }`. Provjerite stvarni zahtjev za ID-token za ovog klijenta prije omogućavanja pristupa samo za ulogu; aplikacija ne čita uloge tokena za pristup. Odbijanje tokena na strani IdP-a može dopuniti, ali ne zamijeniti ovu provjeru na strani aplikacije.
- Na uspjeh se kuje** točno isto** 30-dnevni `auth_token` JWT problemi s prijavom lozinke (`src/app/api/auth/login/route.ts`), tako da je ostatak cjevovoda sesije nadzorne ploče (automatsko osvježavanje, oznake kolačića) nepromijenjen — OIDC samo zamjenjuje način na koji se kolačić iskuje, a ne ono što odobrava. Promjene u IdP roles/groups ne poništavaju postojeće OmniRoute sesije; odjava, rotacija lozinke ili istek sesije i dalje upravljaju njihovim vijekom trajanja.
- Svaka `oidc*` postavka (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) je u `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` odgovara `400 PASSWORD_REQUIRED` osim ako tijelo nosi lozinku za upravljanje kao `currentPassword` (`401 PASSWORD_MISMATCH` kada je pogrešna). `oidcDisablePasswordLogin` odbija zaporku _login_ (`POST /api/auth/login`), ali zadržava pohranjenu hash zaporke, a ponovna autentifikacija i dalje provjerava `currentPassword` u odnosu na nju.
- `corsOrigins` i `bruteForceProtection` također su u `SECURITY_IMPACTING_SETTINGS_KEYS` : labavljenje bilo kojeg slabi obranu prijave, tako da uzimaju istu `currentPassword` ponovnu autorizaciju (kartica Sigurnost to traži) i JSON import ih ispušta.
- Svaki ključ sigurnosne politike — `SECURITY_IMPACTING_SETTINGS_KEYS` unosi, svaki ključ `oidc*` i stanje sesije nadzorne ploče — je** samo za operatera** na `PATCH /api/settings`: API ključ s opsegom upravljanja ili `oma_` pristupni token se odbija sa `403` čak i kada šalje pravi `currentPassword`, a odbijanje se revidira kao `settings.update_failed` sa `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` u `src/lib/api/operatorCredential.ts`). Uobičajene postavke (tema, postavke prikaza) mogu se pisati za `manage` ključ ili `admin` pristupni token. Svaka mutacija samog `/api/settings` a (i `/api/settings/require-login`-a) također treba `admin` opseg tokena pristupa (`ADMIN_MUTATION_EXACT_PATHS` u `src/server/authz/accessScopes.ts`, točno podudaranje putanje); `GET` ostaje `read`, a ostale `/api/settings/*` podsmjernice (proxiji, zadane vrijednosti kombinacije, pseudonimi modela, kompresija, čišćenja...) zadržavaju `write` opseg izveden metodom.
- `POST /api/settings/import-json` preskače tu ponovnu autorizaciju, tako da ispušta svaki ključ u `IMPORT_STRIPPED_SETTINGS_KEYS` (ista datoteka) prije pisanja: lozinku i `currentPassword`, svaki `SECURITY_IMPACTING_SETTINGS_KEYS` unos i stanje sesije nadzorne ploče (`sessionsValidAfter`, `revokedDashboardSessions`). Uvoz starije sigurnosne kopije stoga ne može oživjeti sesiju koja je već završena promjenom lozinke ili odjavom.

#### Izborna TOTP prijava u dva faktora (#16619)

Upisano iz postavki → Sigurnost; isključen dok ga operater ne uključi (`src/server/auth/dashboardMfa.ts`).

- **Što pokriva:** prijava lozinkom (`POST /api/auth/login`, koja tada treba `POST /api/auth/mfa/verify`) i `omniroute connect` (`POST /api/cli/connect`, koja odbija razmjenu samo lozinkom i uzima kod kao `totp`).
- **Što ne pokriva:** OIDC / SSO prijava (`/api/auth/oidc/callback`) ne traži OmniRoute TOTP. Oslanja se na drugi faktor davatelja identiteta, stoga nametnite MFA u IdP ako je OIDC omogućen.
- **Oporavak** (izgubljeni uređaj, nema preostalih kodova za oporavak ili faktor koji se više ne može potvrditi, na primjer nakon promjene `STORAGE_ENCRYPTION_KEY` ):
  1. Ponovno pokrenite poslužitelj sa `OMNIROUTE_DISABLE_MFA=true`.
  2. Na samom hostu (peer i povratna petlja `Host`, kao što je `http://localhost:20128`), prijavite se lozinkom. Drugi faktor se preskače samo za to podrijetlo; svako drugo podrijetlo i dalje treba kod.
  3. U Settings → Security → Disable unesite lozinku i ostavite kôd prazan. `POST /api/auth/mfa/disable` prihvaća tijelo bez `code` samo dok je varijabla postavljena i zahtjev dolazi od hosta; i dalje zahtijeva sesiju nadzorne ploče i trenutnu lozinku, a revidira se kao `auth.mfa.disabled` sa `secondFactor: "recovery_switch"`.
  4. Poništite `OMNIROUTE_DISABLE_MFA`, ponovno pokrenite i ponovno se prijavite ako je potrebno.

## Klase ruta

`src/server/authz/types.ts` definira tri klase; svaka ruta koju nije moguće deterministički klasificirati pada na `MANAGEMENT`.

| Klasa        | Opis                                                                                                                                                          | Potrebna autentifikacija                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| `PUBLIC`     | Izričito sigurne rute — prijava, odjava, status, inicijalizacija, health, bootstrap uvođenja.                                                                 | Nema                                                                  |
| `CLIENT_API` | Krajnje točke za posluživanje modela — `/api/v1/*`, `/api/v1beta/*` te aliasi `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer ključ kada je omogućena učinkovita zastavica `REQUIRE_API_KEY` |
| `MANAGEMENT` | Stranice nadzorne ploče, postavke, pružatelji, ključevi, administrativne i dijagnostičke krajnje točke.                                                       | Sesija nadzorne ploče ILI Bearer s opsegom `manage`                   |

Nekoliko radnji `MANAGEMENT` je **samo za operatora**: ključ `manage` nije dovoljan. Izvoz pohranjenih vjerodajnica (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), vraćanje sigurnosne kopije preko živih podataka (`POST /api/db-backups/import`, uključujući `dryRun=true`, `POST /api/db-backups` vraćanje po id-u, `POST /api/settings/import-json`) i uništavanje točaka vraćanja (čišćenje putem `DELETE /api/db-backups` i također `PATCH /api/db-backups`, jer zadržavanje koje spremi pokreće automatsko orezivanje nakon svake sigurnosne kopije) zahtijevaju sesiju nadzorne ploče, lokalni CLI subjekt ili onemogućenu prijavu. Izdavanje sinkronizacijskog tokena (`POST /api/sync/tokens`) i kovanje CLI pristupnog tokena s opsegom `admin` (`POST /api/cli/tokens`) zahtijevaju sesiju nadzorne ploče ili lokalni CLI subjekt u svim načinima prijave. API ključevi bilo kojeg opsega i `oma_` pristupni tokeni nisu operatorske vjerodajnice: kad se traži operatorska vjerodajnica, dobivaju `403`. Provjera se nalazi u `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Promjena postavki prijave također je rezervirana za operatora: `POST /api/settings/require-login` (postavljanje lozinke za upravljanje / prebacivanje `requireLogin`) prihvaća samo te vjerodajnice kada lozinka već postoji — prozor prvog pokretanja (još bez lozinke) ostaje nepromijenjen — a sesija nadzorne ploče mora poslati `currentPassword` kako bi zamijenila lozinku (`403` ako nedostaje ili je pogrešna, bilježi se kao `settings.update_failed`). Lokalni CLI i instanca s onemogućenom prijavom zadržavaju put oporavka i mogu postaviti lozinku bez nje, jer su obje vezane za host koji posjeduje podatkovni direktorij.

## Cjevovod

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

Pouzdana interna zaglavlja (definirana u `src/server/authz/headers.ts`) su** uklonjeni iz dolaznih zahtjeva** prije klasifikacije — klijenti ne mogu unaprijed popuniti `x-omniroute-auth-*` za oponašanje subjekta.

### Ugovori o policama

Svaka klasa rute ima politiku u `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — uvijek vraća `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — izvlači nositelja, potvrđuje putem `validateApiKey()`. Pada u anonimno samo kada je zastavica značajke efektivne `REQUIRE_API_KEY` onemogućena. Efektivna zastavica se rješava kroz `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) tako da Zastavice značajki nadzorne ploče i varijable okoline dosljedno upravljaju `/api/v1/*`, `/api/v1beta/*` i aliasima; kvarovi razrješitelja fail close. Omogućuje zahtjeve sesije nadzorne ploče na API rutama klijenta (uključujući `/api/v1/models`, koji koristi katalog modela nadzorne ploče). Kada je Entra ID SSO omogućen, Nositeljem koji je strukturno Entra token (tri base64url segmenta, `RS*` alg, `kid`) rukuje SSO grana** prije** `validateApiKey()` i njegova presuda je konačna — nikada ne prolazi kroz stazu API-ključa ili degrade-to-anonimous granu, tako da ispad pružatelja identiteta ne može postati otvoreni pristup. Statički API ključevi nisu pogođeni. Pogledajte [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — prihvaća sesiju nadzorne ploče, interne zahtjeve za sinkronizaciju modela (podudarne sa `/api/providers/[name]/(sync-models|models)`) ili potpuno preskače ako `isAuthRequired()` vrati false. Vraća 403 (`AUTH_001`) kada je token nositelja prisutan, ali nije valjan, 401 u suprotnom. Također provodi razine zaštite rute (LOCAL_ONLY / ALWAYS_PROTECTED) prije bilo koje grane autentifikacije — pogledajte [razine zaštite rute](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY stazama u `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (danas: `/api/mcp/`) može se pristupiti bez povratne petlje kada nositeljski ključ nosi `manage` opseg; sve ostale LOCAL_ONLY staze ostaju strict-loopback bez obzira na opseg.

Uspješna politika vraća `AuthSubject` sa `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Nizvodni rukovatelji mogu ga pročitati putem `assertAuth(request, "CLIENT_API")` u `src/server/authz/assertAuth.ts` umjesto ponovnog pokretanja logike autentifikacije.

## Popis javnih ruta

`src/shared/constants/publicApiRoutes.ts` je eksplicitna lista dopuštenih:

Popis je podijeljen prema** oblik** , a razdvajanje je nosivo (GHSA-74g9-q8f6-793h): prefiks se podudara sa `startsWith()`, tako da također odgovara svakoj susjednoj stazi koja dijeli svoje vodeće znakove. `/api/usage/om-usage` kao prefiks označen `/api/usage/om-usage<anything>` PUBLIC, a Next to rješava u `/api/usage/[connectionId]` — rukovatelja bez vlastite autentifikacije.

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

Rute samo za čitanje su javne** samo** za sigurne metode. Napomena: `classifyRoute()` isključuje `/api/v1/*` i `/api/v1beta/*` iz PUBLIC padajućih — koji su uvijek `CLIENT_API` tako da se pravilo ključa nositelja i dalje primjenjuje.

## Dodavanje nove rute

### Obrazac 1 — Javni API krajnji endpoint za klijente (Bearer autentifikacija)

Rute unutar `/api/v1/` i `/api/v1beta/` automatski se klasificiraju kao `CLIENT_API`. Middleware provodi provjeru Bearer vjerodajnice; rukovatelji rutama ne moraju je ponavljati, ali mogu pročitati subjekt ako im je to korisno.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... logika rukovatelja
}
```

### Obrazac 2 — Upravljački endpoint (sesija ili Bearer + manage)

Upotrijebite `requireManagementAuth()` iz `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... logika rukovatelja
}
```

`requireManagementAuth()` pri uspjehu vraća `null`, a pri pogrešci JSON `Response`:

- 401 `AUTH_001` "Potrebna je autentifikacija" — vjerodajnice uopće nisu navedene
- 403 — nevažeći Bearer **ili** je Bearer naveden, ali ključ nema opseg `manage` / `admin`

`hasManageScope(scopes)` vraća true za `"manage"` ili `"admin"`.

### Obrazac 3 — Dodavanje na javni popis dopuštenih ruta

Odaberite skup prema obliku, a ne prema praktičnosti. Jedna ruta ide u `PUBLIC_API_ROUTES_EXACT` (ili u `PUBLIC_READONLY_CORS_API_ROUTES` ako je namijenjena samo za GET); samo stvarno podstablo ide u `PUBLIC_API_ROUTE_PREFIXES` i ono **mora završavati znakom `/`**. Dodavanje pojedinačne rute na popis prefiksa također objavljuje svaku susjednu putanju koja dijeli njezine početne znakove — uključujući srodne rute s dinamičkim segmentima dodane kasnije (GHSA-74g9-q8f6-793h). Ažurirajte jedinične testove u `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` i `tests/unit/authz/classify.test.ts`.

## Opsezi

Tri imenska prostora. Svaki provjerivač čita samo vlastite nizove. Usporedba,
uključujući zašto `manage` ne uspijeva `scopeMatches` za `read:compression` i zašto
pristupni token `read` ne može `PATCH /api/keys/{id}`, nalazi se u
[Tri imenska prostora opsega](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API ključevi sadrže `scopes` niz (pohranjen kao JSON u `api_keys.scopes`, pogledajte `src/lib/db/apiKeys.ts`).

### Upravljački opseg

- `manage` / `admin` — `hasManageScope`. Nositeljski pristup rutama upravljačkog API-ja.
- `mcp:connect`, `self:usage`, `self:account-quota` i
  `policy:bypass-provider-quota` su aditivni opsezi s točnim podudaranjem. Nalaze se
  izvan `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` otvara samo
  `/api/mcp/` izuzetak koji nije povratna veza.

### Opsezi MCP alata

Katalog i pravila podudaranja (identičan niz znakova, ili dodijeljeni opseg koji završava s `*`):
[Opsezi MCP alata](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` u `src/shared/constants/mcpScopes.ts` je izvorni tipizirani
podskup, a ne taj potpuni katalog. Provedba se izvršava u
`open-sse/mcp-server/scopeEnforcement.ts` nakon što `resolveCallerScopeContext()`
razriješi opsege iz MCP informacija o autentifikaciji, metapodataka zahtjeva ili
`OMNIROUTE_MCP_SCOPES`. Ostaje isključena osim ako `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Opsezi pristupnog tokena

`read` / `write` / `admin` na `oma_live_…` tokenima, rangirani prema `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Ovaj rang se primjenjuje samo na
vjerodajnicu pristupnog tokena. Pogledajte [Upravljačka autentifikacija](../guides/MANAGEMENT-AUTH.md).

## Prekidač za zahtijevanu autentifikaciju

`isAuthRequired()` u `src/shared/utils/apiAuth.ts` odlučuje hoće li se za zahtjev provoditi **bilo kakva** autentifikacija:

- `settings.requireLogin === false` → autentifikacija je globalno isključena, osim za trajno zaštićenu razinu (vidi [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) i pozive koji izdaju vjerodajnicu koju ona prihvaća; oni zahtijevaju istu vjerodajnicu kao i pri uključenoj prijavi: izdavanje sinkronizacijskih tokena, kovanje CLI pristupnih tokena bilo kojeg opsega te stvaranje API ključa s opsegom `manage`/`admin`, dodjeljivanje tog opsega ključu, regeneriranje ili prikaz takvog ključa (`requireCredentialForManagementScopedKey()` u `src/lib/api/requireManagementAuth.ts`). Ključevi samo za inferenciju ostaju otvoreni.
- Nije postavljena lozinka **i** nije postavljena okolinska varijabla `INITIAL_PASSWORD` → bootstrap način dopušta čarobnjak za postavljanje i zahtjeve s loopbacka, ali mrežni zahtjevi izvana i dalje zahtijevaju vjerodajnice.
- Svaka pogreška baze → zatvoreno (secure-by-default).

Provedba API ključa klijenta koristi `isRequireApiKeyEnabled()` u `src/shared/utils/featureFlags.ts`, a ne izravno čitanje `process.env.REQUIRE_API_KEY`. To je važno za instalirane instance: prebacivanje `REQUIRE_API_KEY` u Dashboard → Feature Flags sprema nadjačavanje u bazu i odmah utječe na `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` i druge provjere autentifikacije klijentskog API-ja koje dijele ovaj pomoćnik. Ako se spremište zastavica ne može pročitati, autentifikacija klijentskog API-ja zatvara se i zahtijeva ključ.

## Nekompatibilna promjena — v3.8.0

Krajnje točke `/api/v1/agents/tasks/*` i `/api/resilience/model-cooldowns` **sada zahtijevaju autentifikaciju za upravljanje** (commit `588a0333`). Klijenti koji su prethodno slali običan API ključ bez opsega `manage` primaju `403`. Migracija: ključu dodijelite opseg `manage` na nadzornoj ploči API ključeva ili upotrijebite prijavljenu sesiju nadzorne ploče.

## Promjena ponašanja — v3.8.2

`/api/mcp/*` (udaljeni MCP poslužitelj) i dalje je prema zadanim postavkama LOCAL_ONLY, ali sada prihvaća zahtjeve koji ne dolaze s povratne petlje kada zaglavlje `Authorization: Bearer <api-key>` sadrži opseg `manage`. Iznimka se izričito omogućuje za svaku putanju putem `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` u `src/server/authz/routeGuard.ts`; srodni prefiks LOCAL_ONLY `/api/cli-tools/runtime/*` namjerno se ne može zaobići jer može pokrenuti proizvoljne potprocese. Anonimni zahtjevi prema `/api/mcp/*` koji ne dolaze s povratne petlje i dalje vraćaju `403 LOCAL_ONLY` — zadano ponašanje za svaku novu putanju LOCAL_ONLY ostaje strogo ograničeno na povratnu petlju. Pogledajte [Razine zaštite ruta](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testiranje

- Jedinični testovi: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Javni popis dopuštenih ruta: `tests/unit/public-api-routes.test.ts`.
- Pokretanje ciljanog testa: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Otklanjanje pogrešaka

Cjevovod uvijek označava odgovore sa:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Za autentificirane zahtjeve uzvodna (na strani rukovatelja) zaglavlja zahtjeva također uključuju:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Koristite `assertAuth(req, expectedClass)` unutar rukovatelja — koji izbacuje `AuthzAssertionError` s kodom `AUTHZ_NOT_INITIALIZED` ako je međuprogram zaobiđen (korisno za hvatanje konfiguracijskih regresija u testovima).

## Vidi također

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — oznaka autorizacije po krajnjoj točki
- [COMPLIANCE.md](../security/COMPLIANCE.md) — revizijski zapisnik za događaje autorizacije
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tri imenska prostora opsega i MCP katalog opsega alata
- Izvor: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
