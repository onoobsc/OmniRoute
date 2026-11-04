# Authorization Guide (ਪੰਜਾਬੀ)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **ਸੱਚ ਦਾ ਸਰੋਤ:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **ਆਖਰੀ ਵਾਰ ਅੱਪਡੇਟ ਕੀਤਾ ਗਿਆ:** 2026-09-22 — ਸਕੋਪ ਨੇਮਸਪੇਸ MCP-SERVER.md ਵੱਲ ਇਸ਼ਾਰਾ ਕਰਦੇ ਹਨ

OmniRoute ਕੋਲ ਇੱਕ ਰੂਟ-ਜਾਣੂ ਅਧਿਕਾਰ ਪਾਈਪਲਾਈਨ ਹੈ ਜੋ ਹਰ API ਬੇਨਤੀ ਨੂੰ ਗੇਟ ਕਰਦੀ ਹੈ। ਵਰਗੀਕਰਨ **ਨਿਰਧਾਰਤ** ਅਤੇ **ਫੇਲ-ਕਲੋਜ਼ਡ** ਹੈ — ਕੋਈ ਵੀ ਚੀਜ਼ ਜਿਸਨੂੰ ਵਰਗੀਕ੍ਰਿਤ ਨਹੀਂ ਕੀਤਾ ਜਾ ਸਕਦਾ, ਉਹ `MANAGEMENT` ਦੇ ਰੂਪ ਵਿੱਚ ਖਤਮ ਹੁੰਦੀ ਹੈ ਅਤੇ ਇੱਕ ਸੈਸ਼ਨ ਜਾਂ ਪ੍ਰਬੰਧਨ-ਗ੍ਰੇਡ ਟੋਕਨ ਦੀ ਮੰਗ ਕਰਦੀ ਹੈ। ਇਹ ਪੰਨਾ ਰੂਟਾਂ ਨੂੰ ਬਣਾਈ ਰੱਖਣ ਵਾਲੇ ਜਾਂ ਨਵੇਂ ਐਂਡਪੁਆਇੰਟ ਡਿਜ਼ਾਈਨ ਕਰਨ ਵਾਲੇ ਇੰਜੀਨੀਅਰਾਂ ਲਈ ਮਾਡਲ ਦੀ ਵਿਆਖਿਆ ਕਰਦਾ ਹੈ।

![AuthZ ਪਾਈਪਲਾਈਨ (3 ਰੂਟ ਕਲਾਸਾਂ + ਨੀਤੀ ਮੁਲਾਂਕਣ)](../diagrams/exported/authz-pipeline.svg)

> ਸਰੋਤ: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## ਦੋ ਪ੍ਰਮਾਣਿਕਤਾ ਮੋਡ

### 1. API ਕੁੰਜੀ (ਧਾਰਕ)

OpenAI/Anthropic/Gemini-compatible ਕਲਾਇੰਟ APIs ਅਤੇ ਕੁਝ ਪ੍ਰਬੰਧਨ ਰੂਟਾਂ ਲਈ ਵਰਤਿਆ ਜਾਂਦਾ ਹੈ ਜਦੋਂ ਕੁੰਜੀ ਵਿੱਚ `manage` ਸਕੋਪ ਹੁੰਦਾ ਹੈ।

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` ਵਿੱਚ `isValidApiKey()` / `extractApiKey()` ਦੁਆਰਾ ਪ੍ਰਮਾਣਿਤ ਅਤੇ `src/shared/utils/apiAuth.ts` ਦੁਆਰਾ ਮੁੜ-ਨਿਰਯਾਤ ਕੀਤਾ ਗਿਆ। ਵੈਲੀਡੇਟਰ `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ਨੂੰ ਸਥਾਈ ਪਾਸਥਰੂ ਕੁੰਜੀਆਂ ਦੇ ਤੌਰ 'ਤੇ ਸਵੀਕਾਰ ਕਰਦਾ ਹੈ (ਮਸਲਾ #1350)।

### 2. ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ (auth_token ਕੂਕੀ)

ਡੈਸ਼ਬੋਰਡ ਪੰਨਿਆਂ ਅਤੇ ਐਡਮਿਨ ਓਪਰੇਸ਼ਨਾਂ ਲਈ।

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

