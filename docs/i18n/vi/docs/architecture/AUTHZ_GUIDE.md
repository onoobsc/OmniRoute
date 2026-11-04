# Authorization Guide (Tiếng Việt)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Nguồn đáng tin cậy:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Cập nhật lần cuối:** 2026-09-22 — các không gian tên phạm vi trỏ đến MCP-SERVER.md

OmniRoute có một quy trình ủy quyền nhận biết tuyến đường, kiểm soát mọi yêu cầu API. Phân loại là **xác định** và **đóng khi lỗi** — bất cứ thứ gì không thể phân loại sẽ được xếp vào loại `MANAGEMENT` và yêu cầu một phiên hoặc mã thông báo cấp quản lý. Trang này giải thích mô hình cho các kỹ sư duy trì các tuyến đường hoặc thiết kế các điểm cuối mới.

![Quy trình AuthZ (3 lớp tuyến đường + đánh giá chính sách)](../diagrams/exported/authz-pipeline.svg)

> Nguồn: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Hai chế độ xác thực

### 1. Khóa API (Người mang)

Được sử dụng cho OpenAI/Anthropic/Gemini-compatible client APIs và một số tuyến quản lý khi khóa có phạm vi `manage`.

```
Authorization: Bearer <api-key>
```

Được xác thực bởi `isValidApiKey()` / `extractApiKey()` trong `src/sse/services/auth.ts` và được xuất lại thông qua `src/shared/utils/apiAuth.ts`. Trình xác thực cũng chấp nhận các biến `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env dưới dạng các khóa chuyển tiếp liên tục (vấn đề #1350).

### 2. Phiên bảng điều khiển (cookie auth_token)

Đối với các trang bảng điều khiển và hoạt động quản trị.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Cookie chỉ là phiên khi JWT xác minh** Và** mang `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Mọi người sử dụng cookie (bảo vệ lộ trình bảng điều khiển (`isDashboardSessionAuthenticated()`), làm mới đường dẫn authz, bắt tay WebSocket, máy chủ trực tiếp, `/api/settings/require-login`, `/api/auth/status`) đều đi qua trình trợ giúp đó. JWTs khác được ký với `JWT_SECRET` tồn tại — Cursor CLI truyền qua `iss "omniroute" / aud "cursor-cli"` mã thông báo cho người nắm giữ khóa — và không bao giờ là phiên (#13298).

Được xác minh bởi `isDashboardSessionAuthenticated()` trong `src/shared/utils/apiAuth.ts`. Đường dẫn tự động làm mới JWT khi nó chỉ còn ít hơn 7 ngày trong vòng đời 30 ngày của nó.

Một phiên cũng có thể kết thúc trước khi hết 30 ngày, vì mỗi máy đào đều trải qua `mintDashboardSessionToken` (thời gian phát hành `iat` và id `jti`) và trình xác minh sẽ kiểm tra hai cài đặt: `sessionsValidAfter`, được đặt bằng cách thay đổi mật khẩu để mỗi phiên được phát hành trước khi ngừng xác minh (trình duyệt đã thay đổi mật khẩu sẽ nhận được một cookie mới) và `revokedDashboardSessions`, mà `POST /api/auth/logout` sẽ thêm `jti` của phiên đăng xuất. Các phiên được tạo bởi bản phát hành cũ hơn không có yêu cầu và vẫn hợp lệ cho đến khi thay đổi mật khẩu đầu tiên. Nếu không thể đọc được cài đặt thì phiên đó không đáng tin cậy.

Một số tuyến quản lý chấp nhận** hoặc** chế độ: cookie OR `Bearer <key>` khi khóa API có phạm vi `manage` (hoặc `admin`). Đây là tính năng cho phép quy trình làm việc "có thể định cấu hình thông qua lệnh gọi API " được thêm vào trong v3.8.

#### Cổng đăng nhập OIDC tùy chọn (#6973)

Đăng nhập quản trị viên bảng điều khiển cũng hỗ trợ** chọn tham gia** Luồng OIDC (OpenID Connect) cùng với đăng nhập mật khẩu mặc định — đăng nhập mật khẩu không bao giờ bị xóa, chỉ được bổ sung:

- Bị vô hiệu hóa trừ khi `settings.oidcEnabled === true`** Và** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` đều được định cấu hình (Cài đặt → Auth). `GET /api/auth/oidc/login` trả về `400` nếu không.
- `GET /api/auth/oidc/login` phát hiện ra `authorization_endpoint` từ `/.well-known/openid-configuration` của nhà phát hành (quay trở lại `<issuer>/authorize`), xây dựng URI chuyển hướng từ yêu cầu đến (`x-forwarded-proto` -aware) và chuyển hướng đến IdP với một `state` ngẫu nhiên được lưu trữ trong cookie `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` xác thực `state`, trao đổi mã ủy quyền và xác minh chữ ký của mã thông báo ID thông qua JWKS của nhà phát hành (`jose`'s `createRemoteJWKSet`, được lưu trong bộ nhớ cache trên mỗi JWKS URI) bằng kiểm tra `issuer`/`audience`. Việc đăng ký trang tổng quan yêu cầu danh sách `oidcAllowedSubjects` không trống, chính sách `oidcAdmissionClaim` hoặc cả hai. Danh sách chủ đề chỉ khớp với `sub` hoặc `email` khi `email_verified === true`. Chính sách xác nhận quyền sở hữu tùy chọn có đường dẫn xác nhận quyền sở hữu mã thông báo ID được phân tách bằng dấu chấm (ví dụ: `realm_access.roles`) và một mảng các giá trị được chấp nhận; xác nhận quyền sở hữu đã được giải quyết phải là một chuỗi các chuỗi chứa ít nhất một giá trị được chấp nhận. Nếu cả hai chính sách đều được định cấu hình thì cả hai đều phải vượt qua. Khiếu nại Missing/malformed không được đóng và không có chính sách nào, lệnh gọi lại sẽ từ chối đăng nhập (`not_configured`). Các cấu hình chỉ dành cho chủ đề hiện tại vẫn tiếp tục không thay đổi.
- Keycloak thường ánh xạ các vai trò lãnh thổ vào mã thông báo truy cập, không nhất thiết phải là mã thông báo ID. Để yêu cầu vai trò khu vực `admin`, hãy định cấu hình trình ánh xạ giao thức cho ứng dụng khách này bao gồm `realm_access.roles` trong** mã thông báo ID** , sau đó đặt `oidcAdmissionClaim` thành `{ "path": "realm_access.roles", "values": ["admin"] }`. Kiểm tra xác nhận quyền sở hữu mã thông báo ID thực tế cho khách hàng này trước khi cho phép nhập học chỉ có vai trò; ứng dụng không đọc vai trò mã thông báo truy cập. Việc từ chối mã thông báo phía IdP có thể bổ sung nhưng không thay thế việc kiểm tra phía ứng dụng này.
- Khi thành công, nó tạo ra** chính xác như nhau** Trong 30 ngày `auth_token` JWT các vấn đề đăng nhập mật khẩu (`src/app/api/auth/login/route.ts`), do đó, phần còn lại của quy trình phiên bảng điều khiển (tự động làm mới, cờ cookie) không thay đổi — OIDC chỉ thay thế cách tạo cookie chứ không phải những gì nó cấp. Các thay đổi đối với IdP roles/groups không làm mất hiệu lực các phiên OmniRoute hiện có; đăng xuất, xoay mật khẩu hoặc hết hạn phiên vẫn chi phối thời gian tồn tại của chúng.
- Mọi cài đặt `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) đều ở dạng `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` trả lời `400 PASSWORD_REQUIRED` trừ khi phần thân mang mật khẩu quản lý là `currentPassword` (`401 PASSWORD_MISMATCH` khi sai). `oidcDisablePasswordLogin` từ chối mật khẩu _login_ (`POST /api/auth/login`) nhưng giữ hàm băm mật khẩu được lưu trữ và xác thực lại vẫn kiểm tra `currentPassword` đối với nó.
- `corsOrigins` và `bruteForceProtection` cũng nằm trong `SECURITY_IMPACTING_SETTINGS_KEYS` : việc nới lỏng sẽ làm suy yếu khả năng bảo vệ đăng nhập, do đó, chúng thực hiện cùng một xác thực lại `currentPassword` (tab Bảo mật yêu cầu điều đó) và quá trình nhập JSON sẽ loại bỏ chúng.
- Mọi khóa chính sách bảo mật — các mục nhập `SECURITY_IMPACTING_SETTINGS_KEYS`, mọi khóa `oidc*` và trạng thái phiên bảng điều khiển — là** chỉ dành cho người vận hành** trên `PATCH /api/settings`: khóa API trong phạm vi quản lý hoặc mã thông báo truy cập `oma_` bị từ chối với `403` ngay cả khi nó gửi đúng `currentPassword` và việc từ chối được kiểm tra là `settings.update_failed` với `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` trong `src/lib/api/operatorCredential.ts`). Cài đặt thông thường (chủ đề, tùy chọn hiển thị) vẫn có thể ghi được đối với khóa `manage` hoặc mã thông báo truy cập `admin`. Mọi đột biến của chính `/api/settings` (và của `/api/settings/require-login`) cũng cần phạm vi mã thông báo truy cập `admin` (`ADMIN_MUTATION_EXACT_PATHS` trong `src/server/authz/accessScopes.ts`, khớp đường dẫn chính xác); `GET` vẫn giữ nguyên `read` và các tuyến phụ `/api/settings/*` khác (proxy, mặc định kết hợp, bí danh mô hình, nén, thanh lọc…) giữ phạm vi `write` được suy ra theo phương thức.
- `POST /api/settings/import-json` bỏ qua quá trình xác thực lại đó, do đó, nó bỏ mọi khóa trong `IMPORT_STRIPPED_SETTINGS_KEYS` (cùng một tệp) trước khi ghi: mật khẩu và `currentPassword`, mọi mục nhập `SECURITY_IMPACTING_SETTINGS_KEYS` và trạng thái phiên bảng điều khiển (`sessionsValidAfter`, `revokedDashboardSessions`). Do đó, việc nhập bản sao lưu cũ hơn không thể phục hồi phiên đã thay đổi mật khẩu hoặc đăng xuất đã kết thúc.

