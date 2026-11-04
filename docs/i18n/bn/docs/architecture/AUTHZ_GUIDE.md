# Authorization Guide (বাংলা)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **সত্যের উৎস:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **সর্বশেষ হালনাগাদ:** 2026-09-22 — স্কোপ নেমস্পেসগুলো MCP-SERVER.md-এর দিকে নির্দেশ করে

OmniRoute-এ একটি রুট-সচেতন অথরাইজেশন পাইপলাইন রয়েছে, যা প্রতিটি API অনুরোধকে নিয়ন্ত্রণ করে। শ্রেণিবিন্যাস **নির্ধারণবাদী** এবং **ব্যর্থ হলে বন্ধ** — শ্রেণিবদ্ধ করা যায় না এমন সবকিছু শেষ পর্যন্ত `MANAGEMENT` হিসেবে গণ্য হয় এবং একটি সেশন বা ম্যানেজমেন্ট-গ্রেড টোকেন দাবি করে। রুট রক্ষণাবেক্ষণকারী বা নতুন এন্ডপয়েন্ট ডিজাইনকারী প্রকৌশলীদের জন্য এই পৃষ্ঠায় মডেলটি ব্যাখ্যা করা হয়েছে।

![AuthZ পাইপলাইন (৩টি রুট শ্রেণি + নীতি মূল্যায়ন)](../diagrams/exported/authz-pipeline.svg)

> উৎস: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## দুটি প্রমাণীকরণ মোড

### 1. API কী (বাহক)

OpenAI/Anthropic/Gemini-compatible ক্লায়েন্ট APIs এবং কয়েকটি ম্যানেজমেন্ট রুটের জন্য ব্যবহৃত হয় যখন কীটির `manage` সুযোগ থাকে।

```
Authorization: Bearer <api-key>
```

