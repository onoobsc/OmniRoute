# Authorization Guide (አማርኛ)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **የእውነት ምንጭ:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **መጨረሻ የተዘመነው:** 2026-09-22 — የወሰን ስም-ክልሎች ወደ MCP-SERVER.md ያመለክታሉ

OmniRoute እያንዳንዱን የAPI ጥያቄ የሚቆጣጠር፣ መንገድን የሚያውቅ የፈቃድ መስጫ ሂደት አለው። ምደባው **ቁርጥ ያለ** እና **ሲሳነው-ዝግ** ነው — ሊመደብ የማይችል ማንኛውም ነገር `MANAGEMENT` ሆኖ ይመደባል፣ እንዲሁም ክፍለ-ጊዜ ወይም የአስተዳደር-ደረጃ ቶከን ይጠይቃል። ይህ ገጽ መንገዶችን ለሚንከባከቡ ወይም አዳዲስ የመዳረሻ ነጥቦችን ለሚነድፉ መሐንዲሶች ሞዴሉን ያብራራል።

![የAuthZ ሂደት (3 የመንገድ ምድቦች + የፖሊሲ ግምገማ)](../diagrams/exported/authz-pipeline.svg)

> ምንጭ፦ [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## ሁለት ማረጋገጫ ሁነታዎች

### 1. API ቁልፍ (ተሸካሚ)

ቁልፉ `manage` ወሰን ሲኖረው OpenAI/Anthropic/Gemini-compatible ደንበኛ APIs እና ለጥቂት የአስተዳደር መንገዶች ጥቅም ላይ ይውላል።

```
Authorization: Bearer <api-key>
```

በ `isValidApiKey()` / `extractApiKey()` በ `src/sse/services/auth.ts` የተረጋገጠ እና በ `src/shared/utils/apiAuth.ts` በኩል እንደገና ወደ ውጭ ተልኳል። አረጋጋጩ እንዲሁም `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env varsን እንደ ቋሚ ማለፊያ ቁልፎች (እትም #1350) ይቀበላል።

### 2. ዳሽቦርድ ክፍለ ጊዜ (auth_token ኩኪ)

ለዳሽቦርድ ገፆች እና የአስተዳዳሪ ስራዎች።

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

ኩኪ አንድ ክፍለ ጊዜ JWT ሲያረጋግጥ ብቻ ነው።** እና** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) ይይዛል። እያንዳንዱ የኩኪ ተጠቃሚ (ዳሽቦርድ መንገድ ጠባቂ (`isDashboardSessionAuthenticated()`))፣ authz ቧንቧ መስመር እድሳት፣ WebSocket መጨባበጥ፣ የቀጥታ አገልጋይ፣ `/api/settings/require-login`፣ `/api/auth/status`) በዚያ ረዳት ውስጥ ያልፋል። ሌሎች JWTs `JWT_SECRET` ጋር የተፈራረሙ — የ Cursor CLI ማለፊያ minnts `iss "omniroute" / aud "cursor-cli"` ቶከኖች ለቁልፍ ያዢዎች — እና መቼም ክፍለ ጊዜዎች አይደሉም (#13298)።

በ `isDashboardSessionAuthenticated()` የተረጋገጠ `src/shared/utils/apiAuth.ts` የቧንቧ መስመር JWT በ 30 ቀናት ዕድሜው ከ 7 ቀናት ያነሰ ሲቀረው በራስ-ሰር ያድሳል።

አንድ ክፍለ ጊዜ እንዲሁ 30 ቀናት ከማለቁ በፊት ሊጠናቀቅ ይችላል፣ ምክንያቱም እያንዳንዱ ሚንተር በ `mintDashboardSessionToken` (ችግር ጊዜ `iat` እና አንድ መታወቂያ `jti`) ውስጥ ያልፋል እና አረጋጋጩ ሁለት መቼቶችን ይፈትሻል `sessionsValidAfter`, በይለፍ ቃል ተቀይሯል ስለዚህ እያንዳንዱ ክፍለ ጊዜ ማረጋገጡን ከማቆሙ በፊት (የይለፍ ቃል የለወጠው አሳሽ አዲስ ኩኪ ያገኛል) እና `revokedDashboardSessions`, `POST /api/auth/logout` የወጣበትን ክፍለ ጊዜ `jti`። በአሮጌ ልቀት የተሰሩ ክፍለ-ጊዜዎች የይገባኛል ጥያቄን አይያዙም እና የመጀመሪያው የይለፍ ቃል እስኪቀየር ድረስ ይቆያሉ። ቅንብሮቹ ሊነበቡ ካልቻሉ, ክፍለ-ጊዜው አይታመንም.

አንዳንድ የአስተዳደር መንገዶች ይቀበላሉ።** ወይ** ሁነታ: ኩኪ OR `Bearer <key>` የ API ቁልፍ የ `manage` (ወይም `admin`) ወሰን ሲኖረው። በv3.8 ላይ የተጨመረውን "በ API ጥሪዎች ሊዋቀር የሚችል" የስራ ፍሰትን የሚያስችለው ይህ ነው።

#### አማራጭ OIDC መግቢያ በር (#6973)

የዳሽቦርድ አስተዳዳሪ መግቢያ እንዲሁ ይደግፋል** መርጦ መግባት** OIDC (OpenID Connect) ከነባሪው የይለፍ ቃል መግቢያ ጋር የሚፈሰው ፍሰት — ይለፍ ቃል መግባት በጭራሽ አይወገድም፣ ብቻ ይሟላል

- `settings.oidcEnabled === true` ካልሆነ በስተቀር ተሰናክሏል።** እና** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` ሁሉም ተዋቅረዋል (ቅንጅቶች → Auth)። `GET /api/auth/oidc/login` ያለበለዚያ `400` ይመልሳል።
- `GET /api/auth/oidc/login` `authorization_endpoint` ከሰጪው `/.well-known/openid-configuration` ያገኘው (ወደ `<issuer>/authorize` ተመልሶ ይወድቃል)፣ ከመጪው ጥያቄ (`x-forwarded-proto` -aware) URI ይገነባል፣ እና በዘፈቀደ `state` በ `httpOnly` `oidc_state` ኩኪ ውስጥ ወደ IdP ያዞራል።
- `GET /api/auth/oidc/callback` `state` ያጸድቃል፣ የፈቀዳ ኮድ ይለውጣል እና የ ID token ፊርማ በሰጪው JWKS (`jose`'s `createRemoteJWKSet`፣ cached per JWKS URI) `issuer`/`audience` ቼኮች ያረጋግጣል። የዳሽቦርድ መግቢያ ባዶ ያልሆነ `oidcAllowedSubjects` ዝርዝር፣ `oidcAdmissionClaim` ፖሊሲ ወይም ሁለቱንም ይፈልጋል። የርዕሰ ጉዳዩ ዝርዝር `sub` ወይም `email` የሚዛመደው `email_verified === true` ሲሆን ብቻ ነው። የአማራጭ የይገባኛል ጥያቄ ፖሊሲ በነጥብ-የተለየ መታወቂያ-ቶከን የይገባኛል ጥያቄ ዱካ (ለምሳሌ፣ `realm_access.roles`) እና ተቀባይነት ያላቸውን እሴቶች ድርድር ይወስዳል። የተፈታው የይገባኛል ጥያቄ ቢያንስ አንድ ተቀባይነት ያለው እሴት የያዘ የሕብረቁምፊዎች ድርድር መሆን አለበት። ሁለቱም ፖሊሲዎች ከተዋቀሩ ሁለቱም ማለፍ አለባቸው። Missing/malformed የይገባኛል ጥያቄ አልተዘጋም እና ያለ ሁለቱም ፖሊሲ መልሶ መደወል መግባትን አይቀበልም (`not_configured`)። ነባር የርዕስ-ብቻ ውቅሮች ሳይቀየሩ ይቀጥላሉ።
- የቁልፍ ክሎክ በመደበኛነት የግዛት ሚናዎችን ወደ መዳረሻ ቶከኖች ያዘጋጃል፣ የግድ ID ቶከን አይደለም። የግዛት ሚና `admin` ለመፈለግ፣ ለዚህ ደንበኛ የፕሮቶኮል ካርታን ያዋቅሩ፣ በውስጡም `realm_access.roles` ያካትታል።**ID ማስመሰያ** , ከዚያ `oidcAdmissionClaim` ወደ `{ "path": "realm_access.roles", "values": ["admin"] }` ያዘጋጁ. ሚና-ብቻ መግባትን ከማንቃትዎ በፊት ለዚህ ደንበኛ ትክክለኛውን የመታወቂያ ማስመሰያ ጥያቄ ያረጋግጡ። አፕሊኬሽኑ የመዳረሻ-ቶከን ሚናዎችን አያነብም። ከአይዲፒ ጎን ማስመሰያ አለመቀበል ሊሟላ ይችላል ነገርግን ይህን የመተግበሪያ-ጎን ቼክ አይተካም።
- በስኬት ላይ ይንቃል** በትክክል ተመሳሳይ** የ30-ቀን `auth_token` JWT የይለፍ ቃል መግቢያ ጉዳዮች (`src/app/api/auth/login/route.ts`)፣ ስለዚህ የተቀረው የዳሽቦርድ ክፍለ ጊዜ ቧንቧ መስመር (በራስ-አድስ፣ የኩኪ ባንዲራዎች) ያልተለወጠ — OIDC የሚተካው ኩኪው እንዴት እንደሚሰራ እንጂ የሚሰጠውን አይደለም። በ IdP roles/groups ላይ የሚደረጉ ለውጦች ነባር OmniRoute ክፍለ-ጊዜዎችን አያጠፉም; መውጣት፣ የይለፍ ቃል ማሽከርከር ወይም የክፍለ-ጊዜው ማብቂያ አሁንም በሕይወት ዘመናቸው ይመራሉ።
- እያንዳንዱ `oidc*` መቼት (`oidcEnabled`, `oidcDisablePasswordLogin` `src/shared/constants/securityImpactingSettings.ts` `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` ውስጥ ነው: `PATCH /api/settings` መልስ `400 PASSWORD_REQUIRED` አካል አስተዳደር የይለፍ ቃል `currentPassword` (ስህተት ከሆነ `401 PASSWORD_MISMATCH` ) ይዞ በስተቀር. `oidcDisablePasswordLogin` የይለፍ ቃል _login_ (`POST /api/auth/login`) አይቀበልም ነገር ግን የተከማቸ የይለፍ ቃል ሃሽ ያስቀምጣል እና እንደገና ማረጋገጥ አሁንም `currentPassword` በእሱ ላይ ያረጋግጣል።
- `corsOrigins` እና `bruteForceProtection` በ `SECURITY_IMPACTING_SETTINGS_KEYS` ውስጥም አሉ፡ መፍታት ወይ የመግባት መከላከያን ያዳክማል፣ ስለዚህ ተመሳሳይ `currentPassword` ድጋሚ ማረጋገጫ ወስደዋል (የሴኩሪቲ ትሩ ይጠይቀዋል) እና JSON ማስመጣት ይጥላቸዋል።
- እያንዳንዱ የደህንነት-ፖሊሲ ቁልፍ — የ `SECURITY_IMPACTING_SETTINGS_KEYS` ግቤቶች፣ እያንዳንዱ `oidc*` ቁልፍ እና የዳሽቦርድ ክፍለ ጊዜ — ነው** ኦፕሬተር-ብቻ** በ `PATCH /api/settings` ላይ፡ በአስተዳዳሪ የሚወሰን API ቁልፍ ወይም የ `oma_` መዳረሻ ማስመሰያ በ `403` ትክክለኛውን `currentPassword` ሲልክ እንኳን ውድቅ ይደረጋል፣ እና እምቢታው እንደ `settings.update_failed` በ `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` በ `src/lib/api/operatorCredential.ts`) ኦዲት ይደረጋል። የተለመዱ ቅንብሮች (ጭብጥ፣ የማሳያ ምርጫዎች) ለ `manage` ቁልፍ ወይም ለ `admin` መዳረሻ ማስመሰያ እንደተፃፉ ይቆያሉ። እያንዳንዱ የ `/api/settings` ሚውቴሽን (እና የ `/api/settings/require-login`) እንዲሁ የ `admin` መዳረሻ-ቶከን ወሰን ያስፈልገዋል (`ADMIN_MUTATION_EXACT_PATHS` በ `src/server/authz/accessScopes.ts`፣ ትክክለኛ-መንገድ ተዛማጅ)። `GET` `read` ይቆያል፣ እና ሌሎች `/api/settings/*` ንኡስ መስመሮች (ፕሮክሲዎች፣ ጥምር ነባሪዎች፣ የሞዴል ቅጽል ስሞች፣ መጭመቂያ፣ ማጽጃዎች…) በዘዴ የሚገመተውን `write` ወሰን ይጠብቃሉ።
- `POST /api/settings/import-json` እንደገና የወጣውን ይዘላል፣ ስለዚህ ከመጻፉ በፊት እያንዳንዱን ቁልፍ በ `IMPORT_STRIPPED_SETTINGS_KEYS` (ተመሳሳይ ፋይል) ይጥላል፡ የይለፍ ቃሉ እና `currentPassword`፣ እያንዳንዱ `SECURITY_IMPACTING_SETTINGS_KEYS` ግቤት እና የዳሽቦርዱ ክፍለ ጊዜ ሁኔታ (`sessionsValidAfter`, `revokedDashboardSessions`)። የድሮ ምትኬን ማስመጣት ስለዚህ የይለፍ ቃል የተቀየረበትን ክፍለ ጊዜ ወይም ዘግቶ መውጣትን ማደስ አይችልም።

#### አማራጭ TOTP ባለሁለት ደረጃ መግቢያ (#16619)

ከቅንብሮች → ደህንነት የተመዘገበ; ኦፕሬተሩ (`src/server/auth/dashboardMfa.ts`) እስኪያበራ ድረስ አጥፋ።

- **የሚሸፍነው፡-** የይለፍ ቃል መግቢያ (`POST /api/auth/login`, ከዚያም `POST /api/auth/mfa/verify` ያስፈልገዋል ) እና `omniroute connect` (`POST /api/cli/connect`, የይለፍ ቃል ብቻ መለዋወጥ እምቢ እና ኮዱን `totp` አድርጎ ይወስዳል).
- **የማይሸፍነው፡-** OIDC / SSO መግባት (`/api/auth/oidc/callback`) OmniRoute TOTP አይጠይቅም። እሱ በራሱ ማንነት አቅራቢው ሁለተኛ ደረጃ ላይ ይመሰረታል፣ ስለዚህ OIDC የነቃ ከሆነ MFA በ IdP ያስፈጽሙ።
- **ማገገም** (የጠፋ መሳሪያ፣ ምንም የመልሶ ማግኛ ኮዶች አልቀሩም ወይም ከአሁን በኋላ ሊረጋገጥ የማይችል ነገር፣ ለምሳሌ `STORAGE_ENCRYPTION_KEY` ከተቀየረ በኋላ)
  1. አገልጋዩን በ `OMNIROUTE_DISABLE_MFA=true` እንደገና ያስጀምሩ።
  2. በአስተናጋጁ ራሱ (loopback peer እና loopback `Host`፣እንደ `http://localhost:20128` ያሉ)፣ በይለፍ ቃል ይግቡ። ሁለተኛው ምክንያት የተዘለለው ለዚያ መነሻ ብቻ ነው; ማንኛውም ሌላ ምንጭ አሁንም ኮድ ያስፈልገዋል.
  3. በቅንብሮች → ሴኩሪቲ → አሰናክል፣ የይለፍ ቃሉን ያስገቡ እና ኮዱን ባዶ ይተዉት። `POST /api/auth/mfa/disable` ያለ `code` አካልን የሚቀበለው ተለዋዋጭ ሲዘጋጅ እና ጥያቄው ከአስተናጋጁ ሲመጣ ብቻ ነው; አሁንም የዳሽቦርዱን ክፍለ ጊዜ እና የአሁኑን የይለፍ ቃል ይፈልጋል፣ እና በ `secondFactor: "recovery_switch"` እንደ `auth.mfa.disabled` ኦዲት ይደረጋል።
  4. `OMNIROUTE_DISABLE_MFA` ያራግፉ፣ እንደገና ያስጀምሩ እና ካስፈለገ እንደገና ይመዝገቡ።

## የመንገድ ክፍሎች

`src/server/authz/types.ts` ሶስት ክፍሎችን ይገልጻል፤ በቁርጥ ሊመደብ የማይችል ማንኛውም መንገድ ወደ `MANAGEMENT` ይወድቃል።

| ክፍል          | መግለጫ                                                                                                                                               | የሚያስፈልግ ማረጋገጫ                               |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| `PUBLIC`     | ግልጽ ደህንነታቸው የተጠበቀ መንገዶች — መግቢያ፣ መውጫ፣ ሁኔታ፣ init፣ ጤና፣ የonboarding bootstrap።                                                                         | የለም                                         |
| `CLIENT_API` | ሞዴል የሚያገለግሉ የመጨረሻ ነጥቦች — `/api/v1/*`፣ `/api/v1beta/*`፣ እና ተለዋጭ ስሞቹ `/v1/*`፣ `/v1beta/*`፣ `/chat/completions`፣ `/responses`፣ `/models`፣ `/codex/*`። | ውጤታማው `REQUIRE_API_KEY` ባንዲራ ሲነቃ Bearer ቁልፍ |
| `MANAGEMENT` | የዳሽቦርድ ገጾች፣ ቅንብሮች፣ አቅራቢዎች፣ ቁልፎች፣ የአስተዳዳሪና የምርመራ መጨረሻ ነጥቦች።                                                                                         | የዳሽቦርድ ክፍለ-ጊዜ ወይም `manage` ወሰን ያለው Bearer   |

ጥቂት `MANAGEMENT` ድርጊቶች **ለኦፕሬተር ብቻ** ናቸው፦ `manage` ቁልፍ በቂ አይደለም። የተቀመጡ ምስክርነቶችን ወደ ውጭ ማውጣት (`GET /api/settings/export-json`፣ `GET /api/db-backups/export`፣ `GET /api/db-backups/exportAll`)፣ ምትኬን በቀጥታ ዳታ ላይ መመለስ (`dryRun=true`ን ጨምሮ `POST /api/db-backups/import`፣ በID መመለስ `POST /api/db-backups`፣ `POST /api/settings/import-json`)፣ እና የመመለሻ ነጥቦችን ማጥፋት (`DELETE /api/db-backups` ማጽዳት፣ እንዲሁም `PATCH /api/db-backups` ምክንያቱም የሚያስቀምጠው የማቆያ ፖሊሲ ከእያንዳንዱ ምትኬ በኋላ ራስ-ሰር መቁረጥን ስለሚመራ) የዳሽቦርድ ክፍለ-ጊዜ፣ የአካባቢው CLI ርዕሰ-ጉዳይ ወይም መግቢያ የተሰናከለ መሆን ይፈልጋሉ። የማመሳሰያ ቶከን ማውጣት (`POST /api/sync/tokens`) እና `admin` የCLI መዳረሻ ቶከን መፍጠር (`POST /api/cli/tokens`) በማንኛውም የመግቢያ ሁነታ የዳሽቦርድ ክፍለ-ጊዜ ወይም የአካባቢው CLI ርዕሰ-ጉዳይ ይፈልጋሉ። የማንኛውም ወሰን የAPI ቁልፎችና `oma_` የመዳረሻ ቶከኖች የኦፕሬተር ምስክርነቶች አይደሉም፦ ኦፕሬተር ሲፈለግ `403` ያገኛሉ። ምርመራው በ`src/lib/api/operatorCredential.ts` ውስጥ ነው (`resolveOperatorCredential()` / `requireOperatorCredential()`)። የመግቢያ ቅንብሮችን መቀየርም ለኦፕሬተር ብቻ ነው፦ `POST /api/settings/require-login` (የአስተዳዳሪ የይለፍ ቃል ማዘጋጀት / `requireLogin`ን መቀያየር) የይለፍ ቃል ካለ በኋላ እነዚህን ምስክርነቶች ብቻ ይቀበላል — የመጀመሪያ-ሩጫ bootstrap መስኮት (ገና የይለፍ ቃል ከሌለ) ግን አይለወጥም — እና የዳሽቦርድ ክፍለ-ጊዜ የይለፍ ቃሉን ለመተካት `currentPassword` መላክ አለበት (ከጎደለ ወይም ትክክል ካልሆነ `403`፣ እንደ `settings.update_failed` ኦዲት ይደረጋል)። የአካባቢው CLI እና መግቢያው የተሰናከለበት ምሳሌ የማገገሚያ መንገዱን ይዘው ይቆያሉ እና ያለ እሱ የይለፍ ቃል ማዘጋጀት ይችላሉ፤ ሁለቱም የዳታ ማውጫውን ከያዘው አስተናጋጅ ጋር የተሳሰሩ ናቸው።

## የቧንቧ መስመር

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

የታመኑ የውስጥ ራስጌዎች (በ `src/server/authz/headers.ts` የተገለጹ) ናቸው።** ከገቢ ጥያቄዎች ተወግዷል** ከምድብ በፊት — ደንበኞች አንድን ርዕሰ ጉዳይ ለማስመሰል `x-omniroute-auth-*` አስቀድመው መሙላት አይችሉም።

### የፖሊሲ ውሎች

እያንዳንዱ የመንገድ ክፍል `src/server/authz/policies/` ውስጥ ፖሊሲ አለው፡-

- **`publicPolicy`** (`policies/public.ts`) — ሁልጊዜ `allow({ kind: "anonymous", id: "anonymous" })` ይመልሳል።
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ተዋጽኦዎች Bearer፣ በ `validateApiKey()` በኩል ያረጋግጣል። ውጤታማው `REQUIRE_API_KEY` ባህሪ ባንዲራ ሲሰናከል ብቻ ወደ ማንነቱ ያልታወቀ ይሆናል። ውጤታማው ባንዲራ በ `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ነው የሚፈታው ስለዚህ የዳሽቦርድ ባህሪ ባንዲራዎች እና የአካባቢ ተለዋዋጮች `/api/v1/*`, `/api/v1beta/*`, እና ቅጽል ስሞች በወጥነት ይገዛሉ; የመፍትሄው አለመሳካቶች ተዘግተዋል. የዳሽቦርድ-ክፍለ-ጊዜ ጥያቄዎችን በደንበኛ API መንገዶች ( `/api/v1/models` ጨምሮ፣ በዳሽቦርድ ሞዴል ካታሎግ ጥቅም ላይ እንደሚውል) ይፈቅዳል። Entra ID SSO ሲነቃ፣ መዋቅራዊ የኢንትራ ቶከን የሆነ ተሸካሚ (ሦስት base64url ክፍሎች፣ `RS*` alg፣ `kid`) በ SSO ቅርንጫፍ ይካሄዳል።** ከዚህ በፊት** `validateApiKey()` እና ፍርዱ የመጨረሻ ነው — በጭራሽ ወደ ኤፒአይ-ቁልፍ መንገድ ወይም ወደ ስም-አልባ ቅርንጫፉ አይወድቅም፣ ስለዚህ የማንነት አቅራቢው መቋረጥ ክፍት መዳረሻ ሊሆን አይችልም። የማይለዋወጡ API ቁልፎች አልተነኩም። [Entra ID SSO](../security/ENTRA_SSO.md) ይመልከቱ።
- **`managementPolicy`** (`policies/management.ts`) — የዳሽቦርድ ክፍለ ጊዜን፣ የውስጥ ሞዴል-አመሳስል ጥያቄዎችን ( `/api/providers/[name]/(sync-models|models)` ጋር የሚዛመድ) ይቀበላል ወይም `isAuthRequired()` በውሸት ከተመለሰ ሙሉ በሙሉ ይዘላል። የተሸካሚ ማስመሰያ ሲኖር ግን ልክ ያልሆነ 403 (`AUTH_001`) ይመልሳል፣ ካልሆነ 401። እንዲሁም የመንገድ ጠባቂ ደረጃዎችን (LOCAL_ONLY / ALWAYS_PROTECTED) ከማንኛውም የድጋፍ ቅርንጫፍ በፊት ያስፈጽማል — [የመንገድ ጠባቂ ደረጃዎችን](../security/ROUTE_GUARD_TIERS.md) ይመልከቱ። በ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ውስጥ LOCAL_ONLY ዱካዎች (ዛሬ: `/api/mcp/`) የተሸካሚው ቁልፍ `manage` ወሰን ሲይዝ ከloopback ሊደረስበት ይችላል; ሁሉም ሌሎች LOCAL_ONLY ዱካዎች ምንም ያህል ስፋት ቢኖራቸውም ጥብቅ-loopback ይቆያሉ።

የተሳካ ፖሊሲ `AuthSubject` በ `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` ይመልሳል። የታች ተፋሰስ ተቆጣጣሪዎች የድጋሚ የቃል አመክንዮ ከማሄድ ይልቅ በ `assertAuth(request, "CLIENT_API")` በ `src/server/authz/assertAuth.ts` በኩል ሊያነቡት ይችላሉ።

## የህዝብ መንገዶች ዝርዝር

`src/shared/constants/publicApiRoutes.ts` ግልጽ የተፈቀደ ዝርዝር ነው፡-

ዝርዝሩ የተከፋፈለው በ** ቅርጽ** , እና ክፍፍሉ ተሸካሚ ነው (GHSA-74g9-q8f6-793h)፡ ቅድመ ቅጥያ ከ `startsWith()` ጋር ይዛመዳል፣ ስለዚህ እንዲሁም መሪ ገጸ ባህሪያቱን ከሚጋራው ከጎን ካሉት መንገዶች ጋር ይዛመዳል። `/api/usage/om-usage` እንደ ቅድመ ቅጥያ `/api/usage/om-usage<anything>` PUBLIC ምልክት ተደርጎበታል፣ እና በመቀጠል ያንን በራሱ ማረጋገጫ የሌለውን ተቆጣጣሪ `/api/usage/[connectionId]` — ለማድረግ ይፈታል።

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

ተነባቢ-ብቻ መንገዶች ይፋዊ ናቸው።** ብቻ** ለአስተማማኝ ዘዴዎች. ማሳሰቢያ `classifyRoute()` `/api/v1/*` እና `/api/v1beta/*` ከ PUBLIC ውድቀት-በ — አያካትትም እነዚያ ሁልጊዜ `CLIENT_API` ናቸው ስለዚህ የ Bearer-key ፖሊሲ አሁንም ይሠራል።

## አዲስ መስመር ማከል

### ንድፍ 1 — ይፋዊ የclient API endpoint (Bearer-auth)

በ`/api/v1/` እና `/api/v1beta/` ስር ያሉ መስመሮች በራስ-ሰር `CLIENT_API` ተብለው ይመደባሉ። middlewareው የBearer ማረጋገጫውን ያስገድዳል፤ route handlers ይህንን እንደገና ማከናወን አያስፈልጋቸውም፣ ነገር ግን ጠቃሚ ከሆነ subjectን ማንበብ ይችላሉ።

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... የhandler አመክንዮ
}
```

### ንድፍ 2 — የአስተዳደር endpoint (session ወይም Bearer + manage)

ከ`src/lib/api/requireManagementAuth.ts` የሚገኘውን `requireManagementAuth()` ይጠቀሙ፦

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... የhandler አመክንዮ
}
```

`requireManagementAuth()` ሲሳካ `null`ን፣ ካልሆነ ደግሞ የJSON ስህተት `Response`ን ይመልሳል፦

- 401 `AUTH_001` "ማረጋገጫ ያስፈልጋል" — ምንም credentials የሉም
- 403 — ልክ ያልሆነ Bearer **ወይም** Bearer አለ፣ ነገር ግን keyው የ`manage` / `admin` scope የለውም

`hasManageScope(scopes)` ለ`"manage"` ወይም `"admin"` true ይመልሳል።

### ንድፍ 3 — ወደ ይፋዊ የፈቃድ ዝርዝሩ ማከል

setን በቅርጹ መሠረት ይምረጡ፣ በአመቺነት መሠረት አይደለም። አንድ መስመር ወደ `PUBLIC_API_ROUTES_EXACT` ይገባል (ወይም GET-only ከሆነ ወደ `PUBLIC_READONLY_CORS_API_ROUTES`)፤ ወደ `PUBLIC_API_ROUTE_PREFIXES` የሚገባው እውነተኛ ንዑስ ዛፍ ብቻ ነው፣ እና **በ`/` መጨረስ አለበት**። ነጠላ መስመርን በprefix ዝርዝሩ ውስጥ ማስቀመጥ፣ ተመሳሳይ መሪ ቁምፊዎችን የሚጋሩ ሁሉንም አጎራባች paths ይፋዊ ያደርጋል — ይህም በኋላ የሚታከሉ dynamic-segment siblingsን ይጨምራል (GHSA-74g9-q8f6-793h)። በ`tests/unit/public-api-routes.test.ts`፣ `tests/unit/authz/public-route-exact-match.test.ts` እና `tests/unit/authz/classify.test.ts` ያሉ unit testsን ያዘምኑ።

## የፈቃድ ወሰኖች

ሦስት namespace-ዎች አሉ። እያንዳንዱ checker የሚያነበው የራሱን string-ዎች ብቻ ነው። `manage` ለ`read:compression` በ`scopeMatches` ለምን እንደማይዛመድ እና የ`read` access token ለምን `PATCH /api/keys/{id}` ማድረግ እንደማይችል ጨምሮ፣ የጎን-ለጎን ንጽጽሩ
[ሦስቱ የፈቃድ ወሰን namespace-ዎች](../frameworks/MCP-SERVER.md#three-scope-namespaces) ላይ ይገኛል።

API key-ዎች የ`scopes` array ይይዛሉ (በ`api_keys.scopes` ውስጥ እንደ JSON ይከማቻል፤ `src/lib/db/apiKeys.ts`ን ይመልከቱ)።

### የአስተዳደር ፈቃድ ወሰን

- `manage` / `admin` — `hasManageScope`። ወደ የአስተዳደር API route-ዎች የBearer መዳረሻ።
- `mcp:connect`፣ `self:usage`፣ `self:account-quota` እና
  `policy:bypass-provider-quota` በትክክል የሚዛመዱ ተጨማሪ የፈቃድ ወሰኖች ናቸው። እነዚህ
  ከ`MANAGEMENT_API_KEY_SCOPES` ውጭ ይገኛሉ። `mcp:connect` የሚከፍተው
  የ`/api/mcp/` non-loopback ልዩ ፈቃድን ብቻ ነው።

### የMCP tool ፈቃድ ወሰኖች

Catalog እና የማዛመድ ደንቦች (ተመሳሳይ string፣ ወይም በ`*` የሚያበቃ የተፈቀደ ወሰን)፦
[የMCP tool ፈቃድ ወሰኖች](../frameworks/MCP-SERVER.md#mcp-tool-scopes)።
በ`src/shared/constants/mcpScopes.ts` ውስጥ ያለው `MCP_SCOPE_LIST` ያ ሙሉ catalog ሳይሆን የመጀመሪያው typed
subset ነው። `resolveCallerScopeContext()` ከMCP auth info፣ ከrequest metadata ወይም ከ`OMNIROUTE_MCP_SCOPES`
የፈቃድ ወሰኖችን ከወሰነ በኋላ፣ ማስፈጸሙ በ`open-sse/mcp-server/scopeEnforcement.ts`
ውስጥ ይከናወናል። `OMNIROUTE_MCP_ENFORCE_SCOPES=true` ካልሆነ በስተቀር እንደጠፋ ይቆያል።

### የAccess-token ፈቃድ ወሰኖች

በ`oma_live_…` token-ዎች ላይ `read` / `write` / `admin`፣ በ`scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) ደረጃ የተሰጣቸው። ይህ ደረጃ የሚሠራው ለaccess-token
credential ብቻ ነው። [የአስተዳደር ማረጋገጫ](../guides/MANAGEMENT-AUTH.md)ን ይመልከቱ።

## የማረጋገጫ-ያስፈልጋል መቀያየሪያ

`src/shared/utils/apiAuth.ts` ውስጥ ያለው `isAuthRequired()` ለጥያቄ **ማንኛውም** ማረጋገጫ መተግበሩን ይወስናል፦

- `settings.requireLogin === false` → ማረጋገጫ በአለም አቀፍ ደረጃ ተሰናክሏል፣ ሁልጊዜ-የተጠበቀው ደረጃ ([የመንገድ ጠባቂ ደረጃዎች](../security/ROUTE_GUARD_TIERS.md)) እና ተቀባይ ምስክርነት የሚሰጡ ጥሪዎች ሲቀሩ — እነዚህ መግቢያ በርቶ እንዳለ ያው ምስክርነት ይፈልጋሉ፦ የማመሳሰያ ቶከኖችን ማውጣት፣ በማንኛውም ወሰን የCLI መዳረሻ ቶከኖች መፍጠር፣ እና `manage`/`admin` ወሰን ያለው የAPI ቁልፍ መፍጠር፣ ያንን ወሰን ለቁልፍ መስጠት፣ ወይም እንዲህ ያለውን ቁልፍ ማደስ ወይም ማሳየት (`src/lib/api/requireManagementAuth.ts` ውስጥ `requireCredentialForManagementScopedKey()`)። የኢንፈረንስ-ብቻ ቁልፎች ክፍት ሆነው ይቀጥላሉ።
- የይለፍ ቃል ካልተዋቀረ **እና** `INITIAL_PASSWORD` የአካባቢ ተለዋዋጭ ከሌለ → የbootstrap ሁነታ የመጀመሪያ-ጊዜ ዝግጅት አዋቂውንና loopback ጥያቄዎችን ይፈቅዳል፣ ነገር ግን ለአውታረ መረብ የተጋለጡ ጥያቄዎች አሁንም ምስክርነት ያስፈልጋቸዋል።
- ማንኛውም የDB ስህተት → ዝግ ይሆናል (በነባሪ ደህንነቱ የተጠበቀ)።

የደንበኛ API ቁልፍ ማስገደድ `src/shared/utils/featureFlags.ts` ውስጥ ያለውን `isRequireApiKeyEnabled()` ይጠቀማል፣ በቀጥታ `process.env.REQUIRE_API_KEY` ን ከማንበብ ይልቅ። ይህ ለተሰማሩ ምሳሌዎች ይጠቅማል፦ `REQUIRE_API_KEY`ን በዳሽቦርድ → Feature Flags ውስጥ መቀያየር DB መሻሪያ ያስቀምጣል እና ይህንን ረዳት የሚጋሩ `/v1/*`፣ `/v1beta/*`፣ `/models`፣ `/responses`፣ `/chat/completions`፣ `/codex/*` እና ሌሎች የደንበኛ-API ማረጋገጫ ፍተሻዎችን ወዲያውኑ ይነካል። የባንዲራ ማከማቻው ማንበብ ካልተቻለ የደንበኛ-API ማረጋገጫ ዝግ ይሆናል እና ቁልፍ ይፈልጋል።

## ተኳሃኝነትን የሚያፈርስ ለውጥ — v3.8.0

የ`/api/v1/agents/tasks/*` እና `/api/resilience/model-cooldowns` መጨረሻ ነጥቦች **አሁን የአስተዳደር ማረጋገጫ ይፈልጋሉ** (commit `588a0333`)። ከዚህ በፊት የ`manage` ወሰን የሌለውን መደበኛ API ቁልፍ ይልኩ የነበሩ ደንበኞች `403` ይቀበላሉ። ፍልሰት፦ በAPI Keys dashboard ውስጥ ለቁልፉ የ`manage` ወሰንን ይስጡ፣ ወይም የገቡበትን dashboard ክፍለ ጊዜ ይጠቀሙ።

## የባህሪ ለውጥ — v3.8.2

`/api/mcp/*` (የርቀት MCP አገልጋዩ) አሁንም በነባሪ LOCAL_ONLY ነው፤ ሆኖም የ`Authorization: Bearer <api-key>` ራስጌው የ`manage` ወሰንን ሲይዝ አሁን loopback ያልሆኑ ጥያቄዎችን ይቀበላል። ይህ ልዩ ማስቀረት በ`src/server/authz/routeGuard.ts` ውስጥ ባለው `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` በኩል ለእያንዳንዱ ዱካ በግልጽ ሁኔታ የሚቆጣጠር ነው፤ የወንድም LOCAL_ONLY ቅድመ ቅጥያ `/api/cli-tools/runtime/*` ማናቸውንም ንዑስ ሂደቶች ሊያስነሳ ስለሚችል ሆን ተብሎ ሊታለፍ የማይችል ተደርጓል። loopback ካልሆነ ምንጭ ወደ `/api/mcp/*` የሚላኩ ስም-አልባ ጥያቄዎች `403 LOCAL_ONLY`ን መመለሳቸውን ይቀጥላሉ — ለማንኛውም አዲስ LOCAL_ONLY ዱካ ነባሪው ጥብቅ-loopback ሆኖ ይቀጥላል። [የRoute Guard ደረጃዎች](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out)ን ይመልከቱ።

## ሙከራ

- የክፍል ሙከራዎች፦ `tests/unit/authz/` — `classify.test.ts`፣ `pipeline.test.ts`፣ `client-api-policy.test.ts`፣ `management-policy.test.ts`፣ `public-policy.test.ts`።
- የሕዝብ ፍቃድ ዝርዝር፦ `tests/unit/public-api-routes.test.ts`።
- ያተኮረ ሙከራን ያሂዱ፦ `node --import tsx/esm --test tests/unit/authz/classify.test.ts`።

## ማረም

ቧንቧው ሁል ጊዜ ምላሾችን በሚከተሉት ምልክቶች ያስቀምጣል።

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

ለተረጋገጡ ጥያቄዎች የላይ (ከአስተዳዳሪ-ጎን) የጥያቄ ራስጌዎች በተጨማሪ ያካትታሉ፡

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

`assertAuth(req, expectedClass)` ከውስጥ ተቆጣጣሪዎች ይጠቀሙ — መካከለኛው ዌር ከተታለፈ `AuthzAssertionError` በኮድ `AUTHZ_NOT_INITIALIZED` ይጥላል (በሙከራዎች ውስጥ የውቅር ለውጦችን ለመያዝ ይጠቅማል)።

## በተጨማሪ ይመልከቱ

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ለእያንዳንዱ endpoint የauth ምልክት
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ለauth ክስተቶች የኦዲት መዝገብ
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ሦስት የscope namespace እና የMCP tool-scope ካታሎግ
- ምንጭ፦ `src/server/authz/`፣ `src/lib/api/requireManagementAuth.ts`