#### Đăng nhập hai yếu tố TOTP tùy chọn (#16619)

Đã đăng ký từ Cài đặt → Security; tắt cho đến khi người vận hành bật nó lên (`src/server/auth/dashboardMfa.ts`).

- **Nó bao gồm những gì:** đăng nhập mật khẩu (`POST /api/auth/login`, sau đó cần `POST /api/auth/mfa/verify`) và `omniroute connect` (`POST /api/cli/connect`, từ chối trao đổi chỉ bằng mật khẩu và lấy mã là `totp`).
- **Những gì nó không bao gồm:** đăng nhập OIDC / SSO (`/api/auth/oidc/callback`) không yêu cầu OmniRoute TOTP. Nó dựa vào yếu tố thứ hai của chính nhà cung cấp danh tính, vì vậy hãy thực thi MFA trong IdP nếu OIDC được bật.
- **Sự hồi phục** (thiết bị bị mất, không còn mã khôi phục hoặc yếu tố không thể xác minh được nữa, chẳng hạn như sau khi `STORAGE_ENCRYPTION_KEY` thay đổi):
  1. Khởi động lại máy chủ bằng `OMNIROUTE_DISABLE_MFA=true`.
  2. Trên chính máy chủ (loopback ngang hàng và loopback `Host`, chẳng hạn như `http://localhost:20128`), đăng nhập bằng mật khẩu. Yếu tố thứ hai chỉ được bỏ qua đối với nguồn gốc đó; mọi nguồn gốc khác vẫn cần mã.
  3. Trong Cài đặt → Security → Tắt, nhập mật khẩu và để trống mã. `POST /api/auth/mfa/disable` chỉ chấp nhận phần thân không có `code` trong khi biến được đặt và yêu cầu đến từ máy chủ; nó vẫn yêu cầu phiên bảng điều khiển và mật khẩu hiện tại và được kiểm tra dưới dạng `auth.mfa.disabled` với `secondFactor: "recovery_switch"`.
  4. Bỏ đặt `OMNIROUTE_DISABLE_MFA`, khởi động lại và đăng ký lại nếu cần.