`isValidApiKey()` / `extractApiKey()` দ্বারা `src/sse/services/auth.ts` এ বৈধ এবং `src/shared/utils/apiAuth.ts` মাধ্যমে পুনরায় রপ্তানি করা হয়েছে। যাচাইকারী `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars-কে ক্রমাগত পাসথ্রু কী (ইস্যু #1350) হিসাবে গ্রহণ করে।

### 2. ড্যাশবোর্ড সেশন (auth_token কুকি)

ড্যাশবোর্ড পেজ এবং অ্যাডমিন অপারেশনের জন্য।

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

একটি কুকি শুধুমাত্র একটি সেশন যখন JWT যাচাই করে** এবং** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) বহন করে। কুকির প্রতিটি গ্রাহক (ড্যাশবোর্ড রুট গার্ড (`isDashboardSessionAuthenticated()`), authz পাইপলাইন রিফ্রেশ, WebSocket হ্যান্ডশেক, লাইভ সার্ভার, `/api/settings/require-login`, `/api/auth/status`) সেই সাহায্যকারীর মাধ্যমে যান৷ `JWT_SECRET` সাথে স্বাক্ষরিত অন্যান্য JWTs বিদ্যমান — Cursor CLI পাসথ্রু কী হোল্ডার — জন্য `iss "omniroute" / aud "cursor-cli"` টোকেন এবং কখনোই সেশন নয় (#13298)।

`src/shared/utils/apiAuth.ts` এ `isDashboardSessionAuthenticated()` দ্বারা যাচাই করা হয়েছে। পাইপলাইনটি JWT স্বয়ংক্রিয়ভাবে রিফ্রেশ করে যখন এটির 30 দিনের জীবনে 7 দিনেরও কম বাকি থাকে।

একটি সেশন তার 30 দিন শেষ হওয়ার আগেও শেষ হতে পারে, কারণ প্রতিটি মিনটার `mintDashboardSessionToken` (একটি ইস্যু সময় `iat` এবং একটি id `jti`) এর মধ্য দিয়ে যায় এবং যাচাইকারী দুটি সেটিংস পরীক্ষা করে: `sessionsValidAfter`, একটি পাসওয়ার্ড পরিবর্তন দ্বারা সেট করা হয় যাতে প্রতিটি সেশন যাচাই করা বন্ধ করার আগে জারি করা হয় (পাসওয়ার্ড পরিবর্তন করা ব্রাউজার একটি নতুন কুকি পায়), এবং যা `revokedDashboardSessions` `POST /api/auth/logout` সেশন সাইন আউট করে `jti` একটি পুরানো রিলিজ দ্বারা মিন্ট করা সেশনগুলি কোন দাবি বহন করে না এবং প্রথম পাসওয়ার্ড পরিবর্তন না হওয়া পর্যন্ত বৈধ থাকে। সেটিংস পড়া না গেলে, সেশনটি বিশ্বস্ত নয়।

কিছু ব্যবস্থাপনা রুট গ্রহণ** হয়** মোড: কুকি OR `Bearer <key>` যখন API কীটির `manage` (বা `admin`) সুযোগ থাকে। এটিই v3.8 এ যোগ করা " API কলের মাধ্যমে কনফিগারযোগ্য" কর্মপ্রবাহকে সক্ষম করে।

#### ঐচ্ছিক OIDC লগইন গেট (#6973)

ড্যাশবোর্ড অ্যাডমিন লগইন একটি সমর্থন করে** অপ্ট-ইন** ডিফল্ট পাসওয়ার্ড লগইনের পাশাপাশি OIDC (OpenID Connect) ফ্লো — পাসওয়ার্ড লগইন কখনও সরানো হয় না, শুধুমাত্র পরিপূরক:

- অক্ষম যদি না `settings.oidcEnabled === true`** এবং** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` সব কনফিগার করা হয়েছে (সেটিংস → প্রমাণ)। `GET /api/auth/oidc/login` অন্যথায় `400` ফেরত দেয়।
- `GET /api/auth/oidc/login` ইস্যুকারীর `/.well-known/openid-configuration` থেকে `authorization_endpoint` আবিষ্কার করে ( `<issuer>/authorize` তে ফিরে আসে), ইনকামিং রিকোয়েস্ট (`x-forwarded-proto` -aware) থেকে রিডাইরেক্ট URI তৈরি করে এবং `httpOnly` `oidc_state` কুকিতে সংরক্ষিত একটি এলোমেলো `state` দিয়ে IdP এ পুনঃনির্দেশ করে।
- `GET /api/auth/oidc/callback` `state` যাচাই করে, অনুমোদন কোড বিনিময় করে এবং `issuer`/`audience` চেকের মাধ্যমে ইস্যুকারীর JWKS (`jose`'s `createRemoteJWKSet`, ক্যাশে প্রতি JWKS URI) এর মাধ্যমে ID টোকেনের স্বাক্ষর যাচাই করে। ড্যাশবোর্ডে ভর্তির জন্য একটি খালি `oidcAllowedSubjects` তালিকা, একটি `oidcAdmissionClaim` নীতি বা উভয়ই প্রয়োজন। বিষয় তালিকা `sub` বা `email` সাথে মেলে শুধুমাত্র যখন `email_verified === true`। ঐচ্ছিক দাবি নীতি একটি ডট-বিচ্ছিন্ন আইডি-টোকেন দাবির পথ (উদাহরণস্বরূপ, `realm_access.roles`) এবং গৃহীত মানগুলির একটি অ্যারে নেয়; মীমাংসিত দাবি অন্তত একটি স্বীকৃত মান ধারণকারী স্ট্রিং একটি অ্যারে হতে হবে. উভয় নীতি কনফিগার করা হলে, উভয় পাস করতে হবে. Missing/malformed ক্লেইম বন্ধ হয়ে যায় এবং কোনো নীতি ছাড়াই কলব্যাক লগইন (`not_configured`) অস্বীকার করে। বিদ্যমান শুধুমাত্র-সাবজেক্ট কনফিগারেশন অপরিবর্তিত থাকে।
- কীক্লোক সাধারনত এক্সেস টোকেনে রাজ্যের ভূমিকা ম্যাপ করে, অগত্যা ID টোকেন নয়। রিয়েলম রোল `admin` প্রয়োজনের জন্য, এই ক্লায়েন্টের জন্য একটি প্রোটোকল ম্যাপার কনফিগার করুন যাতে এটির মধ্যে `realm_access.roles` অন্তর্ভুক্ত থাকে**ID টোকেন** , তারপর `oidcAdmissionClaim` কে `{ "path": "realm_access.roles", "values": ["admin"] }` এ সেট করুন। শুধুমাত্র ভূমিকায় ভর্তি চালু করার আগে এই ক্লায়েন্টের জন্য প্রকৃত আইডি-টোকেন দাবি চেক করুন; অ্যাপ্লিকেশন অ্যাক্সেস-টোকেন ভূমিকা পড়তে না. আইডিপি-সাইড টোকেন প্রত্যাখ্যান সম্পূরক হতে পারে কিন্তু এই অ্যাপ্লিকেশন-সাইড চেকটি প্রতিস্থাপন করে না।
- সাফল্যের উপর এটা mints** ঠিক একই** 30-দিনের `auth_token` JWT পাসওয়ার্ড লগইন সমস্যা (`src/app/api/auth/login/route.ts`), তাই বাকি ড্যাশবোর্ড সেশন পাইপলাইন (স্বয়ংক্রিয়-রিফ্রেশ, কুকি ফ্ল্যাগ) অপরিবর্তিত — OIDC শুধুমাত্র কুকি কীভাবে মিন্ট করা হয় তা প্রতিস্থাপন করে, এটি যা দেয় তা নয়। IdP roles/groups তে পরিবর্তন বিদ্যমান OmniRoute সেশনগুলিকে বাতিল করে না; লগআউট, পাসওয়ার্ড ঘূর্ণন, বা সেশনের মেয়াদ এখনও তাদের জীবনকাল পরিচালনা করে।
- প্রতিটি `oidc*` সেটিং (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) এ থাকে : `PATCH /api/settings` উত্তর দেয় `400 PASSWORD_REQUIRED` যদি না বডি ম্যানেজমেন্ট পাসওয়ার্ড বহন করে (যখন `401 PASSWORD_MISMATCH` `currentPassword` ভুল হয়)। `oidcDisablePasswordLogin` পাসওয়ার্ড _login_ (`POST /api/auth/login`) প্রত্যাখ্যান করে কিন্তু সঞ্চিত পাসওয়ার্ড হ্যাশ রাখে এবং পুনরায় প্রমাণীকরণ এখনও এটির বিরুদ্ধে `currentPassword` পরীক্ষা করে।
- `corsOrigins` এবং `bruteForceProtection` `SECURITY_IMPACTING_SETTINGS_KEYS` তেও রয়েছে: শিথিল করা হয় লগইন প্রতিরক্ষাকে দুর্বল করে, তাই তারা একই `currentPassword` পুনরায় প্রমাণীকরণ করে (সিকিউরিটি ট্যাব এটির জন্য জিজ্ঞাসা করে) এবং JSON আমদানি সেগুলি বাদ দেয়।
- প্রতিটি নিরাপত্তা-নীতি কী — `SECURITY_IMPACTING_SETTINGS_KEYS` এন্ট্রি, প্রতিটি `oidc*` কী এবং ড্যাশবোর্ড সেশনের অবস্থা — হয়** শুধুমাত্র অপারেটর** `PATCH /api/settings` এ: একটি ম্যানেজ-স্কোপড API কী বা একটি `oma_` অ্যাক্সেস টোকেন `403` দিয়ে প্রত্যাখ্যান করা হয় এমনকি যখন এটি সঠিক `currentPassword` পাঠায়, এবং প্রত্যাখ্যানটি `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` এ `src/lib/api/operatorCredential.ts`) এর সাথে `settings.update_failed` হিসাবে নিরীক্ষিত হয়। সাধারণ সেটিংস (থিম, প্রদর্শন পছন্দ) একটি `manage` কী বা একটি `admin` অ্যাক্সেস টোকেনের জন্য লেখার যোগ্য থাকে। `/api/settings` এর প্রতিটি মিউটেশনের (এবং `/api/settings/require-login` এর) জন্যও `admin` অ্যাক্সেস-টোকেন স্কোপ প্রয়োজন ( `src/server/authz/accessScopes.ts` এ `ADMIN_MUTATION_EXACT_PATHS`, সঠিক-পাথ মিল); `GET` থাকে `read`, এবং অন্যান্য `/api/settings/*` সাব-রুটগুলি (প্রক্সি, কম্বো ডিফল্ট, মডেল উপনাম, কম্প্রেশন, purges...) পদ্ধতি-অনুমানিত `write` স্কোপ রাখে।
- `POST /api/settings/import-json` সেই পুনঃপ্রমাণ এড়িয়ে যায়, তাই এটি লেখার আগে `IMPORT_STRIPPED_SETTINGS_KEYS` (একই ফাইলে) প্রতিটি কী ফেলে দেয়: পাসওয়ার্ড এবং `currentPassword`, প্রতিটি `SECURITY_IMPACTING_SETTINGS_KEYS` এন্ট্রি এবং ড্যাশবোর্ড সেশনের অবস্থা (`sessionsValidAfter`, `revokedDashboardSessions`)। তাই একটি পুরানো ব্যাকআপ আমদানি করা একটি সেশনকে পুনরুজ্জীবিত করতে পারে না যা একটি পাসওয়ার্ড পরিবর্তন বা সাইন-আউট ইতিমধ্যেই শেষ হয়ে গেছে৷

