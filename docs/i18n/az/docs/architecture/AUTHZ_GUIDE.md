# Authorization Guide (Azərbaycan dili)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Həqiqət mənbəyi:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Son yenilənmə:** 2026-09-22 — əhatə adları MCP-SERVER.md sənədinə istinad edir

OmniRoute hər bir API sorğusunu yoxlayan, marşrutdan xəbərdar avtorizasiya konveyerinə malikdir. Təsnifat **deterministikdir** və **uğursuzluq zamanı girişi rədd edir** — təsnif edilə bilməyən hər bir sorğu `MANAGEMENT` kateqoriyasına düşür və sessiya və ya idarəetmə səviyyəli token tələb edir. Bu səhifə marşrutları idarə edən və ya yeni son nöqtələr layihələndirən mühəndislər üçün modeli izah edir.

![AuthZ konveyeri (3 marşrut sinfi + siyasətin qiymətləndirilməsi)](../diagrams/exported/authz-pipeline.svg)

> Mənbə: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## İki Auth rejimi

### 1. API Açar (Daşıyıcı)

Açar `manage` əhatə dairəsinə malik olduqda OpenAI/Anthropic/Gemini-compatible müştəri APIs və bir neçə idarəetmə marşrutu üçün istifadə olunur.

```
Authorization: Bearer <api-key>
```

