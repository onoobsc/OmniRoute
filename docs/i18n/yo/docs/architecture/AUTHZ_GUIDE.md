# Authorization Guide (Yorùbá)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Orísun òtítọ́:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Ìgbà tó kẹ́yìn tí wọ́n ṣe àtúnṣe:** 2026-09-22 — àwọn orúkọ ààyè ìpele tọ́ka sí MCP-SERVER.md

OmniRoute ní ọ̀nà ìfọwọ́sí tó mọ ọ̀nà tó máa ń ṣàkóso gbogbo ìbéèrè API. Ìsọ̀rí jẹ́ **tí a lè pinnu** àti **tí kò lè kùnà** — ohunkóhun tí kò bá lè ṣe ìsọ̀rí yóò di `MANAGEMENT` yóò sì béèrè ìgbà kan tàbí àmì ìpele ìṣàkóso. Ojúewé yìí ṣàlàyé àwòrán fún àwọn onímọ̀-ẹ̀rọ tó ń tọ́jú àwọn ọ̀nà tàbí tó ń ṣe àwọn ibi ìparí tuntun.

![Ọ̀nà AuthZ (àwọn ìpele ọ̀nà 3 + ìṣàyẹ̀wò ètò)](../diagrams/exported/authz-pipeline.svg)

> Orísun: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Awọn ipo Auth Meji

### 1. Bọtini API (Agbẹru)

Ti a lo fun OpenAI/Anthropic/Gemini-compatible onibara APIs ati awọn ipa ọna iṣakoso diẹ nigbati bọtini naa ni aaye `manage` naa.

```
Authorization: Bearer <api-key>
```

