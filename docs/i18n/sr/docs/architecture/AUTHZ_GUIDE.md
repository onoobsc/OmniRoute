# Authorization Guide (Српски)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Izvor istine:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Poslednje ažurirano:** 2026-09-22 — prostori imena opsega ukazuju na MCP-SERVER.md

OmniRoute ima autorizacionu cevovodnu liniju svesnu ruta koja kontroliše svaki API zahtev. Klasifikacija je **deterministička** i **fail-closed** — sve što se ne može klasifikovati završava kao `MANAGEMENT` i zahteva sesiju ili token menadžerskog nivoa. Ova stranica objašnjava model za inženjere koji održavaju rute ili dizajniraju nove krajnje tačke.

![AuthZ cevovodna linija (3 klase ruta + evaluacija politike)](../diagrams/exported/authz-pipeline.svg)

> Izvor: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Два режима аутентификације

### 1. API кључ (носилац)

Користи се за OpenAI/Anthropic/Gemini-compatible клијент APIs и неколико рута управљања када кључ има `manage` опсег.

```
Authorization: Bearer <api-key>
```

Потврђен `isValidApiKey()` / `extractApiKey()` у `src/sse/services/auth.ts` и поново извезен преко `src/shared/utils/apiAuth.ts`. Валидатор такође прихвата `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` енв варс као трајне пролазне кључеве (проблем #1350).

### 2. Сесија контролне табле (колачић аутх_токен)

За странице контролне табле и администрацијске операције.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Колачић је сесија само када JWT верификује** и** носи `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Сваки потрошач колачића (чувар руте на контролној табли (`isDashboardSessionAuthenticated()`), аутхз освежавање цевовода, WebSocket руковање, живи сервер, `/api/settings/require-login`, `/api/auth/status`) пролази кроз тај помоћник. Остали JWTs потписани са `JWT_SECRET` постоје — Cursor CLI пролаз кроз ковања `iss "omniroute" / aud "cursor-cli"` токена за носиоце кључева — и никада нису сесије (#13298).

Проверио `isDashboardSessionAuthenticated()` у `src/shared/utils/apiAuth.ts`. Цевовод аутоматски освежава JWT када му је преостало мање од 7 дана током његовог 30-дневног века трајања.

Сесија такође може да се заврши пре истека њених 30 дана, јер сваки минтер пролази кроз `mintDashboardSessionToken` (време проблема `iat` и ид `jti`) и верификатор проверава два подешавања: `sessionsValidAfter`, постављена променом лозинке, тако да свака сесија издата пре него што престане са верификацијом (прегледач који је променио лозинку добија нови колачић) и `revokedDashboardSessions`, којој `POST /api/auth/logout` сесија додаје `jti`. Сесије које је створило старије издање не носе ниједно право и остају важеће до прве промене лозинке. Ако се подешавања не могу прочитати, сесија није поуздана.

Неки путеви управљања прихватају** било** режим: колачић OR `Bearer <key>` када API кључ има `manage` (или `admin`) опсег. То је оно што омогућава радни ток који се може конфигурисати путем API позива додат у в3.8.

#### Опциона OIDC капија за пријаву (#6973)

Пријава администратора на контролној табли такође подржава ан** опт-ин** OIDC (OpenID Цоннецт) ток поред подразумеване лозинке за пријаву — лозинке се никада не уклања, само се допуњује:

- Онемогућено осим ако `settings.oidcEnabled === true`** и** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` су сви конфигурисани (Подешавања → Аутх). `GET /api/auth/oidc/login` у супротном враћа `400`.
- `GET /api/auth/oidc/login` открива `authorization_endpoint` из `/.well-known/openid-configuration` издаваоца (враћа се на `<issuer>/authorize`), гради URI за преусмеравање из долазног захтева (`x-forwarded-proto` -aware) и преусмерава на IdP са случајним `state` ускладиштеним у колачићу `httpOnly` `oidc_state`
- `GET /api/auth/oidc/callback` проверава `state`, размењује ауторизациони код и верификује потпис ID токена преко JWKS издаваоца (`jose` `createRemoteJWKSet`, кеширан по JWKS URI) са `issuer`/`audience` проверама. Пријем на контролну таблу захтева непразну `oidcAllowedSubjects` листу, зкл `oidcAdmissionClaim` или обоје. Листа предмета одговара `sub` или `email` само када `email_verified === true`. Опциона политика захтева узима тачку одвојену путању захтева за ИД-токен (на пример, `realm_access.roles`) и низ прихваћених вредности; решени захтев мора бити низ стрингова који садржи најмање једну прихваћену вредност. Ако су обе политике конфигурисане, обе морају проћи. Missing/malformed тврдње нису затворене, а без било које политике повратни позив одбија пријаву (`not_configured`). Постојеће конфигурације само за предмет остају непромењене.
- Кеицлоак обично мапира улоге домена у приступне токене, не нужно ID токене. Да бисте захтевали улогу области `admin`, конфигуришите мапер протокола за овог клијента који укључује `realm_access.roles` у свом**ID токен** , затим поставите `oidcAdmissionClaim` на `{ "path": "realm_access.roles", "values": ["admin"] }`. Проверите стварни ИД-токен захтев за овог клијента пре него што омогућите пријем само за улогу; апликација не чита улоге токена приступа. Одбијање токена на страни ИдП-а може допунити, али не заменити ову проверу на страни апликације.
- На успех кује** потпуно исто** 30-дневни `auth_token` JWT проблеми са пријавом лозинке (`src/app/api/auth/login/route.ts`), тако да је остатак цевовода сесије на контролној табли (аутоматско освежавање, ознаке колачића) непромењен. — OIDC само замењује начин на који се колачић кује, а не оно што даје. Промене у IdP roles/groups не поништавају постојеће OmniRoute сесије; одјава, ротација лозинке или истек сесије и даље утичу на њихов животни век.
- Свака `oidc*` поставка (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) је у `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` одговара `400 PASSWORD_REQUIRED` осим ако тело не носи лозинку за управљање као `currentPassword` (`401 PASSWORD_MISMATCH` када је погрешна). `oidcDisablePasswordLogin` одбија лозинку _логин_ (`POST /api/auth/login`) али чува сачувану хеш лозинке, а поновна аутентизација и даље проверава `currentPassword` у односу на њу.
- `corsOrigins` и `bruteForceProtection` су такође у `SECURITY_IMPACTING_SETTINGS_KEYS` : попуштање или слабљење одбране за пријављивање, па они узимају исту `currentPassword` поновну ауту (картица Безбедност то тражи) и JSON импорт их одбацује.
- Сваки кључ безбедносне политике — `SECURITY_IMPACTING_SETTINGS_KEYS` уносе, сваки `oidc*` кључ и стање сесије контролне табле — је** само за оператера** на `PATCH /api/settings`: API кључ са опсегом управљања или `oma_` приступни токен се одбија са `403` чак и када пошаље прави `currentPassword`, а одбијање се ревидира као `settings.update_failed` са `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` у `src/lib/api/operatorCredential.ts`). Уобичајена подешавања (тема, поставке приказа) остају уписана за `manage` кључ или `admin` приступни токен. Свака мутација самог `/api/settings` (и `/api/settings/require-login`) такође треба `admin` опсег токена приступа (`ADMIN_MUTATION_EXACT_PATHS` у `src/server/authz/accessScopes.ts`, подударање тачног пута); `GET` остаје `read`, а друге `/api/settings/*` подруте (проксији, комбиноване подразумеване вредности, псеудоними модела, компресија, чистке...) задржавају `write` опсег на основу методе.
- `POST /api/settings/import-json` прескаче ту поновну аутентификацију, тако да испушта сваки кључ у `IMPORT_STRIPPED_SETTINGS_KEYS` (иста датотека) пре писања: лозинку и `currentPassword`, сваки `SECURITY_IMPACTING_SETTINGS_KEYS` унос и стање сесије контролне табле (`sessionsValidAfter`, `revokedDashboardSessions`). Увоз старије резервне копије стога не може да оживи сесију на којој је промена лозинке или одјава већ завршена.

