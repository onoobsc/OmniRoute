# Authorization Guide (മലയാളം)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **വിശ്വസനീയമായ ഉറവിടം:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **അവസാനം അപ്ഡേറ്റ് ചെയ്തത്:** 2026-09-22 — സ്കോപ്പ് നെയിംസ്പേസുകൾ MCP-SERVER.md-ലേക്ക് വിരൽ ചൂണ്ടുന്നു

ഓരോ API അഭ്യർത്ഥനകളെയും നിയന്ത്രിക്കുന്ന ഒരു റൂട്ട്-അവബോധമുള്ള ഓതറൈസേഷൻ പൈപ്പ്ലൈൻ OmniRoute-നുണ്ട്. വർഗ്ഗീകരണം **നിർണ്ണായകവും** **ഫെയിൽ-ക്ലോസ്ഡും** ആണ് — വർഗ്ഗീകരിക്കാൻ കഴിയാത്ത എന്തും `MANAGEMENT` ആയി മാറുകയും ഒരു സെഷനോ മാനേജ്മെൻ്റ്-ഗ്രേഡ് ടോക്കണോ ആവശ്യപ്പെടുകയും ചെയ്യും. റൂട്ടുകൾ പരിപാലിക്കുന്ന അല്ലെങ്കിൽ പുതിയ എൻഡ്പോയിന്റുകൾ രൂപകൽപ്പന ചെയ്യുന്ന എഞ്ചിനീയർമാർക്കായി ഈ പേജ് മോഡൽ വിശദീകരിക്കുന്നു.

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> ഉറവിടം: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## രണ്ട് ഓത്ത് മോഡുകൾ

### 1. API കീ (വാഹകൻ)

കീയ്ക്ക് `manage` സ്കോപ്പ് ഉള്ളപ്പോൾ OpenAI/Anthropic/Gemini-compatible ക്ലയൻ്റ് APIs നും കുറച്ച് മാനേജ്മെൻ്റ് റൂട്ടുകൾക്കും ഉപയോഗിക്കുന്നു.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` ൽ `isValidApiKey()` / `extractApiKey()` വഴി സാധൂകരിക്കുകയും `src/shared/utils/apiAuth.ts` വഴി വീണ്ടും കയറ്റുമതി ചെയ്യുകയും ചെയ്യുന്നു. സ്ഥിരമായ പാസ്ത്രൂ കീകളായി (ഇഷ്യൂ #1350) `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars-നെ വാലിഡേറ്റർ സ്വീകരിക്കുന്നു.

### 2. ഡാഷ്ബോർഡ് സെഷൻ (auth_token കുക്കി)

ഡാഷ്ബോർഡ് പേജുകൾക്കും അഡ്മിൻ പ്രവർത്തനങ്ങൾക്കും.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

