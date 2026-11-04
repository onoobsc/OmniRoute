# Authorization Guide (Bahasa Melayu)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Sumber kebenaran:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Terakhir dikemas kini:** 2026-09-22 — ruang lingkup nama ruang merujuk kepada MCP-SERVER.md

OmniRoute mempunyai saluran paip kebenaran yang peka laluan yang mengawal setiap permintaan API. Pengelasan adalah **deterministik** dan **gagal-tertutup** — apa-apa yang tidak dapat dikelaskan akan berakhir sebagai `MANAGEMENT` dan memerlukan sesi atau token gred pengurusan. Halaman ini menerangkan model untuk jurutera yang menyelenggara laluan atau mereka bentuk titik akhir baharu.

![AuthZ pipeline (3 route classes + policy evaluation)](../diagrams/exported/authz-pipeline.svg)

> Sumber: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dua Mod Pengesahan

### 1. API Key (Pembawa)

Digunakan untuk OpenAI/Anthropic/Gemini-compatible klien APIs dan beberapa laluan pengurusan apabila kunci mempunyai skop `manage`.

```
Authorization: Bearer <api-key>
```

Disahkan oleh `isValidApiKey()` / `extractApiKey()` dalam `src/sse/services/auth.ts` dan dieksport semula melalui `src/shared/utils/apiAuth.ts`. Pengesah juga menerima `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars sebagai kunci laluan berterusan (isu #1350).

### 2. Sesi Papan Pemuka (kuki auth_token)

Untuk halaman papan pemuka dan operasi pentadbir.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Kuki ialah sesi hanya apabila JWT mengesahkan** dan** membawa `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Setiap pengguna kuki (pengawal laluan papan pemuka (`isDashboardSessionAuthenticated()`), penyegaran saluran paip authz, jabat tangan WebSocket, pelayan langsung, `/api/settings/require-login`, `/api/auth/status`) melalui pembantu itu. JWTs lain yang ditandatangani dengan `JWT_SECRET` wujud — Cursor CLI passthrough mencetak token `iss "omniroute" / aud "cursor-cli"` untuk pemegang kunci — dan tidak pernah menjadi sesi (#13298).

Disahkan oleh `isDashboardSessionAuthenticated()` dalam `src/shared/utils/apiAuth.ts`. Saluran paip menyegarkan semula JWT secara automatik apabila ia mempunyai kurang daripada 7 hari lagi dalam hayat 30 harinya.

Sesi juga boleh tamat sebelum 30 harinya tamat, kerana setiap penambang melalui `mintDashboardSessionToken` (masa keluaran `iat` dan id `jti`) dan pengesah menyemak dua tetapan: `sessionsValidAfter`, ditetapkan oleh penukaran kata laluan supaya setiap sesi yang dikeluarkan sebelum ia berhenti mengesahkan (penyemak imbas yang menukar kata laluan mendapat kuki baharu), dan `revokedDashboardSessions`, yang `POST /api/auth/logout` -out menambahkan sesi yang ditandatangani `jti`. Sesi yang dicetak oleh keluaran lama tidak membawa tuntutan dan kekal sah sehingga kata laluan pertama ditukar. Jika tetapan tidak boleh dibaca, sesi itu tidak dipercayai.

Beberapa laluan pengurusan menerima** sama ada** mod: cookie OR `Bearer <key>` apabila kunci API mempunyai skop `manage` (atau `admin`). Inilah yang membolehkan aliran kerja "boleh dikonfigurasikan melalui panggilan API " ditambah dalam v3.8.

#### Gerbang log masuk OIDC pilihan (#6973)

Log masuk pentadbir papan pemuka juga menyokong** ikut serta** aliran OIDC (OpenID Connect) bersama log masuk kata laluan lalai log masuk kata laluan — tidak pernah dialih keluar, hanya ditambah:

- Dilumpuhkan melainkan `settings.oidcEnabled === true`** dan** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` semuanya dikonfigurasikan (Tetapan → Auth). `GET /api/auth/oidc/login` mengembalikan `400` sebaliknya.
- `GET /api/auth/oidc/login` menemui `authorization_endpoint` daripada `/.well-known/openid-configuration` pengeluar (berbalik kepada `<issuer>/authorize`), membina ubah hala URI daripada permintaan masuk (`x-forwarded-proto` -aware), dan ubah hala ke IdP dengan `state` rawak yang disimpan dalam kuki `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` mengesahkan `state`, menukar kod kebenaran dan mengesahkan tandatangan token ID melalui JWKS pengeluar (`jose` `createRemoteJWKSet`, dicache setiap JWKS URI) dengan cek `issuer`/`audience`. Kemasukan papan pemuka memerlukan senarai `oidcAllowedSubjects` yang tidak kosong, dasar `oidcAdmissionClaim` atau kedua-duanya. Senarai subjek sepadan dengan `sub` atau `email` hanya apabila `email_verified === true`. Dasar tuntutan pilihan mengambil laluan tuntutan token ID yang dipisahkan titik (contohnya, `realm_access.roles`) dan tatasusunan nilai yang diterima; tuntutan yang diselesaikan mestilah tatasusunan rentetan yang mengandungi sekurang-kurangnya satu nilai yang diterima. Jika kedua-dua dasar dikonfigurasikan, kedua-duanya mesti lulus. tuntutan Missing/malformed gagal ditutup, dan tanpa salah satu dasar panggilan balik menolak log masuk (`not_configured`). Konfigurasi subjek sahaja yang sedia ada terus tidak berubah.
- Keycloak biasanya memetakan peranan alam ke dalam token akses, tidak semestinya token ID. Untuk menghendaki peranan alam `admin`, konfigurasikan pemeta protokol untuk klien ini yang menyertakan `realm_access.roles` di dalamnya** token ID** , kemudian tetapkan `oidcAdmissionClaim` kepada `{ "path": "realm_access.roles", "values": ["admin"] }`. Semak tuntutan token ID sebenar untuk pelanggan ini sebelum mendayakan kemasukan peranan sahaja; aplikasi tidak membaca peranan token akses. Penolakan token sebelah IdP boleh menambah tetapi tidak menggantikan semakan sebelah aplikasi ini.
- Pada kejayaan ia menghasilkan** betul-betul sama** 30 hari `auth_token` JWT isu log masuk kata laluan (`src/app/api/auth/login/route.ts`), jadi saluran paip sesi papan pemuka selebihnya (muat semula automatik, bendera kuki) tidak berubah — OIDC hanya menggantikan cara kuki ditempa, bukan apa yang diberikannya. Perubahan kepada IdP roles/groups tidak membatalkan sesi OmniRoute sedia ada; log keluar, penggiliran kata laluan atau tamat sesi masih mengawal seumur hidup mereka.
- Setiap tetapan `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) adalah dalam `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` menjawab `400 PASSWORD_REQUIRED` melainkan badan itu membawa kata laluan pengurusan sebagai `currentPassword` (`401 PASSWORD_MISMATCH` apabila ia salah). `oidcDisablePasswordLogin` menolak kata laluan _login_ (`POST /api/auth/login`) tetapi menyimpan cincang kata laluan yang disimpan, dan pengesahan semula masih menyemak `currentPassword` terhadapnya.
- `corsOrigins` dan `bruteForceProtection` berada dalam `SECURITY_IMPACTING_SETTINGS_KEYS` juga: melonggarkan sama ada melemahkan pertahanan log masuk, jadi mereka mengambil `currentPassword` re-auth yang sama (tab Keselamatan memintanya) dan import JSON menjatuhkannya.
- Setiap kunci dasar keselamatan — entri `SECURITY_IMPACTING_SETTINGS_KEYS`, setiap kunci `oidc*` dan sesi papan pemuka keadaan — ialah** pengendali sahaja** pada `PATCH /api/settings`: kunci API berskop urus atau token akses `oma_` ditolak dengan `403` walaupun apabila ia menghantar `currentPassword` yang betul dan penolakan itu diaudit sebagai `settings.update_failed` dengan `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` dalam `src/lib/api/operatorCredential.ts`). Tetapan biasa (tema, pilihan paparan) kekal boleh ditulis untuk kunci `manage` atau token akses `admin`. Setiap mutasi `/api/settings` itu sendiri (dan `/api/settings/require-login`) juga memerlukan skop token akses `admin` (`ADMIN_MUTATION_EXACT_PATHS` dalam `src/server/authz/accessScopes.ts`, padanan laluan tepat); `GET` kekal `read`, dan sub-laluan `/api/settings/*` yang lain (proksi, lalai kombo, alias model, mampatan, pembersihan…) mengekalkan skop `write` yang disimpulkan kaedah.
- `POST /api/settings/import-json` melangkau pengesahan semula itu, jadi ia menjatuhkan setiap kekunci dalam `IMPORT_STRIPPED_SETTINGS_KEYS` (fail yang sama) sebelum menulis: kata laluan dan `currentPassword`, setiap masukan `SECURITY_IMPACTING_SETTINGS_KEYS` dan keadaan sesi papan pemuka (`sessionsValidAfter`, `revokedDashboardSessions`). Oleh itu, mengimport sandaran yang lebih lama tidak boleh menghidupkan semula sesi yang telah ditukar kata laluan atau log keluar telah tamat.