`src/sse/services/auth.ts` -də `isValidApiKey()` / `extractApiKey()` tərəfindən təsdiqlənmiş və `src/shared/utils/apiAuth.ts` vasitəsilə yenidən ixrac edilmişdir. Təsdiqləyici həmçinin `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env varlarını davamlı keçid açarları kimi qəbul edir (məsələ #1350).

### 2. İdarə Paneli Sessiyası (auth_token kuki)

Panel səhifələri və admin əməliyyatları üçün.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Kuki yalnız JWT təsdiq etdikdə sessiyadır** və** `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`) daşıyır. Kukinin hər bir istehlakçısı ( tablosuna marşrut qoruyucusu (`isDashboardSessionAuthenticated()`), authz boru kəmərinin yenilənməsi, WebSocket əl sıxma, canlı server, `/api/settings/require-login`, `/api/auth/status`) həmin köməkçidən keçir. `JWT_SECRET` ilə imzalanmış digər JWTs — Cursor CLI keçidi — açar sahibləri üçün `iss "omniroute" / aud "cursor-cli"` tokenləri mövcuddur və heç vaxt sessiya deyil (#13298).

`src/shared/utils/apiAuth.ts`-də `isDashboardSessionAuthenticated()` tərəfindən təsdiq edilmişdir. Boru kəməri 30 günlük istifadə müddətinə 7 gündən az qaldıqda JWT ni avtomatik yeniləyir.

Sessiya 30 gün bitməmişdən əvvəl də bitə bilər, çünki hər minter `mintDashboardSessionToken` (məsələ vaxtı `iat` və id `jti`) keçir və yoxlayıcı iki parametri yoxlayır: `sessionsValidAfter`, parol dəyişikliyi ilə təyin olunur, beləliklə təsdiqləməni dayandırmazdan əvvəl buraxılan hər sessiya (parolu dəyişən brauzer təzə kuki alır) və `revokedDashboardSessions`, buraxılmış seansları ' `POST /api/auth/logout` əlavə `jti`. Köhnə buraxılış tərəfindən hazırlanmış sessiyalar heç bir iddia daşımır və ilk parol dəyişikliyinə qədər etibarlı qalır. Parametrləri oxumaq mümkün deyilsə, sessiya etibarlı deyil.

Some management routes accept **either** mode: cookie OR `Bearer <key>` when the API key has the `manage` (or `admin`) scope. This is what enables the "configurable via API calls" workflow added in v3.8.

#### Könüllü OIDC giriş qapısı (#6973)

Tablosuna admin girişi də dəstəkləyir** daxil olun** OIDC (OpenID Connect) standart parol girişi ilə yanaşı axını — parol girişi heç vaxt silinmir, yalnız əlavə olunur:

- `settings.oidcEnabled === true` olmadığı müddətcə əlildir** və** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` hamısı konfiqurasiya edilmişdir (Parametrlər → Auth). `GET /api/auth/oidc/login` əks halda `400` qaytarır.
- `GET /api/auth/oidc/login` emitentin `/.well-known/openid-configuration` dən `authorization_endpoint` aşkar edir ( `<issuer>/authorize` a qayıdır), daxil olan sorğudan (`x-forwarded-proto` -aware) yönləndirmə URI qurur və `httpOnly` `oidc_state` kukisində saxlanılan təsadüfi `state` ilə IdP ə yönləndirir.
- `GET /api/auth/oidc/callback` `state` doğrulayır, avtorizasiya kodunu dəyişdirir və `issuer`/`audience` yoxlamaları ilə emitentin JWKS (`jose`-nin `createRemoteJWKSet`, hər JWKS URI üçün keşlənmiş ) vasitəsilə ID tokeninin imzasını yoxlayır. İdarə panelinə daxil olmaq üçün boş `oidcAllowedSubjects` siyahısı, `oidcAdmissionClaim` siyasəti və ya hər ikisi tələb olunur. Mövzu siyahısı yalnız `email_verified === true` olduqda `sub` və ya `email` ilə uyğun gəlir. İsteğe bağlı iddia siyasəti nöqtə ilə ayrılmış ID-token iddia yolunu (məsələn, `realm_access.roles`) və qəbul edilmiş dəyərlər massivini götürür; həll edilmiş iddia ən azı bir qəbul edilmiş dəyəri ehtiva edən sətirlər massivi olmalıdır. Hər iki siyasət konfiqurasiya olunubsa, hər ikisi keçməlidir. Missing/malformed iddiaları bağlanmadı və heç bir siyasət olmadan geri çağırış daxil olmaqdan imtina edir (`not_configured`). Mövcud yalnız mövzu konfiqurasiyaları dəyişməz olaraq davam edir.
- Keycloak adətən səltənət rollarını mütləq ID tokenləri ilə deyil, giriş tokenləri ilə əlaqələndirir. `admin` səltənət rolunu tələb etmək üçün bu müştəri üçün `realm_access.roles` daxil olan protokol xəritəçisini konfiqurasiya edin**ID nişanı** , sonra `oidcAdmissionClaim` `{ "path": "realm_access.roles", "values": ["admin"] }` olaraq təyin edin. Yalnız rol üçün qəbulu aktiv etməzdən əvvəl bu müştəri üçün faktiki ID-token iddiasını yoxlayın; proqram giriş-token rollarını oxumur. IdP tərəfi işarəsindən imtina bu tətbiq tərəfi yoxlamasını tamamlaya bilər, lakin onu əvəz etmir.
- Müvəffəqiyyət haqqında o darp edir** tam eyni** 30 günlük `auth_token` JWT parola giriş problemləri (`src/app/api/auth/login/route.ts`), ona görə də tablosuna seans boru xəttinin qalan hissəsi (avtomatik yeniləmə, kuki bayraqları) dəyişməzdir — OIDC yalnız kukinin necə yığıldığını əvəz edir, onun verdiyini deyil. IdP roles/groups -a edilən dəyişikliklər mövcud OmniRoute seanslarını etibarsız etmir; çıxış, parol fırlanması və ya sessiyanın bitmə müddəti hələ də onların ömrünü idarə edir.
- Hər `oidc*` parametri (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) -dadır: `PATCH /api/settings` `400 PASSWORD_REQUIRED` cavab verir, əgər orqan idarəetmə parolunu `currentPassword` (`401 PASSWORD_MISMATCH` ) kimi daşımırsa. `oidcDisablePasswordLogin` _login_ (`POST /api/auth/login`) parolundan imtina edir, lakin saxlanılan parol hashini saxlayır və yenidən auth yenə də ona qarşı `currentPassword` yoxlayır.
- `corsOrigins` və `bruteForceProtection` də `SECURITY_IMPACTING_SETTINGS_KEYS` dədir: gevşetmə ya giriş müdafiəsini zəiflədir, ona görə də onlar eyni `currentPassword` re-auth (Təhlükəsizlik nişanı bunu tələb edir) alır və JSON idxalı onları azaldır.
- Hər bir təhlükəsizlik siyasəti açarı — girişləri, hər `oidc*` açarı və tablosuna seans vəziyyəti — dir `SECURITY_IMPACTING_SETTINGS_KEYS`** yalnız operator üçün** `PATCH /api/settings` də: idarə miqyaslı API açarı və ya `oma_` giriş nişanı hətta düzgün `currentPassword` göndərdikdə `403` ilə rədd edilir və imtina `reason: OPERATOR_REQUIRED` ( `src/lib/api/operatorCredential.ts`-də `requireOperatorCredential()` ) ilə `settings.update_failed` kimi yoxlanılır. Adi parametrlər (mövzu, ekran üstünlükləri) `manage` açarı və ya `admin` giriş nişanı üçün yazıla bilən qalır. `/api/settings` nin özünün (və `/api/settings/require-login`-in) hər mutasiyasının həmçinin `admin` giriş nişanəsinin əhatə dairəsinə ehtiyacı var ( `src/server/authz/accessScopes.ts`-da `ADMIN_MUTATION_EXACT_PATHS`, dəqiq yol uyğunluğu); `GET` `read` olaraq qalır və digər `/api/settings/*` alt marşrutları (proksilər, birləşmiş defoltlar, model ləqəbləri, sıxılma, təmizlənmələr...) metoddan irəli gələn `write` əhatə dairəsini saxlayır.
- `POST /api/settings/import-json` bu təkrar authı atlayır, ona görə də yazmadan əvvəl `IMPORT_STRIPPED_SETTINGS_KEYS` (eyni faylda) hər düyməni buraxır: parol və `currentPassword`, hər `SECURITY_IMPACTING_SETTINGS_KEYS` girişi və tablosuna sessiya vəziyyəti (`sessionsValidAfter`, `revokedDashboardSessions`). Buna görə də köhnə ehtiyat nüsxəsinin idxalı parol dəyişikliyi və ya hesabdan çıxmanın artıq başa çatdığı sessiyanı canlandıra bilməz.

