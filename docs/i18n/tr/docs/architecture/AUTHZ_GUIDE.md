# Authorization Guide (Türkçe)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Doğruluk Kaynağı:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Son Güncelleme:** 2026-09-22 — kapsam ad alanları `MCP-SERVER.md`'yi işaret ediyor

OmniRoute, her API isteğini denetleyen rota-farkındalıklı bir yetkilendirme hattına sahiptir. Sınıflandırma **deterministik** ve **kapalı-güvenli**dir — sınıflandırılamayan her şey `MANAGEMENT` olarak sonuçlanır ve bir oturum veya yönetim düzeyinde bir jeton gerektirir. Bu sayfa, rotaları sürdüren veya yeni uç noktalar tasarlayan mühendisler için modeli açıklar.

![Yetkilendirme hattı (3 rota sınıfı + politika değerlendirmesi)](../diagrams/exported/authz-pipeline.svg)

> Kaynak: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## İki Kimlik Doğrulama Modu

### 1. API Anahtarı (Taşıyıcı)

Anahtar `manage` kapsamına sahip olduğunda OpenAI/Anthropic/Gemini-compatible istemcisi APIs ve birkaç yönetim rotası için kullanılır.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` `isValidApiKey()` / `extractApiKey()` tarafından doğrulandı ve `src/shared/utils/apiAuth.ts` aracılığıyla yeniden dışa aktarıldı. Doğrulayıcı ayrıca `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env değişkenlerini kalıcı geçiş anahtarları olarak kabul eder ( #1350 sorunu).

### 2. Kontrol Paneli Oturumu (auth_token çerezi)

Kontrol paneli sayfaları ve yönetici işlemleri için.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Bir çerez yalnızca JWT doğrulandığında bir oturumdur** Ve** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) taşır. Çerezin her tüketicisi (kontrol paneli rota koruması (`isDashboardSessionAuthenticated()`), authz boru hattı yenilemesi, WebSocket anlaşması, canlı sunucu, `/api/settings/require-login`, `/api/auth/status`) bu yardımcıdan geçer. `JWT_SECRET` ile imzalanan diğer JWTs Cursor CLI doğrudan geçişli —, — anahtar sahipleri için `iss "omniroute" / aud "cursor-cli"` belirteçlerinde mevcuttur ve hiçbir zaman oturum değildir (#13298).

`src/shared/utils/apiAuth.ts` `isDashboardSessionAuthenticated()` tarafından doğrulandı. İşlem hattı, 30 günlük ömründe 7 günden az süre kaldığında JWT otomatik olarak yeniler.

Bir oturum 30 gün dolmadan da sona erebilir, çünkü her toplantı `mintDashboardSessionToken` (bir sorun zamanı `iat` ve bir kimlik `jti`) geçer ve doğrulayıcı iki ayarı kontrol eder: `sessionsValidAfter`, doğrulamayı durdurmadan önce yayınlanan her oturum için bir şifre değişikliğiyle ayarlanır (şifreyi değiştiren tarayıcı yeni bir çerez alır) ve `POST /api/auth/logout` oturum kapatılan oturumun `jti` eklediği `revokedDashboardSessions`. Daha eski bir sürüm tarafından oluşturulan oturumlar herhangi bir hak talebinde bulunmaz ve ilk şifre değişikliğine kadar geçerli kalır. Ayarlar okunamıyorsa oturum güvenilir değildir.

Bazı yönetim yolları kabul eder** herhangi biri** mod: API anahtarı `manage` (veya `admin`) kapsamına sahip olduğunda çerez OR `Bearer <key>`. Bu, v3.8'de eklenen " API çağrıları yoluyla yapılandırılabilir" iş akışını etkinleştiren şeydir.

#### İsteğe bağlı OIDC giriş kapısı (#6973)

Kontrol paneli yönetici girişi aynı zamanda bir** katılım** OIDC (OpenID Connect) akışı, varsayılan parola girişiyle birlikte — parola girişi hiçbir zaman kaldırılmaz, yalnızca eklenir:

- `settings.oidcEnabled === true` olmadığı sürece devre dışı** Ve** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` tümü yapılandırılmıştır (Ayarlar → Kimlik Doğrulaması). aksi takdirde `GET /api/auth/oidc/login` `400` döndürür.
- `GET /api/auth/oidc/login` verenin `/.well-known/openid-configuration` `authorization_endpoint` keşfeder ( `<issuer>/authorize` geri döner), gelen istekten URI yönlendirmesini oluşturur (`x-forwarded-proto` -aware) ve bir `httpOnly` `oidc_state` çerezinde depolanan rastgele bir `state` ile IdP yeniden yönlendirir.
- `GET /api/auth/oidc/callback`, `state` doğrular, yetkilendirme kodunu değiştirir ve ID belirtecinin imzasını, verenin JWKS (`jose` `createRemoteJWKSet`, JWKS URI başına önbelleğe alınmış) aracılığıyla `issuer`/`audience` kontrolleriyle doğrular. Kontrol paneline kabul, boş olmayan bir `oidcAllowedSubjects` listesi, bir `oidcAdmissionClaim` politikası veya her ikisini birden gerektirir. Konu listesi `sub` veya `email` ile yalnızca `email_verified === true` olduğunda eşleşir. İsteğe bağlı talep politikası, noktalarla ayrılmış bir kimlik belirteci talep yolunu (örneğin, `realm_access.roles`) ve kabul edilen değerlerin bir dizisini alır; çözümlenen talep, en az bir kabul edilen değer içeren bir dize dizisi olmalıdır. Her iki politika da yapılandırılmışsa her ikisinin de geçmesi gerekir. Missing/malformed talepleri kapatılamaz ve her iki politika olmadan geri arama oturum açmayı reddeder (`not_configured`). Mevcut yalnızca konuya yönelik yapılandırmalar değişmeden kalır.
- Keycloak normalde bölge rollerini ID belirteçleriyle değil, erişim belirteçleriyle eşler. `admin` bölge rolünü gerektirmek için, bu istemciye yönelik olarak `realm_access.roles` içeren bir protokol eşleyici yapılandırın.**ID jetonu** , ardından `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` olarak ayarlayın. Yalnızca rol kabulünü etkinleştirmeden önce bu istemcinin gerçek kimlik belirteci talebini kontrol edin; uygulama erişim belirteci rollerini okumaz. IdP tarafı jeton reddi, bu uygulama tarafı kontrolünü tamamlayabilir ancak yerini almaz.
- Başarı üzerine şunu darp eder:** tamamen aynı** 30 günlük `auth_token` JWT şifreyle oturum açma sorunları (`src/app/api/auth/login/route.ts`), dolayısıyla kontrol paneli oturum hattının geri kalanı (otomatik yenileme, çerez işaretleri) değişmez — OIDC, sağladığı şeyin yerine yalnızca çerezin nasıl basıldığını değiştirir. IdP roles/groups yapılan değişiklikler mevcut OmniRoute oturumlarını geçersiz kılmaz; oturum kapatma, şifre rotasyonu veya oturumun sona ermesi hâlâ kullanım ömürlerini yönetmektedir.
- Her `oidc*` ayarı (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) içindedir: `PATCH /api/settings` vücut yönetim şifresini `currentPassword` olarak taşımadığı sürece `400 PASSWORD_REQUIRED` yanıt verir (yanlış olduğunda `401 PASSWORD_MISMATCH` ). `oidcDisablePasswordLogin` _login_ (`POST /api/auth/login`) şifresini reddeder ancak saklanan şifre karmasını korur ve yeniden kimlik doğrulama, `currentPassword` buna göre kontrol etmeye devam eder.
- `corsOrigins` ve `bruteForceProtection` de `SECURITY_IMPACTING_SETTINGS_KEYS` : gevşetmek oturum açma savunmasını zayıflatır, bu nedenle aynı `currentPassword` yeniden kimlik doğrulamasını alırlar (Güvenlik sekmesi bunu ister) ve JSON içe aktarma bunları düşürür.
- Her güvenlik politikası anahtarı — `SECURITY_IMPACTING_SETTINGS_KEYS` girişleri, her `oidc*` anahtarı ve kontrol paneli oturum durumu —,** yalnızca operatör** `PATCH /api/settings` üzerinde: yönetim kapsamlı bir API anahtarı veya bir `oma_` erişim belirteci, doğru `currentPassword` gönderse bile `403` ile reddedilir ve ret, `reason: OPERATOR_REQUIRED` ile `settings.update_failed` olarak denetlenir ( `src/lib/api/operatorCredential.ts` `requireOperatorCredential()` ). Sıradan ayarlar (tema, görüntüleme tercihleri), bir `manage` anahtarı veya `admin` erişim belirteci için yazılabilir durumda kalır. `/api/settings` (ve `/api/settings/require-login`) her mutasyonu aynı zamanda `admin` erişim belirteci kapsamına da ihtiyaç duyar ( `src/server/authz/accessScopes.ts` `ADMIN_MUTATION_EXACT_PATHS`, tam yol eşleşmesi); `GET`, `read` olarak kalır ve diğer `/api/settings/*` alt rotaları (proxy'ler, birleşik varsayılanlar, model takma adları, sıkıştırma, temizlemeler…) yöntemden çıkarılan `write` kapsamını korur.
- `POST /api/settings/import-json` bu yeniden kimlik doğrulamayı atlar, bu nedenle yazmadan önce `IMPORT_STRIPPED_SETTINGS_KEYS` (aynı dosya) her anahtarı bırakır: şifre ve `currentPassword`, her `SECURITY_IMPACTING_SETTINGS_KEYS` girişi ve kontrol paneli oturum durumu (`sessionsValidAfter`, `revokedDashboardSessions`). Bu nedenle, daha eski bir yedeğin içe aktarılması, parola değişikliğinin veya oturumu kapatmanın zaten sona erdiği bir oturumu yeniden canlandıramaz.

#### İsteğe bağlı TOTP iki faktörlü oturum açma (#16619)

Ayarlar → Güvenlik'ten kaydoldum; operatör onu açana kadar kapalıdır (`src/server/auth/dashboardMfa.ts`).

- **Neleri kapsar:** şifre girişi (`POST /api/auth/login`, daha sonra `POST /api/auth/mfa/verify` ihtiyaç duyar) ve `omniroute connect` (`POST /api/cli/connect`, yalnızca şifre değişimini reddeder ve kodu `totp` olarak alır).
- **Neleri kapsamaz:** OIDC / SSO oturum açma (`/api/auth/oidc/callback`), OmniRoute TOTP istemez. Kimlik sağlayıcının kendi ikinci faktörüne dayanır, dolayısıyla OIDC etkinse IdP MFA zorunlu kılın.
- **İyileşmek** (cihazın kaybolması, kurtarma kodunun kalmaması veya artık doğrulanamayan bir faktör, örneğin `STORAGE_ENCRYPTION_KEY` değiştirildikten sonra):
  1. Sunucuyu `OMNIROUTE_DISABLE_MFA=true` ile yeniden başlatın.
  2. Ana bilgisayarın kendisinde ( `http://localhost:20128` gibi geridöngü eşi ve geridöngü `Host`), parolayla oturum açın. İkinci faktör yalnızca bu köken için atlanır; diğer tüm kökenlerin hala koda ihtiyacı var.
  3. Ayarlar → Güvenlik → Devre Dışı Bırak'ta şifreyi girin ve kodu boş bırakın. `POST /api/auth/mfa/disable` `code` bir gövdeyi yalnızca değişken ayarlandığında ve istek ana bilgisayardan geldiğinde kabul eder; yine de kontrol paneli oturumunu ve mevcut şifreyi gerektirir ve `secondFactor: "recovery_switch"` ile `auth.mfa.disabled` olarak denetlenir.
  4. `OMNIROUTE_DISABLE_MFA` ayarını kaldırın, yeniden başlatın ve gerekirse yeniden kaydolun.

## Rota Sınıfları

`src/server/authz/types.ts` üç sınıf tanımlar; deterministik olarak sınıflandırılamayan her rota `MANAGEMENT` sınıfına geri döner.

| Sınıf        | Açıklama                                                                                                                                                | Gerekli kimlik doğrulama                                       |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| `PUBLIC`     | Açıkça güvenli rotalar — giriş, çıkış, durum, başlatma, sağlık ve başlangıç kurulumu uç noktaları.                                                      | Yok                                                            |
| `CLIENT_API` | Model sunum uç noktaları — `/api/v1/*`, `/api/v1beta/*` ve takma adlar: `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Etkin `REQUIRE_API_KEY` özellik bayrağı açıksa Bearer anahtarı |
| `MANAGEMENT` | Kontrol paneli sayfaları, ayarlar, sağlayıcılar, anahtarlar, yönetim ve tanılama uç noktaları.                                                          | Kontrol paneli oturumu VEYA `manage` kapsamlı Bearer           |

Bazı `MANAGEMENT` işlemleri **yalnızca operatöre** özeldir: `manage` anahtarı yetmez. Saklanan kimlik bilgilerini dışa aktarmak (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), canlı verilerin üzerine bir yedeği geri yüklemek (`dryRun=true` dahil `POST /api/db-backups/import`, kimlikle geri yükleme `POST /api/db-backups` ve `POST /api/settings/import-json`) ve geri yükleme noktalarını yok etmek (`DELETE /api/db-backups` temizliği ve `PATCH /api/db-backups`, çünkü kalıcı hale getirdiği saklama süresi her yedeklemeden sonraki otomatik temizliği yönetir) bir kontrol paneli oturumu, yerel CLI öznesi veya devre dışı bırakılmış giriş gerektirir. Senkronizasyon token'ı üretmek (`POST /api/sync/tokens`) ve `admin` CLI erişim token'ı basmak (`POST /api/cli/tokens`) her giriş modunda kontrol paneli oturumu veya yerel CLI öznesi gerektirir. Her kapsamdaki API anahtarları ve `oma_` erişim token'ları operatör kimlik bilgisi değildir: gerektiğinde `403` alırlar. Denetim `src/lib/api/operatorCredential.ts` içinde yapılır (`resolveOperatorCredential()` / `requireOperatorCredential()`). Giriş ayarlarını değiştirmek de yalnızca operatöre özeldir: `POST /api/settings/require-login` (yönetim şifresini ayarlama / `requireLogin` değiştirme), bir şifre var olduktan sonra yalnızca bu kimlik bilgilerini kabul eder — ilk kurulum önyükleme penceresi (henüz şifre yoksa) değişmez — ve bir kontrol paneli oturumunun şifreyi değiştirmek için `currentPassword` göndermesi gerekir (eksik veya yanlışsa `403`, `settings.update_failed` olarak denetlenir). Yerel CLI ve girişi devre dışı bırakılmış bir örnek kurtarma yolunu korur ve şifreyi onsuz ayarlayabilir; çünkü ikisi de veri dizinine sahip ana makineye bağlıdır.

## Boru hattı

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

Güvenilir dahili başlıklar ( `src/server/authz/headers.ts` tanımlanmıştır)** gelen isteklerden çıkarıldı** sınıflandırmadan önce — istemcileri bir öznenin kimliğine bürünmek için `x-omniroute-auth-*` önceden dolduramaz.

### Politika sözleşmeleri

Her rota sınıfının `src/server/authz/policies/` bir politikası vardır:

- **`publicPolicy`** (`policies/public.ts`) — her zaman `allow({ kind: "anonymous", id: "anonymous" })` değerini döndürür.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — Taşıyıcıyı çıkarır, `validateApiKey()` aracılığıyla doğrular. Yalnızca etkili `REQUIRE_API_KEY` özelliği bayrağı devre dışı bırakıldığında anonim hale gelir. Etkin bayrak `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) aracılığıyla çözümlenir, böylece Kontrol Paneli Özellik Bayrakları ve ortam değişkenleri `/api/v1/*`, `/api/v1beta/*` ve takma adları tutarlı bir şekilde yönetir; çözümleyici hataları başarısız bir şekilde kapatılır. İstemci API rotalarında kontrol paneli oturumu isteklerine izin verir (pano modeli kataloğu tarafından kullanılan `/api/v1/models` dahil). Entra ID SSO etkinleştirildiğinde, yapısal olarak bir Entra belirteci olan bir Taşıyıcı (üç base64url bölümü, `RS*` alg, `kid`), SSO dalı tarafından işlenir** önce** `validateApiKey()` ve onun kararı nihaidir, — hiçbir zaman API anahtarı yoluna veya anonim şubeye düşmez, dolayısıyla kimlik sağlayıcı kesintisi açık erişime dönüşemez. Statik API anahtarları etkilenmez. Bkz. [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — kontrol paneli oturumunu, dahili model senkronizasyonu isteklerini ( `/api/providers/[name]/(sync-models|models)` ile eşleşen) kabul eder veya `isAuthRequired()` false değerini döndürürse tamamen atlar. Bir Taşıyıcı belirteci mevcut ancak geçersiz olduğunda 403 (`AUTH_001`), aksi durumda 401 değerini döndürür. Ayrıca herhangi bir kimlik doğrulama dalından önce rota koruma katmanlarını (LOCAL_ONLY / ALWAYS_PROTECTED) uygular — bkz. [Rota Koruma Katmanları](../security/ROUTE_GUARD_TIERS.md). Taşıyıcı anahtarı `manage` kapsamını taşıdığında, `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (bugün: `/api/mcp/`) LOCAL_ONLY yollarına geri döngüsüz olarak erişilebilir; diğer tüm LOCAL_ONLY yolları kapsamdan bağımsız olarak katı geri döngü olarak kalır.

Başarılı bir politika `AuthSubject` `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` ile döndürür. Aşağı akış işleyicileri, kimlik doğrulama mantığını yeniden çalıştırmak yerine `src/server/authz/assertAuth.ts` `assertAuth(request, "CLIENT_API")` aracılığıyla okuyabilir.

## Genel Rotalar Listesi

`src/shared/constants/publicApiRoutes.ts` açık izin verilenler listesidir:

Liste şu şekilde bölünmüştür:** şekil** ve bölme yük taşır (GHSA-74g9-q8f6-793h): bir önek `startsWith()` ile eşleştirilir, böylece baş karakterlerini paylaşan her bitişik yolla da eşleşir. `/api/usage/om-usage` `/api/usage/om-usage<anything>` PUBLIC olarak işaretlenmiş bir önek olarak kullanır ve Next, bunu kendi kimlik doğrulaması olmayan bir `/api/usage/[connectionId]` — işleyicisine çözümler.

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

Salt okunur rotalar herkese açıktır** sadece** Güvenli yöntemler için. Not: `classifyRoute()` `/api/v1/*` ve `/api/v1beta/*` PUBLIC geçiş — hariç tutar; bunlar her zaman `CLIENT_API`, dolayısıyla Taşıyıcı anahtar politikası hala geçerlidir.

## Yeni Bir Rota Ekleme

### Kalıp 1 — Herkese açık istemci API uç noktası (Bearer kimlik doğrulaması)

`/api/v1/` ve `/api/v1beta/` altındaki rotalar otomatik olarak `CLIENT_API` şeklinde sınıflandırılır. Ara yazılım Bearer denetimini uygular; rota işleyicilerinin bunu tekrarlaması gerekmez, ancak yararlıysa özneyi okuyabilirler.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... işleyici mantığı
}
```

### Kalıp 2 — Yönetim uç noktası (oturum veya Bearer + manage)

`src/lib/api/requireManagementAuth.ts` dosyasındaki `requireManagementAuth()` işlevini kullanın:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... işleyici mantığı
}
```

`requireManagementAuth()`, başarı durumunda `null`, hata durumunda ise bir JSON `Response` döndürür:

- 401 `AUTH_001` "Kimlik doğrulaması gerekli" — hiçbir kimlik bilgisi yok
- 403 — geçersiz Bearer **veya** Bearer mevcut ancak anahtar `manage` / `admin` kapsamına sahip değil

`hasManageScope(scopes)`, `"manage"` veya `"admin"` için true döndürür.

### Kalıp 3 — Herkese açık izin listesine ekleme

Kümeyi kullanım kolaylığına göre değil, şekle göre seçin. Tek bir rota `PUBLIC_API_ROUTES_EXACT` kümesine (veya yalnızca GET için `PUBLIC_READONLY_CORS_API_ROUTES` listesine) eklenir; yalnızca gerçek bir alt ağaç `PUBLIC_API_ROUTE_PREFIXES` listesine eklenir ve `/` ile **bitmelidir**. Tek bir rotayı önek listesine eklemek, daha sonra eklenecek dinamik segmentli kardeşler de dahil olmak üzere, baştaki karakterlerini paylaşan tüm bitişik yolları da herkese açar (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` ve `tests/unit/authz/classify.test.ts` dosyalarındaki birim testlerini güncelleyin.

## Kapsamlar

Üç ad alanı. Her denetleyici yalnızca kendi dizelerini okur. Yan yana karşılaştırma, `manage`'in `read:compression` için `scopeMatches`'i neden başarısız kıldığını ve bir `read` erişim belirtecinin neden `/api/keys/{id}` adresine `PATCH` yapamadığını içeren detaylar [Üç kapsam ad alanı](../frameworks/MCP-SERVER.md#three-scope-namespaces) bölümündedir.

API anahtarları bir `scopes` dizisi taşır (`api_keys.scopes` içinde JSON olarak saklanır, bkz. `src/lib/db/apiKeys.ts`).

### Yönetim kapsamı

- `manage` / `admin` — `hasManageScope`. Yönetim API rotalarına taşıyıcı erişimi.
- `mcp:connect`, `self:usage`, `self:account-quota` ve `policy:bypass-provider-quota` eklemeli tam eşleşen kapsamlardır. Bunlar `MANAGEMENT_API_KEY_SCOPES` dışında yer alır. `mcp:connect` yalnızca `/api/mcp/` döngüsel olmayan ayrılmış bölümünü açar.

### MCP araç kapsamları

Katalog ve eşleştirme kuralları (aynı dize veya `*` ile biten verilmiş bir kapsam): [MCP araç kapsamları](../frameworks/MCP-SERVER.md#mcp-tool-scopes). `src/shared/constants/mcpScopes.ts` içindeki `MCP_SCOPE_LIST`, tam katalog değil, orijinal yazılmış alt kümedir. Uygulama, `resolveCallerScopeContext()` MCP kimlik doğrulama bilgisinden, istek meta verilerinden veya `OMNIROUTE_MCP_SCOPES`'tan kapsamları çözümledikten sonra `open-sse/mcp-server/scopeEnforcement.ts` içinde çalışır. `OMNIROUTE_MCP_ENFORCE_SCOPES=true` olmadığı sürece kapalı kalır.

### Erişim belirteci kapsamları

`oma_live_…` belirteçlerinde `read` / `write` / `admin`, `scopeSatisfies` (`src/lib/accessTokens/scopes.ts`) tarafından sıralanır. Bu sıralama yalnızca erişim belirteci kimlik bilgisi için geçerlidir. Bkz. [Yönetim Kimlik Doğrulaması](../guides/MANAGEMENT-AUTH.md).

## Kimlik Doğrulama Gerekli Anahtarı

`src/shared/utils/apiAuth.ts` içindeki `isAuthRequired()`, bir istek için **herhangi bir** kimlik doğrulamanın zorunlu olup olmadığını belirler:

- `settings.requireLogin === false` → kimlik doğrulama genel olarak kapalıdır; ancak her zaman korunan katman ([Rota Koruma Katmanları](../security/ROUTE_GUARD_TIERS.md)) ve kabul edilen bir kimlik bilgisini veren çağrılar bunun dışındadır. Bunlar, girişin açık olduğu durumdaki ile aynı kimlik bilgisini ister: senkronizasyon token'ları vermek, her kapsamda CLI erişim token'ları basmak ve `manage`/`admin` kapsamlı API anahtarı oluşturmak, bu kapsamı bir anahtara vermek veya böyle bir anahtarı yeniden üretmek/göstermek (`src/lib/api/requireManagementAuth.ts` içindeki `requireCredentialForManagementScopedKey()`). Çıkarım amaçlı anahtarlar açık kalır.
- Yönetim şifresi yok **ve** `INITIAL_PASSWORD` ortam değişkeni yok → önyükleme modu: kurulum sihirbazına ve loopback isteklerine izin verilir, ancak dışarıdan gelen ağ isteklerinin yine kimlik bilgisi gerekir.
- Herhangi bir veritabanı hatası → kapalı durumda başarısız olur (güvenli varsayılan).

İstemci API anahtarı zorlaması, doğrudan `process.env.REQUIRE_API_KEY` okumak yerine `src/shared/utils/featureFlags.ts` içindeki `isRequireApiKeyEnabled()` fonksiyonunu kullanır. Bu, dağıtılmış örnekler için önemlidir: Kontrol Paneli → Özellik Bayrakları içinde `REQUIRE_API_KEY` değiştirmek bir DB geçersiz kılma kaydeder ve `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` ve bu yardımcıyı paylaşan diğer istemci API kimlik denetimlerini anında etkiler. Özellik bayrağı deposu okunamıyorsa istemci API kimlik doğrulaması kapalı duruma geçer ve bir anahtar ister.

## Uyumluluğu Bozan Değişiklik — v3.8.0

`/api/v1/agents/tasks/*` ve `/api/resilience/model-cooldowns` uç noktaları **artık yönetim kimlik doğrulaması gerektirir** (`588a0333` commit'i). Daha önce `manage` kapsamı olmadan normal bir API anahtarı gönderen istemciler `403` yanıtı alır. Geçiş: API Keys panosunda anahtara `manage` kapsamını verin veya oturum açılmış bir dashboard oturumu kullanın.

## Davranış Değişikliği — v3.8.2

`/api/mcp/*` (uzak MCP sunucusu) varsayılan olarak hâlâ LOCAL_ONLY'dir; ancak `Authorization: Bearer <api-key>` üstbilgisi `manage` kapsamını taşıdığında artık geri döngü dışı istekleri kabul eder. Bu istisna, `src/server/authz/routeGuard.ts` içindeki `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` aracılığıyla yol başına açıkça denetlenir; aynı düzeydeki LOCAL_ONLY öneki `/api/cli-tools/runtime/*`, rastgele alt süreçler başlatabildiği için kasıtlı olarak atlanamaz. Geri döngü dışından `/api/mcp/*` yoluna yapılan anonim istekler `403 LOCAL_ONLY` döndürmeye devam eder — yeni LOCAL_ONLY yollar için varsayılan davranış, yalnızca geri döngüye kesin biçimde izin vermeye devam eder. Bkz. [Rota Koruması Düzeyleri](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Test

- Birim testleri: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Genel erişim izin listesi: `tests/unit/public-api-routes.test.ts`.
- Odaklanmış çalıştırma: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Hata ayıklama

İşlem hattı yanıtları her zaman şununla damgalar:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Kimliği doğrulanmış istekler için yukarı akış (işleyici tarafı) istek başlıkları ayrıca şunları içerir:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

— işleyicilerinin içinde `assertAuth(req, expectedClass)` kullanın, eğer ara yazılım atlanırsa `AUTHZ_NOT_INITIALIZED` koduyla `AuthzAssertionError` atar (testlerde yapılandırma gerilemelerini yakalamak için faydalıdır).

## Ayrıca Bakınız

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — uç nokta başına kimlik doğrulama işaretçisi
- [COMPLIANCE.md](../security/COMPLIANCE.md) — kimlik doğrulama olayları için denetim günlüğü
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — üç kapsam ad alanı ve MCP araç kapsamı kataloğu
- Kaynak: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
