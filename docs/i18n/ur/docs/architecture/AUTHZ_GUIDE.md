# Authorization Guide (اردو)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **معلومات کا ماخذ:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **آخری بار اپ ڈیٹ کیا گیا:** 2026-09-22 — اسکوپ نیم اسپیسز MCP-SERVER.md کی طرف اشارہ کرتے ہیں

OmniRoute کے پاس ایک روٹ-آگاہ اجازت پائپ لائن ہے جو ہر API درخواست کو روکتی ہے۔ درجہ بندی **مقرر** اور **فیل-کلوزڈ** ہے — کوئی بھی چیز جس کی درجہ بندی نہیں کی جا سکتی وہ `MANAGEMENT` کے طور پر ختم ہوتی ہے اور ایک سیشن یا مینجمنٹ-گریڈ ٹوکن کا مطالبہ کرتی ہے۔ یہ صفحہ ان انجینئرز کے لیے ماڈل کی وضاحت کرتا ہے جو روٹس کو برقرار رکھتے ہیں یا نئے اینڈ پوائنٹس ڈیزائن کرتے ہیں۔

![AuthZ پائپ لائن (3 روٹ کلاسز + پالیسی کی تشخیص)](../diagrams/exported/authz-pipeline.svg)

> ماخذ: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## دو آتھ موڈز

### 1. API کلید (بردار)

