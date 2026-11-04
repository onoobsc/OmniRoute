# Authorization Guide (Dansk)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Sandhedskilde:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Senest opdateret:** 2026-09-22 — scope-navnerum peger på MCP-SERVER.md

OmniRoute har en rutebevidst autorisationspipeline, der beskytter hver API-anmodning. Klassificeringen er **deterministisk** og **lukket som standard** — alt, der ikke kan klassificeres, ender som `MANAGEMENT` og kræver en session eller et token på administrationsniveau. Denne side forklarer modellen for teknikere, der vedligeholder ruter eller designer nye slutpunkter.

![AuthZ-pipeline (3 ruteklasser + politikevaluering)](../diagrams/exported/authz-pipeline.svg)

> Kilde: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## To Auth Modes

### 1. API nøgle (bærer)

Bruges til OpenAI/Anthropic/Gemini-compatible klienten APIs og nogle få administrationsruter, når nøglen har `manage` omfanget.

```
Authorization: Bearer <api-key>
```

Valideret af `isValidApiKey()` / `extractApiKey()` i `src/sse/services/auth.ts` og reeksporteret gennem `src/shared/utils/apiAuth.ts`. Validatoren accepterer også `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars som vedvarende passthrough-nøgler (problem #1350).

### 2. Dashboard-session (auth_token-cookie)

Til dashboard-sider og admin-handlinger.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

En cookie er kun en session, når JWT bekræfter** og** bærer `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Hver forbruger af cookien (dashboard route guard (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, live server, `/api/settings/require-login`, `/api/auth/status`) går gennem denne hjælper. Andre JWTs signeret med `JWT_SECRET` eksisterer — Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` tokens for nøgleholdere — og er aldrig sessioner (#13298).

Verificeret af `isDashboardSessionAuthenticated()` i `src/shared/utils/apiAuth.ts`. Pipelinen genopfrisker automatisk JWT, når den har færre end 7 dage tilbage i sin 30-dages levetid.

En session kan også afsluttes, før dens 30 dage er gået, fordi hver minter går gennem `mintDashboardSessionToken` (en udgivelsestid `iat` og en id `jti`), og verifikatoren kontrollerer to indstillinger: `sessionsValidAfter`, indstillet af en adgangskodeændring, så hver session, der udstedes, før den stopper med at bekræfte (browseren, der ændrede adgangskoden, får en ny cookie), og `revokedDashboardSessions`, som `POST /api/auth/logout` -sessionen `jti` til. Sessioner, der er præget af en ældre udgivelse, har ingen krav og forbliver gyldige, indtil den første adgangskodeændring. Hvis indstillingerne ikke kan læses, er sessionen ikke tillid.

Nogle ledelsesruter accepterer** enten** tilstand: cookie OR `Bearer <key>` når API tasten har `manage` (eller `admin`) omfanget. Dette er, hvad der aktiverer arbejdsgangen "konfigurerbar via API -opkald" tilføjet i v3.8.

#### Valgfri OIDC login gate (#6973)

Dashboard admin login understøtter også en** opt-in** OIDC (OpenID Connect) flow sammen med standard password login — password login fjernes aldrig, kun suppleret:

- Deaktiveret, medmindre `settings.oidcEnabled === true`** og** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` er alle konfigureret (Settings → Auth). `GET /api/auth/oidc/login` returnerer `400` ellers.
- `GET /api/auth/oidc/login` opdager `authorization_endpoint` fra udstederens `/.well-known/openid-configuration` (falder tilbage til `<issuer>/authorize`), bygger omdirigeringen URI fra den indkommende anmodning (`x-forwarded-proto` -aware), og omdirigerer til IdP med en tilfældig `state` gemt i en `httpOnly` `oidc_state` cookie.
- `GET /api/auth/oidc/callback` validerer `state`, udveksler autorisationskoden og verificerer ID tokenets signatur via udstederens JWKS (`jose`'s `createRemoteJWKSet`, cachelagret pr. JWKS URI) med `issuer`/`audience` checks. Adgang til dashboard kræver en ikke-tom `oidcAllowedSubjects` liste, en `oidcAdmissionClaim` -politik eller begge dele. Emnelisten matcher kun `sub` eller `email` når `email_verified === true`. Den valgfrie kravpolitik tager en punktsepareret ID-token-kravsti (for eksempel `realm_access.roles`) og en række accepterede værdier; det løste krav skal være en række strenge, der indeholder mindst én accepteret værdi. Hvis begge politikker er konfigureret, skal begge bestå. Missing/malformed kravene fejler lukket, og uden nogen af politikkerne nægter tilbagekaldet login (`not_configured`). Eksisterende emnekonfigurationer fortsætter uændret.
- Keycloak kortlægger normalt realm-roller til adgangstokens, ikke nødvendigvis ID -tokens. For at kræve realm-rollen `admin` skal du konfigurere en protokolmapper for denne klient, der inkluderer `realm_access.roles` i sin**ID token** , og indstil derefter `oidcAdmissionClaim` til `{ "path": "realm_access.roles", "values": ["admin"] }`. Tjek det faktiske ID-tokenkrav for denne klient, før du aktiverer kun rolle-adgang; applikationen læser ikke adgangstoken-roller. IdP-side token-afslag kan supplere, men erstatter ikke dette applikationsside-tjek.
- På succes det præger den** nøjagtig samme** 30-dages `auth_token` JWT adgangskoden login problemer (`src/app/api/auth/login/route.ts`), så resten af dashboard session pipeline (auto-refresh, cookie flag) er uændret — OIDC erstatter kun hvordan cookien bliver præget, ikke hvad den giver. Ændringer i IdP roles/groups ugyldiggør ikke eksisterende OmniRoute sessioner; logout, adgangskoderotation eller sessionsudløb styrer stadig deres levetid.
- Hver `oidc*` indstilling (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) er i `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` svarer `400 PASSWORD_REQUIRED` medmindre kroppen bærer administrationsadgangskoden som `currentPassword` (`401 PASSWORD_MISMATCH` når den er forkert). `oidcDisablePasswordLogin` nægter adgangskode _login_ (`POST /api/auth/login`), men beholder den gemte adgangskode hash, og re-auth tjekker stadig `currentPassword` mod det.
- `corsOrigins` og `bruteForceProtection` er også i `SECURITY_IMPACTING_SETTINGS_KEYS` : Løsning enten svækker login-forsvaret, så de tager den samme `currentPassword` -gengodkendelse (fanen Sikkerhed beder om det), og JSON importen dropper dem.
- Hver sikkerhedspolitiknøgle — `SECURITY_IMPACTING_SETTINGS_KEYS` posterne, hver `oidc*` nøgle og dashboardsessionstilstanden — er** kun operatør** på `PATCH /api/settings`: en API -nøgle med styringsområde eller et `oma_` adgangstoken afvises med `403` selv når det sender den rigtige `currentPassword`, og afslaget revideres som `settings.update_failed` med `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` i `src/lib/api/operatorCredential.ts`). Almindelige indstillinger (tema, visningspræferencer) forbliver skrivbare for en `manage` nøgle eller et `admin` -adgangstoken. Enhver mutation af `/api/settings` selv (og af `/api/settings/require-login`) har også brug for `admin` -adgangstoken-omfanget (`ADMIN_MUTATION_EXACT_PATHS` i `src/server/authz/accessScopes.ts`, nøjagtig-sti-match); `GET` forbliver `read`, og de andre `/api/settings/*` -underruter (proxies, combo-standarder, modelaliaser, komprimering, udrensninger...) beholder det metodeudledte `write` omfang.
- `POST /api/settings/import-json` springer den gengodkendelse over, så den slipper hver tast i `IMPORT_STRIPPED_SETTINGS_KEYS` (samme fil), før den skrives: adgangskoden og `currentPassword`, hver `SECURITY_IMPACTING_SETTINGS_KEYS` indgang og dashboard-sessionstilstanden (`sessionsValidAfter`, `revokedDashboardSessions`). Import af en ældre backup kan derfor ikke genoplive en session, hvor en adgangskodeændring eller en log-out allerede er afsluttet.

#### Valgfri TOTP to-faktor login (#16619)

Tilmeldt fra Indstillinger → Security; slukket, indtil operatøren tænder (`src/server/auth/dashboardMfa.ts`).

- **Hvad det dækker:** password login (`POST /api/auth/login`, som så har brug for `POST /api/auth/mfa/verify`) og `omniroute connect` (`POST /api/cli/connect`, som nægter en adgangskode-kun udveksling og tager koden som `totp`).
- **Hvad det ikke dækker:** OIDC / SSO -logon (`/api/auth/oidc/callback`) beder ikke om OmniRoute TOTP. Den er afhængig af identitetsudbyderens egen anden faktor, så håndhæv MFA i IdP, hvis OIDC er aktiveret.
- **Genopretning** (tabt enhed, ingen gendannelseskoder tilbage eller en faktor, der ikke længere kan verificeres, for eksempel efter `STORAGE_ENCRYPTION_KEY` ændret):
  1. Genstart serveren med `OMNIROUTE_DISABLE_MFA=true`.
  2. På selve værten (loopback peer og loopback `Host`, såsom `http://localhost:20128`), skal du logge ind med adgangskoden. Den anden faktor springes kun over for denne oprindelse; hver anden oprindelse har stadig brug for koden.
  3. I Indstillinger → Security → Deaktiver skal du indtaste adgangskoden og lade koden være tom. `POST /api/auth/mfa/disable` accepterer kun en body uden `code`, mens variablen er indstillet, og anmodningen kommer fra værten; det kræver stadig dashboard-sessionen og den aktuelle adgangskode og revideres som `auth.mfa.disabled` med `secondFactor: "recovery_switch"`.
  4. Fjern `OMNIROUTE_DISABLE_MFA`, genstart, og tilmeld dig igen, hvis det er nødvendigt.

## Rutetyper

`src/server/authz/types.ts` definerer tre typer. Enhver rute, der ikke kan klassificeres deterministisk, falder tilbage til `MANAGEMENT`.

| Type         | Beskrivning                                                                                                                                              | Godkendelse påkrævet                                             |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| `PUBLIC`     | Eksplicit sikre ruter: login, logout, status, init, healthcheck og onboarding-bootstrap.                                                                 | Ingen                                                            |
| `CLIENT_API` | Endpoints til modelbetjening: `/api/v1/*`, `/api/v1beta/*` samt aliasene `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer-nøgle, når feature flag'et `REQUIRE_API_KEY` er aktiveret |
| `MANAGEMENT` | Dashboardsider, indstillinger, udbydere, nøgler, admin- og diagnostikendpoints.                                                                          | Dashboardsession ELLER Bearer med scopet `manage`                |

Nogle `MANAGEMENT`-handlinger er **kun for operatøren**: en nøgle med scopet `manage` er ikke nok. Eksport af gemte loginoplysninger (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), gendannelse af en backup over de aktuelle data (`POST /api/db-backups/import` inklusive `dryRun=true`, `POST /api/db-backups` gendannelse via id, `POST /api/settings/import-json`) og sletning af gendannelsespunkter (`DELETE /api/db-backups` oprydning, og `PATCH /api/db-backups`, fordi den gemte retention styrer den automatiske oprydning efter hver backup) kræver en dashboardsession, den lokale CLI-identitet eller at login er deaktiveret. Udstedelse af et synkroniseringstoken (`POST /api/sync/tokens`) og oprettelse af et `admin`-CLI-adgangstoken (`POST /api/cli/tokens`) kræver en dashboardsession eller den lokale CLI-identitet i alle login-tilstande. API-nøgler med vilket som helst scope og `oma_`-adgangstokens er ikke operatørlegitimationsoplysninger: de får `403`, når en sådan kræves. Kontrollen ligger i `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Ændring af loginindstillingerne er også kun for operatøren: `POST /api/settings/require-login` (sæt administrationsadgangskoden / skift `requireLogin`) accepterer kun disse legitimationsoplysninger, når der først findes en adgangskode. Bootstrap-vinduet ved første opsætning (ingen adgangskode endnu) er uændret, og en dashboardsession skal sende `currentPassword` for at erstatte adgangskoden (`403`, når den mangler eller er forkert, logget som `settings.update_failed`). Den lokale CLI og en instans med login deaktiveret beholder genopretningsstien og må sætte en adgangskode uden den, fordi begge er bundet til den vært, der ejer datamappen.

## Rørledning

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

Pålidelige interne overskrifter (defineret i `src/server/authz/headers.ts`) er** fjernet fra indgående anmodninger** før klassificering kan — klienter ikke på forhånd udfylde `x-omniroute-auth-*` for at efterligne et emne.

### Forsikringskontrakter

Hver ruteklasse har en politik i `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — returnerer altid `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — udtrækker bærer, validerer via `validateApiKey()`. Falder kun igennem til anonym, når det effektive `REQUIRE_API_KEY` funktionsflag er deaktiveret. Det effektive flag løses gennem `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), så Dashboard-funktionsflag og miljøvariabler styrer `/api/v1/*`, `/api/v1beta/*` og aliaser konsekvent; resolver fejl fejl lukket. Tillader anmodninger om dashboard-session på klient- API ruter (inklusive `/api/v1/models`, brugt af dashboard-modelkataloget). Når Entra ID SSO er aktiveret, håndteres en bærer, der strukturelt er en Entra-token (tre base64url-segmenter, `RS*` alg, `kid`) af SSO -grenen** før** `validateApiKey()` og dens dom er endelig — Statiske API nøgler er upåvirkede. Se [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — accepterer dashboardsession, interne modelsynkroniseringsanmodninger (matchet mod `/api/providers/[name]/(sync-models|models)`) eller springer helt over, hvis `isAuthRequired()` returnerer falsk. Returnerer 403 (`AUTH_001`), når et bærer-token er til stede, men ugyldigt, ellers 401. Håndhæver også rutebeskyttelsesniveauerne (LOCAL_ONLY / ALWAYS_PROTECTED) før enhver godkendelsesgren — se [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY stier i `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (i dag: `/api/mcp/`) kan tilgås fra non-loopback, når bærer-nøglen bærer `manage` omfanget; alle andre LOCAL_ONLY stier forbliver strict-loopback uanset omfang.

En vellykket politik returnerer `AuthSubject` med `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Downstream-handlere kan læse det via `assertAuth(request, "CLIENT_API")` i `src/server/authz/assertAuth.ts` i stedet for at køre godkendelseslogik igen.

## Liste over offentlige ruter

`src/shared/constants/publicApiRoutes.ts` er den eksplicitte tilladelsesliste:

Listen er opdelt efter** form** , og opdelingen er bærende (GHSA-74g9-q8f6-793h): et præfiks matches med `startsWith()`, så det matcher også hver tilstødende sti, der deler sine ledende tegn. `/api/usage/om-usage` som et præfiks markeret `/api/usage/om-usage<anything>` PUBLIC, og Next løser det til `/api/usage/[connectionId]` — en handler uden egen godkendelse.

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

Læsebeskyttede ruter er offentlige** kun** for sikre metoder. Bemærk: `classifyRoute()` udelukker `/api/v1/*` og `/api/v1beta/*` fra PUBLIC -fald-through — de er altid `CLIENT_API` så bærernøgle-politikken gælder stadig.

## Tilføjelse af en ny rute

### Mønster 1 — Offentligt klient-API-slutpunkt (Bearer-godkendelse)

Ruter under `/api/v1/` og `/api/v1beta/` klassificeres automatisk som `CLIENT_API`. Middlewaren håndhæver Bearer-kontrollen; rutehandlerne behøver ikke at gentage den, men kan læse subjektet, hvis det er nyttigt.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handlerlogik
}
```

### Mønster 2 — Administrationsslutpunkt (session eller Bearer + administrér)

Brug `requireManagementAuth()` fra `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handlerlogik
}
```

`requireManagementAuth()` returnerer `null` ved succes eller en JSON-fejl-`Response`:

- 401 `AUTH_001` "Godkendelse påkrævet" — ingen legitimationsoplysninger overhovedet
- 403 — ugyldig Bearer **eller** Bearer findes, men nøglen mangler omfanget `manage` / `admin`

`hasManageScope(scopes)` returnerer sand for `"manage"` eller `"admin"`.

### Mønster 3 — Tilføjelse til den offentlige tilladelsesliste

Vælg sættet efter form, ikke efter bekvemmelighed. En enkelt rute placeres i `PUBLIC_API_ROUTES_EXACT` (eller `PUBLIC_READONLY_CORS_API_ROUTES`, hvis den kun understøtter GET); kun et reelt undertræ placeres i `PUBLIC_API_ROUTE_PREFIXES`, og det **skal slutte med `/`**. Hvis en enkelt rute placeres på præfikslisten, offentliggøres også alle tilstødende stier, der deler dens indledende tegn — herunder søskenderuter med dynamiske segmenter, som tilføjes senere (GHSA-74g9-q8f6-793h). Opdater enhedstestene i `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` og `tests/unit/authz/classify.test.ts`.

## Scopes

Tre navnerum. Hver kontrolfunktion læser kun sine egne strenge. Sammenligningen side om side,
herunder hvorfor `manage` ikke består `scopeMatches` for `read:compression`, og hvorfor et
`read`-adgangstoken ikke kan udføre `PATCH /api/keys/{id}`, findes i
[Tre scope-navnerum](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API-nøgler indeholder et `scopes`-array (gemt som JSON i `api_keys.scopes`, se `src/lib/db/apiKeys.ts`).

### Administrations-scope

- `manage` / `admin` — `hasManageScope`. Bearer-adgang til administrations-API-ruter.
- `mcp:connect`, `self:usage`, `self:account-quota` og
  `policy:bypass-provider-quota` er additive scopes med eksakt match. De ligger
  uden for `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` åbner kun
  `/api/mcp/`-undtagelsen for trafik uden for loopback.

### MCP-værktøjsscopes

Katalog og matchningsregler (identisk streng eller et tildelt scope, der slutter med `*`):
[MCP-værktøjsscopes](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` i `src/shared/constants/mcpScopes.ts` er den oprindelige typede
delmængde, ikke hele kataloget. Håndhævelsen kører i
`open-sse/mcp-server/scopeEnforcement.ts`, efter at `resolveCallerScopeContext()`
har fundet scopes fra MCP-godkendelsesoplysninger, request-metadata eller `OMNIROUTE_MCP_SCOPES`.
Den forbliver deaktiveret, medmindre `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Adgangstoken-scopes

`read` / `write` / `admin` på `oma_live_…`-tokens, rangeret af `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Denne rangering gælder kun for
adgangstoken-legitimationsoplysningerne. Se [Administrationsgodkendelse](../guides/MANAGEMENT-AUTH.md).

## Skift for påkrævet godkendelse

`isAuthRequired()` i `src/shared/utils/apiAuth.ts` afgør, om **nogen** godkendelse overhovedet håndhæves for en anmodning:

- `settings.requireLogin === false` → godkendelse er globalt deaktiveret, undtagen for det altid beskyttede niveau (se [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) og de kald, der udleverer en legitimationsoplysning, som den accepterer. De kræver samme legitimation, som når login er aktiveret: udstedelse af synkroniseringstokens, udstedelse af CLI-adgangstokens med vilket som helst scope, og oprettelse af en API-nøgle med scopet `manage`/`admin`, tildeling af det scope til en nøgle, eller regenerering eller visning af en sådan nøgle (`requireCredentialForManagementScopedKey()` i `src/lib/api/requireManagementAuth.ts`). Nøgler, der kun bruges til inferens, forbliver åbne.
- Ingen adgangskode konfigureret **og** ingen `INITIAL_PASSWORD`-miljøvariabel → bootstrap-tilstanden tillader introduktionsguiden og loopback-anmodninger, men eksponerede netværksanmodninger kræver stadig legitimationsoplysninger.
- Enhver DB-fejl → lukker af (sikkert som standard).

Klient-API-nøglehåndhævelsen bruger `isRequireApiKeyEnabled()` i `src/shared/utils/featureFlags.ts` og ikke en direkte læsning af `process.env.REQUIRE_API_KEY`. Det har betydning for udrullede instanser: at ændre `REQUIRE_API_KEY` i Dashboard → Feature Flags gemmer en DB-overskrivning og påvirker straks `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` og andre klient-API-godkendelseskontroller, der deler denne hjælper. Hvis feature flag-lageret ikke kan læses, afviser klient-API-godkendelsen adgang og kræver en nøgle.

## Inkompatibel ændring — v3.8.0

Slutpunkterne `/api/v1/agents/tasks/*` og `/api/resilience/model-cooldowns` **kræver nu administrationsgodkendelse** (commit `588a0333`). Klienter, der tidligere sendte en normal API-nøgle uden adgangsområdet `manage`, modtager `403`. Migrering: Tildel enten nøglen adgangsområdet `manage` i API Keys-dashboardet, eller brug en dashboard-session, hvor der er logget ind.

## Adfærdsændring — v3.8.2

`/api/mcp/*` (den eksterne MCP-server) er stadig LOCAL_ONLY som standard, men accepterer nu anmodninger, der ikke er loopback-anmodninger, når headeren `Authorization: Bearer <api-key>` indeholder adgangsområdet `manage`. Undtagelsen styres eksplicit pr. sti via `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` i `src/server/authz/routeGuard.ts`; det relaterede LOCAL_ONLY-præfiks `/api/cli-tools/runtime/*` kan bevidst IKKE omgås, fordi det kan starte vilkårlige underprocesser. Anonyme anmodninger til `/api/mcp/*`, der ikke er loopback-anmodninger, returnerer fortsat `403 LOCAL_ONLY` — standarden for enhver ny LOCAL_ONLY-sti er fortsat udelukkende at tillade loopback. Se [Niveauer for rutebeskyttelse](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Test

- Enhedstest: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Offentlig tilladelsesliste: `tests/unit/public-api-routes.test.ts`.
- Kør fokuseret: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Fejlretning

Rørledningen stempler altid svar med:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

For godkendte anmodninger inkluderer opstrøms (handler-side) anmodningsheadere også:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Brug `assertAuth(req, expectedClass)` inde i handlere — det kaster `AuthzAssertionError` med kode `AUTHZ_NOT_INITIALIZED`, hvis middlewaren blev omgået (nyttigt til at fange konfigurationsregression i test).

## Se også

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — godkendelsesmarkør pr. slutpunkt
- [COMPLIANCE.md](../security/COMPLIANCE.md) — revisionslog for godkendelseshændelser
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tre scope-navnerum og MCP-værktøjernes scope-katalog
- Kilde: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
