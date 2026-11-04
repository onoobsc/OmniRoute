# Authorization Guide (ខ្មែរ)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **ប្រភពនៃការពិត:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **បានធ្វើបច្ចុប្បន្នភាពចុងក្រោយ:** 2026-09-22 — ឈ្មោះលំហនៃវិសាលភាពចង្អុលទៅ MCP-SERVER.md

OmniRoute មានបំពង់បង្ហូរការអនុញ្ញាតដែលដឹងពីផ្លូវ ដែលទប់ស្កាត់រាល់សំណើ API។ ការចាត់ថ្នាក់គឺ **កំណត់បាន** និង **បរាជ័យបិទ** — អ្វីដែលមិនអាចចាត់ថ្នាក់បាននឹងក្លាយជា `MANAGEMENT` ហើយទាមទារវគ្គ ឬថូខឹនកម្រិតគ្រប់គ្រង។ ទំព័រនេះពន្យល់ពីគំរូសម្រាប់វិស្វករដែលថែទាំផ្លូវ ឬរចនាចំណុចបញ្ចប់ថ្មី។

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> ប្រភព: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## របៀបផ្ទៀងផ្ទាត់ពីរ

### 1. API Key (អ្នកកាន់)

ប្រើសម្រាប់អតិថិជន OpenAI/Anthropic/Gemini-compatible APIs និងផ្លូវគ្រប់គ្រងមួយចំនួននៅពេលដែលសោមានវិសាលភាព `manage` ។

```
Authorization: Bearer <api-key>
```