OpenAI/Anthropic/Gemini-compatible کلائنٹ APIs اور کچھ انتظامی راستوں کے لیے استعمال کیا جاتا ہے جب کلید میں `manage` گنجائش ہو۔

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` میں `isValidApiKey()` / `extractApiKey()` کے ذریعے تصدیق شدہ اور `src/shared/utils/apiAuth.ts` کے ذریعے دوبارہ برآمد کیا گیا۔ توثیق کنندہ `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars کو بھی مستقل پاس تھرو کیز (مسئلہ #1350) کے طور پر قبول کرتا ہے۔

### 2. ڈیش بورڈ سیشن (auth_token کوکی)

ڈیش بورڈ پیجز اور ایڈمن آپریشنز کے لیے۔

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

کوکی صرف اس وقت سیشن ہے جب JWT تصدیق کرتا ہے۔** اور** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) لے جاتا ہے۔ کوکی (ڈیش بورڈ روٹ گارڈ (`isDashboardSessionAuthenticated()`)، authz پائپ لائن ریفریش، WebSocket ہینڈ شیک، لائیو سرور، `/api/settings/require-login`، `/api/auth/status`) کا ہر صارف اس مددگار سے گزرتا ہے۔ `JWT_SECRET` کے ساتھ دستخط شدہ دیگر JWTs موجود ہیں — the Cursor CLI پاس تھرو mints — ہولڈرز کے لیے `iss "omniroute" / aud "cursor-cli"` ٹوکن ہیں اور یہ کبھی بھی سیشن نہیں ہوتے (#13298)۔

`src/shared/utils/apiAuth.ts` میں `isDashboardSessionAuthenticated()` کے ذریعے تصدیق شدہ۔ جب اس کی 30 دن کی زندگی میں 7 دن سے کم باقی رہ جائے تو پائپ لائن JWT کو خود بخود تازہ کر دیتی ہے۔

ایک سیشن اس کے 30 دن ختم ہونے سے پہلے بھی ختم ہو سکتا ہے، کیونکہ ہر منٹر `mintDashboardSessionToken` (مسئلہ کا وقت `iat` اور ایک id `jti`) سے گزرتا ہے اور تصدیق کنندہ دو سیٹنگز چیک کرتا ہے: `sessionsValidAfter`، پاس ورڈ کی تبدیلی کے ذریعے سیٹ کیا جاتا ہے اس لیے ہر سیشن کی تصدیق بند ہونے سے پہلے جاری کیا جاتا ہے (پاس ورڈ کو تبدیل کرنے والے `POST /api/auth/logout` ایک تازہ کوکی ملتی ہے)، اور `revokedDashboardSessions`' سیشن کو سائن آؤٹ کرنے کے لیے۔ `jti` پرانی ریلیز کے ذریعے بنائے گئے سیشنز میں کوئی بھی دعوی نہیں ہوتا ہے اور پہلے پاس ورڈ کی تبدیلی تک درست رہتے ہیں۔ اگر ترتیبات کو نہیں پڑھا جا سکتا ہے، تو سیشن پر بھروسہ نہیں کیا جاتا ہے۔

کچھ انتظامی راستے قبول کرتے ہیں۔** یا تو** موڈ: کوکی OR `Bearer <key>` جب API کلید میں `manage` (یا `admin`) گنجائش ہو۔ یہ وہی ہے جو v3.8 میں شامل " API کالز کے ذریعے قابل ترتیب" ورک فلو کو قابل بناتا ہے۔

#### اختیاری OIDC لاگ ان گیٹ (#6973)

ڈیش بورڈ ایڈمن لاگ ان بھی سپورٹ کرتا ہے۔** آپٹ ان** OIDC (OpenID Connect) پہلے سے طے شدہ پاس ورڈ لاگ ان کے ساتھ بہاؤ — پاس ورڈ لاگ ان کبھی نہیں ہٹایا جاتا ہے، صرف ضمیمہ ہوتا ہے:

- غیر فعال ہے جب تک کہ `settings.oidcEnabled === true` نہ ہو۔** اور** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` سبھی کنفیگرڈ ہیں (ترتیبات → Auth)۔ `GET /api/auth/oidc/login` دوسری صورت میں `400` لوٹاتا ہے۔
- `GET /api/auth/oidc/login` جاری کنندہ کے `/.well-known/openid-configuration` سے `authorization_endpoint` دریافت کرتا ہے (واپس `<issuer>/authorize` پر آتا ہے)، آنے والی درخواست (`x-forwarded-proto` -aware) سے ری ڈائریکٹ URI بناتا ہے، اور `httpOnly` `oidc_state` کوکی میں ذخیرہ شدہ بے ترتیب `state` کے ساتھ IdP کو ری ڈائریکٹ کرتا ہے۔
- `GET /api/auth/oidc/callback` `state` کی توثیق کرتا ہے، اجازت کے کوڈ کا تبادلہ کرتا ہے، اور `issuer`/`audience` چیک کے ساتھ جاری کنندہ کے JWKS (`jose`'s `createRemoteJWKSet`، کیشڈ فی JWKS URI) کے ذریعے ID ٹوکن کے دستخط کی تصدیق کرتا ہے۔ ڈیش بورڈ میں داخلے کے لیے `oidcAllowedSubjects` فہرست، ایک `oidcAdmissionClaim` پالیسی، یا دونوں کی ضرورت ہوتی ہے۔ موضوع کی فہرست صرف `sub` یا `email` سے ملتی ہے جب `email_verified === true`۔ اختیاری دعوے کی پالیسی ڈاٹ سے الگ کردہ ID ٹوکن کلیم پاتھ (مثال کے طور پر `realm_access.roles`) اور قبول شدہ اقدار کی ایک صف لیتی ہے۔ حل شدہ دعوی کم از کم ایک قبول شدہ قدر پر مشتمل تاروں کی ایک صف ہونی چاہیے۔ اگر دونوں پالیسیاں ترتیب دی گئی ہیں، تو دونوں کو پاس ہونا چاہیے۔ Missing/malformed کے دعوے ناکام ہو جاتے ہیں، اور بغیر کسی پالیسی کے کال بیک لاگ ان (`not_configured`) سے انکار کر دیتا ہے۔ صرف موضوع کی موجودہ کنفیگریشنز بغیر تبدیلی کے جاری ہیں۔
- کی کلوک عام طور پر دائرے کے کرداروں کو رسائی ٹوکن میں نقشہ بناتا ہے، ضروری نہیں کہ ID ٹوکنز ہوں۔ ریئل رول `admin` کی ضرورت کے لیے، اس کلائنٹ کے لیے ایک پروٹوکول میپر تشکیل دیں جس میں اس میں `realm_access.roles` شامل ہو**ID ٹوکن** ، پھر `oidcAdmissionClaim` کو `{ "path": "realm_access.roles", "values": ["admin"] }` پر سیٹ کریں۔ صرف رول داخلہ کو فعال کرنے سے پہلے اس کلائنٹ کے لیے اصل ID ٹوکن کا دعویٰ چیک کریں۔ ایپلیکیشن رسائی ٹوکن رولز کو نہیں پڑھتی ہے۔ آئی ڈی پی سائیڈ ٹوکن سے انکار ضمیمہ کر سکتا ہے لیکن اس ایپلیکیشن سائیڈ چیک کو تبدیل نہیں کرتا ہے۔
- کامیابی پر یہ mints the** بالکل اسی طرح** 30-day `auth_token` JWT پاس ورڈ لاگ ان کے مسائل (`src/app/api/auth/login/route.ts`)، لہذا ڈیش بورڈ سیشن کا بقیہ پائپ لائن (آٹو ریفریش، کوکی فلیگ) غیر تبدیل شدہ ہے — OIDC صرف اس بات کی جگہ لیتا ہے کہ کوکی کو کیسے مائنٹ کیا جاتا ہے، نہ کہ یہ کیا دیتا ہے۔ IdP roles/groups میں تبدیلیاں موجودہ OmniRoute سیشنز کو باطل نہیں کرتی ہیں۔ لاگ آؤٹ، پاس ورڈ گھومنا، یا سیشن کی میعاد ختم ہونے پر اب بھی ان کی زندگی کا انتظام ہے۔
- ہر `oidc*` ترتیب (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) میں ہے : `PATCH /api/settings` جواب دیتا ہے `400 PASSWORD_REQUIRED` جب تک کہ باڈی انتظامی پاس ورڈ کو اپنے ساتھ نہ لے ( `currentPassword` کے طور `401 PASSWORD_MISMATCH` غلط ہونے پر )۔ `oidcDisablePasswordLogin` پاس ورڈ _login_ (`POST /api/auth/login`) سے انکار کرتا ہے لیکن ذخیرہ شدہ پاس ورڈ ہیش رکھتا ہے، اور دوبارہ auth پھر بھی اس کے خلاف `currentPassword` چیک کرتا ہے۔
- `corsOrigins` اور `bruteForceProtection` بھی `SECURITY_IMPACTING_SETTINGS_KEYS` میں ہیں: ڈھیلا کرنا یا تو لاگ ان کے دفاع کو کمزور کر دیتا ہے، لہذا وہ وہی `currentPassword` دوبارہ تصنیف کرتے ہیں (سیکیورٹی ٹیب اس کے لیے پوچھتا ہے) اور JSON درآمد انہیں چھوڑ دیتا ہے۔
- ہر سیکیورٹی پالیسی کلید — the `SECURITY_IMPACTING_SETTINGS_KEYS` اندراجات، ہر `oidc*` کلید اور ڈیش بورڈ سیشن کی حالت — ہے** صرف آپریٹر** `PATCH /api/settings` پر: مینیج کے دائرہ کار والی API کلید یا `oma_` رسائی ٹوکن کو `403` کے ساتھ رد کر دیا جاتا ہے یہاں تک کہ جب یہ صحیح `currentPassword` بھیجتا ہے، اور انکار کا آڈٹ `reason: OPERATOR_REQUIRED` کے ساتھ `settings.update_failed` کے طور پر کیا جاتا ہے ( `src/lib/api/operatorCredential.ts` میں `requireOperatorCredential()` )۔ عام ترتیبات (تھیم، ڈسپلے کی ترجیحات) `manage` کلید یا `admin` رسائی ٹوکن کے لیے قابل تحریر رہتی ہیں۔ خود `/api/settings` کے ہر اتپریورتن (اور `/api/settings/require-login` کے) کو بھی `admin` رسائی ٹوکن اسکوپ (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`، exact-path match) کی ضرورت ہوتی ہے۔ `GET` `read` رہتا ہے، اور دیگر `/api/settings/*` ذیلی راستے (پراکسیز، کومبو ڈیفالٹس، ماڈل عرفی نام، کمپریشن، پرجز…) طریقہ سے قیاس شدہ `write` دائرہ کار کو برقرار رکھتے ہیں۔
- `POST /api/settings/import-json` اس دوبارہ تصنیف کو چھوڑ دیتا ہے، لہذا یہ لکھنے سے پہلے `IMPORT_STRIPPED_SETTINGS_KEYS` (ایک ہی فائل) میں ہر کلید کو چھوڑ دیتا ہے: پاس ورڈ اور `currentPassword`، ہر `SECURITY_IMPACTING_SETTINGS_KEYS` اندراج، اور ڈیش بورڈ سیشن کی حالت (`sessionsValidAfter`، `revokedDashboardSessions`)۔ اس لیے پرانے بیک اپ کو درآمد کرنا اس سیشن کو بحال نہیں کر سکتا جس میں پاس ورڈ کی تبدیلی یا سائن آؤٹ پہلے ہی ختم ہو چکا ہو۔

