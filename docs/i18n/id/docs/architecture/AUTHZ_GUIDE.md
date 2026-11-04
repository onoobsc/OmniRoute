# Authorization Guide (Bahasa Indonesia)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Sumber kebenaran:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Terakhir diperbarui:** 2026-09-22 — namespace cakupan mengarah ke MCP-SERVER.md

OmniRoute memiliki pipeline otorisasi yang sadar rute yang menjaga setiap permintaan API. Klasifikasi bersifat **deterministik** dan **fail-closed** — apa pun yang tidak dapat diklasifikasikan akan berakhir sebagai `MANAGEMENT` dan memerlukan sesi atau token tingkat manajemen. Halaman ini menjelaskan model untuk insinyur yang memelihara rute atau merancang endpoint baru.

![Pipeline AuthZ (3 kelas rute + evaluasi kebijakan)](../diagrams/exported/authz-pipeline.svg)

> Sumber: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dua Mode Otentikasi

### 1. Kunci API (Pembawa)

Digunakan untuk klien OpenAI/Anthropic/Gemini-compatible APIs dan beberapa rute manajemen ketika kunci memiliki cakupan `manage`.

```
Authorization: Bearer <api-key>
```

Divalidasi oleh `isValidApiKey()` / `extractApiKey()` di `src/sse/services/auth.ts` dan diekspor kembali melalui `src/shared/utils/apiAuth.ts`. Validator juga menerima `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars sebagai kunci passthrough persisten (masalah #1350).

### 2. Sesi Dasbor (cookie auth_token)

Untuk halaman dasbor dan operasi admin.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Cookie adalah sesi hanya ketika JWT memverifikasi** Dan** membawa `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Setiap konsumen cookie (penjaga rute dasbor (`isDashboardSessionAuthenticated()`), penyegaran pipa authz, jabat tangan WebSocket, server langsung, `/api/settings/require-login`, `/api/auth/status`) melewati pembantu itu. JWTs lain yang ditandatangani dengan `JWT_SECRET` ada — Cursor CLI passthrough mencetak token `iss "omniroute" / aud "cursor-cli"` untuk pemegang kunci — dan tidak pernah berupa sesi (#13298).

Diverifikasi oleh `isDashboardSessionAuthenticated()` di `src/shared/utils/apiAuth.ts`. Pipeline secara otomatis menyegarkan JWT ketika masa pakainya kurang dari 7 hari dalam 30 hari.

Sesi juga dapat berakhir sebelum 30 hari habis, karena setiap pembuat melewati `mintDashboardSessionToken` (waktu penerbitan `iat` dan id `jti`) dan pemverifikasi memeriksa dua pengaturan: `sessionsValidAfter`, yang ditetapkan oleh perubahan kata sandi sehingga setiap sesi dikeluarkan sebelum berhenti memverifikasi (browser yang mengubah kata sandi mendapat cookie baru), dan `revokedDashboardSessions`, yang mana `POST /api/auth/logout` menambahkan `jti` sesi keluar. Sesi yang dibuat oleh rilis lama tidak memiliki klaim apa pun dan tetap valid hingga kata sandi pertama diubah. Jika pengaturan tidak dapat dibaca, sesi tersebut tidak dipercaya.

Beberapa rute manajemen menerima** salah satu** mode: cookie OR `Bearer <key>` ketika kunci API memiliki cakupan `manage` (atau `admin`). Inilah yang memungkinkan alur kerja "dapat dikonfigurasi melalui panggilan API " yang ditambahkan di v3.8.

#### Gerbang masuk OIDC opsional (#6973)

Login admin dashboard juga mendukung** ikut serta** OIDC (OpenID Connect) mengalir di samping login kata sandi default login kata sandi — tidak pernah dihapus, hanya ditambah:

- Dinonaktifkan kecuali `settings.oidcEnabled === true`** Dan** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` semuanya dikonfigurasi (Pengaturan → Auth). `GET /api/auth/oidc/login` mengembalikan `400` sebaliknya.
- `GET /api/auth/oidc/login` menemukan `authorization_endpoint` dari `/.well-known/openid-configuration` penerbit (kembali ke `<issuer>/authorize`), membuat pengalihan URI dari permintaan masuk (`x-forwarded-proto` -aware), dan mengalihkan ke IdP dengan `state` acak yang disimpan dalam cookie `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` memvalidasi `state`, menukar kode otorisasi, dan memverifikasi tanda tangan token ID melalui JWKS penerbit (`jose`'s `createRemoteJWKSet`, di-cache per JWKS URI) dengan pemeriksaan `issuer`/`audience`. Penerimaan dasbor memerlukan daftar `oidcAllowedSubjects` yang tidak kosong, kebijakan `oidcAdmissionClaim`, atau keduanya. Daftar subjek cocok dengan `sub` atau `email` hanya jika `email_verified === true`. Kebijakan klaim opsional menggunakan jalur klaim token ID yang dipisahkan titik (misalnya, `realm_access.roles`) dan serangkaian nilai yang diterima; klaim yang diselesaikan harus berupa array string yang berisi setidaknya satu nilai yang diterima. Jika kedua kebijakan dikonfigurasi, keduanya harus lolos. klaim Missing/malformed gagal ditutup, dan tanpa kebijakan apa pun, panggilan balik menolak masuk (`not_configured`). Konfigurasi khusus subjek yang ada tetap tidak berubah.
- Keycloak biasanya memetakan peran ranah ke dalam token akses, belum tentu token ID. Untuk memerlukan peran ranah `admin`, konfigurasikan pemeta protokol untuk klien ini yang menyertakan `realm_access.roles` di dalamnya** token ID** , lalu atur `oidcAdmissionClaim` ke `{ "path": "realm_access.roles", "values": ["admin"] }`. Periksa klaim token ID sebenarnya untuk klien ini sebelum mengaktifkan penerimaan peran saja; aplikasi tidak membaca peran token akses. Penolakan token sisi IdP dapat melengkapi namun tidak menggantikan pemeriksaan sisi aplikasi ini.
- Jika berhasil, ia akan mencetak** sama persis** 30 hari `auth_token` JWT masalah login kata sandi (`src/app/api/auth/login/route.ts`), sehingga alur sesi dasbor lainnya (penyegaran otomatis, tanda cookie) tidak berubah — OIDC hanya menggantikan cara cookie dicetak, bukan apa yang diberikannya. Perubahan pada IdP roles/groups tidak membuat sesi OmniRoute yang ada tidak valid; logout, rotasi kata sandi, atau berakhirnya sesi masih mengatur masa pakainya.
- Setiap pengaturan `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) ada di `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` menjawab `400 PASSWORD_REQUIRED` kecuali badan membawa kata sandi manajemen sebagai `currentPassword` (`401 PASSWORD_MISMATCH` bila salah). `oidcDisablePasswordLogin` menolak kata sandi _login_ (`POST /api/auth/login`) tetapi tetap menyimpan hash kata sandi yang disimpan, dan autentikasi ulang masih memeriksa `currentPassword` terhadapnya.
- `corsOrigins` dan `bruteForceProtection` juga ada di `SECURITY_IMPACTING_SETTINGS_KEYS` : melonggarkan keduanya akan melemahkan pertahanan login, sehingga mereka melakukan autentikasi ulang `currentPassword` yang sama (tab Keamanan memintanya) dan impor JSON menghapusnya.
- Setiap kunci kebijakan keamanan — entri `SECURITY_IMPACTING_SETTINGS_KEYS`, setiap kunci `oidc*` dan status sesi dasbor — adalah** khusus operator** pada `PATCH /api/settings`: kunci API dengan cakupan pengelolaan atau token akses `oma_` ditolak dengan `403` bahkan ketika ia mengirimkan `currentPassword` yang tepat, dan penolakan tersebut diaudit sebagai `settings.update_failed` dengan `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` di `src/lib/api/operatorCredential.ts`). Pengaturan biasa (tema, preferensi tampilan) tetap dapat ditulis untuk kunci `manage` atau token akses `admin`. Setiap mutasi `/api/settings` itu sendiri (dan `/api/settings/require-login`) juga memerlukan cakupan token akses `admin` (`ADMIN_MUTATION_EXACT_PATHS` di `src/server/authz/accessScopes.ts`, pencocokan jalur tepat); `GET` tetap `read`, dan sub-rute `/api/settings/*` lainnya (proksi, default kombo, alias model, kompresi, pembersihan…) mempertahankan cakupan `write` yang disimpulkan oleh metode.
- `POST /api/settings/import-json` melewatkan autentikasi ulang itu, sehingga ia membuang setiap kunci di `IMPORT_STRIPPED_SETTINGS_KEYS` (file yang sama) sebelum menulis: kata sandi dan `currentPassword`, setiap entri `SECURITY_IMPACTING_SETTINGS_KEYS`, dan status sesi dasbor (`sessionsValidAfter`, `revokedDashboardSessions`). Oleh karena itu, mengimpor cadangan lama tidak dapat menghidupkan kembali sesi yang perubahan kata sandinya atau keluarnya sudah berakhir.