ធ្វើឱ្យមានសុពលភាពដោយ `isValidApiKey()` / `extractApiKey()` ក្នុង `src/sse/services/auth.ts` និងនាំចេញឡើងវិញតាមរយៈ `src/shared/utils/apiAuth.ts`។ អ្នកផ្តល់សុពលភាពក៏ទទួលយក `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ជាគ្រាប់ចុចឆ្លងកាត់ជាប់លាប់ (បញ្ហា #1350)។

### 2. សម័យផ្ទាំងគ្រប់គ្រង (ខូគី auth_token)

សម្រាប់ទំព័រផ្ទាំងគ្រប់គ្រង និងប្រតិបត្តិការអ្នកគ្រប់គ្រង។

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

ខូគីគឺជាវគ្គមួយនៅពេលដែល JWT ផ្ទៀងផ្ទាត់ប៉ុណ្ណោះ។** និង** អនុវត្ត `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) ។ រាល់អ្នកប្រើប្រាស់ខូគី (អ្នកការពារផ្លូវផ្ទាំងគ្រប់គ្រង (`isDashboardSessionAuthenticated()`) ) ការធ្វើឱ្យស្រស់បំពង់ authz ការចាប់ដៃ WebSocket ម៉ាស៊ីនមេបន្តផ្ទាល់ `/api/settings/require-login` `/api/auth/status`) ឆ្លងកាត់ជំនួយនោះ។ JWTs ផ្សេងទៀតដែលបានចុះហត្ថលេខាជាមួយ `JWT_SECRET` មាន — Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` tokens សម្រាប់អ្នកកាន់គន្លឹះ — ហើយមិនមែនជាវគ្គ (#13298) ។

ផ្ទៀងផ្ទាត់ដោយ `isDashboardSessionAuthenticated()` ក្នុង `src/shared/utils/apiAuth.ts`។ បំពង់បញ្ជូន JWT ឡើងវិញដោយស្វ័យប្រវត្តិ នៅពេលដែលវានៅសល់តិចជាង 7 ថ្ងៃក្នុងអាយុកាល 30 ថ្ងៃ។

វគ្គមួយក៏អាចបញ្ចប់មុនរយៈពេល 30 ថ្ងៃរបស់វាដែរ ព្រោះរាល់ minter ឆ្លងកាត់ `mintDashboardSessionToken` (ពេលវេលាមានបញ្ហា `iat` និង id `jti`) ហើយអ្នកផ្ទៀងផ្ទាត់ពិនិត្យមើលការកំណត់ពីរ៖ `sessionsValidAfter` កំណត់ដោយការផ្លាស់ប្តូរពាក្យសម្ងាត់ ដូច្នេះរាល់វគ្គដែលបានចេញមុនពេលវាឈប់ផ្ទៀងផ្ទាត់ (កម្មវិធីរុករកដែលប្តូរពាក្យសម្ងាត់ទទួលបានខូគីថ្មី) និង `revokedDashboardSessions` ដែល `POST /api/auth/logout` បន្ថែម ' `jti`-out sessions ។ វគ្គដែលកំណត់ដោយការចេញផ្សាយចាស់ជាងនេះមិនអាចទាមទារបានទេ ហើយនៅតែមានសុពលភាពរហូតដល់ការប្តូរពាក្យសម្ងាត់ដំបូង។ ប្រសិនបើការកំណត់មិនអាចអានបានទេ សម័យនោះមិនទុកចិត្តទេ។

ផ្លូវគ្រប់គ្រងមួយចំនួនទទួលយក** ទាំង** របៀប៖ ខូគី OR `Bearer <key>` នៅពេលគ្រាប់ចុច API មានវិសាលភាព `manage` (ឬ `admin`) ។ នេះគឺជាអ្វីដែលអនុញ្ញាតឱ្យដំណើរការការងារ "កំណត់រចនាសម្ព័ន្ធតាមរយៈការហៅ API " ដែលបានបន្ថែមនៅក្នុង v3.8 ។

#### ច្រកចូល OIDC ជាជម្រើស (#6973)

ការចូលគ្រប់គ្រងផ្ទាំងគ្រប់គ្រងក៏គាំទ្រផងដែរ។** ជ្រើសរើសចូល** OIDC (OpenID Connect) ហូរអមជាមួយការចូលពាក្យសម្ងាត់លំនាំដើម — ការចូលពាក្យសម្ងាត់មិនត្រូវបានដកចេញទេ មានតែបន្ថែមប៉ុណ្ណោះ៖

- បានបិទ លុះត្រាតែ `settings.oidcEnabled === true`** និង** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` ត្រូវបានកំណត់រចនាសម្ព័ន្ធទាំងអស់ (ការកំណត់ → Auth) ។ `GET /api/auth/oidc/login` ត្រឡប់ `400` បើមិនដូច្នេះទេ។
- `GET /api/auth/oidc/login` រកឃើញ `authorization_endpoint` ពី `/.well-known/openid-configuration` របស់អ្នកចេញ (ធ្លាក់ត្រឡប់ទៅ `<issuer>/authorize`) បង្កើតការប្តូរទិស URI ពីសំណើដែលចូលមក (`x-forwarded-proto` -aware) ហើយប្តូរទិសទៅ IdP ជាមួយនឹង `state` ចៃដន្យដែលរក្សាទុកក្នុង `httpOnly` `oidc_state` cookie ។
- `GET /api/auth/oidc/callback` ផ្តល់សុពលភាព `state` ផ្លាស់ប្តូរលេខកូដអនុញ្ញាត និងផ្ទៀងផ្ទាត់ហត្ថលេខារបស់ ID token តាមរយៈ JWKS របស់អ្នកចេញ (`jose`'s `createRemoteJWKSet`, ឃ្លាំងសម្ងាត់ក្នុងមួយ JWKS URI) ជាមួយនឹងការត្រួតពិនិត្យ `issuer`/`audience` ។ ការចូលប្រើផ្ទាំងគ្រប់គ្រងតម្រូវឱ្យបញ្ជី `oidcAllowedSubjects` មិនទទេ គោលការណ៍ `oidcAdmissionClaim` ឬទាំងពីរ។ បញ្ជីប្រធានបទត្រូវគ្នានឹង `sub` ឬ `email` តែនៅពេល `email_verified === true`. គោលការណ៍ទាមទារជាជម្រើសយកផ្លូវទាមទារលេខសម្គាល់ដែលបំបែកដោយចំនុច (ឧទាហរណ៍ `realm_access.roles`) និងអារេនៃតម្លៃដែលទទួលយក។ ការទាមទារដែលបានដោះស្រាយត្រូវតែជាអារេនៃខ្សែអក្សរដែលមានយ៉ាងហោចណាស់តម្លៃដែលទទួលយកមួយ។ ប្រសិនបើគោលការណ៍ទាំងពីរត្រូវបានកំណត់រចនាសម្ព័ន្ធ ទាំងពីរត្រូវតែឆ្លងកាត់។ ការទាមទារ Missing/malformed បរាជ័យបានបិទ ហើយដោយគ្មានគោលការណ៍ទាំងនោះ ការហៅត្រឡប់វិញបដិសេធការចូល (`not_configured`) ។ ការកំណត់រចនាសម្ព័ន្ធសម្រាប់តែប្រធានបទដែលមានស្រាប់បន្តមិនផ្លាស់ប្តូរ។
- ជាធម្មតា Keycloak គូសផែនទីតួនាទីអាណាចក្រចូលទៅក្នុងនិមិត្តសញ្ញាចូលប្រើ មិនចាំបាច់ជានិមិត្តសញ្ញា ID ទេ។ ដើម្បីទាមទារតួនាទីអាណាចក្រ `admin` កំណត់រចនាសម្ព័ន្ធកម្មវិធីត្រាប់តាមពិធីការសម្រាប់ម៉ាស៊ីនភ្ញៀវនេះដែលរួមបញ្ចូល `realm_access.roles` នៅក្នុងរបស់វា**ID និមិត្តសញ្ញា** បន្ទាប់មកកំណត់ `oidcAdmissionClaim` ទៅ `{ "path": "realm_access.roles", "values": ["admin"] }`។ ពិនិត្យមើលការទាមទារនិមិត្តសញ្ញាលេខសម្គាល់ពិតប្រាកដសម្រាប់អតិថិជននេះ មុនពេលបើកការចូលប្រើសម្រាប់តែតួនាទីប៉ុណ្ណោះ។ កម្មវិធីមិនបានអានតួនាទីសញ្ញាចូលដំណើរការទេ។ ការបដិសេធនិមិត្តសញ្ញាចំហៀង IdP អាចបំពេញបន្ថែម ប៉ុន្តែមិនជំនួសការត្រួតពិនិត្យផ្នែកខាងកម្មវិធីនេះទេ។
- នៅលើភាពជោគជ័យវាកំណត់** ដូចគ្នា** ក្នុងរយៈពេល 30 ថ្ងៃ `auth_token` JWT បញ្ហាការចូលពាក្យសម្ងាត់ (`src/app/api/auth/login/route.ts`) ដូច្នេះនៅសល់នៃបន្ទាត់នៃសម័យប្រជុំផ្ទាំងគ្រប់គ្រង (ការធ្វើឱ្យស្រស់ដោយស្វ័យប្រវត្តិ ទង់ខូគី) គឺមិនផ្លាស់ប្តូរ — OIDC គ្រាន់តែជំនួសរបៀបដែលខូគីត្រូវបាន minted មិនមែនអ្វីដែលវាផ្តល់ឱ្យនោះទេ។ ការផ្លាស់ប្តូរទៅ IdP roles/groups មិនធ្វើឱ្យសម័យ OmniRoute ដែលមានស្រាប់នោះទេ។ ការចាកចេញ ការបង្វិលពាក្យសម្ងាត់ ឬការផុតកំណត់នៃសម័យនៅតែគ្រប់គ្រងពេញមួយជីវិតរបស់ពួកគេ។
- រាល់ការកំណត់ `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) គឺនៅក្នុង `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` ឆ្លើយ `400 PASSWORD_REQUIRED` លុះត្រាតែរាងកាយផ្ទុកពាក្យសម្ងាត់គ្រប់គ្រងជា `currentPassword` (`401 PASSWORD_MISMATCH` នៅពេលដែលវាខុស)។ `oidcDisablePasswordLogin` បដិសេធពាក្យសម្ងាត់ _login_ (`POST /api/auth/login`) ប៉ុន្តែរក្សាលេខសម្ងាត់ដែលបានរក្សាទុក ហើយការផ្ទៀងផ្ទាត់ឡើងវិញនៅតែពិនិត្យមើល `currentPassword` ប្រឆាំងនឹងវា។
- `corsOrigins` និង `bruteForceProtection` ស្ថិតនៅក្នុង `SECURITY_IMPACTING_SETTINGS_KEYS` ផងដែរ៖ ការបន្ធូរបន្ថយ ធ្វើឱ្យការការពារការចូលចុះខ្សោយ ដូច្នេះពួកគេយក `currentPassword` ដូចគ្នាម្តងទៀត (ផ្ទាំងសុវត្ថិភាពស្នើសុំវា) ហើយការនាំចូល JSON ទម្លាក់ពួកគេ។
- រាល់គន្លឹះគោលការណ៍សុវត្ថិភាព — ធាតុ `SECURITY_IMPACTING_SETTINGS_KEYS` រាល់ `oidc*` key និងស្ថានភាពនៃសម័យប្រជុំរបស់ផ្ទាំងគ្រប់គ្រង — គឺ** ប្រតិបត្តិករតែប៉ុណ្ណោះ** នៅលើ `PATCH /api/settings`: គ្រាប់ចុច API ដែលមានវិសាលភាពគ្រប់គ្រង ឬនិមិត្តសញ្ញាចូលប្រើ `oma_` ត្រូវបានបដិសេធដោយ `403` ទោះបីជាវាផ្ញើ `currentPassword` ត្រឹមត្រូវក៏ដោយ ហើយការបដិសេធត្រូវបានធ្វើសវនកម្មជា `settings.update_failed` ជាមួយ `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`) ។ ការកំណត់ធម្មតា (ស្បែក ចំណូលចិត្តការបង្ហាញ) នៅតែអាចសរសេរបានសម្រាប់គ្រាប់ចុច `manage` ឬនិមិត្តសញ្ញាចូលប្រើ `admin` ។ រាល់ការផ្លាស់ប្តូររបស់ `/api/settings` ខ្លួនវា (និង `/api/settings/require-login`) ក៏ត្រូវការវិសាលភាព `admin` access-token (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, exact-path match); `GET` រក្សា `read`, និងផ្លូវរង `/api/settings/*` ផ្សេងទៀត (ប្រូកស៊ី, លំនាំដើមបន្សំ, ឈ្មោះក្លែងក្លាយនៃគំរូ, ការបង្ហាប់, លុប…) រក្សាវិសាលភាព `write` ដែលសន្មតដោយវិធីសាស្ត្រ។
- `POST /api/settings/import-json` រំលងការផ្ទៀងផ្ទាត់ឡើងវិញ ដូច្នេះវាទម្លាក់រាល់គន្លឹះក្នុង `IMPORT_STRIPPED_SETTINGS_KEYS` (ឯកសារដូចគ្នា) មុនពេលសរសេរ៖ ពាក្យសម្ងាត់ និង `currentPassword` រាល់ធាតុ `SECURITY_IMPACTING_SETTINGS_KEYS` និងស្ថានភាពសម័យនៃផ្ទាំងគ្រប់គ្រង (`sessionsValidAfter`, `revokedDashboardSessions`)។ ការនាំចូលការបម្រុងទុកចាស់ ដូច្នេះមិនអាចរស់ឡើងវិញនូវវគ្គដែលការផ្លាស់ប្តូរពាក្យសម្ងាត់ ឬការចាកចេញពីគណនីបានបញ្ចប់រួចហើយនោះទេ។

#### ការចូលជាជម្រើស TOTP two-factor login (#16619)

បានចុះឈ្មោះពីការកំណត់ → Security; បិទរហូតដល់ប្រតិបត្តិករបើកវា (`src/server/auth/dashboardMfa.ts`) ។

- **អ្វីដែលវាគ្របដណ្តប់:** ការចូលពាក្យសម្ងាត់ (`POST /api/auth/login` ដែលបន្ទាប់មកត្រូវការ `POST /api/auth/mfa/verify`) និង `omniroute connect` (`POST /api/cli/connect` ដែលបដិសេធការប្តូរពាក្យសម្ងាត់តែប៉ុណ្ណោះ ហើយយកលេខកូដជា `totp`) ។
- **អ្វីដែលវាមិនគ្របដណ្តប់៖** OIDC / SSO ចូល (`/api/auth/oidc/callback`) មិនសួររក OmniRoute TOTP ទេ។ វាពឹងផ្អែកលើកត្តាទីពីរផ្ទាល់ខ្លួនរបស់អ្នកផ្តល់អត្តសញ្ញាណ ដូច្នេះសូមអនុវត្ត MFA នៅក្នុង IdP ប្រសិនបើ OIDC ត្រូវបានបើក។
- **ការងើបឡើងវិញ** (ឧបករណ៍ដែលបាត់ គ្មានលេខកូដសង្គ្រោះទុកចោល ឬកត្តាដែលមិនអាចផ្ទៀងផ្ទាត់បានទៀតទេ ឧទាហរណ៍បន្ទាប់ពី `STORAGE_ENCRYPTION_KEY` បានផ្លាស់ប្តូរ)៖
  1. ចាប់ផ្តើមម៉ាស៊ីនមេឡើងវិញដោយប្រើ `OMNIROUTE_DISABLE_MFA=true`។
  2. នៅលើម៉ាស៊ីនខ្លួនឯង (loopback peer និង loopback `Host` ដូចជា `http://localhost:20128`) ចូលដោយប្រើពាក្យសម្ងាត់។ កត្តាទីពីរត្រូវបានរំលងសម្រាប់តែប្រភពដើមនោះប៉ុណ្ណោះ។ រាល់ប្រភពដើមផ្សេងទៀតនៅតែត្រូវការលេខកូដ។
  3. នៅក្នុងការកំណត់ → Security → Disable សូមបញ្ចូលពាក្យសម្ងាត់ ហើយទុកលេខកូដឱ្យនៅទទេ។ `POST /api/auth/mfa/disable` ទទួលយកតួដោយគ្មាន `code` តែខណៈពេលដែលអថេរត្រូវបានកំណត់ ហើយសំណើបានមកពីម៉ាស៊ីន។ វានៅតែទាមទារសម័យផ្ទាំងគ្រប់គ្រង និងពាក្យសម្ងាត់បច្ចុប្បន្ន ហើយត្រូវបានធ្វើសវនកម្មជា `auth.mfa.disabled` ជាមួយ `secondFactor: "recovery_switch"`។
  4. មិនកំណត់ `OMNIROUTE_DISABLE_MFA` ចាប់ផ្តើមឡើងវិញ ហើយចុះឈ្មោះម្តងទៀតប្រសិនបើចាំបាច់។

## ប្រភេទ Route

`src/server/authz/types.ts` កំណត់ប្រភេទបី; route ណាមួយដែលមិនអាចចាត់ថ្នាក់ដោយកំណត់បានត្រូវធ្លាក់ទៅ `MANAGEMENT`។

| ប្រភេទ       | ការពិពណ៌នា                                                                                                                                     | ត្រូវការ auth                                                  |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| `PUBLIC`     | Route ដែលមានសុវត្ថិភាពច្បាស់លាស់ — login, logout, status, init, health, onboarding bootstrap។                                                  | គ្មាន                                                          |
| `CLIENT_API` | Endpoint បម្រើម៉ូដែល — `/api/v1/*`, `/api/v1beta/*`, និង alias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`។ | Bearer key នៅពេល feature flag `REQUIRE_API_KEY` ដែលត្រូវបានបើក |
| `MANAGEMENT` | ទំព័រ dashboard, settings, provider, key, endpoint admin និង diagnostics។                                                                      | Dashboard session ឬ Bearer ដែលមាន scope `manage`               |

សកម្មភាព `MANAGEMENT` មួយចំនួនជា **operator-only**: key `manage` មិនគ្រប់គ្រាន់ទេ។ ការនាំចេញ credential ដែលបានរក្សាទុក (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ការស្តារ backup ជំនួស data ផ្ទាល់ (`POST /api/db-backups/import` រួមទាំង `dryRun=true`, `POST /api/db-backups` ស្តារតាម id, `POST /api/settings/import-json`), ការលុប restore point (`DELETE /api/db-backups` cleanup និង `PATCH /api/db-backups` ព្រោះ retention ដែលវារក្សាជំរុញការលុបដោយស្វ័យប្រវត្តិ បន្ទាប់ពីគ្រប់ backup) ទាំងនេះត្រូវការ dashboard session, CLI subject មូលដ្ឋាន ឬការចូលត្រូវបានបិទ។ ការចេញ sync token (`POST /api/sync/tokens`) និងការបង្កើត CLI access token `admin` (`POST /api/cli/tokens`) ត្រូវការ dashboard session ឬ CLI subject មូលដ្ឋានក្នុងគ្រប់ mode ការចូលទាំងអស់។ API key នៃ scope ណាមួយ និង access token `oma_` មិនមែនជា credential operator ទេ: ពួកវាទទួល `403` គ្រប់ពេលដែលត្រូវការ។ ការពិនិត្យស្ថិតនៅ `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`)។ ការផ្លាស់ប្តូរ setting ការចូលក៏ជា operator-only ដែរ: `POST /api/settings/require-login` (កំណត់ management password / បិទបើក `requireLogin`) ទទួលយកតែ credential ទាំងនោះនៅពេលមាន password រួចហើយ — បង្អួច bootstrap លើកដំបូង (មិនទាន់មាន password) មិនផ្លាស់ប្តូរ — ហើយ session dashboard ត្រូវតែផ្ញើ `currentPassword` ដើម្បីជំនួស password (`403` នៅពេលវាបាត់ ឬខុស ត្រូវបានកត់ត្រាជា `settings.update_failed`)។ CLI មូលដ្ឋាន និង instance ដែលបិទការចូល រក្សាផ្លូវសង្គ្រោះ ហើយអាចកំណត់ password ដោយមិនមាន `currentPassword` បាន ព្រោះទាំងពីរភ្ជាប់ជាមួយ host ដែលគ្រប់គ្រង data directory។

## បំពង់

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

បឋមកថាខាងក្នុងដែលអាចទុកចិត្តបាន (កំណត់ក្នុង `src/server/authz/headers.ts`) គឺ** ដកចេញពីសំណើចូល** មុនពេលចាត់ថ្នាក់ — អតិថិជនមិនអាចបញ្ចូល `x-omniroute-auth-*` ជាមុនដើម្បីក្លែងធ្វើជាប្រធានបទបានទេ។

### កិច្ចសន្យាគោលនយោបាយ

ថ្នាក់ផ្លូវនីមួយៗមានគោលការណ៍នៅក្នុង `src/server/authz/policies/`៖

- **`publicPolicy`** (`policies/public.ts`) — តែងតែត្រឡប់ `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ស្រង់ចេញ Bearer ធ្វើឱ្យមានសុពលភាពតាមរយៈ `validateApiKey()`។ ធ្លាក់ចូលទៅក្នុងអនាមិកតែនៅពេលដែលទង់មុខងារ `REQUIRE_API_KEY` ដែលមានប្រសិទ្ធភាពត្រូវបានបិទ។ ទង់ដែលមានប្រសិទ្ធភាពត្រូវបានដោះស្រាយតាមរយៈ `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ដូច្នេះ Dashboard Feature Flags និងបរិស្ថានគ្រប់គ្រង `/api/v1/*`, `/api/v1beta/*` និងឈ្មោះក្លែងក្លាយជាប់លាប់។ ដំណោះស្រាយបរាជ័យបានបិទ។ អនុញ្ញាតសំណើសម័យផ្ទាំងគ្រប់គ្រងលើផ្លូវអតិថិជន API (រួមទាំង `/api/v1/models` ប្រើដោយកាតាឡុកគំរូផ្ទាំងគ្រប់គ្រង)។ នៅពេលដែល Entra ID SSO ត្រូវបានបើក អ្នកកាន់ដែលមានរចនាសម្ព័ន្ធជានិមិត្តសញ្ញា Entra (បីផ្នែក base64url, `RS*` alg, `kid`) ត្រូវបានគ្រប់គ្រងដោយសាខា SSO** ពីមុន** `validateApiKey()` ហើយសាលក្រមរបស់វាគឺ — ចុងក្រោយ វាមិនដែលធ្លាក់ចូលទៅក្នុងផ្លូវ API-key ឬសាខា degrade-to-អនាមិកទេ ដូច្នេះការដាច់ចេញពីអ្នកផ្តល់អត្តសញ្ញាណមិនអាចក្លាយជាការចូលប្រើបើកចំហបានទេ។ គ្រាប់ចុច API ឋិតិវន្តមិនប៉ះពាល់ទេ។ សូមមើល [Entra ID SSO](../security/ENTRA_SSO.md) ។
- **`managementPolicy`** (`policies/management.ts`) — ទទួលយកសម័យផ្ទាំងគ្រប់គ្រង សំណើធ្វើសមកាលកម្មគំរូខាងក្នុង (ត្រូវគ្នានឹង `/api/providers/[name]/(sync-models|models)`) ឬរំលងទាំងស្រុងប្រសិនបើ `isAuthRequired()` ត្រឡប់មិនពិត។ ត្រឡប់ 403 (`AUTH_001`) នៅពេលដែលនិមិត្តសញ្ញា Bearer មានវត្តមាន ប៉ុន្តែមិនត្រឹមត្រូវ 401 បើមិនដូច្នេះទេ។ អនុវត្តផងដែរនូវជួរការពារផ្លូវ (LOCAL_ONLY / ALWAYS_PROTECTED) មុនពេលសាខាផ្ទៀងផ្ទាត់ណាមួយ — ឃើញ [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md) ។ LOCAL_ONLY ផ្លូវក្នុង `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (ថ្ងៃនេះ៖ `/api/mcp/`) អាចត្រូវបានចូលប្រើពី non-loopback នៅពេលដែល Bearer key អនុវត្តវិសាលភាព `manage` ។ ផ្លូវ LOCAL_ONLY ផ្សេងទៀតទាំងអស់នៅតែជារង្វិលជុំតឹងរ៉ឹងដោយមិនគិតពីវិសាលភាព។

គោលការណ៍ជោគជ័យ ត្រឡប់ `AuthSubject` ជាមួយ `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`។ អ្នកដោះស្រាយខាងក្រោមអាចអានវាតាមរយៈ `assertAuth(request, "CLIENT_API")` ក្នុង `src/server/authz/assertAuth.ts` ជំនួសឱ្យការដំណើរការតក្កវិជ្ជាផ្ទៀងផ្ទាត់ឡើងវិញ។

## បញ្ជីផ្លូវសាធារណៈ

`src/shared/constants/publicApiRoutes.ts` គឺជាបញ្ជីអនុញ្ញាតច្បាស់លាស់៖

បញ្ជីត្រូវបានបំបែកដោយ** រាង** ហើយការបំបែកគឺផ្ទុកបន្ទុក (GHSA-74g9-q8f6-793h): បុព្វបទត្រូវបានផ្គូផ្គងជាមួយ `startsWith()` ដូច្នេះវាក៏ត្រូវគ្នានឹងគ្រប់ផ្លូវដែលនៅជាប់គ្នាដែលចែករំលែកតួអក្សរនាំមុខរបស់វា។ `/api/usage/om-usage` ជាបុព្វបទដែលបានសម្គាល់ `/api/usage/om-usage<anything>` PUBLIC ហើយបន្ទាប់ដោះស្រាយវាទៅ `/api/usage/[connectionId]` — អ្នកគ្រប់គ្រងដោយគ្មានសិទ្ធិផ្ទាល់ខ្លួន។

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

ផ្លូវសម្រាប់តែអាន គឺជាផ្លូវសាធារណៈ** តែប៉ុណ្ណោះ** សម្រាប់វិធីសាស្រ្តសុវត្ថិភាព។ ចំណាំ៖ `classifyRoute()` មិនរាប់បញ្ចូល `/api/v1/*` និង `/api/v1beta/*` ពី PUBLIC fall-through — ទាំងនោះតែងតែ `CLIENT_API` ដូច្នេះគោលការណ៍ Bearer-key នៅតែអនុវត្ត។

## ការបន្ថែម Route ថ្មី

### លំនាំទី 1 — Endpoint សាធារណៈសម្រាប់ client API (ការផ្ទៀងផ្ទាត់អត្តសញ្ញាណដោយ Bearer)

Route ក្រោម `/api/v1/` និង `/api/v1beta/` ត្រូវបានចាត់ថ្នាក់ជា `CLIENT_API` ដោយស្វ័យប្រវត្តិ។ Middleware អនុវត្តការត្រួតពិនិត្យ Bearer។ Route handler មិនចាំបាច់ធ្វើវាឡើងវិញទេ ប៉ុន្តែអាចអាន subject បាន ប្រសិនបើមានប្រយោជន៍។

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... តក្កវិជ្ជារបស់ handler
}
```

### លំនាំទី 2 — Endpoint សម្រាប់ការគ្រប់គ្រង (session ឬ Bearer + manage)

ប្រើ `requireManagementAuth()` ពី `src/lib/api/requireManagementAuth.ts`៖

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... តក្កវិជ្ជារបស់ handler
}
```

`requireManagementAuth()` ត្រឡប់ `null` នៅពេលជោគជ័យ ឬ JSON error `Response`៖

- 401 `AUTH_001` "តម្រូវឱ្យមានការផ្ទៀងផ្ទាត់អត្តសញ្ញាណ" — គ្មានព័ត៌មានសម្គាល់អត្តសញ្ញាណសោះ
- 403 — Bearer មិនត្រឹមត្រូវ **ឬ** មាន Bearer ប៉ុន្តែ key ខ្វះ scope `manage` / `admin`

`hasManageScope(scopes)` ត្រឡប់ true សម្រាប់ `"manage"` ឬ `"admin"`។

### លំនាំទី 3 — ការបន្ថែមទៅក្នុង allowlist សាធារណៈ

ជ្រើសរើស set តាមទម្រង់ មិនមែនតាមភាពងាយស្រួលទេ។ Route មួយត្រូវដាក់ក្នុង `PUBLIC_API_ROUTES_EXACT` (ឬ `PUBLIC_READONLY_CORS_API_ROUTES` សម្រាប់ GET-only)។ មានតែ subtree ពិតប្រាកដប៉ុណ្ណោះដែលត្រូវដាក់ក្នុង `PUBLIC_API_ROUTE_PREFIXES` ហើយវា **ត្រូវតែបញ្ចប់ដោយ `/`**។ ការដាក់ route ទោលមួយក្នុងបញ្ជី prefix ក៏ធ្វើឱ្យ path ជាប់គ្នាទាំងអស់ដែលមានតួអក្សរដើមដូចគ្នាក្លាយជាសាធារណៈផងដែរ — រួមទាំង dynamic-segment sibling ដែលត្រូវបានបន្ថែមនៅពេលក្រោយ (GHSA-74g9-q8f6-793h)។ ធ្វើបច្ចុប្បន្នភាព unit test នៅ `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` និង `tests/unit/authz/classify.test.ts`។

## Scopes

ឈ្មោះលំហបី។ កម្មវិធីពិនិត្យនីមួយៗអានតែខ្សែអក្សររបស់វាប៉ុណ្ណោះ។ ការប្រៀបធៀបគ្នា រួមទាំងមូលហេតុដែល `manage` បរាជ័យ `scopeMatches` សម្រាប់ `read:compression` និងមូលហេតុដែល access token `read` មិនអាច `PATCH /api/keys/{id}` គឺ [ឈ្មោះលំហបី](../frameworks/MCP-SERVER.md#three-scope-namespaces)។

API keys មាន array `scopes` (រក្សាទុកជា JSON ក្នុង `api_keys.scopes` សូមមើល `src/lib/db/apiKeys.ts`)។

### Management scope

- `manage` / `admin` — `hasManageScope`។ ការចូលប្រើ Bearer ទៅកាន់ផ្លូវ API គ្រប់គ្រង។
- `mcp:connect`, `self:usage`, `self:account-quota`, និង `policy:bypass-provider-quota` គឺជា scopes ដែលត្រូវគ្នាពិតប្រាកដបន្ថែម។ ពួកវាស្ថិតនៅខាងក្រៅ `MANAGEMENT_API_KEY_SCOPES`។ `mcp:connect` បើកតែ `/api/mcp/` non-loopback carve-out ប៉ុណ្ណោះ។

### MCP tool scopes

កាតាឡុក និងច្បាប់ផ្គូផ្គង (ខ្សែអក្សរដូចគ្នា ឬ scope ដែលបានផ្តល់ដែលបញ្ចប់ដោយ `*`): [MCP tool scopes](../frameworks/MCP-SERVER.md#mcp-tool-scopes)។ `MCP_SCOPE_LIST` ក្នុង `src/shared/constants/mcpScopes.ts` គឺជា subset ដែលបានកំណត់ប្រភេទដើម មិនមែនជាកាតាឡុកពេញលេញនោះទេ។ ការអនុវត្តដំណើរការក្នុង `open-sse/mcp-server/scopeEnforcement.ts` បន្ទាប់ពី `resolveCallerScopeContext()` ដោះស្រាយ scopes ពីព័ត៌មាន MCP auth, metadata សំណើ, ឬ `OMNIROUTE_MCP_SCOPES`។ វានៅតែបិទ លុះត្រាតែ `OMNIROUTE_MCP_ENFORCE_SCOPES=true`។

### Access-token scopes

`read` / `write` / `admin` លើ tokens `oma_live_…` ដែលត្រូវបានចាត់ថ្នាក់ដោយ `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`)។ ចំណាត់ថ្នាក់នេះអនុវត្តចំពោះ access-token credential ប៉ុណ្ណោះ។ សូមមើល [Management Authentication](../guides/MANAGEMENT-AUTH.md)។

## ប៊ូតុងបើក/បិទការត្រួតពិនិត្យ Auth

`isAuthRequired()` នៅ `src/shared/utils/apiAuth.ts` សម្រេចថាតើ auth **ណាមួយ** ត្រូវបានអនុវត្តសម្រាប់សំណើឬអត់:

- `settings.requireLogin === false` → auth ត្រូវបានបិទទូទាំងប្រព័ន្ធ លើកលែងតែ tier ដែលការពារជានិច្ច (មើល [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) និងការហៅដែលផ្ដល់ credential ដែលវាទទួលយក ដែលត្រូវការ credential ដូចគ្នាដូចពេលការចូលបើក: ការចេញ sync token, ការបង្កើត CLI access token នៃ scope ណាមួយ, និងការបង្កើត API key ដែលមាន scope `manage`/`admin`, ការផ្ដល់ scope នោះទៅ key, ឬការបង្កើតឡើងវិញ ឬការបង្ហាញ key បែបនោះ (`requireCredentialForManagementScopedKey()` នៅ `src/lib/api/requireManagementAuth.ts`)។ Key សម្រាប់ inference តែប៉ុណ្ណោះនៅតែបើក។
- មិនបានកំណត់ password **និង** មិនមាន env var `INITIAL_PASSWORD` → mode bootstrap អនុញ្ញាត onboarding wizard និងសំណើ loopback ប៉ុន្តែសំណើបណ្តាញខាងក្រៅនៅតែត្រូវការ credential។
- កំហុស DB ណាមួយ → fail closed (ការពារសុវត្ថិភាពតាមលំនាំដើម)។

ការអនុវត្ត API key របស់ client ប្រើ `isRequireApiKeyEnabled()` នៅ `src/shared/utils/featureFlags.ts` មិនមែនការអាន `process.env.REQUIRE_API_KEY` ដោយផ្ទាល់ទេ។ នេះសំខាន់សម្រាប់ instance ដែលបានដាក់ពង្រាយ: ការប្ដូរ `REQUIRE_API_KEY` ក្នុង Dashboard → Feature Flags ទុក DB override ហើយមានផលភ្លាមៗលើ `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` និងការពិនិត្យ auth client-API ផ្សេងទៀតដែលចែករំលែក helper នេះ។ ប្រសិនបើមិនអាចអាន store feature flag ទេ auth client API fail closed ហើយតម្រូវឱ្យមាន key។

## ការផ្លាស់ប្តូរដែលមិនត្រូវគ្នាជាមួយកំណែមុន — v3.8.0

endpoint `/api/v1/agents/tasks/*` និង `/api/resilience/model-cooldowns` **ឥឡូវនេះតម្រូវឱ្យមានការផ្ទៀងផ្ទាត់សម្រាប់ការគ្រប់គ្រង** (commit `588a0333`)។ Client ដែលពីមុនផ្ញើ API key ធម្មតាដោយគ្មានវិសាលភាព `manage` នឹងទទួលបាន `403`។ ការធ្វើ migration៖ ផ្តល់វិសាលភាព `manage` ដល់ key នៅក្នុង dashboard API Keys ឬប្រើ dashboard session ដែលបាន log in។

## ការផ្លាស់ប្តូរឥរិយាបថ — v3.8.2

`/api/mcp/*` (ម៉ាស៊ីនមេ MCP ពីចម្ងាយ) នៅតែជា LOCAL_ONLY តាមលំនាំដើម ប៉ុន្តែឥឡូវនេះវាទទួលយក request ដែលមិនមែនជា loopback នៅពេល header `Authorization: Bearer <api-key>` មានវិសាលភាព `manage`។ ករណីលើកលែងនេះត្រូវបានគ្រប់គ្រងយ៉ាងច្បាស់លាស់តាម path នីមួយៗតាមរយៈ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` នៅក្នុង `src/server/authz/routeGuard.ts`។ prefix LOCAL_ONLY ដែលនៅជាប់គ្នា `/api/cli-tools/runtime/*` មានចេតនា **មិន** អនុញ្ញាតឱ្យរំលងទេ ព្រោះវាអាចបង្កើត subprocess តាមអំពើចិត្ត។ Anonymous request ទៅកាន់ `/api/mcp/*` ពី non-loopback នៅតែបន្តទទួលបាន `403 LOCAL_ONLY` — លំនាំដើមសម្រាប់ path LOCAL_ONLY ថ្មីណាមួយនៅតែតម្រូវឱ្យជា loopback យ៉ាងតឹងរ៉ឹង។ សូមមើល [កម្រិត Route Guard](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)។

## ការធ្វើតេស្ត

- Unit test៖ `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`។
- Public allowlist៖ `tests/unit/public-api-routes.test.ts`។
- ដំណើរការ test ជាក់លាក់៖ `node --import tsx/esm --test tests/unit/authz/classify.test.ts`។

## ការបំបាត់កំហុស

បំពង់បង្ហូរប្រេងតែងតែបោះត្រាឆ្លើយតបជាមួយ៖

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

សម្រាប់សំណើដែលបានផ្ទៀងផ្ទាត់ ក្បាលសំណើខាងលើ (ផ្នែកខាងអ្នកដោះស្រាយ) ក៏រួមបញ្ចូលផងដែរ៖

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ប្រើ `assertAuth(req, expectedClass)` នៅខាងក្នុងឧបករណ៍ដោះស្រាយ — វាបោះ `AuthzAssertionError` ជាមួយកូដ `AUTHZ_NOT_INITIALIZED` ប្រសិនបើឧបករណ៍កណ្តាលត្រូវបានរំលង (មានប្រយោជន៍សម្រាប់ការចាប់យកការកំណត់រចនាសម្ព័ន្ធក្នុងការធ្វើតេស្ត) ។

## សូមមើលផងដែរ

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — សញ្ញាសម្គាល់ការផ្ទៀងផ្ទាត់សម្រាប់ចុងចំណុចនីមួយៗ
- [COMPLIANCE.md](../security/COMPLIANCE.md) — កំណត់ហេតុសវនកម្មសម្រាប់ព្រឹត្តិការណ៍ផ្ទៀងផ្ទាត់
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ដែនឈ្មោះវិសាលភាពបី និងកាតាឡុកវិសាលភាពឧបករណ៍ MCP
- ប្រភព: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