## Các lớp route

`src/server/authz/types.ts` định nghĩa ba lớp; mọi route không thể phân loại một cách xác định sẽ rơi về `MANAGEMENT`.

| Lớp          | Mô tả                                                                                                                                                     | Xác thực yêu cầu                                                 |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| `PUBLIC`     | Các route an toàn một cách rõ ràng — đăng nhập, đăng xuất, trạng thái, khởi tạo, health và bootstrap onboarding.                                          | Không có                                                         |
| `CLIENT_API` | Các endpoint phục vụ model — `/api/v1/*`, `/api/v1beta/*`, cùng các alias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Khóa Bearer khi cờ tính năng `REQUIRE_API_KEY` hiệu lực đang bật |
| `MANAGEMENT` | Các trang dashboard, cài đặt, nhà cung cấp, khóa, và các endpoint quản trị và chẩn đoán.                                                                  | Phiên dashboard HOẶC Bearer có phạm vi `manage`                  |

Một số hành động `MANAGEMENT` chỉ dành cho **operator**: khóa `manage` là không đủ. Việc xuất thông tin xác thực đã lưu (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), khôi phục bản sao lưu đè lên dữ liệu trực tiếp (`POST /api/db-backups/import` kể cả với `dryRun=true`, `POST /api/db-backups` khôi phục theo id, `POST /api/settings/import-json`), và hủy các điểm khôi phục (`DELETE /api/db-backups` dọn dẹp, và `PATCH /api/db-backups` vì thời gian lưu giữ mà nó duy trì điều khiển việc cắt tỉa tự động sau mỗi bản sao lưu) đều yêu cầu phiên dashboard, chủ thể CLI cục bộ, hoặc đăng nhập đã bị tắt. Việc cấp token đồng bộ (`POST /api/sync/tokens`) và đúc access token CLI `admin` (`POST /api/cli/tokens`) yêu cầu phiên dashboard hoặc chủ thể CLI cục bộ trong mọi chế độ đăng nhập. Khóa API thuộc bất kỳ phạm vi nào và access token `oma_` không phải là thông tin xác thực operator: chúng nhận `403` bất cứ khi nào cần đến. Kiểm tra nằm trong `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Việc thay đổi cài đặt đăng nhập cũng chỉ dành cho operator: `POST /api/settings/require-login` (đặt mật khẩu quản trị / bật tắt `requireLogin`) chỉ chấp nhận các thông tin xác thực đó khi đã có mật khẩu — cửa sổ bootstrap lần đầu (chưa có mật khẩu) giữ nguyên — và phiên dashboard phải gửi `currentPassword` để thay mật khẩu (`403` khi thiếu hoặc sai, được ghi audit là `settings.update_failed`). CLI cục bộ và một instance đã tắt đăng nhập giữ lại đường khôi phục và có thể đặt mật khẩu mà không cần nó, vì cả hai đều gắn với host sở hữu thư mục dữ liệu.

## Đường ống

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

Các tiêu đề nội bộ đáng tin cậy (được xác định trong `src/server/authz/headers.ts`) là** bị loại bỏ khỏi các yêu cầu đến** trước khi phân loại máy khách — không thể điền trước `x-omniroute-auth-*` để mạo danh một chủ đề.

### Hợp đồng chính sách

Mỗi lớp tuyến có một chính sách trong `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — luôn trả về `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — trích xuất Bearer, xác thực thông qua `validateApiKey()`. Chỉ chuyển sang ẩn danh khi cờ tính năng `REQUIRE_API_KEY` hiệu quả bị tắt. Cờ hiệu quả được giải quyết thông qua `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) vì vậy Cờ tính năng của Bảng điều khiển và các biến môi trường chi phối `/api/v1/*`, `/api/v1beta/*` và bí danh một cách nhất quán; lỗi trình giải quyết không đóng được. Cho phép yêu cầu phiên bảng thông tin trên các tuyến API của máy khách (bao gồm `/api/v1/models`, được sử dụng bởi danh mục mô hình bảng thông tin). Khi Entra ID SSO được bật, Bearer có cấu trúc là mã thông báo Entra (ba phân đoạn base64url, `RS*` alg, `kid`) được xử lý bởi nhánh SSO** trước** `validateApiKey()` và phán quyết của nó là — cuối cùng, nó không bao giờ đi đến đường dẫn khóa API hoặc nhánh chuyển đổi thành ẩn danh, do đó, việc ngừng hoạt động của nhà cung cấp danh tính không thể trở thành quyền truy cập mở. Các phím API tĩnh không bị ảnh hưởng. Xem [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — chấp nhận phiên bảng điều khiển, yêu cầu đồng bộ hóa mô hình nội bộ (khớp với `/api/providers/[name]/(sync-models|models)`) hoặc bỏ qua hoàn toàn nếu `isAuthRequired()` trả về sai. Trả về 403 (`AUTH_001`) khi có mã thông báo Bearer nhưng không hợp lệ, nếu không thì trả về 401. Đồng thời thực thi các cấp độ bảo vệ tuyến đường (LOCAL_ONLY / ALWAYS_PROTECTED) trước bất kỳ nhánh xác thực — hãy xem [Cấp độ bảo vệ tuyến đường](../security/ROUTE_GUARD_TIERS.md). Các đường dẫn LOCAL_ONLY trong `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (hôm nay: `/api/mcp/`) có thể được truy cập từ chế độ không lặp lại khi khóa Bearer mang phạm vi `manage` ; tất cả các đường dẫn LOCAL_ONLY khác vẫn ở chế độ vòng lặp nghiêm ngặt bất kể phạm vi.

Chính sách thành công trả về `AuthSubject` với `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Trình xử lý xuôi dòng có thể đọc nó qua `assertAuth(request, "CLIENT_API")` trong `src/server/authz/assertAuth.ts` thay vì chạy lại logic xác thực.

## Danh sách tuyến đường công cộng

`src/shared/constants/publicApiRoutes.ts` là danh sách cho phép rõ ràng:

Danh sách được chia theo** hình dạng** và phần phân tách có tính chất chịu tải (GHSA-74g9-q8f6-793h): tiền tố được khớp với `startsWith()`, do đó, nó cũng khớp với mọi đường dẫn liền kề có chung các ký tự đầu của nó. `/api/usage/om-usage` dưới dạng tiền tố được đánh dấu `/api/usage/om-usage<anything>` PUBLIC và Next giải quyết điều đó thành `/api/usage/[connectionId]` — một trình xử lý không có xác thực riêng.

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

Các tuyến chỉ đọc là công khai** chỉ một** để có những phương pháp an toàn. Lưu ý: `classifyRoute()` loại trừ `/api/v1/*` và `/api/v1beta/*` khỏi PUBLIC rơi vào — chúng luôn là `CLIENT_API` nên chính sách Bearer-key vẫn được áp dụng.

## Thêm route mới

### Mẫu 1 — Endpoint API công khai dành cho máy khách (xác thực bằng Bearer)

Các route trong `/api/v1/` và `/api/v1beta/` được tự động phân loại là `CLIENT_API`. Middleware thực thi bước kiểm tra Bearer; các trình xử lý route không cần thực hiện lại bước này nhưng có thể đọc chủ thể nếu cần.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... logic của trình xử lý
}
```

### Mẫu 2 — Endpoint quản lý (phiên hoặc Bearer + quyền manage)

Sử dụng `requireManagementAuth()` từ `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... logic của trình xử lý
}
```

`requireManagementAuth()` trả về `null` khi thành công hoặc một `Response` lỗi JSON:

- 401 `AUTH_001` "Yêu cầu xác thực" — hoàn toàn không có thông tin xác thực
- 403 — Bearer không hợp lệ **hoặc** có Bearer nhưng khóa không có phạm vi `manage` / `admin`

`hasManageScope(scopes)` trả về true đối với `"manage"` hoặc `"admin"`.

### Mẫu 3 — Thêm vào danh sách cho phép công khai

Chọn tập hợp dựa trên hình dạng, không phải sự tiện lợi. Một route đơn lẻ được đưa vào `PUBLIC_API_ROUTES_EXACT` (hoặc `PUBLIC_READONLY_CORS_API_ROUTES` nếu chỉ hỗ trợ GET); chỉ cây con thực sự mới được đưa vào `PUBLIC_API_ROUTE_PREFIXES`, và nó **phải kết thúc bằng `/`**. Việc đưa một route đơn lẻ vào danh sách tiền tố cũng công khai mọi đường dẫn liền kề có chung các ký tự đầu — bao gồm cả các đường dẫn ngang hàng có phân đoạn động được thêm sau này (GHSA-74g9-q8f6-793h). Cập nhật các unit test tại `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` và `tests/unit/authz/classify.test.ts`.

## Phạm vi

Ba không gian tên. Mỗi trình kiểm tra chỉ đọc các chuỗi của riêng nó. So sánh song song,
bao gồm lý do tại sao `manage` không vượt qua `scopeMatches` cho `read:compression` và tại sao một
mã thông báo truy cập `read` không thể `PATCH /api/keys/{id}`, được giải thích tại
[Ba không gian tên phạm vi](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Các khóa API mang một mảng `scopes` (được lưu trữ dưới dạng JSON trong `api_keys.scopes`, xem `src/lib/db/apiKeys.ts`).

### Phạm vi quản lý

- `manage` / `admin` — `hasManageScope`. Quyền truy cập bearer vào các tuyến API quản lý.
- `mcp:connect`, `self:usage`, `self:account-quota`, và
  `policy:bypass-provider-quota` là các phạm vi khớp chính xác có tính bổ sung. Chúng nằm
  ngoài `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` chỉ mở phần
  `/api/mcp/` không phải loopback.

### Phạm vi công cụ MCP

Danh mục và các quy tắc khớp (chuỗi giống hệt, hoặc một phạm vi được cấp kết thúc bằng `*`):
[Phạm vi công cụ MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` trong `src/shared/constants/mcpScopes.ts` là tập con được định kiểu ban đầu,
không phải toàn bộ danh mục đó. Việc thực thi chạy trong
`open-sse/mcp-server/scopeEnforcement.ts` sau khi `resolveCallerScopeContext()`
giải quyết các phạm vi từ thông tin xác thực MCP, siêu dữ liệu yêu cầu, hoặc `OMNIROUTE_MCP_SCOPES`.
Nó vẫn tắt trừ khi `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Phạm vi mã thông báo truy cập

`read` / `write` / `admin` trên các mã thông báo `oma_live_…`, được xếp hạng bởi `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Thứ hạng này chỉ áp dụng cho thông tin xác thực
mã thông báo truy cập. Xem [Xác thực quản lý](../guides/MANAGEMENT-AUTH.md).

