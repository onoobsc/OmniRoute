# Authorization Guide (ಕನ್ನಡ)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **ಸತ್ಯದ ಮೂಲ:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **ಕೊನೆಯದಾಗಿ ನವೀಕರಿಸಲಾಗಿದೆ:** 2026-09-22 — ಸ್ಕೋಪ್ ನೇಮ್ಸ್ಪೇಸ್ಗಳು MCP-SERVER.md ಅನ್ನು ಸೂಚಿಸುತ್ತವೆ

ಓಮ್ನಿರೂಟ್ ಪ್ರತಿ API ವಿನಂತಿಯನ್ನು ನಿಯಂತ್ರಿಸುವ ರೂಟ್-ಅರಿವಿನ ದೃಢೀಕರಣ ಪೈಪ್ಲೈನ್ ಅನ್ನು ಹೊಂದಿದೆ. ವರ್ಗೀಕರಣವು **ನಿರ್ಣಾಯಕ** ಮತ್ತು **ಫೇಲ್-ಕ್ಲೋಸ್ಡ್** ಆಗಿದೆ — ವರ್ಗೀಕರಿಸಲಾಗದ ಯಾವುದೇ ವಿಷಯವು `MANAGEMENT` ಆಗಿ ಕೊನೆಗೊಳ್ಳುತ್ತದೆ ಮತ್ತು ಸೆಷನ್ ಅಥವಾ ಮ್ಯಾನೇಜ್ಮೆಂಟ್-ಗ್ರೇಡ್ ಟೋಕನ್ ಅನ್ನು ಬೇಡುತ್ತದೆ. ಈ ಪುಟವು ರೂಟ್ಗಳನ್ನು ನಿರ್ವಹಿಸುವ ಅಥವಾ ಹೊಸ ಎಂಡ್ಪಾಯಿಂಟ್ಗಳನ್ನು ವಿನ್ಯಾಸಗೊಳಿಸುವ ಎಂಜಿನಿಯರ್ಗಳಿಗೆ ಮಾದರಿಯನ್ನು ವಿವರಿಸುತ್ತದೆ.

![AuthZ ಪೈಪ್ಲೈನ್ (3 ರೂಟ್ ವರ್ಗಗಳು + ನೀತಿ ಮೌಲ್ಯಮಾಪನ)](../diagrams/exported/authz-pipeline.svg)

> ಮೂಲ: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## ಎರಡು ದೃಢೀಕರಣ ವಿಧಾನಗಳು

### 1. API ಕೀ (ಬೇರರ್)