#### ঐচ্ছিক TOTP টু-ফ্যাক্টর লগইন (#16619)

সেটিংস → সিকিউরিটি থেকে নথিভুক্ত করা হয়েছে; অপারেটর এটি চালু না করা পর্যন্ত বন্ধ (`src/server/auth/dashboardMfa.ts`)।

- **এটি কি কভার করে:** পাসওয়ার্ড লগইন (`POST /api/auth/login`, যার পরে `POST /api/auth/mfa/verify` প্রয়োজন) এবং `omniroute connect` (`POST /api/cli/connect`, যা একটি পাসওয়ার্ড-শুধু বিনিময় প্রত্যাখ্যান করে এবং কোডটিকে `totp` হিসাবে নেয়)।
- **এটি যা কভার করে না:** OIDC / SSO সাইন-ইন (`/api/auth/oidc/callback`) OmniRoute TOTP এর জন্য জিজ্ঞাসা করে না। এটি পরিচয় প্রদানকারীর নিজস্ব দ্বিতীয় ফ্যাক্টরের উপর নির্ভর করে, তাই OIDC সক্ষম হলে IdP এ MFA প্রয়োগ করুন।
- **পুনরুদ্ধার** (হারানো ডিভাইস, কোন পুনরুদ্ধার কোড অবশিষ্ট নেই, বা একটি ফ্যাক্টর যা আর যাচাই করা যাবে না, উদাহরণস্বরূপ `STORAGE_ENCRYPTION_KEY` পরিবর্তনের পরে):
  1. `OMNIROUTE_DISABLE_MFA=true` দিয়ে সার্ভার রিস্টার্ট করুন।
  2. হোস্টেই (লুপব্যাক পিয়ার এবং লুপব্যাক `Host`, যেমন `http://localhost:20128`), পাসওয়ার্ড দিয়ে সাইন ইন করুন। দ্বিতীয় ফ্যাক্টরটি শুধুমাত্র সেই উৎপত্তির জন্য বাদ দেওয়া হয়েছে; প্রতিটি অন্য উত্স এখনও কোড প্রয়োজন.
  3. সেটিংসে → Security → নিষ্ক্রিয় করুন, পাসওয়ার্ড লিখুন এবং কোডটি ফাঁকা রাখুন। `POST /api/auth/mfa/disable` শুধুমাত্র `code` ছাড়া একটি বডি গ্রহণ করে যখন ভেরিয়েবল সেট করা থাকে এবং হোস্ট থেকে অনুরোধ আসে; এটির জন্য এখনও ড্যাশবোর্ড সেশন এবং বর্তমান পাসওয়ার্ড প্রয়োজন, এবং `secondFactor: "recovery_switch"` এর সাথে `auth.mfa.disabled` হিসাবে নিরীক্ষিত হয়।
  4. `OMNIROUTE_DISABLE_MFA` আনসেট করুন, পুনরায় চালু করুন এবং প্রয়োজনে আবার নথিভুক্ত করুন।

