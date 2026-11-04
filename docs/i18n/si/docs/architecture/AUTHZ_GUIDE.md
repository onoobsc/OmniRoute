# Authorization Guide (සිංහල)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **සත්යයේ මූලාශ්රය:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **අවසන් වරට යාවත්කාලීන කරන ලදී:** 2026-09-22 — විෂය පථ නාම අවකාශ MCP-SERVER.md වෙත යොමු කරයි

OmniRoute සතුව සෑම API ඉල්ලීමක්ම පාලනය කරන මාර්ග-දැනුවත් අවසර නල මාර්ගයක් ඇත. වර්ගීකරණය **නිශ්චිත** සහ **අසාර්ථක-වසා දැමූ** වේ — වර්ගීකරණය කළ නොහැකි ඕනෑම දෙයක් `MANAGEMENT` ලෙස අවසන් වන අතර සැසියක් හෝ කළමනාකරණ-ශ්රේණියේ ටෝකනයක් ඉල්ලා සිටී. මෙම පිටුව මාර්ග නඩත්තු කරන හෝ නව අවසන් ලක්ෂ්ය සැලසුම් කරන ඉංජිනේරුවන් සඳහා ආකෘතිය පැහැදිලි කරයි.

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> මූලාශ්රය: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Aut Modes දෙකක්

### 1. API යතුර (දරන්නා)