ಕೀಲಿಯು `manage` ವ್ಯಾಪ್ತಿಯನ್ನು ಹೊಂದಿರುವಾಗ OpenAI/Anthropic/Gemini-compatible ಕ್ಲೈಂಟ್ APIs ಮತ್ತು ಕೆಲವು ನಿರ್ವಹಣಾ ಮಾರ್ಗಗಳಿಗಾಗಿ ಬಳಸಲಾಗುತ್ತದೆ.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` ನಲ್ಲಿ `isValidApiKey()` / `extractApiKey()` ಮೂಲಕ ಮೌಲ್ಯೀಕರಿಸಲಾಗಿದೆ ಮತ್ತು `src/shared/utils/apiAuth.ts` ಮೂಲಕ ಮರು-ರಫ್ತು ಮಾಡಲಾಗಿದೆ. ವ್ಯಾಲಿಡೇಟರ್ ಸಹ `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ಅನ್ನು ನಿರಂತರ ಪಾಸ್ಥ್ರೂ ಕೀಗಳಾಗಿ ಸ್ವೀಕರಿಸುತ್ತದೆ (ಸಂಚಿಕೆ #1350).

### 2. ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಷನ್ (auth_token ಕುಕೀ)

ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಪುಟಗಳು ಮತ್ತು ನಿರ್ವಾಹಕ ಕಾರ್ಯಾಚರಣೆಗಳಿಗಾಗಿ.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

JWT ಪರಿಶೀಲಿಸಿದಾಗ ಮಾತ್ರ ಕುಕೀ ಒಂದು ಸೆಷನ್ ಆಗಿದೆ** ಮತ್ತು** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) ಅನ್ನು ಒಯ್ಯುತ್ತದೆ. ಕುಕೀ (ಡ್ಯಾಶ್ಬೋರ್ಡ್ ರೂಟ್ ಗಾರ್ಡ್ (`isDashboardSessionAuthenticated()`), authz ಪೈಪ್ಲೈನ್ ರಿಫ್ರೆಶ್, WebSocket ಹ್ಯಾಂಡ್ಶೇಕ್, ಲೈವ್ ಸರ್ವರ್, `/api/settings/require-login`, `/api/auth/status`) ನ ಪ್ರತಿಯೊಬ್ಬ ಗ್ರಾಹಕರು ಆ ಸಹಾಯಕ ಮೂಲಕ ಹೋಗುತ್ತಾರೆ. `JWT_SECRET` ನೊಂದಿಗೆ ಸಹಿ ಮಾಡಲಾದ ಇತರ JWTs ಅಸ್ತಿತ್ವದಲ್ಲಿದೆ — Cursor CLI ಪಾಸ್ಥ್ರೂ ಮಿಂಟ್ಸ್ `iss "omniroute" / aud "cursor-cli"` ಟೋಕನ್ಗಳು ಕೀ ಹೋಲ್ಡರ್ಗಳಿಗೆ — ಮತ್ತು ಎಂದಿಗೂ ಸೆಷನ್ಗಳಾಗಿರುವುದಿಲ್ಲ (#13298).

`src/shared/utils/apiAuth.ts` ನಲ್ಲಿ `isDashboardSessionAuthenticated()` ಮೂಲಕ ಪರಿಶೀಲಿಸಲಾಗಿದೆ. ಪೈಪ್ಲೈನ್ ತನ್ನ 30-ದಿನಗಳ ಜೀವಿತಾವಧಿಯಲ್ಲಿ 7 ದಿನಗಳಿಗಿಂತ ಕಡಿಮೆ ಇರುವಾಗ JWT ಅನ್ನು ಸ್ವಯಂ-ರಿಫ್ರೆಶ್ ಮಾಡುತ್ತದೆ.

ಒಂದು ಸೆಶನ್ 30 ದಿನಗಳು ಮುಗಿಯುವ ಮೊದಲು ಕೊನೆಗೊಳ್ಳಬಹುದು, ಏಕೆಂದರೆ ಪ್ರತಿ minter `mintDashboardSessionToken` ಮೂಲಕ ಹೋಗುತ್ತದೆ (ಒಂದು ಸಮಸ್ಯೆ ಸಮಯ `iat` ಮತ್ತು id `jti`) ಮತ್ತು ಪರಿಶೀಲಕವು ಎರಡು ಸೆಟ್ಟಿಂಗ್ಗಳನ್ನು ಪರಿಶೀಲಿಸುತ್ತದೆ: `sessionsValidAfter`, ಪಾಸ್ವರ್ಡ್ ಬದಲಾವಣೆಯಿಂದ ಹೊಂದಿಸಲಾಗಿದೆ ಆದ್ದರಿಂದ ಪರಿಶೀಲಿಸುವುದನ್ನು ನಿಲ್ಲಿಸುವ ಮೊದಲು ನೀಡಲಾದ ಪ್ರತಿ ಸೆಷನ್ (ಪಾಸ್ವರ್ಡ್ ಅನ್ನು ಬದಲಾಯಿಸಿದ ಬ್ರೌಸರ್ ಹೊಸ ಕುಕೀಯನ್ನು ಪಡೆಯುತ್ತದೆ), ಮತ್ತು ಸೆಷನ್ಗೆ ಸೈನ್ ಔಟ್ ಮಾಡಲು `revokedDashboardSessions` ಅನ್ನು `jti`. `POST /api/auth/logout` ಹಳೆಯ ಬಿಡುಗಡೆಯಿಂದ ಮುದ್ರಿಸಲಾದ ಸೆಷನ್ಗಳು ಯಾವುದೇ ಕ್ಲೈಮ್ ಅನ್ನು ಹೊಂದಿರುವುದಿಲ್ಲ ಮತ್ತು ಮೊದಲ ಪಾಸ್ವರ್ಡ್ ಬದಲಾವಣೆಯವರೆಗೂ ಮಾನ್ಯವಾಗಿರುತ್ತವೆ. ಸೆಟ್ಟಿಂಗ್ಗಳನ್ನು ಓದಲಾಗದಿದ್ದರೆ, ಅಧಿವೇಶನವು ವಿಶ್ವಾಸಾರ್ಹವಲ್ಲ.

ಕೆಲವು ನಿರ್ವಹಣಾ ಮಾರ್ಗಗಳು ಸ್ವೀಕರಿಸುತ್ತವೆ** ಒಂದೋ** ಮೋಡ್: API ಕೀಲಿಯು `manage` (ಅಥವಾ `admin`) ವ್ಯಾಪ್ತಿಯನ್ನು ಹೊಂದಿರುವಾಗ ಕುಕೀ OR `Bearer <key>`. ಇದು v3.8 ರಲ್ಲಿ ಸೇರಿಸಲಾದ " API ಕರೆಗಳ ಮೂಲಕ ಕಾನ್ಫಿಗರ್ ಮಾಡಬಹುದಾದ" ವರ್ಕ್ಫ್ಲೋ ಅನ್ನು ಸಕ್ರಿಯಗೊಳಿಸುತ್ತದೆ.

#### ಐಚ್ಛಿಕ OIDC ಲಾಗಿನ್ ಗೇಟ್ (#6973)

ಡ್ಯಾಶ್ಬೋರ್ಡ್ ನಿರ್ವಾಹಕ ಲಾಗಿನ್ ಸಹ ಬೆಂಬಲಿಸುತ್ತದೆ** ಆಯ್ಕೆ** ಡಿಫಾಲ್ಟ್ ಪಾಸ್ವರ್ಡ್ ಲಾಗಿನ್ ಜೊತೆಗೆ OIDC (OpenID ಕನೆಕ್ಟ್) ಹರಿವು — ಪಾಸ್ವರ್ಡ್ ಲಾಗಿನ್ ಅನ್ನು ಎಂದಿಗೂ ತೆಗೆದುಹಾಕಲಾಗುವುದಿಲ್ಲ, ಕೇವಲ ಪೂರಕವಾಗಿದೆ:

- `settings.oidcEnabled === true` ಹೊರತು ನಿಷ್ಕ್ರಿಯಗೊಳಿಸಲಾಗಿದೆ** ಮತ್ತು** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` ಎಲ್ಲವನ್ನೂ ಕಾನ್ಫಿಗರ್ ಮಾಡಲಾಗಿದೆ (ಸೆಟ್ಟಿಂಗ್ಗಳು → Auth). `GET /api/auth/oidc/login` ಇಲ್ಲದಿದ್ದರೆ `400` ಹಿಂತಿರುಗಿಸುತ್ತದೆ.
- `GET /api/auth/oidc/login` ವಿತರಕರ `/.well-known/openid-configuration` ನಿಂದ `authorization_endpoint` ಕಂಡುಹಿಡಿಯುತ್ತದೆ ( `<issuer>/authorize` ಗೆ ಹಿಂತಿರುಗುತ್ತದೆ), ಒಳಬರುವ ವಿನಂತಿಯಿಂದ ಮರುನಿರ್ದೇಶನ URI ನಿರ್ಮಿಸುತ್ತದೆ (`x-forwarded-proto` -aware), ಮತ್ತು `httpOnly` `oidc_state` ಕುಕೀಯಲ್ಲಿ ಸಂಗ್ರಹಿಸಲಾದ ಯಾದೃಚ್ಛಿಕ `state` ನೊಂದಿಗೆ IdP ಗೆ ಮರುನಿರ್ದೇಶಿಸುತ್ತದೆ.
- `GET /api/auth/oidc/callback` `state` ಮೌಲ್ಯೀಕರಿಸುತ್ತದೆ, ದೃಢೀಕರಣ ಕೋಡ್ ಅನ್ನು ವಿನಿಮಯ ಮಾಡುತ್ತದೆ ಮತ್ತು `issuer`/`audience` ಚೆಕ್ಗಳೊಂದಿಗೆ ವಿತರಕರ JWKS (`jose` ನ `createRemoteJWKSet`, ಪ್ರತಿ JWKS URI ಸಂಗ್ರಹಿಸಲಾಗಿದೆ) ಮೂಲಕ ID ಟೋಕನ್ನ ಸಹಿಯನ್ನು ಪರಿಶೀಲಿಸುತ್ತದೆ. ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಪ್ರವೇಶಕ್ಕೆ ಖಾಲಿಯಿಲ್ಲದ `oidcAllowedSubjects` ಪಟ್ಟಿ, `oidcAdmissionClaim` ನೀತಿ ಅಥವಾ ಎರಡರ ಅಗತ್ಯವಿದೆ. ವಿಷಯದ ಪಟ್ಟಿಯು `sub` ಅಥವಾ `email` ಗೆ ಮಾತ್ರ `email_verified === true` ಹೊಂದಿಕೆಯಾಗುತ್ತದೆ. ಐಚ್ಛಿಕ ಹಕ್ಕು ನೀತಿಯು ಡಾಟ್-ಬೇರ್ಪಡಿಸಿದ ID-ಟೋಕನ್ ಕ್ಲೈಮ್ ಮಾರ್ಗವನ್ನು ತೆಗೆದುಕೊಳ್ಳುತ್ತದೆ (ಉದಾಹರಣೆಗೆ, `realm_access.roles`) ಮತ್ತು ಸ್ವೀಕರಿಸಿದ ಮೌಲ್ಯಗಳ ಒಂದು ಶ್ರೇಣಿಯನ್ನು; ಪರಿಹರಿಸಲಾದ ಹಕ್ಕು ಕನಿಷ್ಠ ಒಂದು ಸ್ವೀಕೃತ ಮೌಲ್ಯವನ್ನು ಹೊಂದಿರುವ ಸ್ಟ್ರಿಂಗ್ಗಳ ಒಂದು ಶ್ರೇಣಿಯಾಗಿರಬೇಕು. ಎರಡೂ ನೀತಿಗಳನ್ನು ಕಾನ್ಫಿಗರ್ ಮಾಡಿದ್ದರೆ, ಎರಡೂ ಪಾಸ್ ಆಗಬೇಕು. Missing/malformed ಕ್ಲೈಮ್ಗಳು ವಿಫಲವಾಗಿವೆ, ಮತ್ತು ಯಾವುದೇ ನೀತಿಯಿಲ್ಲದೆ ಕಾಲ್ಬ್ಯಾಕ್ ಲಾಗಿನ್ ಅನ್ನು ನಿರಾಕರಿಸುತ್ತದೆ (`not_configured`). ಅಸ್ತಿತ್ವದಲ್ಲಿರುವ ವಿಷಯ-ಮಾತ್ರ ಕಾನ್ಫಿಗರೇಶನ್ಗಳು ಬದಲಾಗದೆ ಮುಂದುವರಿಯುತ್ತವೆ.
- ಕೀಕ್ಲೋಕ್ ಸಾಮಾನ್ಯವಾಗಿ ಕ್ಷೇತ್ರದ ಪಾತ್ರಗಳನ್ನು ಪ್ರವೇಶ ಟೋಕನ್ಗಳಾಗಿ ನಕ್ಷೆ ಮಾಡುತ್ತದೆ, ಅಗತ್ಯವಾಗಿ ID ಟೋಕನ್ಗಳಲ್ಲ. ರೀಲ್ಮ್ ರೋಲ್ `admin` ಅಗತ್ಯವಿರುವಂತೆ, ಈ ಕ್ಲೈಂಟ್ಗಾಗಿ `realm_access.roles` ಅನ್ನು ಒಳಗೊಂಡಿರುವ ಪ್ರೋಟೋಕಾಲ್ ಮ್ಯಾಪರ್ ಅನ್ನು ಕಾನ್ಫಿಗರ್ ಮಾಡಿ**ID ಟೋಕನ್** , ನಂತರ `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` ಗೆ ಹೊಂದಿಸಿ. ಪಾತ್ರ-ಮಾತ್ರ ಪ್ರವೇಶವನ್ನು ಸಕ್ರಿಯಗೊಳಿಸುವ ಮೊದಲು ಈ ಕ್ಲೈಂಟ್ಗೆ ನಿಜವಾದ ಐಡಿ-ಟೋಕನ್ ಕ್ಲೈಮ್ ಅನ್ನು ಪರಿಶೀಲಿಸಿ; ಅಪ್ಲಿಕೇಶನ್ ಪ್ರವೇಶ-ಟೋಕನ್ ಪಾತ್ರಗಳನ್ನು ಓದುವುದಿಲ್ಲ. IdP-ಸೈಡ್ ಟೋಕನ್ ನಿರಾಕರಣೆ ಪೂರಕವಾಗಬಹುದು ಆದರೆ ಈ ಅಪ್ಲಿಕೇಶನ್-ಸೈಡ್ ಚೆಕ್ ಅನ್ನು ಬದಲಿಸುವುದಿಲ್ಲ.
- ಯಶಸ್ಸಿನ ಮೇಲೆ ಇದು mints ದಿ** ನಿಖರವಾಗಿ ಅದೇ** 30-ದಿನದ `auth_token` JWT ಪಾಸ್ವರ್ಡ್ ಲಾಗಿನ್ ಸಮಸ್ಯೆಗಳು (`src/app/api/auth/login/route.ts`), ಆದ್ದರಿಂದ ಉಳಿದ ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಶನ್ ಪೈಪ್ಲೈನ್ (ಸ್ವಯಂ-ರಿಫ್ರೆಶ್, ಕುಕೀ ಫ್ಲ್ಯಾಗ್ಗಳು) ಬದಲಾಗದೆ — OIDC ಕುಕೀ ಹೇಗೆ ಮುದ್ರಿಸುತ್ತದೆ ಎಂಬುದನ್ನು ಮಾತ್ರ ಬದಲಾಯಿಸುತ್ತದೆ, ಅದು ಏನನ್ನು ನೀಡುತ್ತದೆ ಎಂಬುದನ್ನು ಅಲ್ಲ. IdP roles/groups ಗೆ ಬದಲಾವಣೆಗಳು ಅಸ್ತಿತ್ವದಲ್ಲಿರುವ OmniRoute ಸೆಷನ್ಗಳನ್ನು ಅಮಾನ್ಯಗೊಳಿಸುವುದಿಲ್ಲ; ಲಾಗ್ಔಟ್, ಪಾಸ್ವರ್ಡ್ ಸರದಿ ಅಥವಾ ಸೆಷನ್ ಮುಕ್ತಾಯವು ಇನ್ನೂ ಅವರ ಜೀವಿತಾವಧಿಯನ್ನು ನಿಯಂತ್ರಿಸುತ್ತದೆ.
- ಪ್ರತಿ `oidc*` ಸೆಟ್ಟಿಂಗ್ (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` ನಲ್ಲಿದೆ (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` `400 PASSWORD_REQUIRED` ಉತ್ತರಿಸುತ್ತದೆ ಹೊರತು ದೇಹವು ನಿರ್ವಹಣಾ ಪಾಸ್ವರ್ಡ್ ತಪ್ಪಾಗಿಲ್ಲದಿದ್ದರೆ ( `currentPassword` `401 PASSWORD_MISMATCH` ಎಂದು). `oidcDisablePasswordLogin` ಪಾಸ್ವರ್ಡ್ _login_ (`POST /api/auth/login`) ಅನ್ನು ನಿರಾಕರಿಸುತ್ತದೆ ಆದರೆ ಸಂಗ್ರಹಿಸಿದ ಪಾಸ್ವರ್ಡ್ ಹ್ಯಾಶ್ ಅನ್ನು ಇರಿಸುತ್ತದೆ ಮತ್ತು ಮರು-ದೃಢೀಕರಣವು ಅದರ ವಿರುದ್ಧ `currentPassword` ಇನ್ನೂ ಪರಿಶೀಲಿಸುತ್ತದೆ.
- `corsOrigins` ಮತ್ತು `bruteForceProtection` ಸಹ `SECURITY_IMPACTING_SETTINGS_KEYS` ನಲ್ಲಿವೆ: ಸಡಿಲಗೊಳಿಸುವಿಕೆಯು ಲಾಗಿನ್ ರಕ್ಷಣೆಯನ್ನು ದುರ್ಬಲಗೊಳಿಸುತ್ತದೆ, ಆದ್ದರಿಂದ ಅವರು ಅದೇ `currentPassword` ಮರು-ದೃಢೀಕರಣವನ್ನು ತೆಗೆದುಕೊಳ್ಳುತ್ತಾರೆ (ಸೆಕ್ಯುರಿಟಿ ಟ್ಯಾಬ್ ಅದನ್ನು ಕೇಳುತ್ತದೆ) ಮತ್ತು JSON ಆಮದು ಅವುಗಳನ್ನು ಕೈಬಿಡುತ್ತದೆ.
- ಪ್ರತಿ ಭದ್ರತಾ-ನೀತಿ ಕೀ — `SECURITY_IMPACTING_SETTINGS_KEYS` ನಮೂದುಗಳು, ಪ್ರತಿ `oidc*` ಕೀ ಮತ್ತು ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಷನ್ ಸ್ಥಿತಿ —** ಆಪರೇಟರ್-ಮಾತ್ರ** `PATCH /api/settings` ನಲ್ಲಿ: ಮ್ಯಾನೇಜ್-ಸ್ಕೋಪ್ಡ್ API ಕೀ ಅಥವಾ `oma_` ಪ್ರವೇಶ ಟೋಕನ್ ಅನ್ನು ಅದು ಸರಿಯಾದ `currentPassword` ಕಳುಹಿಸಿದಾಗಲೂ `403` ನೊಂದಿಗೆ ನಿರಾಕರಿಸಲಾಗುತ್ತದೆ ಮತ್ತು ನಿರಾಕರಣೆಯನ್ನು `reason: OPERATOR_REQUIRED` ನೊಂದಿಗೆ `settings.update_failed` ಎಂದು ಆಡಿಟ್ ಮಾಡಲಾಗುತ್ತದೆ ( `src/lib/api/operatorCredential.ts` ನಲ್ಲಿ`requireOperatorCredential()` ). ಸಾಮಾನ್ಯ ಸೆಟ್ಟಿಂಗ್ಗಳು (ಥೀಮ್, ಪ್ರದರ್ಶನ ಪ್ರಾಶಸ್ತ್ಯಗಳು) `manage` ಕೀ ಅಥವಾ `admin` ಪ್ರವೇಶ ಟೋಕನ್ಗಾಗಿ ಬರೆಯಬಹುದಾಗಿದೆ. `/api/settings` ನ ಪ್ರತಿಯೊಂದು ರೂಪಾಂತರಕ್ಕೂ (ಮತ್ತು `/api/settings/require-login`) `admin` ಪ್ರವೇಶ-ಟೋಕನ್ ಸ್ಕೋಪ್ ( `src/server/authz/accessScopes.ts` ನಲ್ಲಿ`ADMIN_MUTATION_EXACT_PATHS`, ನಿಖರವಾದ-ಪಥ ಹೊಂದಾಣಿಕೆ) ಅಗತ್ಯವಿದೆ; `GET` ಸ್ಟೇಸ್ `read`, ಮತ್ತು ಇತರ `/api/settings/*` ಉಪ-ಮಾರ್ಗಗಳು (ಪ್ರಾಕ್ಸಿಗಳು, ಕಾಂಬೊ ಡೀಫಾಲ್ಟ್ಗಳು, ಮಾಡೆಲ್ ಅಲಿಯಾಸ್ಗಳು, ಕಂಪ್ರೆಷನ್, ಪರ್ಜ್ಗಳು...) ವಿಧಾನ-ಊಹಿಸಲಾದ `write` ವ್ಯಾಪ್ತಿಯನ್ನು ಇರಿಸಿಕೊಳ್ಳಿ.
- `POST /api/settings/import-json` ಆ ಮರು-ದೃಢೀಕರಣವನ್ನು ಬಿಟ್ಟುಬಿಡುತ್ತದೆ, ಆದ್ದರಿಂದ ಅದು ಬರೆಯುವ ಮೊದಲು `IMPORT_STRIPPED_SETTINGS_KEYS` (ಅದೇ ಫೈಲ್) ನಲ್ಲಿ ಪ್ರತಿ ಕೀಲಿಯನ್ನು ಬಿಡುತ್ತದೆ: ಪಾಸ್ವರ್ಡ್ ಮತ್ತು `currentPassword`, ಪ್ರತಿ `SECURITY_IMPACTING_SETTINGS_KEYS` ನಮೂದು, ಮತ್ತು ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಷನ್ ಸ್ಥಿತಿ (`sessionsValidAfter`, `revokedDashboardSessions`). ಹಳೆಯ ಬ್ಯಾಕಪ್ ಅನ್ನು ಆಮದು ಮಾಡಿಕೊಳ್ಳುವುದರಿಂದ ಪಾಸ್ವರ್ಡ್ ಬದಲಾವಣೆ ಅಥವಾ ಸೈನ್ ಔಟ್ ಈಗಾಗಲೇ ಮುಗಿದಿರುವ ಸೆಶನ್ ಅನ್ನು ಪುನರುಜ್ಜೀವನಗೊಳಿಸಲು ಸಾಧ್ಯವಿಲ್ಲ.

#### ಐಚ್ಛಿಕ TOTP ಎರಡು-ಅಂಶ ಲಾಗಿನ್ (#16619)

ಸೆಟ್ಟಿಂಗ್ಗಳ → ಭದ್ರತೆಯಿಂದ ನೋಂದಾಯಿಸಲಾಗಿದೆ; ಆಪರೇಟರ್ ಅದನ್ನು ಆನ್ ಮಾಡುವವರೆಗೆ ಆಫ್ ಮಾಡಿ (`src/server/auth/dashboardMfa.ts`).

- **ಇದು ಏನು ಒಳಗೊಂಡಿದೆ:** ಪಾಸ್ವರ್ಡ್ ಲಾಗಿನ್ (`POST /api/auth/login`, ನಂತರ `POST /api/auth/mfa/verify` ಅಗತ್ಯವಿದೆ) ಮತ್ತು `omniroute connect` (`POST /api/cli/connect`, ಇದು ಪಾಸ್ವರ್ಡ್-ಮಾತ್ರ ವಿನಿಮಯವನ್ನು ನಿರಾಕರಿಸುತ್ತದೆ ಮತ್ತು ಕೋಡ್ ಅನ್ನು `totp` ಆಗಿ ತೆಗೆದುಕೊಳ್ಳುತ್ತದೆ).
- **ಅದು ಏನು ಒಳಗೊಂಡಿರುವುದಿಲ್ಲ:** OIDC / SSO ಸೈನ್-ಇನ್ (`/api/auth/oidc/callback`) OmniRoute TOTP ಗಾಗಿ ಕೇಳುವುದಿಲ್ಲ. ಇದು ಗುರುತಿನ ಪೂರೈಕೆದಾರರ ಸ್ವಂತ ಎರಡನೇ ಅಂಶವನ್ನು ಅವಲಂಬಿಸಿದೆ, ಆದ್ದರಿಂದ OIDC ಸಕ್ರಿಯಗೊಳಿಸಿದರೆ IdP ನಲ್ಲಿ MFA ಜಾರಿಗೊಳಿಸಿ.
- **ಚೇತರಿಕೆ** (ಕಳೆದುಹೋದ ಸಾಧನ, ಯಾವುದೇ ಮರುಪಡೆಯುವಿಕೆ ಕೋಡ್ಗಳು ಉಳಿದಿಲ್ಲ, ಅಥವಾ ಇನ್ನು ಮುಂದೆ ಪರಿಶೀಲಿಸಲಾಗದ ಅಂಶ, ಉದಾಹರಣೆಗೆ `STORAGE_ENCRYPTION_KEY` ಬದಲಾದ ನಂತರ):
  1. `OMNIROUTE_DISABLE_MFA=true` ನೊಂದಿಗೆ ಸರ್ವರ್ ಅನ್ನು ಮರುಪ್ರಾರಂಭಿಸಿ.
  2. ಹೋಸ್ಟ್ನಲ್ಲಿಯೇ (ಲೂಪ್ಬ್ಯಾಕ್ ಪೀರ್ ಮತ್ತು ಲೂಪ್ಬ್ಯಾಕ್ `Host`, ಉದಾಹರಣೆಗೆ `http://localhost:20128`), ಪಾಸ್ವರ್ಡ್ನೊಂದಿಗೆ ಸೈನ್ ಇನ್ ಮಾಡಿ. ಎರಡನೆಯ ಅಂಶವನ್ನು ಆ ಮೂಲಕ್ಕೆ ಮಾತ್ರ ಬಿಟ್ಟುಬಿಡಲಾಗಿದೆ; ಪ್ರತಿ ಇತರ ಮೂಲಕ್ಕೆ ಇನ್ನೂ ಕೋಡ್ ಅಗತ್ಯವಿದೆ.
  3. ಸೆಟ್ಟಿಂಗ್ಗಳಲ್ಲಿ → Security → ನಿಷ್ಕ್ರಿಯಗೊಳಿಸಿ, ಪಾಸ್ವರ್ಡ್ ನಮೂದಿಸಿ ಮತ್ತು ಕೋಡ್ ಅನ್ನು ಖಾಲಿ ಬಿಡಿ. ವೇರಿಯಬಲ್ ಅನ್ನು ಹೊಂದಿಸಿದಾಗ ಮತ್ತು ಹೋಸ್ಟ್ನಿಂದ ವಿನಂತಿಯು ಬಂದಾಗ ಮಾತ್ರ `POST /api/auth/mfa/disable` `code` ಇಲ್ಲದೆ ದೇಹವನ್ನು ಸ್ವೀಕರಿಸುತ್ತದೆ; ಇದಕ್ಕೆ ಇನ್ನೂ ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಶನ್ ಮತ್ತು ಪ್ರಸ್ತುತ ಪಾಸ್ವರ್ಡ್ ಅಗತ್ಯವಿರುತ್ತದೆ ಮತ್ತು `secondFactor: "recovery_switch"` ನೊಂದಿಗೆ `auth.mfa.disabled` ಎಂದು ಆಡಿಟ್ ಮಾಡಲಾಗುತ್ತದೆ.
  4. `OMNIROUTE_DISABLE_MFA` ಹೊಂದಿಸಬೇಡಿ, ಮರುಪ್ರಾರಂಭಿಸಿ ಮತ್ತು ಅಗತ್ಯವಿದ್ದರೆ ಮತ್ತೆ ನೋಂದಾಯಿಸಿ.

## ರೂಟ್ ವರ್ಗಗಳು

`src/server/authz/types.ts` ಮೂರು ವರ್ಗಗಳನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುತ್ತದೆ; ನಿರ್ಧಾರಾತ್ಮಕವಾಗಿ ವರ್ಗೀಕರಿಸಲಾಗದ ಯಾವುದೇ ರೂಟ್ `MANAGEMENT` ಗೆ ಹಿಂದಿರುಗುತ್ತದೆ.

| ವರ್ಗ         | ವಿವರಣೆ                                                                                                                                                        | ದೃಢೀಕರಣ ಅಗತ್ಯ                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| `PUBLIC`     | ಸ್ಪಷ್ಟವಾಗಿ ಸುರಕ್ಷಿತ ರೂಟ್‌ಗಳು — ಲಾಗಿನ್, ಲಾಗೌಟ್, ಸ್ಥಿತಿ, ಆರಂಭ, ಆರೋಗ್ಯ, ಆನ್‌ಬೋರ್ಡಿಂಗ್ ಬೂಟ್‌ಸ್ಟ್ರ್ಯಾಪ್.                                                           | ಯಾವುದೂ ಇಲ್ಲ                                                           |
| `CLIENT_API` | ಮಾದರಿ-ಸೇವೆ ಎಂಡ್‌ಪಾಯಿಂಟ್‌ಗಳು — `/api/v1/*`, `/api/v1beta/*`, ಮತ್ತು ಅಲಿಯಾಸ್‌ಗಳು `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | ಪರಿಣಾಮಕಾರಿ `REQUIRE_API_KEY` ಫೀಚರ್ ಫ್ಲ್ಯಾಗ್ ಸಕ್ರಿಯವಾಗಿದ್ದಾಗ Bearer ಕೀ |
| `MANAGEMENT` | ಡ್ಯಾಶ್‌ಬೋರ್ಡ್ ಪುಟಗಳು, ಸೆಟ್ಟಿಂಗ್‌ಗಳು, ಪೂರೈಕೆದಾರರು, ಕೀಗಳು, ಆಡಳಿತ ಮತ್ತು ರೋಗನಿರ್ಣಯ ಎಂಡ್‌ಪಾಯಿಂಟ್‌ಗಳು.                                                              | ಡ್ಯಾಶ್‌ಬೋರ್ಡ್ ಸೆಷನ್ ಅಥವಾ `manage` ಸ್ಕೋಪ್‌ನ Bearer                     |

ಕೆಲವು `MANAGEMENT` ಕ್ರಿಯೆಗಳು **ಆಪರೇಟರ್-ಮಾತ್ರ**: `manage` ಕೀ ಸಾಕಾಗುವುದಿಲ್ಲ. ಸಂಗ್ರಹಿತ ಕ್ರೆಡೆನ್ಶಿಯಲ್‌ಗಳನ್ನು ರಫ್ತು ಮಾಡುವುದು (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ಲೈವ್ ಡೇಟಾದ ಮೇಲೆ ಬ್ಯಾಕಪ್ ಮರುಸ್ಥಾಪಿಸುವುದು (`dryRun=true` ಸಹಿತ `POST /api/db-backups/import`, ID ಮೂಲಕ ಮರುಸ್ಥಾಪನೆಯ `POST /api/db-backups`, `POST /api/settings/import-json`), ಮರುಸ್ಥಾಪನೆ ಬಿಂದುಗಳನ್ನು ನಾಶಪಡಿಸುವುದು (`DELETE /api/db-backups` ಕ್ಲೀನಪ್, ಮತ್ತು `PATCH /api/db-backups` ಏಕೆಂದರೆ ಅದು ಉಳಿಸುವ ಧಾರಣ ನೀತಿಯು ಪ್ರತಿ ಬ್ಯಾಕಪ್ ನಂತರದ ಸ್ವಯಂಚಾಲಿತ ಕ್ಲೀನಪ್ ಅನ್ನು ನಿಯಂತ್ರಿಸುತ್ತದೆ) ಇವೆಲ್ಲವಕ್ಕೂ ಡ್ಯಾಶ್‌ಬೋರ್ಡ್ ಸೆಷನ್, ಸ್ಥಳೀಯ CLI ವಿಷಯ, ಅಥವಾ ಲಾಗಿನ್ ನಿಷ್ಕ್ರಿಯವಾಗಿರುವುದು ಬೇಕು. ಸಿಂಕ್ ಟೋಕನ್ ನೀಡುವುದು (`POST /api/sync/tokens`) ಮತ್ತು `admin` CLI ಪ್ರವೇಶ ಟೋಕನ್ ರಚಿಸುವುದು (`POST /api/cli/tokens`) ಪ್ರತಿ ಲಾಗಿನ್ ಮೋಡ್‌ನಲ್ಲೂ ಡ್ಯಾಶ್‌ಬೋರ್ಡ್ ಸೆಷನ್ ಅಥವಾ ಸ್ಥಳೀಯ CLI ವಿಷಯ ಬೇಕು. ಯಾವುದೇ ಸ್ಕೋಪ್‌ನ API ಕೀಗಳು ಮತ್ತು `oma_` ಪ್ರವೇಶ ಟೋಕನ್‌ಗಳು ಆಪರೇಟರ್ ಕ್ರೆಡೆನ್ಶಿಯಲ್‌ಗಳಲ್ಲ: ಅಗತ್ಯವಿರುವಾಗೆಲ್ಲ ಅವು `403` ಪಡೆಯುತ್ತವೆ. ಈ ಪರಿಶೀಲನೆ `src/lib/api/operatorCredential.ts` ನಲ್ಲಿದೆ (`resolveOperatorCredential()` / `requireOperatorCredential()`). ಲಾಗಿನ್ ಸೆಟ್ಟಿಂಗ್‌ಗಳನ್ನು ಬದಲಿಸುವುದೂ ಆಪರೇಟರ್-ಮಾತ್ರ: ಪಾಸ್‌ವರ್ಡ್ ಇದ್ದ ನಂತರ `POST /api/settings/require-login` (ಮ್ಯಾನೇಜ್‌ಮೆಂಟ್ ಪಾಸ್‌ವರ್ಡ್ ಹೊಂದಿಸುವುದು / `requireLogin` ಟಾಗಲ್ ಮಾಡುವುದು) ಈ ಕ್ರೆಡೆನ್ಶಿಯಲ್‌ಗಳನ್ನು ಮಾತ್ರ ಸ್ವೀಕರಿಸುತ್ತದೆ — ಮೊದಲ-ರನ್ ಬೂಟ್‌ಸ್ಟ್ರ್ಯಾಪ್ ವಿಂಡೋ (ಇನ್ನೂ ಪಾಸ್‌ವರ್ಡ್ ಇಲ್ಲದಿರುವಾಗ) ಬದಲಾಗುವುದಿಲ್ಲ — ಮತ್ತು ಡ್ಯಾಶ್‌ಬೋರ್ಡ್ ಸೆಷನ್ ಪಾಸ್‌ವರ್ಡ್ ಬದಲಿಸಲು `currentPassword` ಕಳುಹಿಸಬೇಕು (ಇಲ್ಲದಿದ್ದರೆ ಅಥವಾ ತಪ್ಪಾಗಿದ್ದರೆ `403`, `settings.update_failed` ಎಂದು ಆಡಿಟ್). ಸ್ಥಳೀಯ CLI ಮತ್ತು ಲಾಗಿನ್ ನಿಷ್ಕ್ರಿಯವಾಗಿರುವ ನಿದರ್ಶನವು ಮರುಪಡೆಯುವಿಕೆ ಮಾರ್ಗವನ್ನು ಉಳಿಸಿಕೊಳ್ಳುತ್ತವೆ ಮತ್ತು ಅದಿಲ್ಲದೆಯೂ ಪಾಸ್‌ವರ್ಡ್ ಹೊಂದಿಸಬಹುದು, ಏಕೆಂದರೆ ಎರಡೂ ಡೇಟಾ ಡೈರೆಕ್ಟರಿಯನ್ನು ಹೊಂದಿರುವ ಹೋಸ್ಟ್‌ಗೆ ಬದ್ಧವಾಗಿವೆ.

## ಪೈಪ್ಲೈನ್

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

ವಿಶ್ವಾಸಾರ್ಹ ಆಂತರಿಕ ಹೆಡರ್ಗಳು ( `src/server/authz/headers.ts` ನಲ್ಲಿ ವ್ಯಾಖ್ಯಾನಿಸಲಾಗಿದೆ).** ಒಳಬರುವ ವಿನಂತಿಗಳಿಂದ ತೆಗೆದುಹಾಕಲಾಗಿದೆ** ವರ್ಗೀಕರಣದ ಮೊದಲು — ಕ್ಲೈಂಟ್ಗಳು ವಿಷಯವನ್ನು ಸೋಗು ಹಾಕಲು `x-omniroute-auth-*` ಪೂರ್ವ-ಜನಪ್ರಿಯಗೊಳಿಸುವಂತಿಲ್ಲ.

### ನೀತಿ ಒಪ್ಪಂದಗಳು

ಪ್ರತಿಯೊಂದು ಮಾರ್ಗ ವರ್ಗವು `src/server/authz/policies/` ನಲ್ಲಿ ನೀತಿಯನ್ನು ಹೊಂದಿದೆ:

- **`publicPolicy`** (`policies/public.ts`) — ಯಾವಾಗಲೂ `allow({ kind: "anonymous", id: "anonymous" })` ಹಿಂದಿರುಗಿಸುತ್ತದೆ.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ಸಾರಗಳು ಬೇರರ್, `validateApiKey()` ಮೂಲಕ ಮೌಲ್ಯೀಕರಿಸುತ್ತದೆ. ಪರಿಣಾಮಕಾರಿ `REQUIRE_API_KEY` ವೈಶಿಷ್ಟ್ಯದ ಫ್ಲ್ಯಾಗ್ ಅನ್ನು ನಿಷ್ಕ್ರಿಯಗೊಳಿಸಿದಾಗ ಮಾತ್ರ ಅನಾಮಧೇಯರಿಗೆ ಬರುತ್ತದೆ. ಪರಿಣಾಮಕಾರಿ ಫ್ಲ್ಯಾಗ್ ಅನ್ನು `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ಮೂಲಕ ಪರಿಹರಿಸಲಾಗುತ್ತದೆ ಆದ್ದರಿಂದ ಡ್ಯಾಶ್ಬೋರ್ಡ್ ವೈಶಿಷ್ಟ್ಯ ಫ್ಲ್ಯಾಗ್ಗಳು ಮತ್ತು ಪರಿಸರ ವೇರಿಯಬಲ್ಗಳು `/api/v1/*`, `/api/v1beta/*` ಮತ್ತು ಅಲಿಯಾಸ್ಗಳನ್ನು ಸ್ಥಿರವಾಗಿ ನಿಯಂತ್ರಿಸುತ್ತವೆ; ಪರಿಹಾರಕ ವೈಫಲ್ಯಗಳು ವಿಫಲವಾಗಿವೆ ಮುಚ್ಚಲಾಗಿದೆ. ಕ್ಲೈಂಟ್ API ಮಾರ್ಗಗಳಲ್ಲಿ ಡ್ಯಾಶ್ಬೋರ್ಡ್-ಸೆಷನ್ ವಿನಂತಿಗಳನ್ನು ಅನುಮತಿಸುತ್ತದೆ (ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಮಾದರಿ ಕ್ಯಾಟಲಾಗ್ನಿಂದ ಬಳಸಲಾಗುವ `/api/v1/models` ಸೇರಿದಂತೆ). Entra ID SSO ಸಕ್ರಿಯಗೊಳಿಸಿದಾಗ, ರಚನಾತ್ಮಕವಾಗಿ ಎಂಟ್ರಾ ಟೋಕನ್ ಆಗಿರುವ ಬೇರರ್ (ಮೂರು base64url ವಿಭಾಗಗಳು, `RS*` alg, `kid`) SSO ಶಾಖೆಯಿಂದ ನಿರ್ವಹಿಸಲ್ಪಡುತ್ತದೆ** ಮೊದಲು** `validateApiKey()` ಮತ್ತು ಅದರ ತೀರ್ಪು ಅಂತಿಮ — ಆಗಿದೆ, ಅದು ಎಂದಿಗೂ API-ಕೀ ಪಥ ಅಥವಾ ಅನಾಮಧೇಯ ಶಾಖೆಗೆ ಬೀಳುವುದಿಲ್ಲ, ಆದ್ದರಿಂದ ಗುರುತನ್ನು ಒದಗಿಸುವವರ ಸ್ಥಗಿತವು ಮುಕ್ತ ಪ್ರವೇಶವಾಗುವುದಿಲ್ಲ. ಸ್ಥಿರ API ಕೀಗಳು ಪರಿಣಾಮ ಬೀರುವುದಿಲ್ಲ. [Entra ID SSO](../security/ENTRA_SSO.md) ನೋಡಿ.
- **`managementPolicy`** (`policies/management.ts`) — ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಷನ್, ಆಂತರಿಕ ಮಾದರಿ-ಸಿಂಕ್ ವಿನಂತಿಗಳನ್ನು ( `/api/providers/[name]/(sync-models|models)` ವಿರುದ್ಧ ಹೊಂದಿಕೆಯಾಗುತ್ತದೆ) ಸ್ವೀಕರಿಸುತ್ತದೆ ಅಥವಾ `isAuthRequired()` ತಪ್ಪನ್ನು ಹಿಂತಿರುಗಿಸಿದರೆ ಸಂಪೂರ್ಣವಾಗಿ ಬಿಟ್ಟುಬಿಡುತ್ತದೆ. ಬೇರರ್ ಟೋಕನ್ ಇರುವಾಗ 403 (`AUTH_001`) ಅನ್ನು ಹಿಂತಿರುಗಿಸುತ್ತದೆ ಆದರೆ ಅಮಾನ್ಯವಾಗಿದೆ, ಇಲ್ಲದಿದ್ದರೆ 401. ಯಾವುದೇ auth ಶಾಖೆಯ ಮೊದಲು ಮಾರ್ಗ-ರಕ್ಷಕ ಶ್ರೇಣಿಗಳನ್ನು (LOCAL_ONLY / ALWAYS_PROTECTED) ಜಾರಿಗೊಳಿಸುತ್ತದೆ — [ರೂಟ್ ಗಾರ್ಡ್ ಶ್ರೇಣಿಗಳನ್ನು](../security/ROUTE_GUARD_TIERS.md) ನೋಡಿ. `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ನಲ್ಲಿ LOCAL_ONLY ಮಾರ್ಗಗಳು (ಇಂದು: `/api/mcp/`) ಬೇರರ್ ಕೀ `manage` ಸ್ಕೋಪ್ ಅನ್ನು ಹೊಂದಿರುವಾಗ ಲೂಪ್ಬ್ಯಾಕ್ ಅಲ್ಲದ ಮೂಲಕ ಪ್ರವೇಶಿಸಬಹುದು; ಎಲ್ಲಾ ಇತರ LOCAL_ONLY ಮಾರ್ಗಗಳು ವ್ಯಾಪ್ತಿಯನ್ನು ಲೆಕ್ಕಿಸದೆ ಕಟ್ಟುನಿಟ್ಟಾದ-ಲೂಪ್ಬ್ಯಾಕ್ ಆಗಿರುತ್ತವೆ.

ಯಶಸ್ವಿ ನೀತಿಯು `AuthSubject` `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` ನೊಂದಿಗೆ ಹಿಂತಿರುಗಿಸುತ್ತದೆ. ಡೌನ್ಸ್ಟ್ರೀಮ್ ಹ್ಯಾಂಡ್ಲರ್ಗಳು ದೃಢೀಕರಣ ತರ್ಕವನ್ನು ಮರು-ಚಾಲನೆ ಮಾಡುವ ಬದಲು `src/server/authz/assertAuth.ts` ನಲ್ಲಿ `assertAuth(request, "CLIENT_API")` ಮೂಲಕ ಓದಬಹುದು.

## ಸಾರ್ವಜನಿಕ ಮಾರ್ಗಗಳ ಪಟ್ಟಿ

`src/shared/constants/publicApiRoutes.ts` ಸ್ಪಷ್ಟವಾದ ಅನುಮತಿ ಪಟ್ಟಿಯಾಗಿದೆ:

ಪಟ್ಟಿಯನ್ನು ವಿಂಗಡಿಸಲಾಗಿದೆ** ಆಕಾರ** , ಮತ್ತು ವಿಭಜನೆಯು ಲೋಡ್-ಬೇರಿಂಗ್ ಆಗಿದೆ (GHSA-74g9-q8f6-793h): ಪೂರ್ವಪ್ರತ್ಯಯವು `startsWith()` ನೊಂದಿಗೆ ಹೊಂದಾಣಿಕೆಯಾಗುತ್ತದೆ, ಆದ್ದರಿಂದ ಇದು ಅದರ ಪ್ರಮುಖ ಪಾತ್ರಗಳನ್ನು ಹಂಚಿಕೊಳ್ಳುವ ಪ್ರತಿಯೊಂದು ಪಕ್ಕದ ಮಾರ್ಗಕ್ಕೂ ಹೊಂದಿಕೆಯಾಗುತ್ತದೆ. `/api/usage/om-usage` ಪೂರ್ವಪ್ರತ್ಯಯವಾಗಿ `/api/usage/om-usage<anything>` PUBLIC ಎಂದು ಗುರುತಿಸಲಾಗಿದೆ, ಮತ್ತು ಮುಂದೆ ತನ್ನದೇ ಆದ ದೃಢೀಕರಣವನ್ನು ಹೊಂದಿರದ ಹ್ಯಾಂಡ್ಲರ್ ಅನ್ನು `/api/usage/[connectionId]` — ಎಂದು ಪರಿಹರಿಸುತ್ತದೆ.

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

ಓದಲು-ಮಾತ್ರ ಮಾರ್ಗಗಳು ಸಾರ್ವಜನಿಕವಾಗಿವೆ** ಮಾತ್ರ** ಸುರಕ್ಷಿತ ವಿಧಾನಗಳಿಗಾಗಿ. ಗಮನಿಸಿ: `classifyRoute()` `/api/v1/*` ಮತ್ತು `/api/v1beta/*` PUBLIC ಫಾಲ್-ಥ್ರೂ — ನಿಂದ ಹೊರತುಪಡಿಸುತ್ತದೆ, ಅವು ಯಾವಾಗಲೂ `CLIENT_API` ಆಗಿರುತ್ತವೆ ಆದ್ದರಿಂದ ಬೇರರ್-ಕೀ ನೀತಿಯು ಇನ್ನೂ ಅನ್ವಯಿಸುತ್ತದೆ.

## ಹೊಸ ರೂಟ್ ಸೇರಿಸುವುದು

### ಮಾದರಿ 1 — ಸಾರ್ವಜನಿಕ ಕ್ಲೈಂಟ್ API ಎಂಡ್ಪಾಯಿಂಟ್ (Bearer-auth)

`/api/v1/` ಮತ್ತು `/api/v1beta/` ಅಡಿಯಲ್ಲಿರುವ ರೂಟ್ಗಳನ್ನು ಸ್ವಯಂಚಾಲಿತವಾಗಿ `CLIENT_API` ಎಂದು ವರ್ಗೀಕರಿಸಲಾಗುತ್ತದೆ. ಮಿಡಲ್ವೇರ್ Bearer ಪರಿಶೀಲನೆಯನ್ನು ಜಾರಿಗೊಳಿಸುತ್ತದೆ; ರೂಟ್ ಹ್ಯಾಂಡ್ಲರ್ಗಳು ಅದನ್ನು ಮರುಮಾಡುವ ಅಗತ್ಯವಿಲ್ಲ, ಆದರೆ ಉಪಯುಕ್ತವಾಗಿದ್ದರೆ subject ಅನ್ನು ಓದಬಹುದು.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... ಹ್ಯಾಂಡ್ಲರ್ ತರ್ಕ
}
```

### ಮಾದರಿ 2 — ನಿರ್ವಹಣಾ ಎಂಡ್ಪಾಯಿಂಟ್ (ಸೆಷನ್ ಅಥವಾ Bearer + manage)

`src/lib/api/requireManagementAuth.ts` ನಿಂದ `requireManagementAuth()` ಅನ್ನು ಬಳಸಿ:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... ಹ್ಯಾಂಡ್ಲರ್ ತರ್ಕ
}
```

ಯಶಸ್ವಿಯಾದಾಗ `requireManagementAuth()` `null` ಅನ್ನು ಅಥವಾ JSON ದೋಷದ `Response` ಅನ್ನು ಹಿಂತಿರುಗಿಸುತ್ತದೆ:

- 401 `AUTH_001` "ದೃಢೀಕರಣ ಅಗತ್ಯವಿದೆ" — ಯಾವುದೇ ರುಜುವಾತುಗಳಿಲ್ಲ
- 403 — ಅಮಾನ್ಯ Bearer **ಅಥವಾ** Bearer ಇದೆ, ಆದರೆ ಕೀ `manage` / `admin` ಸ್ಕೋಪ್ ಅನ್ನು ಹೊಂದಿಲ್ಲ

`hasManageScope(scopes)` `"manage"` ಅಥವಾ `"admin"` ಗೆ true ಅನ್ನು ಹಿಂತಿರುಗಿಸುತ್ತದೆ.

### ಮಾದರಿ 3 — ಸಾರ್ವಜನಿಕ ಅನುಮತಿ ಪಟ್ಟಿಗೆ ಸೇರಿಸುವುದು

ಅನುಕೂಲತೆಯ ಆಧಾರದ ಮೇಲೆ ಅಲ್ಲ, ಆಕಾರದ ಆಧಾರದ ಮೇಲೆ ಸೆಟ್ ಅನ್ನು ಆಯ್ಕೆಮಾಡಿ. ಒಂದೇ ರೂಟ್ ಅನ್ನು `PUBLIC_API_ROUTES_EXACT` ನಲ್ಲಿ (ಅಥವಾ GET-ಮಾತ್ರಕ್ಕಾಗಿ `PUBLIC_READONLY_CORS_API_ROUTES` ನಲ್ಲಿ) ಇರಿಸಬೇಕು; ನಿಜವಾದ ಉಪವೃಕ್ಷವನ್ನು ಮಾತ್ರ `PUBLIC_API_ROUTE_PREFIXES` ನಲ್ಲಿ ಇರಿಸಬೇಕು ಮತ್ತು ಅದು **`/` ನೊಂದಿಗೆ ಕೊನೆಗೊಳ್ಳಲೇಬೇಕು**. ಒಂದೇ ರೂಟ್ ಅನ್ನು ಪ್ರಿಫಿಕ್ಸ್ ಪಟ್ಟಿಯಲ್ಲಿ ಇರಿಸುವುದರಿಂದ ಅದರ ಆರಂಭಿಕ ಅಕ್ಷರಗಳನ್ನು ಹಂಚಿಕೊಳ್ಳುವ ಪ್ರತಿಯೊಂದು ಪಕ್ಕದ ಪಥವೂ ಪ್ರಕಟವಾಗುತ್ತದೆ — ನಂತರ ಸೇರಿಸಲಾದ ಡೈನಾಮಿಕ್-ಸೆಗ್ಮೆಂಟ್ ಸಿಬ್ಲಿಂಗ್ಗಳೂ ಇದರಲ್ಲಿ ಸೇರಿವೆ (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ಮತ್ತು `tests/unit/authz/classify.test.ts` ನಲ್ಲಿರುವ ಯೂನಿಟ್ ಪರೀಕ್ಷೆಗಳನ್ನು ನವೀಕರಿಸಿ.

## ಸ್ಕೋಪ್ಗಳು

ಮೂರು ನೇಮ್ಸ್ಪೇಸ್ಗಳು. ಪ್ರತಿ ಚೆಕರ್ ತನ್ನದೇ ಆದ ಸ್ಟ್ರಿಂಗ್ಗಳನ್ನು ಮಾತ್ರ ಓದುತ್ತದೆ. ಪಕ್ಕಪಕ್ಕದಲ್ಲಿ,
`read:compression` ಗಾಗಿ `manage` ಏಕೆ `scopeMatches` ಅನ್ನು ವಿಫಲಗೊಳಿಸುತ್ತದೆ ಮತ್ತು `read` ಪ್ರವೇಶ ಟೋಕನ್ ಏಕೆ `PATCH /api/keys/{id}` ಅನ್ನು ಮಾಡಲು ಸಾಧ್ಯವಿಲ್ಲ ಎಂಬುದನ್ನು ಒಳಗೊಂಡಂತೆ,
[ಮೂರು ಸ್ಕೋಪ್ ನೇಮ್ಸ್ಪೇಸ್ಗಳು](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API ಕೀಗಳು `scopes` ಅರೇ ಅನ್ನು ಹೊಂದಿರುತ್ತವೆ (`api_keys.scopes` ನಲ್ಲಿ JSON ಆಗಿ ಸಂಗ್ರಹಿಸಲಾಗಿದೆ, `src/lib/db/apiKeys.ts` ನೋಡಿ).

### ನಿರ್ವಹಣಾ ಸ್ಕೋಪ್

- `manage` / `admin` — `hasManageScope`. ನಿರ್ವಹಣಾ API ಮಾರ್ಗಗಳಿಗೆ ಬೇರರ್ ಪ್ರವೇಶ.
- `mcp:connect`, `self:usage`, `self:account-quota`, ಮತ್ತು
  `policy:bypass-provider-quota` ಇವುಗಳು ಸಂಯೋಜಕ ನಿಖರ-ಹೊಂದಾಣಿಕೆಯ ಸ್ಕೋಪ್ಗಳು. ಅವು
  `MANAGEMENT_API_KEY_SCOPES` ಹೊರಗಿವೆ. `mcp:connect` ಕೇವಲ
  `/api/mcp/` ನಾನ್-ಲೂಪ್ಬ್ಯಾಕ್ ಕಾರ್ವ್-ಔಟ್ ಅನ್ನು ತೆರೆಯುತ್ತದೆ.

### MCP ಟೂಲ್ ಸ್ಕೋಪ್ಗಳು

ಕ್ಯಾಟಲಾಗ್ ಮತ್ತು ಹೊಂದಾಣಿಕೆಯ ನಿಯಮಗಳು (ಒಂದೇ ಸ್ಟ್ರಿಂಗ್, ಅಥವಾ `*` ನಲ್ಲಿ ಕೊನೆಗೊಳ್ಳುವ ಅನುಮತಿಸಲಾದ ಸ್ಕೋಪ್):
[MCP ಟೂಲ್ ಸ್ಕೋಪ್ಗಳು](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`src/shared/constants/mcpScopes.ts` ನಲ್ಲಿರುವ `MCP_SCOPE_LIST` ಮೂಲ ಟೈಪ್ ಮಾಡಿದ
ಉಪವಿಭಾಗವಾಗಿದೆ, ಆ ಪೂರ್ಣ ಕ್ಯಾಟಲಾಗ್ ಅಲ್ಲ. ಜಾರಿಗೊಳಿಸುವಿಕೆಯು
`open-sse/mcp-server/scopeEnforcement.ts` ನಲ್ಲಿ `resolveCallerScopeContext()`
MCP ದೃಢೀಕರಣ ಮಾಹಿತಿ, ವಿನಂತಿ ಮೆಟಾಡೇಟಾ, ಅಥವಾ `OMNIROUTE_MCP_SCOPES` ನಿಂದ ಸ್ಕೋಪ್ಗಳನ್ನು ಪರಿಹರಿಸಿದ ನಂತರ ನಡೆಯುತ್ತದೆ.
`OMNIROUTE_MCP_ENFORCE_SCOPES=true` ಆಗುವವರೆಗೆ ಇದು ಆಫ್ ಆಗಿರುತ್ತದೆ.

### ಪ್ರವೇಶ-ಟೋಕನ್ ಸ್ಕೋಪ್ಗಳು

`oma_live_…` ಟೋಕನ್ಗಳಲ್ಲಿ `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) ಮೂಲಕ ಶ್ರೇಣೀಕರಿಸಲಾಗಿದೆ. ಈ ಶ್ರೇಣಿಯು ಪ್ರವೇಶ-ಟೋಕನ್
ಪ್ರಮಾಣಪತ್ರಕ್ಕೆ ಮಾತ್ರ ಅನ್ವಯಿಸುತ್ತದೆ. [ನಿರ್ವಹಣಾ ದೃಢೀಕರಣ](../guides/MANAGEMENT-AUTH.md) ನೋಡಿ.

## ದೃಢೀಕರಣ-ಅಗತ್ಯ ಟಾಗಲ್

`src/shared/utils/apiAuth.ts` ನಲ್ಲಿರುವ `isAuthRequired()` ಒಂದು ವಿನಂತಿಗೆ **ಯಾವುದಾದರೂ** ದೃಢೀಕರಣ ಜಾರಿಗೊಳ್ಳಬೇಕೆ ಎಂದು ನಿರ್ಧರಿಸುತ್ತದೆ:

- `settings.requireLogin === false` → ದೃಢೀಕರಣ ಜಾಗತಿಕವಾಗಿ ನಿಷ್ಕ್ರಿಯ, ಆದರೆ ಯಾವಾಗಲೂ-ರಕ್ಷಿತ ಶ್ರೇಣಿ (ನೋಡಿ [ರೂಟ್ ಗಾರ್ಡ್ ಶ್ರೇಣಿಗಳು](../security/ROUTE_GUARD_TIERS.md)) ಮತ್ತು ಅದು ಸ್ವೀಕರಿಸುವ ಕ್ರೆಡೆನ್ಶಿಯಲ್ ನೀಡುವ ಕರೆಗಳ ಹೊರತಾಗಿ — ಇವಕ್ಕೆ ಲಾಗಿನ್ ಆನ್ ಇದ್ದಾಗ ಬೇಕಾದ ಅದೇ ಕ್ರೆಡೆನ್ಶಿಯಲ್ ಬೇಕು: ಸಿಂಕ್ ಟೋಕನ್‌ಗಳನ್ನು ನೀಡುವುದು, ಯಾವುದೇ ಸ್ಕೋಪ್‌ನಲ್ಲಿ CLI ಪ್ರವೇಶ ಟೋಕನ್‌ಗಳನ್ನು ರಚಿಸುವುದು, ಮತ್ತು `manage`/`admin` ಸ್ಕೋಪ್‌ನ API ಕೀಯನ್ನು ರಚಿಸುವುದು, ಆ ಸ್ಕೋಪ್ ಅನ್ನು ಕೀಗೆ ನೀಡುವುದು, ಅಥವಾ ಅಂತಹ ಕೀಯನ್ನು ಮರು-ಉತ್ಪಾದಿಸುವುದು ಅಥವಾ ಬಹಿರಂಗಪಡಿಸುವುದು (`src/lib/api/requireManagementAuth.ts` ನಲ್ಲಿರುವ `requireCredentialForManagementScopedKey()`). ಇನ್‌ಫರೆನ್ಸ್-ಮಾತ್ರ ಕೀಗಳು ತೆರೆದೇ ಉಳಿಯುತ್ತವೆ.
- ಯಾವುದೇ ಪಾಸ್‌ವರ್ಡ್ ಕಾನ್ಫಿಗರ್ ಆಗಿಲ್ಲ **ಮತ್ತು** `INITIAL_PASSWORD` ಎನ್ವಿರಾನ್ಮೆಂಟ್ ವೇರಿಯಬಲ್ ಇಲ್ಲ → ಬೂಟ್‌ಸ್ಟ್ರ್ಯಾಪ್ ಮೋಡ್ ಆನ್‌ಬೋರ್ಡಿಂಗ್ ವಿಝಾರ್ಡ್ ಮತ್ತು ಲೂಪ್‌ಬ್ಯಾಕ್ ವಿನಂತಿಗಳನ್ನು ಅನುಮತಿಸುತ್ತದೆ, ಆದರೆ ಬಹಿರಂಗ ನೆಟ್‌ವರ್ಕ್ ವಿನಂತಿಗಳಿಗೆ ಇನ್ನೂ ಕ್ರೆಡೆನ್ಶಿಯಲ್‌ಗಳು ಬೇಕು.
- ಯಾವುದೇ DB ದೋಷ → ವಿಫಲ-ಮುಚ್ಚು (ಸುರಕ್ಷಿತ-ಡೀಫಾಲ್ಟ್).

ಕ್ಲೈಂಟ್ API ಕೀ ಜಾರಿಯು `src/shared/utils/featureFlags.ts` ನಲ್ಲಿರುವ `isRequireApiKeyEnabled()` ಅನ್ನು ಬಳಸುತ್ತದೆ, ನೇರ `process.env.REQUIRE_API_KEY` ಓದಿಕೆಯನ್ನಲ್ಲ. ಇದು ನಿಯೋಜಿತ ನಿದರ್ಶನಗಳಿಗೆ ಮುಖ್ಯ: ಡ್ಯಾಶ್‌ಬೋರ್ಡ್ → ಫೀಚರ್ ಫ್ಲ್ಯಾಗ್‌ಗಳಲ್ಲಿ `REQUIRE_API_KEY` ಟಾಗಲ್ ಮಾಡಿದರೆ DB ಓವರ್‌ರೈಡ್ ಸಂಗ್ರಹವಾಗುತ್ತದೆ ಮತ್ತು ತಕ್ಷಣ `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ಮತ್ತು ಈ ಸಹಾಯಕವನ್ನು ಹಂಚಿಕೊಳ್ಳುವ ಇತರ ಕ್ಲೈಂಟ್-API ದೃಢೀಕರಣ ಪರಿಶೀಲನೆಗಳ ಮೇಲೆ ಪರಿಣಾಮ ಬೀರುತ್ತದೆ. ಫೀಚರ್ ಫ್ಲ್ಯಾಗ್ ಸಂಗ್ರಹವನ್ನು ಓದಲಾಗದಿದ್ದರೆ ಕ್ಲೈಂಟ್ API ದೃಢೀಕರಣ ವಿಫಲ-ಮುಚ್ಚುತ್ತದೆ ಮತ್ತು ಕೀ ಅಗತ್ಯವಿರುತ್ತದೆ.

## ಹೊಂದಾಣಿಕೆಯನ್ನು ಮುರಿಯುವ ಬದಲಾವಣೆ — v3.8.0

`/api/v1/agents/tasks/*` ಮತ್ತು `/api/resilience/model-cooldowns` ಎಂಡ್ಪಾಯಿಂಟ್ಗಳಿಗೆ **ಈಗ ನಿರ್ವಹಣಾ ದೃಢೀಕರಣ ಅಗತ್ಯವಿದೆ** (ಕಮಿಟ್ `588a0333`). ಈ ಹಿಂದೆ `manage` ಸ್ಕೋಪ್ ಇಲ್ಲದ ಸಾಮಾನ್ಯ API ಕೀಯನ್ನು ಕಳುಹಿಸುತ್ತಿದ್ದ ಕ್ಲೈಂಟ್ಗಳು `403` ಸ್ವೀಕರಿಸುತ್ತವೆ. ಮೈಗ್ರೇಶನ್: API Keys ಡ್ಯಾಶ್ಬೋರ್ಡ್ನಲ್ಲಿ ಕೀಗೆ `manage` ಸ್ಕೋಪ್ ನೀಡಿ, ಅಥವಾ ಲಾಗಿನ್ ಆಗಿರುವ ಡ್ಯಾಶ್ಬೋರ್ಡ್ ಸೆಷನ್ ಬಳಸಿ.

## ವರ್ತನೆಯ ಬದಲಾವಣೆ — v3.8.2

`/api/mcp/*` (ರಿಮೋಟ್ MCP ಸರ್ವರ್) ಇನ್ನೂ ಪೂರ್ವನಿಯೋಜಿತವಾಗಿ LOCAL_ONLY ಆಗಿದೆ, ಆದರೆ `Authorization: Bearer <api-key>` ಹೆಡರ್ `manage` ಸ್ಕೋಪ್ ಹೊಂದಿರುವಾಗ ಈಗ ಲೂಪ್ಬ್ಯಾಕ್ ಅಲ್ಲದ ವಿನಂತಿಗಳನ್ನು ಸ್ವೀಕರಿಸುತ್ತದೆ. ಈ ವಿನಾಯಿತಿಯನ್ನು `src/server/authz/routeGuard.ts` ನಲ್ಲಿನ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ಮೂಲಕ ಪ್ರತಿ ಪಾಥ್ಗೆ ಸ್ಪಷ್ಟವಾಗಿ ನಿಯಂತ್ರಿಸಲಾಗಿದೆ; ಸಮಾನ ಮಟ್ಟದ LOCAL_ONLY ಪ್ರಿಫಿಕ್ಸ್ `/api/cli-tools/runtime/*` ಅನಿಯಂತ್ರಿತ ಉಪಪ್ರಕ್ರಿಯೆಗಳನ್ನು ಪ್ರಾರಂಭಿಸಬಹುದಾದ ಕಾರಣ ಅದನ್ನು ಉದ್ದೇಶಪೂರ್ವಕವಾಗಿ ಬೈಪಾಸ್ ಮಾಡಲು ಸಾಧ್ಯವಿಲ್ಲ. ಲೂಪ್ಬ್ಯಾಕ್ ಅಲ್ಲದ ಮೂಲಗಳಿಂದ `/api/mcp/*` ಗೆ ಬರುವ ಅನಾಮಧೇಯ ವಿನಂತಿಗಳು `403 LOCAL_ONLY` ಅನ್ನು ಮರಳಿಸುವುದನ್ನು ಮುಂದುವರಿಸುತ್ತವೆ — ಯಾವುದೇ ಹೊಸ LOCAL_ONLY ಪಾಥ್ನ ಪೂರ್ವನಿಯೋಜಿತ ವರ್ತನೆಯು ಕಟ್ಟುನಿಟ್ಟಾದ ಲೂಪ್ಬ್ಯಾಕ್ ಆಗಿಯೇ ಉಳಿಯುತ್ತದೆ. [ರೂಟ್ ಗಾರ್ಡ್ ಹಂತಗಳು](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) ನೋಡಿ.

## ಪರೀಕ್ಷೆ

- ಯೂನಿಟ್ ಪರೀಕ್ಷೆಗಳು: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- ಸಾರ್ವಜನಿಕ ಅನುಮತಿ ಪಟ್ಟಿ: `tests/unit/public-api-routes.test.ts`.
- ಕೇಂದ್ರೀಕೃತವಾಗಿ ಚಲಾಯಿಸಲು: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## ಡೀಬಗ್ ಮಾಡಲಾಗುತ್ತಿದೆ

ಪೈಪ್ಲೈನ್ ಯಾವಾಗಲೂ ಇದರೊಂದಿಗೆ ಪ್ರತಿಕ್ರಿಯೆಗಳನ್ನು ಮುದ್ರೆ ಮಾಡುತ್ತದೆ:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

ದೃಢೀಕೃತ ವಿನಂತಿಗಳಿಗಾಗಿ ಅಪ್ಸ್ಟ್ರೀಮ್ (ಹ್ಯಾಂಡ್ಲರ್-ಸೈಡ್) ವಿನಂತಿ ಹೆಡರ್ಗಳು ಸಹ ಸೇರಿವೆ:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ಹ್ಯಾಂಡ್ಲರ್ಗಳ ಒಳಗೆ `assertAuth(req, expectedClass)` ಬಳಸಿ — ಇದು ಮಿಡಲ್ವೇರ್ ಅನ್ನು ಬೈಪಾಸ್ ಮಾಡಿದರೆ ಕೋಡ್ `AUTHZ_NOT_INITIALIZED` ಜೊತೆಗೆ `AuthzAssertionError` ಎಸೆಯುತ್ತದೆ (ಪರೀಕ್ಷೆಗಳಲ್ಲಿ ಕಾನ್ಫಿಗರೇಶನ್ ರಿಗ್ರೆಷನ್ಗಳನ್ನು ಹಿಡಿಯಲು ಸಹಾಯಕವಾಗಿದೆ).

## ಸಹ ನೋಡಿ

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ಪ್ರತಿ ಎಂಡ್ಪಾಯಿಂಟ್ಗೆ ದೃಢೀಕರಣ ಮಾರ್ಕರ್
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ದೃಢೀಕರಣ ಘಟನೆಗಳಿಗಾಗಿ ಆಡಿಟ್ ಲಾಗ್
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ಮೂರು ಸ್ಕೋಪ್ ನೇಮ್ಸ್ಪೇಸ್ಗಳು ಮತ್ತು MCP ಟೂಲ್-ಸ್ಕೋಪ್ ಕ್ಯಾಟಲಾಗ್
- ಮೂಲ: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