#### اختیاری TOTP ٹو فیکٹر لاگ ان (#16619)

سیٹنگز → سیکیورٹی سے اندراج؛ جب تک آپریٹر اسے آن نہیں کرتا (`src/server/auth/dashboardMfa.ts`)

- **یہ کیا احاطہ کرتا ہے:** پاس ورڈ لاگ ان (`POST /api/auth/login`، جس کے بعد `POST /api/auth/mfa/verify` کی ضرورت ہوتی ہے ) اور `omniroute connect` (`POST /api/cli/connect`، جو صرف پاس ورڈ کے تبادلے سے انکار کرتا ہے اور کوڈ کو `totp` کے طور پر لیتا ہے)۔
- **یہ کیا احاطہ نہیں کرتا:** OIDC / SSO سائن ان (`/api/auth/oidc/callback`) OmniRoute TOTP کے لئے نہیں پوچھتا ہے۔ یہ شناخت فراہم کرنے والے کے اپنے دوسرے عنصر پر انحصار کرتا ہے، لہذا اگر OIDC فعال ہو تو IdP میں MFA نافذ کریں۔
- **بازیابی۔** (گمشدہ ڈیوائس، کوئی ریکوری کوڈ نہیں بچا، یا کوئی ایسا عنصر جس کی مزید تصدیق نہیں ہو سکتی، مثال کے طور پر `STORAGE_ENCRYPTION_KEY` تبدیل ہونے کے بعد):
  1. `OMNIROUTE_DISABLE_MFA=true` کے ساتھ سرور کو دوبارہ شروع کریں۔
  2. میزبان پر ہی (loopback peer اور loopback `Host`، جیسے `http://localhost:20128`)، پاس ورڈ کے ساتھ سائن ان کریں۔ دوسرا عنصر صرف اس اصل کے لیے چھوڑ دیا گیا ہے۔ ہر دوسری اصل کو اب بھی کوڈ کی ضرورت ہے۔
  3. سیٹنگز → Security → ڈس ایبل میں، پاس ورڈ درج کریں اور کوڈ کو خالی چھوڑ دیں۔ `POST /api/auth/mfa/disable` صرف `code` کے بغیر کسی باڈی کو قبول کرتا ہے جب متغیر سیٹ ہو اور درخواست میزبان کی طرف سے آتی ہو۔ اسے اب بھی ڈیش بورڈ سیشن اور موجودہ پاس ورڈ کی ضرورت ہے، اور `secondFactor: "recovery_switch"` کے ساتھ `auth.mfa.disabled` بطور آڈٹ کیا جاتا ہے۔
  4. `OMNIROUTE_DISABLE_MFA` غیر سیٹ کریں، دوبارہ شروع کریں، اور اگر ضرورت ہو تو دوبارہ اندراج کریں۔

