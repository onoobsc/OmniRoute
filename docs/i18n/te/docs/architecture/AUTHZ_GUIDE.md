# Authorization Guide (తెలుగు)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **నిజానికి మూలం:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **చివరిగా నవీకరించబడింది:** 2026-09-22 — స్కోప్ నేమ్స్పేస్లు MCP-SERVER.mdని సూచిస్తాయి

OmniRoute ప్రతి API అభ్యర్థనను నియంత్రించే రూట్-అవేర్ ఆథరైజేషన్ పైప్లైన్ను కలిగి ఉంది. వర్గీకరణ **నిర్ణయాత్మకమైనది** మరియు **ఫెయిల్-క్లోజ్డ్** — వర్గీకరించబడని ఏదైనా `MANAGEMENT`గా ముగుస్తుంది మరియు సెషన్ లేదా మేనేజ్మెంట్-గ్రేడ్ టోకెన్ను డిమాండ్ చేస్తుంది. ఈ పేజీ రూట్లను నిర్వహించే లేదా కొత్త ఎండ్పాయింట్లను రూపొందించే ఇంజనీర్ల కోసం మోడల్ను వివరిస్తుంది.

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> మూలం: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## రెండు ప్రామాణీకరణ మోడ్లు

### 1. API కీ (బేరర్)