JWT പരിശോധിച്ചുറപ്പിക്കുമ്പോൾ മാത്രമാണ് കുക്കി ഒരു സെഷൻ** ഒപ്പം** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) വഹിക്കുന്നു. കുക്കിയുടെ ഓരോ ഉപഭോക്താവും (ഡാഷ്ബോർഡ് റൂട്ട് ഗാർഡ് (`isDashboardSessionAuthenticated()`), authz പൈപ്പ്ലൈൻ പുതുക്കൽ, WebSocket ഹാൻഡ്ഷേക്ക്, ലൈവ് സെർവർ, `/api/settings/require-login`, `/api/auth/status`) ആ സഹായിയിലൂടെ കടന്നുപോകുന്നു. `JWT_SECRET` ഉപയോഗിച്ച് ഒപ്പിട്ട മറ്റ് JWTs — Cursor CLI പാസ്ത്രൂ കീ ഹോൾഡർമാർക്ക് `iss "omniroute" / aud "cursor-cli"` ടോക്കണുകൾ —, അവ ഒരിക്കലും സെഷനുകളല്ല (#13298).

`src/shared/utils/apiAuth.ts` ൽ `isDashboardSessionAuthenticated()` പരിശോധിച്ചുറപ്പിച്ചു. 30 ദിവസത്തെ ആയുസ്സിൽ 7 ദിവസത്തിൽ താഴെ മാത്രം ശേഷിക്കുമ്പോൾ പൈപ്പ്ലൈൻ JWT സ്വയമേവ പുതുക്കുന്നു.

ഒരു സെഷനും അതിൻ്റെ 30 ദിവസം കഴിയുന്നതിന് മുമ്പ് അവസാനിക്കും, കാരണം ഓരോ മിൻ്ററും `mintDashboardSessionToken` (ഒരു ഇഷ്യൂ ടൈം `iat`, ഒരു ഐഡി `jti`) വഴി പോകുകയും വെരിഫയർ രണ്ട് ക്രമീകരണങ്ങൾ പരിശോധിക്കുകയും ചെയ്യുന്നു: `sessionsValidAfter`, ഒരു പാസ്വേഡ് ഉപയോഗിച്ച് സജ്ജീകരിച്ചിരിക്കുന്നു, അതിനാൽ അത് പരിശോധിക്കുന്നത് നിർത്തുന്നതിന് മുമ്പ് പുറപ്പെടുവിച്ച എല്ലാ സെഷനും (പാസ്വേഡ് മാറ്റിയ ബ്രൗസറിന് ഒരു പുതിയ കുക്കി ലഭിക്കും), കൂടാതെ `revokedDashboardSessions` സെഷനിൽ സൈൻ ഔട്ട് ചെയ്ത സെഷൻ ചേർക്കുക `jti` `POST /api/auth/logout` ഒരു പഴയ റിലീസ് മുഖേന തയ്യാറാക്കിയ സെഷനുകൾക്ക് ക്ലെയിം ഇല്ല, ആദ്യ പാസ്വേഡ് മാറുന്നത് വരെ സാധുതയുള്ളതായി തുടരും. ക്രമീകരണങ്ങൾ വായിക്കാൻ കഴിയുന്നില്ലെങ്കിൽ, സെഷൻ വിശ്വസനീയമല്ല.

ചില മാനേജ്മെൻ്റ് റൂട്ടുകൾ അംഗീകരിക്കുന്നു** ഒന്നുകിൽ** മോഡ്: API കീയ്ക്ക് `manage` (അല്ലെങ്കിൽ `admin`) സ്കോപ്പ് ഉള്ളപ്പോൾ കുക്കി OR `Bearer <key>`. ഇതാണ് v3.8-ൽ ചേർത്ത " API കോളുകൾ വഴി ക്രമീകരിക്കാവുന്ന" വർക്ക്ഫ്ലോ പ്രവർത്തനക്ഷമമാക്കുന്നത്.

#### ഓപ്ഷണൽ OIDC ലോഗിൻ ഗേറ്റ് (#6973)

ഡാഷ്ബോർഡ് അഡ്മിൻ ലോഗിനും പിന്തുണയ്ക്കുന്നു** തിരഞ്ഞെടുക്കൽ** OIDC (OpenID Connect) ഫ്ലോ ഡിഫോൾട്ട് പാസ്വേഡ് ലോഗിൻ — പാസ്വേഡ് ലോഗിൻ ഒരിക്കലും നീക്കം ചെയ്യില്ല, അനുബന്ധമായി മാത്രം:

- `settings.oidcEnabled === true` അല്ലാത്തപക്ഷം പ്രവർത്തനരഹിതമാക്കി** ഒപ്പം** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` എല്ലാം ക്രമീകരിച്ചിരിക്കുന്നു (ക്രമീകരണങ്ങൾ → Auth). `GET /api/auth/oidc/login` അല്ലാത്തപക്ഷം `400` നൽകുന്നു.
- `GET /api/auth/oidc/login` ഇഷ്യൂവറുടെ `/.well-known/openid-configuration` യിൽ നിന്ന് `authorization_endpoint` കണ്ടെത്തുന്നു ( `<issuer>/authorize` ലേക്ക് മടങ്ങുന്നു), ഇൻകമിംഗ് അഭ്യർത്ഥനയിൽ നിന്ന് (`x-forwarded-proto` -aware) റീഡയറക്ട് URI നിർമ്മിക്കുന്നു, കൂടാതെ ഒരു `httpOnly` `oidc_state` കുക്കിയിൽ സംഭരിച്ചിരിക്കുന്ന ക്രമരഹിതമായ `state` ഉപയോഗിച്ച് IdP ലേക്ക് റീഡയറക്ട് ചെയ്യുന്നു.
- `GET /api/auth/oidc/callback` `state` സാധൂകരിക്കുന്നു, അംഗീകാര കോഡ് കൈമാറ്റം ചെയ്യുന്നു, കൂടാതെ `issuer`/`audience` ചെക്കുകൾ ഉപയോഗിച്ച് ഇഷ്യൂവറുടെ JWKS (`jose` ൻ്റെ `createRemoteJWKSet`, JWKS URI ന് കാഷെ ചെയ്തത്) വഴി ID ടോക്കണിൻ്റെ ഒപ്പ് പരിശോധിക്കുന്നു. ഡാഷ്ബോർഡ് പ്രവേശനത്തിന് ശൂന്യമല്ലാത്ത `oidcAllowedSubjects` ലിസ്റ്റോ ഒരു `oidcAdmissionClaim` നയമോ അല്ലെങ്കിൽ രണ്ടും ആവശ്യമാണ്. സബ്ജക്റ്റ് ലിസ്റ്റ് `sub` അല്ലെങ്കിൽ `email` എന്നിവയുമായി പൊരുത്തപ്പെടുന്നത് `email_verified === true` ആയിരിക്കുമ്പോൾ മാത്രം. ഓപ്ഷണൽ ക്ലെയിം പോളിസി ഒരു ഡോട്ട്-വേർതിരിക്കപ്പെട്ട ഐഡി-ടോക്കൺ ക്ലെയിം പാതയും (ഉദാഹരണത്തിന്, `realm_access.roles`) അംഗീകൃത മൂല്യങ്ങളുടെ ഒരു നിരയും എടുക്കുന്നു; പരിഹരിച്ച ക്ലെയിം കുറഞ്ഞത് ഒരു അംഗീകൃത മൂല്യമെങ്കിലും അടങ്ങിയിരിക്കുന്ന സ്ട്രിംഗുകളുടെ ഒരു നിരയായിരിക്കണം. രണ്ട് നയങ്ങളും കോൺഫിഗർ ചെയ്തിട്ടുണ്ടെങ്കിൽ, രണ്ടും പാസ്സാകണം. Missing/malformed ക്ലെയിമുകൾ പരാജയപ്പെട്ടു, കൂടാതെ ഒരു നയവുമില്ലാതെ കോൾബാക്ക് ലോഗിൻ നിരസിക്കുന്നു (`not_configured`). നിലവിലുള്ള വിഷയങ്ങൾ മാത്രമുള്ള കോൺഫിഗറേഷനുകൾ മാറ്റമില്ലാതെ തുടരുന്നു.
- കീക്ലോക്ക് സാധാരണയായി റിയൽ റോളുകളെ ആക്സസ് ടോക്കണുകളായി മാപ്പ് ചെയ്യുന്നു, ID ടോക്കണുകളല്ല. റിയൽ റോൾ `admin` ആവശ്യപ്പെടുന്നതിന്, ഈ ക്ലയൻ്റിനായി `realm_access.roles` ഉൾപ്പെടുന്ന ഒരു പ്രോട്ടോക്കോൾ മാപ്പർ കോൺഫിഗർ ചെയ്യുക**ID ടോക്കൺ** , തുടർന്ന് `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` ആയി സജ്ജമാക്കുക. റോൾ-ഒൺലി അഡ്മിഷൻ പ്രവർത്തനക്ഷമമാക്കുന്നതിന് മുമ്പ് ഈ ക്ലയൻ്റിനായുള്ള യഥാർത്ഥ ഐഡി-ടോക്കൺ ക്ലെയിം പരിശോധിക്കുക; ആപ്ലിക്കേഷൻ ആക്സസ്-ടോക്കൺ റോളുകൾ വായിക്കുന്നില്ല. ഐഡിപി-സൈഡ് ടോക്കൺ നിരസനം അനുബന്ധമായി നൽകാമെങ്കിലും ഈ ആപ്പ്-സൈഡ് ചെക്ക് മാറ്റിസ്ഥാപിക്കില്ല.
- വിജയത്തിൽ അത് മിണ്ടുന്നു** കൃത്യം** 30-ദിവസത്തെ `auth_token` JWT പാസ്വേഡ് ലോഗിൻ പ്രശ്നങ്ങൾ (`src/app/api/auth/login/route.ts`), അതിനാൽ ബാക്കിയുള്ള ഡാഷ്ബോർഡ് സെഷൻ പൈപ്പ്ലൈനുകൾ (ഓട്ടോ-റിഫ്രഷ്, കുക്കി ഫ്ലാഗുകൾ) മാറ്റമില്ലാത്ത — OIDC എന്നത് കുക്കി എങ്ങനെ നിർമ്മിക്കുന്നു എന്നതിനെ മാറ്റിസ്ഥാപിക്കുന്നു, അത് അനുവദിക്കുന്നതല്ല. IdP roles/groups ലേക്കുള്ള മാറ്റങ്ങൾ നിലവിലുള്ള OmniRoute സെഷനുകളെ അസാധുവാക്കുന്നില്ല; ലോഗ്ഔട്ട്, പാസ്വേഡ് റൊട്ടേഷൻ അല്ലെങ്കിൽ സെഷൻ കാലഹരണപ്പെടൽ എന്നിവ ഇപ്പോഴും അവരുടെ ജീവിതത്തെ നിയന്ത്രിക്കുന്നു.
- എല്ലാ `oidc*` ക്രമീകരണവും (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` ലാണ് (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` `400 PASSWORD_REQUIRED` ഉത്തരം നൽകുന്നു, അത് മാനേജ്മെൻ്റ് പാസ്വേഡ് തെറ്റായി ഉപയോഗിക്കുമ്പോൾ ( `currentPassword` `401 PASSWORD_MISMATCH` ) `oidcDisablePasswordLogin` പാസ്വേഡ് _login_ (`POST /api/auth/login`) നിരസിക്കുന്നു, പക്ഷേ സംഭരിച്ച പാസ്വേഡ് ഹാഷ് സൂക്ഷിക്കുന്നു, വീണ്ടും ഓത്ത് ഇപ്പോഴും `currentPassword` പരിശോധിക്കുന്നു.
- `corsOrigins`, `bruteForceProtection` `SECURITY_IMPACTING_SETTINGS_KEYS` യിലും ഉണ്ട്: ഒന്നുകിൽ അയവുള്ളതാക്കുന്നത് ലോഗിൻ പ്രതിരോധത്തെ ദുർബലമാക്കുന്നു, അതിനാൽ അവ അതേ `currentPassword` റീ-ഓത്ത് എടുക്കുന്നു (സെക്യൂരിറ്റി ടാബ് അത് ആവശ്യപ്പെടുന്നു) കൂടാതെ JSON ഇറക്കുമതി അവരെ ഡ്രോപ്പ് ചെയ്യുന്നു.
- എല്ലാ സുരക്ഷാ-നയ കീയും — `SECURITY_IMPACTING_SETTINGS_KEYS` എൻട്രികളും ഓരോ `oidc*` കീയും ഡാഷ്ബോർഡ് സെഷൻ സ്റ്റേറ്റ് — ആണ്** ഓപ്പറേറ്റർ-മാത്രം** `PATCH /api/settings` ൽ: ഒരു മാനേജ്-സ്കോപ്പ്ഡ് API കീ അല്ലെങ്കിൽ ഒരു `oma_` ആക്സസ് ടോക്കൺ ശരിയായ `currentPassword` അയയ്ക്കുമ്പോൾ പോലും `403` ഉപയോഗിച്ച് നിരസിക്കപ്പെടും, കൂടാതെ നിരസിക്കുന്നത് `reason: OPERATOR_REQUIRED` ഉപയോഗിച്ച് `settings.update_failed` ആയി ഓഡിറ്റ് ചെയ്യുന്നു ( `src/lib/api/operatorCredential.ts` ൽ `requireOperatorCredential()` ). സാധാരണ ക്രമീകരണങ്ങൾ (തീം, പ്രദർശന മുൻഗണനകൾ) ഒരു `manage` കീ അല്ലെങ്കിൽ ഒരു `admin` ആക്സസ് ടോക്കണിനായി എഴുതാവുന്നതായിരിക്കും. `/api/settings` യുടെ എല്ലാ മ്യൂട്ടേഷനും (ഒപ്പം `/api/settings/require-login` ൻ്റെയും) `admin` ആക്സസ്-ടോക്കൺ സ്കോപ്പ് ആവശ്യമാണ് ( `src/server/authz/accessScopes.ts` ലെ`ADMIN_MUTATION_EXACT_PATHS`, കൃത്യമായ-പാത്ത് പൊരുത്തം); `GET` സ്റ്റേകൾ `read`, മറ്റ് `/api/settings/*` ഉപ-റൂട്ടുകൾ (പ്രോക്സികൾ, കോംബോ ഡിഫോൾട്ടുകൾ, മോഡൽ അപരനാമങ്ങൾ, കംപ്രഷൻ, ശുദ്ധീകരണം...) രീതി അനുമാനിച്ച `write` സ്കോപ്പ് നിലനിർത്തുന്നു.
- `POST /api/settings/import-json` ആ റീ-ഓത്ത് ഒഴിവാക്കുന്നു, അതിനാൽ അത് എഴുതുന്നതിന് മുമ്പ് `IMPORT_STRIPPED_SETTINGS_KEYS` ൽ (അതേ ഫയൽ) എല്ലാ കീയും ഇടുന്നു: പാസ്വേഡും `currentPassword`, എല്ലാ `SECURITY_IMPACTING_SETTINGS_KEYS` എൻട്രിയും ഡാഷ്ബോർഡ് സെഷൻ അവസ്ഥയും (`sessionsValidAfter`, `revokedDashboardSessions`). ഒരു പഴയ ബാക്കപ്പ് ഇമ്പോർട്ടുചെയ്യുന്നതിലൂടെ ഒരു പാസ്വേഡ് മാറ്റമോ സൈൻ ഔട്ട് ഇതിനകം അവസാനിച്ചതോ ആയ ഒരു സെഷൻ പുനരുജ്ജീവിപ്പിക്കാൻ കഴിയില്ല.

#### ഓപ്ഷണൽ TOTP ടു-ഫാക്ടർ ലോഗിൻ (#16619)

ക്രമീകരണങ്ങൾ → സെക്യൂരിറ്റിയിൽ നിന്ന് എൻറോൾ ചെയ്തു; ഓപ്പറേറ്റർ അത് ഓണാക്കുന്നതുവരെ ഓഫ് ചെയ്യുക (`src/server/auth/dashboardMfa.ts`).

- **ഇത് എന്താണ് ഉൾക്കൊള്ളുന്നത്:** പാസ്വേഡ് ലോഗിൻ (`POST /api/auth/login`, അതിന് പിന്നീട് `POST /api/auth/mfa/verify` ആവശ്യമാണ്) കൂടാതെ `omniroute connect` (`POST /api/cli/connect`, ഇത് പാസ്വേഡ് മാത്രമുള്ള കൈമാറ്റം നിരസിക്കുകയും കോഡ് `totp` ആയി എടുക്കുകയും ചെയ്യുന്നു).
- **ഇത് ഉൾക്കൊള്ളാത്തത്:** OIDC / SSO സൈൻ-ഇൻ (`/api/auth/oidc/callback`) OmniRoute TOTP ആവശ്യപ്പെടുന്നില്ല. ഇത് ഐഡൻ്റിറ്റി പ്രൊവൈഡറുടെ സ്വന്തം രണ്ടാമത്തെ ഘടകത്തെ ആശ്രയിച്ചിരിക്കുന്നു, അതിനാൽ OIDC പ്രവർത്തനക്ഷമമാക്കിയിട്ടുണ്ടെങ്കിൽ IdP ൽ MFA നടപ്പിലാക്കുക.
- **വീണ്ടെടുക്കൽ** (നഷ്ടപ്പെട്ട ഉപകരണം, വീണ്ടെടുക്കൽ കോഡുകളൊന്നും അവശേഷിക്കുന്നില്ല, അല്ലെങ്കിൽ ഇനി പരിശോധിക്കാൻ കഴിയാത്ത ഒരു ഘടകം, ഉദാഹരണത്തിന് `STORAGE_ENCRYPTION_KEY` മാറ്റിയതിന് ശേഷം):
  1. `OMNIROUTE_DISABLE_MFA=true` ഉപയോഗിച്ച് സെർവർ പുനരാരംഭിക്കുക.
  2. ഹോസ്റ്റിൽ തന്നെ (ലൂപ്പ്ബാക്ക് പിയർ, ലൂപ്പ്ബാക്ക് `Host`, `http://localhost:20128` പോലുള്ളവ), പാസ്വേഡ് ഉപയോഗിച്ച് സൈൻ ഇൻ ചെയ്യുക. രണ്ടാമത്തെ ഘടകം ആ ഉത്ഭവത്തിന് മാത്രം ഒഴിവാക്കിയിരിക്കുന്നു; മറ്റെല്ലാ ഉത്ഭവത്തിനും ഇപ്പോഴും കോഡ് ആവശ്യമാണ്.
  3. ക്രമീകരണങ്ങളിൽ → Security → പ്രവർത്തനരഹിതമാക്കുക, പാസ്വേഡ് നൽകി കോഡ് ശൂന്യമായി വിടുക. വേരിയബിൾ സജ്ജീകരിച്ച് ഹോസ്റ്റിൽ നിന്ന് അഭ്യർത്ഥന വരുമ്പോൾ മാത്രമേ `POST /api/auth/mfa/disable` `code` ഇല്ലാത്ത ഒരു ബോഡി സ്വീകരിക്കുകയുള്ളൂ; ഇതിന് ഇപ്പോഴും ഡാഷ്ബോർഡ് സെഷനും നിലവിലെ പാസ്വേഡും ആവശ്യമാണ്, കൂടാതെ `auth.mfa.disabled` ആയി ഓഡിറ്റ് ചെയ്യപ്പെടുന്നു `secondFactor: "recovery_switch"`.
  4. `OMNIROUTE_DISABLE_MFA` അൺസെറ്റ് ചെയ്യുക, പുനരാരംഭിക്കുക, ആവശ്യമെങ്കിൽ വീണ്ടും എൻറോൾ ചെയ്യുക.

## റൂട്ട് ക്ലാസുകൾ

`src/server/authz/types.ts` മൂന്ന് ക്ലാസുകൾ നിർവചിക്കുന്നു; നിർണ്ണായകമായി വർഗ്ഗീകരിക്കാനാവാത്ത ഏതൊരു റൂട്ടും `MANAGEMENT` ലേക്ക് വീഴുന്നു.

| ക്ലാസ്       | വിവരണം                                                                                                                                                     | ഓതന്റിക്കേഷൻ ആവശ്യം                                                    |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `PUBLIC`     | വ്യക്തമായി സുരക്ഷിതമായ റൂട്ടുകൾ — ലോഗിൻ, ലോഗൗട്ട്, സ്റ്റാറ്റസ്, ഇനിഷ്യലൈസ്, ഹെൽത്ത്, ഓൺബോർഡിംഗ് ബൂട്ട്സ്ട്രാപ്പ്.                                          | ഒന്നുമില്ല                                                             |
| `CLIENT_API` | മോഡൽ-സേവന എൻഡ്‌പോയിന്റുകൾ — `/api/v1/*`, `/api/v1beta/*`, കൂടാതെ അലിയാസുകൾ `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | ഫലപ്രദമായ `REQUIRE_API_KEY` ഫീച്ചർ ഫ്ലാഗ് പ്രവർത്തനക്ഷമമായാൽ Bearer കീ |
| `MANAGEMENT` | ഡാഷ്‌ബോർഡ് പേജുകൾ, ക്രമീകരണങ്ങൾ, ദാതാക്കൾ, കീകൾ, അഡ്മിൻ, ഡയഗ്നോസ്റ്റിക്സ് എൻഡ്‌പോയിന്റുകൾ.                                                                 | ഡാഷ്‌ബോർഡ് സെഷൻ അല്ലെങ്കിൽ `manage` സ്കോപ്പുള്ള Bearer                 |

ചില `MANAGEMENT` പ്രവർത്തനങ്ങൾ **ഓപ്പറേറ്റർ-മാത്രം** ആണ്: `manage` കീ മതിയാകില്ല. സൂക്ഷിച്ച ക്രെഡൻഷ്യലുകൾ എക്സ്പോർട്ട് ചെയ്യൽ (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), ലൈവ് ഡാറ്റയ്ക്ക് മുകളിൽ ബാക്കപ്പ് പുനഃസ്ഥാപിക്കൽ (`dryRun=true` ഉൾപ്പെടെ `POST /api/db-backups/import`, ID വഴി പുനഃസ്ഥാപിക്കുന്ന `POST /api/db-backups`, `POST /api/settings/import-json`), പുനഃസ്ഥാപന പോയിന്റുകൾ നശിപ്പിക്കൽ (`DELETE /api/db-backups` ക്ലീനപ്പ്, കൂടാതെ `PATCH /api/db-backups` കാരണം അത് സംരക്ഷിക്കുന്ന റിട്ടൻഷൻ ഓരോ ബാക്കപ്പിന് ശേഷവും ഓട്ടോമാറ്റിക് പ്രൂണിംഗിനെ നയിക്കുന്നു) എന്നിവയ്ക്കെല്ലാം ഡാഷ്‌ബോർഡ് സെഷൻ, പ്രാദേശിക CLI വിഷയം, അല്ലെങ്കിൽ ലോഗിൻ പ്രവർത്തനരഹിതമാകൽ എന്നിവ വേണം. സിങ്ക് ടോക്കൺ നൽകുന്നത് (`POST /api/sync/tokens`) കൂടാതെ `admin` CLI ആക്സസ് ടോക്കൺ നിർമ്മിക്കുന്നത് (`POST /api/cli/tokens`) ഓരോ ലോഗിൻ മോഡിലും ഡാഷ്‌ബോർഡ് സെഷനോ പ്രാദേശിക CLI വിഷയമോ ആവശ്യപ്പെടുന്നു. ഏത് സ്കോപ്പിലെയും API കീകളും `oma_` ആക്സസ് ടോക്കണുകളും ഓപ്പറേറ്റർ ക്രെഡൻഷ്യലുകളല്ല: ആവശ്യമായപ്പോഴെല്ലാം അവയ്ക്ക് `403` ലഭിക്കും. ഈ പരിശോധന `src/lib/api/operatorCredential.ts` ലാണ് (`resolveOperatorCredential()` / `requireOperatorCredential()`). ലോഗിൻ ക്രമീകരണങ്ങൾ മാറ്റുന്നതും ഓപ്പറേറ്റർ-മാത്രമാണ്: പാസ്‌വേഡ് നിലവിലുണ്ടായാൽ `POST /api/settings/require-login` (മാനേജ്‌മെന്റ് പാസ്‌വേഡ് സജ്ജമാക്കൽ / `requireLogin` ടോഗിൾ) ഈ ക്രെഡൻഷ്യലുകൾ മാത്രമേ സ്വീകരിക്കൂ — ആദ്യ റൺ ബൂട്ട്സ്ട്രാപ്പ് വിൻഡോ (പാസ്‌വേഡ് ഇതുവരെ ഇല്ലാത്തപ്പോൾ) മാറ്റമില്ലാതെ തുടരുന്നു — പാസ്‌വേഡ് മാറ്റിസ്ഥാപിക്കാൻ ഡാഷ്‌ബോർഡ് സെഷൻ `currentPassword` അയയ്ക്കണം (അത് ഇല്ലെങ്കിലോ തെറ്റാണെങ്കിലോ `403`, `settings.update_failed` ആയി ഓഡിറ്റ് ചെയ്യപ്പെടുന്നു). പ്രാദേശിക CLIയും ലോഗിൻ പ്രവർത്തനരഹിതമായ ഇൻസ്റ്റൻസും വീണ്ടെടുക്കൽ പാത നിലനിർത്തുന്നു, അതില്ലാതെയും പാസ്‌വേഡ് സജ്ജമാക്കാം, കാരണം രണ്ടും ഡാറ്റാ ഡയറക്ടറി ഉടമസ്ഥതയുള്ള ഹോസ്റ്റിനോട് ബന്ധിതമാണ്.

## പൈപ്പ്ലൈൻ

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

വിശ്വസനീയമായ ആന്തരിക തലക്കെട്ടുകളാണ് ( `src/server/authz/headers.ts` യിൽ നിർവചിച്ചിരിക്കുന്നത്).** ഇൻകമിംഗ് അഭ്യർത്ഥനകളിൽ നിന്ന് നീക്കം ചെയ്തു** വർഗ്ഗീകരണത്തിന് മുമ്പ് — ക്ലയൻ്റുകൾക്ക് ഒരു വിഷയമായി ആൾമാറാട്ടം നടത്താൻ `x-omniroute-auth-*` മുൻകൂട്ടി പോപ്പുലേറ്റ് ചെയ്യാൻ കഴിയില്ല.

### നയ കരാറുകൾ

ഓരോ റൂട്ട് ക്ലാസിനും `src/server/authz/policies/` യിൽ ഒരു നയമുണ്ട്:

- **`publicPolicy`** (`policies/public.ts`) — എപ്പോഴും `allow({ kind: "anonymous", id: "anonymous" })` നൽകുന്നു.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — എക്സ്ട്രാക്ട് ബെയറർ, `validateApiKey()` വഴി സാധൂകരിക്കുന്നു. ഫലപ്രദമായ `REQUIRE_API_KEY` ഫീച്ചർ ഫ്ലാഗ് അപ്രാപ്തമാക്കുമ്പോൾ മാത്രമേ അജ്ഞാതനാകൂ. ഫലപ്രദമായ ഫ്ലാഗ് `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) വഴി പരിഹരിക്കപ്പെടുന്നു, അതിനാൽ ഡാഷ്ബോർഡ് ഫീച്ചർ ഫ്ലാഗുകളും പരിസ്ഥിതി വേരിയബിളുകളും `/api/v1/*`, `/api/v1beta/*`, അപരനാമങ്ങൾ എന്നിവ സ്ഥിരമായി നിയന്ത്രിക്കുന്നു; റിസോൾവർ പരാജയങ്ങൾ പരാജയപ്പെട്ടു. ക്ലയൻ്റ് API റൂട്ടുകളിൽ ഡാഷ്ബോർഡ്-സെഷൻ അഭ്യർത്ഥനകൾ അനുവദിക്കുന്നു (ഡാഷ്ബോർഡ് മോഡൽ കാറ്റലോഗ് ഉപയോഗിക്കുന്ന `/api/v1/models` ഉൾപ്പെടെ). Entra ID SSO പ്രവർത്തനക്ഷമമാക്കുമ്പോൾ, ഘടനാപരമായി ഒരു എൻട്രാ ടോക്കൺ (മൂന്ന് base64url സെഗ്മെൻ്റുകൾ, `RS*` alg, `kid`) ഒരു ബെയറർ കൈകാര്യം ചെയ്യുന്നത് SSO ബ്രാഞ്ചാണ്.** മുമ്പ്** `validateApiKey()`, അതിൻ്റെ വിധി അന്തിമ — ആണ്, ഇത് ഒരിക്കലും API-കീ പാഥിലേക്കോ ഡീഗ്രേഡ്-ടു-അജ്ഞാത ബ്രാഞ്ചിലേക്കോ വരുന്നില്ല, അതിനാൽ ഒരു ഐഡൻ്റിറ്റി പ്രൊവൈഡർ ഔട്ടേജ് ഓപ്പൺ ആക്സസ് ആകാൻ കഴിയില്ല. സ്റ്റാറ്റിക് API കീകളെ ബാധിക്കില്ല. [Entra ID SSO](../security/ENTRA_SSO.md) കാണുക.
- **`managementPolicy`** (`policies/management.ts`) — ഡാഷ്ബോർഡ് സെഷൻ, ആന്തരിക മോഡൽ-സമന്വയ അഭ്യർത്ഥനകൾ ( `/api/providers/[name]/(sync-models|models)` മായി പൊരുത്തപ്പെടുന്നു) സ്വീകരിക്കുന്നു അല്ലെങ്കിൽ `isAuthRequired()` തെറ്റായി നൽകുകയാണെങ്കിൽ പൂർണ്ണമായും ഒഴിവാക്കുന്നു. ഒരു ബെയറർ ടോക്കൺ നിലവിലുണ്ടെങ്കിലും അസാധുവാണെങ്കിൽ 403 (`AUTH_001`) നൽകുന്നു, അല്ലാത്തപക്ഷം 401. ഏതെങ്കിലും auth ബ്രാഞ്ചിന് മുമ്പ് റൂട്ട് ഗാർഡ് ടയറുകൾ (LOCAL_ONLY / ALWAYS_PROTECTED) നടപ്പിലാക്കുന്നു — [റൂട്ട് ഗാർഡ് ടയറുകൾ](../security/ROUTE_GUARD_TIERS.md) കാണുക. `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` ലെ LOCAL_ONLY പാതകൾ (ഇന്ന്: `/api/mcp/`) ബെയറർ കീ `manage` സ്കോപ്പ് വഹിക്കുമ്പോൾ നോൺ-ലൂപ്പ്ബാക്കിൽ നിന്ന് ആക്സസ് ചെയ്യാവുന്നതാണ്; മറ്റെല്ലാ LOCAL_ONLY പാതകളും വ്യാപ്തി പരിഗണിക്കാതെ കർശനമായ-ലൂപ്പ്ബാക്ക് ആയി തുടരുന്നു.

വിജയകരമായ ഒരു പോളിസി `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` നൊപ്പം `AuthSubject` നൽകുന്നു. ആധികാരിക ലോജിക് വീണ്ടും പ്രവർത്തിപ്പിക്കുന്നതിനുപകരം `src/server/authz/assertAuth.ts` ൽ `assertAuth(request, "CLIENT_API")` വഴി ഡൗൺസ്ട്രീം ഹാൻഡ്ലർമാർക്ക് ഇത് വായിക്കാനാകും.

## പൊതു റൂട്ടുകളുടെ പട്ടിക

`src/shared/constants/publicApiRoutes.ts` വ്യക്തമായ അനുവദനീയ പട്ടികയാണ്:

പട്ടിക വിഭജിച്ചിരിക്കുന്നു** ആകൃതി** , കൂടാതെ സ്പ്ലിറ്റ് ലോഡ്-ബെയറിംഗ് ആണ് (GHSA-74g9-q8f6-793h): ഒരു പ്രിഫിക്സ് `startsWith()` യുമായി പൊരുത്തപ്പെടുന്നു, അതിനാൽ അതിൻ്റെ മുൻനിര പ്രതീകങ്ങൾ പങ്കിടുന്ന എല്ലാ സമീപ പാതകളുമായും ഇത് പൊരുത്തപ്പെടുന്നു. `/api/usage/om-usage` ഒരു പ്രിഫിക്സായി `/api/usage/om-usage<anything>` PUBLIC എന്ന് അടയാളപ്പെടുത്തി, കൂടാതെ അടുത്തത് `/api/usage/[connectionId]` — സ്വന്തം ആധികാരികതയില്ലാത്ത ഒരു ഹാൻഡ്ലർ എന്ന് പരിഹരിക്കുന്നു.

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

വായന-മാത്രം വഴികൾ പൊതുവായതാണ്** മാത്രം** സുരക്ഷിതമായ രീതികൾക്കായി. കുറിപ്പ്: `classifyRoute()` `/api/v1/*`, `/api/v1beta/*` PUBLIC ഫാൾ-ത്രൂ — ൽ നിന്ന് ഒഴിവാക്കുന്നു, അവ എല്ലായ്പ്പോഴും `CLIENT_API` ആയതിനാൽ ബെയറർ-കീ നയം ഇപ്പോഴും ബാധകമാണ്.

## പുതിയൊരു Route ചേർക്കൽ

### മാതൃക 1 — പൊതു client API endpoint (Bearer-auth)

`/api/v1/`, `/api/v1beta/` എന്നിവയ്ക്കു കീഴിലുള്ള route-ുകൾ സ്വയമേവ `CLIENT_API` ആയി വർഗ്ഗീകരിക്കപ്പെടുന്നു. Middleware Bearer പരിശോധന നടപ്പാക്കുന്നു; route handler-ുകൾ അത് വീണ്ടും ചെയ്യേണ്ടതില്ല, എന്നാൽ പ്രയോജനകരമാണെങ്കിൽ subject വായിക്കാം.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... handler-ന്റെ logic
}
```

### മാതൃക 2 — Management endpoint (session അല്ലെങ്കിൽ Bearer + manage)

`src/lib/api/requireManagementAuth.ts`-ൽ നിന്നുള്ള `requireManagementAuth()` ഉപയോഗിക്കുക:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... handler-ന്റെ logic
}
```

വിജയിക്കുമ്പോൾ `requireManagementAuth()` `null` തിരികെ നൽകും; അല്ലെങ്കിൽ ഒരു JSON error `Response` നൽകും:

- 401 `AUTH_001` "Authentication required" — credentials ഒന്നും നൽകിയിട്ടില്ല
- 403 — അസാധുവായ Bearer **അല്ലെങ്കിൽ** Bearer നൽകിയിട്ടുണ്ടെങ്കിലും key-ക്ക് `manage` / `admin` scope ഇല്ല

`"manage"` അല്ലെങ്കിൽ `"admin"` ലഭിക്കുമ്പോൾ `hasManageScope(scopes)` true തിരികെ നൽകും.

### മാതൃക 3 — പൊതു allowlist-ലേക്ക് ചേർക്കൽ

സൗകര്യം നോക്കിയല്ല, ഘടന അനുസരിച്ച് set തിരഞ്ഞെടുക്കുക. ഒറ്റ route `PUBLIC_API_ROUTES_EXACT`-ലാണ് ചേർക്കേണ്ടത് (അല്ലെങ്കിൽ GET-only ആണെങ്കിൽ `PUBLIC_READONLY_CORS_API_ROUTES`-ൽ); യഥാർഥ subtree മാത്രം `PUBLIC_API_ROUTE_PREFIXES`-ൽ ചേർക്കുക, അത് **`/`-ൽ അവസാനിക്കുകയും വേണം**. ഒരു ഒറ്റ route prefix പട്ടികയിൽ ചേർത്താൽ, അതേ ആരംഭ അക്ഷരങ്ങൾ പങ്കിടുന്ന സമീപത്തുള്ള എല്ലാ path-കളും public ആകും — പിന്നീട് ചേർക്കുന്ന dynamic-segment sibling-ുകൾ ഉൾപ്പെടെ (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts`, `tests/unit/authz/classify.test.ts` എന്നിവയിലെ unit test-ുകൾ പുതുക്കുക.

## സ്കോപ്പുകൾ

മൂന്ന് നെയിംസ്പേസുകൾ. ഓരോ ചെക്കറും അതിൻ്റേതായ സ്ട്രിംഗുകൾ മാത്രമേ വായിക്കൂ. `manage` എന്തുകൊണ്ട് `read:compression` എന്നതിനായുള്ള `scopeMatches` പരാജയപ്പെടുത്തുന്നു, ഒരു `read` ആക്സസ് ടോക്കണിന് എന്തുകൊണ്ട് `PATCH /api/keys/{id}` ചെയ്യാൻ കഴിയില്ല എന്നതുൾപ്പെടെയുള്ള താരതമ്യം, [മൂന്ന് സ്കോപ്പ് നെയിംസ്പേസുകൾ](../frameworks/MCP-SERVER.md#three-scope-namespaces) എന്നതിൽ കാണുക.

API കീകൾ ഒരു `scopes` അറേ വഹിക്കുന്നു (`api_keys.scopes` എന്നതിൽ JSON ആയി സംഭരിച്ചിരിക്കുന്നു, `src/lib/db/apiKeys.ts` കാണുക).

### മാനേജ്മെൻ്റ് സ്കോപ്പ്

- `manage` / `admin` — `hasManageScope`. മാനേജ്മെൻ്റ് API റൂട്ടുകളിലേക്കുള്ള ബെയറർ ആക്സസ്.
- `mcp:connect`, `self:usage`, `self:account-quota`, കൂടാതെ `policy:bypass-provider-quota` എന്നിവ അഡിറ്റീവ് എക്സാക്റ്റ്-മാച്ച് സ്കോപ്പുകളാണ്. അവ `MANAGEMENT_API_KEY_SCOPES` എന്നതിന് പുറത്താണ്. `mcp:connect` എന്നത് `/api/mcp/` നോൺ-ലൂപ്പ്ബാക്ക് കാർവ്-ഔട്ട് മാത്രമേ തുറക്കൂ.

### MCP ടൂൾ സ്കോപ്പുകൾ

കാറ്റലോഗും പൊരുത്തപ്പെടുന്ന നിയമങ്ങളും (ഒരേ സ്ട്രിംഗ്, അല്ലെങ്കിൽ `*` എന്നതിൽ അവസാനിക്കുന്ന ഒരു അനുവദിച്ച സ്കോപ്പ്): [MCP ടൂൾ സ്കോപ്പുകൾ](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `src/shared/constants/mcpScopes.ts` എന്നതിലെ `MCP_SCOPE_LIST` എന്നത് യഥാർത്ഥ ടൈപ്പ് ചെയ്ത ഉപവിഭാഗമാണ്, ആ മുഴുവൻ കാറ്റലോഗല്ല. `resolveCallerScopeContext()` MCP ഓത്ത് വിവരങ്ങൾ, അഭ്യർത്ഥന മെറ്റാഡാറ്റ, അല്ലെങ്കിൽ `OMNIROUTE_MCP_SCOPES` എന്നിവയിൽ നിന്ന് സ്കോപ്പുകൾ പരിഹരിച്ച ശേഷം `open-sse/mcp-server/scopeEnforcement.ts` എന്നതിൽ എൻഫോഴ്സ്മെൻ്റ് പ്രവർത്തിക്കുന്നു. `OMNIROUTE_MCP_ENFORCE_SCOPES=true` അല്ലെങ്കിൽ ഇത് ഓഫായിരിക്കും.

### ആക്സസ്-ടോക്കൺ സ്കോപ്പുകൾ

`oma_live_…` ടോക്കണുകളിലെ `read` / `write` / `admin`, `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`) അനുസരിച്ച് റാങ്ക് ചെയ്തിരിക്കുന്നു. ഈ റാങ്ക് ആക്സസ്-ടോക്കൺ ക്രെഡൻഷ്യലിന് മാത്രമേ ബാധകമാകൂ. [മാനേജ്മെൻ്റ് ഓതൻ്റിക്കേഷൻ](../guides/MANAGEMENT-AUTH.md) കാണുക.

## ഓതന്റിക്കേഷൻ ആവശ്യം ടോഗിൾ

`src/shared/utils/apiAuth.ts` ലെ `isAuthRequired()` ഒരു റിക്വസ്റ്റിന് **ഏതെങ്കിലും** ഓതന്റിക്കേഷൻ ബാധകമാക്കണോ എന്ന് തീരുമാനിക്കുന്നു:

- `settings.requireLogin === false` → ഓതന്റിക്കേഷൻ ആഗോളതലത്തിൽ പ്രവർത്തനരഹിതം, എന്നാൽ എപ്പോഴും സംരക്ഷിതമായ ശ്രേണി (കാണുക [റൂട്ട് ഗാർഡ് ടിയറുകൾ](../security/ROUTE_GUARD_TIERS.md)) ഒഴികെ, കൂടാതെ അത് സ്വീകരിക്കുന്ന ക്രെഡൻഷ്യൽ നൽകുന്ന കോളുകൾ ഒഴികെ — ലോഗിൻ ഓണായിരിക്കുമ്പോൾ ആവശ്യമുള്ള അതേ ക്രെഡൻഷ്യൽ ഇവയ്ക്ക് വേണം: സിങ്ക് ടോക്കണുകൾ നൽകൽ, ഏത് സ്കോപ്പിലും CLI ആക്സസ് ടോക്കണുകൾ നിർമ്മിക്കൽ, `manage`/`admin` സ്കോപ്പുള്ള API കീ സൃഷ്ടിക്കൽ, ആ സ്കോപ്പ് ഒരു കീക്ക് നൽകൽ, അല്ലെങ്കിൽ അത്തരം കീ പുനർസൃഷ്ടിക്കൽ അല്ലെങ്കിൽ വെളിപ്പെടുത്തൽ (`src/lib/api/requireManagementAuth.ts` ലെ `requireCredentialForManagementScopedKey()`). ഇൻഫറൻസ്-മാത്രം കീകൾ തുറന്നു തന്നെ നിൽക്കുന്നു.
- പാസ്‌വേഡ് കോൺഫിഗർ ചെയ്തിട്ടില്ല **കൂടാതെ** `INITIAL_PASSWORD` എൻവയോൺമെന്റ് വേരിയബിളും ഇല്ല → ബൂട്ട്സ്ട്രാപ്പ് മോഡ് ഓൺബോർഡിംഗ് വിസാർഡും ലൂപ്പ്ബാക്ക് റിക്വസ്റ്റുകളും അനുവദിക്കുന്നു, എന്നാൽ തുറന്ന നെറ്റ്‌വർക്ക് റിക്വസ്റ്റുകൾക്ക് ഇപ്പോഴും ക്രെഡൻഷ്യലുകൾ വേണം.
- ഏത് DB പിശകും → ഫെയിൽ-ക്ലോസ്ഡ് (സുരക്ഷിത-സ്ഥിരസ്ഥിതി).

ക്ലയന്റ് API കീ നടപ്പാക്കൽ `src/shared/utils/featureFlags.ts` ലെ `isRequireApiKeyEnabled()` ഉപയോഗിക്കുന്നു, നേരിട്ടുള്ള `process.env.REQUIRE_API_KEY` വായന അല്ല. വിന്യസിച്ച ഇൻസ്റ്റൻസുകൾക്ക് ഇത് പ്രധാനമാണ്: ഡാഷ്‌ബോർഡ് → ഫീച്ചർ ഫ്ലാഗുകളിൽ `REQUIRE_API_KEY` ടോഗിൾ ചെയ്താൽ ഒരു DB ഓവർറൈഡ് സംഭരിക്കപ്പെടുകയും `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` എന്നിവയെയും ഈ ഹെൽപ്പർ പങ്കിടുന്ന മറ്റ് ക്ലയന്റ്-API ഓതന്റിക്കേഷൻ പരിശോധനകളെയും ഉടനടി ബാധിക്കുകയും ചെയ്യുന്നു. ഫീച്ചർ ഫ്ലാഗ് സ്റ്റോർ വായിക്കാനായില്ലെങ്കിൽ ക്ലയന്റ് API ഓതന്റിക്കേഷൻ ഫെയിൽ-ക്ലോസ്ഡ് ആയി മാറുകയും കീ ആവശ്യപ്പെടുകയും ചെയ്യുന്നു.

## ബ്രേക്കിംഗ് മാറ്റം — v3.8.0

`/api/v1/agents/tasks/*`, `/api/resilience/model-cooldowns` എന്നീ എൻഡ്പോയിന്റുകൾക്ക് **ഇപ്പോൾ മാനേജ്മെന്റ് ഓത്ത് ആവശ്യമാണ്** (കമ്മിറ്റ് `588a0333`). മുമ്പ് `manage` സ്കോപ്പ് ഇല്ലാത്ത ഒരു സാധാരണ API കീ അയച്ചിരുന്ന ക്ലയന്റുകൾക്ക് `403` ലഭിക്കും. മൈഗ്രേഷൻ: API Keys ഡാഷ്ബോർഡിൽ കീയ്ക്ക് `manage` സ്കോപ്പ് നൽകുക, അല്ലെങ്കിൽ ലോഗിൻ ചെയ്ത ഡാഷ്ബോർഡ് സെഷൻ ഉപയോഗിക്കുക.

## പെരുമാറ്റ മാറ്റം — v3.8.2

`/api/mcp/*` (റിമോട്ട് MCP സെർവർ) ഇപ്പോഴും ഡിഫോൾട്ടായി LOCAL_ONLY ആണ്, എന്നാൽ `Authorization: Bearer <api-key>` ഹെഡറിൽ `manage` സ്കോപ്പ് ഉണ്ടെങ്കിൽ ഇപ്പോൾ ലൂപ്പ്ബാക്ക് അല്ലാത്ത അഭ്യർത്ഥനകളും സ്വീകരിക്കുന്നു. `src/server/authz/routeGuard.ts`-ലെ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` വഴി ഓരോ പാത്തിനും ഈ ഒഴിവാക്കൽ വ്യക്തമായി നിയന്ത്രിക്കുന്നു; അനുബന്ധ LOCAL_ONLY പ്രിഫിക്സ് ആയ `/api/cli-tools/runtime/*`-ന് മനഃപൂർവം ഈ ബൈപാസ് അനുവദിച്ചിട്ടില്ല, കാരണം അതിന് ഏതുതരം സബ്പ്രോസസും സ്പോൺ ചെയ്യാൻ കഴിയും. ലൂപ്പ്ബാക്ക് അല്ലാത്ത ഇടങ്ങളിൽനിന്ന് `/api/mcp/*`-ലേക്കുള്ള അജ്ഞാത അഭ്യർത്ഥനകൾ തുടർന്നും `403 LOCAL_ONLY` നൽകും — ഏതൊരു പുതിയ LOCAL_ONLY പാത്തിനുമുള്ള ഡിഫോൾട്ട് കർശനമായ ലൂപ്പ്ബാക്ക് മാത്രമായി തുടരും. [റൂട്ട് ഗാർഡ് ടിയറുകൾ](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out) കാണുക.

## പരിശോധന

- യൂണിറ്റ് ടെസ്റ്റുകൾ: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- പൊതു അലൗലിസ്റ്റ്: `tests/unit/public-api-routes.test.ts`.
- കേന്ദ്രീകൃതമായി പ്രവർത്തിപ്പിക്കുക: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## ഡീബഗ്ഗിംഗ്

പൈപ്പ്ലൈൻ എപ്പോഴും പ്രതികരണങ്ങൾ ഉപയോഗിച്ച് സ്റ്റാമ്പ് ചെയ്യുന്നു:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

ആധികാരികമായ അഭ്യർത്ഥനകൾക്കായി അപ്സ്ട്രീം (ഹാൻഡ്ലർ-സൈഡ്) അഭ്യർത്ഥന തലക്കെട്ടുകളും ഉൾപ്പെടുന്നു:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

ഹാൻഡ്ലറുകൾ — ഉള്ളിൽ `assertAuth(req, expectedClass)` ഉപയോഗിക്കുക, മിഡിൽവെയർ ബൈപാസ് ചെയ്താൽ അത് `AUTHZ_NOT_INITIALIZED` കോഡ് ഉപയോഗിച്ച് `AuthzAssertionError` എറിയുന്നു (ടെസ്റ്റുകളിൽ കോൺഫിഗറേഷൻ റിഗ്രഷനുകൾ പിടിക്കാൻ സഹായകമാണ്).

## ഇതും കാണുക

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ഓരോ എൻഡ്പോയിന്റിനും വേണ്ടിയുള്ള ഓത്ത് മാർക്കർ
- [COMPLIANCE.md](../security/COMPLIANCE.md) — ഓത്ത് ഇവന്റുകൾക്കായുള്ള ഓഡിറ്റ് ലോഗ്
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — മൂന്ന് സ്കോപ്പ് നെയിംസ്പേസുകളും MCP ടൂൾ-സ്കോപ്പ് കാറ്റലോഗും
- ഉറവിടം: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