Ti fọwọsi nipasẹ `isValidApiKey()` / `extractApiKey()` ni `src/sse/services/auth.ts` ati tun gbejade nipasẹ `src/shared/utils/apiAuth.ts`. Olufọwọsi naa tun gba `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars bi awọn bọtini itọpa itẹramọṣẹ (ọrọ #1350).

### 2. Ikoni Dasibodu (kuki_auth_token)

Fun awọn oju-iwe dasibodu ati awọn iṣẹ abojuto.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Kuki jẹ igba kan nikan nigbati JWT jẹri** ati** gbe `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Gbogbo olumulo ti kuki ( oluso ipa ọna dasibodu (`isDashboardSessionAuthenticated()`), authz pipeline refresh, WebSocket handshake, olupin laaye, `/api/settings/require-login`, `/api/auth/status`) lọ nipasẹ oluranlọwọ yẹn. JWTs miiran ti o fowo si pẹlu `JWT_SECRET` tẹlẹ — awọn Cursor CLI passthrough mints `iss "omniroute" / aud "cursor-cli"` àmi fun bọtini dimu — ati ki o ko si awọn akoko (#13298).

Jẹrisi nipasẹ `isDashboardSessionAuthenticated()` ni `src/shared/utils/apiAuth.ts`. Opo opo gigun ti epo n ṣe atunṣe JWT nigba ti o kere ju awọn ọjọ 7 ti o ku ni igbesi aye ọgbọn-ọjọ rẹ.

Igba kan tun le pari ṣaaju ki awọn ọjọ 30 rẹ ti lọ, nitori pe gbogbo minter lọ nipasẹ `mintDashboardSessionToken` (akoko ọrọ kan `iat` ati id `jti`) ati oludaniloju ṣayẹwo awọn eto meji: `sessionsValidAfter`, ti a ṣeto nipasẹ iyipada ọrọ igbaniwọle kan ki gbogbo igba ti o jade ṣaaju ki o to daduro ijẹrisi ( ẹrọ aṣawakiri ti o yi ọrọ igbaniwọle pada gba kuki tuntun), ati `revokedDashboardSessions`, eyiti `POST /api/auth/logout` ṣe afikun igba `jti` jade. Awọn akoko ti a ṣe nipasẹ itusilẹ agbalagba ko ni ẹtọ ati duro wulo titi di iyipada ọrọ igbaniwọle akọkọ. Ti awọn eto ko ba le ka, igba naa ko ni igbẹkẹle.

Diẹ ninu awọn ipa ọna iṣakoso gba** boya** mode: kukisi OR `Bearer <key>` nigbati bọtini API ni aaye `manage` (tabi `admin`). Eyi ni ohun ti o jẹ ki “atunto nipasẹ awọn ipe API ” ṣiṣiṣẹsẹhin ti a ṣafikun ni v3.8.

#### Iyanfẹ ẹnu-ọna iwọle OIDC (#6973)

Ibuwọlu abojuto dasibodu tun ṣe atilẹyin ẹya** ijade wọle** OIDC (Sopọ OpenID ) ṣiṣan lẹgbẹẹ iwọle aiyipada ọrọ igbaniwọle — iwọle ọrọ igbaniwọle ko yọkuro rara, ni afikun nikan:

- Alaabo ayafi ti `settings.oidcEnabled === true`** ati** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` gbogbo wa ni tunto (Eto → Auth). `GET /api/auth/oidc/login` pada `400` bibẹkọ ti.
- `GET /api/auth/oidc/login` ṣe awari `authorization_endpoint` lati `/.well-known/openid-configuration` olufun (ṣubu pada si `<issuer>/authorize`), ṣe atundari URI lati inu ibeere ti nwọle (`x-forwarded-proto` -aware), ati ki o ṣe itọsọna si IdP pẹlu `state` laileto ti a fipamọ sinu kuki `httpOnly` `oidc_state` kan.
- `GET /api/auth/oidc/callback` fọwọsi `state`, paarọ koodu aṣẹ, o si ṣe idaniloju ibuwọlu ami ID nipasẹ JWKS olufun (`jose`'s `createRemoteJWKSet`, cached per JWKS URI) pẹlu awọn sọwedowo `issuer`/`audience`. Gbigbawọle Dasibodu nilo atokọ `oidcAllowedSubjects` ti ko ṣofo, ilana `oidcAdmissionClaim` kan, tabi mejeeji. Akojọ koko-ọrọ ibaamu `sub` tabi `email` nikan nigbati `email_verified === true`. Eto imulo ẹtọ yiyan gba ọna ẹtọ ID-aami-aami-aami kan (fun apẹẹrẹ, `realm_access.roles`) ati titobi awọn iye itẹwọgba; ibeere ti o yanju gbọdọ jẹ opo ti awọn gbolohun ọrọ ti o ni o kere ju iye kan ti o gba. Ti awọn eto imulo mejeeji ba tunto, mejeeji gbọdọ kọja. awọn ẹtọ Missing/malformed kuna ni pipade, ati laisi boya eto imulo ipepada kọ buwolu wọle (`not_configured`). Awọn atunto koko-ọrọ nikan ti o wa tẹlẹ tẹsiwaju ko yipada.
- Keycloak deede maapu awọn ipa ijọba sinu awọn ami wiwọle, kii ṣe dandan awọn ami ID. Lati nilo ipo ijọba `admin`, tunto maapu ilana kan fun alabara yii ti o pẹlu `realm_access.roles` ninu rẹ**ID àmi** , lẹhinna ṣeto `oidcAdmissionClaim` si `{ "path": "realm_access.roles", "values": ["admin"] }`. Ṣayẹwo ibeere idanimọ ID gangan fun alabara yii ṣaaju ṣiṣe gbigba ipa-nikan; awọn ohun elo ko ni ka wiwọle-àmi ipa. Kiko tokini ẹgbẹ-IdP le ṣe afikun ṣugbọn ko rọpo ayẹwo-ẹgbẹ ohun elo yii.
- Lori aseyori ti o mints awọn** gangan kanna** 30-ọjọ `auth_token` JWT awọn ọrọ iwọle ọrọ igbaniwọle (`src/app/api/auth/login/route.ts`), nitorinaa iyoku ti opo gigun ti epo igba dasibodu (itura-laifọwọyi, awọn asia kuki) ko yipada — OIDC nikan rọpo bi kuki naa ṣe gba minted, kii ṣe ohun ti o funni. Awọn iyipada si IdP roles/groups ko ba awọn akoko OmniRoute ti o wa tẹlẹ jẹ; ijade jade, yiyi ọrọ igbaniwọle, tabi ipari igba ṣi ṣe akoso igbesi aye wọn.
- Gbogbo eto `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) wa ninu `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` dahun `400 PASSWORD_REQUIRED` ayafi ti ara ba gbe ọrọigbaniwọle isakoso bi `currentPassword` (`401 PASSWORD_MISMATCH` nigbati o jẹ aṣiṣe). `oidcDisablePasswordLogin` kọ ọrọ igbaniwọle _login_ (`POST /api/auth/login`) ṣugbọn o tọju hash ọrọ igbaniwọle ti o fipamọ, ati tun-ifọwọsi ṣi ṣayẹwo `currentPassword` lodi si rẹ.
- `corsOrigins` ati `bruteForceProtection` wa ni `SECURITY_IMPACTING_SETTINGS_KEYS` paapaa: ṣiṣi silẹ boya o dinku awọn aabo iwọle, nitorinaa wọn tun gba `currentPassword` kanna (taabu Aabo beere fun) ati gbewọle JSON silẹ wọn.
- Gbogbo bọtini aabo-eto imulo — awọn titẹ sii `SECURITY_IMPACTING_SETTINGS_KEYS`, gbogbo bọtini `oidc*` ati igba dasibodu ipo — jẹ** onišẹ-nikan** lori `PATCH /api/settings`: bọtini API ti iṣakoso-scoped tabi ami iraye si `oma_` jẹ kọ pẹlu `403` paapaa nigba ti o ba fi `currentPassword` ọtun ranṣẹ, ati pe kiko naa jẹ ṣiṣayẹwo bi `settings.update_failed` pẹlu `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` ni `src/lib/api/operatorCredential.ts`). Awọn eto deede (akori, awọn ayanfẹ ifihan) duro ni kikọ fun bọtini `manage` tabi ami iraye si `admin`. Gbogbo iyipada ti `/api/settings` funrarẹ (ati ti `/api/settings/require-login`) tun nilo aaye-ọna-iwọle `admin` (`ADMIN_MUTATION_EXACT_PATHS` ni `src/server/authz/accessScopes.ts`, ibaamu-ọna gangan); `GET` duro `read`, ati awọn miiran `/api/settings/*` awọn ipa-ọna (awọn aṣoju, awọn aiyipada konbo, inagijẹ awoṣe, funmorawon, purges…) tọju ọna-kika `write` dopin.
- `POST /api/settings/import-json` fo ti o tun-ifọwọsi, nitorinaa o ju gbogbo bọtini silẹ ni `IMPORT_STRIPPED_SETTINGS_KEYS` (faili kanna) ṣaaju kikọ: ọrọ igbaniwọle ati `currentPassword`, gbogbo titẹ sii `SECURITY_IMPACTING_SETTINGS_KEYS`, ati ipo igba dasibodu (`sessionsValidAfter`, `revokedDashboardSessions`). Gbigbe afẹyinti agbalagba wọle nitorina ko le sọji igba ti ọrọ igbaniwọle yipada tabi ami-jade ti pari tẹlẹ.

