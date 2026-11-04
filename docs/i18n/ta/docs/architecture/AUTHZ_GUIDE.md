# Authorization Guide (தமிழ்)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **உண்மையின் ஆதாரம்:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **கடைசியாகப் புதுப்பிக்கப்பட்டது:** 2026-09-22 — ஸ்கோப் நேம்ஸ்பேஸ்கள் MCP-SERVER.md ஐக் குறிக்கின்றன

OmniRoute ஆனது ஒவ்வொரு API கோரிக்கையையும் கட்டுப்படுத்தும் ஒரு வழித்தட-அறிந்த அங்கீகாரப் பைப்லைனைக் கொண்டுள்ளது. வகைப்பாடு **நிர்ணயிக்கக்கூடியது** மற்றும் **தோல்வியுற்றால் மூடும்** — வகைப்படுத்த முடியாத எதுவும் `MANAGEMENT` ஆக முடிவடைகிறது மற்றும் ஒரு அமர்வு அல்லது மேலாண்மை-தர டோக்கனைக் கோருகிறது. இந்த பக்கம் வழித்தடங்களை பராமரிக்கும் அல்லது புதிய இறுதிப்புள்ளிகளை வடிவமைக்கும் பொறியாளர்களுக்கான மாதிரியை விளக்குகிறது.

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> ஆதாரம்: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## இரண்டு அங்கீகார முறைகள்

### 1. API விசை (தாங்கி)

