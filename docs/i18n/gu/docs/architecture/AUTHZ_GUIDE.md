# Authorization Guide (ગુજરાતી)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **સત્યનો સ્ત્રોત:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **છેલ્લે અપડેટ કરાયેલ:** 2026-09-22 — સ્કોપ નેમસ્પેસ MCP-SERVER.md તરફ નિર્દેશ કરે છે

ઓમ્નીરૂટ પાસે રૂટ-અવેર ઓથોરાઇઝેશન પાઇપલાઇન છે જે દરેક API વિનંતીને ગેટ કરે છે. વર્ગીકરણ **નિર્ધારિત** અને **ફેઇલ-ક્લોઝ્ડ** છે — જે કંઈપણ વર્ગીકૃત કરી શકાતું નથી તે `MANAGEMENT` તરીકે સમાપ્ત થાય છે અને સત્ર અથવા મેનેજમેન્ટ-ગ્રેડ ટોકનની માંગ કરે છે. આ પૃષ્ઠ રૂટ જાળવતા અથવા નવા એન્ડપોઇન્ટ્સ ડિઝાઇન કરતા ઇજનેરો માટે મોડેલ સમજાવે છે.

![AuthZ પાઇપલાઇન (3 રૂટ ક્લાસ + નીતિ મૂલ્યાંકન)](../diagrams/exported/authz-pipeline.svg)

> સ્ત્રોત: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## બે ઓથ મોડ્સ

### 1. API કી (વાહક)