#### Login dua faktor TOTP opsional (#16619)

Terdaftar dari Pengaturan → Keamanan; mati sampai operator menyalakannya (`src/server/auth/dashboardMfa.ts`).

- **Cakupannya:** login kata sandi (`POST /api/auth/login`, yang kemudian memerlukan `POST /api/auth/mfa/verify`) dan `omniroute connect` (`POST /api/cli/connect`, yang menolak pertukaran kata sandi saja dan mengambil kode sebagai `totp`).
- **Apa yang tidak dicakupnya:** OIDC / SSO sign-in (`/api/auth/oidc/callback`) tidak meminta OmniRoute TOTP. Ini bergantung pada faktor kedua milik penyedia identitas, jadi terapkan MFA di IdP jika OIDC diaktifkan.
- **Pemulihan** (perangkat hilang, tidak ada kode pemulihan yang tersisa, atau faktor yang tidak dapat diverifikasi lagi, misalnya setelah `STORAGE_ENCRYPTION_KEY` diubah):
  1. Mulai ulang server dengan `OMNIROUTE_DISABLE_MFA=true`.
  2. Di host itu sendiri (loopback peer dan loopback `Host`, seperti `http://localhost:20128`), masuk dengan kata sandi. Faktor kedua dilewati hanya untuk asal tersebut; setiap asal lainnya masih memerlukan kode tersebut.
  3. Di Pengaturan → Keamanan → Nonaktifkan, masukkan kata sandi dan biarkan kode kosong. `POST /api/auth/mfa/disable` menerima isi tanpa `code` hanya ketika variabel disetel dan permintaan datang dari host; itu masih memerlukan sesi dasbor dan kata sandi saat ini, dan diaudit sebagai `auth.mfa.disabled` dengan `secondFactor: "recovery_switch"`.
  4. Batalkan penyetelan `OMNIROUTE_DISABLE_MFA`, mulai ulang, dan daftarkan lagi jika diperlukan.