## راستوں کی اقسام

`src/server/authz/types.ts` تین اقسام متعین کرتا ہے؛ جو راستہ قطعی طور پر درجہ بند نہ ہو سکے وہ `MANAGEMENT` پر واپس آ جاتا ہے۔

| قسم          | تفصیل                                                                                                                                            | احراز ہویت درکار ہے                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| `PUBLIC`     | واضح طور پر محفوظ راستے — login، logout، status، init، health، onboarding bootstrap۔                                                             | کوئی نہیں                                                  |
| `CLIENT_API` | ماڈل سروِنگ اینڈ پوائنٹس — `/api/v1/*`، `/api/v1beta/*`، اور عرف `/v1/*`، `/v1beta/*`، `/chat/completions`، `/responses`، `/models`، `/codex/*`۔ | جب مؤثر `REQUIRE_API_KEY` فیچر فلیگ فعال ہو تو Bearer کلید |
| `MANAGEMENT` | ڈیش بورڈ صفحات، ترتیبات، فراہم کنندگان، کلیدیں، ایڈمن اور تشخیصی اینڈ پوائنٹس۔                                                                   | ڈیش بورڈ سیشن یا `manage` اسکوپ کے ساتھ Bearer             |

چند `MANAGEMENT` اقدامات **صرف آپریٹر کے لیے** ہیں: صرف `manage` کلید کافی نہیں۔ محفوظ شدہ اسناد ایکسپورٹ کرنا (`GET /api/settings/export-json`، `GET /api/db-backups/export`، `GET /api/db-backups/exportAll`)، لائیو ڈیٹا پر بیک اپ بحال کرنا (`dryRun=true` سمیت `POST /api/db-backups/import`، ID کے ذریعے بحالی `POST /api/db-backups`، `POST /api/settings/import-json`) اور بحالی کے نقطے ختم کرنا (`DELETE /api/db-backups` کی صفائی، اور `PATCH /api/db-backups` کیونکہ یہ برقرار رکھنے کی پالیسی محفوظ کرتا ہے جو ہر بیک اپ کے بعد خودکار صفائی چلاتی ہے) کے لیے ڈیش بورڈ سیشن، مقامی CLI کا subject، یا لاگ ان کا بند ہونا درکار ہے۔ sync ٹوکن جاری کرنا (`POST /api/sync/tokens`) اور `admin` اسکوپ کا CLI رسائی ٹوکن بنانا (`POST /api/cli/tokens`) ہر لاگ ان موڈ میں ڈیش بورڈ سیشن یا مقامی CLI کا subject مانگتے ہیں۔ کسی بھی اسکوپ کی API کلیدیں اور `oma_` رسائی ٹوکن آپریٹر اسناد نہیں ہیں: جب بھی کوئی ایسی اسناد درکار ہو، انہیں `403` ملتا ہے۔ اس کی جانچ `src/lib/api/operatorCredential.ts` میں ہے (`resolveOperatorCredential()` / `requireOperatorCredential()`)۔ لاگ ان ترتیبات کی تبدیلی بھی صرف آپریٹر کے لیے ہے: `POST /api/settings/require-login` (مینجمنٹ پاس ورڈ سیٹ کرنا / `requireLogin` ٹوگل کرنا) ایک بار پاس ورڈ موجود ہونے کے بعد صرف انہی اسناد کو قبول کرتا ہے — پہلی بار کی بوٹ اسٹریپ ونڈو (جب ابھی پاس ورڈ نہ ہو) میں کوئی تبدیلی نہیں — اور ڈیش بورڈ سیشن کو پاس ورڈ بدلنے کے لیے `currentPassword` بھیجنا ہوگا (غائب یا غلط ہونے پر `403`، `settings.update_failed` کے طور پر آڈٹ ہوتا ہے)۔ مقامی CLI اور وہ انسٹنس جس کا لاگ ان بند ہو بحالی کا راستہ برقرار رکھتے ہیں اور اس کے بغیر پاس ورڈ سیٹ کر سکتے ہیں، کیونکہ دونوں اُس میزبان سے جڑے ہیں جو ڈیٹا ڈائریکٹری کا مالک ہے۔