ਇੱਕ ਕੂਕੀ ਇੱਕ ਸੈਸ਼ਨ ਹੁੰਦਾ ਹੈ ਜਦੋਂ JWT ਪੁਸ਼ਟੀ ਕਰਦਾ ਹੈ** ਅਤੇ** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) ਰੱਖਦਾ ਹੈ। ਕੂਕੀ (ਡੈਸ਼ਬੋਰਡ ਰੂਟ ਗਾਰਡ (`isDashboardSessionAuthenticated()`), authz ਪਾਈਪਲਾਈਨ ਰਿਫਰੈਸ਼, WebSocket ਹੈਂਡਸ਼ੇਕ, ਲਾਈਵ ਸਰਵਰ, `/api/settings/require-login`, `/api/auth/status`) ਦਾ ਹਰ ਉਪਭੋਗਤਾ ਉਸ ਸਹਾਇਕ ਦੁਆਰਾ ਜਾਂਦਾ ਹੈ। `JWT_SECRET` ਨਾਲ ਹਸਤਾਖਰ ਕੀਤੇ ਹੋਰ JWTs ਮੌਜੂਦ ਹਨ — Cursor CLI ਪਾਸਥਰੂ ਕੁੰਜੀ ਧਾਰਕਾਂ — ਲਈ `iss "omniroute" / aud "cursor-cli"` ਟੋਕਨ ਹਨ ਅਤੇ ਕਦੇ ਵੀ ਸੈਸ਼ਨ ਨਹੀਂ ਹੁੰਦੇ (#13298)।

`src/shared/utils/apiAuth.ts` ਵਿੱਚ `isDashboardSessionAuthenticated()` ਦੁਆਰਾ ਪੁਸ਼ਟੀ ਕੀਤੀ ਗਈ। ਪਾਈਪਲਾਈਨ JWT ਨੂੰ ਸਵੈ-ਤਾਜ਼ਾ ਕਰਦੀ ਹੈ ਜਦੋਂ ਇਸਦੇ 30-ਦਿਨਾਂ ਦੇ ਜੀਵਨ ਕਾਲ ਵਿੱਚ 7 ਦਿਨ ਤੋਂ ਘੱਟ ਬਚੇ ਹੁੰਦੇ ਹਨ।

ਇੱਕ ਸੈਸ਼ਨ ਇਸਦੇ 30 ਦਿਨ ਖਤਮ ਹੋਣ ਤੋਂ ਪਹਿਲਾਂ ਵੀ ਖਤਮ ਹੋ ਸਕਦਾ ਹੈ, ਕਿਉਂਕਿ ਹਰ ਮਿੰਟ `mintDashboardSessionToken` (ਇੱਕ ਮੁੱਦੇ ਦਾ ਸਮਾਂ `iat` ਅਤੇ ਇੱਕ id `jti`) ਵਿੱਚੋਂ ਲੰਘਦਾ ਹੈ ਅਤੇ ਤਸਦੀਕ ਕਰਨ ਵਾਲਾ ਦੋ ਸੈਟਿੰਗਾਂ ਦੀ ਜਾਂਚ ਕਰਦਾ ਹੈ: `sessionsValidAfter`, ਇੱਕ ਪਾਸਵਰਡ ਤਬਦੀਲੀ ਦੁਆਰਾ ਸੈੱਟ ਕੀਤਾ ਗਿਆ ਹੈ ਤਾਂ ਜੋ ਹਰ ਸ਼ੈਸ਼ਨ ਨੂੰ ਪ੍ਰਮਾਣਿਤ ਕਰਨਾ ਬੰਦ ਕਰਨ ਤੋਂ ਪਹਿਲਾਂ ਜਾਰੀ ਕੀਤਾ ਜਾਵੇ (ਪਾਸਵਰਡ ਬਦਲਣ ਵਾਲੇ ਬ੍ਰਾਊਜ਼ਰ ਨੂੰ ਇੱਕ ਤਾਜ਼ਾ ਕੂਕੀ ਮਿਲਦੀ ਹੈ `POST /api/auth/logout`, ਅਤੇ `revokedDashboardSessions`' ਸੈਸ਼ਨ ਨੂੰ ਸਾਈਨ ਆਊਟ ਕਰਨ ਲਈ `jti` ਪੁਰਾਣੇ ਰੀਲੀਜ਼ ਦੁਆਰਾ ਬਣਾਏ ਗਏ ਸੈਸ਼ਨਾਂ ਵਿੱਚ ਕੋਈ ਦਾਅਵਾ ਨਹੀਂ ਹੁੰਦਾ ਹੈ ਅਤੇ ਪਹਿਲੇ ਪਾਸਵਰਡ ਵਿੱਚ ਤਬਦੀਲੀ ਹੋਣ ਤੱਕ ਵੈਧ ਰਹਿੰਦੇ ਹਨ। ਜੇਕਰ ਸੈਟਿੰਗਾਂ ਨੂੰ ਪੜ੍ਹਿਆ ਨਹੀਂ ਜਾ ਸਕਦਾ ਹੈ, ਤਾਂ ਸੈਸ਼ਨ ਭਰੋਸੇਯੋਗ ਨਹੀਂ ਹੈ।

ਕੁਝ ਪ੍ਰਬੰਧਨ ਰੂਟ ਸਵੀਕਾਰ ਕਰਦੇ ਹਨ** ਜਾਂ ਤਾਂ** ਮੋਡ: ਕੂਕੀ OR `Bearer <key>` ਜਦੋਂ API ਕੁੰਜੀ ਵਿੱਚ `manage` (ਜਾਂ `admin`) ਸਕੋਪ ਹੋਵੇ। ਇਹ ਉਹ ਹੈ ਜੋ v3.8 ਵਿੱਚ ਸ਼ਾਮਲ ਕੀਤੇ ਗਏ " API ਕਾਲਾਂ ਰਾਹੀਂ ਸੰਰਚਨਾਯੋਗ" ਵਰਕਫਲੋ ਨੂੰ ਸਮਰੱਥ ਬਣਾਉਂਦਾ ਹੈ।

#### ਵਿਕਲਪਿਕ OIDC ਲਾਗਇਨ ਗੇਟ (#6973)

ਡੈਸ਼ਬੋਰਡ ਐਡਮਿਨ ਲੌਗਇਨ ਵੀ ਇੱਕ ਦਾ ਸਮਰਥਨ ਕਰਦਾ ਹੈ** ਚੋਣ ਕਰੋ** ਡਿਫੌਲਟ ਪਾਸਵਰਡ ਲੌਗਇਨ ਦੇ ਨਾਲ OIDC (OpenID ਕਨੈਕਟ) ਦਾ ਪ੍ਰਵਾਹ — ਪਾਸਵਰਡ ਲੌਗਇਨ ਕਦੇ ਵੀ ਨਹੀਂ ਹਟਾਇਆ ਜਾਂਦਾ, ਸਿਰਫ ਪੂਰਕ:

- `settings.oidcEnabled === true` ਤੱਕ ਅਯੋਗ ਹੈ** ਅਤੇ** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` ਸਭ ਕੌਂਫਿਗਰ ਕੀਤੇ ਗਏ ਹਨ (ਸੈਟਿੰਗਜ਼ → Auth)। `GET /api/auth/oidc/login` ਨਹੀਂ ਤਾਂ `400` ਵਾਪਸ ਕਰਦਾ ਹੈ।
- `GET /api/auth/oidc/login` ਜਾਰੀਕਰਤਾ ਦੇ `/.well-known/openid-configuration` ਤੋਂ `authorization_endpoint` ਦੀ ਖੋਜ ਕਰਦਾ ਹੈ ( `<issuer>/authorize` ਤੇ ਵਾਪਸ ਆਉਂਦਾ ਹੈ), ਆਉਣ ਵਾਲੀ ਬੇਨਤੀ (`x-forwarded-proto` -aware) ਤੋਂ ਰੀਡਾਇਰੈਕਟ URI ਬਣਾਉਂਦਾ ਹੈ, ਅਤੇ `httpOnly` `oidc_state` ਕੂਕੀ ਵਿੱਚ ਸਟੋਰ ਕੀਤੇ ਇੱਕ ਬੇਤਰਤੀਬ `state` ਨਾਲ IdP ਨੂੰ ਰੀਡਾਇਰੈਕਟ ਕਰਦਾ ਹੈ।
- `GET /api/auth/oidc/callback` `state` ਪ੍ਰਮਾਣਿਤ ਕਰਦਾ ਹੈ, ਪ੍ਰਮਾਣੀਕਰਨ ਕੋਡ ਦਾ ਆਦਾਨ-ਪ੍ਰਦਾਨ ਕਰਦਾ ਹੈ, ਅਤੇ `issuer`/`audience` ਜਾਂਚਾਂ ਦੇ ਨਾਲ ਜਾਰੀਕਰਤਾ ਦੇ JWKS (`jose`'s `createRemoteJWKSet`, ਕੈਸ਼ਡ ਪ੍ਰਤੀ JWKS URI) ਰਾਹੀਂ ID ਟੋਕਨ ਦੇ ਦਸਤਖਤ ਦੀ ਪੁਸ਼ਟੀ ਕਰਦਾ ਹੈ। ਡੈਸ਼ਬੋਰਡ ਦਾਖਲੇ ਲਈ ਬਿਨਾਂ ਖਾਲੀ `oidcAllowedSubjects` ਸੂਚੀ, ਇੱਕ `oidcAdmissionClaim` ਨੀਤੀ, ਜਾਂ ਦੋਵਾਂ ਦੀ ਲੋੜ ਹੁੰਦੀ ਹੈ। ਵਿਸ਼ਾ ਸੂਚੀ `sub` ਜਾਂ `email` ਨਾਲ ਮੇਲ ਖਾਂਦੀ ਹੈ ਜਦੋਂ `email_verified === true`. ਵਿਕਲਪਿਕ ਦਾਅਵਾ ਨੀਤੀ ਇੱਕ ਬਿੰਦੂ-ਵੱਖ ID-ਟੋਕਨ ਦਾਅਵਾ ਮਾਰਗ (ਉਦਾਹਰਨ ਲਈ, `realm_access.roles`) ਅਤੇ ਸਵੀਕਾਰ ਕੀਤੇ ਮੁੱਲਾਂ ਦੀ ਇੱਕ ਲੜੀ ਲੈਂਦੀ ਹੈ; ਹੱਲ ਕੀਤਾ ਦਾਅਵਾ ਘੱਟੋ-ਘੱਟ ਇੱਕ ਸਵੀਕਾਰ ਮੁੱਲ ਵਾਲੀ ਸਤਰ ਦੀ ਇੱਕ ਲੜੀ ਹੋਣੀ ਚਾਹੀਦੀ ਹੈ। ਜੇਕਰ ਦੋਵੇਂ ਨੀਤੀਆਂ ਕੌਂਫਿਗਰ ਕੀਤੀਆਂ ਗਈਆਂ ਹਨ, ਤਾਂ ਦੋਵਾਂ ਦਾ ਪਾਸ ਹੋਣਾ ਲਾਜ਼ਮੀ ਹੈ। Missing/malformed ਦਾਅਵੇ ਫੇਲ ਬੰਦ ਹੋ ਜਾਂਦੇ ਹਨ, ਅਤੇ ਬਿਨਾਂ ਕਿਸੇ ਨੀਤੀ ਦੇ ਕਾਲਬੈਕ ਲੌਗਇਨ (`not_configured`) ਤੋਂ ਇਨਕਾਰ ਕਰਦਾ ਹੈ। ਮੌਜੂਦਾ ਵਿਸ਼ੇ-ਸਿਰਫ਼ ਸੰਰਚਨਾਵਾਂ ਬਿਨਾਂ ਬਦਲੇ ਜਾਰੀ ਰਹਿੰਦੀਆਂ ਹਨ।
- ਕੀਕਲੌਕ ਆਮ ਤੌਰ 'ਤੇ ਐਕਸੈਸ ਟੋਕਨਾਂ ਵਿੱਚ ਖੇਤਰ ਦੀਆਂ ਭੂਮਿਕਾਵਾਂ ਨੂੰ ਮੈਪ ਕਰਦਾ ਹੈ, ਜ਼ਰੂਰੀ ਨਹੀਂ ID ਟੋਕਨਾਂ. ਰੀਅਲਮ ਰੋਲ `admin` ਦੀ ਲੋੜ ਲਈ, ਇਸ ਕਲਾਇੰਟ ਲਈ ਇੱਕ ਪ੍ਰੋਟੋਕੋਲ ਮੈਪਰ ਕੌਂਫਿਗਰ ਕਰੋ ਜਿਸ ਵਿੱਚ `realm_access.roles` ਸ਼ਾਮਲ ਹੈ**ID ਟੋਕਨ** , ਫਿਰ `oidcAdmissionClaim` ਨੂੰ `{ "path": "realm_access.roles", "values": ["admin"] }` ਤੇ ਸੈੱਟ ਕਰੋ। ਰੋਲ-ਓਨਲੀ ਦਾਖਲੇ ਨੂੰ ਸਮਰੱਥ ਕਰਨ ਤੋਂ ਪਹਿਲਾਂ ਇਸ ਕਲਾਇੰਟ ਲਈ ਅਸਲ ID-ਟੋਕਨ ਦਾਅਵੇ ਦੀ ਜਾਂਚ ਕਰੋ; ਐਪਲੀਕੇਸ਼ਨ ਐਕਸੈਸ-ਟੋਕਨ ਰੋਲ ਨੂੰ ਨਹੀਂ ਪੜ੍ਹਦੀ ਹੈ। ਆਈਡੀਪੀ-ਸਾਈਡ ਟੋਕਨ ਇਨਕਾਰ ਪੂਰਕ ਹੋ ਸਕਦਾ ਹੈ ਪਰ ਇਸ ਐਪਲੀਕੇਸ਼ਨ-ਸਾਈਡ ਜਾਂਚ ਨੂੰ ਨਹੀਂ ਬਦਲਦਾ।
- ਸਫਲਤਾ 'ਤੇ ਇਸ ਨੂੰ mints** ਬਿਲਕੁਲ ਉਸੇ ਤਰ੍ਹਾਂ** 30-ਦਿਨ `auth_token` JWT ਪਾਸਵਰਡ ਲੌਗਇਨ ਮੁੱਦੇ (`src/app/api/auth/login/route.ts`), ਇਸਲਈ ਬਾਕੀ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਪਾਈਪਲਾਈਨ (ਆਟੋ-ਰਿਫਰੈਸ਼, ਕੂਕੀ ਫਲੈਗ) ਨਾ ਬਦਲੀ ਗਈ — OIDC ਸਿਰਫ ਇਸ ਗੱਲ ਨੂੰ ਬਦਲਦੀ ਹੈ ਕਿ ਕੂਕੀ ਨੂੰ ਕਿਵੇਂ ਮਿਨਟ ਕੀਤਾ ਜਾਂਦਾ ਹੈ, ਨਾ ਕਿ ਇਹ ਕੀ ਦਿੰਦਾ ਹੈ। IdP roles/groups ਵਿੱਚ ਤਬਦੀਲੀਆਂ ਮੌਜੂਦਾ OmniRoute ਸੈਸ਼ਨਾਂ ਨੂੰ ਅਯੋਗ ਨਹੀਂ ਕਰਦੀਆਂ; ਲੌਗਆਉਟ, ਪਾਸਵਰਡ ਰੋਟੇਸ਼ਨ, ਜਾਂ ਸੈਸ਼ਨ ਦੀ ਮਿਆਦ ਅਜੇ ਵੀ ਉਹਨਾਂ ਦੇ ਜੀਵਨ ਕਾਲ ਨੂੰ ਨਿਯੰਤਰਿਤ ਕਰਦੀ ਹੈ।
- ਹਰ `oidc*` ਸੈਟਿੰਗ (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) ਵਿੱਚ ਹੈ : `PATCH /api/settings` ਜਵਾਬ `400 PASSWORD_REQUIRED` ਦਿੰਦਾ ਹੈ ਜਦੋਂ ਤੱਕ ਬਾਡੀ ਪ੍ਰਬੰਧਨ ਪਾਸਵਰਡ ਨਹੀਂ ਲੈਂਦੀ ( `currentPassword` ਦੇ ਤੌਰ 'ਤੇ ਇਹ ਗਲਤ ਹੈ)`401 PASSWORD_MISMATCH` `oidcDisablePasswordLogin` ਪਾਸਵਰਡ _login_ (`POST /api/auth/login`) ਤੋਂ ਇਨਕਾਰ ਕਰਦਾ ਹੈ ਪਰ ਸਟੋਰ ਕੀਤੇ ਪਾਸਵਰਡ ਹੈਸ਼ ਨੂੰ ਰੱਖਦਾ ਹੈ, ਅਤੇ ਮੁੜ-ਪ੍ਰਮਾਣੀਕਰਨ ਅਜੇ ਵੀ ਇਸਦੇ ਵਿਰੁੱਧ `currentPassword` ਜਾਂਚ ਕਰਦਾ ਹੈ।
- `corsOrigins` ਅਤੇ `bruteForceProtection` ਵੀ `SECURITY_IMPACTING_SETTINGS_KEYS` ਵਿੱਚ ਹਨ: ਢਿੱਲਾ ਕਰਨ ਨਾਲ ਜਾਂ ਤਾਂ ਲੌਗਇਨ ਸੁਰੱਖਿਆ ਕਮਜ਼ੋਰ ਹੋ ਜਾਂਦੀ ਹੈ, ਇਸਲਈ ਉਹ ਉਹੀ `currentPassword` ਰੀ-ਅਥ ਲੈਂਦੇ ਹਨ (ਸੁਰੱਖਿਆ ਟੈਬ ਇਸ ਲਈ ਪੁੱਛਦੀ ਹੈ) ਅਤੇ JSON ਆਯਾਤ ਉਹਨਾਂ ਨੂੰ ਛੱਡ ਦਿੰਦਾ ਹੈ।
- ਹਰ ਸੁਰੱਖਿਆ-ਨੀਤੀ ਕੁੰਜੀ — `SECURITY_IMPACTING_SETTINGS_KEYS` ਐਂਟਰੀਆਂ, ਹਰ `oidc*` ਕੁੰਜੀ ਅਤੇ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਦੀ ਸਥਿਤੀ — ਹੈ** ਓਪਰੇਟਰ-ਸਿਰਫ਼** `PATCH /api/settings`'ਤੇ: ਇੱਕ ਪ੍ਰਬੰਧਨ-ਸਕੋਪਡ API ਕੁੰਜੀ ਜਾਂ ਇੱਕ `oma_` ਐਕਸੈਸ ਟੋਕਨ ਨੂੰ `403` ਨਾਲ ਇਨਕਾਰ ਕਰ ਦਿੱਤਾ ਜਾਂਦਾ ਹੈ ਭਾਵੇਂ ਇਹ ਸਹੀ `currentPassword` ਭੇਜਦਾ ਹੈ, ਅਤੇ ਇਨਕਾਰ ਨੂੰ `reason: OPERATOR_REQUIRED` ( `src/lib/api/operatorCredential.ts` ਵਿੱਚ `requireOperatorCredential()` ) ਨਾਲ `settings.update_failed` ਵਜੋਂ ਆਡਿਟ ਕੀਤਾ ਜਾਂਦਾ ਹੈ। ਆਮ ਸੈਟਿੰਗਾਂ (ਥੀਮ, ਡਿਸਪਲੇ ਤਰਜੀਹਾਂ) ਇੱਕ `manage` ਕੁੰਜੀ ਜਾਂ ਇੱਕ `admin` ਐਕਸੈਸ ਟੋਕਨ ਲਈ ਲਿਖਣਯੋਗ ਰਹਿੰਦੀਆਂ ਹਨ। `/api/settings` ਦੇ ਹਰੇਕ ਮਿਊਟੇਸ਼ਨ (ਅਤੇ `/api/settings/require-login` ਦੇ) ਨੂੰ ਵੀ `admin` ਐਕਸੈਸ-ਟੋਕਨ ਸਕੋਪ ( `src/server/authz/accessScopes.ts` ਵਿੱਚ `ADMIN_MUTATION_EXACT_PATHS`, ਸਹੀ-ਪਾਥ ਮੈਚ) ਦੀ ਲੋੜ ਹੁੰਦੀ ਹੈ; `GET` `read` ਰਹਿੰਦਾ ਹੈ, ਅਤੇ ਹੋਰ `/api/settings/*` ਉਪ-ਰੂਟ (ਪ੍ਰੌਕਸੀਜ਼, ਕੰਬੋ ਡਿਫਾਲਟ, ਮਾਡਲ ਉਪਨਾਮ, ਕੰਪਰੈਸ਼ਨ, ਪਰਜਸ...) ਵਿਧੀ-ਅੰਦਾਜ਼ਾ `write` ਸਕੋਪ ਨੂੰ ਰੱਖਦੇ ਹਨ।
- `POST /api/settings/import-json` ਉਸ ਮੁੜ-ਪ੍ਰਮਾਣ ਨੂੰ ਛੱਡ ਦਿੰਦਾ ਹੈ, ਇਸਲਈ ਇਹ ਲਿਖਣ ਤੋਂ ਪਹਿਲਾਂ `IMPORT_STRIPPED_SETTINGS_KEYS` (ਇੱਕੋ ਫਾਈਲ) ਵਿੱਚ ਹਰੇਕ ਕੁੰਜੀ ਨੂੰ ਛੱਡ ਦਿੰਦਾ ਹੈ: ਪਾਸਵਰਡ ਅਤੇ `currentPassword`, ਹਰ `SECURITY_IMPACTING_SETTINGS_KEYS` ਐਂਟਰੀ, ਅਤੇ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਸਥਿਤੀ (`sessionsValidAfter`, `revokedDashboardSessions`)। ਇਸ ਲਈ ਇੱਕ ਪੁਰਾਣੇ ਬੈਕਅੱਪ ਨੂੰ ਆਯਾਤ ਕਰਨਾ ਇੱਕ ਸੈਸ਼ਨ ਨੂੰ ਮੁੜ ਸੁਰਜੀਤ ਨਹੀਂ ਕਰ ਸਕਦਾ ਹੈ ਜਿਸ ਵਿੱਚ ਇੱਕ ਪਾਸਵਰਡ ਤਬਦੀਲੀ ਜਾਂ ਸਾਈਨ-ਆਊਟ ਪਹਿਲਾਂ ਹੀ ਖਤਮ ਹੋ ਗਿਆ ਹੈ।

#### ਵਿਕਲਪਿਕ TOTP ਦੋ-ਕਾਰਕ ਲੌਗਇਨ (#16619)

ਸੈਟਿੰਗਾਂ → ਸੁਰੱਖਿਆ ਤੋਂ ਦਾਖਲਾ; ਜਦੋਂ ਤੱਕ ਓਪਰੇਟਰ ਇਸਨੂੰ ਚਾਲੂ ਨਹੀਂ ਕਰਦਾ (`src/server/auth/dashboardMfa.ts`) ਬੰਦ ਕਰੋ।

- **ਇਹ ਕੀ ਕਵਰ ਕਰਦਾ ਹੈ:** ਪਾਸਵਰਡ ਲੌਗਇਨ (`POST /api/auth/login`, ਜਿਸਨੂੰ ਫਿਰ `POST /api/auth/mfa/verify` ਲੋੜ ਹੁੰਦੀ ਹੈ ) ਅਤੇ `omniroute connect` (`POST /api/cli/connect`, ਜੋ ਕਿ ਇੱਕ ਪਾਸਵਰਡ-ਸਿਰਫ਼ ਐਕਸਚੇਂਜ ਤੋਂ ਇਨਕਾਰ ਕਰਦਾ ਹੈ ਅਤੇ ਕੋਡ ਨੂੰ `totp` ਵਜੋਂ ਲੈਂਦਾ ਹੈ)।
- **ਇਹ ਕੀ ਕਵਰ ਨਹੀਂ ਕਰਦਾ:** OIDC / SSO ਸਾਈਨ-ਇਨ (`/api/auth/oidc/callback`) OmniRoute TOTP ਦੀ ਮੰਗ ਨਹੀਂ ਕਰਦਾ ਹੈ। ਇਹ ਪਛਾਣ ਪ੍ਰਦਾਤਾ ਦੇ ਆਪਣੇ ਦੂਜੇ ਕਾਰਕ 'ਤੇ ਨਿਰਭਰ ਕਰਦਾ ਹੈ, ਇਸ ਲਈ IdP ਵਿੱਚ MFA ਲਾਗੂ ਕਰੋ ਜੇਕਰ OIDC ਸਮਰਥਿਤ ਹੈ।
- **ਰਿਕਵਰੀ** (ਗੁੰਮ ਹੋਈ ਡਿਵਾਈਸ, ਕੋਈ ਰਿਕਵਰੀ ਕੋਡ ਨਹੀਂ ਬਚਿਆ, ਜਾਂ ਕੋਈ ਅਜਿਹਾ ਕਾਰਕ ਜਿਸਦੀ ਹੁਣ ਪੁਸ਼ਟੀ ਨਹੀਂ ਕੀਤੀ ਜਾ ਸਕਦੀ, ਉਦਾਹਰਨ ਲਈ `STORAGE_ENCRYPTION_KEY` ਬਦਲਣ ਤੋਂ ਬਾਅਦ):
  1. ਸਰਵਰ ਨੂੰ `OMNIROUTE_DISABLE_MFA=true` ਨਾਲ ਰੀਸਟਾਰਟ ਕਰੋ।
  2. ਹੋਸਟ 'ਤੇ ਹੀ (ਲੂਪਬੈਕ ਪੀਅਰ ਅਤੇ ਲੂਪਬੈਕ `Host`, ਜਿਵੇਂ ਕਿ `http://localhost:20128`), ਪਾਸਵਰਡ ਨਾਲ ਸਾਈਨ ਇਨ ਕਰੋ। ਦੂਜਾ ਕਾਰਕ ਸਿਰਫ ਉਸ ਮੂਲ ਲਈ ਛੱਡਿਆ ਗਿਆ ਹੈ; ਹਰ ਦੂਜੇ ਮੂਲ ਨੂੰ ਅਜੇ ਵੀ ਕੋਡ ਦੀ ਲੋੜ ਹੈ।
  3. ਸੈਟਿੰਗਾਂ ਵਿੱਚ → ਸੁਰੱਖਿਆ → ਅਯੋਗ ਕਰੋ, ਪਾਸਵਰਡ ਦਰਜ ਕਰੋ ਅਤੇ ਕੋਡ ਨੂੰ ਖਾਲੀ ਛੱਡੋ। `POST /api/auth/mfa/disable` ਬਿਨਾਂ `code` ਸਰੀਰ ਨੂੰ ਸਵੀਕਾਰ ਕਰਦਾ ਹੈ ਜਦੋਂ ਵੇਰੀਏਬਲ ਸੈੱਟ ਹੁੰਦਾ ਹੈ ਅਤੇ ਬੇਨਤੀ ਹੋਸਟ ਤੋਂ ਆਉਂਦੀ ਹੈ; ਇਸ ਨੂੰ ਅਜੇ ਵੀ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਅਤੇ ਮੌਜੂਦਾ ਪਾਸਵਰਡ ਦੀ ਲੋੜ ਹੈ, ਅਤੇ `secondFactor: "recovery_switch"` ਨਾਲ `auth.mfa.disabled` ਵਜੋਂ ਆਡਿਟ ਕੀਤਾ ਜਾਂਦਾ ਹੈ।
  4. `OMNIROUTE_DISABLE_MFA` ਨੂੰ ਅਣਸੈੱਟ ਕਰੋ, ਮੁੜ ਚਾਲੂ ਕਰੋ, ਅਤੇ ਲੋੜ ਪੈਣ 'ਤੇ ਦੁਬਾਰਾ ਦਾਖਲਾ ਕਰੋ।

## ਰੂਟ ਕਲਾਸਾਂ

`src/server/authz/types.ts` ਤਿੰਨ ਕਲਾਸਾਂ ਪਰਿਭਾਸ਼ਿਤ ਕਰਦਾ ਹੈ; ਕੋਈ ਵੀ ਰੂਟ ਜਿਸਨੂੰ ਨਿਰਣਾਇਕ ਤੌਰ 'ਤੇ ਵਰਗੀਕ੍ਰਿਤ ਨਾ ਕੀਤਾ ਜਾ ਸਕੇ, `MANAGEMENT` 'ਤੇ ਡਿੱਗ ਜਾਂਦਾ ਹੈ।

| ਕਲਾਸ         | ਵੇਰਵਾ                                                                                                                                        | ਲੋੜੀਂਦਾ ਪ੍ਰਮਾਣੀਕਰਨ                                              |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| `PUBLIC`     | ਸਪੱਸ਼ਟ ਤੌਰ 'ਤੇ ਸੁਰੱਖਿਅਤ ਰੂਟ — ਲੌਗਇਨ, ਲੌਗਆਉਟ, ਸਥਿਤੀ, ਸ਼ੁਰੂਆਤ, ਹੈਲਥ, ਔਨਬੋਰਡਿੰਗ ਬੂਟਸਟ੍ਰੈਪ।                                                      | ਕੋਈ ਨਹੀਂ                                                        |
| `CLIENT_API` | ਮਾਡਲ-ਸੇਵਾ ਐਂਡਪੌਇੰਟ — `/api/v1/*`, `/api/v1beta/*`, ਅਤੇ ਉਪਨਾਮ `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`। | Bearer ਕੁੰਜੀ ਜਦੋਂ ਪ੍ਰਭਾਵੀ `REQUIRE_API_KEY` ਫੀਚਰ ਫਲੈਗ ਚਾਲੂ ਹੋਵੇ |
| `MANAGEMENT` | ਡੈਸ਼ਬੋਰਡ ਪੰਨੇ, ਸੈਟਿੰਗਾਂ, ਪ੍ਰਦਾਤਾ, ਕੁੰਜੀਆਂ, ਐਡਮਿਨ ਅਤੇ ਡਾਇਗਨੌਸਟਿਕ ਐਂਡਪੌਇੰਟ।                                                                    | ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਜਾਂ `manage` ਸਕੋਪ ਵਾਲਾ Bearer                    |

ਕੁਝ `MANAGEMENT` ਕਾਰਵਾਈਆਂ **ਸਿਰਫ਼ ਓਪਰੇਟਰ** ਲਈ ਹਨ: `manage` ਕੁੰਜੀ ਕਾਫ਼ੀ ਨਹੀਂ। ਸਟੋਰ ਕੀਤੇ ਕ੍ਰੈਡੈਂਸ਼ੀਅਲ ਐਕਸਪੋਰਟ ਕਰਨਾ (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ਲਾਈਵ ਡੇਟਾ ਉੱਤੇ ਬੈਕਅੱਪ ਰੀਸਟੋਰ ਕਰਨਾ (`dryRun=true` ਸਮੇਤ `POST /api/db-backups/import`, ਆਈਡੀ ਰਾਹੀਂ ਰੀਸਟੋਰ `POST /api/db-backups`, `POST /api/settings/import-json`), ਅਤੇ ਰੀਸਟੋਰ ਪੌਇੰਟ ਨਸ਼ਟ ਕਰਨਾ (`DELETE /api/db-backups` ਸਫਾਈ, ਅਤੇ `PATCH /api/db-backups` ਕਿਉਂਕਿ ਇਹ ਜੋ ਰੱਖ-ਰਖਾਵ ਸੰਭਾਲਦਾ ਹੈ ਉਹ ਹਰ ਬੈਕਅੱਪ ਤੋਂ ਬਾਅਦ ਆਟੋਮੈਟਿਕ ਛਾਂਟੀ ਚਲਾਉਂਦਾ ਹੈ) ਲਈ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ, ਲੋਕਲ CLI ਸਬਜੈਕਟ, ਜਾਂ ਲੌਗਇਨ ਬੰਦ ਹੋਣਾ ਲੋੜੀਂਦਾ ਹੈ। ਸਿੰਕ ਟੋਕਨ ਜਾਰੀ ਕਰਨਾ (`POST /api/sync/tokens`) ਅਤੇ `admin` CLI ਐਕਸੈੱਸ ਟੋਕਨ ਬਣਾਉਣਾ (`POST /api/cli/tokens`) ਹਰ ਲੌਗਇਨ ਮੋਡ ਵਿੱਚ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਜਾਂ ਲੋਕਲ CLI ਸਬਜੈਕਟ ਮੰਗਦੇ ਹਨ। ਕਿਸੇ ਵੀ ਸਕੋਪ ਦੀਆਂ API ਕੁੰਜੀਆਂ ਅਤੇ `oma_` ਐਕਸੈੱਸ ਟੋਕਨ ਓਪਰੇਟਰ ਕ੍ਰੈਡੈਂਸ਼ੀਅਲ ਨਹੀਂ ਹਨ: ਜਦੋਂ ਵੀ ਇਹ ਲੋੜੀਂਦਾ ਹੋਵੇ, ਉਹਨਾਂ ਨੂੰ `403` ਮਿਲਦਾ ਹੈ। ਇਹ ਜਾਂਚ `src/lib/api/operatorCredential.ts` ਵਿੱਚ ਹੈ (`resolveOperatorCredential()` / `requireOperatorCredential()`)। ਲੌਗਇਨ ਸੈਟਿੰਗਾਂ ਬਦਲਣਾ ਵੀ ਸਿਰਫ਼ ਓਪਰੇਟਰ ਲਈ ਹੈ: `POST /api/settings/require-login` (ਪ੍ਰਬੰਧਨ ਪਾਸਵਰਡ ਸੈੱਟ ਕਰਨਾ / `requireLogin` ਟੌਗਲ ਕਰਨਾ) ਇੱਕ ਵਾਰ ਪਾਸਵਰਡ ਮੌਜੂਦ ਹੋਣ 'ਤੇ ਸਿਰਫ਼ ਉਹੀ ਕ੍ਰੈਡੈਂਸ਼ੀਅਲ ਸਵੀਕਾਰ ਕਰਦਾ ਹੈ — ਪਹਿਲੀ-ਵਾਰ ਬੂਟਸਟ੍ਰੈਪ ਵਿੰਡੋ (ਅਜੇ ਪਾਸਵਰਡ ਨਹੀਂ) ਨਹੀਂ ਬਦਲਦੀ — ਅਤੇ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਨੂੰ ਪਾਸਵਰਡ ਬਦਲਣ ਲਈ `currentPassword` ਭੇਜਣਾ ਪੈਂਦਾ ਹੈ (ਗੈਰ-ਮੌਜੂਦ ਜਾਂ ਗਲਤ ਹੋਣ 'ਤੇ `403`, `settings.update_failed` ਵਜੋਂ ਆਡਿਟ ਹੁੰਦਾ ਹੈ)। ਲੋਕਲ CLI ਅਤੇ ਲੌਗਇਨ ਬੰਦ ਵਾਲਾ ਇੰਸਟੈਂਸ ਰਿਕਵਰੀ ਰਸਤਾ ਰੱਖਦੇ ਹਨ ਅਤੇ ਇਸ ਤੋਂ ਬਿਨਾਂ ਪਾਸਵਰਡ ਸੈੱਟ ਕਰ ਸਕਦੇ ਹਨ, ਕਿਉਂਕਿ ਦੋਵੇਂ ਉਸ ਹੋਸਟ ਨਾਲ ਬੱਝੇ ਹਨ ਜੋ ਡੇਟਾ ਡਾਇਰੈਕਟਰੀ ਦਾ ਮਾਲਕ ਹੈ।

## ਪਾਈਪਲਾਈਨ

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

ਭਰੋਸੇਯੋਗ ਅੰਦਰੂਨੀ ਸਿਰਲੇਖ ( `src/server/authz/headers.ts` ਵਿੱਚ ਪਰਿਭਾਸ਼ਿਤ) ਹਨ** ਆਉਣ ਵਾਲੀਆਂ ਬੇਨਤੀਆਂ ਤੋਂ ਹਟਾ ਦਿੱਤਾ ਗਿਆ** ਵਰਗੀਕਰਨ ਤੋਂ ਪਹਿਲਾਂ — ਕਲਾਇੰਟ ਕਿਸੇ ਵਿਸ਼ੇ ਦੀ ਨਕਲ ਕਰਨ ਲਈ `x-omniroute-auth-*` ਪਹਿਲਾਂ ਤੋਂ ਤਿਆਰ ਨਹੀਂ ਕਰ ਸਕਦੇ ਹਨ।

### ਨੀਤੀ ਦੇ ਠੇਕੇ

ਹਰੇਕ ਰੂਟ ਕਲਾਸ ਦੀ `src/server/authz/policies/` ਵਿੱਚ ਇੱਕ ਨੀਤੀ ਹੈ:

- **`publicPolicy`** (`policies/public.ts`) — ਹਮੇਸ਼ਾ `allow({ kind: "anonymous", id: "anonymous" })` ਵਾਪਸ ਕਰਦਾ ਹੈ।
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ਬੇਅਰਰ ਨੂੰ ਕੱਢਦਾ ਹੈ, `validateApiKey()` ਰਾਹੀਂ ਪ੍ਰਮਾਣਿਤ ਕਰਦਾ ਹੈ। ਉਦੋਂ ਹੀ ਗੁਮਨਾਮ 'ਤੇ ਡਿੱਗਦਾ ਹੈ ਜਦੋਂ ਪ੍ਰਭਾਵੀ `REQUIRE_API_KEY` ਵਿਸ਼ੇਸ਼ਤਾ ਫਲੈਗ ਅਸਮਰੱਥ ਹੁੰਦਾ ਹੈ। ਪ੍ਰਭਾਵੀ ਫਲੈਗ ਨੂੰ `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) ਦੁਆਰਾ ਹੱਲ ਕੀਤਾ ਜਾਂਦਾ ਹੈ ਇਸਲਈ ਡੈਸ਼ਬੋਰਡ ਫੀਚਰ ਫਲੈਗ ਅਤੇ ਵਾਤਾਵਰਣ ਵੇਰੀਏਬਲ `/api/v1/*`, `/api/v1beta/*`, ਅਤੇ ਉਪਨਾਮਾਂ ਨੂੰ ਲਗਾਤਾਰ ਨਿਯੰਤਰਿਤ ਕਰਦੇ ਹਨ; ਰਿਜ਼ੋਲਵਰ ਅਸਫਲਤਾਵਾਂ ਬੰਦ ਹੋ ਜਾਂਦੀਆਂ ਹਨ। ਕਲਾਇੰਟ API ਰੂਟਾਂ ( `/api/v1/models` ਸਮੇਤ, ਡੈਸ਼ਬੋਰਡ ਮਾਡਲ ਕੈਟਾਲਾਗ ਦੁਆਰਾ ਵਰਤੇ ਗਏ) 'ਤੇ ਡੈਸ਼ਬੋਰਡ-ਸ਼ੈਸ਼ਨ ਬੇਨਤੀਆਂ ਦੀ ਆਗਿਆ ਦਿੰਦਾ ਹੈ। ਜਦੋਂ Entra ID SSO ਸਮਰਥਿਤ ਹੁੰਦਾ ਹੈ, ਤਾਂ ਇੱਕ ਬੇਅਰਰ ਜੋ ਕਿ ਢਾਂਚਾਗਤ ਤੌਰ 'ਤੇ ਇੱਕ Entra ਟੋਕਨ ਹੁੰਦਾ ਹੈ (ਤਿੰਨ base64url ਖੰਡ, `RS*` alg, `kid`) ਨੂੰ SSO ਸ਼ਾਖਾ ਦੁਆਰਾ ਸੰਭਾਲਿਆ ਜਾਂਦਾ ਹੈ।** ਅੱਗੇ** `validateApiKey()` ਅਤੇ ਇਸਦਾ ਫੈਸਲਾ ਅੰਤਿਮ — ਹੈ ਇਹ ਕਦੇ ਵੀ API-ਕੁੰਜੀ ਮਾਰਗ ਜਾਂ ਡੀਗਰੇਡ-ਟੂ-ਅਨਾਮ ਬ੍ਰਾਂਚ ਵਿੱਚ ਨਹੀਂ ਆਉਂਦਾ ਹੈ, ਇਸਲਈ ਇੱਕ ਪਛਾਣ-ਪ੍ਰਦਾਤਾ ਆਊਟੇਜ ਖੁੱਲ੍ਹੀ ਪਹੁੰਚ ਨਹੀਂ ਬਣ ਸਕਦਾ। ਸਥਿਰ API ਕੁੰਜੀਆਂ ਪ੍ਰਭਾਵਿਤ ਨਹੀਂ ਹੁੰਦੀਆਂ ਹਨ। [Entra ID SSO](../security/ENTRA_SSO.md) ਦੇਖੋ।
- **`managementPolicy`** (`policies/management.ts`) — ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ, ਅੰਦਰੂਨੀ ਮਾਡਲ-ਸਿੰਕ ਬੇਨਤੀਆਂ ਨੂੰ ਸਵੀਕਾਰ ਕਰਦਾ ਹੈ ( `/api/providers/[name]/(sync-models|models)` ਨਾਲ ਮੇਲ ਖਾਂਦਾ ਹੈ), ਜਾਂ ਪੂਰੀ ਤਰ੍ਹਾਂ ਛੱਡ ਦਿੰਦਾ ਹੈ ਜੇਕਰ `isAuthRequired()` ਗਲਤ ਵਾਪਸ ਕਰਦਾ ਹੈ। 403 (`AUTH_001`) ਵਾਪਸ ਕਰਦਾ ਹੈ ਜਦੋਂ ਇੱਕ ਬੇਅਰਰ ਟੋਕਨ ਮੌਜੂਦ ਹੁੰਦਾ ਹੈ ਪਰ ਅਵੈਧ ਹੁੰਦਾ ਹੈ, ਨਹੀਂ ਤਾਂ 401। ਕਿਸੇ ਵੀ ਪ੍ਰਮਾਣਿਤ ਸ਼ਾਖਾ — [ਰੂਟ ਗਾਰਡ ਟੀਅਰਜ਼ ਨੂੰ](../security/ROUTE_GUARD_TIERS.md) ਦੇਖਣ ਤੋਂ ਪਹਿਲਾਂ ਰੂਟ-ਗਾਰਡ ਟੀਅਰਜ਼ (LOCAL_ONLY / ALWAYS_PROTECTED) ਨੂੰ ਵੀ ਲਾਗੂ ਕਰਦਾ ਹੈ। `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (ਅੱਜ: `/api/mcp/`) ਵਿੱਚ LOCAL_ONLY ਮਾਰਗਾਂ ਨੂੰ ਗੈਰ-ਲੂਪਬੈਕ ਤੋਂ ਐਕਸੈਸ ਕੀਤਾ ਜਾ ਸਕਦਾ ਹੈ ਜਦੋਂ ਬੇਅਰਰ ਕੁੰਜੀ `manage` ਸਕੋਪ ਨੂੰ ਲੈ ਕੇ ਜਾਂਦੀ ਹੈ; ਹੋਰ ਸਾਰੇ LOCAL_ONLY ਮਾਰਗ ਸਕੋਪ ਦੀ ਪਰਵਾਹ ਕੀਤੇ ਬਿਨਾਂ ਸਖਤ-ਲੂਪਬੈਕ ਰਹਿੰਦੇ ਹਨ।

ਇੱਕ ਸਫਲ ਨੀਤੀ `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` ਨਾਲ `AuthSubject` ਵਾਪਸ ਕਰਦੀ ਹੈ। ਡਾਊਨਸਟ੍ਰੀਮ ਹੈਂਡਲਰ ਇਸ ਨੂੰ `src/server/authz/assertAuth.ts` ਵਿੱਚ `assertAuth(request, "CLIENT_API")` ਦੁਆਰਾ ਪ੍ਰਮਾਣਿਤ ਤਰਕ ਨੂੰ ਮੁੜ ਚਲਾਉਣ ਦੀ ਬਜਾਏ ਪੜ੍ਹ ਸਕਦੇ ਹਨ।

## ਜਨਤਕ ਰੂਟਾਂ ਦੀ ਸੂਚੀ

`src/shared/constants/publicApiRoutes.ts` ਸਪਸ਼ਟ ਅਨੁਮਤੀ ਸੂਚੀ ਹੈ:

ਸੂਚੀ ਨੂੰ ਵੰਡਿਆ ਗਿਆ ਹੈ** ਸ਼ਕਲ** , ਅਤੇ ਸਪਲਿਟ ਲੋਡ-ਬੇਅਰਿੰਗ ਹੈ (GHSA-74g9-q8f6-793h): ਇੱਕ ਅਗੇਤਰ `startsWith()` ਨਾਲ ਮੇਲ ਖਾਂਦਾ ਹੈ, ਇਸਲਈ ਇਹ ਇਸਦੇ ਪ੍ਰਮੁੱਖ ਅੱਖਰਾਂ ਨੂੰ ਸਾਂਝਾ ਕਰਨ ਵਾਲੇ ਹਰੇਕ ਨਾਲ ਲੱਗਦੇ ਮਾਰਗ ਨਾਲ ਵੀ ਮੇਲ ਖਾਂਦਾ ਹੈ। `/api/usage/om-usage` ਇੱਕ ਅਗੇਤਰ ਵਜੋਂ `/api/usage/om-usage<anything>` PUBLIC ਮਾਰਕ ਕੀਤਾ ਗਿਆ ਹੈ, ਅਤੇ ਅਗਲਾ ਨਿਪਟਾਰਾ ਕਰਦਾ ਹੈ ਕਿ ਇੱਕ ਹੈਂਡਲਰ ਨੂੰ `/api/usage/[connectionId]` — ਕਰਨਾ ਹੈ ਜਿਸਦਾ ਕੋਈ ਪ੍ਰਮਾਣਿਕਤਾ ਨਹੀਂ ਹੈ।

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

ਸਿਰਫ਼ ਪੜ੍ਹਨ ਲਈ ਰੂਟ ਜਨਤਕ ਹਨ** ਸਿਰਫ਼** ਸੁਰੱਖਿਅਤ ਢੰਗਾਂ ਲਈ. ਨੋਟ: `classifyRoute()` PUBLIC -ਥਰੂ — ਤੋਂ `/api/v1/*` ਅਤੇ `/api/v1beta/*` ਵੱਖ ਕਰਦਾ ਹੈ ਜੋ ਹਮੇਸ਼ਾ `CLIENT_API` ਹੁੰਦੇ ਹਨ ਇਸਲਈ ਬੇਅਰਰ-ਕੁੰਜੀ ਨੀਤੀ ਅਜੇ ਵੀ ਲਾਗੂ ਹੁੰਦੀ ਹੈ।

## ਨਵਾਂ ਰੂਟ ਜੋੜਨਾ

### ਪੈਟਰਨ 1 — ਸਰਵਜਨਿਕ ਕਲਾਇੰਟ API ਐਂਡਪੌਇੰਟ (Bearer-auth)

`/api/v1/` ਅਤੇ `/api/v1beta/` ਹੇਠਲੇ ਰੂਟ ਆਪਣੇ-ਆਪ `CLIENT_API` ਵਜੋਂ ਵਰਗੀਕ੍ਰਿਤ ਹੁੰਦੇ ਹਨ। ਮਿਡਲਵੇਅਰ Bearer ਜਾਂਚ ਲਾਗੂ ਕਰਦਾ ਹੈ; ਰੂਟ ਹੈਂਡਲਰਾਂ ਨੂੰ ਇਸਨੂੰ ਦੁਬਾਰਾ ਕਰਨ ਦੀ ਲੋੜ ਨਹੀਂ, ਪਰ ਲਾਭਦਾਇਕ ਹੋਣ 'ਤੇ ਉਹ ਸਬਜੈਕਟ ਪੜ੍ਹ ਸਕਦੇ ਹਨ।

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... ਹੈਂਡਲਰ ਲਾਜਿਕ
}
```

### ਪੈਟਰਨ 2 — ਪ੍ਰਬੰਧਨ ਐਂਡਪੌਇੰਟ (ਸੈਸ਼ਨ ਜਾਂ Bearer + manage)

`src/lib/api/requireManagementAuth.ts` ਤੋਂ `requireManagementAuth()` ਵਰਤੋ:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... ਹੈਂਡਲਰ ਲਾਜਿਕ
}
```

ਸਫਲਤਾ 'ਤੇ `requireManagementAuth()` `null` ਵਾਪਸ ਕਰਦਾ ਹੈ, ਨਹੀਂ ਤਾਂ JSON ਗਲਤੀ `Response`:

- 401 `AUTH_001` "ਪ੍ਰਮਾਣੀਕਰਨ ਲੋੜੀਂਦਾ ਹੈ" — ਕੋਈ ਵੀ ਕਰੈਡੈਂਸ਼ਲ ਮੌਜੂਦ ਨਹੀਂ
- 403 — ਅਵੈਧ Bearer **ਜਾਂ** Bearer ਮੌਜੂਦ ਹੈ ਪਰ ਕੀ ਕੋਲ `manage` / `admin` ਸਕੋਪ ਨਹੀਂ ਹੈ

`hasManageScope(scopes)` `"manage"` ਜਾਂ `"admin"` ਲਈ true ਵਾਪਸ ਕਰਦਾ ਹੈ।

### ਪੈਟਰਨ 3 — ਸਰਵਜਨਿਕ ਮਨਜ਼ੂਰਸ਼ੁਦਾ ਸੂਚੀ ਵਿੱਚ ਜੋੜਨਾ

ਸਹੂਲਤ ਦੇ ਆਧਾਰ 'ਤੇ ਨਹੀਂ, ਸਗੋਂ ਆਕਾਰ ਦੇ ਆਧਾਰ 'ਤੇ ਸੈੱਟ ਚੁਣੋ। ਇੱਕ ਰੂਟ `PUBLIC_API_ROUTES_EXACT` ਵਿੱਚ ਜਾਂਦਾ ਹੈ (ਜਾਂ ਕੇਵਲ-GET ਲਈ `PUBLIC_READONLY_CORS_API_ROUTES` ਵਿੱਚ); ਕੇਵਲ ਇੱਕ ਅਸਲ ਸਬਟ੍ਰੀ ਹੀ `PUBLIC_API_ROUTE_PREFIXES` ਵਿੱਚ ਜਾਂਦੀ ਹੈ, ਅਤੇ ਇਸਦਾ ਅੰਤ `/` ਨਾਲ ਹੋਣਾ **ਲਾਜ਼ਮੀ ਹੈ**। ਪ੍ਰੀਫਿਕਸ ਸੂਚੀ ਵਿੱਚ ਇੱਕ ਇਕੱਲਾ ਰੂਟ ਪਾਉਣ ਨਾਲ ਉਹ ਸਾਰੇ ਨਾਲ ਲੱਗਦੇ ਪਾਥ ਵੀ ਸਰਵਜਨਿਕ ਹੋ ਜਾਂਦੇ ਹਨ ਜਿਨ੍ਹਾਂ ਦੇ ਸ਼ੁਰੂਆਤੀ ਅੱਖਰ ਇੱਕੋ ਹਨ — ਇਸ ਵਿੱਚ ਬਾਅਦ ਵਿੱਚ ਜੋੜੇ ਗਏ ਡਾਇਨਾਮਿਕ-ਸੈਗਮੈਂਟ ਸਿਬਲਿੰਗ ਵੀ ਸ਼ਾਮਲ ਹਨ (GHSA-74g9-q8f6-793h)। `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ਅਤੇ `tests/unit/authz/classify.test.ts` ਵਿੱਚ ਯੂਨਿਟ ਟੈਸਟ ਅੱਪਡੇਟ ਕਰੋ।

## ਸਕੋਪਸ

ਤਿੰਨ ਨਾਮਸਪੇਸ। ਹਰੇਕ ਚੈਕਰ ਸਿਰਫ਼ ਆਪਣੀਆਂ ਸਤਰਾਂ ਪੜ੍ਹਦਾ ਹੈ। ਨਾਲ-ਨਾਲ, ਜਿਸ ਵਿੱਚ ਇਹ ਵੀ ਸ਼ਾਮਲ ਹੈ ਕਿ `manage` `read:compression` ਲਈ `scopeMatches` ਵਿੱਚ ਕਿਉਂ ਫੇਲ੍ਹ ਹੁੰਦਾ ਹੈ ਅਤੇ ਇੱਕ `read` ਐਕਸੈਸ ਟੋਕਨ `PATCH /api/keys/{id}` ਕਿਉਂ ਨਹੀਂ ਕਰ ਸਕਦਾ, ਉਹ ਹੈ [ਤਿੰਨ ਸਕੋਪ ਨਾਮਸਪੇਸ](../frameworks/MCP-SERVER.md#three-scope-namespaces)।

API ਕੁੰਜੀਆਂ ਇੱਕ `scopes` ਐਰੇ ਰੱਖਦੀਆਂ ਹਨ (ਜੋ `api_keys.scopes` ਵਿੱਚ JSON ਵਜੋਂ ਸਟੋਰ ਕੀਤੀਆਂ ਜਾਂਦੀਆਂ ਹਨ, ਦੇਖੋ `src/lib/db/apiKeys.ts`)।

### ਪ੍ਰਬੰਧਨ ਸਕੋਪ

- `manage` / `admin` — `hasManageScope`। ਪ੍ਰਬੰਧਨ API ਰੂਟਾਂ ਤੱਕ ਬੀਅਰਰ ਪਹੁੰਚ।
- `mcp:connect`, `self:usage`, `self:account-quota`, ਅਤੇ
  `policy:bypass-provider-quota` ਐਡਿਟਿਵ ਐਗਜ਼ੈਕਟ-ਮੈਚ ਸਕੋਪ ਹਨ। ਉਹ
  `MANAGEMENT_API_KEY_SCOPES` ਤੋਂ ਬਾਹਰ ਹਨ। `mcp:connect` ਸਿਰਫ਼
  `/api/mcp/` ਨਾਨ-ਲੂਪਬੈਕ ਕਾਰਵ-ਆਊਟ ਖੋਲ੍ਹਦਾ ਹੈ।

### MCP ਟੂਲ ਸਕੋਪਸ

ਕੈਟਾਲਾਗ ਅਤੇ ਮੈਚਿੰਗ ਨਿਯਮ (ਇੱਕੋ ਜਿਹੀ ਸਤਰ, ਜਾਂ ਇੱਕ ਗ੍ਰਾਂਟਡ ਸਕੋਪ ਜੋ `*` ਨਾਲ ਖਤਮ ਹੁੰਦਾ ਹੈ):
[MCP ਟੂਲ ਸਕੋਪਸ](../frameworks/MCP-SERVER.md#mcp-tool-scopes)।
`src/shared/constants/mcpScopes.ts` ਵਿੱਚ `MCP_SCOPE_LIST` ਅਸਲੀ ਟਾਈਪਡ
ਸਬਸੈੱਟ ਹੈ, ਨਾ ਕਿ ਉਹ ਪੂਰਾ ਕੈਟਾਲਾਗ। ਲਾਗੂਕਰਨ
`open-sse/mcp-server/scopeEnforcement.ts` ਵਿੱਚ ਚੱਲਦਾ ਹੈ ਜਦੋਂ `resolveCallerScopeContext()`
MCP ਪ੍ਰਮਾਣਿਕਤਾ ਜਾਣਕਾਰੀ, ਬੇਨਤੀ ਮੈਟਾਡੇਟਾ, ਜਾਂ `OMNIROUTE_MCP_SCOPES` ਤੋਂ ਸਕੋਪਾਂ ਨੂੰ ਹੱਲ ਕਰਦਾ ਹੈ।
ਇਹ ਉਦੋਂ ਤੱਕ ਬੰਦ ਰਹਿੰਦਾ ਹੈ ਜਦੋਂ ਤੱਕ `OMNIROUTE_MCP_ENFORCE_SCOPES=true` ਨਹੀਂ ਹੁੰਦਾ।

### ਐਕਸੈਸ-ਟੋਕਨ ਸਕੋਪਸ

`oma_live_…` ਟੋਕਨਾਂ 'ਤੇ `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) ਦੁਆਰਾ ਦਰਜਾਬੰਦੀ ਕੀਤੀ ਗਈ। ਇਹ ਰੈਂਕ ਸਿਰਫ਼ ਐਕਸੈਸ-ਟੋਕਨ
ਪ੍ਰਮਾਣ ਪੱਤਰ 'ਤੇ ਲਾਗੂ ਹੁੰਦਾ ਹੈ। ਦੇਖੋ [ਪ੍ਰਬੰਧਨ ਪ੍ਰਮਾਣਿਕਤਾ](../guides/MANAGEMENT-AUTH.md)।

## ਔਥ ਲੋੜੀਂਦਾ ਟੌਗਲ

`src/shared/utils/apiAuth.ts` ਵਿੱਚ `isAuthRequired()` ਫੈਸਲਾ ਕਰਦਾ ਹੈ ਕਿ ਕਿਸੇ ਬੇਨਤੀ ਲਈ **ਕੋਈ ਵੀ** ਪ੍ਰਮਾਣੀਕਰਨ ਲਾਗੂ ਹੋਵੇਗਾ ਜਾਂ ਨਹੀਂ:

- `settings.requireLogin === false` → ਪ੍ਰਮਾਣੀਕਰਨ ਵਿਸ਼ਵ-ਪੱਧਰ 'ਤੇ ਬੰਦ ਹੈ, ਸਿਵਾਏ ਹਮੇਸ਼ਾ-ਸੁਰੱਖਿਅਤ ਟੀਅਰ (ਵੇਖੋ [ਰੂਟ ਗਾਰਡ ਟੀਅਰ](../security/ROUTE_GUARD_TIERS.md)) ਅਤੇ ਉਹਨਾਂ ਕਾਲਾਂ ਦੇ ਜੋ ਉਹ ਕ੍ਰੈਡੈਂਸ਼ੀਅਲ ਦਿੰਦੀਆਂ ਹਨ ਜੋ ਇਹ ਸਵੀਕਾਰ ਕਰਦਾ ਹੈ — ਇਹਨਾਂ ਨੂੰ ਉਹੀ ਕ੍ਰੈਡੈਂਸ਼ੀਅਲ ਚਾਹੀਦਾ ਹੈ ਜਿਵੇਂ ਲੌਗਇਨ ਚਾਲੂ ਹੋਣ 'ਤੇ: ਸਿੰਕ ਟੋਕਨ ਜਾਰੀ ਕਰਨਾ, ਕਿਸੇ ਵੀ ਸਕੋਪ 'ਤੇ CLI ਐਕਸੈੱਸ ਟੋਕਨ ਬਣਾਉਣਾ, ਅਤੇ `manage`/`admin` ਸਕੋਪ ਵਾਲੀ API ਕੁੰਜੀ ਬਣਾਉਣਾ, ਉਸ ਸਕੋਪ ਨੂੰ ਕਿਸੇ ਕੁੰਜੀ ਨੂੰ ਦੇਣਾ, ਜਾਂ ਅਜਿਹੀ ਕੁੰਜੀ ਨੂੰ ਮੁੜ-ਬਣਾਉਣਾ ਜਾਂ ਦਿਖਾਉਣਾ (`src/lib/api/requireManagementAuth.ts` ਵਿੱਚ `requireCredentialForManagementScopedKey()`)। ਇਨਫਰੈਂਸ-ਸਿਰਫ਼ ਕੁੰਜੀਆਂ ਖੁੱਲ੍ਹੀਆਂ ਰਹਿੰਦੀਆਂ ਹਨ।
- ਕੋਈ ਪਾਸਵਰਡ ਸੰਰਚਿਤ ਨਹੀਂ **ਅਤੇ** ਕੋਈ `INITIAL_PASSWORD` ਵਾਤਾਵਰਣ ਵੇਰੀਏਬਲ ਨਹੀਂ → ਬੂਟਸਟ੍ਰੈਪ ਮੋਡ ਔਨਬੋਰਡਿੰਗ ਵਿਜ਼ਾਰਡ ਅਤੇ ਲੋਕਲ ਬੇਨਤੀਆਂ ਦੀ ਇਜਾਜ਼ਤ ਦਿੰਦਾ ਹੈ, ਪਰ ਬਾਹਰੀ ਨੈੱਟਵਰਕ ਬੇਨਤੀਆਂ ਨੂੰ ਅਜੇ ਵੀ ਕ੍ਰੈਡੈਂਸ਼ੀਅਲ ਚਾਹੀਦੇ ਹਨ।
- ਕੋਈ ਵੀ DB ਗਲਤੀ → ਬੰਦ ਹੋ ਕੇ ਫੇਲ੍ਹ ਹੁੰਦਾ ਹੈ (ਡਿਫਾਲਟ ਤੌਰ 'ਤੇ ਸੁਰੱਖਿਅਤ)।

ਕਲਾਇੰਟ API ਕੁੰਜੀ ਲਾਗੂਕਰਨ `src/shared/utils/featureFlags.ts` ਵਿੱਚ `isRequireApiKeyEnabled()` ਵਰਤਦਾ ਹੈ, ਨਾ ਕਿ ਸਿੱਧਾ `process.env.REQUIRE_API_KEY` ਪੜ੍ਹਨਾ। ਇਹ ਤਾਇਨਾਤ ਇੰਸਟੈਂਸਾਂ ਲਈ ਮਾਇਨੇ ਰੱਖਦਾ ਹੈ: ਡੈਸ਼ਬੋਰਡ → Feature Flags ਵਿੱਚ `REQUIRE_API_KEY` ਬਦਲਣ ਨਾਲ DB ਓਵਰਰਾਈਡ ਸਟੋਰ ਹੁੰਦਾ ਹੈ ਅਤੇ ਤੁਰੰਤ `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ਅਤੇ ਹੋਰ ਕਲਾਇੰਟ-API ਪ੍ਰਮਾਣੀਕਰਨ ਜਾਂਚਾਂ 'ਤੇ ਅਸਰ ਪਾਉਂਦਾ ਹੈ, ਜੋ ਇਸ ਹੈਲਪਰ ਨੂੰ ਸਾਂਝਾ ਕਰਦੀਆਂ ਹਨ। ਜੇ ਫੀਚਰ ਫਲੈਗ ਸਟੋਰ ਪੜ੍ਹਿਆ ਨਾ ਜਾ ਸਕੇ, ਤਾਂ ਕਲਾਇੰਟ API ਪ੍ਰਮਾਣੀਕਰਨ ਬੰਦ ਹੋ ਕੇ ਫੇਲ੍ਹ ਹੁੰਦਾ ਹੈ ਅਤੇ ਕੁੰਜੀ ਲਾਜ਼ਮੀ ਕਰਦਾ ਹੈ।

## ਅਸੰਗਤ ਤਬਦੀਲੀ — v3.8.0

`/api/v1/agents/tasks/*` ਅਤੇ `/api/resilience/model-cooldowns` ਐਂਡਪੌਇੰਟਾਂ ਲਈ **ਹੁਣ ਪ੍ਰਬੰਧਨ ਪ੍ਰਮਾਣੀਕਰਨ ਲੋੜੀਂਦਾ ਹੈ** (ਕਮਿਟ `588a0333`)। ਪਹਿਲਾਂ `manage` ਸਕੋਪ ਤੋਂ ਬਿਨਾਂ ਆਮ API ਕੁੰਜੀ ਭੇਜਣ ਵਾਲੇ ਕਲਾਇੰਟਾਂ ਨੂੰ `403` ਪ੍ਰਾਪਤ ਹੁੰਦਾ ਹੈ। ਮਾਈਗ੍ਰੇਸ਼ਨ: ਜਾਂ ਤਾਂ API Keys ਡੈਸ਼ਬੋਰਡ ਵਿੱਚ ਕੁੰਜੀ ਨੂੰ `manage` ਸਕੋਪ ਦਿਓ, ਜਾਂ ਲੌਗ-ਇਨ ਕੀਤੇ ਡੈਸ਼ਬੋਰਡ ਸੈਸ਼ਨ ਦੀ ਵਰਤੋਂ ਕਰੋ।

## ਵਿਵਹਾਰ ਤਬਦੀਲੀ — v3.8.2

`/api/mcp/*` (ਰਿਮੋਟ MCP ਸਰਵਰ) ਹਾਲੇ ਵੀ ਮੂਲ ਰੂਪ ਵਿੱਚ LOCAL_ONLY ਹੈ, ਪਰ ਹੁਣ ਇਹ ਗੈਰ-ਲੂਪਬੈਕ ਬੇਨਤੀਆਂ ਸਵੀਕਾਰ ਕਰਦਾ ਹੈ ਜਦੋਂ `Authorization: Bearer <api-key>` ਹੈਡਰ ਵਿੱਚ `manage` ਸਕੋਪ ਮੌਜੂਦ ਹੋਵੇ। ਇਸ ਛੋਟ ਨੂੰ `src/server/authz/routeGuard.ts` ਵਿੱਚ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ਰਾਹੀਂ ਹਰੇਕ ਪਾਥ ਲਈ ਸਪਸ਼ਟ ਤੌਰ 'ਤੇ ਨਿਯੰਤਰਿਤ ਕੀਤਾ ਗਿਆ ਹੈ; ਸਮਾਨ LOCAL_ONLY ਪ੍ਰੀਫਿਕਸ `/api/cli-tools/runtime/*` ਨੂੰ ਜਾਣ-ਬੁੱਝ ਕੇ ਬਾਈਪਾਸ ਨਹੀਂ ਕੀਤਾ ਜਾ ਸਕਦਾ, ਕਿਉਂਕਿ ਇਹ ਮਨਮਾਨੀਆਂ ਸਬ-ਪ੍ਰਕਿਰਿਆਵਾਂ ਸ਼ੁਰੂ ਕਰ ਸਕਦਾ ਹੈ। ਗੈਰ-ਲੂਪਬੈਕ ਤੋਂ `/api/mcp/*` ਲਈ ਅਗਿਆਤ ਬੇਨਤੀਆਂ ਨੂੰ ਅਜੇ ਵੀ `403 LOCAL_ONLY` ਮਿਲਦਾ ਹੈ — ਕਿਸੇ ਵੀ ਨਵੇਂ LOCAL_ONLY ਪਾਥ ਲਈ ਮੂਲ ਨੀਤੀ ਸਖ਼ਤ-ਲੂਪਬੈਕ ਹੀ ਰਹਿੰਦੀ ਹੈ। [ਰੂਟ ਗਾਰਡ ਪੱਧਰ](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) ਵੇਖੋ।

## ਟੈਸਟਿੰਗ

- ਯੂਨਿਟ ਟੈਸਟ: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`।
- ਜਨਤਕ ਮਨਜ਼ੂਰਸ਼ੁਦਾ ਸੂਚੀ: `tests/unit/public-api-routes.test.ts`।
- ਕੇਂਦ੍ਰਿਤ ਟੈਸਟ ਚਲਾਓ: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`।

## ਡੀਬੱਗਿੰਗ

ਪਾਈਪਲਾਈਨ ਹਮੇਸ਼ਾ ਜਵਾਬਾਂ 'ਤੇ ਮੋਹਰ ਲਗਾਉਂਦੀ ਹੈ:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

ਪ੍ਰਮਾਣਿਤ ਬੇਨਤੀਆਂ ਲਈ ਅੱਪਸਟ੍ਰੀਮ (ਹੈਂਡਲਰ-ਸਾਈਡ) ਬੇਨਤੀ ਸਿਰਲੇਖਾਂ ਵਿੱਚ ਇਹ ਵੀ ਸ਼ਾਮਲ ਹਨ:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ਹੈਂਡਲਰਜ਼ — ਦੇ ਅੰਦਰ `assertAuth(req, expectedClass)` ਵਰਤੋਂ ਕਰੋ ਇਹ ਕੋਡ `AUTHZ_NOT_INITIALIZED` ਨਾਲ `AuthzAssertionError` ਸੁੱਟਦਾ ਹੈ ਜੇਕਰ ਮਿਡਲਵੇਅਰ ਨੂੰ ਬਾਈਪਾਸ ਕੀਤਾ ਗਿਆ ਸੀ (ਟੈਸਟਾਂ ਵਿੱਚ ਸੰਰਚਨਾ ਰੀਗਰੈਸ਼ਨ ਨੂੰ ਫੜਨ ਲਈ ਮਦਦਗਾਰ)।

## ਇਹ ਵੀ ਵੇਖੋ

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ਪ੍ਰਤੀ ਐਂਡਪੁਆਇੰਟ ਪ੍ਰਮਾਣਿਕਤਾ ਮਾਰਕਰ
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ਪ੍ਰਮਾਣਿਕਤਾ ਇਵੈਂਟਾਂ ਲਈ ਆਡਿਟ ਲੌਗ
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ਤਿੰਨ ਸਕੋਪ ਨਾਮਸਥਾਨ ਅਤੇ MCP ਟੂਲ-ਸਕੋਪ ਕੈਟਾਲਾਗ
- ਸਰੋਤ: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