#### Опционо TOTP пријављивање са два фактора (#16619)

Регистрован из Подешавања → Сецурити; искључен док га оператер не укључи (`src/server/auth/dashboardMfa.ts`).

- **Шта покрива:** лозинка за пријаву (`POST /api/auth/login`, којој је тада потребан `POST /api/auth/mfa/verify`) и `omniroute connect` (`POST /api/cli/connect`, који одбија размену само лозинке и узима код као `totp`).
- **Шта не покрива:** OIDC / SSO пријављивање (`/api/auth/oidc/callback`) не тражи OmniRoute TOTP. Ослања се на други фактор добављача идентитета, тако да примени MFA у IdP ако је OIDC омогућен.
- **Опоравак** (изгубљени уређај, нема преосталих кодова за опоравак или фактор који се више не може проверити, на пример након промене `STORAGE_ENCRYPTION_KEY` ):
  1. Поново покрените сервер са `OMNIROUTE_DISABLE_MFA=true`.
  2. На самом хосту (лоопбацк пеер и лоопбацк `Host`, као што је `http://localhost:20128`), пријавите се са лозинком. Други фактор је прескочен само за то порекло; сваком другом пореклу и даље је потребан код.
  3. У подешавањима → Сецурити → Дисабле, унесите лозинку и оставите код празан. `POST /api/auth/mfa/disable` прихвата тело без `code` само док је променљива постављена и захтев долази од хоста; и даље захтева сесију контролне табле и тренутну лозинку, и ревидира се као `auth.mfa.disabled` са `secondFactor: "recovery_switch"`.
  4. Поништите `OMNIROUTE_DISABLE_MFA`, поново покрените и поново се пријавите ако је потребно.