જ્યારે કી પાસે `manage` સ્કોપ હોય ત્યારે OpenAI/Anthropic/Gemini-compatible ક્લાયંટ APIs અને થોડા મેનેજમેન્ટ રૂટ માટે વપરાય છે.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` માં `isValidApiKey()` / `extractApiKey()` દ્વારા માન્ય અને `src/shared/utils/apiAuth.ts` દ્વારા ફરીથી નિકાસ કરવામાં આવે છે. વેલિડેટર `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ને સતત પાસથ્રુ કી (ઇસ્યુ #1350) તરીકે પણ સ્વીકારે છે.

### 2. ડેશબોર્ડ સત્ર (auth_token કૂકી)

ડેશબોર્ડ પૃષ્ઠો અને એડમિન કામગીરી માટે.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

કૂકી એ સત્ર છે જ્યારે JWT ચકાસણી કરે છે** અને** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) વહન કરે છે. કૂકીના દરેક ઉપભોક્તા (ડેશબોર્ડ રૂટ ગાર્ડ (`isDashboardSessionAuthenticated()`), authz પાઇપલાઇન રિફ્રેશ, WebSocket હેન્ડશેક, લાઇવ સર્વર, `/api/settings/require-login`, `/api/auth/status`) તે સહાયકમાંથી પસાર થાય છે. `JWT_SECRET` સાથે સહી કરેલ અન્ય JWTs અસ્તિત્વમાં છે — ધ Cursor CLI પાસથ્રુ — કી ધારકો માટે `iss "omniroute" / aud "cursor-cli"` ટોકન્સ છે અને તે ક્યારેય સત્રો નથી (#13298).

`src/shared/utils/apiAuth.ts` માં `isDashboardSessionAuthenticated()` દ્વારા ચકાસાયેલ. જ્યારે તેના 30-દિવસના જીવનકાળમાં 7 દિવસથી ઓછા દિવસો બાકી હોય ત્યારે પાઇપલાઇન JWT ને સ્વતઃ-તાજું કરે છે.

સત્ર તેના 30 દિવસ પૂરા થાય તે પહેલાં પણ સમાપ્ત થઈ શકે છે, કારણ કે દરેક મિન્ટર `mintDashboardSessionToken` (ઈસ્યુ ટાઇમ `iat` અને id `jti`)માંથી પસાર થાય છે અને વેરિફાયર બે સેટિંગ્સ તપાસે છે: `sessionsValidAfter`, પાસવર્ડ ફેરફાર દ્વારા સેટ કરવામાં આવે છે જેથી દરેક સત્ર તેની ચકાસણી કરવાનું બંધ કરે તે પહેલાં જારી કરવામાં આવે છે (પાસવર્ડ બદલનાર બ્રાઉઝરને તાજી કૂકી મળે છે), અને જે `revokedDashboardSessions` `POST /api/auth/logout` સત્રને સાઇન આઉટ કરવા માટે `jti` જૂની રીલીઝ દ્વારા ટંકશાળ કરાયેલા સત્રો પ્રથમ પાસવર્ડ બદલાય ત્યાં સુધી દાવો કરતા નથી અને માન્ય રહે છે. જો સેટિંગ્સ વાંચી શકાતી નથી, તો સત્ર વિશ્વસનીય નથી.

કેટલાક મેનેજમેન્ટ રૂટ સ્વીકારે છે** ક્યાં તો** મોડ: જ્યારે API કીમાં `manage` (અથવા `admin`) અવકાશ હોય ત્યારે કૂકી OR `Bearer <key>`. આ તે છે જે v3.8 માં ઉમેરાયેલ " API કૉલ્સ દ્વારા રૂપરેખાંકિત" વર્કફ્લોને સક્ષમ કરે છે.

#### વૈકલ્પિક OIDC લૉગિન ગેટ (#6973)

ડેશબોર્ડ એડમિન લોગિન પણ સપોર્ટ કરે છે** પસંદ કરો** ડિફૉલ્ટ પાસવર્ડ લૉગિન સાથે OIDC (OpenID કનેક્ટ) ફ્લો — પાસવર્ડ લૉગિન ક્યારેય દૂર થતો નથી, માત્ર પૂરક:

- `settings.oidcEnabled === true` સિવાય અક્ષમ** અને** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` બધા ગોઠવેલ છે (સેટિંગ્સ → Auth). `GET /api/auth/oidc/login` અન્યથા `400` પરત કરે છે.
- `GET /api/auth/oidc/login` ઇશ્યુઅરના `/.well-known/openid-configuration` માંથી `authorization_endpoint` શોધે છે ( `<issuer>/authorize` પર પાછા આવે છે), ઇનકમિંગ રિક્વેસ્ટ (`x-forwarded-proto` -aware) થી રીડાયરેક્ટ URI બનાવે છે, અને `httpOnly` `oidc_state` કૂકીમાં સંગ્રહિત રેન્ડમ `state` સાથે IdP પર રીડાયરેક્ટ કરે છે.
- `GET /api/auth/oidc/callback` `state` માન્ય કરે છે, અધિકૃતતા કોડનું વિનિમય કરે છે, અને `issuer`/`audience` ચેક સાથે રજૂકર્તાના JWKS (`jose`'s `createRemoteJWKSet`, JWKS URI દીઠ કેશ્ડ) મારફતે ID ટોકનની સહી ચકાસે છે. ડેશબોર્ડ પ્રવેશ માટે બિન-ખાલી `oidcAllowedSubjects` સૂચિ, `oidcAdmissionClaim` નીતિ અથવા બંનેની જરૂર છે. વિષય સૂચિ `sub` અથવા `email` સાથે મેળ ખાય છે ત્યારે જ `email_verified === true`. વૈકલ્પિક દાવો નીતિ ડોટ-સેપરેટેડ ID-ટોકન દાવો પાથ (ઉદાહરણ તરીકે, `realm_access.roles`) અને સ્વીકૃત મૂલ્યોની શ્રેણી લે છે; ઉકેલાયેલ દાવો ઓછામાં ઓછો એક સ્વીકૃત મૂલ્ય ધરાવતી સ્ટ્રિંગ્સની શ્રેણી હોવી જોઈએ. જો બંને નીતિઓ ગોઠવેલી હોય, તો બંને પાસ થવી આવશ્યક છે. Missing/malformed દાવા નિષ્ફળ જાય છે, અને કોઈપણ નીતિ વિના કૉલબેક લોગિનનો ઇનકાર કરે છે (`not_configured`). હાલની માત્ર વિષયની ગોઠવણીઓ યથાવત ચાલુ રહે છે.
- કીક્લોક સામાન્ય રીતે ક્ષેત્રની ભૂમિકાઓને એક્સેસ ટોકન્સમાં મેપ કરે છે, જરૂરી નથી ID ટોકન્સ. ક્ષેત્રીય ભૂમિકા `admin` ની આવશ્યકતા માટે, આ ક્લાયંટ માટે પ્રોટોકોલ મેપરને ગોઠવો કે જે તેનામાં `realm_access.roles` સમાવે છે**ID ટોકન** , પછી `oidcAdmissionClaim` ને `{ "path": "realm_access.roles", "values": ["admin"] }` પર સેટ કરો. રોલ-ઓન્લી એડમિશન સક્ષમ કરતા પહેલા આ ક્લાયન્ટ માટે વાસ્તવિક ID-ટોકન દાવો તપાસો; એપ્લિકેશન ઍક્સેસ-ટોકન ભૂમિકાઓ વાંચતી નથી. આઇડીપી-સાઇડ ટોકન ઇનકાર પૂરક બની શકે છે પરંતુ આ એપ્લિકેશન-સાઇડ ચેકને બદલતું નથી.
- સફળતા પર તે ટંકશાળ કરે છે** બરાબર એ જ** 30-દિવસ `auth_token` JWT પાસવર્ડ લોગિન મુદ્દાઓ (`src/app/api/auth/login/route.ts`), તેથી બાકીની ડેશબોર્ડ સત્ર પાઇપલાઇન (ઓટો-રિફ્રેશ, કૂકી ફ્લેગ્સ) યથાવત છે — OIDC માત્ર કૂકી કેવી રીતે ટંકશાળ થાય છે તેને બદલે છે, તે શું આપે છે તે નહીં. IdP roles/groups માં ફેરફારો હાલના OmniRoute સત્રોને અમાન્ય બનાવતા નથી; લૉગઆઉટ, પાસવર્ડ રોટેશન અથવા સત્ર સમાપ્તિ હજુ પણ તેમના જીવનકાળનું સંચાલન કરે છે.
- દરેક `oidc*` સેટિંગ (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) માં છે : `PATCH /api/settings` `400 PASSWORD_REQUIRED` જવાબ આપે છે સિવાય કે શરીર મેનેજમેન્ટ પાસવર્ડ વહન કરે છે ( `currentPassword` `401 PASSWORD_MISMATCH` તરીકે ખોટો હોય ત્યારે). `oidcDisablePasswordLogin` પાસવર્ડ _login_ (`POST /api/auth/login`) નો ઇનકાર કરે છે પરંતુ સંગ્રહિત પાસવર્ડ હેશ રાખે છે, અને ફરીથી ઓથ હજુ પણ તેની સામે `currentPassword` તપાસે છે.
- `corsOrigins` અને `bruteForceProtection` પણ `SECURITY_IMPACTING_SETTINGS_KEYS` માં છે: ઢીલું કરવું કાં તો લૉગિન સંરક્ષણને નબળું પાડે છે, તેથી તેઓ સમાન `currentPassword` પુનઃ પ્રમાણીકરણ લે છે (સુરક્ષા ટેબ તેના માટે પૂછે છે) અને JSON આયાત તેમને છોડી દે છે.
- દરેક સુરક્ષા-નીતિ કી — ધ `SECURITY_IMPACTING_SETTINGS_KEYS` એન્ટ્રીઓ, દરેક `oidc*` કી અને ડેશબોર્ડ સત્રની સ્થિતિ — છે** માત્ર ઓપરેટર** `PATCH /api/settings` પર: મેનેજ-સ્કોપવાળી API કી અથવા `oma_` એક્સેસ ટોકન `403` સાથે નકારવામાં આવે છે, પછી ભલે તે યોગ્ય `currentPassword` મોકલે, અને ઇનકારને `reason: OPERATOR_REQUIRED` સાથે `settings.update_failed` તરીકે ઓડિટ કરવામાં આવે છે ( `src/lib/api/operatorCredential.ts` માં`requireOperatorCredential()` ). સામાન્ય સેટિંગ્સ (થીમ, પ્રદર્શન પસંદગીઓ) `manage` કી અથવા `admin` એક્સેસ ટોકન માટે લખી શકાય તેવી રહે છે. `/api/settings` ના દરેક મ્યુટેશનને (અને `/api/settings/require-login` નું) પણ `admin` એક્સેસ-ટોકન સ્કોપની જરૂર છે (`ADMIN_MUTATION_EXACT_PATHS` માં `src/server/authz/accessScopes.ts`, ચોક્કસ-પાથ મેચ); `GET` `read` રહે છે, અને અન્ય `/api/settings/*` પેટા માર્ગો (પ્રોક્સીઓ, કોમ્બો ડિફોલ્ટ્સ, મોડલ ઉપનામો, કમ્પ્રેશન, શુદ્ધિ...) પદ્ધતિ-અનુમાનિત `write` અવકાશ રાખે છે.
- `POST /api/settings/import-json` તે ફરીથી ઓથ કરવાનું છોડી દે છે, તેથી તે લખતા પહેલા `IMPORT_STRIPPED_SETTINGS_KEYS` (સમાન ફાઇલ) ની દરેક કી છોડી દે છે: પાસવર્ડ અને `currentPassword`, દરેક `SECURITY_IMPACTING_SETTINGS_KEYS` એન્ટ્રી અને ડેશબોર્ડ સત્ર સ્થિતિ (`sessionsValidAfter`, `revokedDashboardSessions`). તેથી જૂના બેકઅપને આયાત કરવું એ સત્રને પુનર્જીવિત કરી શકતું નથી કે જે પાસવર્ડમાં ફેરફાર અથવા સાઇન-આઉટ પહેલાથી જ સમાપ્ત થઈ ગયું હોય.

#### વૈકલ્પિક TOTP ટુ-ફેક્ટર લૉગિન (#16619)

સેટિંગ્સ → સુરક્ષામાંથી નોંધણી; જ્યાં સુધી ઓપરેટર તેને ચાલુ ન કરે ત્યાં સુધી બંધ કરો (`src/server/auth/dashboardMfa.ts`).

- **તે શું આવરી લે છે:** પાસવર્ડ લોગીન (`POST /api/auth/login`, જેને પછી `POST /api/auth/mfa/verify` જરૂર પડે છે ) અને `omniroute connect` (`POST /api/cli/connect`, જે ફક્ત પાસવર્ડ-વિનિમયનો ઇનકાર કરે છે અને કોડને `totp` તરીકે લે છે).
- **તે શું આવરી લેતું નથી:** OIDC / SSO સાઇન-ઇન (`/api/auth/oidc/callback`) OmniRoute TOTP માટે પૂછતું નથી. તે ઓળખ પ્રદાતાના પોતાના બીજા પરિબળ પર આધાર રાખે છે, તેથી જો OIDC સક્ષમ હોય તો IdP માં MFA લાગુ કરો.
- **પુનઃપ્રાપ્તિ** (ખોવાયેલ ઉપકરણ, કોઈ પુનઃપ્રાપ્તિ કોડ બાકી નથી, અથવા એક પરિબળ જે હવે ચકાસી શકાતું નથી, ઉદાહરણ તરીકે `STORAGE_ENCRYPTION_KEY` બદલાયા પછી):
  1. `OMNIROUTE_DISABLE_MFA=true` સાથે સર્વરને પુનઃપ્રારંભ કરો.
  2. હોસ્ટ પર જ (લૂપબેક પીઅર અને લૂપબેક `Host`, જેમ કે `http://localhost:20128`), પાસવર્ડ સાથે સાઇન ઇન કરો. બીજું પરિબળ ફક્ત તે મૂળ માટે છોડવામાં આવ્યું છે; દરેક અન્ય મૂળને હજુ પણ કોડની જરૂર છે.
  3. સેટિંગ્સમાં → સુરક્ષા → અક્ષમ કરો, પાસવર્ડ દાખલ કરો અને કોડ ખાલી છોડી દો. `POST /api/auth/mfa/disable` માત્ર `code` વગર બોડી સ્વીકારે છે જ્યારે ચલ સેટ હોય અને હોસ્ટ તરફથી વિનંતી આવે; તેને હજુ પણ ડેશબોર્ડ સત્ર અને વર્તમાન પાસવર્ડની જરૂર છે, અને `secondFactor: "recovery_switch"` સાથે `auth.mfa.disabled` તરીકે ઓડિટ કરવામાં આવે છે.
  4. `OMNIROUTE_DISABLE_MFA` અનસેટ કરો, પુનઃપ્રારંભ કરો અને જો જરૂરી હોય તો ફરીથી નોંધણી કરો.

## રૂટ ક્લાસ

`src/server/authz/types.ts` ત્રણ ક્લાસ વ્યાખ્યાયિત કરે છે; જે રૂટને નિર્ધારક રીતે વર્ગીકૃત ન કરી શકાય તે `MANAGEMENT` પર ફોલબેક થાય છે.

| ક્લાસ        | વર્ણન                                                                                                                                                 | જરૂરી પ્રમાણીકરણ                                               |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| `PUBLIC`     | સ્પષ્ટપણે સુરક્ષિત રૂટ્સ — લૉગિન, લૉગઆઉટ, સ્ટેટસ, ઇનિટ, હેલ્થ, ઓનબોર્ડિંગ બૂટસ્ટ્રેપ.                                                                 | કોઈ નહીં                                                       |
| `CLIENT_API` | મોડેલ-સર્વિંગ એન્ડપોઇન્ટ્સ — `/api/v1/*`, `/api/v1beta/*`, તથા ઉપનામો `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | અસરકારક `REQUIRE_API_KEY` ફીચર ફ્લેગ ચાલુ હોય ત્યારે Bearer કી |
| `MANAGEMENT` | ડેશબોર્ડ પેજ, સેટિંગ્સ, પ્રોવાઇડર્સ, કીઝ, એડમિન અને ડાયગ્નોસ્ટિક એન્ડપોઇન્ટ્સ.                                                                        | ડેશબોર્ડ સેશન અથવા `manage` સ્કોપ સાથે Bearer                  |

કેટલીક `MANAGEMENT` ક્રિયાઓ **ફક્ત ઓપરેટર-માટે** છે: `manage` કી પૂરતી નથી. સંગ્રહિત ક્રેડેન્શિયલ્સ એક્સપોર્ટ કરવા (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), લાઇવ ડેટા પર બેકઅપ રિસ્ટોર કરવો (`dryRun=true` સહિત `POST /api/db-backups/import`, id દ્વારા રિસ્ટોર `POST /api/db-backups`, `POST /api/settings/import-json`), અને રિસ્ટોર પોઇન્ટ નષ્ટ કરવા (`DELETE /api/db-backups` ક્લીનઅપ, અને `PATCH /api/db-backups` કારણ કે તે જે રીટેન્શન સાચવે છે તે દરેક બેકઅપ પછી આપમેળે પ્રૂનિંગ ચલાવે છે) માટે ડેશબોર્ડ સેશન, લોકલ CLI સબ્જેક્ટ, અથવા લૉગિન બંધ હોવું જરૂરી છે. સિંક ટોકન ઇશ્યૂ કરવું (`POST /api/sync/tokens`) અને `admin` CLI એક્સેસ ટોકન બનાવવું (`POST /api/cli/tokens`) દરેક લૉગિન મોડમાં ડેશબોર્ડ સેશન અથવા લોકલ CLI સબ્જેક્ટ માંગે છે. કોઈ પણ સ્કોપની API કીઓ અને `oma_` એક્સેસ ટોકન ઓપરેટર ક્રેડેન્શિયલ નથી: જ્યારે પણ તે જરૂરી હોય ત્યારે તેમને `403` મળે છે. આ તપાસ `src/lib/api/operatorCredential.ts` માં છે (`resolveOperatorCredential()` / `requireOperatorCredential()`). લૉગિન સેટિંગ્સ બદલવી પણ ફક્ત ઓપરેટર-માટે છે: `POST /api/settings/require-login` (મેનેજમેન્ટ પાસવર્ડ સેટ કરવો / `requireLogin` ટૉગલ કરવું) પાસવર્ડ અસ્તિત્વમાં હોય ત્યારે ફક્ત તે જ ક્રેડેન્શિયલ્સ સ્વીકારે છે — પ્રથમ-રન બૂટસ્ટ્રેપ વિન્ડો (હજી પાસવર્ડ નથી) યથાવત રહે છે — અને ડેશબોર્ડ સેશનને પાસવર્ડ બદલવા માટે `currentPassword` મોકલવો પડે છે (ગેરહાજર અથવા ખોટો હોય તો `403`, `settings.update_failed` તરીકે ઓડિટ થાય છે). લોકલ CLI અને લૉગિન બંધ હોય તેવી ઇન્સ્ટન્સ રિકવરી પાથ જાળવે છે અને તેના વિના પાસવર્ડ સેટ કરી શકે છે, કારણ કે બંને ડેટા ડિરેક્ટરીના માલિક હોસ્ટ સાથે બંધાયેલા છે.

## પાઇપલાઇન

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

વિશ્વસનીય આંતરિક હેડરો ( `src/server/authz/headers.ts` માં વ્યાખ્યાયિત) છે** આવનારી વિનંતીઓમાંથી છીનવી લેવામાં આવે છે** વર્ગીકરણ પહેલાં — ક્લાયન્ટ કોઈ વિષયનો ઢોંગ કરવા માટે `x-omniroute-auth-*` પૂર્વ-પોપ્યુલેટ કરી શકતા નથી.

### નીતિ કરાર

દરેક રૂટ વર્ગની `src/server/authz/policies/` માં નીતિ છે:

- **`publicPolicy`** (`policies/public.ts`) — હંમેશા `allow({ kind: "anonymous", id: "anonymous" })` પરત કરે છે.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — અર્ક બેરર, `validateApiKey()` દ્વારા માન્ય કરે છે. જ્યારે અસરકારક `REQUIRE_API_KEY` સુવિધા ફ્લેગ અક્ષમ હોય ત્યારે જ અનામી પર પડે છે. અસરકારક ધ્વજનું નિરાકરણ `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) દ્વારા કરવામાં આવે છે તેથી ડેશબોર્ડ ફીચર ફ્લેગ્સ અને પર્યાવરણ ચલો `/api/v1/*`, `/api/v1beta/*` અને ઉપનામોને સતત નિયંત્રિત કરે છે; રિઝોલ્વર નિષ્ફળતા નિષ્ફળ બંધ. ક્લાયંટ API રૂટ પર ડેશબોર્ડ-સત્ર વિનંતીઓને મંજૂરી આપે છે ( `/api/v1/models` સહિત, ડેશબોર્ડ મોડલ કેટલોગ દ્વારા ઉપયોગમાં લેવાય છે). જ્યારે Entra ID SSO સક્ષમ હોય, ત્યારે એક વાહક કે જે માળખાકીય રીતે Entra ટોકન હોય (ત્રણ base64url સેગમેન્ટ્સ, `RS*` alg, `kid`) SSO શાખા દ્વારા નિયંત્રિત થાય છે.** પહેલાં** `validateApiKey()` અને તેનો ચુકાદો અંતિમ — છે તે ક્યારેય API-કી પાથ અથવા ડિગ્રેડ-ટુ-અનામી શાખામાં આવતો નથી, તેથી ઓળખ-પ્રદાતા આઉટેજ ઓપન એક્સેસ બની શકતું નથી. સ્ટેટિક API કી અપ્રભાવિત છે. [Entra ID SSO](../security/ENTRA_SSO.md) જુઓ.
- **`managementPolicy`** (`policies/management.ts`) — ડેશબોર્ડ સત્ર, આંતરિક મોડલ-સિંક વિનંતીઓ ( `/api/providers/[name]/(sync-models|models)` સામે મેળ ખાતી) સ્વીકારે છે અથવા જો `isAuthRequired()` ખોટું પરત કરે છે તો સંપૂર્ણપણે છોડી દે છે. જ્યારે બેરર ટોકન હાજર હોય પરંતુ અમાન્ય હોય ત્યારે 403 (`AUTH_001`) પરત કરે છે, અન્યથા 401. કોઈપણ auth શાખા — [રૂટ ગાર્ડ ટિયર્સ](../security/ROUTE_GUARD_TIERS.md) જુએ તે પહેલાં રૂટ-ગાર્ડ ટિયર્સ (LOCAL_ONLY / ALWAYS_PROTECTED) ને પણ લાગુ કરે છે. `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` માં LOCAL_ONLY પાથ (આજે: `/api/mcp/`) નોન-લૂપબેકથી એક્સેસ કરી શકાય છે જ્યારે બેરર કી `manage` સ્કોપ ધરાવે છે; અન્ય તમામ LOCAL_ONLY પાથ અવકાશને ધ્યાનમાં લીધા વિના કડક-લૂપબેક રહે છે.

સફળ પોલિસી `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` સાથે `AuthSubject` પરત કરે છે. ડાઉનસ્ટ્રીમ હેન્ડલર્સ તેને ઓથ લોજિકને ફરીથી ચલાવવાને બદલે `src/server/authz/assertAuth.ts` માં `assertAuth(request, "CLIENT_API")` દ્વારા વાંચી શકે છે.

## જાહેર માર્ગોની સૂચિ

`src/shared/constants/publicApiRoutes.ts` એ સ્પષ્ટ મંજૂર સૂચિ છે:

દ્વારા યાદી વિભાજિત થયેલ છે** આકાર** , અને વિભાજન લોડ-બેરિંગ છે (GHSA-74g9-q8f6-793h): ઉપસર્ગ `startsWith()` સાથે મેળ ખાય છે, તેથી તે તેના અગ્રણી અક્ષરોને શેર કરતા દરેક અડીને આવેલા પાથ સાથે પણ મેળ ખાય છે. `/api/usage/om-usage` ઉપસર્ગ તરીકે `/api/usage/om-usage<anything>` PUBLIC ચિહ્નિત કરે છે, અને આગળ તેની પોતાની કોઈ અધિકૃતતા વિના હેન્ડલરને `/api/usage/[connectionId]` — કરવાનું નક્કી કરે છે.

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

ફક્ત વાંચવા માટેના રૂટ સાર્વજનિક છે** માત્ર** સલામત પદ્ધતિઓ માટે. નોંધ: `classifyRoute()` PUBLIC ફૉલ-થ્રુ — માંથી `/api/v1/*` અને `/api/v1beta/*` બાકાત રાખે છે તે હંમેશા `CLIENT_API` હોય છે તેથી બેરર-કી નીતિ હજુ પણ લાગુ પડે છે.

## નવો Route ઉમેરવો

### Pattern 1 — જાહેર client API endpoint (Bearer-auth)

`/api/v1/` અને `/api/v1beta/` હેઠળના routes આપમેળે `CLIENT_API` તરીકે classify થાય છે. middleware Bearer check લાગુ કરે છે; route handlers એ તેને ફરી કરવાની જરૂર નથી, પરંતુ ઉપયોગી હોય તો subject વાંચી શકે છે.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handler logic
}
```

### Pattern 2 — Management endpoint (session અથવા Bearer + manage)

`src/lib/api/requireManagementAuth.ts` માંથી `requireManagementAuth()` નો ઉપયોગ કરો:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handler logic
}
```

સફળતા પર `requireManagementAuth()` `null` પરત કરે છે અથવા JSON error `Response` પરત કરે છે:

- 401 `AUTH_001` "પ્રમાણીકરણ જરૂરી છે" — કોઈ credentials જ નથી
- 403 — અમાન્ય Bearer **અથવા** Bearer હાજર છે, પરંતુ key પાસે `manage` / `admin` scope નથી

`hasManageScope(scopes)` `"manage"` અથવા `"admin"` માટે true પરત કરે છે.

### Pattern 3 — જાહેર allowlist માં ઉમેરવું

સુવિધા અનુસાર નહીં, પણ આકાર અનુસાર set પસંદ કરો. એક route `PUBLIC_API_ROUTES_EXACT` માં જાય છે (અથવા માત્ર GET માટે `PUBLIC_READONLY_CORS_API_ROUTES` માં); માત્ર વાસ્તવિક subtree જ `PUBLIC_API_ROUTE_PREFIXES` માં જાય છે, અને તે **`/` પર સમાપ્ત થવું જ જોઈએ**. prefix સૂચિમાં એકલ route મૂકવાથી સમાન શરૂઆતના અક્ષરો ધરાવતા દરેક નજીકના path પણ જાહેર થઈ જાય છે — જેમાં પછીથી ઉમેરાયેલા dynamic-segment siblings પણ સામેલ છે (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` અને `tests/unit/authz/classify.test.ts` ખાતેના unit tests અપડેટ કરો.

## સ્કોપ્સ

ત્રણ નેમસ્પેસ. દરેક ચેકર ફક્ત તેની પોતાની સ્ટ્રિંગ્સ વાંચે છે. બાજુ-બાજુની સરખામણી, જેમાં શા માટે `manage` `read:compression` માટે `scopeMatches` માં નિષ્ફળ જાય છે અને શા માટે `read` એક્સેસ ટોકન `PATCH /api/keys/{id}` કરી શકતું નથી, તે [ત્રણ સ્કોપ નેમસ્પેસ](../frameworks/MCP-SERVER.md#three-scope-namespaces) માં છે.

API કી `scopes` એરે ધરાવે છે (જે `api_keys.scopes` માં JSON તરીકે સંગ્રહિત છે, જુઓ `src/lib/db/apiKeys.ts`).

### મેનેજમેન્ટ સ્કોપ

- `manage` / `admin` — `hasManageScope`. મેનેજમેન્ટ API રૂટ્સ માટે બેરર એક્સેસ.
- `mcp:connect`, `self:usage`, `self:account-quota`, અને `policy:bypass-provider-quota` એ એડિટિવ એક્ઝેક્ટ-મેચ સ્કોપ્સ છે. તેઓ `MANAGEMENT_API_KEY_SCOPES` ની બહાર છે. `mcp:connect` ફક્ત `/api/mcp/` નોન-લૂપબેક કાર્વ-આઉટ ખોલે છે.

### MCP ટૂલ સ્કોપ્સ

કેટલોગ અને મેચિંગ નિયમો (સમાન સ્ટ્રિંગ, અથવા `*` માં સમાપ્ત થતો ગ્રાન્ટેડ સ્કોપ): [MCP ટૂલ સ્કોપ્સ](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `src/shared/constants/mcpScopes.ts` માં `MCP_SCOPE_LIST` એ મૂળ ટાઈપ્ડ સબસેટ છે, તે સંપૂર્ણ કેટલોગ નથી. અમલીકરણ `open-sse/mcp-server/scopeEnforcement.ts` માં `resolveCallerScopeContext()` MCP ઓથ માહિતી, વિનંતી મેટાડેટા, અથવા `OMNIROUTE_MCP_SCOPES` માંથી સ્કોપ્સને રિઝોલ્વ કર્યા પછી ચાલે છે. જો `OMNIROUTE_MCP_ENFORCE_SCOPES=true` ન હોય તો તે બંધ રહે છે.

### એક્સેસ-ટોકન સ્કોપ્સ

`oma_live_…` ટોકન્સ પર `read` / `write` / `admin`, `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`) દ્વારા ક્રમાંકિત. આ ક્રમ ફક્ત એક્સેસ-ટોકન ક્રેડેન્શિયલને લાગુ પડે છે. જુઓ [મેનેજમેન્ટ ઓથેન્ટિકેશન](../guides/MANAGEMENT-AUTH.md).

## Auth Required ટૉગલ

`src/shared/utils/apiAuth.ts` માં `isAuthRequired()` નક્કી કરે છે કે કોઈ વિનંતી માટે **કોઈ પણ** પ્રમાણીકરણ લાગુ થવું જોઈએ કે નહીં:

- `settings.requireLogin === false` → પ્રમાણીકરણ વૈશ્વિક રીતે બંધ છે, સિવાય કે હંમેશા-સુરક્ષિત ટિયર (જુઓ [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) અને તે કૉલ્સ જે એવા ક્રેડેન્શિયલ આપે છે જે તે સ્વીકારે છે, જેમને લૉગિન ચાલુ હોય ત્યારે જેવો જ ક્રેડેન્શિયલ જોઈએ: સિંક ટોકન ઇશ્યૂ કરવા, કોઈ પણ સ્કોપમાં CLI એક્સેસ ટોકન બનાવવા, અને `manage`/`admin` સ્કોપવાળી API કી બનાવવી, તે સ્કોપ કોઈ કીને આપવો, અથવા એવી કી ફરીથી જનરેટ કરવી કે દેખાડવી (`src/lib/api/requireManagementAuth.ts` માં `requireCredentialForManagementScopedKey()`). ઇન્ફરન્સ-ફક્ત કીઓ ખુલ્લી રહે છે.
- કોઈ પાસવર્ડ ગોઠવાયો નથી **અને** કોઈ `INITIAL_PASSWORD` એન્વાયર્નમેન્ટ વેરિએબલ નથી → બૂટસ્ટ્રેપ મોડ ઓનબોર્ડિંગ વિઝાર્ડ અને લોકલ વિનંતીઓને મંજૂરી આપે છે, પરંતુ ખુલ્લી નેટવર્ક વિનંતીઓને હજુ પણ ક્રેડેન્શિયલ્સ જોઈએ.
- કોઈ પણ DB ભૂલ → બંધ થઈને નિષ્ફળ (secure-by-default).

ક્લાયન્ટ API કી અમલીકરણ `src/shared/utils/featureFlags.ts` માં `isRequireApiKeyEnabled()` વાપરે છે, સીધું `process.env.REQUIRE_API_KEY` વાંચતું નથી. આ તૈનાત ઇન્સ્ટન્સ માટે મહત્વનું છે: ડેશબોર્ડ → Feature Flags માં `REQUIRE_API_KEY` ટૉગલ કરવાથી DB ઓવરરાઇડ સંગ્રહાય છે અને તરત જ `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` અને આ હેલ્પર વહેંચતા અન્ય ક્લાયન્ટ-API પ્રમાણીકરણ તપાસો પર અસર કરે છે. જો ફીચર ફ્લેગ સ્ટોર વાંચી ન શકાય, તો ક્લાયન્ટ API પ્રમાણીકરણ બંધ થઈને નિષ્ફળ જાય છે અને કીની જરૂર પડે છે.

## બ્રેકિંગ ફેરફાર — v3.8.0

`/api/v1/agents/tasks/*` અને `/api/resilience/model-cooldowns` એન્ડપોઇન્ટ્સને **હવે મેનેજમેન્ટ પ્રમાણીકરણ જરૂરી છે** (કમિટ `588a0333`). અગાઉ `manage` સ્કોપ વિના સામાન્ય API કી મોકલતા ક્લાયન્ટ્સને `403` મળે છે. માઇગ્રેશન: API Keys ડૅશબોર્ડમાં કીને `manage` સ્કોપ આપો અથવા લૉગ-ઇન કરેલા ડૅશબોર્ડ સેશનનો ઉપયોગ કરો.

## વર્તન ફેરફાર — v3.8.2

`/api/mcp/*` (રિમોટ MCP સર્વર) મૂળભૂત રીતે હજુ પણ LOCAL_ONLY છે, પરંતુ હવે જ્યારે `Authorization: Bearer <api-key>` હેડરમાં `manage` સ્કોપ હોય ત્યારે તે નૉન-લૂપબૅક વિનંતીઓ સ્વીકારે છે. આ અપવાદને `src/server/authz/routeGuard.ts` માં `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` મારફતે દરેક પાથ માટે સ્પષ્ટ રીતે નિયંત્રિત કરવામાં આવે છે; સમકક્ષ LOCAL_ONLY પ્રીફિક્સ `/api/cli-tools/runtime/*` ને ઇરાદાપૂર્વક બાયપાસ કરી શકાતું નથી, કારણ કે તે મનસ્વી સબપ્રોસેસ શરૂ કરી શકે છે. નૉન-લૂપબૅકમાંથી `/api/mcp/*` માટેની અનામી વિનંતીઓ હજુ પણ `403 LOCAL_ONLY` પરત કરે છે — કોઈપણ નવા LOCAL_ONLY પાથ માટે મૂળભૂત નિયમ કડક-લૂપબૅક જ રહે છે. [રાઉટ ગાર્ડ સ્તરો](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) જુઓ.

## પરીક્ષણ

- યુનિટ પરીક્ષણો: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- જાહેર અલાઉલિસ્ટ: `tests/unit/public-api-routes.test.ts`.
- કેન્દ્રિત પરીક્ષણ ચલાવો: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## ડીબગીંગ

પાઈપલાઈન હંમેશા પ્રતિસાદોને આની સાથે સ્ટેમ્પ કરે છે:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

અધિકૃત વિનંતીઓ માટે અપસ્ટ્રીમ (હેન્ડલર-સાઇડ) વિનંતી હેડરોમાં પણ સમાવેશ થાય છે:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

હેન્ડલર્સ — ની અંદર `assertAuth(req, expectedClass)` ઉપયોગ કરો જો મિડલવેરને બાયપાસ કરવામાં આવ્યું હોય તો તે કોડ `AUTHZ_NOT_INITIALIZED` સાથે `AuthzAssertionError` ફેંકે છે (પરીક્ષણોમાં રૂપરેખાંકન રીગ્રેસનને પકડવા માટે મદદરૂપ).

## આ પણ જુઓ

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — દરેક એન્ડપોઇન્ટ દીઠ ઓથ માર્કર
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ઓથ ઇવેન્ટ્સ માટે ઓડિટ લોગ
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ત્રણ સ્કોપ નેમસ્પેસ અને MCP ટૂલ-સ્કોપ કેટલોગ
- સ્ત્રોત: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
