# Authorization Guide (ଓଡ଼ିଆ)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **ସତ୍ୟର ଉତ୍ସ:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **ଶେଷ ଅପଡେଟ୍:** 2026-09-22 — ସ୍କୋପ୍ ନାମସ୍ପେସ୍ MCP-SERVER.md କୁ ସୂଚାଏ

OmniRoute ରେ ଏକ ରୁଟ୍-ସଚେତନ ଅନୁମତି ପାଇପଲାଇନ୍ ଅଛି ଯାହା ପ୍ରତ୍ୟେକ API ଅନୁରୋଧକୁ ଗେଟ୍ କରେ। ବର୍ଗୀକରଣ **ନିର୍ଣ୍ଣାୟକ** ଏବଂ **ଫେଲ୍-କ୍ଲୋଜ୍ଡ** — ଯାହା ବର୍ଗୀକୃତ ହୋଇପାରିବ ନାହିଁ ତାହା `MANAGEMENT` ଭାବରେ ଶେଷ ହୁଏ ଏବଂ ଏକ ସେସନ୍ କିମ୍ବା ମ୍ୟାନେଜମେଣ୍ଟ-ଗ୍ରେଡ୍ ଟୋକେନ୍ ଆବଶ୍ୟକ କରେ। ଏହି ପୃଷ୍ଠାଟି ରୁଟ୍ ରକ୍ଷଣାବେକ୍ଷଣ କରୁଥିବା କିମ୍ବା ନୂତନ ଏଣ୍ଡପଏଣ୍ଟ୍ ଡିଜାଇନ୍ କରୁଥିବା ଇଞ୍ଜିନିୟରମାନଙ୍କ ପାଇଁ ମଡେଲ୍ ବ୍ୟାଖ୍ୟା କରେ।

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> ଉତ୍ସ: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## ଦୁଇଟି Auth ମୋଡ୍।

### 1। API କି (ଧାରକ)

