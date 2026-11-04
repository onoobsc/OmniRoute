# Authorization Guide (العربية)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **مصدر الحقيقة:** `src/server/authz/`، `src/shared/constants/publicApiRoutes.ts`، `src/lib/api/requireManagementAuth.ts`، `src/shared/utils/apiAuth.ts`
> **آخر تحديث:** 2026-09-22 — تشير مساحات أسماء النطاقات إلى MCP-SERVER.md

لدى OmniRoute مسار معالجة تخويل مُدرك للمسارات، يتحكم في كل طلب API. ويُعد التصنيف **حتميًا** و**مغلقًا عند الفشل** — فأي شيء يتعذر تصنيفه ينتهي به المطاف ضمن `MANAGEMENT` ويتطلب جلسة أو رمزًا مميزًا بمستوى الإدارة. تشرح هذه الصفحة النموذج للمهندسين الذين يتولون صيانة المسارات أو تصميم نقاط نهاية جديدة.

![مسار معالجة AuthZ (3 فئات للمسارات + تقييم السياسات)](../diagrams/exported/authz-pipeline.svg)

> المصدر: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## وضعان للمصادقة

### 1. مفتاح API (حامله)

يُستخدم لعميل OpenAI/Anthropic/Gemini-compatible APIs وبعض مسارات الإدارة عندما يكون للمفتاح نطاق `manage`.

```
Authorization: Bearer <api-key>
```