## Công tắc yêu cầu xác thực

`isAuthRequired()` trong `src/shared/utils/apiAuth.ts` quyết định liệu **bất kỳ** xác thực nào có được áp dụng cho một yêu cầu hay không:

- `settings.requireLogin === false` → xác thực bị tắt toàn cục, ngoại trừ tầng luôn được bảo vệ (xem [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) và các lệnh gọi cấp thông tin xác thực mà nó chấp nhận, vốn cần cùng thông tin xác thực như khi đăng nhập được bật: cấp token đồng bộ, đúc access token CLI ở bất kỳ phạm vi nào, và tạo khóa API có phạm vi `manage`/`admin`, cấp phạm vi đó cho một khóa, hoặc tạo lại hay hiển thị một khóa như vậy (`requireCredentialForManagementScopedKey()` trong `src/lib/api/requireManagementAuth.ts`). Các khóa chỉ dùng cho inference vẫn mở.
- Chưa cấu hình mật khẩu **và** không có biến môi trường `INITIAL_PASSWORD` → chế độ bootstrap: trình hướng dẫn onboarding và các yêu cầu loopback được phép, nhưng các yêu cầu từ mạng bên ngoài vẫn cần thông tin xác thực.
- Bất kỳ lỗi DB nào → thất bại đóng (an toàn theo mặc định).

Việc cưỡng chế khóa API client dùng `isRequireApiKeyEnabled()` trong `src/shared/utils/featureFlags.ts`, không đọc trực tiếp `process.env.REQUIRE_API_KEY`. Điều này quan trọng với các instance đã triển khai: bật tắt `REQUIRE_API_KEY` trong Dashboard → Feature Flags sẽ lưu một ghi đè DB và ảnh hưởng ngay đến `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` cùng các kiểm tra xác thực API client khác dùng chung hàm trợ giúp này. Nếu kho feature flag không đọc được, xác thực API client thất bại đóng và yêu cầu một khóa.

## Thay đổi không tương thích — v3.8.0

Các endpoint `/api/v1/agents/tasks/*` và `/api/resilience/model-cooldowns` **hiện yêu cầu xác thực quản lý** (commit `588a0333`). Các client trước đây gửi khóa API thông thường không có phạm vi `manage` sẽ nhận được `403`. Cách chuyển đổi: cấp phạm vi `manage` cho khóa trong dashboard API Keys hoặc sử dụng một phiên dashboard đã đăng nhập.

## Thay đổi hành vi — v3.8.2

`/api/mcp/*` (máy chủ MCP từ xa) vẫn mặc định là LOCAL_ONLY nhưng hiện chấp nhận các yêu cầu không phải loopback khi header `Authorization: Bearer <api-key>` mang phạm vi `manage`. Ngoại lệ này được kiểm soát rõ ràng theo từng đường dẫn thông qua `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` trong `src/server/authz/routeGuard.ts`; tiền tố LOCAL_ONLY cùng cấp `/api/cli-tools/runtime/*` được chủ ý thiết kế để KHÔNG thể bỏ qua vì nó có thể khởi chạy các tiến trình con tùy ý. Các yêu cầu ẩn danh tới `/api/mcp/*` từ địa chỉ không phải loopback vẫn tiếp tục trả về `403 LOCAL_ONLY` — mặc định cho mọi đường dẫn LOCAL_ONLY mới vẫn là chỉ cho phép loopback một cách nghiêm ngặt. Xem [Các cấp độ Route Guard](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Kiểm thử

- Kiểm thử đơn vị: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Danh sách cho phép công khai: `tests/unit/public-api-routes.test.ts`.
- Chạy kiểm thử tập trung: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Gỡ lỗi

Quy trình luôn đóng dấu phản hồi bằng:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Đối với các yêu cầu được xác thực, các tiêu đề yêu cầu ngược dòng (phía trình xử lý) cũng bao gồm:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Sử dụng `assertAuth(req, expectedClass)` bên trong trình xử lý — nó sẽ ném `AuthzAssertionError` với mã `AUTHZ_NOT_INITIALIZED` nếu phần mềm trung gian bị bỏ qua (hữu ích để phát hiện các hồi quy cấu hình trong các thử nghiệm).

## Xem thêm

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — đánh dấu xác thực cho mỗi điểm cuối
- [COMPLIANCE.md](../security/COMPLIANCE.md) — nhật ký kiểm tra cho các sự kiện xác thực
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — ba không gian tên phạm vi và danh mục phạm vi công cụ MCP
- Nguồn: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