#### Log masuk dua faktor TOTP pilihan (#16619)

Didaftarkan daripada Tetapan → Security; padam sehingga operator menghidupkannya (`src/server/auth/dashboardMfa.ts`).

- **Perkara yang merangkumi:** log masuk kata laluan (`POST /api/auth/login`, yang kemudiannya memerlukan `POST /api/auth/mfa/verify`) dan `omniroute connect` (`POST /api/cli/connect`, yang menolak pertukaran kata laluan sahaja dan mengambil kod sebagai `totp`).
- **Perkara yang tidak dilindungi:** log masuk OIDC / SSO (`/api/auth/oidc/callback`) tidak meminta OmniRoute TOTP. Ia bergantung pada faktor kedua pembekal identiti itu sendiri, jadi kuatkuasakan MFA dalam IdP jika OIDC didayakan.
- **Pemulihan** (peranti hilang, tiada kod pemulihan yang tinggal atau faktor yang tidak boleh disahkan lagi, contohnya selepas `STORAGE_ENCRYPTION_KEY` ditukar):
  1. Mulakan semula pelayan dengan `OMNIROUTE_DISABLE_MFA=true`.
  2. Pada hos itu sendiri (loopback peer dan loopback `Host`, seperti `http://localhost:20128`), log masuk dengan kata laluan. Faktor kedua dilangkau untuk asal itu sahaja; setiap asal lain masih memerlukan kod itu.
  3. Dalam Tetapan → Keselamatan → Lumpuhkan, masukkan kata laluan dan biarkan kod kosong. `POST /api/auth/mfa/disable` menerima badan tanpa `code` sahaja semasa pembolehubah ditetapkan dan permintaan datang daripada hos; ia masih memerlukan sesi papan pemuka dan kata laluan semasa, dan diaudit sebagai `auth.mfa.disabled` dengan `secondFactor: "recovery_switch"`.
  4. Nyahset `OMNIROUTE_DISABLE_MFA`, mulakan semula dan daftar semula jika perlu.