## Kelas Rute

`src/server/authz/types.ts` mendefinisikan tiga kelas; rute apa pun yang tidak dapat diklasifikasikan secara deterministik akan jatuh kembali ke `MANAGEMENT`.

| Kelas        | Deskripsi                                                                                                                                           | Autentikasi yang diperlukan                                                |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| `PUBLIC`     | Rute yang secara eksplisit aman — login, logout, status, inisialisasi, health, dan bootstrap onboarding.                                            | Tidak ada                                                                  |
| `CLIENT_API` | Endpoint penyajian model — `/api/v1/*`, `/api/v1beta/*`, plus alias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Kunci Bearer ketika feature flag `REQUIRE_API_KEY` yang efektif diaktifkan |
| `MANAGEMENT` | Halaman dashboard, pengaturan, provider, kunci, dan endpoint admin serta diagnostik.                                                                | Sesi dashboard ATAU Bearer dengan cakupan `manage`                         |

Beberapa aksi `MANAGEMENT` bersifat **khusus operator**: kunci `manage` tidak cukup. Mengekspor kredensial tersimpan (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), memulihkan cadangan di atas data aktif (`POST /api/db-backups/import` termasuk `dryRun=true`, `POST /api/db-backups` pemulihan berdasarkan id, `POST /api/settings/import-json`), dan menghancurkan titik pemulihan (`DELETE /api/db-backups` untuk pembersihan, dan `PATCH /api/db-backups` karena retensi yang disimpannya menggerakkan pemangkasan otomatis setelah setiap cadangan) memerlukan sesi dashboard, subjek CLI lokal, atau login yang dinonaktifkan. Menerbitkan token sinkronisasi (`POST /api/sync/tokens`) dan mencetak token akses CLI `admin` (`POST /api/cli/tokens`) memerlukan sesi dashboard atau subjek CLI lokal di setiap mode login. Kunci API dengan cakupan apa pun dan token akses `oma_` bukan kredensial operator: mereka mendapat `403` setiap kali salah satunya diperlukan. Pemeriksaannya ada di `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Mengubah pengaturan login juga khusus operator: `POST /api/settings/require-login` (mengatur kata sandi manajemen / mengaktifkan-menonaktifkan `requireLogin`) hanya menerima kredensial tersebut setelah kata sandi ada — jendela bootstrap pertama kali (belum ada kata sandi) tidak berubah — dan sesi dashboard harus mengirim `currentPassword` untuk mengganti kata sandi (`403` jika tidak ada atau salah, dicatat sebagai `settings.update_failed`). CLI lokal dan instans dengan login dinonaktifkan mempertahankan jalur pemulihan dan dapat mengatur kata sandi tanpanya, karena keduanya terikat pada host yang memiliki direktori data.

## Saluran pipa

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

Header internal tepercaya (didefinisikan dalam `src/server/authz/headers.ts`) adalah** dihapus dari permintaan masuk** sebelum klasifikasi — klien tidak dapat mengisi `x-omniroute-auth-*` terlebih dahulu untuk meniru subjek.

### Kontrak kebijakan

Setiap kelas rute memiliki kebijakan di `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — selalu mengembalikan `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — mengekstrak Pembawa, memvalidasi melalui `validateApiKey()`. Masuk ke anonim hanya ketika tanda fitur `REQUIRE_API_KEY` yang efektif dinonaktifkan. Bendera yang efektif diselesaikan melalui `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) sehingga Bendera Fitur Dasbor dan variabel lingkungan mengatur `/api/v1/*`, `/api/v1beta/*`, dan alias secara konsisten; kegagalan penyelesai gagal ditutup. Mengizinkan permintaan sesi dasbor pada rute API klien (termasuk `/api/v1/models`, yang digunakan oleh katalog model dasbor). Ketika Entra ID SSO diaktifkan, Pembawa yang secara struktural merupakan token Entra (tiga segmen base64url, `RS*` alg, `kid`) ditangani oleh cabang SSO** sebelum** `validateApiKey()` dan putusannya bersifat final — tidak pernah masuk ke jalur kunci API atau cabang degradasi ke anonim, sehingga penghentian penyedia identitas tidak dapat menjadi akses terbuka. Kunci API statis tidak terpengaruh. Lihat [Masuk ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — menerima sesi dasbor, permintaan sinkronisasi model internal (cocok dengan `/api/providers/[name]/(sync-models|models)`), atau melompati seluruhnya jika `isAuthRequired()` mengembalikan false. Mengembalikan 403 (`AUTH_001`) ketika token Pembawa ada tetapi tidak valid, 401 sebaliknya. Juga menerapkan tingkatan penjaga rute (LOCAL_ONLY / ALWAYS_PROTECTED) sebelum cabang autentikasi mana pun — lihat [Tingkatan Penjaga Rute](../security/ROUTE_GUARD_TIERS.md). jalur LOCAL_ONLY di `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (hari ini: `/api/mcp/`) dapat diakses dari non-loopback ketika kunci Pembawa membawa cakupan `manage` ; semua jalur LOCAL_ONLY lainnya tetap loopback ketat terlepas dari cakupannya.

Kebijakan yang berhasil mengembalikan `AuthSubject` dengan `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Penangan hilir dapat membacanya melalui `assertAuth(request, "CLIENT_API")` di `src/server/authz/assertAuth.ts` alih-alih menjalankan kembali logika autentikasi.

## Daftar Rute Umum

`src/shared/constants/publicApiRoutes.ts` adalah daftar yang diizinkan secara eksplisit:

Daftar ini dibagi berdasarkan** membentuk** , dan pemisahannya bersifat menahan beban (GHSA-74g9-q8f6-793h): awalan dicocokkan dengan `startsWith()`, sehingga juga cocok dengan setiap jalur berdekatan yang berbagi karakter utamanya. `/api/usage/om-usage` sebagai awalan bertanda `/api/usage/om-usage<anything>` PUBLIC, dan Next menyelesaikannya menjadi `/api/usage/[connectionId]` — penangan tanpa autentikasinya sendiri.

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

Rute hanya-baca bersifat publik** hanya** untuk metode yang aman. Catatan: `classifyRoute()` mengecualikan `/api/v1/*` dan `/api/v1beta/*` dari PUBLIC fall-through — yang selalu `CLIENT_API` sehingga kebijakan Bearer-key tetap berlaku.

## Menambahkan Rute Baru

### Pola 1 — Endpoint API klien publik (autentikasi Bearer)

Rute di bawah `/api/v1/` dan `/api/v1beta/` diklasifikasikan sebagai `CLIENT_API` secara otomatis. Middleware menerapkan pemeriksaan Bearer; handler rute tidak perlu mengulanginya, tetapi dapat membaca subjek jika diperlukan.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... logika handler
}
```

### Pola 2 — Endpoint pengelolaan (sesi atau Bearer + manage)

Gunakan `requireManagementAuth()` dari `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... logika handler
}
```

`requireManagementAuth()` mengembalikan `null` jika berhasil atau `Response` kesalahan JSON:

- 401 `AUTH_001` "Autentikasi diperlukan" — tidak ada kredensial sama sekali
- 403 — Bearer tidak valid **atau** Bearer tersedia tetapi kunci tidak memiliki scope `manage` / `admin`

`hasManageScope(scopes)` mengembalikan true untuk `"manage"` atau `"admin"`.

### Pola 3 — Menambahkan ke daftar izin publik

Pilih himpunan berdasarkan bentuk, bukan berdasarkan kemudahan. Satu rute dimasukkan ke `PUBLIC_API_ROUTES_EXACT` (atau `PUBLIC_READONLY_CORS_API_ROUTES` jika hanya untuk GET); hanya subtree yang sebenarnya yang dimasukkan ke `PUBLIC_API_ROUTE_PREFIXES`, dan entri tersebut **harus diakhiri dengan `/`**. Memasukkan satu rute ke daftar prefiks juga memublikasikan setiap path berdekatan yang memiliki karakter awal yang sama — termasuk sibling segmen dinamis yang ditambahkan kemudian (GHSA-74g9-q8f6-793h). Perbarui pengujian unit di `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts`, dan `tests/unit/authz/classify.test.ts`.

## Cakupan

Tiga namespace. Setiap pemeriksa hanya membaca stringnya sendiri. Perbandingan berdampingan, termasuk mengapa `manage` gagal `scopeMatches` untuk `read:compression` dan mengapa token akses `read` tidak dapat `PATCH /api/keys/{id}`, ada di [Tiga namespace cakupan](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Kunci API membawa array `scopes` (disimpan sebagai JSON di `api_keys.scopes`, lihat `src/lib/db/apiKeys.ts`).

### Cakupan manajemen

- `manage` / `admin` — `hasManageScope`. Akses bearer ke rute API manajemen.
- `mcp:connect`, `self:usage`, `self:account-quota`, dan
  `policy:bypass-provider-quota` adalah cakupan pencocokan persis yang aditif. Mereka berada di luar `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` hanya membuka bagian non-loopback `/api/mcp/`.

### Cakupan alat MCP

Katalog dan aturan pencocokan (string identik, atau cakupan yang diberikan diakhiri dengan `*`):
[Cakupan alat MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` di `src/shared/constants/mcpScopes.ts` adalah subset yang diketik asli, bukan katalog lengkap itu. Penegakan berjalan di
`open-sse/mcp-server/scopeEnforcement.ts` setelah `resolveCallerScopeContext()` menyelesaikan cakupan dari info otentikasi MCP, metadata permintaan, atau `OMNIROUTE_MCP_SCOPES`.
Ini tetap mati kecuali `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Cakupan token akses

`read` / `write` / `admin` pada token `oma_live_…`, diberi peringkat oleh `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Peringkat ini hanya berlaku untuk kredensial token akses. Lihat [Otentikasi Manajemen](../guides/MANAGEMENT-AUTH.md).