#### Iyan TOTP wiwọle-meji ifosiwewe (#16619)

Ti forukọsilẹ lati Eto → Aabo; pipa titi oniṣẹ ẹrọ yoo fi tan-an (`src/server/auth/dashboardMfa.ts`).

- **Ohun ti o bo:** wiwọle ọrọigbaniwọle (`POST /api/auth/login`, eyi ti o nilo `POST /api/auth/mfa/verify`) ati `omniroute connect` (`POST /api/cli/connect`, eyi ti o kọ paṣipaaro-ọrọ igbaniwọle nikan ti o gba koodu naa bi `totp`).
- **Ohun ti ko bo:** OIDC / SSO iwọle (`/api/auth/oidc/callback`) ko beere fun OmniRoute TOTP. O da lori ifosiwewe keji ti olupese idanimo, nitorina fi agbara mu MFA ninu IdP ti OIDC ba ti ṣiṣẹ.
- **Imularada** (Ẹrọ ti o sọnu, ko si awọn koodu imularada ti o ku, tabi ifosiwewe kan ti ko le ṣe idaniloju, fun apẹẹrẹ lẹhin iyipada `STORAGE_ENCRYPTION_KEY` ):
  1. Tun olupin bẹrẹ pẹlu `OMNIROUTE_DISABLE_MFA=true`.
  2. Lori agbalejo funrararẹ (loopback peer ati loopback `Host`, gẹgẹ bi `http://localhost:20128`), wọle pẹlu ọrọ igbaniwọle. Awọn keji ifosiwewe ti wa ni skipped fun awọn ti Oti nikan; gbogbo orisun miiran tun nilo koodu naa.
  3. Ninu Eto → Aabo → Muu ṣiṣẹ, tẹ ọrọ igbaniwọle sii ki o fi koodu naa silẹ ni ofifo. `POST /api/auth/mfa/disable` gba ara kan laisi `code` nikan nigba ti a ṣeto oniyipada ati pe ibeere wa lati ọdọ agbalejo; o tun nilo igba dasibodu ati ọrọ igbaniwọle lọwọlọwọ, ati pe a ṣe ayẹwo bi `auth.mfa.disabled` pẹlu `secondFactor: "recovery_switch"`.
  4. Yọ `OMNIROUTE_DISABLE_MFA` kuro, tun bẹrẹ, ati forukọsilẹ lẹẹkansi ti o ba nilo.