#### Könüllü TOTP iki faktorlu giriş (#16619)

Parametrlər → Security-dən qeydiyyatdan keçib; operator onu işə salana qədər söndürün (`src/server/auth/dashboardMfa.ts`).

- **Nələri əhatə edir:** parol girişi (`POST /api/auth/login`, daha sonra `POST /api/auth/mfa/verify` lazımdır) və `omniroute connect` (`POST /api/cli/connect`, yalnız parol mübadiləsindən imtina edir və kodu `totp` kimi qəbul edir).
- **Nələri əhatə etmir:** OIDC / SSO girişi (`/api/auth/oidc/callback`) OmniRoute TOTP tələb etmir. O, identifikasiya provayderinin özünün ikinci faktoruna əsaslanır, ona görə də OIDC aktivdirsə, MFA IdP -də tətbiq edin.
- **Bərpa** (itirilmiş cihaz, bərpa kodları qalmayıb və ya artıq yoxlanıla bilməyən amil, məsələn `STORAGE_ENCRYPTION_KEY` dəyişdirildikdən sonra):
  1. `OMNIROUTE_DISABLE_MFA=true` ilə serveri yenidən başladın.
  2. Hostun özündə (loopback peer və loopback `Host`, məsələn `http://localhost:20128`) parol ilə daxil olun. İkinci amil yalnız bu mənşə üçün atlanır; hər bir başqa mənşə hələ də koda ehtiyac duyur.
  3. Parametrlər → Security → Disable-də parolu daxil edin və kodu boş buraxın. `POST /api/auth/mfa/disable` `code` olmadan bədəni yalnız dəyişən təyin edildikdə və sorğu hostdan gələrkən qəbul edir; o, hələ də tablosuna seans və cari parol tələb edir və `secondFactor: "recovery_switch"` ilə `auth.mfa.disabled` kimi yoxlanılır.
  4. `OMNIROUTE_DISABLE_MFA` ləğv edin, yenidən başladın və lazım gələrsə yenidən qeydiyyatdan keçin.

## Marşrut sinifləri

`src/server/authz/types.ts` üç sinif təyin edir; deterministik şəkildə təsnif edilə bilməyən hər marşrut `MANAGEMENT`-ə düşür.