යතුරට `manage` විෂය පථය ඇති විට OpenAI/Anthropic/Gemini-compatible සේවාලාභියා APIs සහ කළමනාකරණ මාර්ග කිහිපයක් සඳහා භාවිතා වේ.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` හි `isValidApiKey()` / `extractApiKey()` මගින් වලංගු කර `src/shared/utils/apiAuth.ts` හරහා ප්‍රති අපනයනය කෙරේ. වලංගුකාරකය `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ස්ථීර පාස්ත්‍රෝ යතුරු ලෙස ද පිළිගනී (නිකුතුව #1350).

### 2. උපකරණ පුවරු සැසිය (auth_token කුකිය)

උපකරණ පුවරු පිටු සහ පරිපාලක මෙහෙයුම් සඳහා.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

කුකියක් සැසියක් වන්නේ JWT සත්‍යාපනය කරන විට පමණි** සහ** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) දරයි. කුකියේ සෑම පාරිභෝගිකයෙක්ම (උපකරණ පුවරුවේ මාර්ග ආරක්ෂකයා (`isDashboardSessionAuthenticated()`), authz නල මාර්ග නැවුම් කිරීම, WebSocket අතට අත දීම, සජීවී සේවාදායකය, `/api/settings/require-login`, `/api/auth/status`) එම සහායකයා හරහා ගමන් කරයි. `JWT_SECRET` සමඟ අත්සන් කර ඇති අනෙකුත් JWTs පවතිනුයේ — Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` යතුරු දරන්නන් සඳහා — ටෝකන වන අතර ඒවා කිසිදා සැසි නොවේ (#13298).

`src/shared/utils/apiAuth.ts` හි `isDashboardSessionAuthenticated()` මගින් සත්‍යාපනය කර ඇත. එහි දින 30ක ආයු කාලය තුළ දින 7කට වඩා අඩු කාලයක් ඉතිරිව ඇති විට නල මාර්ගය JWT ස්වයංක්‍රීයව නැවුම් කරයි.

සැසියක් එහි දින 30 අවසන් වීමට පෙර අවසන් විය හැක, මන්ද සෑම minter එකක්ම `mintDashboardSessionToken` (නිකුත් කිරීමේ වේලාවක් `iat` සහ id `jti`) හරහා යන නිසා සහ සත්‍යාපකය විසින් සිටුවම් දෙකක් පරීක්ෂා කරයි: `sessionsValidAfter`, මුරපද වෙනස් කිරීමකින් සකසා ඇති නිසා එය සත්‍යාපනය කිරීම නැවැත්වීමට පෙර නිකුත් කරන ලද සෑම සැසියකටම (මුරපදය වෙනස් කළ බ්‍රවුසරයට නැවුම් කුකියක් ලැබේ), සහ `revokedDashboardSessions` අත්සන් කළ සැසිය `jti` කිරීමට `POST /api/auth/logout` පැරණි නිකුතුවක් මඟින් සකස් කරන ලද සැසිවලට හිමිකම් පෑමක් සිදු නොවන අතර පළමු මුරපදය වෙනස් වන තෙක් වලංගු වේ. සැකසුම් කියවිය නොහැකි නම්, සැසිය විශ්වාස නොවේ.

සමහර කළමනාකරණ මාර්ග පිළිගනී** එක්කෝ** මාදිලිය: API යතුරෙහි `manage` (හෝ `admin`) විෂය පථය ඇති විට කුකී OR `Bearer <key>`. v3.8 හි එකතු කරන ලද " API ඇමතුම් හරහා වින්‍යාසගත කළ හැකි" කාර්ය ප්‍රවාහය සක්‍රීය කරන්නේ මෙයයි.

#### විකල්ප OIDC පිවිසුම් දොරටුව (#6973)

උපකරණ පුවරු පරිපාලක පිවිසුම ද සහාය දක්වයි** තේරීම** OIDC (OpenID Connect) ප්‍රවාහය පෙරනිමි මුරපද ලොගින් — මුරපද ප්‍රවිෂ්ටය කිසිවිටක ඉවත් නොකෙරේ, පරිපූරක පමණි:

- `settings.oidcEnabled === true` හැර අබල කර ඇත** සහ** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` සියල්ල වින්‍යාස කර ඇත (සැකසීම් → Auth). `GET /api/auth/oidc/login` වෙනත් ආකාරයකින් `400` ලබා දෙයි.
- `GET /api/auth/oidc/login` නිකුත් කරන්නාගේ `/.well-known/openid-configuration` වෙතින් `authorization_endpoint` සොයා ගනී (ආපසු `<issuer>/authorize` වෙත වැටේ), ලැබෙන ඉල්ලීමෙන් (`x-forwarded-proto` -aware) යළි-යොමුවීම් URI ගොඩනඟයි, සහ `httpOnly` `oidc_state` කුකියක ගබඩා කර ඇති අහඹු `state` සමඟ IdP වෙත යළි-යොමු කරයි.
- `GET /api/auth/oidc/callback` `state` වලංගු කරයි, අවසර කේතය හුවමාරු කරයි, සහ `issuer`/`audience` චෙක්පත් සමඟ නිකුත් කරන්නාගේ JWKS (`jose`'s `createRemoteJWKSet`, JWKS URI සඳහා හැඹිලිගත කර ඇත) හරහා ID ටෝකනයේ අත්සන සත්‍යාපනය කරයි. උපකරණ පුවරු ඇතුළත් කිරීම සඳහා හිස් නොවන `oidcAllowedSubjects` ලැයිස්තුවක්, `oidcAdmissionClaim` ප්‍රතිපත්තියක් හෝ දෙකම අවශ්‍ය වේ. විෂය ලැයිස්තුව `sub` හෝ `email` සමඟ ගැළපෙන්නේ `email_verified === true` විට පමණි. විකල්ප හිමිකම් ප්‍රතිපත්තිය තිත්-වෙන් වූ ID-ටෝකන හිමිකම් මාර්ගයක් (උදාහරණයක් ලෙස, `realm_access.roles`) සහ පිළිගත් අගයන් අරාවක් ගනී; විසඳන ලද හිමිකම් පෑම අවම වශයෙන් එක් පිළිගත් අගයක් අඩංගු තන්තු මාලාවක් විය යුතුය. ප්‍රතිපත්ති දෙකම වින්‍යාස කර ඇත්නම්, දෙකම සමත් විය යුතුය. Missing/malformed හිමිකම් අසාර්ථක වන අතර, ප්‍රතිපත්ති දෙකකින් තොරව ආපසු ඇමතුම ප්‍රතික්ෂේප කරයි (`not_configured`). පවතින විෂය-පමණි වින්‍යාසයන් නොවෙනස්ව පවතී.
- Keycloak සාමාන්‍යයෙන් ක්ෂේත්‍ර භූමිකාවන් ප්‍රවේශ ටෝකන බවට සිතියම්ගත කරයි, අවශ්‍යයෙන්ම ID ටෝකන නොවේ. ප්‍රදේශයේ භූමිකාව `admin` අවශ්‍ය කිරීමට, මෙම සේවාදායකයා සඳහා එහි `realm_access.roles` ඇතුළත් ප්‍රොටෝකෝල සිතියම්කරුවෙකු වින්‍යාස කරන්න**ID ටෝකනය** , ඉන්පසු `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` ලෙස සකසන්න. භූමිකාව-පමණි ඇතුළත් කිරීම සබල කිරීමට පෙර මෙම සේවාදායකයා සඳහා සැබෑ ID-ටෝකන හිමිකම් පෑම පරීක්ෂා කරන්න; යෙදුම ප්‍රවේශ-ටෝකන් භූමිකාවන් කියවන්නේ නැත. IdP-පාර්ශවීය ටෝකන් ප්‍රතික්ෂේප කිරීම අතිරේක කළ හැකි නමුත් මෙම යෙදුම-පැති පරීක්ෂාව ප්‍රතිස්ථාපනය නොකරයි.
- සාර්ථකත්වය මත එය mints the** හරියටම සමාන** දින 30 `auth_token` JWT මුරපද පිවිසුම් ගැටළු (`src/app/api/auth/login/route.ts`), එබැවින් උපකරණ පුවරුවේ සැසි නල මාර්ගයේ ඉතිරි කොටස (ස්වයං-නැවුම්, කුකී කොඩි) නොවෙනස්ව පවතී — OIDC ප්‍රතිස්ථාපනය කරන්නේ කුකිය මින්ට් කරන ආකාරය මිස එය ලබා දෙන දේ නොවේ. IdP roles/groups හි වෙනස්කම් පවතින OmniRoute සැසි අවලංගු නොකරයි; පිටවීම, මුරපද භ්‍රමණය හෝ සැසිය කල් ඉකුත්වීම තවමත් ඔවුන්ගේ ජීවිත කාලය පාලනය කරයි.
- සෑම `oidc*` සැකසුමක්ම (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` හි ඇත (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` `400 PASSWORD_REQUIRED` පිළිතුරු දෙයි, එය කළමනාකාරීත්වය වැරදි ලෙස ශරීරය රැගෙන ගියහොත් මිස ( `currentPassword` `401 PASSWORD_MISMATCH` ). `oidcDisablePasswordLogin` මුරපදය _login_ ප්‍රතික්ෂේප කරයි (`POST /api/auth/login`) නමුත් ගබඩා කර ඇති මුරපද හැෂ් තබා ගන්නා අතර නැවත සත්‍යාපනය තවමත් එයට එරෙහිව `currentPassword` පරීක්ෂා කරයි.
- `corsOrigins` සහ `bruteForceProtection` `SECURITY_IMPACTING_SETTINGS_KEYS` හි ද ඇත: ලිහිල් කිරීම එක්කෝ පිවිසුම් ආරක්‍ෂාව දුර්වල කරයි, එබැවින් ඔවුන් එකම `currentPassword` නැවත සත්‍යාපනය ලබා ගනී (ආරක්ෂක පටිත්ත එය ඉල්ලයි) සහ JSON ආයාත කිරීම ඒවා පහත හෙළයි.
- සෑම ආරක්ෂක-ප්‍රතිපත්ති යතුරක්ම — `SECURITY_IMPACTING_SETTINGS_KEYS` ඇතුළත් කිරීම්, සෑම `oidc*` යතුරක්ම සහ උපකරණ පුවරු සැසි රාජ්‍ය — වේ** ක්රියාකරු-පමණි** `PATCH /api/settings` මත : කළමනාකරණය-පථය සහිත API යතුරක් හෝ `oma_` ප්‍රවේශ ටෝකනයක් එය නිවැරදි `currentPassword` යවන විට පවා `403` සමඟ ප්‍රතික්ෂේප කරනු ලබන අතර, ප්‍රතික්ෂේප කිරීම `reason: OPERATOR_REQUIRED` සමඟ `settings.update_failed` ලෙස විගණනය කරනු ලැබේ ( `src/lib/api/operatorCredential.ts` හි`requireOperatorCredential()` ). සාමාන්‍ය සැකසුම් (තේමාව, සංදර්ශක මනාප) `manage` යතුරක් හෝ `admin` ප්‍රවේශ ටෝකනයක් සඳහා ලිවිය හැකිව පවතී. `/api/settings` හි සෑම විකෘතියකටම (සහ `/api/settings/require-login` හි) `admin` ප්‍රවේශ-ටෝකන විෂය පථය ද අවශ්‍ය වේ ( `src/server/authz/accessScopes.ts` හි`ADMIN_MUTATION_EXACT_PATHS`, නියම-මාර්ග ගැලපීම); `GET` රැඳී සිටින්නේ `read`, සහ අනෙකුත් `/api/settings/*` උප මාර්ග (ප්‍රොක්සි, කොම්බෝ පෙරනිමි, ආකෘති අන්වර්ථ, සම්පීඩනය, පවිත්‍ර කිරීම්...) ක්‍රම-අනුමාන කළ `write` විෂය පථය තබා ගන්න.
- `POST /api/settings/import-json` එම නැවත සත්‍යාපනය මඟ හරියි, එබැවින් එය ලිවීමට පෙර `IMPORT_STRIPPED_SETTINGS_KEYS` (එකම ගොනුව) හි සෑම යතුරක්ම පහත දමයි: මුරපදය සහ `currentPassword`, සෑම `SECURITY_IMPACTING_SETTINGS_KEYS` ප්‍රවේශයක්ම සහ උපකරණ පුවරු සැසි තත්ත්වය (`sessionsValidAfter`, `revokedDashboardSessions`). පැරණි උපස්ථයක් ආයාත කිරීමෙන් මුරපදය වෙනස් කිරීමක් හෝ වරනයක් දැනටමත් අවසන් වී ඇති සැසියක් නැවත පණ ගැන්වීමට නොහැක.

#### විකල්ප TOTP ද්වි-සාධක පිවිසුම (#16619)

සැකසීම් → ආරක්‍ෂාවෙන් ලියාපදිංචි විය; ක්‍රියාකරු එය ක්‍රියාත්මක කරන තුරු අක්‍රිය කරන්න (`src/server/auth/dashboardMfa.ts`).

- **එය ආවරණය කරන දේ:** මුරපද පිවිසුම (`POST /api/auth/login`, එවිට `POST /api/auth/mfa/verify` අවශ්‍ය වේ) සහ `omniroute connect` (`POST /api/cli/connect`, මුරපදය පමණක් හුවමාරු කිරීම ප්‍රතික්ෂේප කරන අතර කේතය `totp` ලෙස ගනී).
- **එය ආවරණය නොකරන දේ:** OIDC / SSO පුරනය වීම (`/api/auth/oidc/callback`) OmniRoute TOTP ඉල්ලන්නේ නැත. එය අනන්‍යතා සපයන්නාගේම දෙවන සාධකය මත රඳා පවතී, එබැවින් OIDC සක්‍රීය කර ඇත්නම් IdP තුළ MFA බලාත්මක කරන්න.
- **ප්රකෘතිමත් වීම** (අහිමි වූ උපාංගය, ප්‍රතිසාධන කේත ඉතිරිව නැත, හෝ තවදුරටත් සත්‍යාපනය කළ නොහැකි සාධකයක්, උදාහරණයක් ලෙස `STORAGE_ENCRYPTION_KEY` වෙනස් වූ පසු):
  1. `OMNIROUTE_DISABLE_MFA=true` සමඟ සේවාදායකය නැවත ආරම්භ කරන්න.
  2. ධාරකයේදීම (loopback peer සහ loopback `Host`, `http://localhost:20128` වැනි), මුරපදය සමඟින් පුරනය වන්න. දෙවන සාධකය මඟ හැරෙන්නේ එම සම්භවය සඳහා පමණි; අනෙක් සෑම සම්භවයක්ම තවමත් කේතය අවශ්‍ය වේ.
  3. සැකසීම් තුළ → Security → Disable, මුරපදය ඇතුළත් කර කේතය හිස්ව තබන්න. `POST /api/auth/mfa/disable` `code` නොමැති ශරීරයක් පිළිගනු ලබන්නේ විචල්‍යය සකසා ඇති අතර ඉල්ලීම සත්කාරකයෙන් ලැබෙන විට පමණි; එයට තවමත් උපකරණ පුවරුවේ සැසිය සහ වත්මන් මුරපදය අවශ්‍ය වන අතර `auth.mfa.disabled` ලෙස විගණනය කෙරේ `secondFactor: "recovery_switch"`.
  4. `OMNIROUTE_DISABLE_MFA` සැකසීම ඉවත් කරන්න, නැවත ආරම්භ කරන්න, සහ අවශ්‍ය නම් නැවත ලියාපදිංචි වන්න.

## මාර්ග පන්ති

`src/server/authz/types.ts` පන්ති තුනක් අර්ථ දක්වයි; තීරණාත්මකව වර්ගීකරණය කළ නොහැකි ඕනෑම මාර්ගයක් `MANAGEMENT` වෙත ආපසු වැටේ.

| පන්තිය       | විස්තරය                                                                                                                                             | සත්‍යාපනය අවශ්‍ය වේ                                           |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| `PUBLIC`     | පැහැදිලිවම ආරක්ෂිත මාර්ග — පිවිසීම, පිටවීම, තත්ත්වය, ආරම්භය, සෞඛ්‍යය, ඔන්බෝඩින් බූට්ස්ට්‍රැප්.                                                      | නැත                                                           |
| `CLIENT_API` | ආකෘති-සේවා endpoints — `/api/v1/*`, `/api/v1beta/*`, සහ අන්වර්ථ නාම `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | ඵලදායී `REQUIRE_API_KEY` විශේෂාංග ධජය සක්‍රිය විට Bearer යතුර |
| `MANAGEMENT` | ඩෑෂ්බෝඩ් පිටු, සැකසුම්, සපයන්නන්, යතුරු, පරිපාලක සහ රෝග විනිශ්චය endpoints.                                                                         | ඩෑෂ්බෝඩ් සැසිය හෝ `manage` විෂය පථය සහිත Bearer               |

`MANAGEMENT` ක්‍රියා කිහිපයක් **ක්‍රියාකරු-පමණක්** වේ: `manage` යතුරක් ප්‍රමාණවත් නොවේ. ගබඩා කළ අක්තපත්‍ර නිර්යාත කිරීම (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), දැනට පවතින දත්ත මත උපස්ථයක් ප්‍රත්‍යාස්ථාපනය කිරීම (`dryRun=true` ඇතුළුව `POST /api/db-backups/import`, id අනුව `POST /api/db-backups` ප්‍රත්‍යාස්ථාපනය, `POST /api/settings/import-json`), ප්‍රත්‍යාස්ථාපන ලක්ෂ්‍ය විනාශ කිරීම (`DELETE /api/db-backups` පිරිසිදු කිරීම, සහ `PATCH /api/db-backups` — එය ස්ථාවර කරන රඳවා ගැනීම සෑම උපස්ථයකින් පසු ස්වයංක්‍රීය කප්පාදුව පාලනය කරන නිසා) ඩෑෂ්බෝඩ් සැසියක්, දේශීය CLI විෂයක්, හෝ පිවිසුම අක්‍රිය කිරීමක් අවශ්‍ය කරයි. සමමුහුර්තකරණ ටෝකනයක් නිකුත් කිරීම (`POST /api/sync/tokens`) සහ `admin` CLI ප්‍රවේශ ටෝකනයක් ටංකනය කිරීම (`POST /api/cli/tokens`) සෑම පිවිසුම් ප්‍රකාරයකම ඩෑෂ්බෝඩ් සැසියක් හෝ දේශීය CLI විෂයක් අවශ්‍ය කරයි. ඕනෑම විෂය පථයක API යතුරු සහ `oma_` ප්‍රවේශ ටෝකන මෙහෙයුම්කරු අක්තපත්‍ර නොවේ: එකක් අවශ්‍ය වන විට ඒවාට `403` ලැබේ. පරීක්ෂාව `src/lib/api/operatorCredential.ts` හි ඇත (`resolveOperatorCredential()` / `requireOperatorCredential()`). පිවිසුම් සැකසුම් වෙනස් කිරීමද ක්‍රියාකරු-පමණකි: `POST /api/settings/require-login` (කළමනාකරණ මුරපදය සකසන / `requireLogin` මාරු කරන) මුරපදයක් පවතින විට පමණක් එම අක්තපත්‍ර පිළිගනී — පළමු-ධාවන ආරම්භක කවුළුව (තවම මුරපදයක් නැත) වෙනස් නොවේ — සහ ඩෑෂ්බෝඩ් සැසියක් මුරපදය ප්‍රතිස්ථාපනය කිරීමට `currentPassword` යැවිය යුතුය (එය නැති හෝ වැරදි නම් `403`, `settings.update_failed` ලෙස විගණනය කෙරේ). දේශීය CLI සහ පිවිසුම අක්‍රිය කළ අවස්ථාව ප්‍රතිසාධන මාර්ගය තබා ගන්නා අතර, දෙකම දත්ත නාමාවලිය හිමි සත්කාරකයට බැඳී ඇති නිසා, එය නොමැතිව මුරපදයක් සැකසිය හැක.

## පයිප්ලයින්

```
ඇතුළුවන ඉල්ලීම → src/proxy.ts
  → src/server/authz/pipeline.ts හි runAuthzPipeline()
    1. විශ්වාසදායක අභ්යන්තර headers ඉවත් කරන්න (x-omniroute-auth-*, x-omniroute-route-class)
    2. ඉල්ලීම් id එක ජනනය කර, classifyRoute() හරහා route එක වර්ගීකරණය කරන්න
    3. pathname == "/" නම් → /dashboard වෙත redirect කරන්න
    4. draining (සුමට වසා දැමීම) සහ /api/* නම් → 503
    5. non-GET /api/* නම් → checkBodySize() guard පරීක්ෂා කරන්න
    6. OPTIONS නම් → CORS preflight 204
    7. options.enforce == false නම් → route-class headers සමඟ pass-through කරන්න
    8. එසේ නොමැතිනම්: POLICIES[routeClass].evaluate(ctx)
       - allow  → x-omniroute-auth-{kind,id,label,scopes} සලකුණු කර → NextResponse.next()
       - reject → correlation_id සහිත JSON දෝෂයක් (dashboard pages → 302 /login)
```

`src/server/authz/headers.ts` හි අර්ථ දක්වා ඇති විශ්වාසදායක අභ්යන්තර headers, වර්ගීකරණයට පෙර **ඇතුළුවන ඉල්ලීම්වලින් ඉවත් කරනු ලැබේ** — clients හට subject කෙනෙකු ලෙස ව්යාජ ලෙස පෙනී සිටීමට `x-omniroute-auth-*` පෙර-පිරවිය නොහැක.

### Policy ගිවිසුම්

සෑම route class එකකටම `src/server/authz/policies/` තුළ policy එකක් ඇත:

- **`publicPolicy`** (`policies/public.ts`) — සෑම විටම `allow({ kind: "anonymous", id: "anonymous" })` ලබා දෙයි.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — Bearer එක උපුටාගෙන, `validateApiKey()` හරහා වලංගු කරයි. සක්රීය `REQUIRE_API_KEY` feature flag එක අක්රිය කර ඇති විට පමණක් anonymous වෙත fallback වේ. සක්රීය flag එක `isRequireApiKeyEnabled()` හරහා විසඳනු ලැබේ (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), එබැවින් Dashboard Feature Flags සහ environment variables `/api/v1/*`, `/api/v1beta/*`, සහ aliases සඳහා එකම ආකාරයෙන් බලපායි; resolver අසමත් වුවහොත් ප්රවේශය ආරක්ෂිතව වසා දමනු ලැබේ. Client API routes මත dashboard-session requests සඳහාද අවසර දෙයි (`/api/v1/models` ඇතුළුව, එය dashboard model catalog එක භාවිත කරයි).
  Entra ID SSO සක්රීය කර ඇති විට, ව්යුහාත්මකව Entra token එකක් වන Bearer එකක් (base64url segments තුනක්, `RS*` alg එකක්, `kid`) `validateApiKey()` ට පෙර SSO branch එක මඟින් හසුරුවනු ලබන අතර එහි verdict එක අවසාන වේ — එය කිසිවිටෙක API-key path වෙත හෝ degrade-to-anonymous branch වෙත fallback නොවේ. එබැවින් identity-provider outage එකක් open access බවට පත්විය නොහැක. Static API keys වලට බලපෑමක් නැත. [Entra ID SSO](../security/ENTRA_SSO.md) බලන්න.
- **`managementPolicy`** (`policies/management.ts`) — dashboard session, අභ්යන්තර model-sync requests (`/api/providers/[name]/(sync-models|models)` සමඟ ගැළපෙන) පිළිගනී, නැතහොත් `isAuthRequired()` මඟින් false ලබා දෙන්නේ නම් සම්පූර්ණයෙන්ම මඟ හරියි. Bearer token එකක් තිබුණත් එය වලංගු නොවේ නම් 403 (`AUTH_001`) ලබා දෙයි; අනෙක් අවස්ථාවල 401 ලබා දෙයි. ඕනෑම auth branch එකකට පෙර route-guard tiers (LOCAL_ONLY / ALWAYS_PROTECTED) ද බලාත්මක කරයි — [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md) බලන්න. `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` හි ඇති LOCAL_ONLY paths (දැනට: `/api/mcp/`) වෙත Bearer key එක `manage` scope එක රැගෙන යන්නේ නම් non-loopback ස්ථානයකින් ප්රවේශ විය හැක; අනෙකුත් සියලුම LOCAL_ONLY paths scope එක නොසලකා strict-loopback ලෙස පවතී.

සාර්ථක policy එකක් `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` සහිත `AuthSubject` එකක් ලබා දෙයි. නැවත auth logic ධාවනය කිරීම වෙනුවට downstream handlers හට එය `src/server/authz/assertAuth.ts` හි `assertAuth(request, "CLIENT_API")` හරහා කියවිය හැක.

## පොදු මාර්ග ලැයිස්තුව

`src/shared/constants/publicApiRoutes.ts` යනු පැහැදිලි අවසර ලැයිස්තුවයි:

ලැයිස්තුව බෙදී ඇත** හැඩය** , සහ බෙදීම බර දරයි (GHSA-74g9-q8f6-793h): උපසර්ගයක් `startsWith()` සමඟ ගැලපේ, එබැවින් එය එහි ප්‍රමුඛ අක්ෂර බෙදා ගන්නා සෑම යාබද මාර්ගයකටම ගැලපේ. `/api/usage/om-usage` උපසර්ගයක් ලෙස `/api/usage/om-usage<anything>` PUBLIC ලෙස සලකුණු කර ඇති අතර, මීලඟට තමන්ගේම සත්‍යාපනයක් නොමැති හසුරුවන්නක් `/api/usage/[connectionId]` — ලෙස විසඳයි.

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

කියවීමට පමණක් මාර්ග පොදු වේ** පමණි** ආරක්ෂිත ක්රම සඳහා. සටහන: `classifyRoute()` `/api/v1/*` සහ `/api/v1beta/*` PUBLIC drop-through — වෙතින් බැහැර කරයි, ඒවා සැමවිටම `CLIENT_API` වේ, එබැවින් Bearer-key ප්‍රතිපත්තිය තවමත් අදාළ වේ.

## නව මාර්ගයක් එක් කිරීම

### රටාව 1 — පොදු සේවාලාභී API අන්ත ලක්ෂ්යය (Bearer-auth)

`/api/v1/` සහ `/api/v1beta/` යටතේ ඇති මාර්ග ස්වයංක්රීයව `CLIENT_API` ලෙස වර්ගීකරණය කෙරේ. Middleware එක Bearer පරීක්ෂාව බලාත්මක කරයි; මාර්ග හසුරුවනවලට එය නැවත සිදු කිරීමට අවශ්ය නැත, නමුත් ප්රයෝජනවත් නම් subject එක කියවිය හැක.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... හසුරුවන තර්කනය
}
```

### රටාව 2 — කළමනාකරණ අන්ත ලක්ෂ්යය (session හෝ Bearer + manage)

`src/lib/api/requireManagementAuth.ts` වෙතින් `requireManagementAuth()` භාවිත කරන්න:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... හසුරුවන තර්කනය
}
```

`requireManagementAuth()` සාර්ථක වූ විට `null` හෝ JSON දෝෂ `Response` එකක් ආපසු ලබා දෙයි:

- 401 `AUTH_001` "සත්යාපනය අවශ්යයි" — කිසිදු අක්තපත්රයක් නොමැත
- 403 — වලංගු නොවන Bearer එකක් **හෝ** Bearer එකක් තිබුණත් යතුරට `manage` / `admin` විෂය පථය නොමැත

`hasManageScope(scopes)` විසින් `"manage"` හෝ `"admin"` සඳහා true ලබා දෙයි.

### රටාව 3 — පොදු අවසර ලැයිස්තුවට එක් කිරීම

පහසුව අනුව නොව, හැඩය අනුව කට්ටලය තෝරන්න. එක් මාර්ගයක් `PUBLIC_API_ROUTES_EXACT` තුළට යයි (නැතහොත් GET සඳහා පමණක් නම් `PUBLIC_READONLY_CORS_API_ROUTES` තුළට); සැබෑ උපවෘක්ෂයක් පමණක් `PUBLIC_API_ROUTE_PREFIXES` තුළට යන අතර, එය **`/` අක්ෂරයෙන් අවසන් විය යුතුය**. තනි මාර්ගයක් උපසර්ග ලැයිස්තුවට දැමීමෙන්, පසුව එක් කරන ගතික-ඛණ්ඩ සහෝදර මාර්ග ඇතුළුව, එහි ආරම්භක අක්ෂර බෙදාගන්නා සෑම යාබද මාර්ගයක්ම ද ප්රකාශයට පත් වේ (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` සහ `tests/unit/authz/classify.test.ts` හි ඒකක පරීක්ෂණ යාවත්කාලීන කරන්න.

## විෂය පථ

අවකාශ තුනක්. එක් එක් පරීක්ෂකයා කියවන්නේ තමන්ගේම තන්තු පමණි.
`manage` `read:compression` සඳහා `scopeMatches` අසමත් වන්නේ ඇයිද යන්න සහ
`read` ප්රවේශ ටෝකනයකට `PATCH /api/keys/{id}` කළ නොහැක්කේ මන්ද යන්න ඇතුළුව,
පැත්තෙන් පැත්තට විස්තරය [අවකාශ නාමාවලිය තුනක්](../frameworks/MCP-SERVER.md#three-scope-namespaces) හි ඇත.

API යතුරු `scopes` අරාවක් දරයි (`api_keys.scopes` හි JSON ලෙස ගබඩා කර ඇත, `src/lib/db/apiKeys.ts` බලන්න).

### කළමනාකරණ විෂය පථය

- `manage` / `admin` — `hasManageScope`. කළමනාකරණ API මාර්ග වෙත Bearer ප්රවේශය.
- `mcp:connect`, `self:usage`, `self:account-quota`, සහ
  `policy:bypass-provider-quota` යනු එකතු කළ හැකි නිශ්චිත-ගැලපෙන විෂය පථ වේ. ඒවා
  `MANAGEMENT_API_KEY_SCOPES` වලින් පිටත පිහිටා ඇත. `mcp:connect` විවෘත කරන්නේ
  `/api/mcp/` non-loopback carve-out පමණි.

### MCP මෙවලම් විෂය පථ

නාමාවලිය සහ ගැලපෙන නීති (එකම තන්තුව, හෝ `*` වලින් අවසන් වන ලබා දුන් විෂය පථයක්):
[MCP මෙවලම් විෂය පථ](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`src/shared/constants/mcpScopes.ts` හි ඇති `MCP_SCOPE_LIST` යනු මුල් ටයිප් කරන ලද
උප කුලකය මිස සම්පූර්ණ නාමාවලිය නොවේ. බලාත්මක කිරීම
`open-sse/mcp-server/scopeEnforcement.ts` හි `resolveCallerScopeContext()`
MCP සත්යාපන තොරතුරු, ඉල්ලීම් පාර-දත්ත, හෝ `OMNIROUTE_MCP_SCOPES` වෙතින් විෂය පථ
විසඳීමෙන් පසුව ක්රියාත්මක වේ. `OMNIROUTE_MCP_ENFORCE_SCOPES=true` නොවන තාක් කල් එය
ක්රියා විරහිතව පවතී.

### ප්රවේශ-ටෝකන විෂය පථ

`oma_live_…` ටෝකන මත `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) මගින් ශ්රේණිගත කර ඇත. මෙම ශ්රේණිය අදාළ වන්නේ
ප්රවේශ-ටෝකන අක්තපත්රයට පමණි. [කළමනාකරණ සත්යාපනය](../guides/MANAGEMENT-AUTH.md) බලන්න.

## Auth අවශ්‍ය ටොගලය

`src/shared/utils/apiAuth.ts` හි `isAuthRequired()` මගින් ඕනෑම ඉල්ලීමක් සඳහා **ඕනෑම** සත්‍යාපනයක් බලාත්මක කළ යුතුද යන්න තීරණය කරයි:

- `settings.requireLogin === false` → සත්‍යාපනය ගෝලීයව අක්‍රියයි, මුල්-ආරක්ෂිත ස්ථරය ([Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) සහ එය පිළිගන්නා අක්තපත්‍රය ලබා දෙන ඇමතුම් හැර — ඒවාට පිවිසුම ක්‍රියාත්මක විට ලෙසම එම අක්තපත්‍රයක් අවශ්‍යයි: සමමුහුර්ත ටෝකන නිකුත් කිරීම, ඕනෑම විෂය පථයකින් CLI ප්‍රවේශ ටෝකන ටංකනය කිරීම, සහ `manage`/`admin` විෂය පථය සහිත API යතුරක් සෑදීම, එම විෂය පථය යතුරකට ලබාදීම, හෝ එවැනි යතුරක් යළි උත්පාදනය කිරීම හෝ හෙළි කිරීම (`src/lib/api/requireManagementAuth.ts` හි `requireCredentialForManagementScopedKey()`). ඇතුළත් කිරීම-පමණක් යතුරු විවෘතව පවතී.
- මුරපදයක් සකසා නොමැති **සහ** `INITIAL_PASSWORD` පරිසර විචල්‍යක් නොමැති → ආරම්භක මාදිලිය ඔන්බෝඩින් වීසාර්ඩය සහ loopback ඉල්ලීම් ඉඩ දෙයි, නමුත් නිරාවරණය වූ ජාල ඉල්ලීම්වලට තවමත් අක්තපත්‍ර අවශ්‍යයි.
- ඕනෑම DB දෝෂයක් → අසාර්ථක-වැසීම (ආරක්ෂිත-පෙරනිමිය).

Client API යතුරු බලාත්මක කිරීම `src/shared/utils/featureFlags.ts` හි `isRequireApiKeyEnabled()` භාවිතා කරයි, සෘජු `process.env.REQUIRE_API_KEY` කියවීමක් නොවේ. මෙය යෙදවූ උදාහරණ සඳහා වැදගත්ය: ඩෑෂ්බෝඩ් → Feature Flags හි `REQUIRE_API_KEY` ටොගල් කිරීම DB අභිබවා යාමක් ගබඩා කර `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` සහ මෙම උපයෝගිතාව බෙදාගන්නා අනෙකුත් client-API සත්‍යාපන පරීක්ෂා වලට වහාම බලපායි. විශේෂාංග ධජ ගබඩාව කියවිය නොහැකි නම්, client API සත්‍යාපනය අසාර්ථක-වැසෙන අතර යතුරක් අවශ්‍ය කරයි.

## පසුගාමී අනුකූලතාව බිඳ දමන වෙනස — v3.8.0

`/api/v1/agents/tasks/*` සහ `/api/resilience/model-cooldowns` අන්ත ලක්ෂ්ය සඳහා **දැන් කළමනාකරණ සත්යාපනය අවශ්ය වේ** (`588a0333` commit එක). මීට පෙර `manage` විෂය පථය නොමැති සාමාන්ය API යතුරක් යැවූ සේවාලාභීන්ට `403` ලැබේ. සංක්රමණය: API Keys dashboard එකෙන් යතුරට `manage` විෂය පථය නිකුත් කරන්න, නැතහොත් පුරනය වූ dashboard සැසියක් භාවිත කරන්න.

## හැසිරීම් වෙනස — v3.8.2

`/api/mcp/*` (දුරස්ථ MCP සේවාදායකය) පෙරනිමියෙන් තවමත් LOCAL_ONLY වන නමුත්, `Authorization: Bearer <api-key>` ශීර්ෂය තුළ `manage` විෂය පථය තිබේ නම් එය දැන් loopback නොවන ඉල්ලීම් පිළිගනී. මෙම ව්යතිරේකය `src/server/authz/routeGuard.ts` තුළ ඇති `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` හරහා එක් එක් මාර්ගය අනුව පැහැදිලිව පාලනය කෙරේ; එයට සම මට්ටමේ LOCAL_ONLY උපසර්ගය වන `/api/cli-tools/runtime/*` මඟ හැරිය නොහැකි ලෙස හිතාමතා සකසා ඇත, මන්ද එයට අභිමත උපක්රියාවලි ආරම්භ කළ හැකි බැවිනි. loopback නොවන ස්ථානවලින් `/api/mcp/*` වෙත එන නිර්නාමික ඉල්ලීම් දිගටම `403 LOCAL_ONLY` ආපසු ලබා දෙයි — ඕනෑම නව LOCAL_ONLY මාර්ගයක් සඳහා පෙරනිමිය දැඩි-loopback ලෙසම පවතී. [මාර්ග ආරක්ෂක ස්ථර](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) බලන්න.

## පරීක්ෂණ

- ඒකක පරීක්ෂණ: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- පොදු අවසර ලැයිස්තුව: `tests/unit/public-api-routes.test.ts`.
- ඉලක්කගතව ධාවනය කරන්න: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## දෝෂ නිදොස්කරණය

Pipeline එක සෑම ප්රතිචාරයකටම පහත ඒවා එක් කරයි:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

සත්යාපනය කළ ඉල්ලීම් සඳහා upstream (handler-side) ඉල්ලීම් headers තුළ පහත ඒවා ද ඇතුළත් වේ:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Handlers තුළ `assertAuth(req, expectedClass)` භාවිත කරන්න — middleware එක මඟහැරී ඇත්නම්, එය `AUTHZ_NOT_INITIALIZED` code එක සහිත `AuthzAssertionError` එකක් throw කරයි (tests තුළ configuration regressions හඳුනා ගැනීමට මෙය උපකාරී වේ).

## තවදුරටත් බලන්න

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — එක් එක් අන්ත ලක්ෂ්යය සඳහා සත්යාපන සලකුණ
- [COMPLIANCE.md](../security/COMPLIANCE.md) — සත්යාපන සිදුවීම් සඳහා විගණන ලොගය
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — විෂය පථ නාම අවකාශ තුනක් සහ MCP මෙවලම්-විෂය පථ නාමාවලිය
- මූලාශ්රය: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