## Класе рута

`src/server/authz/types.ts` дефинише три класе; свака рута која не може да се класификује детерминистички подразумевано припада класи `MANAGEMENT`.

| Класа        | Опис                                                                                                                                                           | Потребна аутентификација                                                        |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| `PUBLIC`     | Изричито безбедне руте: пријава, одјава, статус, иницијализација, провера здравља, почетно подешавање при уводу.                                               | Није потребна                                                                   |
| `CLIENT_API` | Крајње тачке за услуживање модела: `/api/v1/*`, `/api/v1beta/*`, као и алијаси `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer кључ када је укључена ефективна функционална заставица `REQUIRE_API_KEY` |
| `MANAGEMENT` | Странице контролне табле, подешавања, провајдери, кључеви, административне и дијагностичке крајње тачке.                                                       | Сесија контролне табле ИЛИ Bearer са опсегом `manage`                           |

Неке радње `MANAGEMENT` су **само за оператора**: кључ са опсегом `manage` није довољан.
Извоз сачуваних акредитива (`GET /api/settings/export-json`, `GET /api/db-backups/export`,
`GET /api/db-backups/exportAll`), враћање резервне копије преко актуелних података
(`POST /api/db-backups/import`, укључујући `dryRun=true`, `POST /api/db-backups` враћање по id-ју,
`POST /api/settings/import-json`), као и уклањање тачака за враћање (чишћење преко `DELETE /api/db-backups`
и `PATCH /api/db-backups`, јер задржавање које овај метод чува покреће аутоматско брисање после
сваке резервне копије) захтевају сесију контролне табле, локални CLI субјект или искључену пријаву.
Издавање токена за синхронизацију (`POST /api/sync/tokens`) и прављење CLI токена за приступ са опсегом `admin`
(`POST /api/cli/tokens`) захтевају сесију контролне табле или локални CLI субјект у сваком режиму пријаве.
API кључеви било ког опсега и токени за приступ `oma_` нису операторски акредитиви: кад се захтева оператор,
добијају `403`. Провера се налази у `src/lib/api/operatorCredential.ts`
(`resolveOperatorCredential()` / `requireOperatorCredential()`). Промена подешавања пријаве такође је само за оператора:
`POST /api/settings/require-login` (постављање лозинке за управљање / укључивање или искључивање `requireLogin`)
прихвата само те акредитиве када лозинка већ постоји. Прозор почетног подешавања (лозинка још не постоји)
не мења се, а сесија контролне табле мора да пошаље `currentPassword` да би заменила лозинку (`403` ако недостаје
или је погрешна; бележи се у ревизији као `settings.update_failed`). Локални CLI и инстанца са искљученом пријавом
задржавају путању за опоравак и могу да поставе лозинку без ње, јер су обе везане за хост који поседује
директоријум са подацима.

## Цевовод

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

Поуздана интерна заглавља (дефинисана у `src/server/authz/headers.ts`) су** скинут са долазних захтева** пре класификације — клијенти не могу унапред да попуне `x-omniroute-auth-*` да би имитирали субјект.

### Уговори о политици

Свака класа руте има политику у `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — увек враћа `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — издваја носиоца, проверава преко `validateApiKey()`. Прелази на анонимно само када је деактивирана заставица `REQUIRE_API_KEY` функције онемогућена. Ефективна заставица се решава преко `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) тако да заставице карактеристика контролне табле и променљиве окружења доследно управљају `/api/v1/*`, `/api/v1beta/*` и алиасима; неуспех разрешивача затворен. Дозвољава захтеве за сесијом контролне табле на клијентским API рутама (укључујући `/api/v1/models`, који користи каталог модела контролне табле). Када је Ентра ID SSO омогућен, носилац који је структурно Ентра токен (три басе64урл сегмента, `RS*` алг, `kid`) управља SSO грана** пре** `validateApiKey()` и његова пресуда је коначна — никада не пада на путању АПИ кључа или грану деградирања у анонимну, тако да прекид провајдера идентитета не може постати отворен приступ. Статични API кључеви нису погођени. Погледајте [Ентра ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — прихвата сесију контролне табле, интерне захтеве за синхронизацију модела (усклађене са `/api/providers/[name]/(sync-models|models)`) или у потпуности прескаче ако `isAuthRequired()` врати нетачно. Враћа 403 (`AUTH_001`) када је токен носиоца присутан, али неважећи, 401 у супротном. Такође примењује нивое чувања руте (LOCAL_ONLY / ALWAYS_PROTECTED) пре било које гране аутх — види [Нивое чувања руте](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY путањама у `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (данас: `/api/mcp/`) може се приступити из без повратне петље када кључ носиоца носи `manage` опсег; све остале LOCAL_ONLY путање остају стриктне петље без обзира на опсег.

Успешна политика враћа `AuthSubject` са `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Низводни руковаоци могу да га прочитају преко `assertAuth(request, "CLIENT_API")` у `src/server/authz/assertAuth.ts` уместо да поново покрећу аутх логику.

## Листа јавних рута

`src/shared/constants/publicApiRoutes.ts` је експлицитна листа дозвољених:

Листа је подељена по** облик** , а подела је носива (GHSA-74g9-q8f6-793h): префикс се поклапа са `startsWith()`, тако да такође одговара свакој суседној путањи која дели своје водеће знакове. `/api/usage/om-usage` као префикс означен `/api/usage/om-usage<anything>` PUBLIC, а Нект то решава у `/api/usage/[connectionId]` — руковалац без сопствене аутентификације.

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

Руте само за читање су јавне** само** за безбедне методе. Напомена: `classifyRoute()` искључује `/api/v1/*` и `/api/v1beta/*` из PUBLIC падајућег — они су увек `CLIENT_API` тако да политика носиоца кључа и даље важи.

## Додавање нове руте

### Образац 1 — Јавна крајња тачка клијентског API-ја (Bearer аутентификација)

Руте под `/api/v1/` и `/api/v1beta/` аутоматски се класификују као `CLIENT_API`. Посреднички софтвер спроводи Bearer проверу; обрађивачи рута не морају да је понављају, али могу да прочитају субјекат ако је то корисно.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... логика обрађивача
}
```

### Образац 2 — Управљачка крајња тачка (сесија или Bearer + manage)

Користите `requireManagementAuth()` из `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... логика обрађивача
}
```

`requireManagementAuth()` враћа `null` у случају успеха или JSON грешку типа `Response`:

- 401 `AUTH_001` „Аутентификација је обавезна“ — акредитиви уопште нису наведени
- 403 — неважећи Bearer **или** је Bearer присутан, али кључ нема опсег `manage` / `admin`

`hasManageScope(scopes)` враћа true за `"manage"` или `"admin"`.

### Образац 3 — Додавање на јавну листу дозвољених рута

Изаберите скуп према облику, а не према погодности. Једна рута иде у `PUBLIC_API_ROUTES_EXACT` (или у `PUBLIC_READONLY_CORS_API_ROUTES` ако је намењена само за GET); само стварно подстабло иде у `PUBLIC_API_ROUTE_PREFIXES` и оно **мора да се завршава са `/`**. Стављање једне руте на листу префикса такође објављује сваку суседну путању која дели њене почетне знакове — укључујући сродне руте са динамичким сегментима које се додају касније (GHSA-74g9-q8f6-793h). Ажурирајте јединичне тестове у `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` и `tests/unit/authz/classify.test.ts`.

## Opsezi

Tri imenska prostora. Svaki proveravač čita samo sopstvene stringove. Uporedni prikaz,
uključujući zašto `manage` ne uspeva `scopeMatches` za `read:compression` i zašto
`read` pristupni token ne može `PATCH /api/keys/{id}`, nalazi se u
[Tri imenska prostora opsega](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API ključevi sadrže niz `scopes` (sačuvan kao JSON u `api_keys.scopes`, pogledajte `src/lib/db/apiKeys.ts`).

### Opseg upravljanja

- `manage` / `admin` — `hasManageScope`. Pristup upravljačkim API rutama putem Bearer tokena.
- `mcp:connect`, `self:usage`, `self:account-quota` i
  `policy:bypass-provider-quota` su aditivni opsezi sa tačnim podudaranjem. Oni se nalaze
  izvan `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` otvara samo
  `/api/mcp/` ne-povratni izuzetak.

### MCP alatni opsezi

Katalog i pravila podudaranja (identičan string, ili dodeljeni opseg koji se završava sa `*`):
[MCP alatni opsezi](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` u `src/shared/constants/mcpScopes.ts` je originalni tipizirani
podskup, a ne taj puni katalog. Sprovođenje se vrši u
`open-sse/mcp-server/scopeEnforcement.ts` nakon što `resolveCallerScopeContext()`
razreši opsege iz MCP informacija o autentifikaciji, metapodataka zahteva ili `OMNIROUTE_MCP_SCOPES`.
Ostaje isključeno osim ako `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Opsezi pristupnog tokena

`read` / `write` / `admin` na `oma_live_…` tokenima, rangirani po `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Ovaj rang se primenjuje samo na akreditive
pristupnog tokena. Pogledajte [Autentifikacija upravljanja](../guides/MANAGEMENT-AUTH.md).