## Kelas Laluan

`src/server/authz/types.ts` mentakrifkan tiga kelas; mana-mana laluan yang tidak dapat diklasifikasikan secara deterministik akan jatuh balik kepada `MANAGEMENT`.

| Kelas        | Penerangan                                                                                                                                              | Pengesahan diperlukan                                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `PUBLIC`     | Laluan yang secara eksplisit selamat — log masuk, log keluar, status, inisialisasi, kesihatan dan bootstrap pendaftaran.                                | Tiada                                                                        |
| `CLIENT_API` | Titik akhir penyajian model — `/api/v1/*`, `/api/v1beta/*`, serta alias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Kunci Bearer apabila bendera ciri `REQUIRE_API_KEY` yang berkesan diaktifkan |
| `MANAGEMENT` | Halaman papan pemuka, tetapan, pembekal, kunci, serta titik akhir pentadbiran dan diagnostik.                                                           | Sesi papan pemuka ATAU Bearer dengan skop `manage`                           |

Beberapa tindakan `MANAGEMENT` adalah **khusus operator**: kunci `manage` tidak mencukupi. Mengeksport kelayakan tersimpan (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), memulihkan sandaran ke atas data langsung (`POST /api/db-backups/import` termasuk `dryRun=true`, `POST /api/db-backups` pemulihan mengikut id, `POST /api/settings/import-json`), dan memusnahkan titik pemulihan (`DELETE /api/db-backups` pembersihan, dan `PATCH /api/db-backups` kerana pengekalannya memacu pemangkasan automatik selepas setiap sandaran) memerlukan sesi papan pemuka, subjek CLI tempatan, atau log masuk yang dilumpuhkan. Mengeluarkan token penyegerakan (`POST /api/sync/tokens`) dan mencetak token akses CLI `admin` (`POST /api/cli/tokens`) memerlukan sesi papan pemuka atau subjek CLI tempatan dalam setiap mod log masuk. Kunci API bagi mana-mana skop dan token akses `oma_` bukan kelayakan operator: ia menerima `403` setiap kali salah satu diperlukan. Semakannya terdapat dalam `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Menukar tetapan log masuk juga khusus operator: `POST /api/settings/require-login` (menetapkan kata laluan pengurusan / menukar `requireLogin`) hanya menerima kelayakan tersebut selepas kata laluan wujud — tetingkap bootstrap permulaan (belum ada kata laluan) kekal tidak berubah — dan sesi papan pemuka mesti menghantar `currentPassword` untuk menggantikan kata laluan (`403` jika tiada atau salah, diaudit sebagai `settings.update_failed`). CLI tempatan dan contoh yang log masuknya dilumpuhkan mengekalkan laluan pemulihan dan boleh menetapkan kata laluan tanpanya, kerana kedua-duanya terikat pada hos yang memiliki direktori data.

## Saluran paip

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

Pengepala dalaman yang dipercayai (ditakrifkan dalam `src/server/authz/headers.ts`) ialah** dilucutkan daripada permintaan masuk** sebelum pengelasan — pelanggan tidak boleh pra-populasi `x-omniroute-auth-*` untuk menyamar sebagai subjek.

### Kontrak polisi

Setiap kelas laluan mempunyai dasar dalam `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — sentiasa mengembalikan `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — ekstrak Pembawa, mengesahkan melalui `validateApiKey()`. Terjadi tanpa nama hanya apabila bendera ciri `REQUIRE_API_KEY` yang berkesan dilumpuhkan. Bendera berkesan diselesaikan melalui `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) jadi Bendera Ciri Papan Pemuka dan pembolehubah persekitaran mengawal `/api/v1/*`, `/api/v1beta/*` dan alias secara konsisten; kegagalan penyelesai gagal ditutup. Membenarkan permintaan sesi papan pemuka pada laluan API pelanggan (termasuk `/api/v1/models`, digunakan oleh katalog model papan pemuka). Apabila Entra ID SSO didayakan, Pembawa yang secara struktur ialah token Entra (tiga segmen base64url, `RS*` alg, `kid`) dikendalikan oleh cawangan SSO** sebelum ini** `validateApiKey()` dan keputusannya adalah — muktamad ia tidak pernah jatuh ke laluan kunci API atau cawangan merendahkan kepada tanpa nama, jadi gangguan pembekal identiti tidak boleh menjadi akses terbuka. Kekunci API statik tidak terjejas. Lihat [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — menerima sesi papan pemuka, permintaan penyegerakan model dalaman (dipadanan dengan `/api/providers/[name]/(sync-models|models)`), atau melangkau sepenuhnya jika `isAuthRequired()` mengembalikan palsu. Mengembalikan 403 (`AUTH_001`) apabila token Pembawa hadir tetapi tidak sah, 401 sebaliknya. Juga menguatkuasakan peringkat pengawal laluan (LOCAL_ONLY / ALWAYS_PROTECTED) sebelum mana-mana cawangan pengesahan — lihat [Peringkat Pengawal Laluan](../security/ROUTE_GUARD_TIERS.md). laluan LOCAL_ONLY dalam `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (hari ini: `/api/mcp/`) boleh diakses daripada bukan gelung apabila kunci Pembawa membawa skop `manage` ; semua laluan LOCAL_ONLY lain kekal strict-loopback tanpa mengira skop.

Polisi yang berjaya mengembalikan `AuthSubject` dengan `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Pengendali hiliran boleh membacanya melalui `assertAuth(request, "CLIENT_API")` dalam `src/server/authz/assertAuth.ts` dan bukannya menjalankan semula logik auth.

## Senarai Laluan Awam

`src/shared/constants/publicApiRoutes.ts` ialah senarai benar yang jelas:

Senarai dipecahkan oleh** bentuk** , dan pemisahan adalah menanggung beban (GHSA-74g9-q8f6-793h): awalan dipadankan dengan `startsWith()`, jadi ia juga sepadan dengan setiap laluan bersebelahan yang berkongsi aksara utamanya. `/api/usage/om-usage` sebagai awalan bertanda `/api/usage/om-usage<anything>` PUBLIC, dan Seterusnya menyelesaikannya kepada `/api/usage/[connectionId]` — pengendali tanpa pengesahan sendiri.

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

Laluan baca sahaja adalah awam** sahaja** untuk kaedah selamat. Nota: `classifyRoute()` mengecualikan `/api/v1/*` dan `/api/v1beta/*` daripada PUBLIC jatuh-melalui — yang sentiasa `CLIENT_API` jadi dasar kunci Pembawa masih terpakai.

## Menambah Laluan Baharu

### Corak 1 — Titik akhir API klien awam (pengesahan Bearer)

Laluan di bawah `/api/v1/` dan `/api/v1beta/` dikelaskan sebagai `CLIENT_API` secara automatik. Perisian tengah menguatkuasakan semakan Bearer; pengendali laluan tidak perlu mengulanginya, tetapi boleh membaca subjek jika berguna.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... logik pengendali
}
```

### Corak 2 — Titik akhir pengurusan (sesi atau Bearer + manage)

Gunakan `requireManagementAuth()` daripada `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... logik pengendali
}
```

`requireManagementAuth()` mengembalikan `null` apabila berjaya atau `Response` ralat JSON:

- 401 `AUTH_001` "Pengesahan diperlukan" — langsung tiada bukti kelayakan
- 403 — Bearer tidak sah **atau** Bearer tersedia tetapi kunci tidak mempunyai skop `manage` / `admin`

`hasManageScope(scopes)` mengembalikan true untuk `"manage"` atau `"admin"`.

### Corak 3 — Menambah pada senarai dibenarkan awam

Pilih set berdasarkan bentuk, bukan kemudahan. Satu laluan dimasukkan ke dalam `PUBLIC_API_ROUTES_EXACT` (atau `PUBLIC_READONLY_CORS_API_ROUTES` untuk GET sahaja); hanya subpohon sebenar dimasukkan ke dalam `PUBLIC_API_ROUTE_PREFIXES`, dan ia **mesti berakhir dengan `/`**. Meletakkan satu laluan dalam senarai awalan turut menerbitkan setiap laluan bersebelahan yang berkongsi aksara permulaannya — termasuk laluan saudara segmen dinamik yang ditambah kemudian (GHSA-74g9-q8f6-793h). Kemas kini ujian unit di `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` dan `tests/unit/authz/classify.test.ts`.

## Skop

Tiga ruang nama. Setiap penyemak hanya membaca rentetan sendiri. Perbandingan bersebelahan,
termasuk mengapa `manage` gagal `scopeMatches` untuk `read:compression` dan mengapa token akses `read` tidak boleh `PATCH /api/keys/{id}`, adalah
[Tiga ruang nama skop](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Kunci API membawa tatasusunan `scopes` (disimpan sebagai JSON dalam `api_keys.scopes`, lihat `src/lib/db/apiKeys.ts`).

### Skop pengurusan

- `manage` / `admin` — `hasManageScope`. Akses pembawa ke laluan API pengurusan.
- `mcp:connect`, `self:usage`, `self:account-quota`, dan
  `policy:bypass-provider-quota` adalah skop padanan tepat tambahan. Ia berada
  di luar `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` hanya membuka laluan
  `/api/mcp/` yang bukan gelung balik.

### Skop alat MCP

Katalog dan peraturan padanan (rentetan yang sama, atau skop yang diberikan berakhir dengan `*`):
[Skop alat MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` dalam `src/shared/constants/mcpScopes.ts` adalah subset bertaip asal,
bukan katalog penuh itu. Penguatkuasaan berjalan dalam
`open-sse/mcp-server/scopeEnforcement.ts` selepas `resolveCallerScopeContext()`
menyelesaikan skop daripada maklumat pengesahan MCP, metadata permintaan, atau `OMNIROUTE_MCP_SCOPES`.
Ia kekal tidak aktif melainkan `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Skop token akses

`read` / `write` / `admin` pada token `oma_live_…`, disenaraikan mengikut `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Peringkat ini hanya terpakai pada
kelayakan token akses. Lihat [Pengesahan Pengurusan](../guides/MANAGEMENT-AUTH.md).