## Sakelar Autentikasi Wajib

`isAuthRequired()` di `src/shared/utils/apiAuth.ts` memutuskan apakah **autentikasi apa pun** diterapkan untuk sebuah permintaan:

- `settings.requireLogin === false` → autentikasi dinonaktifkan secara global, kecuali untuk tingkat yang selalu dilindungi (lihat [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) dan panggilan yang menyerahkan kredensial yang diterimanya, yang memerlukan kredensial yang sama seperti ketika login aktif: menerbitkan token sinkronisasi, mencetak token akses CLI pada cakupan apa pun, dan membuat kunci API dengan cakupan `manage`/`admin`, memberikan cakupan tersebut ke sebuah kunci, atau meregenerasi atau menampilkan kunci seperti itu (`requireCredentialForManagementScopedKey()` di `src/lib/api/requireManagementAuth.ts`). Kunci khusus inferensi tetap terbuka.
- Belum ada kata sandi yang dikonfigurasi **dan** tidak ada env var `INITIAL_PASSWORD` → mode bootstrap: wizard onboarding dan permintaan loopback diizinkan, tetapi permintaan jaringan eksternal tetap memerlukan kredensial.
- Kesalahan DB apa pun → gagal tertutup (aman secara default).

Penegakan kunci API klien menggunakan `isRequireApiKeyEnabled()` di `src/shared/utils/featureFlags.ts`, bukan pembacaan langsung `process.env.REQUIRE_API_KEY`. Ini penting untuk instans yang di-deploy: mengubah `REQUIRE_API_KEY` di Dashboard → Feature Flags menyimpan override DB dan langsung memengaruhi `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*`, dan pemeriksaan autentikasi API klien lainnya yang memakai helper ini. Jika penyimpanan feature flag tidak dapat dibaca, autentikasi API klien gagal tertutup dan mewajibkan kunci.

## Perubahan yang Tidak Kompatibel — v3.8.0

Endpoint `/api/v1/agents/tasks/*` dan `/api/resilience/model-cooldowns` **kini memerlukan autentikasi pengelolaan** (commit `588a0333`). Klien yang sebelumnya mengirimkan kunci API biasa tanpa cakupan `manage` akan menerima `403`. Migrasi: berikan cakupan `manage` pada kunci tersebut di dasbor Kunci API, atau gunakan sesi dasbor yang telah login.

## Perubahan Perilaku — v3.8.2

`/api/mcp/*` (server MCP jarak jauh) masih bersifat LOCAL_ONLY secara default, tetapi kini menerima permintaan non-loopback ketika header `Authorization: Bearer <api-key>` memiliki cakupan `manage`. Pengecualian ini dibatasi secara eksplisit per jalur melalui `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` di `src/server/authz/routeGuard.ts`; prefiks LOCAL_ONLY terkait `/api/cli-tools/runtime/*` sengaja TIDAK dapat dilewati karena dapat menjalankan subproses arbitrer. Permintaan anonim ke `/api/mcp/*` dari non-loopback akan tetap menghasilkan `403 LOCAL_ONLY` — perilaku default untuk setiap jalur LOCAL_ONLY baru tetap loopback-ketat. Lihat [Tingkatan Pengaman Rute](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Pengujian

- Pengujian unit: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Daftar izin publik: `tests/unit/public-api-routes.test.ts`.
- Jalankan pengujian terfokus: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Men-debug

Pipeline selalu menandai respons dengan:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Untuk permintaan yang diautentikasi, header permintaan upstream (sisi pengendali) juga mencakup:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Gunakan `assertAuth(req, expectedClass)` di dalam penangan — ia melempar `AuthzAssertionError` dengan kode `AUTHZ_NOT_INITIALIZED` jika middleware dilewati (berguna untuk menangkap regresi konfigurasi dalam pengujian).

## Lihat Juga

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — penanda otentikasi per endpoint
- [COMPLIANCE.md](../security/COMPLIANCE.md) — log audit untuk peristiwa otentikasi
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — tiga namespace cakupan dan katalog cakupan alat MCP
- Sumber: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