| Sinif        | Təsvir                                                                                                                                                 | Tələb olunan autentifikasiya                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| `PUBLIC`     | Açıq şəkildə təhlükəsiz marşrutlar — giriş, çıxış, status, başlatma, sağlamlıq və quraşdırmanın ilkin endpoint-ləri.                                   | Yoxdur                                                              |
| `CLIENT_API` | Model xidmət endpoint-ləri — `/api/v1/*`, `/api/v1beta/*` və ləqəblər: `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Effektiv `REQUIRE_API_KEY` funksiya bayrağı aktivdirsə Bearer açarı |
| `MANAGEMENT` | İdarəetmə paneli səhifələri, parametrlər, provayderlər, açarlar, admin və diaqnostika endpoint-ləri.                                                   | İdarəetmə paneli sessiyası VƏ YA `manage` əhatəli Bearer            |

Bəzi `MANAGEMENT` əməliyyatları **yalnız operator üçündür**: `manage` açarı kifayət etmir. Saxlanılan etimadnamələrin ixracı (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), canlı məlumatların üzərinə ehtiyat nüsxəsinin bərpası (`dryRun=true` daxil olmaqla `POST /api/db-backups/import`, identifikatora görə bərpa `POST /api/db-backups` və `POST /api/settings/import-json`) və bərpa nöqtələrinin məhv edilməsi (`DELETE /api/db-backups` təmizləməsi və `PATCH /api/db-backups`, çünki saxladığı saxlama müddəti hər ehtiyat nüsxəsindən sonrakı avtomatik təmizləməni idarə edir) idarəetmə paneli sessiyası, yerli CLI subyekti və ya söndürülmüş giriş tələb edir. Sinxronizasiya tokeni vermək (`POST /api/sync/tokens`) və `admin` CLI giriş tokeni vermək (`POST /api/cli/tokens`) bütün giriş rejimlərində idarəetmə paneli sessiyası və ya yerli CLI subyekti tələb edir. İstənilən əhatəli API açarları və `oma_` giriş tokenləri operator etimadnaməsi deyil: tələb olunduqda `403` alırlar. Yoxlama `src/lib/api/operatorCredential.ts`-dədir (`resolveOperatorCredential()` / `requireOperatorCredential()`). Giriş parametrlərinin dəyişdirilməsi də yalnız operator üçündür: parol mövcud olduqdan sonra `POST /api/settings/require-login` (idarəetmə parolunu təyin etmək / `requireLogin`-i dəyişmək) yalnız bu etimadnamələri qəbul edir — ilk quraşdırma bootstrap pəncərəsi (hələ parol yoxdursa) dəyişməz qalır — və idarəetmə paneli sessiyası parolu əvəz etmək üçün `currentPassword` göndərməlidir (yoxdursa və ya səhvdirsə `403`, `settings.update_failed` kimi audit olunur). Yerli CLI və girişi söndürülmüş instansiya bərpa yolunu saxlayır və parolu onsuz təyin edə bilər, çünki ikisi də məlumat qovluğuna sahib olan hosta bağlıdır.

## Boru kəməri

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

Etibarlı daxili başlıqlar ( `src/server/authz/headers.ts` ilə müəyyən edilir) bunlardır** daxil olan sorğulardan məhrum edilmişdir** təsnifatdan əvvəl — müştəriləri subyekti təqlid etmək üçün `x-omniroute-auth-*` əvvəlcədən doldura bilməzlər.

### Siyasət müqavilələri

Hər bir marşrut sinfinin `src/server/authz/policies/`-da siyasəti var:

- **`publicPolicy`** (`policies/public.ts`) — həmişə `allow({ kind: "anonymous", id: "anonymous" })` qaytarır.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — Daşıyıcını çıxarır, `validateApiKey()` vasitəsilə təsdiq edir. Yalnız effektiv `REQUIRE_API_KEY` funksiyasının bayrağı deaktiv edildikdə anonimə keçir. Effektiv bayraq `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) vasitəsilə həll edilir, beləliklə, İdarə Paneli Xüsusiyyətləri Bayraqlar və mühit dəyişənləri `/api/v1/*`, `/api/v1beta/*` və ləqəbləri ardıcıl olaraq idarə edir; həlledici uğursuzluqlar bağlandı. Müştəri API marşrutları üzrə (o cümlədən tablosuna model kataloqu tərəfindən istifadə edilən `/api/v1/models`) panel-sessiya sorğularına icazə verir. Entra ID SSO aktivləşdirildikdə, struktur olaraq Entra tokeni (üç base64url seqmenti, `RS*` alg, `kid`) olan Daşıyıcı SSO filialı tərəfindən idarə olunur.** əvvəl** `validateApiKey()` və onun hökmü yekun — o, heç vaxt API açarı yoluna və ya degraddan anonim filiala düşmür, ona görə də identifikasiya provayderinin kəsilməsi açıq girişə çevrilə bilməz. Statik API düymələri təsirlənmir. [Entra ID SSO](../security/ENTRA_SSO.md) baxın.
- **`managementPolicy`** (`policies/management.ts`) — tablosuna seansı, daxili model sinxronizasiya sorğularını qəbul edir ( `/api/providers/[name]/(sync-models|models)` ilə uyğun gəlir) və ya `isAuthRequired()` yalnış qaytardıqda tamamilə ötür. Daşıyıcı nişanı mövcud olduqda, lakin etibarsız olduqda 403 (`AUTH_001`) qaytarır, əks halda 401. Həmçinin marşrut qoruyucu səviyyələrini (LOCAL_ONLY / ALWAYS_PROTECTED) hər hansı auth filialından əvvəl tətbiq edir — Baxın [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` da (bu gün: `/api/mcp/`) LOCAL_ONLY yollarına Daşıyıcı açarı `manage` əhatə dairəsini daşıdıqda qeyri-döngüdən daxil ola bilər; bütün digər LOCAL_ONLY yolları əhatə dairəsindən asılı olmayaraq ciddi geri dönmə olaraq qalır.

Uğurlu siyasət `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }` ilə `AuthSubject` qaytarır. Aşağı axın işləyiciləri auth məntiqini yenidən işə salmaq əvəzinə onu `src/server/authz/assertAuth.ts` -də `assertAuth(request, "CLIENT_API")` vasitəsilə oxuya bilər.

## İctimai marşrutların siyahısı

`src/shared/constants/publicApiRoutes.ts` açıq icazə siyahısıdır:

Siyahı bölünür** forma** , və bölünmə yükdaşıyıcıdır (GHSA-74g9-q8f6-793h): prefiks `startsWith()` ilə uyğunlaşdırılır, buna görə də o, aparıcı simvollarını paylaşan hər bir qonşu yola uyğun gəlir. `/api/usage/om-usage` prefiks olaraq `/api/usage/om-usage<anything>` PUBLIC ilə işarələnir və Next bunu öz authu olmayan bir işləyicini `/api/usage/[connectionId]` — həll edir.

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

Yalnız oxumaq üçün nəzərdə tutulan marşrutlar ictimaidir** yalnız** təhlükəsiz üsullar üçün. Qeyd: `classifyRoute()` `/api/v1/*` və `/api/v1beta/*` PUBLIC aşağı — dən istisna edir, onlar həmişə `CLIENT_API` dir, ona görə də Daşıyıcı-açar siyasəti hələ də qüvvədədir.

## Yeni marşrutun əlavə edilməsi

### Nümunə 1 — Açıq müştəri API son nöqtəsi (Bearer autentifikasiyası)

`/api/v1/` və `/api/v1beta/` altındakı marşrutlar avtomatik olaraq `CLIENT_API` kimi təsnif edilir. Ara proqram Bearer yoxlamasını tətbiq edir; marşrut işləyicilərinin bunu təkrar etməsinə ehtiyac yoxdur, lakin faydalı olarsa subyekti oxuya bilərlər.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... işləyici məntiqi
}
```

### Nümunə 2 — İdarəetmə son nöqtəsi (sessiya və ya Bearer + manage)

`src/lib/api/requireManagementAuth.ts` faylındakı `requireManagementAuth()` funksiyasından istifadə edin:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... işləyici məntiqi
}
```

`requireManagementAuth()` uğur halında `null`, əks halda isə JSON xətası olan `Response` qaytarır:

- 401 `AUTH_001` "Autentifikasiya tələb olunur" — ümumiyyətlə heç bir giriş məlumatı yoxdur
- 403 — etibarsız Bearer **və ya** Bearer mövcuddur, lakin açarda `manage` / `admin` əhatə dairəsi yoxdur

`hasManageScope(scopes)` funksiyası `"manage"` və ya `"admin"` üçün true qaytarır.

### Nümunə 3 — Açıq icazə siyahısına əlavə etmə

Çoxluğu rahatlığa görə deyil, formasına görə seçin. Bir marşrut `PUBLIC_API_ROUTES_EXACT` çoxluğuna (və ya yalnız GET üçün `PUBLIC_READONLY_CORS_API_ROUTES` siyahısına) daxil edilir; yalnız həqiqi alt ağac `PUBLIC_API_ROUTE_PREFIXES` siyahısına daxil edilir və o, **`/` ilə bitməlidir**. Tək marşrutu prefiks siyahısına daxil etmək, başlanğıc simvollarını onunla paylaşan bütün bitişik yolları, o cümlədən sonradan əlavə edilən dinamik seqmentli qardaş marşrutları da açıq edir (GHSA-74g9-q8f6-793h). `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` və `tests/unit/authz/classify.test.ts` fayllarındakı vahid testlərini yeniləyin.

## Əhatə dairələri

Üç ad məkanı mövcuddur. Hər yoxlayıcı yalnız öz sətirlərini oxuyur. `manage` əhatə dairəsinin `read:compression` üçün `scopeMatches` yoxlamasından niyə keçmədiyi və `read` giriş tokeninin niyə `PATCH /api/keys/{id}` sorğusunu yerinə yetirə bilmədiyi də daxil olmaqla paralel müqayisə üçün baxın:
[Üç əhatə dairəsi ad məkanı](../frameworks/MCP-SERVER.md#three-scope-namespaces).

API açarları `scopes` massivi daşıyır (`api_keys.scopes` daxilində JSON kimi saxlanılır, baxın: `src/lib/db/apiKeys.ts`).

### İdarəetmə əhatə dairəsi

- `manage` / `admin` — `hasManageScope`. İdarəetmə API marşrutlarına Bearer girişi.
- `mcp:connect`, `self:usage`, `self:account-quota` və
  `policy:bypass-provider-quota` əlavə, dəqiq uyğunluq tələb edən əhatə dairələridir. Onlar
  `MANAGEMENT_API_KEY_SCOPES` xaricində yerləşir. `mcp:connect` yalnız
  `/api/mcp/` üçün qeyri-loopback istisnasını açır.

### MCP alət əhatə dairələri

Kataloq və uyğunlaşdırma qaydaları (eyni sətir və ya `*` ilə bitən verilmiş əhatə dairəsi):
[MCP alət əhatə dairələri](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`src/shared/constants/mcpScopes.ts` daxilindəki `MCP_SCOPE_LIST` həmin tam kataloq deyil, ilkin tipləşdirilmiş
alt çoxluqdur. Məcburi tətbiqetmə
`open-sse/mcp-server/scopeEnforcement.ts` daxilində, `resolveCallerScopeContext()`
əhatə dairələrini MCP autentifikasiya məlumatından, sorğu metadatasından və ya `OMNIROUTE_MCP_SCOPES` dəyişənindən
müəyyən etdikdən sonra işləyir. `OMNIROUTE_MCP_ENFORCE_SCOPES=true` olmadığı halda deaktiv qalır.

### Giriş tokeni əhatə dairələri

`oma_live_…` tokenlərində `read` / `write` / `admin`, `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`) tərəfindən dərəcələndirilir. Bu dərəcə yalnız giriş tokeni
etimadnaməsinə tətbiq olunur. Baxın: [İdarəetmə autentifikasiyası](../guides/MANAGEMENT-AUTH.md).

## Autentifikasiya tələbi açarı

`src/shared/utils/apiAuth.ts`-dəki `isAuthRequired()` sorğu üçün **hər hansı** autentifikasiyanın tətbiq olunub-olunmayacağını müəyyən edir:

- `settings.requireLogin === false` → autentifikasiya qlobal olaraq söndürülür, lakin həmişə qorunan təbəqə ([Marşrut Qoruma Təbəqələri](../security/ROUTE_GUARD_TIERS.md)) və qəbul edilən etimadnaməni verən çağırışlar istisnadır. Bunlar girişin aktiv olduğu zamankı ilə eyni etimadnaməni tələb edir: sinxronizasiya tokenləri vermək, istənilən əhatədə CLI giriş tokenləri vermək və `manage`/`admin` əhatəli API açarı yaratmaq, bu əhatəni açara vermək və ya belə açarı yenidən yaratmaq/göstərmək (`src/lib/api/requireManagementAuth.ts`-dəki `requireCredentialForManagementScopedKey()`). Inference üçün açarlar açıq qalır.
- İdarəetmə parolu yoxdur **və** `INITIAL_PASSWORD` mühit dəyişəni yoxdur → bootstrap rejimi: quraşdırma sehrbazına və loopback sorğularına icazə verilir, lakin xarici şəbəkə sorğuları hələ də etimadnamə tələb edir.
- İstənilən verilənlər bazası xətası → bağlı şəkildə uğursuz olur (təhlükəsiz defolt).

Müştəri API açarının tətbiqi birbaşa `process.env.REQUIRE_API_KEY` oxumaq yerinə `src/shared/utils/featureFlags.ts`-dəki `isRequireApiKeyEnabled()`-dən istifadə edir. Bu yerləşdirilmiş instansiyalar üçün vacibdir: İdarəetmə Paneli → Funksiya Bayraqlarında `REQUIRE_API_KEY`-i dəyişdirmək DB üzərində override saxlayır və `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` və bu köməkçini paylaşan digər müştəri API autentifikasiya yoxlamalarına dərhal təsir edir. Funksiya bayrağı anbarı oxuna bilmirsə, müştəri API autentifikasiyası bağlı şəkildə uğursuz olur və açar tələb edir.

## Uyğunluğu pozan dəyişiklik — v3.8.0

`/api/v1/agents/tasks/*` və `/api/resilience/model-cooldowns` son nöqtələri **artıq idarəetmə autentifikasiyası tələb edir** (`588a0333` commit-i). Əvvəllər `manage` əhatə dairəsi olmadan adi API açarı göndərən müştərilər `403` cavabı alır. Miqrasiya: ya API Açarları idarə panelində açara `manage` əhatə dairəsi təyin edin, ya da giriş edilmiş idarə paneli sessiyasından istifadə edin.

## Davranış dəyişikliyi — v3.8.2

`/api/mcp/*` (uzaq MCP serveri) standart olaraq hələ də LOCAL_ONLY rejimindədir, lakin `Authorization: Bearer <api-key>` başlığı `manage` əhatə dairəsini ehtiva etdikdə artıq loopback olmayan sorğuları qəbul edir. Bu istisna `src/server/authz/routeGuard.ts` daxilindəki `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` vasitəsilə hər yol üçün ayrıca aktivləşdirilir; əlaqəli LOCAL_ONLY prefiksi olan `/api/cli-tools/runtime/*` qəsdən bu istisnaya daxil edilmir, çünki ixtiyari alt proseslər başlada bilər. Loopback olmayan mənbələrdən `/api/mcp/*` ünvanına göndərilən anonim sorğular yenə də `403 LOCAL_ONLY` qaytarır — istənilən yeni LOCAL_ONLY yolu üçün standart davranış ciddi loopback məhdudiyyəti olaraq qalır. Baxın: [Marşrut qoruyucusunun səviyyələri](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Sınaq

- Vahid testləri: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- İctimai icazə siyahısı: `tests/unit/public-api-routes.test.ts`.
- Fokuslanmış şəkildə işə salmaq üçün: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Sazlama

Boru kəməri həmişə cavabları möhürləyir:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Doğrulanmış sorğular üçün yuxarı (işləyici tərəfi) sorğu başlıqlarına da daxildir:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

İşləyicilərin içərisində `assertAuth(req, expectedClass)` istifadə edin — əgər ara proqram yan keçibsə, `AuthzAssertionError` kodunu `AUTHZ_NOT_INITIALIZED` ilə atır (testlərdə konfiqurasiya reqressiyalarını tutmaq üçün faydalıdır).

## Həmçinin baxın

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — hər son nöqtə üçün autentifikasiya markeri
- [COMPLIANCE.md](../security/COMPLIANCE.md) — autentifikasiya hadisələri üçün audit jurnalı
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — üç əhatə sahəsi ad məkanı və MCP alət-əhatə sahəsi kataloqu
- Mənbə: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