## Suis Pengesahan Diperlukan

`isAuthRequired()` dalam `src/shared/utils/apiAuth.ts` menentukan sama ada **sebarang** pengesahan dikuatkuasakan untuk sesuatu permintaan:

- `settings.requireLogin === false` → pengesahan dilumpuhkan secara global, kecuali bagi peringkat yang sentiasa dilindungi (lihat [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) dan panggilan yang menyerahkan kelayakan yang diterimanya, yang memerlukan kelayakan yang sama seperti apabila log masuk dihidupkan: mengeluarkan token penyegerakan, mencetak token akses CLI pada mana-mana skop, dan mencipta kunci API dengan skop `manage`/`admin`, memberikan skop tersebut kepada kunci, atau menjana semula atau mendedahkan kunci sedemikian (`requireCredentialForManagementScopedKey()` dalam `src/lib/api/requireManagementAuth.ts`). Kunci khusus inferens kekal terbuka.
- Tiada kata laluan dikonfigurasi **dan** tiada pembolehubah persekitaran `INITIAL_PASSWORD` → mod bootstrap: wizard pendaftaran dan permintaan loopback dibenarkan, tetapi permintaan rangkaian luaran masih memerlukan kelayakan.
- Sebarang ralat DB → gagal tertutup (selamat secara lalai).

Penguatkuasaan kunci API klien menggunakan `isRequireApiKeyEnabled()` dalam `src/shared/utils/featureFlags.ts`, bukan bacaan langsung `process.env.REQUIRE_API_KEY`. Ini penting bagi contoh yang dideploy: menukar `REQUIRE_API_KEY` dalam Papan Pemuka → Feature Flags menyimpan override DB dan segera memberi kesan kepada `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` dan semakan pengesahan API klien lain yang berkongsi pembantu ini. Jika stor feature flag tidak dapat dibaca, pengesahan API klien gagal tertutup dan memerlukan kunci.

## Perubahan Pecah Keserasian — v3.8.0

Titik akhir `/api/v1/agents/tasks/*` dan `/api/resilience/model-cooldowns` **kini memerlukan pengesahan pengurusan** (komit `588a0333`). Klien yang sebelum ini menghantar kunci API biasa tanpa skop `manage` akan menerima `403`. Migrasi: sama ada berikan skop `manage` kepada kunci dalam papan pemuka API Keys, atau gunakan sesi papan pemuka yang telah dilog masuk.

## Perubahan Tingkah Laku — v3.8.2

`/api/mcp/*` (pelayan MCP jauh) masih LOCAL_ONLY secara lalai tetapi kini menerima permintaan bukan gelung balik apabila pengepala `Authorization: Bearer <api-key>` membawa skop `manage`. Pengecualian ini dikawal secara eksplisit bagi setiap laluan melalui `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` dalam `src/server/authz/routeGuard.ts`; awalan LOCAL_ONLY yang setara, `/api/cli-tools/runtime/*`, sengaja TIDAK boleh dipintas kerana ia boleh mewujudkan subproses sewenang-wenangnya. Permintaan tanpa nama ke `/api/mcp/*` daripada bukan gelung balik terus mengembalikan `403 LOCAL_ONLY` — lalai bagi mana-mana laluan LOCAL_ONLY baharu kekal sebagai gelung balik ketat. Lihat [Tahap Pengawal Laluan](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Pengujian

- Ujian unit: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Senarai dibenarkan awam: `tests/unit/public-api-routes.test.ts`.
- Jalankan ujian khusus: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Penyahpepijatan

Saluran paip sentiasa mengecap respons dengan:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Untuk permintaan yang disahkan, pengepala permintaan huluan (sebelah pengendali) juga termasuk:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Gunakan `assertAuth(req, expectedClass)` dalam pengendali — ia membuang `AuthzAssertionError` dengan kod `AUTHZ_NOT_INITIALIZED` jika perisian tengah dipintas (bermanfaat untuk menangkap regresi konfigurasi dalam ujian).

## Lihat Juga

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — penanda pengesahan bagi setiap titik akhir
- [COMPLIANCE.md](../security/COMPLIANCE.md) — log audit untuk peristiwa pengesahan
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tiga ruang nama skop dan katalog skop alat MCP
- Sumber: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
