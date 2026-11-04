# Authorization Guide (Oʻzbekcha)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Haqiqat manbai:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Oxirgi yangilangan sana:** 2026-09-22 — koʻlam nomfazo (scope namespaces) MCP-SERVER.md ga ishora qiladi

OmniRoute har bir API soʻrovini boshqaradigan marshrutni biluvchi avtorizatsiya quvuriga ega. Tasniflash **deterministik** va **fail-closed** (xato boʻlsa yopiladi) — tasniflanmaydigan har qanday narsa `MANAGEMENT` sifatida yakunlanadi va sessiya yoki boshqaruv darajasidagi token talab qiladi. Ushbu sahifa marshrutlarni saqlovchi yoki yangi yakuniy nuqtalarni loyihalashtiruvchi muhandislar uchun modelni tushuntiradi.

![AuthZ quvuri (3 ta marshrut sinfi + siyosatni baholash)](../diagrams/exported/authz-pipeline.svg)

> Manba: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Ikki autentifikatsiya rejimi

### 1. API kaliti (tashuvchi)

Kalit `manage` qamroviga ega bo'lsa, OpenAI/Anthropic/Gemini-compatible mijozi APIs va bir nechta boshqaruv marshrutlari uchun ishlatiladi.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` da `isValidApiKey()` / `extractApiKey()` tomonidan tasdiqlangan va `src/shared/utils/apiAuth.ts` orqali qayta eksport qilingan. Tasdiqlovchi, shuningdek, `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env varslarini doimiy o'tish kalitlari sifatida qabul qiladi ( #1350 muammosi).

### 2. Boshqaruv paneli sessiyasi (auth_token cookie fayli)

Boshqarish paneli sahifalari va boshqaruv operatsiyalari uchun.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

A cookie is a session only when the JWT verifies **and** carries `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Every consumer of the cookie (dashboard route guard (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, live server, `/api/settings/require-login`, `/api/auth/status`) goes through that helper. Other JWTs signed with `JWT_SECRET` exist — the Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` tokens for key holders — and are never sessions (#13298).

`isDashboardSessionAuthenticated()` tomonidan `src/shared/utils/apiAuth.ts` tomonidan tasdiqlangan. Quvur liniyasi 30 kunlik muddati tugashiga 7 kundan kamroq vaqt qolganda JWT ni avtomatik yangilaydi.

Seans 30 kunlik tugashidan oldin ham tugashi mumkin, chunki har bir minter `mintDashboardSessionToken` (chiqarish vaqti `iat` va identifikator `jti`) dan o'tadi va tekshiruvchi ikkita sozlamani tekshiradi: `sessionsValidAfter`, parolni o'zgartirish orqali o'rnatiladi, shuning uchun tekshirishni `POST /api/auth/logout` oldin chiqarilgan har bir seans (parolni o'zgartirgan brauzer yangi cookie-faylni oladi) va `revokedDashboardSessions`-chiqish seanslarini `jti`. Eski versiyada ishlangan seanslar hech qanday da'voga ega emas va birinchi parol o'zgartirilgunga qadar amal qiladi. Agar sozlamalarni o'qib bo'lmasa, sessiya ishonchli emas.

Ba'zi boshqaruv yo'nalishlari qabul qiladi** yoki** rejimi: API tugmasi `manage` (yoki `admin`) qamroviga ega bo‘lganda cookie OR `Bearer <key>`. Bu v3.8 da qo'shilgan " API qo'ng'iroqlari orqali sozlanishi" ish jarayonini faollashtiradi.

#### Ixtiyoriy OIDC kirish eshigi (#6973)

Boshqaruv paneliga kirish ham qo'llab-quvvatlaydi** ro'yxatdan o'tish** OIDC (OpenID Connect) oqimi standart parol bilan kirish — parolga kirish hech qachon olib tashlanmaydi, faqat to'ldiriladi:

- Agar `settings.oidcEnabled === true` bo'lmasa, o'chirilgan** va** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` hammasi sozlangan (Sozlamalar → Auth). `GET /api/auth/oidc/login` aks holda `400` qaytaradi.
- `GET /api/auth/oidc/login` emitentning `/.well-known/openid-configuration` dan `authorization_endpoint` topadi ( `<issuer>/authorize` ga qaytadi), kiruvchi so‘rovdan (`x-forwarded-proto` -aware) qayta yo‘naltiruvchi URI quradi va `httpOnly` `oidc_state` cookie faylida saqlangan tasodifiy `state` bilan IdP ga yo‘naltiradi.
- `GET /api/auth/oidc/callback` `state` tasdiqlaydi, avtorizatsiya kodini almashtiradi va ID token imzosini emitentning JWKS (`jose` `createRemoteJWKSet`, JWKS URI uchun keshlangan) orqali `issuer`/`audience` tekshiruvlari bilan tekshiradi. Boshqaruv paneliga kirish uchun boʻsh boʻlmagan `oidcAllowedSubjects` roʻyxati, `oidcAdmissionClaim` siyosati yoki ikkalasi ham talab qilinadi. Mavzular ro'yxati `sub` yoki `email` faqat `email_verified === true` bo'lganda mos keladi. Ixtiyoriy daʼvo siyosati nuqta bilan ajratilgan ID-token daʼvo yoʻlini (masalan, `realm_access.roles`) va qabul qilingan qiymatlar qatorini oladi; hal qilingan da'vo kamida bitta qabul qilingan qiymatni o'z ichiga olgan qatorlar massivi bo'lishi kerak. Ikkala siyosat ham sozlangan bo'lsa, ikkalasi ham o'tishi kerak. Missing/malformed da'volari yopilmadi va hech qanday siyosatsiz qayta qo'ng'iroq kirishni rad etadi (`not_configured`). Mavjud faqat mavzu konfiguratsiyasi o'zgarishsiz davom etadi.
- Keycloak odatda soha rollarini ID tokenlari bilan emas, balki kirish tokenlari bilan taqqoslaydi. `admin` soha rolini talab qilish uchun ushbu mijoz uchun `realm_access.roles` o‘z ichiga olgan protokol xaritasini sozlang.**ID tokeni** , keyin `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` ga o'rnating. Faqat rol uchun ruxsatni yoqishdan oldin ushbu mijoz uchun haqiqiy ID-token daʼvosini tekshiring; ilova kirish belgisi rollarini o'qimaydi. IdP tomoni tokenini rad etish ushbu ilova tomonidagi tekshiruvni toʻldirishi mumkin, lekin oʻrnini bosmaydi.
- Muvaffaqiyatga erishgandan so'ng, u muvaffaqiyatga erishadi** aynan bir xil** 30 kunlik `auth_token` JWT parolga kirish bilan bog'liq muammolar (`src/app/api/auth/login/route.ts`), shuning uchun asboblar panelidagi seansning qolgan qismi (avtomatik yangilash, cookie bayroqlari) o'zgarmaydi — OIDC faqat cookie qanday zarb qilinishini almashtiradi, u bergan narsa emas. IdP roles/groups ga kiritilgan o'zgartirishlar mavjud OmniRoute seanslarini bekor qilmaydi; chiqish, parolni aylantirish yoki seansning amal qilish muddati hali ham ularning umrini boshqaradi.
- Har bir `oidc*` sozlamasi (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) da bo‘ladi: `PATCH /api/settings` `400 PASSWORD_REQUIRED` deb javob beradi, agar tana boshqaruv parolini `currentPassword` (`401 PASSWORD_MISMATCH` bo‘lsa) sifatida olib yurmasa. `oidcDisablePasswordLogin` parolni _login_ (`POST /api/auth/login`) rad etadi, lekin saqlangan parol xeshini saqlaydi va qayta autentifikatsiya `currentPassword` unga qarshi tekshiradi.
- `corsOrigins` va `bruteForceProtection` ham `SECURITY_IMPACTING_SETTINGS_KEYS` ichida: bo'shatish yoki login himoyasini zaiflashtiradi, shuning uchun ular bir xil `currentPassword` qayta autentsiyasini oladi (Xavfsizlik yorlig'i buni so'raydi) va JSON importi ularni o'chirib qo'yadi.
- Har bir xavfsizlik siyosati kaliti — yozuvlari, har bir `oidc*` kaliti va asboblar panelidagi sessiya holati — hisoblanadi `SECURITY_IMPACTING_SETTINGS_KEYS`** faqat operator uchun** `PATCH /api/settings` bo'yicha: boshqarish-ko'lamli API kaliti yoki `oma_` kirish tokeni to'g'ri `currentPassword` yuborganda ham `403` bilan rad etiladi va rad etish `reason: OPERATOR_REQUIRED` bilan `settings.update_failed` sifatida tekshiriladi ( `src/lib/api/operatorCredential.ts` da `requireOperatorCredential()` ). Oddiy sozlamalar (mavzu, displey sozlamalari) `manage` kaliti yoki `admin` kirish tokeni uchun yozilishi mumkin. Har bir `/api/settings` mutatsiyasining (va `/api/settings/require-login` ning) o'zi ham `admin` kirish-token doirasiga muhtoj ( `src/server/authz/accessScopes.ts` dagi `ADMIN_MUTATION_EXACT_PATHS`, aniq yo'l mosligi); `GET` `read` bo‘lib qoladi va boshqa `/api/settings/*` sub-marshrutlari (proksi-serverlar, birlashtirilgan standart sozlamalar, model taxalluslari, siqish, tozalashlar…) usuldan olingan `write` qamrovini saqlaydi.
- `POST /api/settings/import-json` qayta autentifikatsiyani o'tkazib yuboradi, shuning uchun yozishdan oldin u har bir kalitni `IMPORT_STRIPPED_SETTINGS_KEYS` (xuddi shu fayl) ga tushiradi: parol va `currentPassword`, har bir `SECURITY_IMPACTING_SETTINGS_KEYS` yozuvi va asboblar panelidagi sessiya holati (`sessionsValidAfter`, `revokedDashboardSessions`). Shuning uchun eski zaxira nusxasini import qilish parol o'zgartirilgan yoki tizimdan chiqish allaqachon tugagan seansni qayta tiklay olmaydi.

#### Ixtiyoriy TOTP ikki faktorli login (#16619)

→ Xavfsizlik sozlamalaridan ro'yxatdan o'tgan; operator uni yoqmaguncha o'chiring (`src/server/auth/dashboardMfa.ts`).

- **U nimani o'z ichiga oladi:** parol bilan login (`POST /api/auth/login`, keyin `POST /api/auth/mfa/verify` kerak ) va `omniroute connect` (`POST /api/cli/connect`, faqat parol almashinuvini rad etadi va kodni `totp` sifatida oladi ).
- **U nimani qamrab olmaydi:** OIDC / SSO kirish (`/api/auth/oidc/callback`) OmniRoute TOTP ni so'ramaydi. Bu identifikator provayderining ikkinchi omiliga tayanadi, shuning uchun OIDC yoqilgan bo'lsa, IdP MFA qo'llang.
- **Qayta tiklash** (qurilma yo'qolgan, tiklash kodlari qolmagan yoki endi tekshirib bo'lmaydigan omil, masalan `STORAGE_ENCRYPTION_KEY` o'zgartirilgandan keyin):
  1. Serverni `OMNIROUTE_DISABLE_MFA=true` bilan qayta ishga tushiring.
  2. Xostning o'zida (loopback peer va loopback `Host`, masalan `http://localhost:20128`) parol bilan tizimga kiring. Ikkinchi omil faqat shu kelib chiqishi uchun o'tkazib yuboriladi; har bir boshqa kelib chiqishi hali ham kodga muhtoj.
  3. Sozlamalar → Security → Disable-da parolni kiriting va kodni bo'sh qoldiring. `POST /api/auth/mfa/disable` `code` tanani faqat o‘zgaruvchi o‘rnatilgan va so‘rov xostdan kelganda qabul qiladi; u hali ham asboblar paneli seansini va joriy parolni talab qiladi va `secondFactor: "recovery_switch"` bilan `auth.mfa.disabled` sifatida tekshiriladi.
  4. `OMNIROUTE_DISABLE_MFA` sozlamasini olib tashlang, qayta ishga tushiring va kerak bo'lsa qayta ro'yxatdan o'ting.

## Marshrut sinflari

`src/server/authz/types.ts` uchta sinfni belgilaydi; deterministik tarzda tasniflanmaydigan har qanday marshrut `MANAGEMENT` ga tushadi.

| Sinf         | Tavsif                                                                                                                                                   | Talab qilinadigan autentifikatsiya                                         |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `PUBLIC`     | Aniq xavfsiz marshrutlar — kirish, chiqish, holat, ishga tushirish, sog‘liq tekshiruvi va sozlashning dastlabki endpointlari.                            | Yo‘q                                                                       |
| `CLIENT_API` | Model xizmat endpointlari — `/api/v1/*`, `/api/v1beta/*` va taxalluslar: `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Samarali `REQUIRE_API_KEY` funksiya bayrog‘i yoqilgan bo‘lsa Bearer kaliti |
| `MANAGEMENT` | Boshqaruv paneli sahifalari, sozlamalar, provayderlar, kalitlar, ma’muriy va diagnostika endpointlari.                                                   | Boshqaruv paneli seansi YOKI `manage` doirali Bearer                       |

Ba’zi `MANAGEMENT` amallari **faqat operator** uchun: `manage` kaliti yetarli emas. Saqlangan hisob ma’lumotlarini eksport qilish (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), jonli ma’lumotlar ustiga zaxira nusxasini tiklash (`dryRun=true` bilan `POST /api/db-backups/import`, identifikator bo‘yicha tiklash `POST /api/db-backups` va `POST /api/settings/import-json`) hamda tiklash nuqtalarini yo‘q qilish (`DELETE /api/db-backups` tozalashi va `PATCH /api/db-backups`, chunki u saqlagan saqlash muddati har bir zaxiradan keyingi avtomatik tozalashni boshqaradi) boshqaruv paneli seansini, mahalliy CLI subyektini yoki kirish o‘chirilganligini talab qiladi. Sinxronizatsiya tokenini berish (`POST /api/sync/tokens`) va `admin` CLI kirish tokenini chiqarish (`POST /api/cli/tokens`) har qanday kirish rejimida boshqaruv paneli seansini yoki mahalliy CLI subyektini talab qiladi. Har qanday doirali API kalitlari va `oma_` kirish tokenlari operator hisob ma’lumotlari emas: kerak bo‘lganda ular `403` oladi. Tekshiruv `src/lib/api/operatorCredential.ts` da joylashgan (`resolveOperatorCredential()` / `requireOperatorCredential()`). Kirish sozlamalarini o‘zgartirish ham faqat operator uchun: parol mavjud bo‘lgandan keyin `POST /api/settings/require-login` (boshqaruv parolini o‘rnatish / `requireLogin` ni almashtirish) faqat shu hisob ma’lumotlarini qabul qiladi — birinchi o‘rnatish bootstrap oynasi (hali parol yo‘q bo‘lsa) o‘zgarmaydi — va boshqaruv paneli seansi parolni almashtirish uchun `currentPassword` yuborishi kerak (yo‘q yoki noto‘g‘ri bo‘lsa `403`, `settings.update_failed` sifatida auditga yoziladi). Mahalliy CLI va kirish o‘chirilgan nusxa tiklash yo‘lini saqlab qoladi va parolni unsiz ham o‘rnatishi mumkin, chunki ikkalasi ham ma’lumotlar katalogiga ega bo‘lgan xostga bog‘langan.

## Quvur liniyasi

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

Ishonchli ichki sarlavhalar ( `src/server/authz/headers.ts` da belgilangan).** kiruvchi so'rovlardan mahrum** tasniflashdan oldin — mijozlari sub'ektga taqlid qilish uchun `x-omniroute-auth-*` oldindan to'ldira olmaydi.

### Siyosiy shartnomalar

Har bir marshrut sinfida `src/server/authz/policies/` siyosati mavjud:

- **`publicPolicy`** (`policies/public.ts`) — har doim `allow({ kind: "anonymous", id: "anonymous" })` qaytaradi.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — Bearerni chiqaradi, `validateApiKey()` orqali tasdiqlaydi. Faqat samarali `REQUIRE_API_KEY` funksiyasi bayrog'i o'chirilganda anonimga tushadi. Samarali bayroq `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) orqali hal qilinadi, shuning uchun asboblar paneli funksiyasi Bayroqlar va muhit oʻzgaruvchilari `/api/v1/*`, `/api/v1beta/*` va taxalluslarni doimiy ravishda boshqaradi; hal qiluvchi nosozliklar yopilmadi. Mijoz API marshrutlari boʻyicha asboblar paneli-sessiya soʻrovlariga ruxsat beradi (jumladan, asboblar paneli modellari katalogi tomonidan ishlatiladigan `/api/v1/models`). Entra ID SSO yoqilganda, tizimli ravishda Entra tokeni (uchta base64url segmenti, `RS*` alg, `kid`) bo‘lgan Tashuvchi SSO filiali tomonidan boshqariladi.** oldin** `validateApiKey()` va uning hukmi yakuniy — bo'lib, u hech qachon API-kalit yo'liga yoki degradatsiyadan anonimga o'tishga tushmaydi, shuning uchun identifikatsiya provayderining uzilishi ochiq kirishga aylanmaydi. Statik API kalitlari ta'sir qilmaydi. [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — asboblar paneli seansini, ichki model-sinxronizatsiya so‘rovlarini qabul qiladi ( `/api/providers/[name]/(sync-models|models)` ga mos keladi) yoki `isAuthRequired()` noto‘g‘ri qiymatini qaytarsa, butunlay o‘tkazib yuboradi. Bearer tokeni mavjud boʻlsa, lekin yaroqsiz boʻlsa, 403 (`AUTH_001`) ni qaytaradi, aks holda 401. Shuningdek, marshrutni qo'riqlash sathlarini (LOCAL_ONLY / ALWAYS_PROTECTED) har qanday [autentifikatsiya](../security/ROUTE_GUARD_TIERS.md) bo'limi — qarang. `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (bugungi kunda: `/api/mcp/`) dagi LOCAL_ONLY yo'llariga Bearer kaliti `manage` skopini olib yurganida, orqaga qaytmagan holda kirish mumkin; boshqa barcha LOCAL_ONLY yo'llari qamrovdan qat'i nazar, qat'iy orqaga qaytish bo'lib qoladi.

Muvaffaqiyatli siyosat `AuthSubject` `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` bilan qaytaradi. Pastki oqim ishlovchilari autentifikatsiya mantiqini qayta ishga tushirish o'rniga `src/server/authz/assertAuth.ts` -da `assertAuth(request, "CLIENT_API")` orqali o'qishlari mumkin.

## Jamoat yo'llari ro'yxati

`src/shared/constants/publicApiRoutes.ts` - bu aniq ruxsat etilgan ro'yxat:

Ro'yxat bo'linadi** shakli** , va bo'linish yuk ko'taruvchi (GHSA-74g9-q8f6-793h): prefiks `startsWith()` bilan mos keladi, shuning uchun u o'zining bosh belgilarini baham ko'radigan har bir qo'shni yo'lga ham mos keladi. `/api/usage/om-usage` prefiks sifatida `/api/usage/om-usage<anything>` PUBLIC bilan belgilangan va Keyingi buni o‘z autentsiyasi bo‘lmagan ishlov beruvchini `/api/usage/[connectionId]` — deb hal qiladi.

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

Faqat o‘qish uchun mo‘ljallangan marshrutlar hammaga ochiq** faqat** xavfsiz usullar uchun. Eslatma: `classifyRoute()` `/api/v1/*` va `/api/v1beta/*` PUBLIC pasayish — dan chiqarib tashlaydi, ular har doim `CLIENT_API` bo‘ladi, shuning uchun “Ko‘rsatuvchi kalit” siyosati hali ham amal qiladi.

## Yangi marshrut qoʻshish

### 1-andoza — Ommaviy mijoz API endpointi (Bearer autentifikatsiyasi)

`/api/v1/` va `/api/v1beta/` ostidagi marshrutlar avtomatik ravishda `CLIENT_API` sifatida tasniflanadi. Oraliq dastur Bearer tekshiruvini majburiy qiladi; marshrut ishlov beruvchilari uni qayta bajarishi shart emas, ammo zarur boʻlsa subyektni oʻqishi mumkin.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... ishlov beruvchi mantiqi
}
```

### 2-andoza — Boshqaruv endpointi (sessiya yoki Bearer + manage)

`src/lib/api/requireManagementAuth.ts` ichidagi `requireManagementAuth()` dan foydalaning:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... ishlov beruvchi mantiqi
}
```

`requireManagementAuth()` muvaffaqiyatli boʻlsa `null`, aks holda JSON xatosi boʻlgan `Response` qaytaradi:

- 401 `AUTH_001` "Autentifikatsiya talab qilinadi" — umuman hisob maʼlumotlari yoʻq
- 403 — Bearer yaroqsiz **yoki** Bearer mavjud, ammo kalitda `manage` / `admin` doirasi yoʻq

`hasManageScope(scopes)` `"manage"` yoki `"admin"` uchun true qaytaradi.

### 3-andoza — Ommaviy ruxsat etilganlar roʻyxatiga qoʻshish

Toʻplamni qulaylikka qarab emas, shakliga qarab tanlang. Bitta marshrut `PUBLIC_API_ROUTES_EXACT` ga (yoki faqat GET uchun `PUBLIC_READONLY_CORS_API_ROUTES` ga) qoʻshiladi; faqat haqiqiy quyi daraxt `PUBLIC_API_ROUTE_PREFIXES` ga qoʻshiladi va u **`/` bilan tugashi shart**. Bitta marshrutni prefikslar roʻyxatiga kiritish uning boshlangʻich belgilariga ega barcha yondosh yoʻllarni, jumladan keyinchalik qoʻshilgan dinamik segmentli qardosh yoʻllarni ham ommaviy qiladi (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` va `tests/unit/authz/classify.test.ts` fayllaridagi birlik testlarini yangilang.

## Doiralar

Uchta nom maydoni. Har bir tekshiruvchi faqat o'zining satrlarini o'qiydi. Yonma-yon taqqoslash, jumladan, nima uchun `manage` `read:compression` uchun `scopeMatches`ni bajara olmasligi va nima uchun `read` kirish tokeni `PATCH /api/keys/{id}`ni bajara olmasligi [Uchta nom maydoni](../frameworks/MCP-SERVER.md#three-scope-namespaces)da keltirilgan.

API kalitlari `scopes` massivini o'z ichiga oladi (`api_keys.scopes`da JSON sifatida saqlanadi, qarang `src/lib/db/apiKeys.ts`).

### Boshqaruv doirasi

- `manage` / `admin` — `hasManageScope`. Boshqaruv API marshrutlariga tashuvchi orqali kirish.
- `mcp:connect`, `self:usage`, `self:account-quota` va `policy:bypass-provider-quota` qo'shimcha aniq mos keladigan doiralardir. Ular `MANAGEMENT_API_KEY_SCOPES`dan tashqarida joylashgan. `mcp:connect` faqat `/api/mcp/` non-loopback ajratmasini ochadi.

### MCP asbob doiralari

Katalog va mos kelish qoidalari (bir xil satr yoki `*` bilan tugaydigan berilgan doira): [MCP asbob doiralari](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `src/shared/constants/mcpScopes.ts`dagi `MCP_SCOPE_LIST` to'liq katalog emas, balki asl terilgan kichik to'plamdir. Ijro etish `open-sse/mcp-server/scopeEnforcement.ts`da `resolveCallerScopeContext()` MCP autentifikatsiya ma'lumotlari, so'rov metama'lumotlari yoki `OMNIROUTE_MCP_SCOPES`dan doiralarni hal qilgandan so'ng amalga oshiriladi. U `OMNIROUTE_MCP_ENFORCE_SCOPES=true` bo'lmaguncha o'chirilgan holatda qoladi.

### Kirish tokeni doiralari

`oma_live_…` tokenlarida `read` / `write` / `admin`, `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`) bo'yicha tartiblangan. Bu daraja faqat kirish tokeni hisob ma'lumotlariga tegishli. Qarang [Boshqaruv autentifikatsiyasi](../guides/MANAGEMENT-AUTH.md).

## Autentifikatsiya talab qilinadigan kalit

`src/shared/utils/apiAuth.ts` dagi `isAuthRequired()` so‘rov uchun **istalgan** autentifikatsiya qo‘llanilishini aniqlaydi:

- `settings.requireLogin === false` → autentifikatsiya global o‘chirilgan, lekin doimo himoyalangan qatlam ([Marshrut himoyasi qatlamlari](../security/ROUTE_GUARD_TIERS.md)) va qabul qilinadigan hisob ma’lumotini beruvchi chaqiruvlar bundan mustasno. Ular kirish yoqilgan holatdagi bilan bir xil hisob ma’lumotini talab qiladi: sinxronizatsiya tokenlarini berish, istalgan doirada CLI kirish tokenlarini chiqarish va `manage`/`admin` doirali API kaliti yaratish, shu doirani kalitga berish yoki bunday kalitni qayta yaratish/ko‘rsatish (`src/lib/api/requireManagementAuth.ts` dagi `requireCredentialForManagementScopedKey()`). Inference uchun kalitlar ochiq qoladi.
- Boshqaruv paroli yo‘q **va** `INITIAL_PASSWORD` muhit o‘zgaruvchisi yo‘q → bootstrap rejimi: sozlash ustasi va loopback so‘rovlariga ruxsat beriladi, lekin tashqi tarmoq so‘rovlariga hali ham hisob ma’lumoti kerak.
- Istalgan ma’lumotlar bazasi xatosi → yopiq holatda muvaffaqiyatsiz tugaydi (xavfsiz standart).

Mijoz API kalitini majburlash `process.env.REQUIRE_API_KEY` ni to‘g‘ridan-to‘g‘ri o‘qish o‘rniga `src/shared/utils/featureFlags.ts` dagi `isRequireApiKeyEnabled()` dan foydalanadi. Bu joylashtirilgan nusxalar uchun muhim: Boshqaruv paneli → Funksiya bayroqlarida `REQUIRE_API_KEY` ni almashtirish DB ustidan bekor qilishni saqlaydi va `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` hamda shu yordamchidan foydalanadigan boshqa mijoz API autentifikatsiya tekshiruvlariga darhol ta’sir qiladi. Agar funksiya bayrog‘i ombori o‘qib bo‘lmasa, mijoz API autentifikatsiyasi yopiq holatda muvaffaqiyatsiz tugaydi va kalit talab qiladi.

## Moslikni buzuvchi oʻzgarish — v3.8.0

`/api/v1/agents/tasks/*` va `/api/resilience/model-cooldowns` endpointlari **endi boshqaruv autentifikatsiyasini talab qiladi** (`588a0333` kommiti). Avval `manage` qamrovisiz oddiy API kalitini yuborgan mijozlar `403` javobini oladi. Migratsiya: API Keys boshqaruv panelida kalitga `manage` qamrovini bering yoki tizimga kirilgan boshqaruv paneli seansidan foydalaning.

## Xatti-harakat oʻzgarishi — v3.8.2

`/api/mcp/*` (masofaviy MCP serveri) hali ham standart holatda LOCAL_ONLY, ammo `Authorization: Bearer <api-key>` sarlavhasida `manage` qamrovi mavjud boʻlsa, endi loopback boʻlmagan soʻrovlarni ham qabul qiladi. Ushbu istisno `src/server/authz/routeGuard.ts` ichidagi `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` orqali har bir yoʻl uchun alohida boshqariladi; yonma-yon joylashgan `/api/cli-tools/runtime/*` LOCAL_ONLY prefiksini ataylab chetlab oʻtib boʻlmaydi, chunki u ixtiyoriy quyi jarayonlarni ishga tushirishi mumkin. Loopback boʻlmagan manzildan `/api/mcp/*` ga yuborilgan anonim soʻrovlar `403 LOCAL_ONLY` javobini qaytarishda davom etadi — har qanday yangi LOCAL_ONLY yoʻli uchun standart holat qatʼiy loopback boʻlib qoladi. [Yoʻnalish himoyachisi darajalari](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) boʻlimiga qarang.

## Sinov

- Birlik sinovlari: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Ommaviy ruxsat berilganlar roʻyxati: `tests/unit/public-api-routes.test.ts`.
- Yoʻnaltirilgan ishga tushirish: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Nosozliklarni tuzatish

Quvur liniyasi har doim javoblarni quyidagicha belgilaydi:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Autentifikatsiya qilingan so'rovlar uchun yuqoridagi (ishlovchi tomoni) so'rov sarlavhalari quyidagilarni o'z ichiga oladi:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Ishlovchilar ichida `assertAuth(req, expectedClass)` foydalaning — agar o'rta dastur chetlab o'tilgan bo'lsa, `AUTHZ_NOT_INITIALIZED` kodi bilan `AuthzAssertionError` chiqaradi (testlarda konfiguratsiya regressiyalarini aniqlash uchun foydali).

## Yana qarang

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — har bir yakuniy nuqta uchun avtorizatsiya belgisi
- [COMPLIANCE.md](../security/COMPLIANCE.md) — avtorizatsiya hodisalari uchun audit jurnali
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — uchta qamrov nomfazo va MCP asbob-qamrov katalogi
- Manba: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