## রুট শ্রেণি

`src/server/authz/types.ts` তিনটি শ্রেণি সংজ্ঞায়িত করে; যে রুট নির্ধারণযোগ্যভাবে শ্রেণিবদ্ধ করা যায় না তা `MANAGEMENT`-এ ফিরে যায়।

| শ্রেণি       | বিবরণ                                                                                                                                               | প্রয়োজনীয় প্রমাণীকরণ                                          |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| `PUBLIC`     | স্পষ্টভাবে নিরাপদ রুট — লগইন, লগআউট, status, init, health, onboarding bootstrap।                                                                    | কিছুই নয়                                                       |
| `CLIENT_API` | মডেল-পরিবেশনকারী endpoint — `/api/v1/*`, `/api/v1beta/*`, এবং উপনাম `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`। | কার্যকর `REQUIRE_API_KEY` feature flag সক্রিয় থাকলে Bearer key |
| `MANAGEMENT` | ড্যাশবোর্ড পৃষ্ঠা, settings, providers, keys, admin ও diagnostics endpoint।                                                                         | ড্যাশবোর্ড সেশন বা `manage` scope সহ Bearer                     |

কয়েকটি `MANAGEMENT` অ্যাকশন **শুধু operator-এর জন্য**: `manage` key যথেষ্ট নয়। সংরক্ষিত credentials রপ্তানি (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), লাইভ ডেটার উপর backup পুনরুদ্ধার (`dryRun=true` সহ `POST /api/db-backups/import`, id দ্বারা `POST /api/db-backups` পুনরুদ্ধার, `POST /api/settings/import-json`), এবং restore point ধ্বংস (`DELETE /api/db-backups` cleanup, এবং `PATCH /api/db-backups` কারণ এটি যে retention সংরক্ষণ করে তা প্রতিটি backup-এর পর স্বয়ংক্রিয় pruning চালায়) — এগুলোর জন্য ড্যাশবোর্ড সেশন, স্থানীয় CLI subject, অথবা লগইন নিষ্ক্রিয় থাকা প্রয়োজন। Sync token ইস্যু (`POST /api/sync/tokens`) এবং `admin` CLI access token তৈরি (`POST /api/cli/tokens`) প্রতিটি login মোডে ড্যাশবোর্ড সেশন বা স্থানীয় CLI subject দাবি করে। যেকোনো scope-এর API key এবং `oma_` access token operator credential নয়: প্রয়োজন হলে এগুলো `403` পায়। এই পরীক্ষা `src/lib/api/operatorCredential.ts`-এ (`resolveOperatorCredential()` / `requireOperatorCredential()`) আছে। লগইন সেটিং পরিবর্তনও operator-only: `POST /api/settings/require-login` (ম্যানেজমেন্ট পাসওয়ার্ড সেট করা / `requireLogin` টগল করা) একটি পাসওয়ার্ড থাকার পর শুধু সেই credentials গ্রহণ করে — প্রথম-রানের bootstrap উইন্ডো (যখনও পাসওয়ার্ড নেই) অপরিবর্তিত — এবং পাসওয়ার্ড বদলাতে ড্যাশবোর্ড সেশনকে `currentPassword` পাঠাতে হয় (না থাকলে বা ভুল হলে `403`, `settings.update_failed` হিসেবে audit হয়)। স্থানীয় CLI এবং লগইন নিষ্ক্রিয় থাকা instance পুনরুদ্ধার পথ ধরে রাখে এবং এটি ছাড়াই পাসওয়ার্ড সেট করতে পারে, কারণ দুটোই ডেটা ডিরেক্টরির মালিক হোস্টের সাথে আবদ্ধ।

