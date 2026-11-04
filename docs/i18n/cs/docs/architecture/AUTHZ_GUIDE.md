# Authorization Guide (Čeština)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Zdroj pravdy:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Poslední aktualizace:** 2026-09-22 — jmenné prostory rozsahů odkazují na MCP-SERVER.md

OmniRoute používá autorizační řetězec zohledňující routy, který kontroluje každý požadavek API. Klasifikace je **deterministická** a **fail-closed** — cokoli, co nelze klasifikovat, spadá do kategorie `MANAGEMENT` a vyžaduje relaci nebo token s oprávněními pro správu. Tato stránka vysvětluje model určený technikům, kteří udržují routy nebo navrhují nové koncové body.

![Autorizační řetězec (3 třídy rout + vyhodnocení zásad)](../diagrams/exported/authz-pipeline.svg)

> Zdroj: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dva režimy ověření

### 1. klíč API (nosič)

Používá se pro klienta OpenAI/Anthropic/Gemini-compatible APIs a několik tras správy, když má klíč rozsah `manage`.

```
Authorization: Bearer <api-key>
```

Ověřeno `isValidApiKey()` / `extractApiKey()` v `src/sse/services/auth.ts` a reexportováno přes `src/shared/utils/apiAuth.ts`. Validátor také přijímá proměnné env `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` jako trvalé průchozí klíče (problém #1350).

### 2. Relace hlavního panelu (auth_token cookie)

Pro stránky řídicího panelu a operace správce.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Soubor cookie je relace pouze tehdy, když JWT ověří** a** nese `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Každý uživatel souboru cookie (hlídač trasy řídicího panelu (`isDashboardSessionAuthenticated()`), obnovení potrubí authz, handshake WebSocket, živý server, `/api/settings/require-login`, `/api/auth/status`) prochází tímto pomocníkem. Jiné JWTs podepsané pomocí `JWT_SECRET` existují — Cursor CLI passthrough razí `iss "omniroute" / aud "cursor-cli"` tokeny pro držitele klíčů — a nikdy se nejedná o relace (#13298).

Ověřeno `isDashboardSessionAuthenticated()` v `src/shared/utils/apiAuth.ts`. Potrubí automaticky obnoví JWT, když mu zbývá méně než 7 dní do jeho 30denní životnosti.

Relace může také skončit před uplynutím 30 dnů, protože každý minter prochází `mintDashboardSessionToken` (čas problému `iat` a id `jti`) a ověřovatel kontroluje dvě nastavení: `sessionsValidAfter`, nastavené změnou hesla, takže každá relace spuštěná před ukončením ověřování (prohlížeč, který změnil heslo, získá nový soubor cookie) a `revokedDashboardSessions`, do kterého `POST /api/auth/logout` ' session přidá podepsané `jti`. Relace vytvořené starší verzí nemají žádný nárok a zůstávají v platnosti až do první změny hesla. Pokud nastavení nelze přečíst, relace není důvěryhodná.

Některé cesty vedení akceptují** buď** režim: cookie OR `Bearer <key>` když má klíč API rozsah `manage` (nebo `admin`). To umožňuje pracovní postup „konfigurovatelné pomocí volání API “ přidaný ve verzi 3.8.

#### Volitelná přihlašovací brána OIDC (#6973)

Přihlášení správce dashboardu také podporuje** přihlásit se** OIDC (OpenID Connect) tok spolu s výchozím přihlašovacím heslem — password login není nikdy odstraněn, pouze doplněn:

- Zakázáno, pokud není `settings.oidcEnabled === true`** a** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` jsou všechny nakonfigurovány (Nastavení → Auth). `GET /api/auth/oidc/login` jinak vrátí `400`.
- `GET /api/auth/oidc/login` objeví `authorization_endpoint` ze `/.well-known/openid-configuration` emitenta (spadá zpět na `<issuer>/authorize`), vytvoří přesměrování URI z příchozího požadavku (`x-forwarded-proto` -aware) a přesměruje na IdP pomocí náhodného `state` uloženého v `httpOnly` `oidc_state` cookie.
- `GET /api/auth/oidc/callback` ověřuje `state`, vyměňuje autorizační kód a ověřuje podpis tokenu ID prostřednictvím JWKS vydavatele (`jose` `createRemoteJWKSet`, uložené v mezipaměti na JWKS URI) pomocí kontrol `issuer`/`audience`. Přijetí řídicího panelu vyžaduje neprázdný seznam `oidcAllowedSubjects`, zásady `oidcAdmissionClaim` nebo obojí. Seznam předmětů odpovídá `sub` nebo `email` pouze v případě, že `email_verified === true`. Volitelná zásada deklarace přebírá cestu deklarace ID tokenu oddělenou tečkami (například `realm_access.roles`) a pole akceptovaných hodnot; vyřešený nárok musí být polem řetězců obsahujících alespoň jednu přijatou hodnotu. Pokud jsou nakonfigurovány obě zásady, musí projít obě. Missing/malformed nároky se nezdaří a bez kterékoli zásady zpětné volání odmítne přihlášení (`not_configured`). Stávající konfigurace pouze pro předmět zůstávají beze změny.
- Keycloak normálně mapuje role sfér na přístupové tokeny, ne nutně na tokeny ID. Chcete-li vyžadovat roli sféry `admin`, nakonfigurujte mapovač protokolů pro tohoto klienta, který obsahuje `realm_access.roles`**ID token** , poté nastavte `oidcAdmissionClaim` na `{ "path": "realm_access.roles", "values": ["admin"] }`. Před povolením přístupu pouze pro roli zkontrolujte skutečný nárok na token ID pro tohoto klienta; aplikace nečte role přístupového tokenu. Odmítnutí tokenu na straně IdP může tuto kontrolu na straně aplikace doplnit, ale nenahrazuje.
- Na úspěchu to razí** úplně stejný** 30denní `auth_token` JWT problémy s přihlášením pomocí hesla (`src/app/api/auth/login/route.ts`), takže zbytek kanálu relace dashboardu (automatické obnovení, příznaky cookie) se nemění — OIDC pouze nahrazuje způsob, jakým se cookie razí, nikoli to, co uděluje. Změny IdP roles/groups neruší platnost existujících relací OmniRoute ; odhlášení, rotace hesla nebo vypršení platnosti relace stále řídí jejich životnost.
- Každé nastavení `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) je v `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` odpovídá `400 PASSWORD_REQUIRED` pokud tělo nenese heslo pro správu jako `currentPassword` (`401 PASSWORD_MISMATCH` když je špatné). `oidcDisablePasswordLogin` odmítne heslo _login_ (`POST /api/auth/login`), ale ponechá uložený hash hesla a re-auth proti němu stále kontroluje `currentPassword`.
- `corsOrigins` a `bruteForceProtection` jsou také v `SECURITY_IMPACTING_SETTINGS_KEYS` : uvolnění buď oslabí obranu přihlášení, takže provedou stejné opětovné ověření `currentPassword` (vyžádá si to karta Zabezpečení) a import JSON je zruší.
- Každý klíč bezpečnostní politiky — položky `SECURITY_IMPACTING_SETTINGS_KEYS`, každý klíč `oidc*` a stav relace řídicího panelu — je** pouze pro operátora** na `PATCH /api/settings`: klíč API s rozsahem správy nebo přístupový token `oma_` je odmítnut pomocí `403` i když posílá správné `currentPassword`, a odmítnutí je auditováno jako `settings.update_failed` se `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` v `src/lib/api/operatorCredential.ts`). Běžná nastavení (téma, předvolby zobrazení) zůstávají zapisovatelná pro klíč `manage` nebo přístupový token `admin`. Každá mutace samotného `/api/settings` (a `/api/settings/require-login`) také potřebuje rozsah přístupového tokenu `admin` (`ADMIN_MUTATION_EXACT_PATHS` v `src/server/authz/accessScopes.ts`, shoda přesné cesty); `GET` zůstává `read` a ostatní podcesty `/api/settings/*` (proxy, výchozí nastavení komba, aliasy modelu, komprese, čištění…) si zachovávají rozsah `write` odvozený z metody.
- `POST /api/settings/import-json` toto opětovné ověření přeskočí, takže před zápisem zahodí každý klíč v `IMPORT_STRIPPED_SETTINGS_KEYS` (stejný soubor): heslo a `currentPassword`, každý záznam `SECURITY_IMPACTING_SETTINGS_KEYS` a stav relace řídicího panelu (`sessionsValidAfter`, `revokedDashboardSessions`). Import starší zálohy proto nemůže obnovit relaci, u které již skončila změna hesla nebo odhlášení.

#### Volitelné TOTP dvoufaktorové přihlášení (#16619)

Registrováno z Nastavení → Zabezpečení; vypnuto, dokud jej operátor nezapne (`src/server/auth/dashboardMfa.ts`).

- **Co zahrnuje:** přihlašovací heslo (`POST /api/auth/login`, které pak potřebuje `POST /api/auth/mfa/verify`) a `omniroute connect` (`POST /api/cli/connect`, které odmítá výměnu pouze hesla a bere kód jako `totp`).
- **Na co se nevztahuje:** Přihlášení OIDC / SSO (`/api/auth/oidc/callback`) nepožaduje OmniRoute TOTP. Spoléhá na vlastní druhý faktor poskytovatele identity, takže pokud je povoleno OIDC, vynucujte MFA v IdP.
- **Zotavení** (ztracené zařízení, nezůstaly žádné obnovovací kódy nebo faktor, který již nelze ověřit, například po změně `STORAGE_ENCRYPTION_KEY` ):
  1. Restartujte server pomocí `OMNIROUTE_DISABLE_MFA=true`.
  2. Na samotném hostiteli (loopback peer a loopback `Host`, jako je `http://localhost:20128`), se přihlaste pomocí hesla. Druhý faktor je přeskočen pouze pro tento původ; každý jiný původ stále potřebuje kód.
  3. V Nastavení → Zabezpečení → Zakázat zadejte heslo a ponechte kód prázdný. `POST /api/auth/mfa/disable` přijímá tělo bez `code` pouze tehdy, když je proměnná nastavena a požadavek přichází od hostitele; stále vyžaduje relaci řídicího panelu a aktuální heslo a je auditován jako `auth.mfa.disabled` pomocí `secondFactor: "recovery_switch"`.
  4. Zrušte nastavení `OMNIROUTE_DISABLE_MFA`, restartujte a v případě potřeby znovu zaregistrujte.

## Třídy tras

`src/server/authz/types.ts` definuje tři třídy; každá trasa, kterou nelze jednoznačně zařadit, spadá do `MANAGEMENT`.

| Třída        | Popis                                                                                                                                                   | Vyžadovaná autentizace                                                 |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `PUBLIC`     | Explicitně bezpečné trasy — přihlášení, odhlášení, stav, inicializace, health, bootstrap onboardingu.                                                   | Žádná                                                                  |
| `CLIENT_API` | Koncové body pro obsluhu modelů — `/api/v1/*`, `/api/v1beta/*` a aliasy `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer klíč, pokud je zapnuta efektivní feature flag `REQUIRE_API_KEY` |
| `MANAGEMENT` | Stránky panelu, nastavení, poskytovatelé, klíče, administrátorské a diagnostické koncové body.                                                          | Relace panelu NEBO Bearer s rozsahem `manage`                          |

Několik akcí `MANAGEMENT` je **pouze pro operátora**: klíč `manage` nestačí. Export uložených pověření (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), obnovení zálohy přes živá data (`POST /api/db-backups/import` včetně `dryRun=true`, `POST /api/db-backups` obnovení podle id, `POST /api/settings/import-json`) a ničení bodů obnovy (úklid přes `DELETE /api/db-backups` a také `PATCH /api/db-backups`, protože uložená retence řídí automatické promazávání po každé záloze) vyžadují relaci panelu, lokální subjekt CLI nebo vypnuté přihlášení. Vydání tokenu synchronizace (`POST /api/sync/tokens`) a vytvoření přístupového tokenu CLI s rozsahem `admin` (`POST /api/cli/tokens`) vyžadují relaci panelu nebo lokální subjekt CLI ve všech režimech přihlášení. Klíče API libovolného rozsahu a přístupové tokeny `oma_` nejsou operátorská pověření: pokud je vyžadováno operátorské pověření, dostanou `403`. Kontrola je v `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Změna nastavení přihlášení je rovněž vyhrazena operátorovi: `POST /api/settings/require-login` (nastavení správcovského hesla / přepnutí `requireLogin`) přijme pouze tato pověření, jakmile heslo existuje — okno prvního spuštění (zatím bez hesla) zůstává beze změny — a relace panelu musí pro nahrazení hesla poslat `currentPassword` (`403`, pokud chybí nebo je špatné, audituje se jako `settings.update_failed`). Lokální CLI a instance s vypnutým přihlášením si zachovávají obnovovací cestu a mohou nastavit heslo bez něj, protože obě jsou vázány na hostitele, který vlastní datový adresář.

## Potrubí

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

Důvěryhodné interní hlavičky (definované v `src/server/authz/headers.ts`) jsou** odstraněny z příchozích požadavků** před klasifikací klienti — nemohou předem vyplnit `x-omniroute-auth-*`, aby se vydávali za subjekt.

### Pojistné smlouvy

Každá třída trasy má zásady v `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — vždy vrátí `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — extrahuje nosič, ověřuje přes `validateApiKey()`. Propadne na anonymní pouze tehdy, když je deaktivován efektivní příznak funkce `REQUIRE_API_KEY`. Efektivní příznak je vyřešen pomocí `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), takže příznaky funkcí ovládacího panelu a proměnné prostředí řídí `/api/v1/*`, `/api/v1beta/*` a aliasy konzistentně; Selhání resolveru uzavřeno. Umožňuje požadavky na relaci řídicího panelu na klientských trasách API (včetně `/api/v1/models`, používaného v katalogu modelů řídicích panelů). Když je Entra ID SSO povolen, Nosič, který je strukturálně token Entra (tři segmenty base64url, `RS*` alg, `kid`), zpracovává větev SSO** před** `validateApiKey()` a jeho verdikt je konečný — nikdy neprojde cestou klíče API nebo větve degradace na anonymní, takže výpadek poskytovatele identity se nemůže stát otevřeným přístupem. Statické klávesy API nejsou ovlivněny. Viz [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — přijímá relaci řídicího panelu, požadavky na interní synchronizaci modelu (porovnané se `/api/providers/[name]/(sync-models|models)`) nebo zcela přeskakuje, pokud `isAuthRequired()` vrátí hodnotu false. Vrátí 403 (`AUTH_001`), když je token nositele přítomen, ale neplatný, jinak 401. Také vynucuje úrovně ochrany trasy (LOCAL_ONLY / ALWAYS_PROTECTED) před jakoukoli auth větví — viz [vrstvy Route Guard](../security/ROUTE_GUARD_TIERS.md). Cesty LOCAL_ONLY v `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (dnes: `/api/mcp/`) mohou být přístupné z bez zpětné smyčky, když klíč Nosiče nese rozsah `manage` ; všechny ostatní cesty LOCAL_ONLY zůstávají striktně-loopback bez ohledu na rozsah.

Úspěšná politika vrátí `AuthSubject` s `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Následné obslužné programy jej mohou číst prostřednictvím `assertAuth(request, "CLIENT_API")` v `src/server/authz/assertAuth.ts` namísto opětovného spouštění auth logiky.

## Seznam veřejných tras

`src/shared/constants/publicApiRoutes.ts` je explicitní seznam povolených:

Seznam je rozdělen podle** tvar** a rozdělení je nosné (GHSA-74g9-q8f6-793h): předpona je shodná s `startsWith()`, takže také odpovídá každé sousední cestě sdílející její vedoucí znaky. `/api/usage/om-usage` jako prefix označený `/api/usage/om-usage<anything>` PUBLIC a Next to řeší tak, že `/api/usage/[connectionId]` — obslužný program bez vlastního ověření.

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

Trasy pouze pro čtení jsou veřejné** pouze** pro bezpečné metody. Poznámka: `classifyRoute()` vylučuje `/api/v1/*` a `/api/v1beta/*` z propadu PUBLIC — ty jsou vždy `CLIENT_API` takže zásada nosného klíče stále platí.

## Přidání nové trasy

### Vzor 1 — Veřejný koncový bod klientského API (ověřování Bearer)

Trasy pod `/api/v1/` a `/api/v1beta/` jsou automaticky klasifikovány jako `CLIENT_API`. Middleware vynucuje kontrolu Bearer; obslužné rutiny tras ji nemusejí opakovat, ale mohou v případě potřeby načíst subjekt.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... logika obslužné rutiny
}
```

### Vzor 2 — Koncový bod pro správu (relace nebo Bearer + oprávnění ke správě)

Použijte `requireManagementAuth()` ze souboru `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... logika obslužné rutiny
}
```

Při úspěchu vrací `requireManagementAuth()` hodnotu `null`, jinak chybovou odpověď JSON typu `Response`:

- 401 `AUTH_001` „Je vyžadováno ověření“ — nejsou k dispozici žádné přihlašovací údaje
- 403 — neplatný Bearer **nebo** je Bearer přítomen, ale klíč nemá rozsah `manage` / `admin`

`hasManageScope(scopes)` vrací hodnotu true pro `"manage"` nebo `"admin"`.

### Vzor 3 — Přidání do seznamu veřejných tras

Sadu zvolte podle tvaru, nikoli podle pohodlnosti. Jedna trasa patří do `PUBLIC_API_ROUTES_EXACT` (nebo do `PUBLIC_READONLY_CORS_API_ROUTES`, pokud podporuje pouze GET); pouze skutečný podstrom patří do `PUBLIC_API_ROUTE_PREFIXES` a **musí končit znakem `/`**. Vložením jedné trasy do seznamu prefixů zveřejníte také každou sousední cestu se stejnými počátečními znaky — včetně sourozeneckých tras s dynamickými segmenty přidaných později (GHSA-74g9-q8f6-793h). Aktualizujte jednotkové testy v `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` a `tests/unit/authz/classify.test.ts`.

## Rozsahy

Tři jmenné prostory. Každý kontrolní mechanismus čte pouze své vlastní řetězce. Porovnání vedle sebe,
včetně toho, proč `manage` nevyhoví funkci `scopeMatches` pro `read:compression` a proč
přístupový token s rozsahem `read` nemůže provést `PATCH /api/keys/{id}`, najdete v dokumentu
[Tři jmenné prostory rozsahů](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Klíče API obsahují pole `scopes` (uložené jako JSON v `api_keys.scopes`, viz `src/lib/db/apiKeys.ts`).

### Rozsah správy

- `manage` / `admin` — `hasManageScope`. Přístup s tokenem Bearer k trasám rozhraní API pro správu.
- `mcp:connect`, `self:usage`, `self:account-quota` a
  `policy:bypass-provider-quota` jsou doplňkové rozsahy s přesnou shodou. Nacházejí se
  mimo `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` povoluje pouze
  výjimku pro přístup k `/api/mcp/` mimo rozhraní loopback.

### Rozsahy nástrojů MCP

Katalog a pravidla porovnávání (identický řetězec nebo udělený rozsah končící znakem `*`):
[Rozsahy nástrojů MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` v `src/shared/constants/mcpScopes.ts` je původní typovaná
podmnožina, nikoli celý tento katalog. Vynucování probíhá v souboru
`open-sse/mcp-server/scopeEnforcement.ts` poté, co `resolveCallerScopeContext()`
zjistí rozsahy z ověřovacích údajů MCP, metadat požadavku nebo `OMNIROUTE_MCP_SCOPES`.
Zůstává vypnuté, pokud není nastaveno `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Rozsahy přístupových tokenů

`read` / `write` / `admin` u tokenů `oma_live_…`, seřazené funkcí `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Toto pořadí se vztahuje pouze na přihlašovací údaj
přístupového tokenu. Viz [Ověřování pro správu](../guides/MANAGEMENT-AUTH.md).

## Přepínač vyžadování autentizace

`isAuthRequired()` v `src/shared/utils/apiAuth.ts` rozhoduje, zda se pro požadavek vynucuje **jakákoli** autentizace:

- `settings.requireLogin === false` → autentizace je globálně vypnuta, kromě trvale chráněné úrovně (viz [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) a volání, která vydávají pověření, jež tato konfigurace přijímá; ta vyžadují stejné pověření jako při zapnutém přihlášení: vydávání tokenů synchronizace, vytváření přístupových tokenů CLI v libovolném rozsahu a vytváření klíče API s rozsahem `manage`/`admin`, udělování tohoto rozsahu klíči, regenerace nebo zobrazení takového klíče (`requireCredentialForManagementScopedKey()` v `src/lib/api/requireManagementAuth.ts`). Klíče určené pouze pro inferenci zůstávají otevřené.
- Není nastaveno žádné heslo **a** není nastavena proměnná prostředí `INITIAL_PASSWORD` → bootstrap režim povolí průvodce nastavením a požadavky z loopbacku, ale požadavky ze sítě stále vyžadují pověření.
- Jakákoli chyba databáze → selhání uzavřené (secure-by-default).

Vynucení klientského API klíče používá `isRequireApiKeyEnabled()` v `src/shared/utils/featureFlags.ts`, nikoli přímé čtení `process.env.REQUIRE_API_KEY`. To je důležité pro nasazené instance: přepnutí `REQUIRE_API_KEY` v Dashboard → Feature Flags uloží přepsání do databáze a okamžitě ovlivní `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` a další kontroly autentizace klientského API, které sdílejí tento pomocník. Pokud nelze přečíst úložiště feature flagů, autentizace klientského API selže uzavřeně a vyžaduje klíč.

## Zásadní změna — v3.8.0

Koncové body `/api/v1/agents/tasks/*` a `/api/resilience/model-cooldowns` **nyní vyžadují ověření pro správu** (commit `588a0333`). Klienti, kteří dříve odesílali běžný klíč API bez rozsahu oprávnění `manage`, obdrží `403`. Migrace: buď klíči přidělte rozsah oprávnění `manage` na panelu API Keys, nebo použijte přihlášenou relaci panelu.

## Změna chování — v3.8.2

`/api/mcp/*` (vzdálený server MCP) je ve výchozím nastavení stále LOCAL_ONLY, ale nyní přijímá požadavky mimo zpětnou smyčku, pokud hlavička `Authorization: Bearer <api-key>` obsahuje rozsah oprávnění `manage`. Tato výjimka je explicitně povolována pro jednotlivé cesty prostřednictvím `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` v `src/server/authz/routeGuard.ts`; související prefix LOCAL_ONLY `/api/cli-tools/runtime/*` záměrně nelze obejít, protože může spouštět libovolné podprocesy. Anonymní požadavky na `/api/mcp/*` mimo zpětnou smyčku nadále vracejí `403 LOCAL_ONLY` — výchozí nastavení pro každou novou cestu LOCAL_ONLY nadále striktně vyžaduje zpětnou smyčku. Viz [Úrovně ochrany tras](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testování

- Jednotkové testy: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Veřejný seznam povolených položek: `tests/unit/public-api-routes.test.ts`.
- Spuštění vybraného testu: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Ladění

Potrubí vždy označí odpovědi:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Pro autentizované požadavky upstream (na straně obslužné rutiny) hlavičky požadavků také zahrnují:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Použijte `assertAuth(req, expectedClass)` uvnitř obslužných rutin — to vyvolá `AuthzAssertionError` s kódem `AUTHZ_NOT_INITIALIZED` pokud byl middleware obejit (užitečné pro zachycení konfiguračních regresí v testech).

## Viz také

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — označení autentizace pro každý koncový bod
- [COMPLIANCE.md](../security/COMPLIANCE.md) — protokol auditu událostí autentizace
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tři jmenné prostory rozsahů a katalog rozsahů nástrojů MCP
- Zdroj: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