## Прекидач обавезне аутентификације

`isAuthRequired()` у `src/shared/utils/apiAuth.ts` одлучује да ли се за захтев примењује **било каква** аутентификација:

- `settings.requireLogin === false` → аутентификација је глобално искључена, осим за увек заштићени ниво
  (видети [Нивои заштите рута](../security/ROUTE_GUARD_TIERS.md)) и позиве који издају акредитив који систем прихвата.
  За њих важе исти акредитиви као и при укљученој пријави: издавање токена за синхронизацију, издавање CLI токена за приступ
  са било којим опсегом, као и прављење API кључа са опсегом `manage`/`admin`, додељивање таквог опсега кључу,
  регенерисање или приказивање таквог кључа (`requireCredentialForManagementScopedKey()` у
  `src/lib/api/requireManagementAuth.ts`). Кључеви само за инференцију остају отворени.
- Лозинка није подешена **и** не постоји променљива окружења `INITIAL_PASSWORD` → режим почетног подешавања дозвољава
  чаробњака за увод и захтеве са loopback адресе, али захтеви из мреже и даље захтевају акредитиве.
- Било каква грешка у бази → одбијање (безбедно подразумевано, fail closed).

Провера клијентских API кључева користи `isRequireApiKeyEnabled()` у `src/shared/utils/featureFlags.ts`,
а не директно читање `process.env.REQUIRE_API_KEY`. То је важно за распоређене инстанце: укључивање или искључивање
`REQUIRE_API_KEY` у Dashboard → Feature Flags чува перегазивање у бази и одмах утиче на `/v1/*`, `/v1beta/*`, `/models`,
`/responses`, `/chat/completions`, `/codex/*` и друге провере клијентског API-ја које користе ову помоћну функцију.
Ако складиште заставица не може да се прочита, аутентификација клијентског API-ја одбија захтев и тражи кључ.