## Àwọn Ẹ̀ka Route

`src/server/authz/types.ts` ṣàlàyé ẹ̀ka mẹ́ta; route kan tí a kò lè pín ní ìdánilójú ń padà sí `MANAGEMENT`.

| Ẹ̀ka          | Àpèjúwe                                                                                                                                                        | Ìjẹ́rìí tí a nílò                                                        |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| `PUBLIC`     | Àwọn route tí ó ṣe kedere ní ààbò: wíwọlé, jíjáde, ipò, init, health, onboarding bootstrap.                                                                    | Kò sí                                                                   |
| `CLIENT_API` | Àwọn endpoint ìsìn àwòṣe: `/api/v1/*`, `/api/v1beta/*`, pẹ̀lú àwọn orúkọ àpọ́nlé `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Bearer key nígbà tí feature flag `REQUIRE_API_KEY` tó ń ṣiṣẹ́ bá ti ṣiṣẹ́ |
| `MANAGEMENT` | Àwọn ojú-ìwé dashboard, àwọn ètò, àwọn olùpèsè, àwọn kọ́kọ́rọ́, àwọn endpoint admin àti ìwádìí.                                                                   | Ìgbà dashboard TÀBÍ Bearer tí ó ní ìwọ̀n `manage`                        |

Àwọn ìgbésẹ̀ `MANAGEMENT` kan jẹ́ **ti operator nìkan**: kọ́kọ́rọ́ `manage` kò tó. Kíkó àwọn credential tí a tọ́jú jáde (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), dída afẹ́yìntì padà sórí data ààyè (`POST /api/db-backups/import` pẹ̀lú `dryRun=true`, `POST /api/db-backups` restore nípa id, `POST /api/settings/import-json`), àti pípa àwọn ibi ìpadàbọ̀ rẹ́ (`DELETE /api/db-backups` cleanup, àti `PATCH /api/db-backups` nítorí pé retention tí ó ń tọ́jú ni ó ń wa pruning aládàáṣe lẹ́yìn gbogbo backup) nílò ìgbà dashboard, olùmọ̀ CLI ti agbègbè, tàbí wíwọlé tí a ti pa. Fífúnni ní sync token (`POST /api/sync/tokens`) àti ṣíṣe `admin` CLI access token (`POST /api/cli/tokens`) nílò ìgbà dashboard tàbí olùmọ̀ CLI ti agbègbè ní gbogbo ipò wíwọlé. Àwọn kọ́kọ́rọ́ API ti ìwọ̀n èyíkéyìí àti àwọn `oma_` access token kì í ṣe àwọn credential operator: wọ́n máa gba `403` nígbàkígbà tí a bá nílò ọ̀kan. Àyẹ̀wò yìí wà nínú `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Yíyí àwọn ètò wíwọlé padà pẹ̀lú jẹ́ ti operator nìkan: `POST /api/settings/require-login` (ṣètò ọ̀rọ̀ aṣínà ìṣàkóso / yí `requireLogin` padà) ń gba àwọn credential wọ̀nyí nìkan nígbà tí ọ̀rọ̀ aṣínà bá ti wà. Fèrèsé bootstrap ìbẹ̀rẹ̀ (kò sí ọ̀rọ̀ aṣínà síbẹ̀) kò yí padà, ìgbà dashboard sì gbọ́dọ̀ fi `currentPassword` ránṣẹ́ láti rọ́pò ọ̀rọ̀ aṣínà (`403` tí ó bá kù tàbí tí kò tọ̀nà, a sì ń ṣe àkọsílẹ̀ rẹ̀ gẹ́gẹ́ bí `settings.update_failed`). CLI ti agbègbè àti instance tí wíwọlé rẹ̀ jẹ́ alaabọ̀ ń pa ọ̀nà ìmúpadàbọ̀sípò mọ́, wọ́n sì lè ṣètò ọ̀rọ̀ aṣínà láìsí i, nítorí méjèèjì ni a so mọ́ host tí ó ni data directory.