## পাইপলাইন

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

বিশ্বস্ত অভ্যন্তরীণ শিরোনাম ( `src/server/authz/headers.ts` তে সংজ্ঞায়িত) হল** ইনকামিং অনুরোধ থেকে ছিনতাই** শ্রেণীবিভাগের আগে — ক্লায়েন্টরা একটি বিষয়ের ছদ্মবেশী করার জন্য `x-omniroute-auth-*` প্রাক-পপুলেট করতে পারে না।

### নীতি চুক্তি

প্রতিটি রুট ক্লাসের `src/server/authz/policies/` তে একটি নীতি রয়েছে:

- **`publicPolicy`** (`policies/public.ts`) — সবসময় `allow({ kind: "anonymous", id: "anonymous" })` ফেরত দেয়।
- **`clientApiPolicy`** (`policies/clientApi.ts`) — নির্যাস বহনকারী, `validateApiKey()` মাধ্যমে যাচাই করে। কার্যকরী `REQUIRE_API_KEY` বৈশিষ্ট্য পতাকা নিষ্ক্রিয় করা হলেই শুধুমাত্র বেনামে পড়ে। কার্যকরী পতাকাটি `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) এর মাধ্যমে সমাধান করা হয় তাই ড্যাশবোর্ড ফিচার ফ্ল্যাগ এবং এনভায়রনমেন্ট ভেরিয়েবল `/api/v1/*`, `/api/v1beta/*`, এবং উপনামগুলি ধারাবাহিকভাবে নিয়ন্ত্রণ করে; সমাধানকারী ব্যর্থতা ব্যর্থ বন্ধ. ক্লায়েন্ট API রুটে ড্যাশবোর্ড-সেশন অনুরোধের অনুমতি দেয় ( `/api/v1/models` সহ, ড্যাশবোর্ড মডেল ক্যাটালগ দ্বারা ব্যবহৃত)। যখন Entra ID SSO সক্ষম করা হয়, তখন একজন বহনকারী যা কাঠামোগতভাবে একটি Entra টোকেন (তিনটি base64url সেগমেন্ট, `RS*` alg, `kid`) SSO শাখা দ্বারা পরিচালিত হয়** আগে** `validateApiKey()` এবং এর রায় চূড়ান্ত — এটি কখনই API-কী পাথ বা ডিগ্রেড-টু-বেনামী শাখায় পড়ে না, তাই একটি পরিচয়-প্রদানকারী বিভ্রাট ওপেন অ্যাক্সেস হতে পারে না। স্ট্যাটিক API কীগুলি প্রভাবিত হয় না। [Entra ID SSO](../security/ENTRA_SSO.md) দেখুন।
- **`managementPolicy`** (`policies/management.ts`) — ড্যাশবোর্ড সেশন গ্রহণ করে, অভ্যন্তরীণ মডেল-সিঙ্ক অনুরোধ ( `/api/providers/[name]/(sync-models|models)` এর সাথে মিলে যায়), অথবা `isAuthRequired()` মিথ্যা প্রত্যাবর্তন করলে সম্পূর্ণভাবে এড়িয়ে যায়। 403 (`AUTH_001`) প্রদান করে যখন একটি Bearer টোকেন উপস্থিত থাকে কিন্তু অবৈধ, অন্যথায় 401। এছাড়াও কোনো প্রমাণীকরণ শাখা — [রুট গার্ড টিয়ার](../security/ROUTE_GUARD_TIERS.md) দেখার আগে রুট-গার্ড টিয়ারগুলি (LOCAL_ONLY / ALWAYS_PROTECTED) প্রয়োগ করে৷ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` এ LOCAL_ONLY পাথগুলি (আজ: `/api/mcp/`) নন-লুপব্যাক থেকে অ্যাক্সেস করা যেতে পারে যখন Bearer কী `manage` স্কোপ বহন করে; অন্য সব LOCAL_ONLY পাথ কঠোর-লুপব্যাক থাকে সুযোগ নির্বিশেষে।

একটি সফল নীতি `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` দিয়ে `AuthSubject` ফেরত দেয়। ডাউনস্ট্রিম হ্যান্ডলাররা প্রমাণীকরণ যুক্তি পুনরায় চালু করার পরিবর্তে `src/server/authz/assertAuth.ts` এ `assertAuth(request, "CLIENT_API")` এর মাধ্যমে এটি পড়তে পারে।

## পাবলিক রুট তালিকা

`src/shared/constants/publicApiRoutes.ts` হল সুস্পষ্ট অনুমোদিত তালিকা:

তালিকা দ্বারা বিভক্ত করা হয়** আকৃতি** , এবং বিভাজন হল লোড-বেয়ারিং (GHSA-74g9-q8f6-793h): একটি উপসর্গ `startsWith()` এর সাথে মিলে যায়, তাই এটি প্রতিটি সংলগ্ন পাথের সাথে তার অগ্রণী অক্ষর ভাগ করে নেয়। `/api/usage/om-usage` একটি উপসর্গ হিসাবে চিহ্নিত `/api/usage/om-usage<anything>` PUBLIC, এবং পরবর্তী সমাধান করে যে `/api/usage/[connectionId]` — হ্যান্ডলারের নিজস্ব কোনো প্রমাণ নেই।

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

শুধুমাত্র-পঠন রুট সর্বজনীন** শুধুমাত্র** নিরাপদ পদ্ধতির জন্য। দ্রষ্টব্য: `classifyRoute()` ফল- — PUBLIC `/api/v1/*` এবং `/api/v1beta/*` বাদ দেয় সেগুলি সর্বদা `CLIENT_API` হয় তাই Bearer-key নীতি এখনও প্রযোজ্য।

## নতুন Route যোগ করা

### Pattern 1 — পাবলিক client API endpoint (Bearer-auth)

`/api/v1/` এবং `/api/v1beta/`-এর অধীন route-গুলো স্বয়ংক্রিয়ভাবে `CLIENT_API` হিসেবে শ্রেণিবদ্ধ হয়। Middleware Bearer যাচাই প্রয়োগ করে; route handler-গুলোকে এটি পুনরায় করতে হয় না, তবে প্রয়োজন হলে subject পড়তে পারে।

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handler-এর logic
}
```

### Pattern 2 — Management endpoint (session অথবা Bearer + manage)

`src/lib/api/requireManagementAuth.ts` থেকে `requireManagementAuth()` ব্যবহার করুন:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handler-এর logic
}
```

সফল হলে `requireManagementAuth()` `null` ফেরত দেয়, অন্যথায় একটি JSON error `Response` ফেরত দেয়:

- 401 `AUTH_001` "প্রমাণীকরণ প্রয়োজন" — কোনো credentials-ই নেই
- 403 — Bearer অবৈধ **অথবা** Bearer উপস্থিত, কিন্তু key-তে `manage` / `admin` scope নেই

`hasManageScope(scopes)` `"manage"` অথবা `"admin"`-এর জন্য true ফেরত দেয়।

### Pattern 3 — পাবলিক অনুমোদন-তালিকায় যোগ করা

সুবিধা অনুযায়ী নয়, আকৃতি অনুযায়ী set নির্বাচন করুন। একটি route `PUBLIC_API_ROUTES_EXACT`-এ যায় (অথবা শুধুমাত্র GET হলে `PUBLIC_READONLY_CORS_API_ROUTES`-এ); কেবল একটি প্রকৃত subtree `PUBLIC_API_ROUTE_PREFIXES`-এ যায়, এবং সেটি **অবশ্যই `/` দিয়ে শেষ হতে হবে**। Prefix তালিকায় একটি একক route রাখলে একই প্রারম্ভিক অক্ষরবিশিষ্ট প্রতিটি সংলগ্ন path-ও প্রকাশিত হয়ে যায় — এমনকি পরে যোগ করা dynamic-segment sibling-ও (GHSA-74g9-q8f6-793h)। `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` এবং `tests/unit/authz/classify.test.ts`-এ unit test হালনাগাদ করুন।

## স্কোপসমূহ

তিনটি নেমস্পেস। প্রতিটি পরীক্ষক কেবল তার নিজস্ব স্ট্রিং পড়ে। পাশাপাশি তুলনা, যার মধ্যে কেন `manage` `read:compression`-এর জন্য `scopeMatches`-এ ব্যর্থ হয় এবং কেন একটি `read` অ্যাক্সেস টোকেন `PATCH /api/keys/{id}` করতে পারে না, তা এখানে রয়েছে:
[তিনটি স্কোপ নেমস্পেস](../frameworks/MCP-SERVER.md#three-scope-namespaces)।

API কিগুলো একটি `scopes` অ্যারে বহন করে (`api_keys.scopes`-এ JSON হিসেবে সংরক্ষিত, দেখুন `src/lib/db/apiKeys.ts`)।

### ব্যবস্থাপনা স্কোপ

- `manage` / `admin` — `hasManageScope`। ব্যবস্থাপনা API রুটগুলোতে Bearer অ্যাক্সেস।
- `mcp:connect`, `self:usage`, `self:account-quota`, এবং
  `policy:bypass-provider-quota` হলো সংযোজনধর্মী হুবহু-মিল স্কোপ। এগুলো
  `MANAGEMENT_API_KEY_SCOPES`-এর বাইরে থাকে। `mcp:connect` কেবল
  `/api/mcp/` নন-লুপব্যাক ব্যতিক্রমটি উন্মুক্ত করে।

### MCP টুল স্কোপসমূহ

ক্যাটালগ এবং মেলানোর নিয়মাবলি (অভিন্ন স্ট্রিং, অথবা `*` দিয়ে শেষ হওয়া কোনো মঞ্জুরকৃত স্কোপ):
[MCP টুল স্কোপসমূহ](../frameworks/MCP-SERVER.md#mcp-tool-scopes)।
`src/shared/constants/mcpScopes.ts`-এর `MCP_SCOPE_LIST` হলো মূল টাইপযুক্ত
উপসেট, সম্পূর্ণ ক্যাটালগটি নয়। `resolveCallerScopeContext()` MCP প্রমাণীকরণ তথ্য, অনুরোধের মেটাডেটা, অথবা `OMNIROUTE_MCP_SCOPES` থেকে স্কোপ নির্ধারণ করার পর
`open-sse/mcp-server/scopeEnforcement.ts`-এ প্রয়োগ কার্যকর হয়।
`OMNIROUTE_MCP_ENFORCE_SCOPES=true` না হলে এটি নিষ্ক্রিয় থাকে।

### অ্যাক্সেস-টোকেন স্কোপসমূহ

`oma_live_…` টোকেনে `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) অনুযায়ী র্যাঙ্ক করা। এই র্যাঙ্ক কেবল অ্যাক্সেস-টোকেন
ক্রেডেনশিয়ালের ক্ষেত্রেই প্রযোজ্য। দেখুন [ব্যবস্থাপনা প্রমাণীকরণ](../guides/MANAGEMENT-AUTH.md)।

## Auth Required টগল

`src/shared/utils/apiAuth.ts`-এর `isAuthRequired()` সিদ্ধান্ত নেয় কোনো অনুরোধের জন্য **আদৌ** কোনো প্রমাণীকরণ প্রয়োগ হবে কি না:

- `settings.requireLogin === false` → প্রমাণীকরণ বিশ্বব্যাপীভাবে নিষ্ক্রিয় হয়, তবে always-protected tier ([Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) এবং যে কলগুলো এমন credential ইস্যু করে যা গ্রহণ করা হয়, সেগুলো বাদে — লগইন সক্রিয় থাকলে যে credential লাগে সেটিই লাগে: sync token ইস্যু, যেকোনো scope-এ CLI access token তৈরি, এবং `manage`/`admin` scope-সহ API key তৈরি, ওই scope কোনো key-কে দেওয়া, বা এমন key পুনরুৎপাদন বা প্রকাশ (`src/lib/api/requireManagementAuth.ts`-এর `requireCredentialForManagementScopedKey()`)। শুধু inference-এর জন্য key খোলা থাকে।
- কোনো পাসওয়ার্ড কনফিগার না থাকে **এবং** `INITIAL_PASSWORD` env var না থাকে → bootstrap মোড onboarding wizard ও loopback অনুরোধকে অনুমতি দেয়, কিন্তু উন্মুক্ত network অনুরোধগুলোর এখনো credential লাগে।
- যেকোনো DB ত্রুটি → fail closed (secure-by-default)।

Client API key প্রয়োগ `src/shared/utils/featureFlags.ts`-এর `isRequireApiKeyEnabled()` ব্যবহার করে, সরাসরি `process.env.REQUIRE_API_KEY` পড়ে না। এটি deployed instance-এর জন্য গুরুত্বপূর্ণ: Dashboard → Feature Flags-এ `REQUIRE_API_KEY` টগল করলে একটি DB override সংরক্ষিত হয় এবং তাৎক্ষণিকভাবে `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` এবং এই helper ভাগ করা অন্যান্য client-API auth পরীক্ষায় প্রভাব ফেলে। Feature flag store পড়া না গেলে client API auth fail closed হয় এবং একটি key চায়।

## ব্রেকিং পরিবর্তন — v3.8.0

`/api/v1/agents/tasks/*` এবং `/api/resilience/model-cooldowns` এন্ডপয়েন্টগুলোর জন্য **এখন ম্যানেজমেন্ট auth আবশ্যক** (commit `588a0333`)। আগে `manage` স্কোপ ছাড়া একটি সাধারণ API কী পাঠানো ক্লায়েন্টগুলো এখন `403` পায়। মাইগ্রেশন: API Keys dashboard-এ কীটিকে `manage` স্কোপ দিন, অথবা লগইন করা dashboard session ব্যবহার করুন।

## আচরণগত পরিবর্তন — v3.8.2

`/api/mcp/*` (রিমোট MCP server) এখনও ডিফল্টভাবে LOCAL_ONLY, তবে `Authorization: Bearer <api-key>` header-এ `manage` স্কোপ থাকলে এখন non-loopback রিকোয়েস্ট গ্রহণ করে। এই ব্যতিক্রমটি `src/server/authz/routeGuard.ts`-এর `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES`-এর মাধ্যমে প্রতিটি path-এর জন্য স্পষ্টভাবে নিয়ন্ত্রিত; পাশাপাশি থাকা LOCAL_ONLY prefix `/api/cli-tools/runtime/*` ইচ্ছাকৃতভাবে bypass করা যায় না, কারণ এটি যেকোনো subprocess চালু করতে পারে। non-loopback থেকে `/api/mcp/*`-এ আসা anonymous রিকোয়েস্টগুলো এখনও `403 LOCAL_ONLY` ফেরত দেয়—যেকোনো নতুন LOCAL_ONLY path-এর ডিফল্ট কঠোর loopback-ই থাকে। দেখুন [রুট গার্ড স্তরসমূহ](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)।

## টেস্টিং

- ইউনিট টেস্ট: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`।
- পাবলিক allowlist: `tests/unit/public-api-routes.test.ts`।
- নির্দিষ্ট টেস্ট চালান: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`।

## ডিবাগিং

পাইপলাইন সর্বদা এর সাথে প্রতিক্রিয়াগুলি স্ট্যাম্প করে:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

প্রমাণীকৃত অনুরোধের জন্য আপস্ট্রিম (হ্যান্ডলার-সাইড) অনুরোধ শিরোনামগুলিও অন্তর্ভুক্ত করে:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

মিডলওয়্যারটি বাইপাস করা হলে — হ্যান্ডলারের ভিতরে `assertAuth(req, expectedClass)` ব্যবহার করুন এটি `AUTHZ_NOT_INITIALIZED` কোড সহ `AuthzAssertionError` ছুঁড়ে দেয় (পরীক্ষায় কনফিগারেশন রিগ্রেশন ধরার জন্য সহায়ক)।

## আরও দেখুন

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — প্রতিটি এন্ডপয়েন্টের auth মার্কার
- [COMPLIANCE.md](../security/COMPLIANCE.md) — auth ইভেন্টগুলোর জন্য অডিট লগ
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — তিনটি scope namespace এবং MCP tool-scope ক্যাটালগ
- সোর্স: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