## Promena koja narušava kompatibilnost — v3.8.0

Krajnje tačke `/api/v1/agents/tasks/*` i `/api/resilience/model-cooldowns` **sada zahtevaju upravljačku autentifikaciju** (izmena `588a0333`). Klijenti koji su ranije slali običan API ključ bez opsega `manage` dobijaju `403`. Migracija: dodelite ključu opseg `manage` na kontrolnoj tabli API ključeva ili koristite prijavljenu sesiju kontrolne table.

## Promena ponašanja — v3.8.2

`/api/mcp/*` (udaljeni MCP server) je i dalje podrazumevano LOCAL_ONLY, ali sada prihvata zahteve koji ne dolaze sa povratne sprege kada zaglavlje `Authorization: Bearer <api-key>` sadrži opseg `manage`. Izuzetak se eksplicitno omogućava za svaku putanju putem `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` u `src/server/authz/routeGuard.ts`; srodni prefiks LOCAL_ONLY `/api/cli-tools/runtime/*` namerno nije moguće zaobići jer može da pokrene proizvoljne potprocese. Anonimni zahtevi ka `/api/mcp/*` koji ne dolaze sa povratne sprege i dalje vraćaju `403 LOCAL_ONLY` — podrazumevano ponašanje za svaku novu LOCAL_ONLY putanju ostaje strogo ograničeno na povratnu spregu. Pogledajte [Nivoi zaštite ruta](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testiranje

- Jedinični testovi: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Javna lista dozvoljenih ruta: `tests/unit/public-api-routes.test.ts`.
- Pokretanje ciljanog testa: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Отклањање грешака

Цевовод увек означава одговоре са:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

За проверене захтеве, заглавља захтева узводно (на страни руковаоца) такође укључују:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Користите `assertAuth(req, expectedClass)` унутар руковалаца — он избацује `AuthzAssertionError` са кодом `AUTHZ_NOT_INITIALIZED` ако је међуверзија заобиђена (корисно за хватање регресије конфигурације у тестовима).

## Pogledajte takođe

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — oznaka za autentifikaciju po krajnjoj tački
- [COMPLIANCE.md](../security/COMPLIANCE.md) — dnevnik revizije za događaje autentifikacije
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tri imenska prostora opsega i MCP katalog opsega alata
- Izvor: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