## Pipeline

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

Awọn akọle inu ti o gbẹkẹle (ti a ṣalaye ni `src/server/authz/headers.ts`) jẹ** yọ kuro lati awọn ibeere ti nwọle** ṣaaju ki ikasi — awọn alabara ko le ṣaju-gbejade `x-omniroute-auth-*` lati farawe koko-ọrọ kan.

### Awọn adehun imulo

Kilasi ipa ọna kọọkan ni eto imulo ni `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — nigbagbogbo da `allow({ kind: "anonymous", id: "anonymous" })` pada.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ayokuro Bearer, sooto nipasẹ `validateApiKey()`. Ṣubu nipasẹ ailorukọ nikan nigbati asia ẹya `REQUIRE_API_KEY` ti o munadoko jẹ alaabo. Asia ti o munadoko jẹ ipinnu nipasẹ `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) nitorinaa Awọn asia Ẹya Dasibodu ati awọn oniyipada ayika ṣe akoso `/api/v1/*`, `/api/v1beta/*`, ati awọn inagijẹ nigbagbogbo; awọn ikuna ipinnu kuna ni pipade. Faye gba awọn ibeere dasibodu-igba lori awọn ipa ọna API alabara (pẹlu `/api/v1/models`, ti a lo nipasẹ katalogi awoṣe dasibodu). Nigbati o ba mu Entra ID SSO ṣiṣẹ, Oluduro ti o jẹ apẹrẹ ti o jẹ ami Entra (awọn ipele base64url mẹta, `RS*` alg, `kid`) ni a ṣakoso nipasẹ ẹka SSO** ṣaaju ki o to** `validateApiKey()` ati idajo rẹ jẹ — ti o kẹhin kii yoo ṣubu si ọna bọtini API tabi ẹka ti o bajẹ-si-ailorukọ, nitorinaa ijade olupese idanimọ ko le di iwọle si ṣiṣi. Awọn bọtini API aimi ko ni ipa. Wo [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — gba igba dasibodu, awọn ibeere amuṣiṣẹpọ inu inu (ti o baamu si `/api/providers/[name]/(sync-models|models)`), tabi fo patapata ti `isAuthRequired()` ba pada eke. Pada 403 (`AUTH_001`) nigbati aami Oluduro kan wa ṣugbọn ko wulo, 401 bibẹẹkọ. Paapaa fi agbara mu awọn ipele oluso ipa-ọna (LOCAL_ONLY / ALWAYS_PROTECTED) ṣaaju eyikeyi ẹka auth — wo [Awọn ipele Ẹṣọ Ipa-ọna](../security/ROUTE_GUARD_TIERS.md). awọn ọna LOCAL_ONLY ni `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (loni: `/api/mcp/`) le wọle lati ti kii ṣe loopback nigbati bọtini Bearer gbe aaye `manage` ; gbogbo awọn ọna LOCAL_ONLY miiran wa ti o muna-loopback laibikita iwọn.

Ilana aṣeyọri da `AuthSubject` pada pẹlu `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Awọn olutọju isalẹ le ka nipasẹ `assertAuth(request, "CLIENT_API")` ni `src/server/authz/assertAuth.ts` dipo ṣiṣiṣẹ auth kannaa.

## Akojọ Awọn ipa ọna gbangba

`src/shared/constants/publicApiRoutes.ts` jẹ atokọ ti o han gbangba:

Awọn akojọ ti wa ni pin nipa** apẹrẹ** , ati pipin jẹ fifuye-rù (GHSA-74g9-q8f6-793h): ìpele kan ti baamu pẹlu `startsWith()`, nitorina o tun baamu gbogbo ọna ti o wa nitosi pinpin awọn ohun kikọ asiwaju rẹ. `/api/usage/om-usage` gẹgẹbi ìpele ti samisi `/api/usage/om-usage<anything>` PUBLIC, ati Nigbamii ti pinnu pe lati `/api/usage/[connectionId]` — oluṣakoso kan ti ko ni ijẹrisi tirẹ.

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

Awọn ipa ọna kika-nikan jẹ ti gbogbo eniyan** nikan** fun awọn ọna ailewu. Akiyesi: `classifyRoute()` yọkuro `/api/v1/*` ati `/api/v1beta/*` kuro ninu isubu PUBLIC -nipasẹ — awọn wọn jẹ `CLIENT_API` nigbagbogbo nitorina eto imulo bọtini Bearer ṣi wa.

## Fífì Route Tuntun Kún Un

### Àpẹẹrẹ 1 — Endpoint API oníbàárà gbangba (Bearer-auth)

Àwọn route lábẹ́ `/api/v1/` àti `/api/v1beta/` ni a máa ń pín sí `CLIENT_API` láìfọwọ́ṣe. Middleware náà ń fipá mú àyẹ̀wò Bearer; àwọn route handler kò nílò láti tún un ṣe, ṣùgbọ́n wọ́n lè ka subject náà bí ó bá wúlò.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... ìlànà handler
}
```

### Àpẹẹrẹ 2 — Endpoint ìṣàkóso (session tàbí Bearer + manage)

Lo `requireManagementAuth()` láti `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... ìlànà handler
}
```

`requireManagementAuth()` máa ń dá `null` padà nígbà àṣeyọrí tàbí `Response` àṣìṣe JSON kan:

- 401 `AUTH_001` "A nílò ìfàṣẹsí" — kò sí credential rárá
- 403 — Bearer tí kò tọ́ **tàbí** Bearer wà ṣùgbọ́n key náà kò ní scope `manage` / `admin`

`hasManageScope(scopes)` máa ń dá true padà fún `"manage"` tàbí `"admin"`.

### Àpẹẹrẹ 3 — Fífì kún àtòjọ ìyọ̀ǹda gbangba

Yan set náà gẹ́gẹ́ bí ìrísí, kì í ṣe nítorí ìrọ̀rùn. Route kan ṣoṣo lọ sínú `PUBLIC_API_ROUTES_EXACT` (tàbí `PUBLIC_READONLY_CORS_API_ROUTES` fún GET-nìkan); subtree gidi nìkan ló yẹ kó lọ sínú `PUBLIC_API_ROUTE_PREFIXES`, ó sì **gbọdọ̀ parí pẹ̀lú `/`**. Fífi route kan ṣoṣo sínú àtòjọ prefix tún máa ń sọ gbogbo path tó wà lẹ́gbẹ̀ẹ́ tí wọ́n ní àwọn àmì ìbẹ̀rẹ̀ kan náà di gbangba — pẹ̀lú àwọn dynamic-segment sibling tí a bá fi kún un lọ́jọ́ iwájú (GHSA-74g9-q8f6-793h). Ṣàfikún àwọn unit test ní `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` àti `tests/unit/authz/classify.test.ts`.

## Àwọn Àyè

Àwọn àyè orúkọ mẹ́ta. Olùṣàyẹ̀wò kọ̀ọ̀kan ka àwọn okùn tirẹ̀ nìkan. Ìfiwéra, pẹ̀lú ìdí tí `manage` fi kùnà `scopeMatches` fún `read:compression` àti ìdí tí àmì ìwọlé `read` kò fi lè `PATCH /api/keys/{id}`, wà ní [Àwọn àyè orúkọ mẹ́ta](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Àwọn kọ́kọ́rọ́ API gbé àtòpọ̀ `scopes` (tí a tọ́jú sí bi JSON nínú `api_keys.scopes`, wo `src/lib/db/apiKeys.ts`).

### Àyè ìṣàkóso

- `manage` / `admin` — `hasManageScope`. Ìwọlé tí ó gbé àmì sí àwọn ọ̀nà API ìṣàkóso.
- `mcp:connect`, `self:usage`, `self:account-quota`, àti
  `policy:bypass-provider-quota` jẹ́ àwọn àyè ìbámu-gangan tí a lè fi kún. Wọ́n wà ní ìta `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` ṣí
  `/api/mcp/` ìpín-ìwọlé tí kìí ṣe loopback nìkan.

### Àwọn àyè irinṣẹ́ MCP

Ìtòlẹ́sẹẹsẹ àti àwọn òfin ìbámu (okùn kan náà, tàbí àyè tí a fún tí ó parí pẹ̀lú `*`):
[Àwọn àyè irinṣẹ́ MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` nínú `src/shared/constants/mcpScopes.ts` jẹ́ ìpín-ẹ̀ka tí a tẹ́ tẹ́lẹ̀, kìí ṣe gbogbo ìtòlẹ́sẹẹsẹ náà. Ìmúṣẹ́ ń ṣiṣẹ́ nínú
`open-sse/mcp-server/scopeEnforcement.ts` lẹ́hìn tí `resolveCallerScopeContext()`
bá ti yanjú àwọn àyè láti ìwífún ìfọwọ́sí MCP, metadata ìbéèrè, tàbí `OMNIROUTE_MCP_SCOPES`. Kò ní ṣiṣẹ́ àyàfi tí `OMNIROUTE_MCP_ENFORCE_SCOPES=true` bá wà.

