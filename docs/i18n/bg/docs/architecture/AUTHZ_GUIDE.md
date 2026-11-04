# Authorization Guide (Български)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Източник на истина:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Последна актуализация:** 2026-09-22 — пространствата от имена на обхватите сочат към MCP-SERVER.md

OmniRoute разполага с ориентиран към маршрутите конвейер за оторизация, който контролира всяка API заявка. Класифицирането е **детерминистично** и **затворено при неуспех** — всичко, което не може да бъде класифицирано, се причислява към `MANAGEMENT` и изисква сесия или токен с управленско ниво на достъп. Тази страница обяснява модела за инженерите, които поддържат маршрути или проектират нови крайни точки.

![Конвейер за AuthZ (3 класа маршрути + оценяване на политики)](../diagrams/exported/authz-pipeline.svg)

> Източник: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Два режима на удостоверяване

### 1. API ключ (носител)

Използва се за OpenAI/Anthropic/Gemini-compatible клиента APIs и няколко маршрута за управление, когато ключът има `manage` обхват.

```
Authorization: Bearer <api-key>
```

Валидиран от `isValidApiKey()` / `extractApiKey()` в `src/sse/services/auth.ts` и реекспортиран чрез `src/shared/utils/apiAuth.ts`. Валидаторът също така приема `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars като постоянни ключове за преминаване (проблем #1350).

### 2. Сесия на таблото за управление (бисквитка auth_token)

За страници на таблото за управление и администраторски операции.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Бисквитката е сесия само когато JWT потвърди** и** носи `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Всеки потребител на бисквитка (защита на маршрута на таблото (`isDashboardSessionAuthenticated()`), опресняване на тръбопровода за удостоверяване, ръкостискане WebSocket, сървър на живо, `/api/settings/require-login`, `/api/auth/status`) преминава през този помощник. Други JWTs подписани с `JWT_SECRET` съществуват — Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` токени за притежатели на ключове — и никога не са сесии (#13298).

Проверено от `isDashboardSessionAuthenticated()` в `src/shared/utils/apiAuth.ts`. Конвейерът автоматично опреснява JWT когато му остават по-малко от 7 дни от 30-дневния му живот.

Една сесия може също да приключи преди изтичането на нейните 30 дни, тъй като всеки минтер преминава през `mintDashboardSessionToken` (време на издаване `iat` и id `jti`) и верификаторът проверява две настройки: `sessionsValidAfter`, зададена чрез промяна на парола, така че всяка сесия, издадена преди да спре проверката (браузърът, който е променил паролата, получава нова бисквитка), и `revokedDashboardSessions`, към която `POST /api/auth/logout` добавя `jti` на сесията, в която не сте излезли. Сесиите, изсечени от по-стара версия, не носят нито една претенция и остават валидни до първата промяна на паролата. Ако настройките не могат да бъдат прочетени, сесията не е надеждна.

Някои маршрути за управление приемат** или** режим: бисквитка OR `Bearer <key>` когато ключът API има `manage` (или `admin`) обхват. Това позволява работния процес „конфигурируем чрез API повиквания“, добавен във v3.8.

#### Допълнителен OIDC портал за вход (#6973)

Входът за администратор на таблото за управление също поддържа an** включване** OIDC (OpenID Connect) протича заедно с влизането с парола по подразбиране — паролата за влизане никога не се премахва, само се допълва:

- Дезактивирано, освен ако `settings.oidcEnabled === true`** и** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` са конфигурирани (Настройки → Auth). `GET /api/auth/oidc/login` връща `400` в противен случай.
- `GET /api/auth/oidc/login` открива `authorization_endpoint` от `/.well-known/openid-configuration` на издателя (връща се към `<issuer>/authorize`), изгражда пренасочването URI от входящата заявка (`x-forwarded-proto` -aware) и пренасочва към IdP с случаен `state` съхранен в `httpOnly` `oidc_state` бисквитка.
- `GET /api/auth/oidc/callback` валидира `state`, обменя кода за оторизация и проверява подписа на токена ID чрез JWKS на издателя (`jose` на `createRemoteJWKSet`, кеширан за JWKS URI) с проверки `issuer`/`audience`. Достъпът до таблото за управление изисква непразен `oidcAllowedSubjects` списък, `oidcAdmissionClaim` политика или и двете. Списъкът с теми съответства `sub` или `email` само когато `email_verified === true`. Незадължителната политика за искане приема разделен с точка път за искане на ID-токен (например `realm_access.roles`) и масив от приети стойности; разрешената претенция трябва да бъде масив от низове, съдържащи поне една приета стойност. Ако и двете политики са конфигурирани, и двете трябва да преминат. Missing/malformed заявките се затварят неуспешно и без нито една политика обратното извикване отказва влизане (`not_configured`). Съществуващите конфигурации само за субекти остават непроменени.
- Keycloak обикновено картографира ролите на областта в токени за достъп, не непременно токени ID. За да изисквате ролята на областта `admin`, конфигурирайте картограф на протокол за този клиент, който включва `realm_access.roles` в своя**ID токен** , след това задайте `oidcAdmissionClaim` на `{ "path": "realm_access.roles", "values": ["admin"] }`. Проверете действителното искане за ID-токен за този клиент, преди да активирате достъп само за роля; приложението не чете ролите на маркер за достъп. Отказът на токен от страна на IdP може да допълни, но не замества тази проверка от страна на приложението.
- При успех сече** точно същото** 30-дневен `auth_token` JWT проблеми с паролата за влизане (`src/app/api/auth/login/route.ts`), така че останалата част от сесията на таблото за управление (автоматично опресняване, флагове за бисквитки) е непроменена — OIDC замества само начина, по който бисквитката се изсича, а не това, което предоставя. Промените в IdP roles/groups не обезсилват съществуващите OmniRoute сесии; излизането, ротацията на паролата или изтичането на сесията все още определят техния живот.
- Всяка настройка `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) е в `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` отговаря `400 PASSWORD_REQUIRED` освен ако тялото носи паролата за управление като `currentPassword` (`401 PASSWORD_MISMATCH`, когато е грешна). `oidcDisablePasswordLogin` отказва парола _login_ (`POST /api/auth/login`), но запазва съхранената хеш парола и повторното удостоверяване все още проверява `currentPassword` срещу нея.
- `corsOrigins` и `bruteForceProtection` също са в `SECURITY_IMPACTING_SETTINGS_KEYS` : разхлабването или отслабва защитите при влизане, така че те приемат същото `currentPassword` повторно удостоверяване (разделът Сигурност го изисква) и импортирането на JSON ги изпуска.
- Всеки ключ за политика за сигурност — записите в `SECURITY_IMPACTING_SETTINGS_KEYS`, всеки ключ `oidc*` и състоянието на сесията на таблото — е** само за оператор** на `PATCH /api/settings`: API ключ с обхват на управление или `oma_` токен за достъп се отказва с `403` дори когато изпраща правилния `currentPassword` и отказът се проверява като `settings.update_failed` с `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` в `src/lib/api/operatorCredential.ts`). Обикновените настройки (тема, предпочитания за показване) остават записваеми за `manage` ключ или `admin` токен за достъп. Всяка мутация на самия `/api/settings` (и на `/api/settings/require-login`) също се нуждае от обхвата на токена за достъп `admin` (`ADMIN_MUTATION_EXACT_PATHS` в `src/server/authz/accessScopes.ts`, съвпадение на точен път); `GET` остава `read`, а другите `/api/settings/*` подмаршрути (проксита, комбо настройки по подразбиране, псевдоними на модела, компресия, изчиствания...) запазват изведения от метода `write` обхват.
- `POST /api/settings/import-json` пропуска това повторно удостоверяване, така че изпуска всеки ключ в `IMPORT_STRIPPED_SETTINGS_KEYS` (същия файл) преди запис: паролата и `currentPassword`, всеки запис `SECURITY_IMPACTING_SETTINGS_KEYS` и състоянието на сесията на таблото за управление (`sessionsValidAfter`, `revokedDashboardSessions`). Импортирането на по-стар архив следователно не може да съживи сесия, която вече е приключила с промяна на парола или излизане.

#### Незадължително TOTP двуфакторно влизане (#16619)

Записан от Настройки → Сигурност; изключен, докато операторът не го включи (`src/server/auth/dashboardMfa.ts`).

- **Какво обхваща:** парола за влизане (`POST /api/auth/login`, която след това се нуждае от `POST /api/auth/mfa/verify`) и `omniroute connect` (`POST /api/cli/connect`, която отказва обмен само с парола и приема кода като `totp`).
- **Какво не покрива:** OIDC / SSO влизане (`/api/auth/oidc/callback`) не изисква OmniRoute TOTP. Той разчита на собствения втори фактор на доставчика на самоличност, така че наложете MFA в IdP, ако OIDC е активиран.
- **Възстановяване** (загубено устройство, без останали кодове за възстановяване или фактор, който вече не може да бъде проверен, например след промяна `STORAGE_ENCRYPTION_KEY` ):
  1. Рестартирайте сървъра с `OMNIROUTE_DISABLE_MFA=true`.
  2. На самия хост (loopback peer и loopback `Host`, като `http://localhost:20128`), влезте с паролата. Вторият фактор се пропуска само за този произход; всеки друг произход все още се нуждае от кода.
  3. В Settings → Security → Disable въведете паролата и оставете кода празен. `POST /api/auth/mfa/disable` приема тяло без `code` само докато променливата е зададена и заявката идва от хоста; все още изисква сесията на таблото за управление и текущата парола и се проверява като `auth.mfa.disabled` с `secondFactor: "recovery_switch"`.
  4. Премахнете настройката `OMNIROUTE_DISABLE_MFA`, рестартирайте и се регистрирайте отново, ако е необходимо.

## Класове маршрути

`src/server/authz/types.ts` дефинира три класа; всеки маршрут, който не може да се класифицира детерминистично, се причислява по подразбиране към `MANAGEMENT`.

| Клас         | Описание                                                                                                                                                               | Изисквано удостоверяване                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| `PUBLIC`     | Изрично безопасни маршрути: вход, изход, статус, инициализация, проверка на състоянието, начално настройване при онбординг.                                            | Не се изисква                                                                 |
| `CLIENT_API` | Крайни точки за обслужване на модели: `/api/v1/*`, `/api/v1beta/*`, както и псевдоними `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer ключ, когато е активирана ефективната флагче-функция `REQUIRE_API_KEY` |
| `MANAGEMENT` | Страници на таблото за управление, настройки, доставчици, ключове, крайни точки за администриране и диагностика.                                                       | Сесия в таблото ИЛИ Bearer с обхват `manage`                                  |

Някои действия `MANAGEMENT` са **само за оператора**: ключ с обхват `manage` не е достатъчен.
Износът на съхранените удостоверителни данни (`GET /api/settings/export-json`, `GET /api/db-backups/export`,
`GET /api/db-backups/exportAll`), възстановяването на архив върху текущите данни
(`POST /api/db-backups/import`, включително с `dryRun=true`, `POST /api/db-backups` с възстановяване по id,
`POST /api/settings/import-json`), както и премахването на точки за възстановяване (почистване с `DELETE /api/db-backups`
и `PATCH /api/db-backups`, защото запазената от този метод политика за съхранение задейства автоматичното изчистване
след всяко архивиране), изискват сесия в таблото, локалния CLI субект или изключен вход.
Издаването на токен за синхронизация (`POST /api/sync/tokens`) и създаването на CLI токен за достъп с обхват `admin`
(`POST /api/cli/tokens`) изискват сесия в таблото или локалния CLI субект при всеки режим на вход.
API ключовете с всякакъв обхват и токените за достъп `oma_` не са операторски удостоверителни данни: когато се изисква,
те получават `403`. Проверката се извършва в `src/lib/api/operatorCredential.ts`
(`resolveOperatorCredential()` / `requireOperatorCredential()`). Промяната на настройките за вход също е само за оператора:
`POST /api/settings/require-login` (задаване на паролата за управление / превключване на `requireLogin`) приема само
тези удостоверителни данни, след като вече има парола. Прозорецът за първоначално настройване (още няма парола)
не се променя, а сесията в таблото трябва да изпрати `currentPassword`, за да смени паролата (`403`, ако липсва или е
грешна; записва се в одита като `settings.update_failed`). Локалният CLI и инстанцията с изключен вход запазват
пътя за възстановяване и могат да зададат парола без нея, тъй като и двете са свързани с хоста, на който принадлежи
директорията с данни.

## Тръбопровод

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

Надеждни вътрешни заглавки (дефинирани в `src/server/authz/headers.ts`) са** премахнати от входящи заявки** преди класификация — клиентите не могат да попълват предварително `x-omniroute-auth-*` за да се представят за субект.

### Договори за полици

Всеки клас маршрут има политика в `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — винаги връща `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — извлича Bearer, валидира чрез `validateApiKey()`. Преминава към анонимен само когато флагът за ефективна функция `REQUIRE_API_KEY` е деактивиран. Ефективният флаг се разрешава чрез `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), така че флаговете на функциите на таблото за управление и променливите на средата управляват `/api/v1/*`, `/api/v1beta/*` и псевдонимите последователно; неуспешно затваряне на резолвера. Позволява заявки за сесия на таблото за клиентски API маршрути (включително `/api/v1/models`, използван от каталога на модела на таблото). Когато Entra ID SSO е активиран, носител, който структурно е Entra токен (три base64url сегмента, `RS*` alg, `kid`) се обработва от SSO клона** преди** `validateApiKey()` и неговата присъда е окончателна — той никога не попада в пътя на ключа на API или клона за деградиране до анонимен, така че прекъсването на доставчик на идентичност не може да стане отворен достъп. Статичните API ключове не са засегнати. Вижте [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — приема сесия на таблото за управление, вътрешни заявки за синхронизиране на модели (съвпадащи с `/api/providers/[name]/(sync-models|models)`) или пропуска изцяло, ако `isAuthRequired()` върне false. Връща 403 (`AUTH_001`), когато токенът на носител е наличен, но е невалиден, 401 в противен случай. Също така налага нивата за защита на маршрута (LOCAL_ONLY / ALWAYS_PROTECTED) преди всеки клон за удостоверяване — вижте [Нивата за защита на маршрута](../security/ROUTE_GUARD_TIERS.md). LOCAL_ONLY пътеките в `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (днес: `/api/mcp/`) могат да бъдат достъпни от non-loopback, когато носещият ключ носи `manage` обхвата; всички останали LOCAL_ONLY пътища остават стриктно обратно независимо от обхвата.

Успешна политика връща `AuthSubject` с `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Манипулаторите надолу по веригата могат да го прочетат чрез `assertAuth(request, "CLIENT_API")` в `src/server/authz/assertAuth.ts` вместо да изпълняват повторно логиката за удостоверяване.

## Списък с обществени маршрути

`src/shared/constants/publicApiRoutes.ts` е изричният списък с разрешени:

Списъкът е разделен на** форма** , а разделянето е носещо (GHSA-74g9-q8f6-793h): префиксът се съпоставя с `startsWith()`, така че съвпада и с всеки съседен път, споделящ своите водещи знаци. `/api/usage/om-usage` като префикс, отбелязан `/api/usage/om-usage<anything>` PUBLIC, и Next разрешава това на `/api/usage/[connectionId]` — манипулатор без собствено удостоверяване.

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

Маршрутите само за четене са публични** само** за безопасни методи. Забележка: `classifyRoute()` изключва `/api/v1/*` и `/api/v1beta/*` от PUBLIC падащия — те винаги са `CLIENT_API` така че политиката за ключ на носител все още се прилага.

## Добавяне на нов маршрут

### Шаблон 1 — Публична крайна точка на клиентския API (Bearer удостоверяване)

Маршрутите под `/api/v1/` и `/api/v1beta/` автоматично се класифицират като `CLIENT_API`. Middleware компонентът налага Bearer проверката; не е необходимо обработчиците на маршрути да я повтарят, но могат да прочетат субекта, ако това е полезно.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... логика на обработчика
}
```

### Шаблон 2 — Крайна точка за управление (сесия или Bearer + manage)

Използвайте `requireManagementAuth()` от `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... логика на обработчика
}
```

При успех `requireManagementAuth()` връща `null`, а при грешка — JSON `Response`:

- 401 `AUTH_001` „Изисква се удостоверяване“ — липсват каквито и да е идентификационни данни
- 403 — невалиден Bearer **или** е предоставен Bearer, но ключът няма обхват `manage` / `admin`

`hasManageScope(scopes)` връща true за `"manage"` или `"admin"`.

### Шаблон 3 — Добавяне към публичния списък с разрешени маршрути

Изберете множеството според формата, а не според удобството. Единичен маршрут се добавя в `PUBLIC_API_ROUTES_EXACT` (или в `PUBLIC_READONLY_CORS_API_ROUTES`, ако е само за GET); единствено реално поддърво се добавя в `PUBLIC_API_ROUTE_PREFIXES` и то **трябва да завършва с `/`**. Добавянето на единичен маршрут в списъка с префикси прави публичен и всеки съседен път, който споделя началните му символи — включително маршрути със сродни динамични сегменти, добавени по-късно (GHSA-74g9-q8f6-793h). Актуализирайте модулните тестове в `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` и `tests/unit/authz/classify.test.ts`.

## Обхвати

Три пространства от имена. Всяка проверка чете само собствените си низове. Съпоставката,
включително защо `manage` не преминава `scopeMatches` за `read:compression` и защо
токен за достъп с `read` не може да изпълни `PATCH /api/keys/{id}`, е описана в
[Три пространства от имена за обхвати](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API ключовете съдържат масив `scopes` (съхраняван като JSON в `api_keys.scopes`, вижте `src/lib/db/apiKeys.ts`).

### Обхват за управление

- `manage` / `admin` — `hasManageScope`. Bearer достъп до маршрутите на API за управление.
- `mcp:connect`, `self:usage`, `self:account-quota` и
  `policy:bypass-provider-quota` са допълващи обхвати с точно съвпадение. Те са
  извън `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` отваря само
  изключението за адреси извън loopback за `/api/mcp/`.

### Обхвати на MCP инструменти

Каталог и правила за съвпадение (идентичен низ или предоставен обхват, завършващ на `*`):
[Обхвати на MCP инструменти](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` в `src/shared/constants/mcpScopes.ts` е първоначалното типизирано
подмножество, а не пълният каталог. Налагането на ограниченията се извършва в
`open-sse/mcp-server/scopeEnforcement.ts`, след като `resolveCallerScopeContext()`
разреши обхватите от информацията за MCP удостоверяване, метаданните на заявката или `OMNIROUTE_MCP_SCOPES`.
То остава изключено, освен ако `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Обхвати на токени за достъп

`read` / `write` / `admin` при токени `oma_live_…`, подредени по ранг чрез `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Този ранг се прилага само към идентификационните
данни на токена за достъп. Вижте [Удостоверяване за управление](../guides/MANAGEMENT-AUTH.md).

## Превключвател за задължително удостоверяване

`isAuthRequired()` в `src/shared/utils/apiAuth.ts` решава дали за дадена заявка се прилага **някакво** удостоверяване:

- `settings.requireLogin === false` → удостоверяването е изключено глобално, с изключение на винаги защитеното ниво
  (вж. [Нива на защита на маршрутите](../security/ROUTE_GUARD_TIERS.md)) и извикванията, които издават удостоверителни данни,
  приемани от системата. За тях се изисква същото удостоверителни данни, както при включен вход: издаване на токени
  за синхронизация, издаване на CLI токени за достъп с всякакъв обхват, както и създаване на API ключ с обхват
  `manage`/`admin`, даване на такъв обхват на ключ, пренареждане или показване на такъв ключ
  (`requireCredentialForManagementScopedKey()` в `src/lib/api/requireManagementAuth.ts`). Ключовете само за инференция
  остават отворени.
- Не е конфигурирана парола **и** няма променлива на средата `INITIAL_PASSWORD` → режимът на начално настройване позволява
  съветника за онбординг и заявките от loopback, но заявките от мрежата все още изискват удостоверителни данни.
- Всяка грешка в БД → отказ (сигурно по подразбиране, fail closed).

Проверката на клиентските API ключове използва `isRequireApiKeyEnabled()` в `src/shared/utils/featureFlags.ts`,
а не директно четене на `process.env.REQUIRE_API_KEY`. Това е важно за разгърнатите инстанции: превключването на
`REQUIRE_API_KEY` в Dashboard → Feature Flags записва изключение в БД и веднага засяга `/v1/*`, `/v1beta/*`, `/models`,
`/responses`, `/chat/completions`, `/codex/*` и другите проверки на клиентското API, които използват този помощен модул.
Ако хранилището на флаговете не може да се прочете, удостоверяването на клиентското API отказва и изисква ключ.

## Несъвместима промяна — v3.8.0

Крайните точки `/api/v1/agents/tasks/*` и `/api/resilience/model-cooldowns` **вече изискват удостоверяване за управление** (commit `588a0333`). Клиентите, които преди са изпращали обикновен API ключ без обхвата `manage`, получават `403`. Миграция: или задайте на ключа обхвата `manage` в таблото API Keys, или използвайте сесия с влизане в таблото.

## Промяна в поведението — v3.8.2

`/api/mcp/*` (отдалеченият MCP сървър) все още е LOCAL_ONLY по подразбиране, но вече приема заявки, които не са loopback, когато заглавката `Authorization: Bearer <api-key>` съдържа обхвата `manage`. Изключението се управлява изрично за всеки път чрез `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` в `src/server/authz/routeGuard.ts`; сродният LOCAL_ONLY префикс `/api/cli-tools/runtime/*` умишлено НЕ може да бъде заобиколен, защото може да стартира произволни подпроцеси. Анонимните заявки към `/api/mcp/*`, които не са loopback, продължават да връщат `403 LOCAL_ONLY` — поведението по подразбиране за всеки нов LOCAL_ONLY път остава строго ограничено до loopback. Вижте [Нива на защита на маршрутите](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Тестване

- Модулни тестове: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Публичен списък с разрешени маршрути: `tests/unit/public-api-routes.test.ts`.
- Изпълнение на конкретен тест: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Отстраняване на грешки

Тръбопроводът винаги подпечатва отговорите с:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

За удостоверени заявки заглавките на заявките нагоре (от страна на манипулатора) също включват:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Използвайте `assertAuth(req, expectedClass)` вътрешни манипулатори — той хвърля `AuthzAssertionError` с код `AUTHZ_NOT_INITIALIZED` ако междинният софтуер е бил заобиколен (полезно за улавяне на регресии в конфигурацията при тестове).

## Вижте също

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — маркер за удостоверяване за всяка крайна точка
- [COMPLIANCE.md](../security/COMPLIANCE.md) — журнал за одит на събитията по удостоверяване
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — три пространства от имена за обхвати и каталог на обхватите на MCP инструментите
- Изходен код: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
