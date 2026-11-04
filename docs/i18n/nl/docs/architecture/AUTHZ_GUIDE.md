# Authorization Guide (Nederlands)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Bron van waarheid:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Laatst bijgewerkt:** 2026-09-22 — scope-namespaces verwijzen naar MCP-SERVER.md

OmniRoute heeft een route-bewuste autorisatiepipeline die elke API-aanvraag afschermt. Classificatie is **deterministisch** en **fail-closed** — alles wat niet geclassificeerd kan worden, eindigt als `MANAGEMENT` en vereist een sessie of een token van managementkwaliteit. Deze pagina legt het model uit voor engineers die routes onderhouden of nieuwe endpoints ontwerpen.

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> Bron: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Twee verificatiemodi

### 1. API sleutel (drager)

Wordt gebruikt voor de OpenAI/Anthropic/Gemini-compatible client APIs en een paar beheerroutes wanneer de sleutel het `manage` bereik heeft.

```
Authorization: Bearer <api-key>
```

Gevalideerd door `isValidApiKey()` / `extractApiKey()` in `src/sse/services/auth.ts` en opnieuw geëxporteerd via `src/shared/utils/apiAuth.ts`. De validator accepteert ook de `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars als persistente passthrough-sleutels (probleem #1350).

### 2. Dashboardsessie (auth_token cookie)

Voor dashboardpagina's en beheerdersactiviteiten.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Een cookie is pas een sessie als de JWT dit verifieert** En** draagt `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Elke consument van de cookie (dashboard route guard (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, live server, `/api/settings/require-login`, `/api/auth/status`) gaat door die helper. Andere JWTs ondertekend met `JWT_SECRET` bestaan — de Cursor CLI passthrough pepermuntjes `iss "omniroute" / aud "cursor-cli"` tokens voor sleutelhouders — en zijn nooit sessies (#13298).

Geverifieerd door `isDashboardSessionAuthenticated()` in `src/shared/utils/apiAuth.ts`. De pijplijn vernieuwt de JWT automatisch wanneer deze minder dan zeven dagen over heeft in de levensduur van 30 dagen.

Een sessie kan ook eindigen voordat de 30 dagen voorbij zijn, omdat elke minter `mintDashboardSessionToken` doorloopt (een uitgiftetijd `iat` en een id `jti`) en de verifier twee instellingen controleert: `sessionsValidAfter`, ingesteld door een wachtwoordwijziging, zodat elke sessie die wordt uitgegeven voordat deze stopt met verifiëren (de browser die het wachtwoord heeft gewijzigd, een nieuwe cookie krijgt), en `revokedDashboardSessions`, waaraan `POST /api/auth/logout` de `jti` van de afgemelde sessie toevoegt. Sessies die door een oudere release zijn aangemaakt, hebben geen enkele claim en blijven geldig tot de eerste wachtwoordwijziging. Als de instellingen niet kunnen worden gelezen, wordt de sessie niet vertrouwd.

Sommige managementroutes accepteren dit** of** modus: cookie OR `Bearer <key>` wanneer de API sleutel het bereik `manage` (of `admin`) heeft. Dit is wat de workflow "configureerbaar via API -aanroepen" mogelijk maakt die is toegevoegd in v3.8.

#### Optionele OIDC inlogpoort (#6973)

De dashboardbeheerderaanmelding ondersteunt ook een** aanmelden** OIDC (OpenID Connect) stroom naast het standaard wachtwoord login — wachtwoord login wordt nooit verwijderd, alleen aangevuld:

- Uitgeschakeld tenzij `settings.oidcEnabled === true`** En** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` zijn allemaal geconfigureerd (Instellingen → Auth). `GET /api/auth/oidc/login` retourneert anders `400`.
- `GET /api/auth/oidc/login` ontdekt de `authorization_endpoint` van de `/.well-known/openid-configuration` van de uitgever (valt terug naar `<issuer>/authorize`), bouwt de omleiding URI op van het inkomende verzoek (`x-forwarded-proto` -aware), en verwijst door naar de IdP met een willekeurige `state` opgeslagen in een `httpOnly` `oidc_state` cookie.
- `GET /api/auth/oidc/callback` valideert `state`, wisselt de autorisatiecode uit en verifieert de handtekening van het ID token via de JWKS van de uitgever (`jose`'s `createRemoteJWKSet`, in de cache opgeslagen per JWKS URI) met `issuer`/`audience` -controles. Voor toegang tot het dashboard is een niet-lege `oidcAllowedSubjects` lijst, een `oidcAdmissionClaim` beleid of beide vereist. De onderwerpenlijst komt alleen overeen met `sub` of `email` als `email_verified === true`. Het optionele claimbeleid gebruikt een door punten gescheiden ID-token-claimpad (bijvoorbeeld `realm_access.roles`) en een array met geaccepteerde waarden; de opgeloste claim moet een array van tekenreeksen zijn die ten minste één geaccepteerde waarde bevatten. Als beide beleidsregels zijn geconfigureerd, moeten beide worden goedgekeurd. Missing/malformed -claims mislukken, en zonder een van beide beleid weigert de callback login (`not_configured`). Bestaande configuraties voor alleen onderwerpen blijven ongewijzigd.
- Keycloak wijst realm-rollen normaal gesproken toe aan toegangstokens, niet noodzakelijkerwijs ID tokens. Om de realm-rol `admin` te vereisen, configureert u een protocoltoewijzer voor deze client die `realm_access.roles` in zijn bestand bevat**ID -token** en stel vervolgens `oidcAdmissionClaim` in op `{ "path": "realm_access.roles", "values": ["admin"] }`. Controleer de daadwerkelijke ID-tokenclaim voor deze client voordat u alleen-roltoegang inschakelt; de toepassing leest geen toegangstokenrollen. Tokenweigering aan de IdP-zijde kan deze controle aan de toepassingszijde aanvullen, maar vervangt deze niet.
- Bij succes wordt de munt geslagen** precies hetzelfde** 30 dagen `auth_token` JWT de problemen met het inloggen op het wachtwoord (`src/app/api/auth/login/route.ts`), dus de rest van de pijplijn van de dashboardsessie (automatisch vernieuwen, cookievlaggen) blijft ongewijzigd — OIDC vervangt alleen hoe de cookie wordt aangemaakt, niet wat deze toekent. Wijzigingen in IdP roles/groups maken bestaande OmniRoute sessies niet ongeldig; uitloggen, wachtwoordrotatie of het verlopen van een sessie bepalen nog steeds hun levensduur.
- Elke `oidc*` instelling (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) bevindt zich in `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` antwoordt `400 PASSWORD_REQUIRED` tenzij de instantie het beheerwachtwoord als `currentPassword` draagt (`401 PASSWORD_MISMATCH` als het verkeerd is). `oidcDisablePasswordLogin` weigert wachtwoord _login_ (`POST /api/auth/login`) maar behoudt de opgeslagen wachtwoord-hash, en opnieuw verifiëren controleert `currentPassword` er nog steeds op.
- `corsOrigins` en `bruteForceProtection` zitten ook in `SECURITY_IMPACTING_SETTINGS_KEYS` : het losmaken van beide verzwakt de inlogverdedigingen, dus nemen ze dezelfde `currentPassword` -herauthenticatie (het tabblad Beveiliging vraagt erom) en de JSON import verwijdert ze.
- Elke beveiligingsbeleidssleutel — de `SECURITY_IMPACTING_SETTINGS_KEYS` -vermeldingen, elke `oidc*` sleutel en de dashboardsessiestatus — is** alleen voor de operator** op `PATCH /api/settings`: een API -sleutel met beheerbereik of een `oma_` toegangstoken wordt geweigerd met `403` zelfs wanneer deze de juiste `currentPassword` verzendt, en de weigering wordt gecontroleerd als `settings.update_failed` met `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`). Gewone instellingen (thema, weergavevoorkeuren) blijven beschrijfbaar voor een `manage` sleutel of een `admin` toegangstoken. Elke mutatie van `/api/settings` zelf (en van `/api/settings/require-login`) heeft ook de `admin` access-token scope nodig (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, exact-path match); `GET` blijft `read`, en de andere `/api/settings/*` -subroutes (proxy's, combo-standaardwaarden, modelaliassen, compressie, opschoningen...) behouden de door de methode afgeleide `write` scope.
- `POST /api/settings/import-json` slaat die herauthenticatie over, dus laat het elke sleutel in `IMPORT_STRIPPED_SETTINGS_KEYS` (hetzelfde bestand) vallen voordat het wordt geschreven: het wachtwoord en `currentPassword`, elke `SECURITY_IMPACTING_SETTINGS_KEYS` invoer en de dashboardsessiestatus (`sessionsValidAfter`, `revokedDashboardSessions`). Het importeren van een oudere back-up kan daarom een sessie waarin een wachtwoordwijziging of een afmelding al is beëindigd, niet nieuw leven inblazen.

#### Optioneel TOTP twee-factor login (#16619)

Ingeschreven via Instellingen → Beveiliging; uitgeschakeld totdat de operator het inschakelt (`src/server/auth/dashboardMfa.ts`).

- **Wat het omvat:** wachtwoord login (`POST /api/auth/login`, dat dan `POST /api/auth/mfa/verify` nodig heeft ) en `omniroute connect` (`POST /api/cli/connect`, dat een uitwisseling van alleen wachtwoorden weigert en de code als `totp` aanneemt).
- **Wat er niet onder valt:** OIDC / SSO sign-in (`/api/auth/oidc/callback`) vraagt niet om de OmniRoute TOTP. Het is afhankelijk van de tweede factor van de identiteitsprovider, dus dwing MFA af in de IdP als OIDC is ingeschakeld.
- **Herstel** (apparaat verloren, geen herstelcodes meer, of een factor die niet meer kan worden geverifieerd, bijvoorbeeld nadat `STORAGE_ENCRYPTION_KEY` is gewijzigd):
  1. Start de server opnieuw op met `OMNIROUTE_DISABLE_MFA=true`.
  2. Op de host zelf (loopback peer en loopback `Host`, zoals `http://localhost:20128`), logt u in met het wachtwoord. Alleen voor die herkomst wordt de tweede factor overgeslagen; elke andere oorsprong heeft nog steeds de code nodig.
  3. Voer in Instellingen → Beveiliging → Uitschakelen het wachtwoord in en laat de code leeg. `POST /api/auth/mfa/disable` accepteert alleen een body zonder `code` als de variabele is ingesteld en het verzoek van de host komt; het vereist nog steeds de dashboardsessie en het huidige wachtwoord, en wordt gecontroleerd als `auth.mfa.disabled` met `secondFactor: "recovery_switch"`.
  4. Schakel `OMNIROUTE_DISABLE_MFA` uit, start opnieuw op en schrijf u indien nodig opnieuw in.

## Routeklassen

`src/server/authz/types.ts` definieert drie klassen; elke route die niet deterministisch kan worden geclassificeerd, valt terug op `MANAGEMENT`.

| Klasse       | Beschrijving                                                                                                                                                   | Authenticatie vereist                                                              |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `PUBLIC`     | Expliciet veilige routes: aanmelden, afmelden, status, initialisatie, health-check en onboarding-bootstrap.                                                    | Geen                                                                               |
| `CLIENT_API` | Eindpunten voor modelbediening: `/api/v1/*`, `/api/v1beta/*`, plus de aliassen `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer-sleutel wanneer de effectieve `REQUIRE_API_KEY`-featureflag is ingeschakeld |
| `MANAGEMENT` | Dashboardpagina's, instellingen, providers, sleutels, beheer- en diagnose-eindpunten.                                                                          | Dashboardsessie OF Bearer met scope `manage`                                       |

Enkele `MANAGEMENT`-acties zijn **alleen voor de operator**: een `manage`-sleutel is niet voldoende. Opgeslagen inloggegevens exporteren (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), een back-up herstellen over de actieve gegevens (`POST /api/db-backups/import`, ook met `dryRun=true`, `POST /api/db-backups` met herstel op id, `POST /api/settings/import-json`), en herstelpunten vernietigen (opschonen via `DELETE /api/db-backups` en `PATCH /api/db-backups`, omdat de bewaartermijn die het opslaat de automatische opschoning na elke back-up bepaalt) vereisen een dashboardsessie, de identiteit van de lokale CLI of uitgeschakelde aanmelding. Het uitgeven van een synchronisatietoken (`POST /api/sync/tokens`) en het aanmaken van een CLI-toegangstoken met scope `admin` (`POST /api/cli/tokens`) vereisen in elke aanmeldmodus een dashboardsessie of de identiteit van de lokale CLI. API-sleutels van elke scope en `oma_`-toegangstokens zijn geen operatorcredentials: ze krijgen `403` wanneer er een vereist is. De controle staat in `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Het wijzigen van de aanmeldinstellingen is ook alleen voor de operator: `POST /api/settings/require-login` (het beheerwachtwoord instellen / `requireLogin` in- of uitschakelen) accepteert deze credentials alleen zodra er al een wachtwoord bestaat. Het bootstrapvenster van de eerste start (nog geen wachtwoord) blijft ongewijzigd, en een dashboardsessie moet `currentPassword` meesturen om het wachtwoord te vervangen (`403` als het ontbreekt of onjuist is, gelogd als `settings.update_failed`). De lokale CLI en een instantie met uitgeschakelde aanmelding behouden het herstelpad en mogen zonder die stap een wachtwoord instellen, omdat beide gebonden zijn aan de host die de gegevensmap bezit.

## Pijpleiding

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

Vertrouwde interne headers (gedefinieerd in `src/server/authz/headers.ts`) zijn dat wel** ontdaan van inkomende verzoeken** vóór classificatie kunnen — clients `x-omniroute-auth-*` niet vooraf invullen om een onderwerp na te bootsen.

### Beleidscontracten

Elke routeklasse heeft een beleid in `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — retourneert altijd `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — extraheert Bearer, valideert via `validateApiKey()`. Valt alleen door naar anoniem wanneer de effectieve `REQUIRE_API_KEY` functievlag is uitgeschakeld. De effectieve vlag wordt opgelost via `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), zodat Dashboard Feature Flags en omgevingsvariabelen `/api/v1/*`, `/api/v1beta/*` en aliassen consistent beheren; fouten in de oplosser zijn mislukt. Staat dashboardsessieverzoeken toe op client API routes (inclusief `/api/v1/models`, gebruikt door de dashboardmodelcatalogus). Wanneer Entra ID SSO is ingeschakeld, wordt een Bearer die structureel een Entra-token is (drie base64url-segmenten, `RS*` alg, `kid`) afgehandeld door de SSO vertakking** voor** `validateApiKey()` en zijn oordeel is definitief. — valt nooit door naar het API-sleutelpad of de degrade-naar-anonieme vertakking, dus een storing van de identiteitsprovider kan geen open toegang worden. Statische API sleutels worden niet beïnvloed. Zie [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — accepteert dashboardsessies, interne modelsynchronisatieverzoeken (gematcht met `/api/providers/[name]/(sync-models|models)`), of slaat deze volledig over als `isAuthRequired()` false retourneert. Retourneert 403 (`AUTH_001`) wanneer een Bearer-token aanwezig is maar ongeldig, anders 401. Dwingt ook de route-guard-niveaus (LOCAL_ONLY / ALWAYS_PROTECTED) af vóór elke auth-vertakking — zie [Route Guard-niveaus](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY paden in `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (vandaag: `/api/mcp/`) zijn toegankelijk vanuit niet-loopback wanneer de Bearer-sleutel de `manage` scope draagt; alle andere LOCAL_ONLY paden blijven strikte loopback, ongeacht de reikwijdte.

Een succesvol beleid retourneert `AuthSubject` met `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Stroomafwaartse handlers kunnen het lezen via `assertAuth(request, "CLIENT_API")` in `src/server/authz/assertAuth.ts` in plaats van de auth-logica opnieuw uit te voeren.

## Lijst met openbare routes

`src/shared/constants/publicApiRoutes.ts` is de expliciete toelatingslijst:

De lijst is opgesplitst per** vorm** , en de splitsing is dragend (GHSA-74g9-q8f6-793h): een voorvoegsel wordt gekoppeld aan `startsWith()`, dus het komt ook overeen met elk aangrenzend pad dat de hoofdletters deelt. `/api/usage/om-usage` als voorvoegsel gemarkeerd `/api/usage/om-usage<anything>` PUBLIC, en Next lost dat op in `/api/usage/[connectionId]` — een handler zonder eigen authenticatie.

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

Alleen-lezen routes zijn openbaar** alleen** voor veilige methoden. Opmerking: `classifyRoute()` sluit `/api/v1/*` en `/api/v1beta/*` uit van de PUBLIC fall-through — deze zijn altijd `CLIENT_API` dus het Bearer-key-beleid is nog steeds van toepassing.

## Een nieuwe route toevoegen

### Patroon 1 — Openbaar client-API-eindpunt (Bearer-authenticatie)

Routes onder `/api/v1/` en `/api/v1beta/` worden automatisch geclassificeerd als `CLIENT_API`. De middleware dwingt de Bearer-controle af; routehandlers hoeven deze niet opnieuw uit te voeren, maar kunnen het subject uitlezen als dat nuttig is.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handlerlogica
}
```

### Patroon 2 — Beheereindpunt (sessie of Bearer + manage)

Gebruik `requireManagementAuth()` uit `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handlerlogica
}
```

`requireManagementAuth()` retourneert `null` bij succes of een JSON-fout-`Response`:

- 401 `AUTH_001` "Authenticatie vereist" — er zijn helemaal geen referenties aanwezig
- 403 — ongeldige Bearer **of** Bearer aanwezig, maar de sleutel mist het bereik `manage` / `admin`

`hasManageScope(scopes)` retourneert true voor `"manage"` of `"admin"`.

### Patroon 3 — Toevoegen aan de openbare toelatingslijst

Kies de verzameling op basis van de vorm, niet op basis van gemak. Eén route hoort in `PUBLIC_API_ROUTES_EXACT` (of in `PUBLIC_READONLY_CORS_API_ROUTES` als deze alleen GET ondersteunt); alleen een echte substructuur hoort in `PUBLIC_API_ROUTE_PREFIXES`, en deze **moet eindigen op `/`**. Door één route in de prefixlijst te plaatsen, worden ook alle aangrenzende paden met dezelfde begintekens openbaar gemaakt — inclusief later toegevoegde siblings met dynamische segmenten (GHSA-74g9-q8f6-793h). Werk de unit-tests bij in `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` en `tests/unit/authz/classify.test.ts`.

## Scopes

Drie namespaces. Elke checker leest alleen zijn eigen strings. De vergelijking,
inclusief waarom `manage` faalt bij `scopeMatches` voor `read:compression` en waarom een
`read` access token geen `PATCH /api/keys/{id}` kan uitvoeren, is
[Drie scope namespaces](../frameworks/MCP-SERVER.md#drie-scope-namespaces).

API-sleutels bevatten een `scopes` array (opgeslagen als JSON in `api_keys.scopes`, zie `src/lib/db/apiKeys.ts`).

### Management scope

- `manage` / `admin` — `hasManageScope`. Bearer-toegang tot management API-routes.
- `mcp:connect`, `self:usage`, `self:account-quota`, en
  `policy:bypass-provider-quota` zijn additieve exact-match scopes. Ze vallen
  buiten `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` opent alleen de
  `/api/mcp/` non-loopback carve-out.

### MCP tool scopes

Catalogus en matchingregels (identieke string, of een toegekende scope eindigend op `*`):
[MCP tool scopes](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` in `src/shared/constants/mcpScopes.ts` is de originele getypeerde
subset, niet die volledige catalogus. Handhaving vindt plaats in
`open-sse/mcp-server/scopeEnforcement.ts` nadat `resolveCallerScopeContext()`
scopes oplost uit MCP auth info, request metadata, of `OMNIROUTE_MCP_SCOPES`.
Het blijft uitgeschakeld tenzij `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Access-token scopes

`read` / `write` / `admin` op `oma_live_…` tokens, gerangschikt door `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Deze rangschikking is alleen van toepassing op de
access-token credential. Zie [Management Authenticatie](../guides/MANAGEMENT-AUTH.md).

## Schakelaar voor vereiste authenticatie

`isAuthRequired()` in `src/shared/utils/apiAuth.ts` bepaalt of **enige** authenticatie wordt afgedwongen voor een verzoek:

- `settings.requireLogin === false` → authenticatie is globaal uitgeschakeld, behalve voor het altijd beschermde niveau (zie [Route Guard-niveaus](../security/ROUTE_GUARD_TIERS.md)) en de aanroepen die een credential uitgeven dat het accepteert. Die vereisen dezelfde credential als wanneer aanmelding aan staat: synchronisatietokens uitgeven, CLI-toegangstokens met elke scope aanmaken, een API-sleutel met scope `manage`/`admin` aanmaken, die scope aan een sleutel toekennen, of zo'n sleutel opnieuw genereren of tonen (`requireCredentialForManagementScopedKey()` in `src/lib/api/requireManagementAuth.ts`). Sleutels die alleen voor inferentie zijn, blijven open.
- Geen wachtwoord ingesteld **en** geen omgevingsvariabele `INITIAL_PASSWORD` → de bootstrapmodus staat de onboardingwizard en loopback-verzoeken toe, maar blootgestelde netwerkverzoeken hebben nog steeds credentials nodig.
- Elke databasefout → faalt gesloten (veilig per standaard).

Het afdwingen van client-API-sleutels gebruikt `isRequireApiKeyEnabled()` in `src/shared/utils/featureFlags.ts`, en niet een directe lezing van `process.env.REQUIRE_API_KEY`. Dit is belangrijk voor uitgerolde instanties: `REQUIRE_API_KEY` wijzigen in Dashboard → Feature Flags slaat een databaseoverschrijving op en werkt meteen door op `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` en de andere authenticatiecontroles van de client-API die deze helper delen. Als de opslag van de featureflags niet kan worden gelezen, faalt de authenticatie van de client-API gesloten en vereist ze een sleutel.

## Incompatibele wijziging — v3.8.0

De eindpunten `/api/v1/agents/tasks/*` en `/api/resilience/model-cooldowns` **vereisen nu beheerauthenticatie** (commit `588a0333`). Clients die eerder een normale API-sleutel zonder de scope `manage` verzonden, ontvangen `403`. Migratie: wijs de scope `manage` toe aan de sleutel in het API Keys-dashboard of gebruik een aangemelde dashboardsessie.

## Gedragswijziging — v3.8.2

`/api/mcp/*` (de externe MCP-server) is standaard nog steeds LOCAL_ONLY, maar accepteert nu niet-loopbackrequests wanneer de header `Authorization: Bearer <api-key>` de scope `manage` bevat. De uitzondering wordt expliciet per pad beheerd via `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` in `src/server/authz/routeGuard.ts`; het verwante LOCAL_ONLY-prefix `/api/cli-tools/runtime/*` kan bewust NIET worden omzeild, omdat het willekeurige subprocessen kan starten. Anonieme requests naar `/api/mcp/*` die niet van loopback afkomstig zijn, blijven `403 LOCAL_ONLY` retourneren — de standaard voor elk nieuw LOCAL_ONLY-pad blijft strikt beperkt tot loopback. Zie [Route Guard-niveaus](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testen

- Unittests: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Openbare toelatingslijst: `tests/unit/public-api-routes.test.ts`.
- Gericht uitvoeren: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Foutopsporing

De pijplijn stempelt antwoorden altijd met:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Voor geauthenticeerde verzoeken bevatten de upstream (handlerzijde) verzoekheaders ook:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Gebruik `assertAuth(req, expectedClass)` binnen handlers — het gooit `AuthzAssertionError` met code `AUTHZ_NOT_INITIALIZED` als de middleware werd omzeild (handig voor het opvangen van configuratieregressies in tests).

## Zie ook

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — auth marker per eindpunt
- [COMPLIANCE.md](../security/COMPLIANCE.md) — auditlog voor auth-gebeurtenissen
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — drie scope-namespaces en MCP tool-scope catalogus
- Bron: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