تم التحقق من صحته بواسطة `isValidApiKey()` / `extractApiKey()` في `src/sse/services/auth.ts` وإعادة تصديره من خلال `src/shared/utils/apiAuth.ts`. يقبل المدقق أيضًا `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars كمفاتيح عبور مستمرة (الإصدار #1350).

### 2. جلسة لوحة المعلومات (ملف تعريف الارتباط auth_token)

لصفحات لوحة المعلومات وعمليات الإدارة.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

ملف تعريف الارتباط هو جلسة فقط عندما يتم التحقق من JWT** و** يحمل `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). كل مستهلك لملف تعريف الارتباط (حارس مسار لوحة المعلومات (`isDashboardSessionAuthenticated()`)، تحديث خط أنابيب authz، مصافحة WebSocket ، الخادم المباشر، `/api/settings/require-login`، `/api/auth/status`) يمر عبر هذا المساعد. JWTs الأخرى الموقعة مع `JWT_SECRET` موجودة — the Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` tokens لحاملي المفاتيح — ولا تكون جلسات أبدًا (#13298).

تم التحقق منها بواسطة `isDashboardSessionAuthenticated()` في `src/shared/utils/apiAuth.ts`. يقوم خط الأنابيب بتحديث JWT تلقائيًا عندما يتبقى له أقل من 7 أيام في عمره البالغ 30 يومًا.

يمكن أن تنتهي الجلسة أيضًا قبل انتهاء 30 يومًا، لأن كل مندوب يمر عبر `mintDashboardSessionToken` (وقت الإصدار `iat` وid `jti`) ويتحقق المدقق من إعدادين: `sessionsValidAfter`، يتم ضبطه بواسطة تغيير كلمة المرور بحيث يتم إصدار كل جلسة قبل أن تتوقف عن التحقق (يحصل المتصفح الذي غير كلمة المرور على ملف تعريف ارتباط جديد)، و `revokedDashboardSessions`، حيث يضيف `POST /api/auth/logout` `jti` للجلسة التي تم تسجيل الخروج منها. لا تحمل الجلسات التي تم سكها بواسطة إصدار أقدم أي مطالبة وتظل صالحة حتى يتم تغيير كلمة المرور الأولى. إذا تعذرت قراءة الإعدادات، فهذا يعني أن الجلسة غير موثوقة.

تقبل بعض طرق الإدارة** أيضاً** الوضع: ملف تعريف الارتباط OR `Bearer <key>` عندما يكون لمفتاح API نطاق `manage` (أو `admin`). وهذا هو ما يمكّن سير العمل "القابل للتكوين عبر مكالمات API " الذي تمت إضافته في الإصدار 3.8.

#### بوابة تسجيل الدخول OIDC الاختيارية (#6973)

يدعم تسجيل دخول مسؤول لوحة المعلومات أيضًا** الاشتراك** تدفق OIDC (OpenID Connect) جنبًا إلى جنب مع تسجيل الدخول بكلمة المرور الافتراضية لا تتم إزالة تسجيل الدخول بكلمة مرور — مطلقًا، بل يتم استكماله فقط:

- معطل ما لم `settings.oidcEnabled === true`** و** تم تكوين جميع `oidcIssuer` / `oidcClientId` / `oidcClientSecret` (إعدادات → Auth). `GET /api/auth/oidc/login` ترجع `400` خلاف ذلك.
- تكتشف `GET /api/auth/oidc/login` `authorization_endpoint` من `/.well-known/openid-configuration` الخاص بجهة الإصدار (تعود إلى `<issuer>/authorize`)، وتنشئ إعادة توجيه URI من الطلب الوارد (`x-forwarded-proto` -aware)، وتعيد التوجيه إلى IdP باستخدام `state` العشوائي المخزن في ملف تعريف الارتباط `httpOnly` `oidc_state`.
- يقوم `GET /api/auth/oidc/callback` بالتحقق من صحة `state`، وتبادل رمز التفويض، والتحقق من توقيع رمز ID عبر JWKS الخاص بجهة الإصدار (`jose`'s `createRemoteJWKSet`، مخبأة لكل JWKS URI) مع عمليات فحص `issuer`/`audience`. يتطلب قبول لوحة المعلومات وجود قائمة `oidcAllowedSubjects` غير فارغة، أو سياسة `oidcAdmissionClaim` ، أو كليهما. تتطابق قائمة المواضيع مع `sub` أو `email` فقط عندما `email_verified === true`. تأخذ سياسة المطالبة الاختيارية مسار مطالبة رمز معرف مفصول بنقاط (على سبيل المثال، `realm_access.roles`) ومجموعة من القيم المقبولة؛ يجب أن تكون المطالبة التي تم حلها عبارة عن مجموعة من السلاسل التي تحتوي على قيمة واحدة مقبولة على الأقل. إذا تم تكوين كلا النهجين، فيجب تمريرهما. فشل إغلاق مطالبات Missing/malformed ، وبدون أي من السياسات، يرفض رد الاتصال تسجيل الدخول (`not_configured`). تستمر التكوينات الحالية للموضوع فقط دون تغيير.
- تقوم Keycloak عادة بتعيين أدوار المجال إلى رموز الوصول، وليس بالضرورة رموز ID. لطلب دور المجال `admin`، قم بتكوين مخطط بروتوكول لهذا العميل الذي يتضمن `realm_access.roles` في ملفه** رمز ID** ، ثم اضبط `oidcAdmissionClaim` على `{ "path": "realm_access.roles", "values": ["admin"] }`. تحقق من المطالبة الفعلية لرمز المعرف لهذا العميل قبل تمكين قبول الدور فقط؛ لا يقرأ التطبيق أدوار رمز الوصول. يمكن أن يكون رفض الرمز المميز من جانب IdP مكملاً لهذا الفحص من جانب التطبيق ولكنه لا يحل محله.
- على النجاح فإنه النعناع** نفس الشيء بالضبط** 30 يومًا `auth_token` JWT مشكلات تسجيل الدخول بكلمة المرور (`src/app/api/auth/login/route.ts`)، وبالتالي فإن بقية مسار جلسة لوحة المعلومات (التحديث التلقائي، علامات ملفات تعريف الارتباط) لم تتغير. — OIDC يستبدل فقط كيفية سك ملف تعريف الارتباط، وليس ما يمنحه. لا تؤدي التغييرات التي تم إجراؤها على IdP roles/groups إلى إبطال جلسات OmniRoute الموجودة؛ لا يزال تسجيل الخروج أو تدوير كلمة المرور أو انتهاء صلاحية الجلسة هو الذي يحكم مدة بقائها.
- كل إعداد `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) موجود في `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): يجيب `PATCH /api/settings` على `400 PASSWORD_REQUIRED` ما لم يحمل الجسم كلمة مرور الإدارة كـ `currentPassword` (`401 PASSWORD_MISMATCH` عندما تكون خاطئة). يرفض `oidcDisablePasswordLogin` كلمة المرور _login_ (`POST /api/auth/login`) ولكنه يحتفظ بتجزئة كلمة المرور المخزنة، ولا تزال عملية إعادة المصادقة تتحقق من `currentPassword` مقابلها.
- `corsOrigins` و `bruteForceProtection` موجودان في `SECURITY_IMPACTING_SETTINGS_KEYS` أيضًا: يؤدي التخفيف إما إلى إضعاف دفاعات تسجيل الدخول، لذا فهم يأخذون نفس إعادة مصادقة `currentPassword` (تطلب علامة التبويب "الأمان" ذلك) ويسقطهم استيراد JSON.
- كل مفتاح سياسة أمان — وإدخالات `SECURITY_IMPACTING_SETTINGS_KEYS` وكل مفتاح `oidc*` وحالة جلسة لوحة المعلومات — هي** المشغل فقط** على `PATCH /api/settings`: يتم رفض مفتاح API ذو نطاق الإدارة أو رمز وصول `oma_` باستخدام `403` حتى عندما يرسل `currentPassword` الصحيح، ويتم تدقيق الرفض على أنه `settings.update_failed` مع `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` في `src/lib/api/operatorCredential.ts`). تظل الإعدادات العادية (السمة، وتفضيلات العرض) قابلة للكتابة لمفتاح `manage` أو رمز وصول `admin`. تحتاج كل طفرة في `/api/settings` نفسها (و `/api/settings/require-login`) أيضًا إلى نطاق رمز الوصول `admin` (`ADMIN_MUTATION_EXACT_PATHS` في `src/server/authz/accessScopes.ts`، مطابقة المسار التام)؛ يبقى `GET` `read`، وتحتفظ مسارات `/api/settings/*` الفرعية الأخرى (الوكلاء، وافتراضيات التحرير والسرد، والأسماء المستعارة للنماذج، والضغط، وعمليات التطهير...) بنطاق `write` المستنتج من الطريقة.
- يتخطى `POST /api/settings/import-json` عملية إعادة المصادقة هذه، لذا فهو يسقط كل مفتاح في `IMPORT_STRIPPED_SETTINGS_KEYS` (نفس الملف) قبل الكتابة: كلمة المرور و `currentPassword`، وكل إدخال `SECURITY_IMPACTING_SETTINGS_KEYS` ، وحالة جلسة لوحة المعلومات (`sessionsValidAfter`، `revokedDashboardSessions`). وبالتالي، لا يمكن لاستيراد نسخة احتياطية قديمة إحياء الجلسة التي تم بالفعل تغيير كلمة المرور أو تسجيل الخروج منها.

#### تسجيل الدخول الاختياري TOTP ثنائي العامل (#16619)

تم التسجيل من إعدادات → Security؛ إيقاف حتى يقوم المشغل بتشغيله (`src/server/auth/dashboardMfa.ts`).

- **ما يغطيه:** تسجيل الدخول بكلمة المرور (`POST /api/auth/login`، والذي يحتاج بعد ذلك `POST /api/auth/mfa/verify`) و `omniroute connect` (`POST /api/cli/connect`، الذي يرفض تبادل كلمة المرور فقط ويأخذ الرمز كـ `totp`).
- **ما لا يغطيه:** تسجيل الدخول OIDC / SSO (`/api/auth/oidc/callback`) لا يطلب OmniRoute TOTP. وهو يعتمد على العامل الثاني الخاص بموفر الهوية، لذا قم بفرض MFA في IdP إذا تم تمكين OIDC.
- **استعادة** (جهاز مفقود، أو عدم وجود رموز استرداد متبقية، أو عامل لم يعد من الممكن التحقق منه، على سبيل المثال بعد تغيير `STORAGE_ENCRYPTION_KEY` ):
  1. أعد تشغيل الخادم باستخدام `OMNIROUTE_DISABLE_MFA=true`.
  2. على المضيف نفسه (نظير الاسترجاع والاسترجاع `Host`، مثل `http://localhost:20128`)، قم بتسجيل الدخول باستخدام كلمة المرور. يتم تخطي العامل الثاني لهذا الأصل فقط؛ كل أصل آخر لا يزال بحاجة إلى الكود.
  3. في إعدادات → Security → Disable، أدخل كلمة المرور واترك الرمز فارغًا. يقبل `POST /api/auth/mfa/disable` نصًا بدون `code` فقط أثناء تعيين المتغير ويأتي الطلب من المضيف؛ لا يزال يتطلب جلسة لوحة المعلومات وكلمة المرور الحالية، ويتم تدقيقه كـ `auth.mfa.disabled` باستخدام `secondFactor: "recovery_switch"`.
  4. قم بإلغاء تعيين `OMNIROUTE_DISABLE_MFA` وأعد التشغيل وقم بالتسجيل مرة أخرى إذا لزم الأمر.

## فئات المسارات

يعرّف `src/server/authz/types.ts` ثلاث فئات، وأي مسار لا يمكن تصنيفه بشكل حتمي يرجع إلى `MANAGEMENT`.

| Class        | Description                                                                                                                                                     | Auth required                                                 |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| `PUBLIC`     | مسارات آمنة صراحةً: تسجيل الدخول، وتسجيل الخروج، والحالة، والتهيئة، والصحة، وتمهيد الإعداد الأولي.                                                              | لا شيء                                                        |
| `CLIENT_API` | نقاط خدمة النماذج: `/api/v1/*` و`/api/v1beta/*`، بالإضافة إلى الأسماء المستعارة `/v1/*` و`/v1beta/*` و`/chat/completions` و`/responses` و`/models` و`/codex/*`. | مفتاح Bearer عندما تكون ميزة `REQUIRE_API_KEY` الفعلية مفعّلة |
| `MANAGEMENT` | صفحات لوحة التحكم، والإعدادات، والمزوّدون، والمفاتيح، ونقاط الإدارة والتشخيص.                                                                                   | جلسة لوحة التحكم **أو** Bearer بنطاق `manage`                 |

تحتاج بعض إجراءات `MANAGEMENT` إلى **المشغّل فقط**: فمفتاح `manage` لا يكفي. فتصدير بيانات الاعتماد المخزّنة (`GET /api/settings/export-json` و`GET /api/db-backups/export` و`GET /api/db-backups/exportAll`)، واستعادة نسخة احتياطية فوق البيانات الحية (`POST /api/db-backups/import` بما فيه `dryRun=true`، و`POST /api/db-backups` للاستعادة بالمعرّف، و`POST /api/settings/import-json`)، وإتلاف نقاط الاستعادة (تنظيف `DELETE /api/db-backups`، و`PATCH /api/db-backups` لأن الاحتفاظ الذي يحفظه يقود التقليم التلقائي بعد كل نسخة احتياطية) كلها تتطلب جلسة لوحة التحكم، أو هوية CLI المحلية، أو تعطيل تسجيل الدخول. ويتطلب إصدار رمز مزامنة (`POST /api/sync/tokens`) وسكّ رمز وصول CLI بنطاق `admin` (`POST /api/cli/tokens`) جلسة لوحة التحكم أو هوية CLI المحلية في كل أوضاع تسجيل الدخول. ومفاتيح API بأي نطاق ورموز الوصول `oma_` ليست بيانات اعتماد للمشغّل: فتتلقى الخطأ `403` كلما اشترط المسار ذلك. ويقع الفحص في `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). وتغيير إعدادات تسجيل الدخول مقصور على المشغّل أيضًا: إذ لا يقبل `POST /api/settings/require-login` (لضبط كلمة مرور الإدارة أو تبديل `requireLogin`) إلا هذه البيانات بعد وجود كلمة مرور، أما نافذة التمهيد الأولي عند أول تشغيل (قبل وجود كلمة مرور) فتبقى كما هي، ويجب أن ترسل جلسة لوحة التحكم `currentPassword` لاستبدال كلمة المرور (فيعيد `403` عند غيابها أو خطئها، ويُدقَّق بوصفه `settings.update_failed`). وتحتفظ CLI المحلية، والنسخة التي عُطّل فيها تسجيل الدخول، بمسار الاسترداد، ويجوز لها ضبط كلمة مرور دون هذا الشرط، لأن كليهما مرتبط بالمضيف الذي يملك مجلد البيانات.

## خط أنابيب

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

الرؤوس الداخلية الموثوقة (المحددة في `src/server/authz/headers.ts`) هي** جردت من الطلبات الواردة** قبل التصنيف، لا يمكن لعملاء — تعبئة `x-omniroute-auth-*` مسبقًا لانتحال شخصية موضوع ما.

### عقود السياسة

كل فئة مسار لها سياسة في `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — يُرجع دائمًا `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — يستخرج Bearer، ويتم التحقق من صحته عبر `validateApiKey()`. يصل إلى المجهول فقط عند تعطيل علامة ميزة `REQUIRE_API_KEY` الفعالة. يتم حل العلامة الفعالة من خلال `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) لذا فإن علامات ميزات لوحة المعلومات ومتغيرات البيئة تحكم `/api/v1/*` و `/api/v1beta/*` والأسماء المستعارة بشكل متسق؛ فشل محلل مغلقة. يسمح بطلبات جلسة لوحة المعلومات على مسارات API للعميل (بما في ذلك `/api/v1/models`، المستخدمة بواسطة كتالوج نموذج لوحة المعلومات). عند تمكين Entra ID SSO ، تتم معالجة الحامل الذي يمثل رمز Entra من الناحية الهيكلية (ثلاثة مقاطع base64url، `RS*` alg، `kid`) بواسطة فرع SSO** قبل** `validateApiKey()` وحكمه نهائي — فهو لا يصل أبدًا إلى مسار مفتاح واجهة برمجة التطبيقات (API) أو الفرع الذي يتحول إلى مجهول، لذلك لا يمكن أن يصبح انقطاع موفر الهوية وصولاً مفتوحًا. لا تتأثر مفاتيح API الثابتة. انظر [إنترا ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) يقبل — جلسة لوحة المعلومات، أو طلبات مزامنة النموذج الداخلي (المتطابقة مع `/api/providers/[name]/(sync-models|models)`)، أو يتخطى كليًا إذا أعاد `isAuthRequired()` خطأ. تُرجع 403 (`AUTH_001`) في حالة وجود رمز حامل ولكنه غير صالح، وتُرجع 401 بخلاف ذلك. يفرض أيضًا طبقات حماية الطريق (LOCAL_ONLY / ALWAYS_PROTECTED) قبل أي فرع مصادقة — راجع [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). يمكن الوصول إلى مسارات LOCAL_ONLY في `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (اليوم: `/api/mcp/`) من دون استرجاع عندما يحمل المفتاح Bearer نطاق `manage` ؛ تظل كافة مسارات LOCAL_ONLY الأخرى ذات استرجاع صارم بغض النظر عن النطاق.

السياسة الناجحة ترجع `AuthSubject` مع `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. يمكن للمعالجات النهائية قراءتها عبر `assertAuth(request, "CLIENT_API")` في `src/server/authz/assertAuth.ts` بدلاً من إعادة تشغيل منطق المصادقة.

## قائمة الطرق العامة

`src/shared/constants/publicApiRoutes.ts` هي القائمة المسموح بها الصريحة:

القائمة مقسمة حسب** شكل** ، والتقسيم حامل (GHSA-74g9-q8f6-793h): تتم مطابقة البادئة مع `startsWith()`، لذا فهي تتطابق أيضًا مع كل مسار مجاور يتقاسم أحرفه الرئيسية. `/api/usage/om-usage` كبادئة تم وضع علامة `/api/usage/om-usage<anything>` PUBLIC عليها، ويحل Next ذلك إلى `/api/usage/[connectionId]` — معالج بدون مصادقة خاصة به.

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

طرق القراءة فقط عامة** فقط** للطرق الآمنة. ملاحظة: `classifyRoute()` تستبعد `/api/v1/*` و `/api/v1beta/*` من PUBLIC Fall-through — وهما دائمًا `CLIENT_API` لذا تظل سياسة Bearer-key سارية.

## إضافة مسار جديد

### النمط 1 — نقطة نهاية عامة لواجهة API الخاصة بالعميل (مصادقة Bearer)

تُصنَّف المسارات الواقعة تحت `/api/v1/` و`/api/v1beta/` تلقائيًا على أنها `CLIENT_API`. تفرض البرمجية الوسيطة التحقق من Bearer؛ ولا تحتاج معالجات المسارات إلى تكراره، لكن يمكنها قراءة هوية صاحب الطلب عند الحاجة.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... منطق المعالج
}
```

### النمط 2 — نقطة نهاية إدارية (جلسة أو Bearer + manage)

استخدم `requireManagementAuth()` من `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... منطق المعالج
}
```

تعيد `requireManagementAuth()` القيمة `null` عند النجاح، أو `Response` لخطأ بصيغة JSON:

- 401 `AUTH_001` "المصادقة مطلوبة" — لا توجد أي بيانات اعتماد
- 403 — بيانات Bearer غير صالحة **أو** توجد بيانات Bearer لكن المفتاح يفتقر إلى النطاق `manage` / `admin`

تعيد `hasManageScope(scopes)` القيمة true عند وجود `"manage"` أو `"admin"`.

### النمط 3 — الإضافة إلى قائمة السماح العامة

اختر المجموعة بناءً على الشكل، لا على سهولة الاستخدام. يوضع المسار المنفرد في `PUBLIC_API_ROUTES_EXACT` (أو في `PUBLIC_READONLY_CORS_API_ROUTES` إذا كان مخصصًا لـ GET فقط)؛ ولا يوضع في `PUBLIC_API_ROUTE_PREFIXES` سوى شجرة فرعية فعلية، ويجب أن **تنتهي بـ `/`**. يؤدي وضع مسار منفرد في قائمة البادئات أيضًا إلى نشر كل مسار مجاور يشترك معه في المحارف الأولى — بما في ذلك المسارات الشقيقة ذات المقاطع الديناميكية التي تُضاف لاحقًا (GHSA-74g9-q8f6-793h). حدّث اختبارات الوحدة في `tests/unit/public-api-routes.test.ts` و`tests/unit/authz/public-route-exact-match.test.ts` و`tests/unit/authz/classify.test.ts`.

## النطاقات

ثلاثة مساحات أسماء. يقرأ كل مدقّق السلاسل النصية الخاصة به فقط. للمقارنة جنبًا إلى جنب، بما في ذلك سبب فشل `manage` في `scopeMatches` بالنسبة إلى `read:compression` وسبب عدم تمكّن رمز وصول ذي نطاق `read` من تنفيذ `PATCH /api/keys/{id}`، راجع
[مساحات أسماء النطاقات الثلاث](../frameworks/MCP-SERVER.md#three-scope-namespaces).

تحمل مفاتيح API مصفوفة `scopes` (مخزّنة بصيغة JSON في `api_keys.scopes`، راجع `src/lib/db/apiKeys.ts`).

### نطاق الإدارة

- `manage` / `admin` — `hasManageScope`. وصول حامل الرمز إلى مسارات واجهة API الإدارية.
- إن `mcp:connect` و`self:usage` و`self:account-quota` و
  `policy:bypass-provider-quota` هي نطاقات تراكمية تعتمد على التطابق التام. وهي تقع
  خارج `MANAGEMENT_API_KEY_SCOPES`. لا يتيح `mcp:connect` سوى
  استثناء الوصول غير المحلي إلى `/api/mcp/`.

### نطاقات أدوات MCP

دليل النطاقات وقواعد المطابقة (سلسلة نصية متطابقة، أو نطاق ممنوح ينتهي بـ `*`):
[نطاقات أدوات MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
تمثّل `MCP_SCOPE_LIST` في `src/shared/constants/mcpScopes.ts` المجموعة الفرعية الأصلية
ذات الأنواع المحددة، وليست الدليل الكامل. يجري الإنفاذ في
`open-sse/mcp-server/scopeEnforcement.ts` بعد أن تحلّ `resolveCallerScopeContext()`
النطاقات من معلومات مصادقة MCP أو بيانات الطلب الوصفية أو `OMNIROUTE_MCP_SCOPES`.
ويظل معطّلًا ما لم تكن `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### نطاقات رموز الوصول

`read` / `write` / `admin` على رموز `oma_live_…`، مرتبة بواسطة `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). ينطبق هذا الترتيب على بيانات اعتماد رمز الوصول
فقط. راجع [مصادقة الإدارة](../guides/MANAGEMENT-AUTH.md).

## تبديل اشتراط المصادقة

تحدّد `isAuthRequired()` في `src/shared/utils/apiAuth.ts` ما إذا كانت **أي** مصادقة مطلوبة لطلب ما:

- `settings.requireLogin === false` ← تُعطّل المصادقة على مستوى النظام، باستثناء فئة الحماية الدائمة (انظر [مستويات حارس المسارات](../security/ROUTE_GUARD_TIERS.md)) والاستدعاءات التي تُسلّم بيانات اعتماد يقبلها النظام، والتي تتطلب بيانات الاعتماد نفسها كما لو كان تسجيل الدخول مفعّلًا: إصدار رموز المزامنة، وسكّ رموز وصول CLI بأي نطاق، وإنشاء مفتاح API بنطاق `manage`/`admin`، ومنح هذا النطاق لمفتاح، أو إعادة توليد مفتاح من هذا النوع أو كشفه (`requireCredentialForManagementScopedKey()` في `src/lib/api/requireManagementAuth.ts`). أما مفاتيح الاستدلال فقط فتبقى مفتوحة.
- لا توجد كلمة مرور مُعدّة **ولا** متغير البيئة `INITIAL_PASSWORD` ← يسمح وضع التمهيد بمعالج الإعداد وبالطلبات المحلية (loopback)، لكن الطلبات الشبكية المكشوفة ما زالت تحتاج إلى بيانات اعتماد.
- أي خطأ في قاعدة البيانات ← يفشل النظام مغلقًا (آمن افتراضيًا).

يستخدم فرض مفتاح API للعميل `isRequireApiKeyEnabled()` في `src/shared/utils/featureFlags.ts`، لا قراءة مباشرة لـ `process.env.REQUIRE_API_KEY`. وهذا مهم للنسخ المنشورة: فتبديل `REQUIRE_API_KEY` في لوحة التحكم ← أعلام الميزات يخزّن تجاوزًا في قاعدة البيانات ويؤثر فورًا في `/v1/*` و`/v1beta/*` و`/models` و`/responses` و`/chat/completions` و`/codex/*`، وفي فحوص مصادقة واجهة برمجة العميل الأخرى التي تشارك هذه الدالة المساعدة. وإذا تعذّرت قراءة مخزن أعلام الميزات فإن مصادقة واجهة العميل تفشل مغلقة وتشترط مفتاحًا.

## تغيير غير متوافق — v3.8.0

أصبحت نقطتا النهاية `/api/v1/agents/tasks/*` و`/api/resilience/model-cooldowns` **تتطلبان الآن مصادقة إدارية** (الالتزام `588a0333`). تتلقى تطبيقات العميل التي كانت ترسل سابقًا مفتاح API عاديًا من دون نطاق `manage` استجابة `403`. الترحيل: امنح المفتاح نطاق `manage` من لوحة معلومات API Keys، أو استخدم جلسة مسجَّلة الدخول في لوحة المعلومات.

## تغيير في السلوك — v3.8.2

لا يزال `/api/mcp/*` (خادم MCP البعيد) مضبوطًا افتراضيًا على LOCAL_ONLY، لكنه يقبل الآن الطلبات غير الواردة من عنوان الاسترجاع المحلي عندما يحمل الترويس `Authorization: Bearer <api-key>` نطاق `manage`. يُقيَّد هذا الاستثناء صراحةً لكل مسار عبر `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` في `src/server/authz/routeGuard.ts`؛ أما بادئة LOCAL_ONLY الشقيقة `/api/cli-tools/runtime/*` فلا يمكن تجاوزها عمدًا لأنها تستطيع تشغيل عمليات فرعية عشوائية. تستمر الطلبات المجهولة إلى `/api/mcp/*` من عناوين غير محلية في تلقي `403 LOCAL_ONLY` — ويظل الإعداد الافتراضي لأي مسار LOCAL_ONLY جديد مقتصرًا بصرامة على الاسترجاع المحلي. راجع [مستويات حارس المسارات](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## الاختبار

- اختبارات الوحدة: `tests/unit/authz/` — `classify.test.ts` و`pipeline.test.ts` و`client-api-policy.test.ts` و`management-policy.test.ts` و`public-policy.test.ts`.
- قائمة السماح العامة: `tests/unit/public-api-routes.test.ts`.
- لتشغيل اختبار محدد: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## تصحيح الأخطاء

يقوم المسار دائمًا بختم الاستجابات بـ:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

بالنسبة للطلبات التي تمت مصادقتها، تتضمن رؤوس الطلب الأولية (جانب المعالج) أيضًا ما يلي:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

استخدم `assertAuth(req, expectedClass)` داخل المعالجات — حيث يرمي `AuthzAssertionError` بالكود `AUTHZ_NOT_INITIALIZED` إذا تم تجاوز البرنامج الوسيط (مفيد في اكتشاف تراجعات التكوين في الاختبارات).

## انظر أيضًا

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — علامة المصادقة لكل نقطة نهاية
- [COMPLIANCE.md](../security/COMPLIANCE.md) — سجل التدقيق لأحداث المصادقة
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — نطاقات الأذونات الثلاثة ودليل نطاقات أدوات MCP
- المصدر: `src/server/authz/`، `src/lib/api/requireManagementAuth.ts`