OpenAI/Anthropic/Gemini-compatible கிளையன்ட் APIs மற்றும் விசை `manage` ஸ்கோப்பைக் கொண்டிருக்கும் போது சில மேலாண்மை வழிகளுக்குப் பயன்படுத்தப்படுகிறது.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` இல் `isValidApiKey()` / `extractApiKey()` ஆல் சரிபார்க்கப்பட்டு `src/shared/utils/apiAuth.ts` மூலம் மீண்டும் ஏற்றுமதி செய்யப்படுகிறது. வேலிடேட்டரும் `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ஐ நிலையான பாஸ்த்ரூ விசைகளாக ஏற்றுக்கொள்கிறார் (இஷ்யூ #1350).

### 2. டாஷ்போர்டு அமர்வு (auth_token cookie)

டாஷ்போர்டு பக்கங்கள் மற்றும் நிர்வாக செயல்பாடுகளுக்கு.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

JWT சரிபார்க்கும் போது மட்டுமே குக்கீ ஒரு அமர்வு ஆகும்** மற்றும்** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) கொண்டு செல்கிறது. குக்கீயின் ஒவ்வொரு நுகர்வோரும் (டாஷ்போர்டு ரூட் கார்டு (`isDashboardSessionAuthenticated()`), authz பைப்லைன் புதுப்பிப்பு, WebSocket ஹேண்ட்ஷேக், லைவ் சர்வர், `/api/settings/require-login`, `/api/auth/status`) அந்த உதவியாளர் வழியாக செல்கிறது. `JWT_SECRET` உடன் கையொப்பமிடப்பட்ட மற்ற JWTs — உள்ளது Cursor CLI பாஸ்த்ரூ mints `iss "omniroute" / aud "cursor-cli"` டோக்கன்கள் முக்கிய வைத்திருப்பவர்களுக்கான — மற்றும் அவை ஒருபோதும் அமர்வுகள் அல்ல (#13298).

`src/shared/utils/apiAuth.ts` இல் `isDashboardSessionAuthenticated()` ஆல் சரிபார்க்கப்பட்டது. பைப்லைன் அதன் 30 நாள் வாழ்நாளில் 7 நாட்களுக்கும் குறைவாக இருக்கும் போது JWT ஐ தானாக புதுப்பிக்கிறது.

ஒரு அமர்வு 30 நாட்கள் முடிவதற்குள் முடிவடையும், ஏனெனில் ஒவ்வொரு minter `mintDashboardSessionToken` (ஒரு சிக்கல் நேரம் `iat` மற்றும் ஒரு id `jti`) வழியாகச் செல்கிறது மற்றும் சரிபார்ப்பு இரண்டு அமைப்புகளைச் சரிபார்க்கிறது: `sessionsValidAfter`, கடவுச்சொல் மாற்றத்தால் அமைக்கப்பட்டது, எனவே அது சரிபார்ப்பதை நிறுத்தும் முன் வழங்கப்படும் ஒவ்வொரு அமர்வும் (கடவுச்சொல்லை மாற்றிய உலாவி, புதிய குக்கீயைப் பெறுகிறது), மேலும் `revokedDashboardSessions` `jti` சேர்க்க `POST /api/auth/logout` பழைய வெளியீட்டின் மூலம் தயாரிக்கப்பட்ட அமர்வுகள் எந்த உரிமைகோரலையும் கொண்டிருக்காது மற்றும் முதல் கடவுச்சொல்லை மாற்றும் வரை செல்லுபடியாகும். அமைப்புகளைப் படிக்க முடியாவிட்டால், அமர்வு நம்பகமானதாக இருக்காது.

சில மேலாண்மை வழிகள் ஏற்கின்றன** ஒன்று** முறை: API விசை `manage` (அல்லது `admin`) ஸ்கோப்பைக் கொண்டிருக்கும் போது குக்கீ OR `Bearer <key>`. இதுவே v3.8 இல் சேர்க்கப்பட்ட " API அழைப்புகள் வழியாக உள்ளமைக்கக்கூடிய" பணிப்பாய்வுகளை செயல்படுத்துகிறது.

#### விருப்பமான OIDC உள்நுழைவு வாயில் (#6973)

டாஷ்போர்டு நிர்வாக உள்நுழைவும் ஆதரிக்கிறது** தேர்வு** இயல்புநிலை கடவுச்சொல் உள்நுழைவுடன் OIDC (OpenID இணைப்பு) ஓட்டம் — கடவுச்சொல் உள்நுழைவு அகற்றப்படாது, கூடுதலாக மட்டுமே:

- `settings.oidcEnabled === true` இல்லாவிட்டால் முடக்கப்படும்** மற்றும்** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` அனைத்தும் கட்டமைக்கப்பட்டுள்ளன (அமைப்புகள் → அங்கீகாரம்). `GET /api/auth/oidc/login` இல்லையெனில் `400` திரும்பும்.
- `GET /api/auth/oidc/login` வழங்குபவரின் `/.well-known/openid-configuration` இலிருந்து `authorization_endpoint` கண்டுபிடித்து (மீண்டும் `<issuer>/authorize` க்கு விழுகிறது), உள்வரும் கோரிக்கையிலிருந்து (`x-forwarded-proto` -aware) திசைதிருப்பும் URI உருவாக்குகிறது, மேலும் `httpOnly` `oidc_state` குக்கீயில் சேமிக்கப்பட்ட ஒரு சீரற்ற `state` மூலம் IdP க்கு திருப்பி விடுகிறது.
- `GET /api/auth/oidc/callback` `state` URI `audience` அங்கீகாரக் குறியீட்டைப் பரிமாறி, ID டோக்கனின் கையொப்பத்தை வழங்குபவரின் JWKS வழியாக சரிபார்க்கிறது `issuer` `jose` JWKS `createRemoteJWKSet` டாஷ்போர்டு சேர்க்கைக்கு வெற்று `oidcAllowedSubjects` பட்டியல், `oidcAdmissionClaim` கொள்கை அல்லது இரண்டும் தேவை. பொருள் பட்டியல் `sub` அல்லது `email` உடன் மட்டுமே `email_verified === true` க்கு பொருந்தும். விருப்பமான உரிமைகோரல் கொள்கையானது புள்ளியால் பிரிக்கப்பட்ட ஐடி-டோக்கன் உரிமைகோரல் பாதை (உதாரணமாக, `realm_access.roles`) மற்றும் ஏற்றுக்கொள்ளப்பட்ட மதிப்புகளின் வரிசையை எடுக்கும்; தீர்க்கப்பட்ட உரிமைகோரல் குறைந்தபட்சம் ஒரு ஏற்றுக்கொள்ளப்பட்ட மதிப்பைக் கொண்ட சரங்களின் வரிசையாக இருக்க வேண்டும். இரண்டு கொள்கைகளும் கட்டமைக்கப்பட்டிருந்தால், இரண்டும் கடந்து செல்ல வேண்டும். Missing/malformed உரிமைகோரல்கள் தோல்வியடைந்தன, மேலும் கொள்கை எதுவும் இல்லாமல் திரும்ப அழைப்பானது உள்நுழைவை மறுக்கிறது (`not_configured`). ஏற்கனவே உள்ள பொருள் மட்டுமே உள்ளமைவுகள் மாறாமல் தொடர்கின்றன.
- Keycloak பொதுவாக சாம்ராஜ்ய பாத்திரங்களை அணுகல் டோக்கன்களாக வரைபடமாக்குகிறது, ID டோக்கன்கள் அவசியமில்லை. ராஜ்யம் பங்கு `admin` தேவைப்படுவதற்கு, இந்த கிளையண்டிற்கான நெறிமுறை மேப்பரை உள்ளமைக்கவும், அதில் `realm_access.roles` உள்ளது**ID டோக்கன்** , பின்னர் `oidcAdmissionClaim` ஐ `{ "path": "realm_access.roles", "values": ["admin"] }` ஆக அமைக்கவும். பங்கு மட்டும் சேர்க்கையை இயக்கும் முன் இந்தக் கிளையண்டிற்கான உண்மையான ஐடி-டோக்கன் உரிமைகோரலைச் சரிபார்க்கவும்; பயன்பாடு அணுகல்-டோக்கன் பாத்திரங்களைப் படிக்கவில்லை. ஐடிபி பக்க டோக்கன் மறுப்பு துணையாக இருக்கலாம் ஆனால் இந்த ஆப்ஸ் பக்க சரிபார்ப்பை மாற்றாது.
- வெற்றியைப் பற்றி அது குறிப்பிடுகிறது** அதே** 30-நாள் `auth_token` JWT கடவுச்சொல் உள்நுழைவு சிக்கல்கள் (`src/app/api/auth/login/route.ts`), எனவே மீதமுள்ள டேஷ்போர்டு அமர்வு பைப்லைன் (தானியங்கு-புதுப்பிப்பு, குக்கீ கொடிகள்) மாறாமல் — OIDC ஆனது குக்கீ எவ்வாறு அச்சிடப்படுகிறது என்பதை மட்டுமே மாற்றுகிறது, அது என்ன வழங்குகிறது என்பதை அல்ல. IdP roles/groups இன் மாற்றங்கள் ஏற்கனவே உள்ள OmniRoute அமர்வுகளை செல்லாததாக்குவதில்லை; வெளியேறுதல், கடவுச்சொல் சுழற்சி அல்லது அமர்வு காலாவதியானது இன்னும் அவர்களின் வாழ்நாளைக் கட்டுப்படுத்துகிறது.
- ஒவ்வொரு `oidc*` அமைப்பும் (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) இல் இருக்கும்: `PATCH /api/settings` க்கு பதிலளிக்கும் போது, அது `currentPassword` என நிர்வாகம் தவறாக இருந்தால், `400 PASSWORD_REQUIRED` `401 PASSWORD_MISMATCH`. `oidcDisablePasswordLogin` கடவுச்சொல் _login_ (`POST /api/auth/login`) ஐ மறுக்கிறது, ஆனால் சேமிக்கப்பட்ட கடவுச்சொல் ஹாஷை வைத்திருக்கிறது, மேலும் மறு அங்கீகாரம் இன்னும் `currentPassword` சரிபார்க்கிறது.
- `corsOrigins` மற்றும் `bruteForceProtection` ஆகியவை `SECURITY_IMPACTING_SETTINGS_KEYS` இல் உள்ளன: தளர்த்துவது உள்நுழைவு பாதுகாப்பை பலவீனப்படுத்துகிறது, எனவே அவை அதே `currentPassword` மறு அங்கீகாரத்தை (பாதுகாப்பு தாவல் கேட்கிறது) மற்றும் JSON இறக்குமதி குறைகிறது.
- ஒவ்வொரு பாதுகாப்பு-கொள்கை விசையும் — `SECURITY_IMPACTING_SETTINGS_KEYS` உள்ளீடுகள், ஒவ்வொரு `oidc*` விசை மற்றும் டாஷ்போர்டு அமர்வு நிலை —** ஆபரேட்டர்-மட்டும்** `PATCH /api/settings` இல்: ஒரு மேலாண்மை-நோக்கமுள்ள API விசை அல்லது `oma_` அணுகல் டோக்கன் சரியான `currentPassword` அனுப்பும்போதும் `403` உடன் மறுக்கப்படுகிறது, மேலும் மறுப்பு `reason: OPERATOR_REQUIRED` உடன் `settings.update_failed` ஆக தணிக்கை செய்யப்படுகிறது ( `src/lib/api/operatorCredential.ts` இல்`requireOperatorCredential()` ). சாதாரண அமைப்புகள் (தீம், காட்சி விருப்பத்தேர்வுகள்) `manage` விசை அல்லது `admin` அணுகல் டோக்கனுக்கு எழுதக்கூடியதாக இருக்கும். `/api/settings` இன் ஒவ்வொரு பிறழ்வுக்கும் (மற்றும் `/api/settings/require-login`) `admin` அணுகல்-டோக்கன் நோக்கம் ( `src/server/authz/accessScopes.ts` இல்`ADMIN_MUTATION_EXACT_PATHS`, சரியான பாதை பொருத்தம்) தேவை; `GET` ஆனது `read`, மற்றும் பிற `/api/settings/*` துணை வழிகள் (ப்ராக்ஸிகள், காம்போ இயல்புநிலைகள், மாதிரி மாற்றுப்பெயர்கள், சுருக்கம், சுத்திகரிப்பு...) முறை-ஊகிக்கப்பட்ட `write` நோக்கத்தை வைத்திருக்கிறது.
- `POST /api/settings/import-json` அந்த மறு அங்கீகாரத்தைத் தவிர்க்கிறது, எனவே அது எழுதும் முன் `IMPORT_STRIPPED_SETTINGS_KEYS` (அதே கோப்பு) இல் உள்ள ஒவ்வொரு விசையையும் கைவிடுகிறது: கடவுச்சொல் மற்றும் `currentPassword`, ஒவ்வொரு `SECURITY_IMPACTING_SETTINGS_KEYS` உள்ளீடு மற்றும் டாஷ்போர்டு அமர்வு நிலை (`sessionsValidAfter`, `revokedDashboardSessions`). பழைய காப்புப்பிரதியை இறக்குமதி செய்வதால் கடவுச்சொல் மாற்றம் அல்லது வெளியேறுதல் ஏற்கனவே முடிவடைந்த அமர்வை புதுப்பிக்க முடியாது.

#### விருப்பமான TOTP இரண்டு காரணி உள்நுழைவு (#16619)

→ பாதுகாப்பு அமைப்புகளில் இருந்து பதிவுசெய்யப்பட்டது; ஆபரேட்டர் அதை இயக்கும் வரை (`src/server/auth/dashboardMfa.ts`) அணைக்கப்படும்.

- **இது என்ன உள்ளடக்கியது:** கடவுச்சொல் உள்நுழைவு (`POST /api/auth/login`, பின்னர் `POST /api/auth/mfa/verify` தேவை ) மற்றும் `omniroute connect` (`POST /api/cli/connect`, இது கடவுச்சொல் மட்டும் பரிமாற்றத்தை மறுத்து குறியீட்டை `totp` ஆக எடுத்துக்கொள்கிறது).
- **இது எதை உள்ளடக்காது:** OIDC / SSO உள்நுழைவு (`/api/auth/oidc/callback`) OmniRoute TOTP ஐக் கேட்காது. இது அடையாள வழங்குநரின் சொந்த இரண்டாவது காரணியைச் சார்ந்துள்ளது, எனவே OIDC இயக்கப்பட்டிருந்தால் IdP இல் MFA செயல்படுத்தவும்.
- **மீட்பு** (இழந்த சாதனம், மீட்புக் குறியீடுகள் எதுவும் இல்லை, அல்லது சரிபார்க்க முடியாத காரணி, எடுத்துக்காட்டாக `STORAGE_ENCRYPTION_KEY` மாற்றப்பட்ட பிறகு):
  1. `OMNIROUTE_DISABLE_MFA=true` உடன் சேவையகத்தை மறுதொடக்கம் செய்யுங்கள்.
  2. ஹோஸ்டிலேயே (loopback peer மற்றும் loopback `Host`, `http://localhost:20128` போன்றவை), கடவுச்சொல்லைக் கொண்டு உள்நுழையவும். இரண்டாவது காரணி அந்த தோற்றத்திற்காக மட்டுமே தவிர்க்கப்பட்டது; மற்ற எல்லா மூலங்களுக்கும் இன்னும் குறியீடு தேவை.
  3. அமைப்புகளில் → Security → முடக்கு, கடவுச்சொல்லை உள்ளிட்டு குறியீட்டை காலியாக விடவும். `POST /api/auth/mfa/disable` ஆனது `code` இல்லாத உடலை ஏற்றுக்கொள்கிறது, மாறி அமைக்கப்பட்டு, ஹோஸ்டிடமிருந்து கோரிக்கை வரும்; அதற்கு இன்னும் டாஷ்போர்டு அமர்வு மற்றும் தற்போதைய கடவுச்சொல் தேவைப்படுகிறது, மேலும் `secondFactor: "recovery_switch"` உடன் `auth.mfa.disabled` ஆக தணிக்கை செய்யப்படுகிறது.
  4. `OMNIROUTE_DISABLE_MFA` அமைக்காமல், மறுதொடக்கம் செய்து, தேவைப்பட்டால் மீண்டும் பதிவு செய்யவும்.

## ரூட் வகைகள்

`src/server/authz/types.ts` மூன்று வகைகளை வரையறுக்கிறது; தீர்மானகரமாக வகைப்படுத்த முடியாத எந்த route-உம் `MANAGEMENT`-க்குத் திரும்பும்.

| Class        | Description                                                                                                                                             | Auth required                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| `PUBLIC`     | வெளிப்படையாகவே பாதுகாப்பான routes — login, logout, status, init, health, onboarding bootstrap.                                                          | எதுவும் தேவையில்லை                                              |
| `CLIENT_API` | Model-serving endpoints — `/api/v1/*`, `/api/v1beta/*`, மற்றும் aliases `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | `REQUIRE_API_KEY` feature flag செயலில் இருக்கும்போது Bearer key |
| `MANAGEMENT` | Dashboard பக்கங்கள், settings, providers, keys, admin மற்றும் diagnostics endpoints.                                                                    | Dashboard session அல்லது `manage` scope உடைய Bearer             |

சில `MANAGEMENT` செயல்கள் **operator-only** ஆகும்: `manage` key மட்டும் போதாது. சேமிக்கப்பட்ட credentials-ஐ ஏற்றுமதி செய்தல் (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), live data-வின் மேல் backup-ஐ மீட்டமைத்தல் (`dryRun=true` உட்பட `POST /api/db-backups/import`, id மூலம் `POST /api/db-backups` restore, `POST /api/settings/import-json`), restore points-ஐ அழித்தல் (`DELETE /api/db-backups` cleanup, மற்றும் `PATCH /api/db-backups` ஏனெனில் அது சேமிக்கும் retention ஒவ்வொரு backup-க்குப் பின்னும் தானியங்கு நீக்கத்தை இயக்குகிறது) ஆகியவற்றுக்கு dashboard session, உள்ளூர் CLI subject, அல்லது login முடக்கப்பட்டிருப்பது தேவை. Sync token-ஐ வழங்குதல் (`POST /api/sync/tokens`) மற்றும் `admin` CLI access token-ஐ உருவாக்குதல் (`POST /api/cli/tokens`) ஒவ்வொரு login mode-இலும் dashboard session அல்லது உள்ளூர் CLI subject தேவை. எந்த scope-இன் API keys-உம், `oma_` access tokens-உம் operator credentials அல்ல: தேவைப்படும்போதெல்லாம் அவை `403` பெறும். இச்சரிபார்ப்பு `src/lib/api/operatorCredential.ts`-இல் உள்ளது (`resolveOperatorCredential()` / `requireOperatorCredential()`). Login settings-ஐ மாற்றுவதும் operator-only: ஒரு கடவுச்சொல் ஏற்கனவே இருந்தால் `POST /api/settings/require-login` (நிர்வாகக் கடவுச்சொல்லை அமைத்தல் / `requireLogin`-ஐ மாற்றுதல்) அந்த credentials-ஐ மட்டுமே ஏற்கும் — கடவுச்சொல் இல்லாத முதல்-முறை bootstrap சாளரம் மாறாது — மேலும் கடவுச்சொல்லை மாற்ற dashboard session `currentPassword` அனுப்ப வேண்டும் (அது இல்லாவிட்டால் அல்லது தவறாக இருந்தால் `403`, `settings.update_failed` என தணிக்கை செய்யப்படும்). உள்ளூர் CLI-உம், login முடக்கப்பட்ட instance-உம் மீட்புப் பாதையைத் தக்கவைக்கின்றன; அவை data directory-ஐ வைத்திருக்கும் host-உடன் பிணைக்கப்பட்டிருப்பதால், அது இல்லாமலேயே கடவுச்சொல்லை அமைக்கலாம்.

## குழாய்

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

நம்பகமான உள் தலைப்புகள் ( `src/server/authz/headers.ts` இல் வரையறுக்கப்பட்டுள்ளன)** உள்வரும் கோரிக்கைகளிலிருந்து அகற்றப்பட்டது** — வகைப்பாட்டிற்கு முன் கிளையண்டுகள் ஒரு விஷயத்தைப் போல ஆள்மாறாட்டம் செய்ய `x-omniroute-auth-*` முன் நிரப்ப முடியாது.

### கொள்கை ஒப்பந்தங்கள்

ஒவ்வொரு வழி வகுப்பிற்கும் `src/server/authz/policies/` இல் கொள்கை உள்ளது:

- **`publicPolicy`** (`policies/public.ts`) — எப்போதும் `allow({ kind: "anonymous", id: "anonymous" })` வழங்கும்.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — பிரித்தெடுத்தல் தாங்கி, `validateApiKey()` வழியாக சரிபார்க்கிறது. பயனுள்ள `REQUIRE_API_KEY` அம்சக் கொடி முடக்கப்பட்டிருக்கும் போது மட்டுமே அநாமதேயமாக மாறும். பயனுள்ள கொடியானது `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) மூலம் தீர்க்கப்படுகிறது, எனவே டாஷ்போர்டு அம்சம் கொடிகள் மற்றும் சூழல் மாறிகள் `/api/v1/*`, `/api/v1beta/*` மற்றும் மாற்றுப்பெயர்களை தொடர்ந்து நிர்வகிக்கின்றன; தீர்க்கும் தோல்விகள் தோல்வி அடைகின்றன. கிளையன்ட் API வழிகளில் டேஷ்போர்டு-அமர்வு கோரிக்கைகளை அனுமதிக்கிறது ( `/api/v1/models`, டாஷ்போர்டு மாதிரி அட்டவணையால் பயன்படுத்தப்படுகிறது). Entra ID SSO இயக்கப்பட்டால், கட்டமைப்பு ரீதியாக என்ட்ரா டோக்கனாக இருக்கும் ஒரு தாங்கி (மூன்று base64url பிரிவுகள், `RS*` alg, `kid`) SSO கிளையால் கையாளப்படுகிறது.** முன்** `validateApiKey()` மற்றும் அதன் தீர்ப்பு இறுதி — ஆகும், இது ஒருபோதும் API-கீ பாதை அல்லது சிதைவிலிருந்து அநாமதேய கிளைக்கு வராது, எனவே அடையாள-வழங்குபவர் செயலிழப்பு திறந்த அணுகலாக மாற முடியாது. நிலையான API விசைகள் பாதிக்கப்படாது. [Entra ID SSO](../security/ENTRA_SSO.md) ஐப் பார்க்கவும்.
- **`managementPolicy`** (`policies/management.ts`) — டாஷ்போர்டு அமர்வு, உள் மாதிரி-ஒத்திசைவு கோரிக்கைகளை ( `/api/providers/[name]/(sync-models|models)` க்கு எதிராகப் பொருந்துகிறது) ஏற்றுக்கொள்கிறது அல்லது `isAuthRequired()` தவறு எனத் திரும்பினால் முழுவதுமாகத் தவிர்க்கிறது. ஒரு தாங்கி டோக்கன் இருக்கும் போது 403 (`AUTH_001`) ஐ வழங்குகிறது ஆனால் செல்லாது, இல்லையெனில் 401. மேலும் வழி — காவலர் [அடுக்குகளை](../security/ROUTE_GUARD_TIERS.md) (LOCAL_ONLY / ALWAYS_PROTECTED) செயல்படுத்துகிறது. `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` இல் உள்ள LOCAL_ONLY பாதைகள் (இன்று: `/api/mcp/`) பியரர் விசை `manage` ஸ்கோப்பைக் கொண்டிருக்கும் போது லூப்பேக் அல்லாதவற்றிலிருந்து அணுகலாம்; மற்ற அனைத்து LOCAL_ONLY பாதைகளும் ஸ்கோப்பைப் பொருட்படுத்தாமல் கண்டிப்பான-லூப்பேக்காக இருக்கும்.

வெற்றிகரமான கொள்கையானது `AuthSubject` `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` உடன் வழங்கும். கீழ்நிலை கையாளுபவர்கள் அங்கீகார தர்க்கத்தை மீண்டும் இயக்குவதற்குப் பதிலாக `src/server/authz/assertAuth.ts` இல் `assertAuth(request, "CLIENT_API")` வழியாகப் படிக்கலாம்.

## பொது வழிகள் பட்டியல்

`src/shared/constants/publicApiRoutes.ts` என்பது வெளிப்படையான அனுமதிப்பட்டியல்:

பட்டியல் பிரிக்கப்பட்டுள்ளது** வடிவம்** , மற்றும் பிளவு சுமை தாங்கும் (GHSA-74g9-q8f6-793h): ஒரு முன்னொட்டு `startsWith()` உடன் பொருந்துகிறது, எனவே இது அதன் முன்னணி எழுத்துக்களைப் பகிர்ந்து கொள்ளும் ஒவ்வொரு அருகிலுள்ள பாதைக்கும் பொருந்தும். `/api/usage/om-usage` ஒரு முன்னொட்டாக `/api/usage/om-usage<anything>` PUBLIC எனக் குறிக்கப்பட்டது, மேலும் அதன் சொந்த அங்கீகாரம் இல்லாத ஒரு ஹேண்ட்லரை `/api/usage/[connectionId]` — என்று அடுத்து தீர்க்கிறது.

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

படிக்க மட்டும் வழிகள் பொது** மட்டுமே** பாதுகாப்பான முறைகளுக்கு. குறிப்பு: `classifyRoute()` PUBLIC Fal-through — இலிருந்து `/api/v1/*` மற்றும் `/api/v1beta/*` விலக்குகிறது `CLIENT_API`

## புதிய Route ஒன்றைச் சேர்த்தல்

### முறை 1 — பொது client API endpoint (Bearer-auth)

`/api/v1/` மற்றும் `/api/v1beta/`-இன் கீழுள்ள routes தானாகவே `CLIENT_API` என வகைப்படுத்தப்படுகின்றன. Middleware, Bearer சரிபார்ப்பை அமல்படுத்துகிறது; route handlers அதை மீண்டும் செய்ய வேண்டியதில்லை, ஆனால் பயனுள்ளதாக இருந்தால் subject-ஐப் படிக்கலாம்.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handler தர்க்கம்
}
```

### முறை 2 — Management endpoint (session அல்லது Bearer + manage)

`src/lib/api/requireManagementAuth.ts`-இலிருந்து `requireManagementAuth()`-ஐப் பயன்படுத்தவும்:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handler தர்க்கம்
}
```

வெற்றியின்போது `requireManagementAuth()` ஆனது `null`-ஐ வழங்கும்; இல்லையெனில் JSON error `Response`-ஐ வழங்கும்:

- 401 `AUTH_001` "அங்கீகாரம் தேவை" — எந்த credentials-உம் இல்லை
- 403 — தவறான Bearer **அல்லது** Bearer இருந்தும் key-இல் `manage` / `admin` scope இல்லை

`hasManageScope(scopes)` ஆனது `"manage"` அல்லது `"admin"`-க்கு true-ஐ வழங்கும்.

### முறை 3 — பொது allowlist-இல் சேர்த்தல்

வசதியின் அடிப்படையில் அல்லாமல், வடிவத்தின் அடிப்படையில் set-ஐத் தேர்ந்தெடுக்கவும். ஒரு route, `PUBLIC_API_ROUTES_EXACT`-இல் (அல்லது GET-only எனில் `PUBLIC_READONLY_CORS_API_ROUTES`-இல்) சேர்க்கப்பட வேண்டும்; உண்மையான subtree மட்டுமே `PUBLIC_API_ROUTE_PREFIXES`-இல் சேர்க்கப்பட வேண்டும், மேலும் அது **`/`-இல் முடிய வேண்டும்**. ஒரு தனிப்பட்ட route-ஐ prefix பட்டியலில் சேர்ப்பது, அதன் தொடக்க எழுத்துகளைப் பகிரும் அருகிலுள்ள ஒவ்வொரு path-ஐயும் பொது அணுகலுக்கு வெளியிடும் — பின்னர் சேர்க்கப்படும் dynamic-segment sibling routes உட்பட (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` மற்றும் `tests/unit/authz/classify.test.ts` ஆகியவற்றிலுள்ள unit tests-ஐப் புதுப்பிக்கவும்.

## ஸ்கோப்கள்

மூன்று நேம்ஸ்பேஸ்கள். ஒவ்வொரு செக்கரும் அதன் சொந்த ஸ்ட்ரிங்குகளை மட்டுமே படிக்கிறது. `manage` ஏன் `read:compression` க்கான `scopeMatches` ஐத் தவறவிடுகிறது மற்றும் ஒரு `read` அணுகல் டோக்கன் ஏன் `PATCH /api/keys/{id}` ஐச் செய்ய முடியாது என்பது உட்பட, பக்கவாட்டு ஒப்பீடு [மூன்று ஸ்கோப் நேம்ஸ்பேஸ்கள்](../frameworks/MCP-SERVER.md#three-scope-namespaces) ஆகும்.

API கீகள் ஒரு `scopes` வரிசையைக் கொண்டுள்ளன (`api_keys.scopes` இல் JSON ஆக சேமிக்கப்படும், `src/lib/db/apiKeys.ts` ஐப் பார்க்கவும்).

### மேலாண்மை ஸ்கோப்

- `manage` / `admin` — `hasManageScope`. மேலாண்மை API ரூட்டுகளுக்கான பியரர் அணுகல்.
- `mcp:connect`, `self:usage`, `self:account-quota`, மற்றும் `policy:bypass-provider-quota` ஆகியவை சேர்க்கக்கூடிய துல்லியமான-பொருந்தும் ஸ்கோப்கள் ஆகும். அவை `MANAGEMENT_API_KEY_SCOPES` க்கு வெளியே உள்ளன. `mcp:connect` ஆனது `/api/mcp/` நான்-லூப் பேக் கார்வ்-அவுட்டை மட்டுமே திறக்கிறது.

### MCP கருவி ஸ்கோப்கள்

கேட்டலாக் மற்றும் பொருந்தும் விதிகள் (ஒரே மாதிரியான ஸ்ட்ரிங், அல்லது `*` இல் முடிவடையும் ஒரு வழங்கப்பட்ட ஸ்கோப்): [MCP கருவி ஸ்கோப்கள்](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `src/shared/constants/mcpScopes.ts` இல் உள்ள `MCP_SCOPE_LIST` என்பது அசல் டைப் செய்யப்பட்ட துணைக்குழு ஆகும், முழு கேட்டலாக் அல்ல. MCP அங்கீகாரத் தகவல், கோரிக்கை மெட்டாடேட்டா அல்லது `OMNIROUTE_MCP_SCOPES` இலிருந்து ஸ்கோப்களை `resolveCallerScopeContext()` தீர்த்த பிறகு, `open-sse/mcp-server/scopeEnforcement.ts` இல் அமலாக்கம் செயல்படுகிறது. `OMNIROUTE_MCP_ENFORCE_SCOPES=true` ஆக இல்லாவிட்டால் அது அணைக்கப்படும்.

### அணுகல்-டோக்கன் ஸ்கோப்கள்

`oma_live_…` டோக்கன்களில் `read` / `write` / `admin`, `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`) மூலம் தரவரிசைப்படுத்தப்பட்டுள்ளது. இந்த தரவரிசை அணுகல்-டோக்கன் நற்சான்றிதழுக்கு மட்டுமே பொருந்தும். [மேலாண்மை அங்கீகாரம்](../guides/MANAGEMENT-AUTH.md) ஐப் பார்க்கவும்.

## Auth Required மாற்று (toggle)

`src/shared/utils/apiAuth.ts`-இல் உள்ள `isAuthRequired()`, ஒரு request-க்கு **ஏதேனும்** auth கட்டாயமா என்பதை முடிவு செய்கிறது:

- `settings.requireLogin === false` → auth உலகளவில் முடக்கப்படும், ஆனால் எப்போதும்-பாதுகாக்கப்பட்ட அடுக்கு ([Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) தவிர, மற்றும் ஏற்கப்படும் credential-ஐ வழங்கும் calls தவிர — அவை login இயக்கத்தில் இருக்கும்போது தேவைப்படும் அதே credential-ஐக் கோரும்: sync tokens வழங்குதல், எந்த scope-இலும் CLI access tokens உருவாக்குதல், மற்றும் `manage`/`admin` scope கொண்ட API key-ஐ உருவாக்குதல், ஒரு key-க்கு அந்த scope-ஐ வழங்குதல், அல்லது அத்தகைய key-ஐ மீண்டும் உருவாக்குதல் அல்லது வெளிப்படுத்துதல் (`src/lib/api/requireManagementAuth.ts`-இல் `requireCredentialForManagementScopedKey()`). Inference-only keys திறந்தே இருக்கும்.
- கடவுச்சொல் அமைக்கப்படவில்லை **மற்றும்** `INITIAL_PASSWORD` env var இல்லை → bootstrap mode onboarding wizard-ஐயும் loopback requests-ஐயும் அனுமதிக்கும், ஆனால் வெளிப்படும் network requests-க்கு இன்னும் credentials தேவை.
- ஏதேனும் DB error → fail closed (secure-by-default).

Client API key enforcement, நேரடியாக `process.env.REQUIRE_API_KEY`-ஐப் படிப்பதற்குப் பதிலாக, `src/shared/utils/featureFlags.ts`-இல் உள்ள `isRequireApiKeyEnabled()`-ஐப் பயன்படுத்துகிறது. இது deployed instances-க்கு முக்கியம்: Dashboard → Feature Flags-இல் `REQUIRE_API_KEY`-ஐ மாற்றினால் DB override சேமிக்கப்பட்டு, `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, மேலும் இந்த helper-ஐப் பகிரும் பிற client-API auth சோதனைகள் உடனடியாகப் பாதிக்கப்படும். Feature flag store படிக்க முடியாவிட்டால், client API auth fail closed ஆகி key-ஐக் கோரும்.

## இணக்கமுறிவு மாற்றம் — v3.8.0

`/api/v1/agents/tasks/*` மற்றும் `/api/resilience/model-cooldowns` எண்ட்பாயிண்டுகளுக்கு **இப்போது மேலாண்மை அங்கீகாரம் தேவை** (`588a0333` commit). முன்பு `manage` ஸ்கோப் இல்லாத சாதாரண API விசையை அனுப்பிய கிளையன்ட்கள் `403` பதிலைப் பெறுகின்றனர். இடம்பெயர்வு: API Keys டாஷ்போர்டில் அந்த விசைக்கு `manage` ஸ்கோப்பை வழங்கவும் அல்லது உள்நுழைந்த டாஷ்போர்டு அமர்வைப் பயன்படுத்தவும்.

## நடத்தையில் மாற்றம் — v3.8.2

`/api/mcp/*` (தொலைநிலை MCP சேவையகம்) இன்னும் முன்னிருப்பாக LOCAL_ONLY ஆக உள்ளது; ஆனால் இப்போது `Authorization: Bearer <api-key>` தலைப்பு `manage` ஸ்கோப்பைக் கொண்டிருக்கும்போது, லூப்பேக் அல்லாத கோரிக்கைகளை ஏற்கிறது. `src/server/authz/routeGuard.ts`-இல் உள்ள `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` வழியாக, இந்த விதிவிலக்கு ஒவ்வொரு பாதைக்கும் வெளிப்படையாகக் கட்டுப்படுத்தப்படுகிறது; தொடர்புடைய LOCAL_ONLY முன்னொட்டான `/api/cli-tools/runtime/*`, எந்தவொரு துணைச் செயல்முறையையும் தொடங்கக்கூடும் என்பதால், திட்டமிட்டே புறக்கணிக்க முடியாததாக உள்ளது. லூப்பேக் அல்லாத இடங்களிலிருந்து `/api/mcp/*`-க்கு வரும் அநாமதேயக் கோரிக்கைகள் தொடர்ந்து `403 LOCAL_ONLY` பதிலைப் பெறும் — எந்தவொரு புதிய LOCAL_ONLY பாதைக்கும் முன்னிருப்பு, லூப்பேக்கை மட்டுமே கண்டிப்பாக அனுமதிப்பதாகவே இருக்கும். [பாதைக் காவலர் அடுக்குகள்](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)-ஐப் பார்க்கவும்.

## சோதனை

- அலகுச் சோதனைகள்: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- பொது அனுமதிப்பட்டியல்: `tests/unit/public-api-routes.test.ts`.
- குறிப்பிட்ட சோதனையை இயக்க: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## பிழைத்திருத்தம்

பைப்லைன் எப்போதும் பதில்களை முத்திரையிடுகிறது:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

அங்கீகரிக்கப்பட்ட கோரிக்கைகளுக்கு அப்ஸ்ட்ரீம் (ஹேண்ட்லர்-பக்கம்) கோரிக்கை தலைப்புகளும் அடங்கும்:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

— ஹேண்ட்லர்களுக்குள் `assertAuth(req, expectedClass)` பயன்படுத்தவும், மிடில்வேர் புறக்கணிக்கப்பட்டிருந்தால், `AUTHZ_NOT_INITIALIZED` குறியீட்டுடன் `AuthzAssertionError` வீசுகிறது (சோதனைகளில் உள்ளமைவு பின்னடைவுகளைப் பிடிக்க உதவுகிறது).

## மேலும் காண்க

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ஒவ்வொரு இறுதிப்புள்ளிக்கும் அங்கீகார குறிப்பான்
- [COMPLIANCE.md](../security/COMPLIANCE.md) — அங்கீகார நிகழ்வுகளுக்கான தணிக்கை பதிவு
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — மூன்று ஸ்கோப் நேம்ஸ்பேஸ்கள் மற்றும் MCP கருவி-ஸ்கோப் பட்டியல்
- ஆதாரம்: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