## پائپ لائن

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

قابل اعتماد اندرونی ہیڈر ( `src/server/authz/headers.ts` میں بیان کردہ) ہیں۔** آنے والی درخواستوں سے چھین لیا گیا۔** درجہ بندی سے پہلے — کلائنٹ کسی موضوع کی نقالی کرنے کے لیے `x-omniroute-auth-*` پہلے سے آباد نہیں کر سکتے۔

### پالیسی معاہدے

ہر روٹ کلاس کی `src/server/authz/policies/` میں ایک پالیسی ہوتی ہے:

- **`publicPolicy`** (`policies/public.ts`) — ہمیشہ `allow({ kind: "anonymous", id: "anonymous" })` لوٹاتا ہے۔
- **`clientApiPolicy`** (`policies/clientApi.ts`) — بیئرر کو نکالتا ہے، `validateApiKey()` کے ذریعے توثیق کرتا ہے۔ گمنام میں صرف اس وقت آتا ہے جب مؤثر `REQUIRE_API_KEY` خصوصیت کا جھنڈا غیر فعال ہو۔ مؤثر پرچم کو `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) کے ذریعے حل کیا جاتا ہے لہذا ڈیش بورڈ فیچر فلیگ اور ماحولیاتی متغیرات `/api/v1/*`، `/api/v1beta/*`، اور عرفی ناموں کو مستقل طور پر کنٹرول کرتے ہیں۔ حل کرنے والی ناکامیاں بند ہوگئیں. کلائنٹ API روٹس پر ڈیش بورڈ سیشن کی درخواستوں کی اجازت دیتا ہے (بشمول `/api/v1/models`، ڈیش بورڈ ماڈل کیٹلاگ کے ذریعے استعمال کیا جاتا ہے)۔ جب Entra ID SSO فعال کیا جاتا ہے، ایک بیئرر جو ساختی طور پر ایک Entra ٹوکن ہے (تین base64url سیگمنٹ، `RS*` alg، `kid`) SSO برانچ کے ذریعے ہینڈل کیا جاتا ہے۔** پہلے** `validateApiKey()` اور اس کا فیصلہ حتمی — ہے یہ کبھی بھی API-key پاتھ یا degrade-to-unonymous برانچ میں نہیں آتا، لہذا شناخت فراہم کرنے والے کی بندش کھلی رسائی نہیں بن سکتی۔ جامد API کیز غیر متاثر ہیں۔ [Entra ID SSO](../security/ENTRA_SSO.md) دیکھیں۔
- **`managementPolicy`** (`policies/management.ts`) — ڈیش بورڈ سیشن، اندرونی ماڈل کی مطابقت پذیری کی درخواستوں کو قبول کرتا ہے ( `/api/providers/[name]/(sync-models|models)` کے خلاف مماثل ہے)، یا اگر `isAuthRequired()` غلط لوٹتا ہے تو مکمل طور پر چھوڑ دیتا ہے۔ 403 (`AUTH_001`) واپس کرتا ہے جب بیئرر ٹوکن موجود ہو لیکن غلط ہو، ورنہ 401۔ روٹ گارڈ ٹائرز (LOCAL_ONLY / ALWAYS_PROTECTED) کو بھی نافذ کرتا ہے اس سے پہلے کہ کسی بھی auth برانچ — [روٹ گارڈ ٹائرز](../security/ROUTE_GUARD_TIERS.md) دیکھیں۔ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` میں LOCAL_ONLY پاتھز (آج: `/api/mcp/`) تک نان لوپ بیک سے اس وقت رسائی حاصل کی جا سکتی ہے جب بیئرر کلید `manage` اسکوپ کو لے جاتی ہے۔ دیگر تمام LOCAL_ONLY راستے دائرہ کار سے قطع نظر سخت-لوپ بیک رہتے ہیں۔

ایک کامیاب پالیسی `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` کے ساتھ `AuthSubject` واپس کرتی ہے۔ ڈاؤن اسٹریم ہینڈلرز اسے `src/server/authz/assertAuth.ts` میں `assertAuth(request, "CLIENT_API")` کے ذریعے auth logic کو دوبارہ چلانے کے بجائے پڑھ سکتے ہیں۔

## عوامی راستوں کی فہرست

`src/shared/constants/publicApiRoutes.ts` واضح اجازت دی گئی فہرست ہے:

فہرست کی طرف سے تقسیم کیا جاتا ہے** شکل** ، اور تقسیم بوجھ برداشت کرنے والی ہے (GHSA-74g9-q8f6-793h): ایک سابقہ `startsWith()` کے ساتھ مماثل ہے، لہذا یہ ہر ملحقہ راستے سے بھی میل کھاتا ہے جو اس کے اہم کرداروں کا اشتراک کرتا ہے۔ `/api/usage/om-usage` بطور سابقہ نشان زد `/api/usage/om-usage<anything>` PUBLIC، اور اگلا حل کرتا ہے کہ `/api/usage/[connectionId]` — ہینڈلر کو اس کی اپنی کوئی سند نہیں ہے۔

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

صرف پڑھنے کے راستے عوامی ہیں۔** صرف** محفوظ طریقوں کے لیے۔ نوٹ: `classifyRoute()` `/api/v1/*` اور `/api/v1beta/*` PUBLIC فال تھرو — سے خارج کرتا ہے وہ ہمیشہ `CLIENT_API` ہوتے ہیں لہذا Bearer-key پالیسی اب بھی لاگو ہوتی ہے۔

## نیا Route شامل کرنا

### طریقہ 1 — عوامی client API endpoint (Bearer-auth)

`/api/v1/` اور `/api/v1beta/` کے تحت routes خودکار طور پر `CLIENT_API` کے طور پر classify ہوتے ہیں۔ middleware، Bearer check نافذ کرتا ہے؛ route handlers کو اسے دوبارہ انجام دینے کی ضرورت نہیں، لیکن مفید ہونے کی صورت میں وہ subject پڑھ سکتے ہیں۔

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handler کی منطق
}
```

### طریقہ 2 — Management endpoint (session یا Bearer + manage)

`src/lib/api/requireManagementAuth.ts` سے `requireManagementAuth()` استعمال کریں:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handler کی منطق
}
```

کامیابی پر `requireManagementAuth()`، `null` واپس کرتا ہے، بصورت دیگر JSON error `Response`:

- 401 `AUTH_001` "توثیق درکار ہے" — کوئی credentials موجود نہیں
- 403 — غلط Bearer **یا** Bearer موجود ہے لیکن key کے پاس `manage` / `admin` scope نہیں

`hasManageScope(scopes)`، `"manage"` یا `"admin"` کے لیے true واپس کرتا ہے۔

### طریقہ 3 — عوامی اجازت فہرست میں شامل کرنا

set کا انتخاب سہولت کے بجائے ساخت کے لحاظ سے کریں۔ ایک route کو `PUBLIC_API_ROUTES_EXACT` میں رکھا جاتا ہے (یا صرف GET کے لیے `PUBLIC_READONLY_CORS_API_ROUTES` میں)؛ صرف حقیقی subtree کو `PUBLIC_API_ROUTE_PREFIXES` میں رکھا جاتا ہے، اور اس کا اختتام **لازماً `/` پر ہونا چاہیے**۔ prefix فہرست میں ایک منفرد route رکھنے سے ہر وہ متصل path بھی عوامی ہو جاتا ہے جس کے ابتدائی حروف یکساں ہوں — بشمول بعد میں شامل کیے جانے والے dynamic-segment siblings (GHSA-74g9-q8f6-793h)۔ `tests/unit/public-api-routes.test.ts`، `tests/unit/authz/public-route-exact-match.test.ts` اور `tests/unit/authz/classify.test.ts` میں unit tests اپ ڈیٹ کریں۔

## سکوپس

تین نام اسپیسز۔ ہر چیکر صرف اپنی سٹرنگز پڑھتا ہے۔ ساتھ ساتھ موازنہ، بشمول یہ کہ `manage` `read:compression` کے لیے `scopeMatches` میں کیوں ناکام ہوتا ہے اور ایک `read` ایکسیس ٹوکن `PATCH /api/keys/{id}` کیوں نہیں کر سکتا، [تین سکوپ نام اسپیسز](../frameworks/MCP-SERVER.md#three-scope-namespaces) میں ہے۔

API کیز میں ایک `scopes` ایرے شامل ہوتا ہے (جو `api_keys.scopes` میں JSON کے طور پر محفوظ کیا جاتا ہے، دیکھیں `src/lib/db/apiKeys.ts`)۔

### مینجمنٹ سکوپ

- `manage` / `admin` — `hasManageScope`۔ مینجمنٹ API روٹس تک بیئرر رسائی۔
- `mcp:connect`، `self:usage`، `self:account-quota`، اور `policy:bypass-provider-quota` اضافی عین مطابق میچ سکوپس ہیں۔ یہ `MANAGEMENT_API_KEY_SCOPES` سے باہر رہتے ہیں۔ `mcp:connect` صرف `/api/mcp/` نان-لوپ بیک کارو آؤٹ کو کھولتا ہے۔

### MCP ٹول سکوپس

کیٹلاگ اور میچنگ کے قواعد (یکساں سٹرنگ، یا ایک عطا کردہ سکوپ جو `*` پر ختم ہوتا ہے): [MCP ٹول سکوپس](../frameworks/MCP-SERVER.md#mcp-tool-scopes)۔ `src/shared/constants/mcpScopes.ts` میں `MCP_SCOPE_LIST` اصل ٹائپ شدہ ذیلی سیٹ ہے، نہ کہ وہ مکمل کیٹلاگ۔ نفاذ `open-sse/mcp-server/scopeEnforcement.ts` میں `resolveCallerScopeContext()` کے بعد چلتا ہے جو MCP تصدیقی معلومات، ریکویسٹ میٹا ڈیٹا، یا `OMNIROUTE_MCP_SCOPES` سے سکوپس کو حل کرتا ہے۔ یہ بند رہتا ہے جب تک کہ `OMNIROUTE_MCP_ENFORCE_SCOPES=true` نہ ہو۔

### ایکسیس ٹوکن سکوپس

`oma_live_…` ٹوکنز پر `read` / `write` / `admin`، جن کی درجہ بندی `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`) کے ذریعے کی جاتی ہے۔ یہ درجہ بندی صرف ایکسیس ٹوکن کریڈینشل پر لاگو ہوتی ہے۔ [مینجمنٹ تصدیق](../guides/MANAGEMENT-AUTH.md) دیکھیں۔

## Auth Required ٹوگل

`src/shared/utils/apiAuth.ts` میں `isAuthRequired()` طے کرتا ہے کہ کسی درخواست کے لیے **کوئی بھی** احراز ہویت نافذ ہونی چاہیے یا نہیں:

- `settings.requireLogin === false` → احراز ہویت مجموعی طور پر غیر فعال ہے، سوائے ہمیشہ محفوظ رہنے والے درجے کے (دیکھیں [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) اور ان کالز کے جو ایسی اسناد جاری کرتی ہیں جنہیں قبول کیا جاتا ہے اور جنہیں لاگ ان فعال ہونے کی صورت جیسی ہی اسناد درکار ہوتی ہیں: sync ٹوکن جاری کرنا، کسی بھی اسکوپ کے CLI رسائی ٹوکن بنانا، اور `manage`/`admin` اسکوپ والی API کلید بنانا، کسی کلید کو وہ اسکوپ دینا، یا ایسی کلید کو دوبارہ بنانا یا ظاہر کرنا (`src/lib/api/requireManagementAuth.ts` میں `requireCredentialForManagementScopedKey()`)۔ صرف‌ استنتاج والی کلیدیں کھلی رہتی ہیں۔
- کوئی پاس ورڈ کنفیگر نہیں **اور** `INITIAL_PASSWORD` ماحولیاتی متغیر موجود نہیں → بوٹ اسٹریپ موڈ آن بورڈنگ وزرڈ اور loopback درخواستوں کی اجازت دیتا ہے، لیکن نیٹ ورک پر ظاہر درخواستوں کو اب بھی اسناد درکار ہیں۔
- کوئی DB خرابی → بند ہو جاتا ہے (ڈیفالٹ کے طور پر محفوظ)۔

کلائنٹ API کلید کا نفاذ `src/shared/utils/featureFlags.ts` میں `isRequireApiKeyEnabled()` استعمال کرتا ہے، براہ راست `process.env.REQUIRE_API_KEY` پڑھنے کے بجائے۔ تعینات شدہ انسٹنسز کے لیے یہ اہم ہے: ڈیش بورڈ → Feature Flags میں `REQUIRE_API_KEY` ٹوگل کرنے سے DB اوور رائڈ محفوظ ہوتا ہے اور فوراً `/v1/*`، `/v1beta/*`، `/models`، `/responses`، `/chat/completions`، `/codex/*` اور وہ دیگر کلائنٹ API احراز ہویت چیکس متاثر ہوتے ہیں جو اس ہیلپر کو استعمال کرتے ہیں۔ اگر فیچر فلیگ اسٹور نہ پڑھا جا سکے تو کلائنٹ API احراز ہویت بند ہو جاتی ہے اور کلید لازم ہوتی ہے۔

## بریکنگ تبدیلی — v3.8.0

`/api/v1/agents/tasks/*` اور `/api/resilience/model-cooldowns` اینڈ پوائنٹس کو **اب مینجمنٹ توثیق درکار ہے** (کمیٹ `588a0333`)۔ پہلے `manage` اسکوپ کے بغیر عام API کی بھیجنے والے کلائنٹس کو `403` موصول ہوتا ہے۔ مائیگریشن: یا API Keys ڈیش بورڈ میں کی کو `manage` اسکوپ جاری کریں، یا لاگ اِن شدہ ڈیش بورڈ سیشن استعمال کریں۔

## طرزِ عمل میں تبدیلی — v3.8.2

`/api/mcp/*` (ریموٹ MCP سرور) اب بھی بطور ڈیفالٹ LOCAL_ONLY ہے، لیکن اب غیر لوپ بیک درخواستیں قبول کرتا ہے جب `Authorization: Bearer <api-key>` ہیڈر میں `manage` اسکوپ موجود ہو۔ اس استثنا کو `src/server/authz/routeGuard.ts` میں `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` کے ذریعے واضح طور پر ہر پاتھ کے لیے گیٹ کیا گیا ہے؛ اس سے ملتا جلتا LOCAL_ONLY پری فکس `/api/cli-tools/runtime/*` دانستہ طور پر بائی پاس نہیں کیا جا سکتا کیونکہ یہ من مانی ذیلی پروسیسز چلا سکتا ہے۔ غیر لوپ بیک سے `/api/mcp/*` کو بھیجی گئی گمنام درخواستیں بدستور `403 LOCAL_ONLY` واپس کرتی ہیں — کسی بھی نئے LOCAL_ONLY پاتھ کے لیے ڈیفالٹ سخت لوپ بیک ہی رہتا ہے۔ [روٹ گارڈ درجات](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) دیکھیں۔

## ٹیسٹنگ

- یونٹ ٹیسٹس: `tests/unit/authz/` — `classify.test.ts`، `pipeline.test.ts`، `client-api-policy.test.ts`، `management-policy.test.ts`، `public-policy.test.ts`۔
- عوامی اجازت فہرست: `tests/unit/public-api-routes.test.ts`۔
- مخصوص ٹیسٹ چلائیں: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`۔

## ڈیبگنگ

پائپ لائن ہمیشہ اس کے ساتھ جوابات پر مہر لگاتی ہے:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

تصدیق شدہ درخواستوں کے لیے اپ اسٹریم (ہینڈلر سائیڈ) درخواست کے ہیڈر میں بھی شامل ہیں:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ہینڈلرز — کے اندر `assertAuth(req, expectedClass)` استعمال کریں اگر مڈل ویئر کو نظرانداز کیا گیا تھا تو یہ `AuthzAssertionError` کوڈ `AUTHZ_NOT_INITIALIZED` کے ساتھ پھینک دیتا ہے (ٹیسٹوں میں کنفیگریشن ریگریشنز کو پکڑنے میں مددگار)۔

## مزید دیکھیں

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ہر اینڈ پوائنٹ کے لیے auth مارکر
- [COMPLIANCE.md](../security/COMPLIANCE.md) — auth ایونٹس کے لیے آڈٹ لاگ
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — تین اسکوپ نیم اسپیسز اور MCP ٹول-اسکوپ کیٹلاگ
- ماخذ: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
