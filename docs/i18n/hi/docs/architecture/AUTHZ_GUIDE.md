# Authorization Guide (हिन्दी)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **सत्य का स्रोत:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **अंतिम बार अपडेट किया गया:** 2026-09-22 — स्कोप नेमस्पेस MCP-SERVER.md की ओर इशारा करते हैं

ओम्नीराउट में एक रूट-जागरूक प्रमाणीकरण पाइपलाइन है जो हर एपीआई अनुरोध को नियंत्रित करती है। वर्गीकरण **निर्धारित** और **फेल-क्लोज्ड** है — जो कुछ भी वर्गीकृत नहीं किया जा सकता है वह `MANAGEMENT` के रूप में समाप्त होता है और एक सत्र या प्रबंधन-ग्रेड टोकन की मांग करता है। यह पृष्ठ उन इंजीनियरों के लिए मॉडल की व्याख्या करता है जो रूट्स का रखरखाव कर रहे हैं या नए एंडपॉइंट्स डिज़ाइन कर रहे हैं।

![AuthZ पाइपलाइन (3 रूट क्लास + नीति मूल्यांकन)](../diagrams/exported/authz-pipeline.svg)

> स्रोत: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## दो प्रामाणिक मोड

### 1. API कुंजी (वाहक)

जब कुंजी में `manage` दायरा होता है तो इसका उपयोग OpenAI/Anthropic/Gemini-compatible क्लाइंट APIs और कुछ प्रबंधन मार्गों के लिए किया जाता है।

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` में `isValidApiKey()` / `extractApiKey()` द्वारा मान्य और `src/shared/utils/apiAuth.ts` के माध्यम से पुनः निर्यात किया गया। सत्यापनकर्ता `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars को लगातार पासथ्रू कुंजी (इश्यू #1350) के रूप में भी स्वीकार करता है।

### 2. डैशबोर्ड सत्र (auth_token कुकी)

डैशबोर्ड पृष्ठों और व्यवस्थापक संचालन के लिए।

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

कुकी एक सत्र तभी होती है जब JWT सत्यापित करता है** और** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) वहन करता है। कुकी (डैशबोर्ड रूट गार्ड (`isDashboardSessionAuthenticated()`), ऑथ्ज़ पाइपलाइन रिफ्रेश, WebSocket हैंडशेक, लाइव सर्वर, `/api/settings/require-login`, `/api/auth/status`) का प्रत्येक उपभोक्ता उस सहायक के माध्यम से जाता है। `JWT_SECRET` के साथ हस्ताक्षरित अन्य JWTs मौजूद हैं — Cursor CLI पासथ्रू टकसाल — कुंजी धारकों के लिए `iss "omniroute" / aud "cursor-cli"` टोकन और कभी भी सत्र (#13298) नहीं होते हैं।

`src/shared/utils/apiAuth.ts` में `isDashboardSessionAuthenticated()` द्वारा सत्यापित। जब 30 दिन के जीवनकाल में 7 दिन से कम समय बचा हो तो पाइपलाइन JWT को स्वतः रिफ्रेश कर देती है।

एक सत्र अपने 30 दिन पूरे होने से पहले भी समाप्त हो सकता है, क्योंकि प्रत्येक मिंटर `mintDashboardSessionToken` (एक जारी समय `iat` और एक आईडी `jti`) से गुजरता है और सत्यापनकर्ता दो सेटिंग्स की जाँच करता है: `sessionsValidAfter`, एक पासवर्ड परिवर्तन द्वारा सेट किया जाता है इसलिए जारी किया गया प्रत्येक सत्र सत्यापन बंद करने से पहले (पासवर्ड बदलने वाले ब्राउज़र को एक ताज़ा कुकी मिलती है), और `revokedDashboardSessions`, जिसमें `POST /api/auth/logout` साइन-आउट सत्र के `jti` जोड़ता है। पुराने रिलीज़ द्वारा बनाए गए सत्रों पर कोई दावा नहीं किया जाता है और पहला पासवर्ड बदलने तक वैध रहते हैं। यदि सेटिंग्स को पढ़ा नहीं जा सकता है, तो सत्र पर भरोसा नहीं किया जाता है।

कुछ प्रबंधन मार्ग स्वीकार करते हैं** दोनों में से एक** मोड: कुकी OR `Bearer <key>` जब API कुंजी में `manage` (या `admin`) दायरा होता है। यह वही है जो v3.8 में जोड़े गए " API कॉल के माध्यम से कॉन्फ़िगर करने योग्य" वर्कफ़्लो को सक्षम बनाता है।

#### वैकल्पिक OIDC लॉगिन गेट (#6973)

डैशबोर्ड एडमिन लॉगिन भी एक का समर्थन करता है** में चुनें** डिफ़ॉल्ट पासवर्ड लॉगिन के साथ OIDC (OpenID कनेक्ट) प्रवाह — पासवर्ड लॉगिन कभी नहीं हटाया जाता है, केवल पूरक होता है:

- `settings.oidcEnabled === true` तक अक्षम** और** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` सभी कॉन्फ़िगर किए गए हैं (सेटिंग्स → प्रामाणिक)। `GET /api/auth/oidc/login` अन्यथा `400` लौटाता है।
- `GET /api/auth/oidc/login` जारीकर्ता के `/.well-known/openid-configuration` से `authorization_endpoint` खोजता है ( `<issuer>/authorize` पर वापस आता है), आने वाले अनुरोध (`x-forwarded-proto` -aware) से रीडायरेक्ट URI बनाता है, और `httpOnly` `oidc_state` कुकी में संग्रहीत यादृच्छिक `state` के साथ IdP पर रीडायरेक्ट करता है।
- `GET /api/auth/oidc/callback` `state` मान्य करता है, प्राधिकरण कोड का आदान-प्रदान करता है, और `issuer`/`audience` जांच के साथ जारीकर्ता के JWKS (`jose` के `createRemoteJWKSet`, प्रति JWKS URI कैश्ड) के माध्यम से ID टोकन के हस्ताक्षर को सत्यापित करता है। डैशबोर्ड प्रवेश के लिए एक गैर-रिक्त `oidcAllowedSubjects` सूची, एक `oidcAdmissionClaim` नीति या दोनों की आवश्यकता होती है। विषय सूची `sub` या `email` तभी मेल खाती है जब `email_verified === true`। वैकल्पिक दावा नीति एक डॉट-पृथक आईडी-टोकन दावा पथ (उदाहरण के लिए, `realm_access.roles`) और स्वीकृत मानों की एक श्रृंखला लेती है; हल किया गया दावा कम से कम एक स्वीकृत मान वाली स्ट्रिंग्स की एक श्रृंखला होनी चाहिए। यदि दोनों नीतियां कॉन्फ़िगर की गई हैं, तो दोनों को पास होना होगा। Missing/malformed दावे विफल हो जाते हैं, और किसी भी नीति के बिना कॉलबैक लॉगिन (`not_configured`) से इनकार कर देता है। मौजूदा केवल-विषय कॉन्फ़िगरेशन अपरिवर्तित जारी रहेगा।
- कीक्लोक आम तौर पर पहुंच टोकन में दायरे की भूमिकाओं को मैप करता है, जरूरी नहीं कि ID टोकन हो। दायरे की भूमिका `admin` की आवश्यकता के लिए, इस क्लाइंट के लिए एक प्रोटोकॉल मैपर कॉन्फ़िगर करें जिसमें `realm_access.roles` शामिल है**ID टोकन** , फिर `oidcAdmissionClaim` को `{ "path": "realm_access.roles", "values": ["admin"] }` पर सेट करें। केवल-भूमिका प्रवेश सक्षम करने से पहले इस ग्राहक के लिए वास्तविक आईडी-टोकन दावे की जाँच करें; एप्लिकेशन एक्सेस-टोकन भूमिकाएँ नहीं पढ़ता है। आईडीपी-साइड टोकन इनकार पूरक हो सकता है लेकिन इस एप्लिकेशन-साइड चेक को प्रतिस्थापित नहीं करता है।
- सफलता पर यह टकसाल बन जाता है** बिलकुल सटीक** 30-दिवसीय `auth_token` JWT पासवर्ड लॉगिन समस्याएँ (`src/app/api/auth/login/route.ts`), इसलिए शेष डैशबोर्ड सत्र पाइपलाइन (ऑटो-रिफ्रेश, कुकी फ़्लैग) अपरिवर्तित है — OIDC केवल कुकी को ढालने के तरीके को प्रतिस्थापित करता है, न कि यह कि यह क्या अनुदान देता है। IdP roles/groups में परिवर्तन मौजूदा OmniRoute सत्रों को अमान्य नहीं करते हैं; लॉगआउट, पासवर्ड रोटेशन, या सत्र समाप्ति अभी भी उनके जीवनकाल को नियंत्रित करती है।
- प्रत्येक `oidc*` सेटिंग (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) में है: `PATCH /api/settings` `400 PASSWORD_REQUIRED` उत्तर देता है जब तक कि शरीर प्रबंधन पासवर्ड `currentPassword` (`401 PASSWORD_MISMATCH` जब यह गलत हो) के रूप में नहीं रखता है। `oidcDisablePasswordLogin` पासवर्ड _लॉगिन_ (`POST /api/auth/login`) को अस्वीकार करता है लेकिन संग्रहीत पासवर्ड हैश रखता है, और पुनः प्रमाणीकरण अभी भी इसके विरुद्ध `currentPassword` जांच करता है।
- `corsOrigins` और `bruteForceProtection` भी `SECURITY_IMPACTING_SETTINGS_KEYS` में हैं: या तो ढीला करने से लॉगिन सुरक्षा कमजोर हो जाती है, इसलिए वे वही `currentPassword` पुनः प्रमाणीकरण करते हैं (सुरक्षा टैब इसके लिए पूछता है) और JSON आयात उन्हें हटा देता है।
- प्रत्येक सुरक्षा-नीति कुंजी — `SECURITY_IMPACTING_SETTINGS_KEYS` प्रविष्टियाँ, प्रत्येक `oidc*` कुंजी और डैशबोर्ड सत्र स्थिति — है** केवल ऑपरेटर** `PATCH /api/settings` पर: एक प्रबंधन-स्कोप वाली API कुंजी या `oma_` एक्सेस टोकन को `403` के साथ अस्वीकार कर दिया जाता है, भले ही वह सही `currentPassword` भेजता हो, और इनकार को `reason: OPERATOR_REQUIRED` ( `src/lib/api/operatorCredential.ts` में`requireOperatorCredential()` ) के साथ `settings.update_failed` के रूप में ऑडिट किया जाता है। सामान्य सेटिंग्स (थीम, डिस्प्ले प्राथमिकताएं) `manage` कुंजी या `admin` एक्सेस टोकन के लिए लिखने योग्य रहती हैं। `/api/settings` के प्रत्येक उत्परिवर्तन (और `/api/settings/require-login` के) को भी `admin` एक्सेस-टोकन स्कोप ( `src/server/authz/accessScopes.ts` में`ADMIN_MUTATION_EXACT_PATHS`, सटीक-पथ मिलान) की आवश्यकता होती है; `GET` `read` रहता है, और अन्य `/api/settings/*` उप-मार्ग (प्रॉक्सी, कॉम्बो डिफ़ॉल्ट, मॉडल उपनाम, संपीड़न, पर्ज ...) विधि-अनुमानित `write` गुंजाइश रखते हैं।
- `POST /api/settings/import-json` उस पुनः प्रमाणीकरण को छोड़ देता है, इसलिए यह लिखने से पहले `IMPORT_STRIPPED_SETTINGS_KEYS` (समान फ़ाइल) में प्रत्येक कुंजी को छोड़ देता है: पासवर्ड और `currentPassword`, प्रत्येक `SECURITY_IMPACTING_SETTINGS_KEYS` प्रविष्टि, और डैशबोर्ड सत्र स्थिति (`sessionsValidAfter`, `revokedDashboardSessions`)। इसलिए पुराने बैकअप को आयात करने से उस सत्र को पुनर्जीवित नहीं किया जा सकता है जिसमें पासवर्ड बदल गया हो या साइन-आउट पहले ही समाप्त हो गया हो।

#### वैकल्पिक TOTP दो-कारक लॉगिन (#16619)

सेटिंग्स → सुरक्षा से नामांकित; जब तक ऑपरेटर इसे चालू नहीं कर देता (`src/server/auth/dashboardMfa.ts`)।

- **इसमें क्या शामिल है:** पासवर्ड लॉगिन (`POST /api/auth/login`, जिसे तब `POST /api/auth/mfa/verify` आवश्यकता होती है) और `omniroute connect` (`POST /api/cli/connect`, जो केवल-पासवर्ड एक्सचेंज से इंकार कर देता है और कोड को `totp` के रूप में लेता है)।
- **इसमें क्या शामिल नहीं है:** OIDC / SSO साइन-इन (`/api/auth/oidc/callback`) OmniRoute TOTP के लिए नहीं पूछता है। यह पहचान प्रदाता के अपने दूसरे कारक पर निर्भर करता है, इसलिए यदि OIDC सक्षम है तो IdP में MFA लागू करें।
- **वसूली** (डिवाइस खो गया है, कोई पुनर्प्राप्ति कोड नहीं बचा है, या कोई ऐसा कारक जिसे अब सत्यापित नहीं किया जा सकता है, उदाहरण के लिए `STORAGE_ENCRYPTION_KEY` बदलने के बाद):
  1. `OMNIROUTE_DISABLE_MFA=true` के साथ सर्वर को पुनरारंभ करें।
  2. होस्ट पर ही (लूपबैक पीयर और लूपबैक `Host`, जैसे `http://localhost:20128`), पासवर्ड के साथ साइन इन करें। दूसरा कारक केवल उस मूल के लिए छोड़ दिया गया है; प्रत्येक अन्य मूल को अभी भी कोड की आवश्यकता है।
  3. सेटिंग्स → सुरक्षा → अक्षम में, पासवर्ड दर्ज करें और कोड को खाली छोड़ दें। `POST /api/auth/mfa/disable` किसी बॉडी को `code` बिना तभी स्वीकार करता है जब वेरिएबल सेट होता है और अनुरोध होस्ट से आता है; इसके लिए अभी भी डैशबोर्ड सत्र और वर्तमान पासवर्ड की आवश्यकता है, और इसे `secondFactor: "recovery_switch"` के साथ `auth.mfa.disabled` के रूप में ऑडिट किया जाता है।
  4. `OMNIROUTE_DISABLE_MFA` को अनसेट करें, पुनरारंभ करें, और यदि आवश्यक हो तो फिर से नामांकन करें।

## रूट वर्ग

`src/server/authz/types.ts` तीन वर्ग परिभाषित करता है; जो रूट निर्धारक रूप से वर्गीकृत नहीं हो सकता वह `MANAGEMENT` पर लौट जाता है।

| वर्ग         | विवरण                                                                                                                                               | आवश्यक प्रमाणीकरण                                                 |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| `PUBLIC`     | स्पष्ट रूप से सुरक्षित रूट — लॉगिन, लॉगआउट, स्थिति, इनिट, हेल्थ, ऑनबोर्डिंग बूटस्ट्रैप।                                                             | कोई नहीं                                                          |
| `CLIENT_API` | मॉडल-सर्विंग एंडपॉइंट — `/api/v1/*`, `/api/v1beta/*`, साथ में उपनाम `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`। | प्रभावी `REQUIRE_API_KEY` फ़ीचर फ़्लैग सक्षम होने पर Bearer कुंजी |
| `MANAGEMENT` | डैशबोर्ड पेज, सेटिंग्स, प्रदाता, कुंजियाँ, एडमिन और डायग्नोस्टिक्स एंडपॉइंट।                                                                        | डैशबोर्ड सेशन या `manage` स्कोप वाला Bearer                       |

कुछ `MANAGEMENT` क्रियाएँ **केवल-ऑपरेटर** हैं: `manage` कुंजी पर्याप्त नहीं है। संग्रहीत क्रेडेंशियल्स का निर्यात
(`GET /api/settings/export-json`, `GET /api/db-backups/export`,
`GET /api/db-backups/exportAll`), लाइव डेटा पर बैकअप रीस्टोर
(`POST /api/db-backups/import` जिसमें `dryRun=true` भी शामिल है, `POST /api/db-backups` id से रीस्टोर,
`POST /api/settings/import-json`), रीस्टोर पॉइंट्स को नष्ट करना (`DELETE /api/db-backups` सफ़ाई,
और `PATCH /api/db-backups` क्योंकि यह जो retention सहेजता है वह हर बैकअप के बाद स्वचालित प्रूनिंग चलाता है) —
इन सभी के लिए डैशबोर्ड सेशन, स्थानीय CLI सब्जेक्ट, या लॉगिन अक्षम होना आवश्यक है। sync टोकन जारी करना
(`POST /api/sync/tokens`) और `admin` CLI एक्सेस टोकन बनाना (`POST /api/cli/tokens`) हर लॉगिन मोड में
डैशबोर्ड सेशन या स्थानीय CLI सब्जेक्ट माँगते हैं। किसी भी स्कोप की API कुंजियाँ और `oma_` एक्सेस टोकन
ऑपरेटर क्रेडेंशियल नहीं हैं: जब भी ऐसा क्रेडेंशियल ज़रूरी हो, उन्हें `403` मिलता है। यह जाँच
`src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` /
`requireOperatorCredential()`) में है। लॉगिन सेटिंग्स बदलना भी केवल-ऑपरेटर है:
`POST /api/settings/require-login` (प्रबंधन पासवर्ड सेट करें / `requireLogin` टॉगल करें) एक बार पासवर्ड मौजूद
होने पर केवल इन्हीं क्रेडेंशियल्स को स्वीकार करता है — पहली-बार की बूटस्ट्रैप विंडो (जब तक पासवर्ड न हो)
अपरिवर्तित है — और पासवर्ड बदलने के लिए डैशबोर्ड सेशन को `currentPassword` भेजना होगा (न होने या गलत होने
पर `403`, `settings.update_failed` के रूप में ऑडिट)। स्थानीय CLI और लॉगिन-अक्षम इंस्टेंस रिकवरी पथ बनाए
रखते हैं और उसके बिना पासवर्ड सेट कर सकते हैं, क्योंकि दोनों डेटा डायरेक्टरी के मालिक होस्ट से बँधे हैं।

## पाइपलाइन

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

विश्वसनीय आंतरिक शीर्षलेख ( `src/server/authz/headers.ts` में परिभाषित) हैं** आने वाले अनुरोधों से हटा दिया गया** वर्गीकरण से पहले — क्लाइंट किसी विषय का प्रतिरूपण करने के लिए `x-omniroute-auth-*` पूर्व-पॉप्युलेट नहीं कर सकते हैं।

### नीति अनुबंध

प्रत्येक रूट क्लास की `src/server/authz/policies/` में एक नीति होती है:

- **`publicPolicy`** (`policies/public.ts`) — हमेशा `allow({ kind: "anonymous", id: "anonymous" })` लौटाता है।
- **`clientApiPolicy`** (`policies/clientApi.ts`) — बियरर को निकालता है, `validateApiKey()` के माध्यम से मान्य करता है। प्रभावी `REQUIRE_API_KEY` सुविधा ध्वज अक्षम होने पर ही यह गुमनाम हो जाता है। प्रभावी ध्वज को `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) के माध्यम से हल किया जाता है, इसलिए डैशबोर्ड फ़ीचर फ़्लैग और पर्यावरण चर लगातार `/api/v1/*`, `/api/v1beta/*` और उपनामों को नियंत्रित करते हैं; रिज़ॉल्वर विफलताएँ विफल बंद हो गईं। क्लाइंट API मार्गों पर डैशबोर्ड-सत्र अनुरोधों की अनुमति देता है (डैशबोर्ड मॉडल कैटलॉग द्वारा प्रयुक्त `/api/v1/models` सहित)। जब Entra ID SSO सक्षम होता है, तो एक बियरर जो संरचनात्मक रूप से एक Entra टोकन (तीन बेस 64url खंड, `RS*` alg, `kid`) होता है, को SSO शाखा द्वारा नियंत्रित किया जाता है** पहले** `validateApiKey()` और इसका फैसला अंतिम है — यह कभी भी एपीआई-कुंजी पथ या डीग्रेड-टू-अनाम शाखा से नहीं गुजरता है, इसलिए एक पहचान-प्रदाता आउटेज खुली पहुंच नहीं बन सकता है। स्टेटिक API कुंजियाँ अप्रभावित हैं। [एन्ट्रा ID SSO](../security/ENTRA_SSO.md) देखें।
- **`managementPolicy`** (`policies/management.ts`) — डैशबोर्ड सत्र, आंतरिक मॉडल-सिंक अनुरोध ( `/api/providers/[name]/(sync-models|models)` के विरुद्ध मिलान) स्वीकार करता है, या यदि `isAuthRequired()` गलत रिटर्न देता है तो पूरी तरह से छोड़ देता है। जब बियरर टोकन मौजूद हो लेकिन अमान्य हो तो 403 (`AUTH_001`) लौटाता है, अन्यथा 401 लौटाता है। किसी भी प्राधिकरण शाखा — से पहले रूट-गार्ड टियर (LOCAL_ONLY / ALWAYS_PROTECTED) को लागू करता है [, रूट गार्ड टियर](../security/ROUTE_GUARD_TIERS.md) देखें। `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` में LOCAL_ONLY पथ (आज: `/api/mcp/`) को गैर-लूपबैक से एक्सेस किया जा सकता है जब बियरर कुंजी `manage` स्कोप रखती है; अन्य सभी LOCAL_ONLY पथ दायरे की परवाह किए बिना सख्त-लूपबैक बने रहते हैं।

एक सफल नीति `AuthSubject` `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` के साथ लौटाती है। डाउनस्ट्रीम हैंडलर ऑथ लॉजिक को दोबारा चलाने के बजाय इसे `src/server/authz/assertAuth.ts` में `assertAuth(request, "CLIENT_API")` के माध्यम से पढ़ सकते हैं।

## सार्वजनिक मार्गों की सूची

`src/shared/constants/publicApiRoutes.ts` स्पष्ट अनुमति सूची है:

सूची विभाजित है** आकार** , और विभाजन लोड-असर (GHSA-74g9-q8f6-793h) है: एक उपसर्ग `startsWith()` से मेल खाता है, इसलिए यह अपने प्रमुख पात्रों को साझा करने वाले प्रत्येक आसन्न पथ से भी मेल खाता है। `/api/usage/om-usage` एक उपसर्ग के रूप में `/api/usage/om-usage<anything>` PUBLIC के रूप में चिह्नित किया गया है, और नेक्स्ट इसे `/api/usage/[connectionId]` — एक हैंडलर के रूप में हल करता है जिसका अपना कोई प्रमाणीकरण नहीं है।

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

केवल पढ़ने योग्य मार्ग सार्वजनिक हैं** केवल** सुरक्षित तरीकों के लिए. ध्यान दें: `classifyRoute()` `/api/v1/*` और `/api/v1beta/*` PUBLIC फ़ॉल-थ्रू — से बाहर रखता है, जो हमेशा `CLIENT_API` होते हैं इसलिए बियरर-कुंजी नीति अभी भी लागू होती है।

## नया Route जोड़ना

### पैटर्न 1 — सार्वजनिक client API endpoint (Bearer-auth)

`/api/v1/` और `/api/v1beta/` के अंतर्गत आने वाले routes अपने-आप `CLIENT_API` के रूप में वर्गीकृत होते हैं। middleware Bearer जाँच लागू करता है; route handlers को इसे दोबारा करने की आवश्यकता नहीं है, लेकिन उपयोगी होने पर वे subject को पढ़ सकते हैं।

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handler का logic
}
```

### पैटर्न 2 — प्रबंधन endpoint (session या Bearer + manage)

`src/lib/api/requireManagementAuth.ts` से `requireManagementAuth()` का उपयोग करें:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handler का logic
}
```

सफलता पर `requireManagementAuth()` `null` लौटाता है, अन्यथा JSON त्रुटि वाला `Response`:

- 401 `AUTH_001` "प्रमाणीकरण आवश्यक है" — कोई भी credentials मौजूद नहीं
- 403 — अमान्य Bearer **या** Bearer मौजूद है, लेकिन key में `manage` / `admin` scope नहीं है

`hasManageScope(scopes)` `"manage"` या `"admin"` के लिए true लौटाता है।

### पैटर्न 3 — सार्वजनिक अनुमति-सूची में जोड़ना

set को सुविधा के आधार पर नहीं, बल्कि आकार के आधार पर चुनें। एक route को `PUBLIC_API_ROUTES_EXACT` में रखें (या केवल GET के लिए `PUBLIC_READONLY_CORS_API_ROUTES` में); केवल वास्तविक subtree को `PUBLIC_API_ROUTE_PREFIXES` में रखें, और वह **`/` पर समाप्त होना ही चाहिए**। किसी एकल route को prefix सूची में रखने से समान आरंभिक वर्णों वाला हर निकटवर्ती path भी सार्वजनिक हो जाता है — इसमें बाद में जोड़े गए dynamic-segment siblings भी शामिल हैं (GHSA-74g9-q8f6-793h)। `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` और `tests/unit/authz/classify.test.ts` में unit tests अपडेट करें।

## स्कोप्स

तीन नेमस्पेस। प्रत्येक चेकर केवल अपनी स्ट्रिंग्स पढ़ता है। साइड-बाय-साइड तुलना, जिसमें यह भी शामिल है कि `manage` `read:compression` के लिए `scopeMatches` में क्यों विफल होता है और एक `read` एक्सेस टोकन `PATCH /api/keys/{id}` क्यों नहीं कर सकता, [तीन स्कोप नेमस्पेस](../frameworks/MCP-SERVER.md#three-scope-namespaces) में है।

एपीआई कुंजियों में एक `scopes` ऐरे होता है (जो `api_keys.scopes` में JSON के रूप में संग्रहीत होता है, देखें `src/lib/db/apiKeys.ts`)।

### प्रबंधन स्कोप

- `manage` / `admin` — `hasManageScope`। प्रबंधन एपीआई राउट्स तक बेयरर एक्सेस।
- `mcp:connect`, `self:usage`, `self:account-quota`, और
  `policy:bypass-provider-quota` योगात्मक सटीक-मैच स्कोप्स हैं। वे `MANAGEMENT_API_KEY_SCOPES` के बाहर स्थित हैं। `mcp:connect` केवल `/api/mcp/` नॉन-लूपबैक कार्व-आउट खोलता है।

### MCP टूल स्कोप्स

कैटलॉग और मिलान नियम (समान स्ट्रिंग, या `*` में समाप्त होने वाला एक स्वीकृत स्कोप):
[MCP टूल स्कोप्स](../frameworks/MCP-SERVER.md#mcp-tool-scopes)।
`src/shared/constants/mcpScopes.ts` में `MCP_SCOPE_LIST` मूल टाइप किया गया सबसेट है, न कि वह पूरा कैटलॉग। प्रवर्तन
`open-sse/mcp-server/scopeEnforcement.ts` में `resolveCallerScopeContext()` द्वारा MCP प्रमाणीकरण जानकारी, अनुरोध मेटाडेटा, या `OMNIROUTE_MCP_SCOPES` से स्कोप्स को हल करने के बाद चलता है।
यह तब तक बंद रहता है जब तक `OMNIROUTE_MCP_ENFORCE_SCOPES=true` नहीं होता।

### एक्सेस-टोकन स्कोप्स

`oma_live_…` टोकन पर `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) द्वारा रैंक किए गए। यह रैंक केवल एक्सेस-टोकन क्रेडेंशियल पर लागू होती है। देखें [प्रबंधन प्रमाणीकरण](../guides/MANAGEMENT-AUTH.md)।

## Auth Required टॉगल

`src/shared/utils/apiAuth.ts` में `isAuthRequired()` तय करता है कि किसी अनुरोध के लिए **कोई भी** प्रमाणीकरण लागू होना चाहिए या नहीं:

- `settings.requireLogin === false` → प्रमाणीकरण वैश्विक रूप से अक्षम है, सिवाय हमेशा-सुरक्षित टियर (देखें [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) और उन कॉल्स के जो वह क्रेडेंशियल देती हैं जिसे वह स्वीकार करता है — इनके लिए वही क्रेडेंशियल चाहिए जो लॉगिन चालू होने पर चाहिए: sync टोकन जारी करना, किसी भी स्कोप पर CLI एक्सेस टोकन बनाना, और `manage`/`admin` स्कोप वाली API कुंजी बनाना, किसी कुंजी को वह स्कोप देना, या ऐसी कुंजी को पुनः जनरेट या प्रकट करना (`src/lib/api/requireManagementAuth.ts` में `requireCredentialForManagementScopedKey()`)। केवल-इनफ़रेंस कुंजियाँ खुली रहती हैं।
- कोई पासवर्ड कॉन्फ़िगर नहीं **और** `INITIAL_PASSWORD` env var नहीं → बूटस्ट्रैप मोड ऑनबोर्डिंग विज़ार्ड और loopback अनुरोधों की अनुमति देता है, लेकिन बाहर खुले नेटवर्क अनुरोधों को अब भी क्रेडेंशियल चाहिए।
- कोई भी DB त्रुटि → बंद होकर विफल होता है (डिफ़ॉल्ट रूप से सुरक्षित)।

क्लाइंट API कुंजी प्रवर्तन `src/shared/utils/featureFlags.ts` में `isRequireApiKeyEnabled()` का उपयोग करता है, सीधे `process.env.REQUIRE_API_KEY` पढ़ने का नहीं। तैनात इंस्टेंस के लिए यह मायने रखता है: डैशबोर्ड → Feature Flags में `REQUIRE_API_KEY` टॉगल करने से DB ओवरराइड संग्रहीत होता है और तुरंत `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, और इस हेल्पर को साझा करने वाली अन्य क्लाइंट-API प्रमाणीकरण जाँचों पर असर पड़ता है। यदि फ़ीचर फ़्लैग स्टोर पढ़ा नहीं जा सकता, तो क्लाइंट API प्रमाणीकरण बंद होकर विफल होता है और कुंजी माँगता है।

## असंगत परिवर्तन — v3.8.0

`/api/v1/agents/tasks/*` और `/api/resilience/model-cooldowns` एंडपॉइंट को **अब प्रबंधन प्रमाणीकरण की आवश्यकता है** (कमिट `588a0333`)। पहले `manage` स्कोप के बिना सामान्य API कुंजी भेजने वाले क्लाइंट को `403` प्राप्त होता है। माइग्रेशन: API Keys डैशबोर्ड में कुंजी को `manage` स्कोप प्रदान करें, या लॉग-इन किए हुए डैशबोर्ड सत्र का उपयोग करें।

## व्यवहार परिवर्तन — v3.8.2

`/api/mcp/*` (रिमोट MCP सर्वर) अब भी डिफ़ॉल्ट रूप से LOCAL_ONLY है, लेकिन अब यह गैर-लूपबैक अनुरोधों को स्वीकार करता है, जब `Authorization: Bearer <api-key>` हेडर में `manage` स्कोप होता है। यह अपवाद `src/server/authz/routeGuard.ts` में `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` के माध्यम से प्रत्येक पथ के लिए स्पष्ट रूप से नियंत्रित होता है; समान स्तर वाला LOCAL_ONLY प्रीफ़िक्स `/api/cli-tools/runtime/*` जानबूझकर बायपास नहीं किया जा सकता, क्योंकि यह मनमानी सबप्रोसेस शुरू कर सकता है। गैर-लूपबैक से `/api/mcp/*` पर आने वाले अनाम अनुरोध अब भी `403 LOCAL_ONLY` लौटाते हैं — किसी भी नए LOCAL_ONLY पथ के लिए डिफ़ॉल्ट सख्त-लूपबैक ही रहता है। देखें [रूट गार्ड स्तर](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)।

## परीक्षण

- यूनिट परीक्षण: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`।
- सार्वजनिक अनुमति-सूची: `tests/unit/public-api-routes.test.ts`।
- केंद्रित परीक्षण चलाएँ: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`।

## डिबगिंग

पाइपलाइन हमेशा प्रतिक्रियाओं पर मुहर लगाती है:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

प्रमाणित अनुरोधों के लिए अपस्ट्रीम (हैंडलर-साइड) अनुरोध हेडर में यह भी शामिल है:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

हैंडलर — के अंदर `assertAuth(req, expectedClass)` उपयोग करें यदि मिडलवेयर को बायपास किया गया था तो यह कोड `AUTHZ_NOT_INITIALIZED` के साथ `AuthzAssertionError` फेंकता है (परीक्षणों में कॉन्फ़िगरेशन रिग्रेशन को पकड़ने के लिए सहायक)।

## इन्हें भी देखें

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — प्रति एंडपॉइंट प्रमाणीकरण मार्कर
- [COMPLIANCE.md](../security/COMPLIANCE.md) — प्रमाणीकरण घटनाओं के लिए ऑडिट लॉग
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — तीन स्कोप नेमस्पेस और एमसीपी टूल-स्कोप कैटलॉग
- स्रोत: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