### Àwọn àyè àmì ìwọlé

`read` / `write` / `admin` lórí àwọn àmì `oma_live_…`, tí a tò lẹ́sẹẹsẹ nípasẹ̀ `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Ìpele yìí kan ìwé-ẹ̀rí àmì ìwọlé nìkan. Wo [Ìfọwọ́sí Ìṣàkóso](../guides/MANAGEMENT-AUTH.md).

## Ìyípadà Ìjẹ́rìí Tí A Nílò

`isAuthRequired()` nínú `src/shared/utils/apiAuth.ts` ló ń pinnu bóyá a óò fi **ìjẹ́rìí** kankan lélẹ̀ fún ìbéèrè kan:

- `settings.requireLogin === false` → ìjẹ́rìí ti di pípa lápapọ̀, àfi ipele ààbò tí ó máa wà nígbà gbogbo (wo [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) àti àwọn ìpè tí ń fúnni ní credential tí ó gbà, tí ó nílò credential kan náà bí wíwọlé ṣe wà ní títàn: fífúnni ní sync token, ṣíṣe CLI access token ní ìwọ̀n èyíkéyìí, àti dídá kọ́kọ́rọ́ API tí ó ní ìwọ̀n `manage`/`admin`, fífún kọ́kọ́rọ́ ní ìwọ̀n yẹn, tàbí tún ṣe tàbí fihàn irú kọ́kọ́rọ́ bẹ́ẹ̀ (`requireCredentialForManagementScopedKey()` nínú `src/lib/api/requireManagementAuth.ts`). Àwọn kọ́kọ́rọ́ inference nìkan ló wà ní sísílẹ̀.
- Kò sí ọ̀rọ̀ aṣínà tí a ṣètò **àti** kò sí env var `INITIAL_PASSWORD` → ipò bootstrap: ó gba onboarding wizard àti àwọn ìbéèrè loopback láàyè, ṣùgbọ́n àwọn ìbéèrè nẹ́tíwọ́kì tí a ṣí payá ṣì nílò credential.
- Àṣìṣe DB èyíkéyìí → ó kùnà ní títì (secure-by-default).

Ìfipágbára API key ti oníbàárà ń lo `isRequireApiKeyEnabled()` nínú `src/shared/utils/featureFlags.ts`, kì í ṣe kíka `process.env.REQUIRE_API_KEY` tààrà. Èyí ṣe pàtàkì fún àwọn instance tí a fi ránṣẹ́: yíyí `REQUIRE_API_KEY` padà nínú Dashboard → Feature Flags ń tọ́jú DB override, ó sì ń nípa lórí `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, àti àwọn àyẹ̀wò ìjẹ́rìí client-API mìíràn tí ó ń pín olùrànlọ́wọ́ yìí lẹsẹkẹsẹ. Tí a kò bá lè ka feature flag store, ìjẹ́rìí client API ń kùnà ní títì, ó sì nílò kọ́kọ́rọ́.