కీ `manage` పరిధిని కలిగి ఉన్నప్పుడు OpenAI/Anthropic/Gemini-compatible క్లయింట్ APIs మరియు కొన్ని నిర్వహణ మార్గాల కోసం ఉపయోగించబడుతుంది.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` లో `isValidApiKey()` / `extractApiKey()` ద్వారా ధృవీకరించబడింది మరియు `src/shared/utils/apiAuth.ts` ద్వారా తిరిగి ఎగుమతి చేయబడుతుంది. వ్యాలిడేటర్ `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env varsను స్థిరమైన పాస్త్రూ కీలుగా కూడా అంగీకరిస్తుంది (ఇష్యూ #1350).

### 2. డాష్బోర్డ్ సెషన్ (auth_token కుక్కీ)

డాష్బోర్డ్ పేజీలు మరియు నిర్వాహక కార్యకలాపాల కోసం.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

కుకీ అనేది JWT ధృవీకరించినప్పుడు మాత్రమే సెషన్ అవుతుంది** మరియు** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`)ని కలిగి ఉంటుంది. కుక్కీ (డ్యాష్బోర్డ్ రూట్ గార్డ్ (`isDashboardSessionAuthenticated()`), authz పైప్లైన్ రిఫ్రెష్, WebSocket హ్యాండ్షేక్, లైవ్ సర్వర్, `/api/settings/require-login`, `/api/auth/status`) యొక్క ప్రతి వినియోగదారుడు ఆ సహాయకుడి గుండా వెళతారు. `JWT_SECRET` తో సంతకం చేయబడిన ఇతర JWTs — ఉన్నాయి Cursor CLI పాస్త్రూ కీ హోల్డర్స్ — కోసం `iss "omniroute" / aud "cursor-cli"` టోకెన్లు ఉన్నాయి మరియు అవి ఎప్పుడూ సెషన్లు కావు (#13298).

`src/shared/utils/apiAuth.ts` లో `isDashboardSessionAuthenticated()` ద్వారా ధృవీకరించబడింది. పైప్లైన్ దాని 30-రోజుల జీవితకాలంలో 7 రోజుల కంటే తక్కువ మిగిలి ఉన్నప్పుడు JWT ని స్వయంచాలకంగా రిఫ్రెష్ చేస్తుంది.

ఒక సెషన్ దాని 30 రోజులు ముగియకముందే ముగియవచ్చు, ఎందుకంటే ప్రతి minter `mintDashboardSessionToken` (ఒక ఇష్యూ సమయం `iat` మరియు ఒక id `jti`) గుండా వెళుతుంది మరియు వెరిఫైయర్ రెండు సెట్టింగ్లను తనిఖీ చేస్తుంది: `sessionsValidAfter`, పాస్వర్డ్ మార్పు ద్వారా సెట్ చేయబడింది, కనుక ఇది ధృవీకరించడం ఆపివేయబడుతుంది (పాస్వర్డ్ను మార్చిన బ్రౌజర్ తాజా కుక్కీని పొందుతుంది), మరియు `revokedDashboardSessions` `POST /api/auth/logout` సెషన్ను సైన్ అవుట్ చేయడానికి సైన్ అవుట్ చేయడానికి `jti` పాత విడుదల ద్వారా రూపొందించబడిన సెషన్లు దావా వేయవు మరియు మొదటి పాస్వర్డ్ మార్చే వరకు చెల్లుబాటులో ఉంటాయి. సెట్టింగ్లను చదవలేకపోతే, సెషన్ విశ్వసించబడదు.

కొన్ని నిర్వహణ మార్గాలు అంగీకరిస్తాయి** గాని** మోడ్: API కీ `manage` (లేదా `admin`) పరిధిని కలిగి ఉన్నప్పుడు కుకీ OR `Bearer <key>`. ఇది v3.8లో జోడించబడిన " API కాల్స్ ద్వారా కాన్ఫిగర్ చేయదగిన" వర్క్ఫ్లోను ప్రారంభిస్తుంది.

#### ఐచ్ఛిక OIDC లాగిన్ గేట్ (#6973)

డాష్బోర్డ్ అడ్మిన్ లాగిన్ కూడా ఒక మద్దతు ఇస్తుంది** ఎంపిక** OIDC (OpenID కనెక్ట్) ప్రవాహం డిఫాల్ట్ పాస్వర్డ్ లాగిన్ — పాస్వర్డ్ లాగిన్ ఎప్పటికీ తీసివేయబడదు, అనుబంధంగా మాత్రమే:

- `settings.oidcEnabled === true` తప్ప డిసేబుల్** మరియు** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` అన్నీ కాన్ఫిగర్ చేయబడ్డాయి (సెట్టింగ్లు → Auth). `GET /api/auth/oidc/login` లేకపోతే `400` తిరిగి వస్తుంది.
- `GET /api/auth/oidc/login` జారీచేసేవారి `/.well-known/openid-configuration` నుండి `authorization_endpoint` కనుగొంటుంది (తిరిగి `<issuer>/authorize` కి వస్తుంది), ఇన్కమింగ్ అభ్యర్థన (`x-forwarded-proto` -aware) నుండి దారిమార్పు URI నిర్మిస్తుంది మరియు `httpOnly` `oidc_state` కుక్కీలో నిల్వ చేయబడిన యాదృచ్ఛిక `state` తో IdP కి దారి మళ్లిస్తుంది.
- `GET /api/auth/oidc/callback` `state` ధృవీకరిస్తుంది, అధికార కోడ్ను మార్పిడి చేస్తుంది మరియు `issuer`/`audience` తనిఖీలతో జారీ చేసినవారి JWKS (`jose` యొక్క `createRemoteJWKSet`, JWKS URI కి కాష్ చేయబడింది) ద్వారా ID టోకెన్ సంతకాన్ని ధృవీకరిస్తుంది. డాష్బోర్డ్ ప్రవేశానికి ఖాళీ లేని `oidcAllowedSubjects` జాబితా, `oidcAdmissionClaim` విధానం లేదా రెండూ అవసరం. `email_verified === true` ఉన్నప్పుడు మాత్రమే విషయ జాబితా `sub` లేదా `email` తో సరిపోలుతుంది. ఐచ్ఛిక దావా విధానం డాట్-వేరు చేయబడిన ID-టోకెన్ క్లెయిమ్ పాత్ (ఉదాహరణకు, `realm_access.roles`) మరియు ఆమోదించబడిన విలువల శ్రేణిని తీసుకుంటుంది; పరిష్కరించబడిన దావా తప్పనిసరిగా కనీసం ఒక ఆమోదించబడిన విలువను కలిగి ఉన్న స్ట్రింగ్ల శ్రేణి అయి ఉండాలి. రెండు విధానాలు కాన్ఫిగర్ చేయబడితే, రెండూ తప్పనిసరిగా పాస్ కావాలి. Missing/malformed క్లెయిమ్లు విఫలమయ్యాయి మరియు పాలసీ లేకుండానే కాల్బ్యాక్ లాగిన్ని నిరాకరిస్తుంది (`not_configured`). ఇప్పటికే ఉన్న సబ్జెక్ట్-ఓన్లీ కాన్ఫిగరేషన్లు మారకుండా కొనసాగుతాయి.
- కీక్లోక్ సాధారణంగా రాజ్య పాత్రలను యాక్సెస్ టోకెన్లుగా మ్యాప్ చేస్తుంది, తప్పనిసరిగా ID టోకెన్లు కాదు. రియల్మ్ రోల్ `admin` అవసరం కావాలంటే, ఈ క్లయింట్లో `realm_access.roles` కలిగి ఉన్న ప్రోటోకాల్ మ్యాపర్ను కాన్ఫిగర్ చేయండి**ID టోకెన్** , ఆపై `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` కి సెట్ చేయండి. రోల్-ఓన్లీ అడ్మిషన్ను ఎనేబుల్ చేసే ముందు ఈ క్లయింట్ కోసం అసలు ID-టోకెన్ దావాను తనిఖీ చేయండి; అప్లికేషన్ యాక్సెస్-టోకెన్ పాత్రలను చదవదు. IdP-వైపు టోకెన్ తిరస్కరణ అనుబంధంగా ఉంటుంది కానీ ఈ అప్లికేషన్ వైపు తనిఖీని భర్తీ చేయదు.
- విజయంపై అది మింట్స్ ది** సరిగ్గా అదే** 30-రోజుల `auth_token` JWT పాస్వర్డ్ లాగిన్ సమస్యలు (`src/app/api/auth/login/route.ts`), కాబట్టి మిగిలిన డాష్బోర్డ్ సెషన్ పైప్లైన్ (ఆటో-రిఫ్రెష్, కుకీ ఫ్లాగ్లు) మారదు — OIDC అనేది కుక్కీ ఎలా ముద్రించబడుతుందో మాత్రమే భర్తీ చేస్తుంది, అది ఏమి మంజూరు చేస్తుందో కాదు. IdP roles/groups కి మార్పులు ఇప్పటికే ఉన్న OmniRoute సెషన్లను చెల్లుబాటు చేయవు; లాగ్అవుట్, పాస్వర్డ్ రొటేషన్ లేదా సెషన్ గడువు ఇప్పటికీ వారి జీవితకాలాన్ని నియంత్రిస్తుంది.
- ప్రతి `oidc*` సెట్టింగ్ (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`)లో ఉంటుంది: `PATCH /api/settings` `400 PASSWORD_REQUIRED` అని సమాధానం ఇస్తుంది, అది నిర్వహణ తప్పుగా ఉంటే ( `currentPassword` `401 PASSWORD_MISMATCH` నిర్వహణ పాస్వర్డ్ ఉంటే తప్ప). `oidcDisablePasswordLogin` పాస్వర్డ్ _login_ (`POST /api/auth/login`)ని నిరాకరిస్తుంది కానీ నిల్వ చేయబడిన పాస్వర్డ్ హాష్ను ఉంచుతుంది మరియు రీ-ఆథ్ ఇప్పటికీ దానికి వ్యతిరేకంగా `currentPassword` తనిఖీ చేస్తుంది.
- `corsOrigins` మరియు `bruteForceProtection` కూడా `SECURITY_IMPACTING_SETTINGS_KEYS` లో ఉన్నాయి: వదులుకోవడం లాగిన్ రక్షణను బలహీనపరుస్తుంది, కాబట్టి అవి అదే `currentPassword` పునఃప్రామాణీకరణను తీసుకుంటాయి (భద్రతా ట్యాబ్ దాని కోసం అడుగుతుంది) మరియు JSON దిగుమతి వాటిని తగ్గిస్తుంది.
- ప్రతి భద్రతా-విధాన కీ — `SECURITY_IMPACTING_SETTINGS_KEYS` ఎంట్రీలు, ప్రతి `oidc*` కీ మరియు డాష్బోర్డ్ సెషన్ స్థితి —** ఆపరేటర్-మాత్రమే** `PATCH /api/settings` లో: నిర్వహణ-స్కోప్డ్ API కీ లేదా `oma_` యాక్సెస్ టోకెన్ సరైన `currentPassword` పంపినప్పుడు కూడా `403` తో తిరస్కరించబడుతుంది మరియు తిరస్కరణ `reason: OPERATOR_REQUIRED` ( `src/lib/api/operatorCredential.ts` లో`requireOperatorCredential()` )తో `settings.update_failed` గా ఆడిట్ చేయబడుతుంది. సాధారణ సెట్టింగ్లు (థీమ్, ప్రదర్శన ప్రాధాన్యతలు) `manage` కీ లేదా `admin` యాక్సెస్ టోకెన్ కోసం వ్రాయగలిగేలా ఉంటాయి. `/api/settings` యొక్క ప్రతి మ్యుటేషన్కు (మరియు `/api/settings/require-login`) కూడా `admin` యాక్సెస్-టోకెన్ స్కోప్ అవసరం ( `src/server/authz/accessScopes.ts` లో`ADMIN_MUTATION_EXACT_PATHS`, ఖచ్చితమైన-పాత్ మ్యాచ్); `GET` స్టేస్ `read`, మరియు ఇతర `/api/settings/*` ఉప-మార్గాలు (ప్రాక్సీలు, కాంబో డిఫాల్ట్లు, మోడల్ మారుపేర్లు, కంప్రెషన్, ప్రక్షాళనలు...) పద్ధతి-అనుమానించిన `write` పరిధిని ఉంచుతాయి.
- `POST /api/settings/import-json` ఆ పునఃప్రామాణీకరణను దాటవేస్తుంది, కాబట్టి ఇది వ్రాయడానికి ముందు `IMPORT_STRIPPED_SETTINGS_KEYS` (అదే ఫైల్)లోని ప్రతి కీని వదిలివేస్తుంది: పాస్వర్డ్ మరియు `currentPassword`, ప్రతి `SECURITY_IMPACTING_SETTINGS_KEYS` ఎంట్రీ మరియు డాష్బోర్డ్ సెషన్ స్థితి (`sessionsValidAfter`, `revokedDashboardSessions`). పాత బ్యాకప్ని దిగుమతి చేయడం వలన పాస్వర్డ్ మార్పు లేదా సైన్-అవుట్ ఇప్పటికే ముగిసిన సెషన్ను పునరుద్ధరించడం సాధ్యం కాదు.

#### ఐచ్ఛిక TOTP రెండు-కారకాల లాగిన్ (#16619)

→ సెక్యూరిటీ సెట్టింగ్ల నుండి నమోదు చేయబడింది; ఆపరేటర్ దానిని ఆన్ చేసే వరకు ఆఫ్ చేయండి (`src/server/auth/dashboardMfa.ts`).

- **ఇది ఏమి కవర్ చేస్తుంది:** పాస్వర్డ్ లాగిన్ (`POST /api/auth/login`, దీనికి `POST /api/auth/mfa/verify` అవసరం) మరియు `omniroute connect` (`POST /api/cli/connect`, ఇది పాస్వర్డ్-మాత్రమే మార్పిడిని నిరాకరిస్తుంది మరియు కోడ్ను `totp` గా తీసుకుంటుంది).
- **ఇది ఏమి కవర్ చేయదు:** OIDC / SSO సైన్-ఇన్ (`/api/auth/oidc/callback`) OmniRoute TOTP కోసం అడగదు. ఇది గుర్తింపు ప్రదాత యొక్క స్వంత రెండవ అంశంపై ఆధారపడి ఉంటుంది, కాబట్టి OIDC ప్రారంభించబడితే IdP లో MFA అమలు చేయండి.
- **రికవరీ** (పోగొట్టుకున్న పరికరం, రికవరీ కోడ్లు ఏవీ మిగిలి లేవు లేదా ఇకపై ధృవీకరించబడని అంశం, ఉదాహరణకు `STORAGE_ENCRYPTION_KEY` మార్చబడిన తర్వాత):
  1. `OMNIROUTE_DISABLE_MFA=true` తో సర్వర్ని పునఃప్రారంభించండి.
  2. హోస్ట్లోనే (లూప్బ్యాక్ పీర్ మరియు లూప్బ్యాక్ `Host`, `http://localhost:20128` వంటివి), పాస్వర్డ్తో సైన్ ఇన్ చేయండి. రెండవ అంశం ఆ మూలానికి మాత్రమే దాటవేయబడింది; ప్రతి ఇతర మూలానికి ఇప్పటికీ కోడ్ అవసరం.
  3. సెట్టింగ్లలో → సెక్యూరిటీ → డిసేబుల్, పాస్వర్డ్ను నమోదు చేసి, కోడ్ను ఖాళీగా ఉంచండి. వేరియబుల్ సెట్ చేయబడినప్పుడు మరియు హోస్ట్ నుండి అభ్యర్థన వచ్చినప్పుడు మాత్రమే `POST /api/auth/mfa/disable` `code` లేని శరీరాన్ని అంగీకరిస్తుంది; దీనికి ఇప్పటికీ డాష్బోర్డ్ సెషన్ మరియు ప్రస్తుత పాస్వర్డ్ అవసరం మరియు `secondFactor: "recovery_switch"` తో `auth.mfa.disabled` గా ఆడిట్ చేయబడుతుంది.
  4. `OMNIROUTE_DISABLE_MFA` సెట్ని తీసివేయండి, పునఃప్రారంభించండి మరియు అవసరమైతే మళ్లీ నమోదు చేయండి.

## రూట్ తరగతులు

`src/server/authz/types.ts` మూడు తరగతులను నిర్వచిస్తుంది; నిర్ణయాత్మకంగా వర్గీకరించలేని ఏ route అయినా `MANAGEMENT`కు తిరిగి వెళ్తుంది.

| Class        | Description                                                                                                                                           | Auth required                                                            |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| `PUBLIC`     | స్పష్టంగా సురక్షితమైన routes — login, logout, status, init, health, onboarding bootstrap.                                                             | ఏదీ అవసరం లేదు                                                           |
| `CLIENT_API` | Model-serving endpoints — `/api/v1/*`, `/api/v1beta/*`, మరియు aliases `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | `REQUIRE_API_KEY` feature flag ప్రభావవంతంగా ఆన్‌లో ఉన్నప్పుడు Bearer key |
| `MANAGEMENT` | Dashboard పేజీలు, settings, providers, keys, admin మరియు diagnostics endpoints.                                                                       | Dashboard session లేదా `manage` scope ఉన్న Bearer                        |

కొన్ని `MANAGEMENT` చర్యలు **operator-only**: `manage` key సరిపోదు. నిల్వ చేసిన credentials ఎగుమతి (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), live data పై backup ను పునరుద్ధరించడం (`dryRun=true` తో సహా `POST /api/db-backups/import`, id ద్వారా `POST /api/db-backups` restore, `POST /api/settings/import-json`), restore points ను నాశనం చేయడం (`DELETE /api/db-backups` cleanup, మరియు `PATCH /api/db-backups` ఎందుకంటే అది నిల్వ చేసే retention ప్రతి backup తర్వాత స్వయంచాలక తొలగింపును నడుపుతుంది) వంటి వాటికి dashboard session, స్థానిక CLI subject, లేదా login నిలిపివేయబడి ఉండటం అవసరం. Sync token జారీ (`POST /api/sync/tokens`) మరియు `admin` CLI access token తయారు చేయడం (`POST /api/cli/tokens`) ప్రతి login mode లో dashboard session లేదా స్థానిక CLI subject అవసరం. ఏ scope అయినా API keys మరియు `oma_` access tokens operator credentials కావు: అవసరమైనప్పుడెల్లా వాటికి `403` వస్తుంది. ఈ తనిఖీ `src/lib/api/operatorCredential.ts`లో ఉంది (`resolveOperatorCredential()` / `requireOperatorCredential()`). Login settings మార్చడం కూడా operator-only: పాస్‌వర్డ్ ఇప్పటికే ఉంటే `POST /api/settings/require-login` (మేనేజ్‌మెంట్ పాస్‌వర్డ్ సెట్ చేయడం / `requireLogin` టోగుల్ చేయడం) ఆ credentials నే అంగీకరిస్తుంది — పాస్‌వర్డ్ లేని మొదటి-రన్ bootstrap విండో మారదు — మరియు పాస్‌వర్డ్‌ను మార్చడానికి dashboard session `currentPassword` పంపాలి (అది లేకపోయినా లేదా తప్పుగా ఉన్నా `403`, `settings.update_failed` గా ఆడిట్ చేయబడుతుంది). స్థానిక CLI మరియు login నిలిపివేయబడిన instance రికవరీ మార్గాన్ని ఉంచుతాయి; అవి data directory ను కలిగి ఉన్న host కు బంధించబడి ఉన్నాయి కాబట్టి, అది లేకుండానే పాస్‌వర్డ్ సెట్ చేయవచ్చు.

## పైప్లైన్

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

విశ్వసనీయ అంతర్గత శీర్షికలు ( `src/server/authz/headers.ts` లో నిర్వచించబడ్డాయి).** ఇన్కమింగ్ అభ్యర్థనల నుండి తీసివేయబడింది** వర్గీకరణకు ముందు — క్లయింట్లు ఒక సబ్జెక్ట్గా నటించడానికి `x-omniroute-auth-*` ప్రీ-పాపులేట్ చేయలేరు.

### విధాన ఒప్పందాలు

ప్రతి రూట్ క్లాస్ `src/server/authz/policies/` లో ఒక విధానాన్ని కలిగి ఉంటుంది:

- **`publicPolicy`** (`policies/public.ts`) — ఎల్లప్పుడూ `allow({ kind: "anonymous", id: "anonymous" })` ని అందిస్తుంది.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ఎక్స్ట్రాక్ట్స్ బేరర్, `validateApiKey()` ద్వారా చెల్లుబాటు అవుతుంది. ప్రభావవంతమైన `REQUIRE_API_KEY` ఫీచర్ ఫ్లాగ్ నిలిపివేయబడినప్పుడు మాత్రమే అనామకులకు వస్తుంది. ప్రభావవంతమైన ఫ్లాగ్ `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ద్వారా పరిష్కరించబడుతుంది కాబట్టి డాష్బోర్డ్ ఫీచర్ ఫ్లాగ్లు మరియు ఎన్విరాన్మెంట్ వేరియబుల్స్ `/api/v1/*`, `/api/v1beta/*` మరియు మారుపేర్లను స్థిరంగా నియంత్రిస్తాయి; పరిష్కర్త వైఫల్యాలు విఫలమవుతాయి. క్లయింట్ API మార్గాల్లో డాష్బోర్డ్-సెషన్ అభ్యర్థనలను అనుమతిస్తుంది (డ్యాష్బోర్డ్ మోడల్ కేటలాగ్ ద్వారా ఉపయోగించబడుతుంది `/api/v1/models` తో సహా). Entra ID SSO ప్రారంభించబడినప్పుడు, నిర్మాణాత్మకంగా Entra టోకెన్ అయిన బేరర్ (మూడు base64url విభాగాలు, `RS*` alg, `kid`) SSO శాఖ ద్వారా నిర్వహించబడుతుంది.** ముందు** `validateApiKey()` మరియు దాని తీర్పు తుది — ఇది API-కీ మార్గం లేదా అనామక బ్రాంచ్కి దిగజారదు, కాబట్టి గుర్తింపు ప్రదాత అంతరాయం ఓపెన్ యాక్సెస్గా మారదు. స్టాటిక్ API కీలు ప్రభావితం కావు. [ఎంట్రా ID SSO](../security/ENTRA_SSO.md) చూడండి.
- **`managementPolicy`** (`policies/management.ts`) — డాష్బోర్డ్ సెషన్, అంతర్గత మోడల్-సమకాలీకరణ అభ్యర్థనలను ( `/api/providers/[name]/(sync-models|models)` కి వ్యతిరేకంగా సరిపోల్చింది) అంగీకరిస్తుంది లేదా `isAuthRequired()` తప్పు అని తిరిగి ఇస్తే పూర్తిగా దాటవేస్తుంది. బేరర్ టోకెన్ ఉన్నప్పటికీ చెల్లదు, 401 లేకపోతే 403 (`AUTH_001`)ని అందిస్తుంది. ఏదైనా auth బ్రాంచ్ — ముందు రూట్-గార్డ్ టైర్లను (LOCAL_ONLY / ALWAYS_PROTECTED) అమలు చేస్తుంది, [రూట్ గార్డ్ టైర్లను](../security/ROUTE_GUARD_TIERS.md) చూడండి. బేరర్ కీ `manage` స్కోప్ను కలిగి ఉన్నప్పుడు `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (ఈనాడు: `/api/mcp/`)లోని LOCAL_ONLY మార్గాలు నాన్-లూప్బ్యాక్ నుండి యాక్సెస్ చేయబడవచ్చు; స్కోప్తో సంబంధం లేకుండా అన్ని ఇతర LOCAL_ONLY మార్గాలు కఠినమైన-లూప్బ్యాక్గా ఉంటాయి.

విజయవంతమైన పాలసీ `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` తో `AuthSubject` ని అందిస్తుంది. డౌన్స్ట్రీమ్ హ్యాండ్లర్లు ప్రామాణీకరణ తర్కాన్ని మళ్లీ అమలు చేయడానికి బదులుగా `src/server/authz/assertAuth.ts` లో `assertAuth(request, "CLIENT_API")` ద్వారా చదవగలరు.

## పబ్లిక్ రూట్ల జాబితా

`src/shared/constants/publicApiRoutes.ts` అనేది స్పష్టమైన అనుమతి జాబితా:

జాబితా విభజించబడింది** ఆకారం** , మరియు స్ప్లిట్ లోడ్-బేరింగ్ (GHSA-74g9-q8f6-793h): ఒక ఉపసర్గ `startsWith()` తో సరిపోలుతుంది, కాబట్టి ఇది దాని ప్రముఖ పాత్రలను పంచుకునే ప్రతి ప్రక్కనే ఉన్న మార్గానికి కూడా సరిపోతుంది. `/api/usage/om-usage` ఉపసర్గగా `/api/usage/om-usage<anything>` PUBLIC గా గుర్తించబడింది మరియు తదుపరిది `/api/usage/[connectionId]` — హ్యాండ్లర్ని దాని స్వంత ప్రమాణీకరణ లేకుండా పరిష్కరిస్తుంది.

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

చదవడానికి మాత్రమే మార్గాలు పబ్లిక్** మాత్రమే** సురక్షితమైన పద్ధతుల కోసం. గమనిక: `classifyRoute()` PUBLIC ఫాల్-త్రూ — నుండి `/api/v1/*` మరియు `/api/v1beta/*` మినహాయించింది, అవి ఎల్లప్పుడూ `CLIENT_API` కాబట్టి బేరర్-కీ విధానం ఇప్పటికీ వర్తిస్తుంది.

## కొత్త రూట్ను జోడించడం

### నమూనా 1 — పబ్లిక్ క్లయింట్ API ఎండ్పాయింట్ (Bearer ఆథెంటికేషన్)

`/api/v1/` మరియు `/api/v1beta/` కింద ఉన్న రూట్లు స్వయంచాలకంగా `CLIENT_API`గా వర్గీకరించబడతాయి. మిడిల్వేర్ Bearer తనిఖీని అమలు చేస్తుంది; రూట్ హ్యాండ్లర్లు దాన్ని మళ్లీ చేయాల్సిన అవసరం లేదు, కానీ ఉపయోగకరమైతే సబ్జెక్ట్ను చదవవచ్చు.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... హ్యాండ్లర్ లాజిక్
}
```

### నమూనా 2 — నిర్వహణ ఎండ్పాయింట్ (సెషన్ లేదా Bearer + manage)

`src/lib/api/requireManagementAuth.ts` నుండి `requireManagementAuth()`ను ఉపయోగించండి:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... హ్యాండ్లర్ లాజిక్
}
```

విజయవంతమైనప్పుడు `requireManagementAuth()` `null`ను, లేకపోతే JSON ఎర్రర్ `Response`ను తిరిగి ఇస్తుంది:

- 401 `AUTH_001` "ఆథెంటికేషన్ అవసరం" — ఎలాంటి క్రెడెన్షియల్స్ లేవు
- 403 — చెల్లని Bearer **లేదా** Bearer ఉన్నప్పటికీ కీకి `manage` / `admin` స్కోప్ లేదు

`hasManageScope(scopes)` అనేది `"manage"` లేదా `"admin"` కోసం trueను తిరిగి ఇస్తుంది.

### నమూనా 3 — పబ్లిక్ అనుమతి జాబితాకు జోడించడం

సౌలభ్యం ఆధారంగా కాకుండా, ఆకృతి ఆధారంగా సెట్ను ఎంచుకోండి. ఒక రూట్ను `PUBLIC_API_ROUTES_EXACT`లో ఉంచాలి (లేదా GET-మాత్రమే అయితే `PUBLIC_READONLY_CORS_API_ROUTES`లో); నిజమైన సబ్ట్రీని మాత్రమే `PUBLIC_API_ROUTE_PREFIXES`లో ఉంచాలి, అలాగే అది **తప్పనిసరిగా `/`తో ముగియాలి**. ఒకే రూట్ను ప్రిఫిక్స్ జాబితాలో ఉంచడం వల్ల, దాని ప్రారంభ అక్షరాలను పంచుకునే ప్రతి సమీప పాత్ కూడా పబ్లిక్ అవుతుంది — భవిష్యత్తులో జోడించే డైనమిక్-సెగ్మెంట్ సిబ్లింగ్లతో సహా (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` మరియు `tests/unit/authz/classify.test.ts` వద్ద ఉన్న యూనిట్ టెస్ట్లను నవీకరించండి.

## స్కోప్లు

మూడు నేమ్స్పేస్లు. ప్రతి చెకర్ దాని స్వంత స్ట్రింగ్లను మాత్రమే చదువుతుంది. పక్కపక్కన, `read:compression` కోసం `manage` ఎందుకు `scopeMatches`లో విఫలమవుతుంది మరియు `read` యాక్సెస్ టోకెన్ `PATCH /api/keys/{id}` చేయలేకపోవడానికి కారణంతో సహా, [మూడు స్కోప్ నేమ్స్పేస్లు](../frameworks/MCP-SERVER.md#three-scope-namespaces)లో ఉంది.

API కీలు `scopes` శ్రేణిని కలిగి ఉంటాయి (`api_keys.scopes`లో JSONగా నిల్వ చేయబడతాయి, `src/lib/db/apiKeys.ts` చూడండి).

### మేనేజ్మెంట్ స్కోప్

- `manage` / `admin` — `hasManageScope`. మేనేజ్మెంట్ API రూట్లకు బేరర్ యాక్సెస్.
- `mcp:connect`, `self:usage`, `self:account-quota`, మరియు
  `policy:bypass-provider-quota` అనేవి అడిటివ్ ఎగ్జాక్ట్-మ్యాచ్ స్కోప్లు. అవి
  `MANAGEMENT_API_KEY_SCOPES` వెలుపల ఉంటాయి. `mcp:connect` కేవలం `/api/mcp/`
  నాన్-లూప్బ్యాక్ కార్వ్-అవుట్ను మాత్రమే తెరుస్తుంది.

### MCP టూల్ స్కోప్లు

కేటలాగ్ మరియు సరిపోలే నియమాలు (ఒకే స్ట్రింగ్, లేదా `*`తో ముగిసే మంజూరు చేయబడిన స్కోప్):
[MCP టూల్ స్కోప్లు](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`src/shared/constants/mcpScopes.ts`లోని `MCP_SCOPE_LIST` అనేది అసలు టైప్ చేయబడిన
సబ్సెట్, పూర్తి కేటలాగ్ కాదు. `resolveCallerScopeContext()` MCP ప్రామాణీకరణ
సమాచారం, అభ్యర్థన మెటాడేటా లేదా `OMNIROUTE_MCP_SCOPES` నుండి స్కోప్లను
పరిష్కరించిన తర్వాత `open-sse/mcp-server/scopeEnforcement.ts`లో అమలు జరుగుతుంది.
`OMNIROUTE_MCP_ENFORCE_SCOPES=true` కాకపోతే అది నిలిపివేయబడుతుంది.

### యాక్సెస్-టోకెన్ స్కోప్లు

`oma_live_…` టోకెన్లపై `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) ద్వారా ర్యాంక్ చేయబడతాయి. ఈ ర్యాంక్
యాక్సెస్-టోకెన్ క్రెడెన్షియల్కు మాత్రమే వర్తిస్తుంది. [మేనేజ్మెంట్ ప్రామాణీకరణ](../guides/MANAGEMENT-AUTH.md) చూడండి.

## Auth Required టోగుల్

`src/shared/utils/apiAuth.ts`లోని `isAuthRequired()` ఒక request కు **ఏదైనా** auth అమలు చేయాలా వద్దా అని నిర్ణయిస్తుంది:

- `settings.requireLogin === false` → auth ప్రపంచవ్యాప్తంగా నిలిపివేయబడుతుంది, కానీ ఎల్లప్పుడూ-రక్షిత శ్రేణి ([Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) మినహా, మరియు అంగీకరించే credential ను జారీ చేసే calls మినహా — login ఆన్‌లో ఉన్నప్పుడు అవసరమయ్యే అదే credential కావాలి: sync tokens జారీ చేయడం, ఏ scope లోనైనా CLI access tokens తయారు చేయడం, మరియు `manage`/`admin` scope ఉన్న API key ను సృష్టించడం, ఒక key కు ఆ scope ఇవ్వడం, లేదా అలాంటి key ను రీజెనరేట్ చేయడం లేదా బహిర్గతం చేయడం (`src/lib/api/requireManagementAuth.ts`లోని `requireCredentialForManagementScopedKey()`). Inference-only keys తెరిచే ఉంటాయి.
- పాస్‌వర్డ్ కాన్ఫిగర్ కాలేదు **మరియు** `INITIAL_PASSWORD` env var లేదు → bootstrap mode onboarding wizard ను మరియు loopback requests ను అనుమతిస్తుంది, కానీ బహిర్గతమైన network requests కు ఇంకా credentials అవసరం.
- ఏదైనా DB error → fail closed (secure-by-default).

Client API key అమలు, నేరుగా `process.env.REQUIRE_API_KEY`ని చదవకుండా, `src/shared/utils/featureFlags.ts`లోని `isRequireApiKeyEnabled()`ను ఉపయోగిస్తుంది. ఇది deployed instances కు ముఖ్యం: Dashboard → Feature Flags లో `REQUIRE_API_KEY`ను టోగుల్ చేస్తే DB override నిల్వ అవుతుంది మరియు `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, ఈ helper ను పంచుకునే ఇతర client-API auth తనిఖీలు వెంటనే ప్రభావితమవుతాయి. Feature flag store చదవలేకపోతే, client API auth fail closed అవుతుంది మరియు key ను కోరుతుంది.

## బ్రేకింగ్ మార్పు — v3.8.0

`/api/v1/agents/tasks/*` మరియు `/api/resilience/model-cooldowns` ఎండ్పాయింట్లకు **ఇప్పుడు నిర్వహణ ప్రమాణీకరణ అవసరం** (కమిట్ `588a0333`). గతంలో `manage` స్కోప్ లేని సాధారణ API కీని పంపిన క్లయింట్లు `403`ను అందుకుంటారు. మైగ్రేషన్: API Keys డ్యాష్బోర్డ్లో కీకి `manage` స్కోప్ను కేటాయించండి లేదా లాగిన్ చేసిన డ్యాష్బోర్డ్ సెషన్ను ఉపయోగించండి.

## ప్రవర్తన మార్పు — v3.8.2

`/api/mcp/*` (రిమోట్ MCP సర్వర్) ఇప్పటికీ డిఫాల్ట్గా LOCAL_ONLYగా ఉంటుంది, కానీ `Authorization: Bearer <api-key>` హెడర్లో `manage` స్కోప్ ఉన్నప్పుడు ఇప్పుడు లూప్బ్యాక్ కాని అభ్యర్థనలను అంగీకరిస్తుంది. `src/server/authz/routeGuard.ts`లోని `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ద్వారా ఈ మినహాయింపు ప్రతి పాత్కు స్పష్టంగా నియంత్రించబడుతుంది; సమాన స్థాయి LOCAL_ONLY ప్రిఫిక్స్ `/api/cli-tools/runtime/*` ఏవైనా సబ్ప్రాసెస్లను ప్రారంభించగలదు కాబట్టి, దాన్ని ఉద్దేశపూర్వకంగానే బైపాస్ చేయడం సాధ్యం కాదు. లూప్బ్యాక్ కాని చోట్ల నుండి `/api/mcp/*`కు వచ్చే అనామక అభ్యర్థనలు weiterhin `403 LOCAL_ONLY`ను అందుకుంటాయి — ఏదైనా కొత్త LOCAL_ONLY పాత్కు డిఫాల్ట్గా కఠినమైన లూప్బ్యాక్ నియమమే వర్తిస్తుంది. [రూట్ గార్డ్ స్థాయిలు](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) చూడండి.

## టెస్టింగ్

- యూనిట్ టెస్ట్లు: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- పబ్లిక్ అనుమతి జాబితా: `tests/unit/public-api-routes.test.ts`.
- నిర్దిష్ట టెస్ట్ను అమలు చేయడానికి: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## డీబగ్గింగ్

పైప్లైన్ ఎల్లప్పుడూ దీనితో ప్రతిస్పందనలను స్టాంప్ చేస్తుంది:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

ప్రామాణీకరించబడిన అభ్యర్థనల కోసం అప్స్ట్రీమ్ (హ్యాండ్లర్-సైడ్) అభ్యర్థన శీర్షికలు కూడా ఉన్నాయి:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

మిడిల్వేర్ బైపాస్ చేయబడితే (పరీక్షలలో కాన్ఫిగరేషన్ `AUTHZ_NOT_INITIALIZED` క్యాచ్ చేయడంలో సహాయపడుతుంది) హ్యాండ్లర్స్ — లోపల `assertAuth(req, expectedClass)` `AuthzAssertionError`.

## వీటిని కూడా చూడండి

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ప్రతి ఎండ్పాయింట్కు ప్రామాణీకరణ మార్కర్
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ప్రామాణీకరణ ఈవెంట్ల కోసం ఆడిట్ లాగ్
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — మూడు స్కోప్ నేమ్స్పేస్లు మరియు MCP టూల్-స్కోప్ కేటలాగ్
- మూలం: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