OpenAI/Anthropic/Gemini-compatible କ୍ଲାଏଣ୍ଟ APIs ଏବଂ କିଛି ପରିଚାଳନା ମାର୍ଗ ପାଇଁ ବ୍ୟବହୃତ ହୁଏ ଯେତେବେଳେ ଚାବିର `manage` ପରିସର ଥାଏ।

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` ରେ `isValidApiKey()` / `extractApiKey()` ଦ୍ୱାରା ବ Val ଧ ଏବଂ `src/shared/utils/apiAuth.ts` ମାଧ୍ୟମରେ ପୁନ export ରପ୍ତାନି। ବ valid ଧତାକାରୀ `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars କୁ ସ୍ଥାୟୀ ପାସ୍ ଚାବି ଭାବରେ ଗ୍ରହଣ କରେ ( #1350 ଇସ୍ୟୁ)।

### 2। ଡ୍ୟାସବୋର୍ଡ ଅଧିବେଶନ (auth_token କୁକି)

ଡ୍ୟାସବୋର୍ଡ ପୃଷ୍ଠା ଏବଂ ଆଡମିନି ଅପରେସନ୍ ପାଇଁ।

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

JWT ଯାଞ୍ଚ କଲାବେଳେ ଏକ କୁକି ହେଉଛି ଏକ ଅଧିବେଶନ।** ଏବଂ** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) ବହନ କରେ। କୁକିର ପ୍ରତ୍ୟେକ ଗ୍ରାହକ (ଡ୍ୟାସବୋର୍ଡ ରୁଟ୍ ଗାର୍ଡ (`isDashboardSessionAuthenticated()`), authz ପାଇପଲାଇନ ସତେଜ, WebSocket ହ୍ୟାଣ୍ଡସେକ, ଲାଇଭ ସର୍ଭର, `/api/settings/require-login`, `/api/auth/status`) ସେହି ହେଲପର ଦେଇ ଯାଆନ୍ତି। `JWT_SECRET` ସହିତ ସ୍ signed ାକ୍ଷରିତ ଅନ୍ୟ JWTs ବିଦ୍ୟମାନ ଅଛି — Cursor ପାସ୍ଟ୍ରୋ ମାଇନ୍ସ `iss "omniroute" / aud "cursor-cli"` ପ୍ରମୁଖ ଧାରକମାନଙ୍କ ପାଇଁ — ଟୋକେନ୍ ଏବଂ କଦାପି ଅଧିବେଶନ ନୁହେଁ (#13298) CLI

`src/shared/utils/apiAuth.ts` ରେ `isDashboardSessionAuthenticated()` ଦ୍ୱାରା ଯାଞ୍ଚ କରାଯାଇଛି। ପାଇପଲାଇନ JWT କୁ ସ୍ auto ତ - ସତେଜ କରେ ଯେତେବେଳେ ଏହାର 30 ଦିନର ଜୀବନକାଳରେ 7 ଦିନରୁ କମ୍ ସମୟ ରହିଥାଏ।

ଏହାର 30 ଦିନ ଶେଷ ହେବା ପୂର୍ବରୁ ଏକ ଅଧିବେଶନ ମଧ୍ୟ ଶେଷ ହୋଇପାରେ, କାରଣ ପ୍ରତ୍ୟେକ ମିନିଟର `mintDashboardSessionToken` (ଏକ ଇସୁ ଟାଇମ୍ `iat` ଏବଂ ଏକ id `jti`) ଦେଇ ଯାଆନ୍ତି ଏବଂ ଯାଞ୍ଚକାରୀ ଦୁଇଟି ସେଟିଂ ଯାଞ୍ଚ କରନ୍ତି: `sessionsValidAfter`, ପାସୱାର୍ଡ ପରିବର୍ତ୍ତନ ଦ୍ set ାରା ସେଟ୍ ହୋଇଛି ତେଣୁ ଯାଞ୍ଚ ବନ୍ଦ ହେବା ପୂର୍ବରୁ ଜାରି କରାଯାଇଥିବା ପ୍ରତ୍ୟେକ ଅଧିବେଶନ (ପାସୱାର୍ଡ ବଦଳାଇଥିବା ବ୍ରାଉଜର୍ ଏକ ନୂତନ କୁକି ପାଇଥାଏ), ଏବଂ `revokedDashboardSessions`, ଯେଉଁଥିରେ `POST /api/auth/logout` ସାଇନ୍-ଆଉଟ୍ ଅଧିବେଶନ `jti` କରିଥାଏ। ପୁରାତନ ପ୍ରକାଶନ ଦ୍ int ାରା ପ୍ରସ୍ତୁତ ଅଧିବେଶନଗୁଡ଼ିକ କ claim ଣସି ଦାବି ବହନ କରେ ନାହିଁ ଏବଂ ପ୍ରଥମ ପାସୱାର୍ଡ ପରିବର୍ତ୍ତନ ନହେବା ପର୍ଯ୍ୟନ୍ତ ବ valid ଧ ରହିଥାଏ। ଯଦି ସେଟିଂସମୂହ ପ read ିହେବ ନାହିଁ, ଅଧିବେଶନ ବିଶ୍ୱାସଯୋଗ୍ୟ ନୁହେଁ।

କିଛି ପରିଚାଳନା ମାର୍ଗ ଗ୍ରହଣ କରେ।** କିମ୍ବା** ମୋଡ୍: କୁକି OR `Bearer <key>` ଯେତେବେଳେ API କିରେ `manage` (କିମ୍ବା `admin`) ପରିସର ଥାଏ। ଏହା ହେଉଛି v3.8 ରେ ଯୋଗ କରାଯାଇଥିବା “ API କଲ୍ ମାଧ୍ୟମରେ ବିନ୍ୟାସଯୋଗ୍ୟ” ୱାର୍କଫ୍ଲୋକୁ ସକ୍ଷମ କରିଥାଏ।

#### ବ tion କଳ୍ପିକ OIDC ଲଗଇନ୍ ଗେଟ୍ (#6973)

ଡ୍ୟାସବୋର୍ଡ ଆଡମିନି ଲଗଇନ୍ ମଧ୍ୟ ଏକ ସମର୍ଥନ କରେ।** ଅପ୍ଟ-ଇନ୍** OIDC (OpenID ସଂଯୋଗ) ଡିଫଲ୍ଟ ପାସୱାର୍ଡ ଲଗଇନ୍ ସହିତ ପ୍ରବାହ — ପାସୱାର୍ଡ ଲଗଇନ୍ କେବେବି ଅପସାରିତ ହୁଏ ନାହିଁ, କେବଳ ସପ୍ଲିମେଣ୍ଟ ହୋଇଛି:

- `settings.oidcEnabled === true` ନହେବା ପର୍ଯ୍ୟନ୍ତ ଅକ୍ଷମ।** ଏବଂ** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` ସମସ୍ତ ବିନ୍ୟାସିତ ହୋଇଛି (ସେଟିଂସମୂହ → Auth)। `GET /api/auth/oidc/login` ଅନ୍ୟଥା `400` ରିଟର୍ନ କରେ।
- `GET /api/auth/oidc/login` ପ୍ରଦାନକାରୀଙ୍କ `/.well-known/openid-configuration` ରୁ `authorization_endpoint` ଆବିଷ୍କାର କରେ ( `<issuer>/authorize` କୁ ଫେରିଯାଏ), ଆସୁଥିବା ଅନୁରୋଧ (`x-forwarded-proto` -aware) ରୁ ପୁନ ir ନିର୍ଦ୍ଦେଶ URI ନିର୍ମାଣ କରେ, ଏବଂ `httpOnly` `oidc_state` କୁକିରେ ସଂରକ୍ଷିତ ଏକ `state` ସହିତ IdP କୁ ପୁନ ir ନିର୍ଦ୍ଦେଶ କରେ।
- `GET /api/auth/oidc/callback` `state` ID JWKS `jose` `createRemoteJWKSet` JWKS URI `issuer` `audience` ଡ୍ୟାସବୋର୍ଡ ଆଡମିଶନ ଏକ ଅଣମୁକ୍ତ `oidcAllowedSubjects` ତାଲିକା, ଏକ `oidcAdmissionClaim` ନୀତି କିମ୍ବା ଉଭୟ ଆବଶ୍ୟକ କରେ। ବିଷୟ ତାଲିକା `sub` କିମ୍ବା `email` ସହିତ ମେଳ ହୁଏ ଯେତେବେଳେ `email_verified === true` ବ option କଳ୍ପିକ ଦାବି ନୀତି ଏକ ବିନ୍ଦୁ-ପୃଥକ ID- ଟୋକେନ୍ ଦାବି ପଥ (ଉଦାହରଣ ସ୍ୱରୂପ, `realm_access.roles`) ଏବଂ ଗ୍ରହଣୀୟ ମୂଲ୍ୟଗୁଡ଼ିକର ଏକ ଆରେ ନେଇଥାଏ। ସମାଧାନ ହୋଇଥିବା ଦାବି ଅତିକମରେ ଗୋଟିଏ ଗ୍ରହଣୀୟ ମୂଲ୍ୟ ଧାରଣ କରିଥିବା ଷ୍ଟ୍ରିଙ୍ଗଗୁଡିକର ଏକ ଆରେ ହେବା ଜରୁରୀ। ଯଦି ଉଭୟ ନୀତି ବିନ୍ୟାସିତ ହୋଇଛି, ଉଭୟ ନିଶ୍ଚିତ ଭାବରେ ପାସ୍ କରିବେ। Missing/malformed ଦାବି ବନ୍ଦ ବିଫଳ ହୋଇଛି, ଏବଂ କ policy ଣସି ନୀତି ବିନା କଲବ୍ୟାକ୍ ଲଗଇନ୍ (`not_configured`) କୁ ପ୍ରତ୍ୟାଖ୍ୟାନ କରେ। ବିଦ୍ୟମାନ ବିଷୟ-କେବଳ ବିନ୍ୟାସଗୁଡ଼ିକ ଅପରିବର୍ତ୍ତିତ ରହିଛି।
- କୀକ୍ଲୋକ୍ ସାଧାରଣତ real ଆକ୍ସେସ୍ ଟୋକେନ୍ରେ କ୍ଷେତ୍ର ଭୂମିକା ମାନଚିତ୍ର କରେ, ଅବଶ୍ୟ ID ଟୋକେନ୍ ନୁହେଁ। `admin` ଭୂମିକା ଆବଶ୍ୟକ କରିବାକୁ, ଏହି କ୍ଲାଏଣ୍ଟ ପାଇଁ ଏକ ପ୍ରୋଟୋକଲ୍ ମ୍ୟାପର୍ ବିନ୍ୟାସ କରନ୍ତୁ ଯେଉଁଥିରେ `realm_access.roles` ଅନ୍ତର୍ଭୂକ୍ତ କରେ।**ID ଟୋକେନ୍।** , ତାପରେ `oidcAdmissionClaim` କୁ `{ "path": "realm_access.roles", "values": ["admin"] }` ରେ ସେଟ୍ କରନ୍ତୁ। କେବଳ ଭୂମିକା ଆଡମିଶନ ସକ୍ଷମ କରିବା ପୂର୍ବରୁ ଏହି କ୍ଲାଏଣ୍ଟ ପାଇଁ ପ୍ରକୃତ ID- ଟୋକେନ୍ ଦାବି ଯାଞ୍ଚ କରନ୍ତୁ। ଅନୁପ୍ରୟୋଗ ଆକ୍ସେସ୍-ଟୋକେନ୍ ଭୂମିକା ପ read େ ନାହିଁ। IdP- ପାର୍ଶ୍ୱ ଟୋକେନ୍ ପ୍ରତ୍ୟାଖ୍ୟାନ ସପ୍ଲିମେଣ୍ଟ କରିପାରିବ କିନ୍ତୁ ଏହି ପ୍ରୟୋଗ-ପାର୍ଶ୍ୱ ଯାଞ୍ଚକୁ ବଦଳାଇବ ନାହିଁ।
- ସଫଳତା ଉପରେ ଏହା** ଠିକ୍ ସମାନ।** 30 ଦିନିଆ `auth_token` JWT ପାସୱାର୍ଡ ଲଗଇନ୍ ଇସୁ (`src/app/api/auth/login/route.ts`), ତେଣୁ ବାକି ଡ୍ୟାସବୋର୍ଡ ଅଧିବେଶନ ପାଇପଲାଇନ (ଅଟୋ-ରିଫ୍ରେସ୍, କୁକି ଫ୍ଲାଗ୍) ଅପରିବର୍ତ୍ତିତ — OIDC କେବଳ କୁକି କିପରି ମେଣ୍ଟ ହୁଏ ତାହା ବଦଳାଇଥାଏ, ଯାହା ତାହା ପ୍ରଦାନ କରେ ନାହିଁ। IdP roles/groups ରେ ପରିବର୍ତ୍ତନ ବିଦ୍ୟମାନ OmniRoute ଅଧିବେଶନକୁ ଅବ ate ଧ କରେ ନାହିଁ; ଲଗଆଉଟ୍, ପାସୱାର୍ଡ ଘୂର୍ଣ୍ଣନ, କିମ୍ବା ଅଧିବେଶନ ସମାପ୍ତି ଏପର୍ଯ୍ୟନ୍ତ ସେମାନଙ୍କ ଜୀବନକାଳକୁ ନିୟନ୍ତ୍ରଣ କରେ।
- ପ୍ରତ୍ୟେକ `oidc*` ସେଟିଂ (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) `400 PASSWORD_REQUIRED` ଅଛି: ଯଦି `PATCH /api/settings` ( `currentPassword` `401 PASSWORD_MISMATCH` ) `oidcDisablePasswordLogin` ପାସୱାର୍ଡ _login_ (`POST /api/auth/login`) କୁ ପ୍ରତ୍ୟାଖ୍ୟାନ କରେ କିନ୍ତୁ ଗଚ୍ଛିତ ପାସୱାର୍ଡ ହ୍ୟାଶକୁ ରଖେ, ଏବଂ ପୁନ aut- auth ତଥାପି ଏହା ବିରୁଦ୍ଧରେ `currentPassword` ଯାଞ୍ଚ କରେ।
- `corsOrigins` ଏବଂ `bruteForceProtection` ମଧ୍ୟ `SECURITY_IMPACTING_SETTINGS_KEYS` ରେ ଅଛି: ଖୋଲିବା ଲଗଇନ୍ ପ୍ରତିରକ୍ଷାକୁ ଦୁର୍ବଳ କରିଥାଏ, ତେଣୁ ସେମାନେ ସମାନ `currentPassword` re-auth ନିଅନ୍ତି (ସୁରକ୍ଷା ଟ୍ୟାବ୍ ଏହା ମାଗେ) ଏବଂ JSON ଆମଦାନୀ ସେମାନଙ୍କୁ ଡ୍ରପ୍ କରେ।
- ପ୍ରତ୍ୟେକ ସୁରକ୍ଷା-ନୀତି କି — `SECURITY_IMPACTING_SETTINGS_KEYS` ପ୍ରବିଷ୍ଟ, ପ୍ରତ୍ୟେକ `oidc*` କି ଏବଂ ଡ୍ୟାସବୋର୍ଡ ଅଧିବେଶନ ସ୍ଥିତି — ହେଉଛି।** କେବଳ ଅପରେଟର୍।** `PATCH /api/settings` ରେ: ଏକ ପରିଚାଳନା-ସ୍କୋପିଡ୍ API କି କିମ୍ବା ଏକ `oma_` ଆକ୍ସେସ୍ ଟୋକନ୍ `403` ସହିତ ସଠିକ୍ `currentPassword` ପଠାଇଲେ ମଧ୍ୟ ପ୍ରତ୍ୟାଖ୍ୟାନ କରାଯାଏ, ଏବଂ ପ୍ରତ୍ୟାଖ୍ୟାନ `reason: OPERATOR_REQUIRED` ସହିତ `settings.update_failed` ( `src/lib/api/operatorCredential.ts` ରେ`requireOperatorCredential()` ) ସହିତ ଅଡିଟ୍ କରାଯାଏ। ସାଧାରଣ ସେଟିଂସମୂହ (ଥିମ୍, ପ୍ରଦର୍ଶନ ପସନ୍ଦ) ଏକ `manage` କି କିମ୍ବା `admin` ଆକସେସ୍ ଟୋକେନ୍ ପାଇଁ ଲେଖାଯିବ। `/api/settings` ର ପ୍ରତ୍ୟେକ ପରିବର୍ତ୍ତନ (ଏବଂ `/api/settings/require-login` ର) ମଧ୍ୟ `admin` ଆକ୍ସେସ୍-ଟୋକେନ୍ ପରିସର ଆବଶ୍ୟକ କରେ ( `src/server/authz/accessScopes.ts` ରେ`ADMIN_MUTATION_EXACT_PATHS`, ସଠିକ୍ ପଥ ମ୍ୟାଚ୍); `GET` `read` ରୁହେ, ଏବଂ ଅନ୍ୟ `/api/settings/*` ଉପ-ମାର୍ଗ (ପ୍ରକ୍ସି, କମ୍ବୋ ଡିଫଲ୍ଟ, ମଡେଲ୍ ଛଦ୍ମନାମ, ସଙ୍କୋଚନ, ଶୁଦ୍ଧ…) ପଦ୍ଧତି-ଅନୁମାନିତ `write` ପରିସରକୁ ରଖେ।
- `POST /api/settings/import-json` ସ୍କିପ୍ କରେ ଯାହା ପୁନର୍ବାର ଲେଖାଏ, ତେଣୁ ଏହା ଲେଖିବା ପୂର୍ବରୁ `IMPORT_STRIPPED_SETTINGS_KEYS` (ସମାନ ଫାଇଲ) ରେ ପ୍ରତ୍ୟେକ ଚାବିକୁ ଡ୍ରପ୍ କରେ: ପାସୱାର୍ଡ ଏବଂ `currentPassword`, ପ୍ରତ୍ୟେକ `SECURITY_IMPACTING_SETTINGS_KEYS` ଏଣ୍ଟ୍ରି, ଏବଂ ଡ୍ୟାସବୋର୍ଡ ଅଧିବେଶନ ସ୍ଥିତି (`sessionsValidAfter`, `revokedDashboardSessions`)। ଏକ ପୁରାତନ ବ୍ୟାକଅପ୍ ଆମଦାନୀ କରିବା ତେଣୁ ଏକ ଅଧିବେଶନକୁ ପୁନର୍ଜୀବିତ କରିପାରିବ ନାହିଁ ଯାହା ଏକ ପାସୱାର୍ଡ ପରିବର୍ତ୍ତନ କିମ୍ବା ଏକ ସାଇନ୍ ଆଉଟ୍ ପୂର୍ବରୁ ସମାପ୍ତ ହୋଇଛି।

#### ବ z କଳ୍ପିକ TOTP ଦୁଇ-ଫ୍ୟାକ୍ଟର୍ ଲଗଇନ୍ (#16619)

ସେଟିଂସମୂହରୁ ନାମ ଲେଖା → ସୁରକ୍ଷା; ଅପରେଟର୍ ଏହାକୁ (`src/server/auth/dashboardMfa.ts`) ଟର୍ନ୍ ଅନ୍ କରିବା ପର୍ଯ୍ୟନ୍ତ ବନ୍ଦ।

- **ଏହା କଭର୍ କରେ:** ପାସୱାର୍ଡ ଲଗଇନ୍ (`POST /api/auth/login`, ଯାହା ପରେ `POST /api/auth/mfa/verify` ଆବଶ୍ୟକ କରେ) ଏବଂ `omniroute connect` (`POST /api/cli/connect`, ଯାହା କେବଳ ପାସୱାର୍ଡ ବିନିମୟକୁ ପ୍ରତ୍ୟାଖ୍ୟାନ କରେ ଏବଂ କୋଡ୍ କୁ `totp` ଭାବରେ ନେଇଥାଏ)।
- **ଏହା କ’ଣ ଆଚ୍ଛାଦନ କରେ ନାହିଁ:** OIDC / SSO ସାଇନ୍-ଇନ୍ (`/api/auth/oidc/callback`) OmniRoute TOTP ମାଗେ ନାହିଁ। ଏହା ପରିଚୟ ପ୍ରଦାନକାରୀଙ୍କର ନିଜସ୍ୱ ଦ୍ୱିତୀୟ କାରକ ଉପରେ ନିର୍ଭର କରେ, ତେଣୁ OIDC ସକ୍ଷମ ହେଲେ IdP ରେ MFA ବାଧ୍ୟତାମୂଳକ କର।
- **ପୁନରୁଦ୍ଧାର** (ହଜିଯାଇଥିବା ଉପକରଣ, କ recovery ଣସି ପୁନରୁଦ୍ଧାର ସଂକେତ ବାକି ନାହିଁ, କିମ୍ବା ଏକ କାରକ ଯାହା ଆଉ ଯାଞ୍ଚ ହୋଇପାରିବ ନାହିଁ, ଉଦାହରଣ ସ୍ୱରୂପ `STORAGE_ENCRYPTION_KEY` ପରିବର୍ତ୍ତନ ହେବା ପରେ):
  1. `OMNIROUTE_DISABLE_MFA=true` ସହିତ ସର୍ଭରକୁ ପୁନ Rest ଆରମ୍ଭ କରନ୍ତୁ।
  2. ହୋଷ୍ଟ ନିଜେ (ଲୁପବ୍ୟାକ୍ ସାଥି ଏବଂ ଲୁପ୍ ବ୍ୟାକ୍ `Host`, ଯେପରିକି `http://localhost:20128`), ପାସୱାର୍ଡ ସହିତ ସାଇନ୍ ଇନ୍ କରନ୍ତୁ। ଦ୍ୱିତୀୟ କାରକ କେବଳ ସେହି ଉତ୍ପତ୍ତି ପାଇଁ ଏଡ଼ାଇ ଦିଆଯାଏ; ଅନ୍ୟ ସମସ୍ତ ଉତ୍ପତ୍ତି ତଥାପି କୋଡ୍ ଆବଶ୍ୟକ କରେ।
  3. ସେଟିଂସମୂହରେ → ସୁରକ୍ଷା → ଅକ୍ଷମ କରନ୍ତୁ, ପାସୱାର୍ଡ ପ୍ରବେଶ କରନ୍ତୁ ଏବଂ କୋଡ୍ ଖାଲି ରଖନ୍ତୁ। `POST /api/auth/mfa/disable` କେବଳ `code` ବିନା ଏକ ଶରୀର ଗ୍ରହଣ କରେ ଯେତେବେଳେ ଭେରିଏବଲ୍ ସେଟ୍ ହୁଏ ଏବଂ ଅନୁରୋଧ ହୋଷ୍ଟରୁ ଆସେ। ଏହା ତଥାପି ଡ୍ୟାସବୋର୍ଡ ଅଧିବେଶନ ଏବଂ ସାମ୍ପ୍ରତିକ ପାସୱାର୍ଡ ଆବଶ୍ୟକ କରେ, ଏବଂ `secondFactor: "recovery_switch"` ସହିତ `auth.mfa.disabled` ଭାବରେ ଅଡିଟ୍ କରାଯାଏ।
  4. `OMNIROUTE_DISABLE_MFA` ସେଟ୍ କରନ୍ତୁ, ପୁନ art ଆରମ୍ଭ କରନ୍ତୁ ଏବଂ ଆବଶ୍ୟକ ହେଲେ ପୁନର୍ବାର ନାମ ଲେଖାନ୍ତୁ।

## ରାଉଟ୍ ଶ୍ରେଣୀ

`src/server/authz/types.ts` ତିନୋଟି ଶ୍ରେଣୀ ନିର୍ଦ୍ଧାରଣ କରେ; ନିର୍ଦ୍ଧାରିତ ଭାବେ ଶ୍ରେଣୀଭୁକ୍ତ ହୋଇପାରୁନଥିବା ଯେକୌଣସି ରାଉଟ୍ `MANAGEMENT` କୁ ଫଲ୍‌ବ୍ୟାକ୍ ହୁଏ।

| ଶ୍ରେଣୀ       | ବିବରଣୀ                                                                                                                                          | ପ୍ରାମାଣିକରଣ ଆବଶ୍ୟକ                                             |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| `PUBLIC`     | ସ୍ପଷ୍ଟଭାବେ ନିରାପଦ ରାଉଟ୍ — ଲଗଇନ୍, ଲଗଆଉଟ୍, ସ୍ଥିତି, ଇନିଟ୍, ସ୍ୱାସ୍ଥ୍ୟ, ଅନବୋର୍ଡିଙ୍ଗ୍ ବୁଟ୍‌ଷ୍ଟ୍ରାପ୍।                                                  | କିଛି ନାହିଁ                                                     |
| `CLIENT_API` | ମଡେଲ୍-ସେବା endpoints — `/api/v1/*`, `/api/v1beta/*`, ଏବଂ ଆଲିଆସ୍ `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`। | ପ୍ରଭାବଶାଳୀ `REQUIRE_API_KEY` ଫିଚର୍ ଫ୍ଲାଗ୍ ସକ୍ଷମ ଥିଲେ Bearer କୀ |
| `MANAGEMENT` | ଡ୍ୟାସବୋର୍ଡ ପୃଷ୍ଠା, ସେଟିଂସ୍, ପ୍ରଦାତା, କୀ, ଆଡ୍‌ମିନ୍ ଏବଂ ଡାଏଗ୍ନୋଷ୍ଟିକ୍ endpoints।                                                                  | ଡ୍ୟାସବୋର୍ଡ ସେସନ୍ କିମ୍ବା `manage` ସ୍କୋପ୍ ସହିତ Bearer            |

କିଛି `MANAGEMENT` କାର୍ଯ୍ୟ **କେବଳ ଅପରେଟର୍** ଅଟେ: `manage` କୀ ଯଥେଷ୍ଟ ନୁହେଁ। ସଂରକ୍ଷିତ କ୍ରେଡେନସିଆଲ୍ ରପ୍ତାନି (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ଜୀବନ୍ତ ଡାଟା ଉପରେ ବ୍ୟାକଅପ୍ ପୁନଃସ୍ଥାପନ (`dryRun=true` ସମେତ `POST /api/db-backups/import`, id ଦ୍ୱାରା `POST /api/db-backups` ପୁନଃସ୍ଥାପନ, `POST /api/settings/import-json`), ପୁନଃସ୍ଥାପନ ବିନ୍ଦୁ ନଷ୍ଟ କରିବା (`DELETE /api/db-backups` ସଫାସୁତରା, ଏବଂ `PATCH /api/db-backups` କାରଣ ଏହା ସଞ୍ଚୟ କରୁଥିବା ରିଟେନସନ୍ ପ୍ରତି ବ୍ୟାକଅପ୍ ପରେ ସ୍ୱୟଂଚାଳିତ ପ୍ରୁନିଂ ଚଳାଏ) ଡ୍ୟାସବୋର୍ଡ ସେସନ୍, ସ୍ଥାନୀୟ CLI ବିଷୟ, କିମ୍ବା ଲଗଇନ୍ ଅକ୍ଷମ ଥିବା ଆବଶ୍ୟକ କରେ। ସିଙ୍କ୍ ଟୋକେନ୍ ଜାରି କରିବା (`POST /api/sync/tokens`) ଏବଂ `admin` CLI ଆକ୍ସେସ୍ ଟୋକେନ୍ ଜାରି କରିବା (`POST /api/cli/tokens`) ପ୍ରତ୍ୟେକ ଲଗଇନ୍ ମୋଡ୍‌ରେ ଡ୍ୟାସବୋର୍ଡ ସେସନ୍ କିମ୍ବା ସ୍ଥାନୀୟ CLI ବିଷୟ ଆବଶ୍ୟକ କରେ। ଯେକୌଣସି ସ୍କୋପ୍‌ର API କୀ ଏବଂ `oma_` ଆକ୍ସେସ୍ ଟୋକେନ୍ ଅପରେଟର୍ କ୍ରେଡେନସିଆଲ୍ ନୁହଁନ୍ତି: ଯେତେବେଳେ ଏକ ଅପରେଟର୍ ଆବଶ୍ୟକ ହୁଏ, ସେମାନେ `403` ପାଆନ୍ତି। ଯାଞ୍ଚଟି `src/lib/api/operatorCredential.ts` ରେ ଅଛି (`resolveOperatorCredential()` / `requireOperatorCredential()`)। ଲଗଇନ୍ ସେଟିଂସ୍ ବଦଳାଇବା ମଧ୍ୟ କେବଳ ଅପରେଟର୍: `POST /api/settings/require-login` (ପରିଚାଳନା ପାସୱାର୍ଡ ସେଟ୍ / `requireLogin` ଟଗଲ୍) ଏକ ପାସୱାର୍ଡ ଥିଲେ କେବଳ ସେହି କ୍ରେଡେନସିଆଲ୍ ଗ୍ରହଣ କରେ — ପ୍ରଥମ-ଚାଲନା ବୁଟଷ୍ଟ୍ରାପ୍ ୱିଣ୍ଡୋ (ଏପର୍ଯ୍ୟନ୍ତ ପାସୱାର୍ଡ ନାହିଁ) ଅପରିବର୍ତ୍ତିତ ରହେ — ଏବଂ ପାସୱାର୍ଡ ବଦଳାଇବାକୁ ଡ୍ୟାସବୋର୍ଡ ସେସନ୍‌କୁ `currentPassword` ପଠାଇବାକୁ ପଡ଼େ (ଏହା ନଥିଲେ କିମ୍ବା ଭୁଲ ହେଲେ `403`, `settings.update_failed` ଭାବରେ ଅଡିଟ୍ ହୁଏ)। ସ୍ଥାନୀୟ CLI ଏବଂ ଲଗଇନ୍ ଅକ୍ଷମ ଥିବା ଇନଷ୍ଟାନ୍ସ ପୁନରୁଦ୍ଧାର ପଥ ରଖନ୍ତି ଏବଂ ତାହା ବିନା ପାସୱାର୍ଡ ସେଟ୍ କରିପାରନ୍ତି, କାରଣ ଉଭୟ ଡାଟା ଡାଇରେକ୍ଟ୍ରୀର ମାଲିକ ହୋଷ୍ଟ ସହ ବନ୍ଧା।

## ପାଇପଲାଇନ

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

ବିଶ୍ୱସ୍ତ ଆଭ୍ୟନ୍ତରୀଣ ଶୀର୍ଷଲେଖଗୁଡ଼ିକ ( `src/server/authz/headers.ts` ରେ ବ୍ୟାଖ୍ୟା କରାଯାଇଛି) \|** ଆସୁଥିବା ଅନୁରୋଧରୁ ଛଡ଼ାଯାଇଛି \|** ବର୍ଗୀକରଣ ପୂର୍ବରୁ — ଗ୍ରାହକମାନେ ଏକ ବିଷୟର ଛଦ୍ମନାମ କରିବାକୁ `x-omniroute-auth-*` ପୂର୍ବ-ଜନସଂଖ୍ୟା କରିପାରିବେ ନାହିଁ \|

### ନୀତି ଚୁକ୍ତି

ପ୍ରତ୍ୟେକ ରୁଟ୍ ଶ୍ରେଣୀର `src/server/authz/policies/` ରେ ଏକ ନୀତି ଅଛି:

- **`publicPolicy`** (`policies/public.ts`) — ସର୍ବଦା `allow({ kind: "anonymous", id: "anonymous" })` ଫେରସ୍ତ କରେ \|
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ନିର୍ବାହକାରୀ, `validateApiKey()` ମାଧ୍ୟମରେ ବ valid ଧ କରେ \| ପ୍ରଭାବଶାଳୀ `REQUIRE_API_KEY` feature ଶିଷ୍ଟ୍ୟ ପତାକା ଅକ୍ଷମ ହେଲେ ହିଁ ଅଜ୍ଞାତ ହୋଇଯାଏ \| ପ୍ରଭାବଶାଳୀ ପତାକା `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ମାଧ୍ୟମରେ ସମାଧାନ ହୋଇଛି ତେଣୁ ଡ୍ୟାସବୋର୍ଡ ବ ature ଶିଷ୍ଟ୍ୟ ଫ୍ଲାଗ ଏବଂ ପରିବେଶ ଭେରିଏବଲ୍ `/api/v1/*`, `/api/v1beta/*`, ଏବଂ ଛଦ୍ମନାମକୁ କ୍ରମାଗତ ଭାବରେ ପରିଚାଳନା କରେ \| ସମାଧାନକାରୀ ବିଫଳତା ବନ୍ଦ ହୋଇଯାଏ \| କ୍ଲାଏଣ୍ଟ API ରୁଟରେ ଡ୍ୟାସବୋର୍ଡ-ଅଧିବେଶନ ଅନୁରୋଧକୁ ଅନୁମତି ଦେଇଥାଏ ( `/api/v1/models` ଅନ୍ତର୍ଭୂକ୍ତ କରି, ଡ୍ୟାସବୋର୍ଡ ମଡେଲ କାଟାଲଗ୍ ଦ୍ୱାରା ବ୍ୟବହୃତ) \| ଯେତେବେଳେ ଏଣ୍ଟ୍ରା ID SSO ସକ୍ଷମ ହୁଏ, ଏକ ବିୟର ଯାହାକି ଗଠନମୂଳକ ଭାବରେ ଏକ ଏଣ୍ଟ୍ରା ଟୋକେନ୍ (ତିନୋଟି ଆଧାର 64url ସେଗମେଣ୍ଟ, `RS*` alg, `kid`) SSO ଶାଖା ଦ୍ୱାରା ପରିଚାଳିତ ହୋଇଥାଏ \|** ପୂର୍ବରୁ** `validateApiKey()` — ଷ୍ଟାଟିକ୍ API କିଗୁଡ଼ିକ ପ୍ରଭାବିତ ନୁହେଁ \| [Entra ID SSO](../security/ENTRA_SSO.md) ଦେଖନ୍ତୁ \|
- **`managementPolicy`** (`policies/management.ts`) — ଡ୍ୟାସବୋର୍ଡ ଅଧିବେଶନ, ଆଭ୍ୟନ୍ତରୀଣ ମଡେଲ-ସିଙ୍କ ଅନୁରୋଧ ( `/api/providers/[name]/(sync-models|models)` ସହିତ ମେଳ) ଗ୍ରହଣ କରେ, କିମ୍ବା ଯଦି `isAuthRequired()` ମିଥ୍ୟା ଫେରସ୍ତ କରେ ତେବେ ସଂପୂର୍ଣ୍ଣ ଛାଡିଦିଏ \| 403 (`AUTH_001`) ଫେରସ୍ତ କରେ ଯେତେବେଳେ ଏକ ବିୟର ଟୋକନ୍ ଉପସ୍ଥିତ କିନ୍ତୁ ଅବ alid ଧ, 401 ଅନ୍ୟଥା \| ଯେକ any ଣସି auth ଶାଖା — [ରୁଟ୍ ଗାର୍ଡ ଟାୟର୍](../security/ROUTE_GUARD_TIERS.md) ଦେଖିବା ପୂର୍ବରୁ ରୁଟ୍-ଗାର୍ଡ ସ୍ତରଗୁଡିକ (LOCAL_ONLY / ALWAYS_PROTECTED) କୁ ମଧ୍ୟ କାର୍ଯ୍ୟକାରୀ କରିଥାଏ \| `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ରେ LOCAL_ONLY ପଥ (ଆଜି: `/api/mcp/`) ଅଣ-ଲୁପବ୍ୟାକ୍ ରୁ ପ୍ରବେଶ କରାଯାଇପାରେ ଯେତେବେଳେ ବିୟର ଚାବି `manage` ପରିସର ବହନ କରେ; ଅନ୍ୟ ସମସ୍ତ LOCAL_ONLY ପଥଗୁଡିକ ପରିସରକୁ ଖାତିର ନକରି କଠୋର-ଲୁପବ୍ୟାକ୍ ରହିଥାଏ \|

ଏକ ସଫଳ ନୀତି `AuthSubject` ସହିତ `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` ଫେରସ୍ତ କରେ \| ଡାଉନ୍ଷ୍ଟ୍ରିମ୍ ହ୍ୟାଣ୍ଡେଲର୍ମାନେ auth ତର୍କକୁ ପୁନ running ଚଲାଇବା ପରିବର୍ତ୍ତେ `src/server/authz/assertAuth.ts` ରେ `assertAuth(request, "CLIENT_API")` ମାଧ୍ୟମରେ ପ read ିପାରିବେ \|

## ସର୍ବସାଧାରଣ ମାର୍ଗ ତାଲିକା।

`src/shared/constants/publicApiRoutes.ts` ହେଉଛି ସ୍ପଷ୍ଟ ଅନୁମତି ତାଲିକା:

ତାଲିକା ଦ୍ୱାରା ବିଭକ୍ତ।** ଆକୃତି।** , ଏବଂ ବିଭାଜନ ହେଉଛି ଭାର ଧାରଣକାରୀ (GHSA-74g9-q8f6-793h): ଏକ ଉପସର୍ଗ `startsWith()` ସହିତ ମେଳ ହୋଇଛି, ତେଣୁ ଏହା ଏହାର ଅଗ୍ରଣୀ ଅକ୍ଷରଗୁଡ଼ିକୁ ଅଂଶୀଦାର କରୁଥିବା ପ୍ରତ୍ୟେକ ସଂଲଗ୍ନ ପଥ ସହିତ ମଧ୍ୟ ମେଳ ଖାଉଛି। `/api/usage/om-usage` ଏକ ଉପସର୍ଗ ଭାବରେ `/api/usage/om-usage<anything>` PUBLIC ଚିହ୍ନିତ ହୋଇଛି, ଏବଂ ପରବର୍ତ୍ତୀ ସମାଧାନ କରେ ଯେ `/api/usage/[connectionId]` — କୁ ଏକ ହ୍ୟାଣ୍ଡେଲର୍ ନିଜର କ aut ଣସି auth ବିନା।

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

କେବଳ ପଠନ ମାର୍ଗଗୁଡ଼ିକ ସର୍ବସାଧାରଣ ଅଟେ।** କେବଳ** ସୁରକ୍ଷିତ ପଦ୍ଧତି ପାଇଁ। ଟିପନ୍ତୁ: `classifyRoute()` `/api/v1/*` ଏବଂ `/api/v1beta/*` PUBLIC fall-through — ରୁ ବାଦ ଦେଇଥାଏ ଯାହା ସର୍ବଦା `CLIENT_API` ଅଟେ ତେଣୁ ବିୟର-କି ନୀତି ପ୍ରଯୁଜ୍ୟ।

## ଏକ ନୂତନ ରୁଟ୍ ଯୋଡ଼ିବା

### ପ୍ୟାଟର୍ନ 1 — ସାର୍ବଜନୀନ କ୍ଲାଏଣ୍ଟ API ଏଣ୍ଡପଏଣ୍ଟ (Bearer-ପ୍ରମାଣୀକରଣ)

`/api/v1/` ଏବଂ `/api/v1beta/` ଅଧୀନରେ ଥିବା ରୁଟ୍ଗୁଡ଼ିକୁ ସ୍ୱୟଂଚାଳିତ ଭାବରେ `CLIENT_API` ଭାବେ ବର୍ଗୀକୃତ କରାଯାଏ। ମିଡଲ୍ୱେର୍ Bearer ଯାଞ୍ଚକୁ ବାଧ୍ୟତାମୂଳକ କରେ; ରୁଟ୍ ହ୍ୟାଣ୍ଡଲର୍ଗୁଡ଼ିକୁ ଏହା ପୁନର୍ବାର କରିବାର ଆବଶ୍ୟକତା ନାହିଁ, କିନ୍ତୁ ଉପଯୋଗୀ ହେଲେ ସବ୍ଜେକ୍ଟକୁ ପଢ଼ିପାରିବେ।

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... ହ୍ୟାଣ୍ଡଲର୍ ତର୍କ
}
```

### ପ୍ୟାଟର୍ନ 2 — ପରିଚାଳନା ଏଣ୍ଡପଏଣ୍ଟ (ସେସନ୍ କିମ୍ବା Bearer + manage)

`src/lib/api/requireManagementAuth.ts`ରୁ `requireManagementAuth()` ବ୍ୟବହାର କରନ୍ତୁ:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... ହ୍ୟାଣ୍ଡଲର୍ ତର୍କ
}
```

ସଫଳ ହେଲେ `requireManagementAuth()` `null` ଫେରାଏ, ନଚେତ୍ ଏକ JSON ତ୍ରୁଟି `Response` ଫେରାଏ:

- 401 `AUTH_001` "ପ୍ରମାଣୀକରଣ ଆବଶ୍ୟକ" — ଆଦୌ କୌଣସି ପରିଚୟପତ୍ର ନାହିଁ
- 403 — ଅବୈଧ Bearer **କିମ୍ବା** Bearer ଉପସ୍ଥିତ ଅଛି, କିନ୍ତୁ କୀ ପାଖରେ `manage` / `admin` ସ୍କୋପ୍ ନାହିଁ

`"manage"` କିମ୍ବା `"admin"` ପାଇଁ `hasManageScope(scopes)` true ଫେରାଏ।

### ପ୍ୟାଟର୍ନ 3 — ସାର୍ବଜନୀନ ଅନୁମୋଦିତ ତାଲିକାରେ ଯୋଡ଼ିବା

ସୁବିଧା ଅନୁସାରେ ନୁହେଁ, ଆକୃତି ଅନୁସାରେ ସେଟ୍ ବାଛନ୍ତୁ। ଗୋଟିଏ ରୁଟ୍ `PUBLIC_API_ROUTES_EXACT`ରେ ଯାଏ (କିମ୍ବା କେବଳ-GET ପାଇଁ `PUBLIC_READONLY_CORS_API_ROUTES`ରେ); କେବଳ ଏକ ପ୍ରକୃତ ଉପବୃକ୍ଷ `PUBLIC_API_ROUTE_PREFIXES`ରେ ଯାଏ, ଏବଂ ଏହା **`/`ରେ ଶେଷ ହେବା ଆବଶ୍ୟକ**। ଉପସର୍ଗ ତାଲିକାରେ ଗୋଟିଏ ଏକକ ରୁଟ୍ ରଖିବା ଦ୍ୱାରା ଏହାର ପ୍ରାରମ୍ଭିକ ଅକ୍ଷରଗୁଡ଼ିକ ସମାନ ଥିବା ପ୍ରତ୍ୟେକ ସଂଲଗ୍ନ ପଥ ମଧ୍ୟ ସାର୍ବଜନୀନ ହୋଇଯାଏ — ଏଥିରେ ପରେ ଯୋଡ଼ାଯାଇଥିବା ଡାଇନାମିକ୍-ସେଗମେଣ୍ଟ ସହୋଦର ରୁଟ୍ଗୁଡ଼ିକ ମଧ୍ୟ ଅନ୍ତର୍ଭୁକ୍ତ (GHSA-74g9-q8f6-793h)। `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ଏବଂ `tests/unit/authz/classify.test.ts`ରେ ଥିବା ୟୁନିଟ୍ ପରୀକ୍ଷାଗୁଡ଼ିକୁ ଅଦ୍ୟତନ କରନ୍ତୁ।

## ସ୍କୋପ୍ସ

ତିନୋଟି ନାମସ୍ପେସ୍। ପ୍ରତ୍ୟେକ ଚେକର୍ କେବଳ ନିଜର ଷ୍ଟ୍ରିଙ୍ଗ୍ ପଢ଼େ। `manage` କାହିଁକି `read:compression` ପାଇଁ `scopeMatches` ରେ ବିଫଳ ହୁଏ ଏବଂ `read` ଆକ୍ସେସ୍ ଟୋକେନ୍ କାହିଁକି `PATCH /api/keys/{id}` କରିପାରିବ ନାହିଁ, ତାହା ସହିତ ପାର୍ଶ୍ୱ-ପାର୍ଶ୍ୱ ତୁଳନା [ତିନୋଟି ସ୍କୋପ୍ ନାମସ୍ପେସ୍](../frameworks/MCP-SERVER.md#three-scope-namespaces) ରେ ଦିଆଯାଇଛି।

API କି'ଗୁଡ଼ିକ ଏକ `scopes` ଆରେ ଧାରଣ କରନ୍ତି (JSON ଭାବରେ `api_keys.scopes` ରେ ସଂରକ୍ଷିତ, `src/lib/db/apiKeys.ts` ଦେଖନ୍ତୁ)।

### ପରିଚାଳନା ସ୍କୋପ୍

- `manage` / `admin` — `hasManageScope`। ପରିଚାଳନା API ରୁଟ୍ଗୁଡ଼ିକୁ ବେୟରର୍ ଆକ୍ସେସ୍।
- `mcp:connect`, `self:usage`, `self:account-quota`, ଏବଂ
  `policy:bypass-provider-quota` ହେଉଛି ଯୋଗାତ୍ମକ ସଠିକ୍-ମେଳ ସ୍କୋପ୍ସ। ସେଗୁଡ଼ିକ
  `MANAGEMENT_API_KEY_SCOPES` ବାହାରେ ରୁହନ୍ତି। `mcp:connect` କେବଳ
  `/api/mcp/` ନନ୍-ଲୁପ୍ବ୍ୟାକ୍ କାର୍ଭ-ଆଉଟ୍ ଖୋଲିଥାଏ।

### MCP ଟୁଲ୍ ସ୍କୋପ୍ସ

କାଟାଲଗ୍ ଏବଂ ମେଳ ଖାଉଥିବା ନିୟମ (ସମାନ ଷ୍ଟ୍ରିଙ୍ଗ୍, କିମ୍ବା `*` ରେ ଶେଷ ହେଉଥିବା ଏକ ଅନୁମତିପ୍ରାପ୍ତ ସ୍କୋପ୍):
[MCP ଟୁଲ୍ ସ୍କୋପ୍ସ](../frameworks/MCP-SERVER.md#mcp-tool-scopes)।
`src/shared/constants/mcpScopes.ts` ରେ ଥିବା `MCP_SCOPE_LIST` ହେଉଛି ମୂଳ ଟାଇପ୍ କରାଯାଇଥିବା ସବ୍ସେଟ୍,
ସମ୍ପୂର୍ଣ୍ଣ କାଟାଲଗ୍ ନୁହେଁ। `resolveCallerScopeContext()` MCP ଅଥ୍ ସୂଚନା, ଅନୁରୋଧ ମେଟାଡାଟା,
କିମ୍ବା `OMNIROUTE_MCP_SCOPES` ରୁ ସ୍କୋପ୍ସ ସମାଧାନ କରିବା ପରେ
`open-sse/mcp-server/scopeEnforcement.ts` ରେ ଏନଫୋର୍ସମେଣ୍ଟ ଚାଲିଥାଏ।
`OMNIROUTE_MCP_ENFORCE_SCOPES=true` ନହେବା ପର୍ଯ୍ୟନ୍ତ ଏହା ବନ୍ଦ ରୁହେ।

### ଆକ୍ସେସ୍-ଟୋକେନ୍ ସ୍କୋପ୍ସ

`oma_live_…` ଟୋକେନ୍ଗୁଡ଼ିକ ଉପରେ `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) ଦ୍ୱାରା ମାନ୍ୟତାପ୍ରାପ୍ତ। ଏହି ମାନ୍ୟତା କେବଳ
ଆକ୍ସେସ୍-ଟୋକେନ୍ କ୍ରେଡେନ୍ସିଆଲ୍ ପାଇଁ ପ୍ରଯୁଜ୍ୟ। [ପରିଚାଳନା ପ୍ରମାଣୀକରଣ](../guides/MANAGEMENT-AUTH.md) ଦେଖନ୍ତୁ।

## Auth ଆବଶ୍ୟକ ଟଗଲ୍

`src/shared/utils/apiAuth.ts` ରେ `isAuthRequired()` ନିର୍ଣ୍ଣୟ କରେ ଯେ ଏକ ଅନୁରୋଧ ପାଇଁ **କୌଣସି** ପ୍ରାମାଣିକରଣ ବାଧ୍ୟତାମୂଳକ ହେବ କି ନାହିଁ:

- `settings.requireLogin === false` → ପ୍ରାମାଣିକରଣ ବିଶ୍ୱସ୍ତରରେ ଅକ୍ଷମ, ସର୍ବଦା-ସୁରକ୍ଷିତ ସ୍ତର ([Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) ଏବଂ ଯେ କଲ୍ ଏହା ଗ୍ରହଣ କରୁଥିବା କ୍ରେଡେନସିଆଲ୍ ଦିଏ ସେଗୁଡ଼ିକ ବ୍ୟତୀତ — ଲଗଇନ୍ ଚାଲୁ ଥିବା ପରି ସେହି କ୍ରେଡେନସିଆଲ୍ ଆବଶ୍ୟକ: ସିଙ୍କ୍ ଟୋକେନ୍ ଜାରି କରିବା, ଯେ କୌଣସି ସ୍କୋପ୍‌ରେ CLI ଆକ୍ସେସ୍ ଟୋକେନ୍ ଜାରି କରିବା, ଏବଂ `manage`/`admin` ସ୍କୋପ୍ ସହ API କୀ ସୃଷ୍ଟି କରିବା, ସେହି ସ୍କୋପ୍ କୀକୁ ଦେବା, କିମ୍ବା ଏପରି କୀ ପୁନର୍ଜନନ କିମ୍ବା ପ୍ରକାଶ କରିବା (`src/lib/api/requireManagementAuth.ts` ରେ `requireCredentialForManagementScopedKey()`)। କେବଳ-ଇନଫରେନ୍ସ କୀ ଖୋଲା ରହେ।
- କୌଣସି ପାସୱାର୍ଡ ସେଟ୍ ନାହିଁ **ଏବଂ** `INITIAL_PASSWORD` ପରିବେଶ ଭେରିଏବଲ୍ ନାହିଁ → ବୁଟଷ୍ଟ୍ରାପ୍ ମୋଡ୍ ଅନବୋର୍ଡିଙ୍ଗ୍ ୱିଜାର୍ଡ ଏବଂ loopback ଅନୁରୋଧକୁ ଅନୁମତି ଦିଏ, କିନ୍ତୁ ଏକ୍ସପୋଜ୍ ହୋଇଥିବା ନେଟୱାର୍କ ଅନୁରୋଧକୁ ତଥାପି କ୍ରେଡେନସିଆଲ୍ ଆବଶ୍ୟକ।
- ଯେକୌଣସି DB ତ୍ରୁଟି → ବିଫଳ-ବନ୍ଦ (ସୁରକ୍ଷା-ଡିଫଲ୍ଟ)।

Client API କୀ ବାଧ୍ୟତା `src/shared/utils/featureFlags.ts` ରେ `isRequireApiKeyEnabled()` ବ୍ୟବହାର କରେ, ସିଧାସଳଖ `process.env.REQUIRE_API_KEY` ପଢ଼ା ନୁହେଁ। ଏହା ଡିପ୍ଲୟ୍ କରାଯାଇଥିବା ଇନଷ୍ଟାନ୍ସ ପାଇଁ ଗୁରୁତ୍ୱପୂର୍ଣ୍ଣ: ଡ୍ୟାସବୋର୍ଡ → Feature Flags ରେ `REQUIRE_API_KEY` ଟଗଲ୍ କରିବା ଏକ DB ଓଭରରାଇଡ୍ ସଞ୍ଚୟ କରେ ଏବଂ `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ଓ ଏହି ସହାୟକ ବାଣ୍ଟୁଥିବା ଅନ୍ୟ client-API ପ୍ରାମାଣିକରଣ ଯାଞ୍ଚକୁ ତୁରନ୍ତ ପ୍ରଭାବିତ କରେ। ଫିଚର୍ ଫ୍ଲାଗ୍ ଷ୍ଟୋର୍ ପଢ଼ାଯାଇ ନ ପାରିଲେ, client API ପ୍ରାମାଣିକରଣ ବିଫଳ-ବନ୍ଦ ହୁଏ ଏବଂ ଏକ କୀ ଆବଶ୍ୟକ କରେ।

## ବ୍ରେକିଂ ପରିବର୍ତ୍ତନ — v3.8.0

`/api/v1/agents/tasks/*` ଏବଂ `/api/resilience/model-cooldowns` ଏଣ୍ଡପଏଣ୍ଟଗୁଡ଼ିକ ପାଇଁ **ବର୍ତ୍ତମାନ ପରିଚାଳନା ପ୍ରମାଣୀକରଣ ଆବଶ୍ୟକ** (commit `588a0333`)। ପୂର୍ବରୁ `manage` ସ୍କୋପ୍ ବିନା ଏକ ସାଧାରଣ API କୀ ପଠାଉଥିବା କ୍ଲାଏଣ୍ଟଗୁଡ଼ିକ `403` ପାଇବେ। ମାଇଗ୍ରେସନ୍: API Keys ଡ୍ୟାସ୍ବୋର୍ଡ୍ରେ କୀକୁ `manage` ସ୍କୋପ୍ ଦିଅନ୍ତୁ, କିମ୍ବା ଏକ ଲଗ୍ଇନ୍ ହୋଇଥିବା ଡ୍ୟାସ୍ବୋର୍ଡ୍ ସେସନ୍ ବ୍ୟବହାର କରନ୍ତୁ।

## ଆଚରଣ ପରିବର୍ତ୍ତନ — v3.8.2

`/api/mcp/*` (ରିମୋଟ୍ MCP ସର୍ଭର୍) ଏବେ ମଧ୍ୟ ଡିଫଲ୍ଟ ଭାବେ LOCAL_ONLY ଅଟେ, କିନ୍ତୁ `Authorization: Bearer <api-key>` ହେଡର୍ରେ `manage` ସ୍କୋପ୍ ଥିଲେ ଏହା ବର୍ତ୍ତମାନ ଅଣ-ଲୁପ୍ବ୍ୟାକ୍ ଅନୁରୋଧଗୁଡ଼ିକୁ ଗ୍ରହଣ କରେ। ଏହି ବିଶେଷ ଛାଡ଼ `src/server/authz/routeGuard.ts`ରେ ଥିବା `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ମାଧ୍ୟମରେ ପ୍ରତ୍ୟେକ ପଥ ପାଇଁ ସ୍ପଷ୍ଟ ଭାବେ ନିୟନ୍ତ୍ରିତ; ସମାନ ସ୍ତରର LOCAL_ONLY ପ୍ରିଫିକ୍ସ `/api/cli-tools/runtime/*`କୁ ଉଦ୍ଦେଶ୍ୟମୂଳକ ଭାବେ ବାଇପାସ୍ଯୋଗ୍ୟ କରାଯାଇନାହିଁ, କାରଣ ଏହା ଇଚ୍ଛାମୁତାବକ ସବ୍ପ୍ରୋସେସ୍ଗୁଡ଼ିକୁ ସୃଷ୍ଟି କରିପାରେ। ଅଣ-ଲୁପ୍ବ୍ୟାକ୍ରୁ `/api/mcp/*`କୁ ଆସୁଥିବା ଅଜ୍ଞାତ ଅନୁରୋଧଗୁଡ଼ିକ `403 LOCAL_ONLY` ଫେରାଇବା ଜାରି ରଖେ — ଯେକୌଣସି ନୂତନ LOCAL_ONLY ପଥ ପାଇଁ ଡିଫଲ୍ଟ ନୀତି କଠୋର-ଲୁପ୍ବ୍ୟାକ୍ ହୋଇ ରହେ। [ରୁଟ୍ ଗାର୍ଡ୍ ସ୍ତରଗୁଡ଼ିକ](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) ଦେଖନ୍ତୁ।

## ପରୀକ୍ଷଣ

- ୟୁନିଟ୍ ପରୀକ୍ଷଣଗୁଡ଼ିକ: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`।
- ସାର୍ବଜନୀନ ଅନୁମୋଦିତ ତାଲିକା: `tests/unit/public-api-routes.test.ts`।
- କେନ୍ଦ୍ରିତ ଭାବେ ଚଲାନ୍ତୁ: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`।

## ତ୍ରୁଟି ନିବାରଣ

ପାଇପଲାଇନ ସର୍ବଦା ପ୍ରତିକ୍ରିୟାଗୁଡ଼ିକୁ ଷ୍ଟାମ୍ପ କରିଥାଏ:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

ପ୍ରାମାଣିକ ଅନୁରୋଧ ପାଇଁ ଅପଷ୍ଟ୍ରିମ୍ (ହ୍ୟାଣ୍ଡେଲର୍-ସାଇଡ୍) ଅନୁରୋଧ ହେଡର୍ ଗୁଡିକ ମଧ୍ୟ ଅନ୍ତର୍ଭୁକ୍ତ କରେ:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ହ୍ୟାଣ୍ଡଲର୍ ଭିତରେ `assertAuth(req, expectedClass)` ବ୍ୟବହାର କରନ୍ତୁ — ଏହା `AuthzAssertionError` `AUTHZ_NOT_INITIALIZED` ସହିତ ଫୋପାଡିଥାଏ ଯଦି ମଧ୍ୟମ ସଫ୍ଟୱେର୍ ବାଇପାସ୍ ହୋଇଥଲା (ପରୀକ୍ଷଣରେ ବିନ୍ୟାସକରଣ ରିଗ୍ରେସନ୍ ଧରିବାରେ ସାହାଯ୍ୟକାରୀ) \|

## ଏହା ମଧ୍ୟ ଦେଖନ୍ତୁ

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ପ୍ରତି ଏଣ୍ଡପଏଣ୍ଟ ପାଇଁ ଅଥ୍ ମାର୍କର୍
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ଅଥ୍ ଇଭେଣ୍ଟଗୁଡ଼ିକ ପାଇଁ ଅଡିଟ୍ ଲଗ୍
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ତିନୋଟି ସ୍କୋପ୍ ନେମସ୍ପେସ୍ ଏବଂ MCP ଟୁଲ୍-ସ୍କୋପ୍ କାଟାଲଗ୍
- ଉତ୍ସ: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