## Àyípadà Tó Fọ́ Ìbámu — v3.8.0

Àwọn endpoint `/api/v1/agents/tasks/*` àti `/api/resilience/model-cooldowns` **ní báyìí nílò ìfàṣẹsí ìṣàkóso** (commit `588a0333`). Àwọn oníbàárà tí wọ́n ti ń fi kọ́kọ́rọ́ API àdáṣe ránṣẹ́ láìsí ìwọ̀n ààyè `manage` máa gba `403`. Ìṣílọ: yálà fún kọ́kọ́rọ́ náà ní ìwọ̀n ààyè `manage` nínú dashboard API Keys, tàbí lo session dashboard tí a ti wọlé sí.

## Àyípadà Ìhùwàsí — v3.8.2

`/api/mcp/*` (server MCP jíjìn) ṣì jẹ́ LOCAL_ONLY ní àiyípẹ̀, ṣùgbọ́n ní báyìí ó ń gba àwọn ìbéèrè tí kì í ṣe loopback nígbà tí header `Authorization: Bearer <api-key>` bá ní ìwọ̀n ààyè `manage`. Ààyè àkànṣe náà jẹ́ dídènà ní kedere fún path kọ̀ọ̀kan nípasẹ̀ `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` nínú `src/server/authz/routeGuard.ts`; prefix LOCAL_ONLY ẹlẹgbẹ́ rẹ̀ `/api/cli-tools/runtime/*` jẹ́ èyí tí a mọ̀ọ́mọ̀ ṣe pé a kò lè kọjá rẹ̀ nítorí pé ó lè dá àwọn subprocess aláìlópin sílẹ̀. Àwọn ìbéèrè aláìlórúkọ sí `/api/mcp/*` láti ibi tí kì í ṣe loopback ṣì ń dá `403 LOCAL_ONLY` padà — àiyípẹ̀ fún path LOCAL_ONLY tuntun èyíkéyìí ṣì jẹ́ loopback nìkan tó muna. Wo [Àwọn Ìpele Route Guard](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Ìdánwò

- Àwọn ìdánwò unit: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Àkójọ àṣẹ gbogbogbò: `tests/unit/public-api-routes.test.ts`.
- Ṣíṣe ìdánwò àfojúsùn: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## N ṣatunṣe aṣiṣe

Opo gigun ti epo nigbagbogbo n ṣe awọn idahun pẹlu:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Fun awọn ibeere ti o ni idaniloju awọn akọle ibeere ti oke (ẹgbẹ-aṣakoso) tun pẹlu:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Lo `assertAuth(req, expectedClass)` inu awọn olutọju — o jabọ `AuthzAssertionError` pẹlu koodu `AUTHZ_NOT_INITIALIZED` ti agbedemeji ti o ba kọja (ṣe iranlọwọ fun mimu awọn atunto iṣeto ni awọn idanwo).

## Wo Pẹ̀lú

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — àmì ìfọwọ́sí fún ojúami kọ̀ọ̀kan
- [COMPLIANCE.md](../security/COMPLIANCE.md) — àkọsílẹ̀ àyẹ̀wò fún àwọn ìṣẹ̀lẹ̀ ìfọwọ́sí
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — àwọn ààyè orúkọ ìpele mẹ́ta àti àtòjọ àwọn irinṣẹ́ MCP
- Orísun: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
