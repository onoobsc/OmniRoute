# Authorization Guide (Português (Portugal))

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Fonte da verdade:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Última atualização:** 2026-09-22 — os espaços de nomes de âmbito apontam para MCP-SERVER.md

OmniRoute possui um pipeline de autorização sensível a rotas que protege cada pedido de API. A classificação é **determinística** e **fail-closed** — qualquer coisa que não possa ser classificada acaba como `MANAGEMENT` e exige uma sessão ou um token de nível de gestão. Esta página explica o modelo para engenheiros que mantêm rotas ou que desenham novos endpoints.

![Pipeline de AuthZ (3 classes de rota + avaliação de política)](../diagrams/exported/authz-pipeline.svg)

> Fonte: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Dois modos de autenticação

### 1. Chave API (portador)

Utilizado para o cliente OpenAI/Anthropic/Gemini-compatible APIs e algumas rotas de gestão quando a chave tem o âmbito `manage`.

```
Authorization: Bearer <api-key>
```

Validado por `isValidApiKey()` / `extractApiKey()` em `src/sse/services/auth.ts` e reexportado através de `src/shared/utils/apiAuth.ts`. O validador também aceita os vars `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env como chaves de passagem persistentes (problema #1350).

### 2. Sessão do painel (cookie auth_token)

Para páginas do painel e operações administrativas.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Um cookie é uma sessão apenas quando o JWT verifica** e** carrega `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Cada consumidor do cookie (painel route guard (`isDashboardSessionAuthenticated()`), authz pipeline update, handshake WebSocket, active server, `/api/settings/require-login`, `/api/auth/status`) passa por este auxiliar. Outros JWTs assinados com `JWT_SECRET` existem — o passthrough Cursor CLI cria tokens `iss "omniroute" / aud "cursor-cli"` para detentores de chaves — e nunca são sessões (#13298).

Verificado por `isDashboardSessionAuthenticated()` em `src/shared/utils/apiAuth.ts`. O pipeline atualiza automaticamente o JWT quando restam menos de 7 dias na sua vida útil de 30 dias.

Uma sessão também pode terminar antes de os seus 30 dias terminarem, porque cada minter passa por `mintDashboardSessionToken` (uma hora de emissão `iat` e um id `jti`) e o verificador verifica duas definições: `sessionsValidAfter`, definida por uma alteração de palavra-passe para que cada sessão emitida antes de parar de verificar (o browser que alterou a palavra-passe recebe um novo cookie) e `revokedDashboardSessions`, ao qual `POST /api/auth/logout` adiciona o `jti` da sessão desligada. As sessões criadas por uma versão mais antiga não têm qualquer reivindicação e permanecem válidas até à primeira alteração de palavra-passe. Se as definições não puderem ser lidas, a sessão não é fiável.

Algumas rotas de gestão aceitam** ou** mode: cookie OR `Bearer <key>` quando a chave API tem o âmbito `manage` (ou `admin`). É isto que permite o workflow "configurável através de chamadas API " adicionado na v3.8.

#### Porta de login OIDC opcional (#6973)

O login de administrador do painel também suporta um** aceitar** O fluxo OIDC (OpenID Connect) juntamente com o login de password padrão — password login nunca é removido, apenas complementado:

- Desativado, a menos que `settings.oidcEnabled === true`** e** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` estão todos configurados ( → Auth Settings). `GET /api/auth/oidc/login` retorna `400` caso contrário.
- `GET /api/auth/oidc/login` descobre o `authorization_endpoint` do `/.well-known/openid-configuration` do emissor (volta para `<issuer>/authorize`), cria o redireccionamento URI a partir do pedido recebido (`x-forwarded-proto` -aware) e redirecciona para o IdP com um `state` aleatório armazenado num cookie `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` valida `state`, troca o código de autorização e verifica a assinatura do token ID através do JWKS do emissor (`jose` de `createRemoteJWKSet`, armazenado em cache por JWKS URI) com verificações `issuer`/`audience`. A admissão no painel requer uma lista `oidcAllowedSubjects` não vazia, uma política `oidcAdmissionClaim` ou ambas. A lista de assuntos corresponde `sub` ou `email` apenas quando `email_verified === true`. A política de declaração opcional utiliza um caminho de declaração de token de ID separado por pontos (por exemplo, `realm_access.roles`) e uma matriz de valores aceites; a instrução resolvida deve ser uma matriz de strings contendo pelo menos um valor aceite. Se ambas as políticas estiverem configuradas, ambas terão de ser aprovadas. As reivindicações Missing/malformed falham o fecho e, sem qualquer uma das políticas, o callback recusa o login (`not_configured`). As definições existentes apenas de motivo permanecem inalteradas.
- O keycloak mapeia normalmente as funções de domínio em tokens de acesso, não necessariamente em tokens ID. Para exigir a função de região `admin`, configure um mapeador de protocolo para esse cliente que inclua `realm_access.roles` no seu** token ID** e defina `oidcAdmissionClaim` como `{ "path": "realm_access.roles", "values": ["admin"] }`. Verifique a reivindicação real do token de ID deste cliente antes de ativar a admissão apenas de funções; a aplicação não lê funções de token de acesso. A recusa do token do lado do IdP pode complementar, mas não substitui, esta verificação do lado da aplicação.
- Com sucesso, ele cunha o** exatamente o mesmo** 30 dias `auth_token` JWT os problemas de login da palavra-passe (`src/app/api/auth/login/route.ts`), pelo que o resto do pipeline da sessão do painel (atualização automática, sinalizadores de cookies) permanece inalterado — OIDC apenas substitui a forma como o cookie é criado, não o que concede. As alterações ao IdP roles/groups não invalidam as sessões OmniRoute existentes; logout, rotação de palavra-passe ou expiração de sessão ainda regem a sua vida útil.
- Cada configuração `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) está em `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` responde `400 PASSWORD_REQUIRED` a menos que o corpo carregue a palavra-passe de gestão como `currentPassword` (`401 PASSWORD_MISMATCH` quando está errada). `oidcDisablePasswordLogin` recusa a palavra-passe _login_ (`POST /api/auth/login`), mas mantém o hash da palavra-passe armazenada e a reautenticação ainda verifica `currentPassword` contra ela.
- `corsOrigins` e `bruteForceProtection` também estão no `SECURITY_IMPACTING_SETTINGS_KEYS` : afrouxar ou enfraquece as defesas de login, depois fazem a mesma reautenticação `currentPassword` (o separador Segurança pede isso) e a importação JSON descarta-as.
- Cada chave de política de segurança — as entradas `SECURITY_IMPACTING_SETTINGS_KEYS`, cada chave `oidc*` e o estado da sessão do painel — são** somente operador** em `PATCH /api/settings`: uma chave API com âmbito de gestão ou um token de acesso `oma_` é recusado com `403` mesmo quando envia o `currentPassword` correto, e a recusa é auditada como `settings.update_failed` com `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` em `src/lib/api/operatorCredential.ts`). As definições comuns (tema, preferências de visualização) permanecem graváveis para uma chave `manage` ou um token de acesso `admin`. Cada mutação do próprio `/api/settings` (e do `/api/settings/require-login`) necessita também do âmbito do token de acesso `admin` (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, correspondência de caminho exato); `GET` permanece `read`, e as outras sub-rotas `/api/settings/*` (proxies, padrões de combinação, aliases de modelo, compressão, limpezas…) mantêm o âmbito `write` inferido pelo método.
- `POST /api/settings/import-json` ignora esta nova autenticação, pelo que descarta todas as chaves em `IMPORT_STRIPPED_SETTINGS_KEYS` (mesmo ficheiro) antes de escrever: a palavra-passe e `currentPassword`, cada entrada `SECURITY_IMPACTING_SETTINGS_KEYS` e o estado da sessão do painel (`sessionsValidAfter`, `revokedDashboardSessions`). A importação de um backup mais antigo não pode, portanto, reavivar uma sessão cuja alteração de palavra-passe ou logout já tenha terminado.

#### Login opcional TOTP de dois factores (#16619)

Inscrito em Configurações → Security; desligado até que o operador o ligue (`src/server/auth/dashboardMfa.ts`).

- **O que cobre:** login de password (`POST /api/auth/login`, que necessita então `POST /api/auth/mfa/verify`) e `omniroute connect` (`POST /api/cli/connect`, que recusa uma alteração apenas de password e assume o código como `totp`).
- **O que não cobre:** O login OIDC / SSO (`/api/auth/oidc/callback`) não solicita o OmniRoute TOTP. Depende do segundo fator do próprio fornecedor de identidade, por isso aplique MFA no IdP se OIDC estiver ativado.
- **Recuperação** (dispositivo perdido, sem código de recuperação restante ou um fator que já não pode ser verificado, por exemplo, após a alteração `STORAGE_ENCRYPTION_KEY` ):
  1. Reinicie o servidor com `OMNIROUTE_DISABLE_MFA=true`.
  2. No próprio host (loopback point e loopback `Host`, como `http://localhost:20128`), inicie sessão com a palavra-passe. O segundo fator é ignorado apenas para esta origem; todas as outras origens ainda necessitam do código.
  3. Em Definições → Segurança → Desativar, introduza a palavra-passe e deixe o código em branco. `POST /api/auth/mfa/disable` aceita um corpo sem `code` apenas enquanto a variável está definida e o pedido vem do host; ainda requer a sessão do painel e a palavra-passe atual e é auditado como `auth.mfa.disabled` com `secondFactor: "recovery_switch"`.
  4. Desmarque `OMNIROUTE_DISABLE_MFA`, reinicie e volte a inscrever-se, se necessário.

## Classes de rotas

`src/server/authz/types.ts` define três classes; qualquer rota que não possa ser classificada de forma determinística recorre a `MANAGEMENT`.

| Classe       | Descrição                                                                                                                                                                  | Autenticação necessária                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| `PUBLIC`     | Rotas explicitamente seguras: início de sessão, fim de sessão, estado, inicialização, verificação de funcionamento e bootstrap do onboarding.                              | Nenhuma                                                                   |
| `CLIENT_API` | Pontos finais de disponibilização de modelos: `/api/v1/*`, `/api/v1beta/*`, além dos alias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Chave Bearer quando a funcionalidade `REQUIRE_API_KEY` efetiva está ativa |
| `MANAGEMENT` | Páginas do painel, definições, fornecedores, chaves, pontos finais de administração e diagnóstico.                                                                         | Sessão do painel OU Bearer com âmbito `manage`                            |

Algumas ações de `MANAGEMENT` são **exclusivas do operador**: uma chave `manage` não basta. Exportar credenciais guardadas (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), restaurar uma cópia de segurança sobre os dados ativos (`POST /api/db-backups/import`, incluindo `dryRun=true`, `POST /api/db-backups` com restauro por id, `POST /api/settings/import-json`), e eliminar pontos de restauro (a limpeza com `DELETE /api/db-backups` e `PATCH /api/db-backups`, porque a retenção que este guarda controla a poda automática após cada cópia de segurança) exigem uma sessão do painel, a identidade da CLI local ou o início de sessão desativado. Emitir um token de sincronização (`POST /api/sync/tokens`) e criar um token de acesso da CLI com âmbito `admin` (`POST /api/cli/tokens`) exigem, em todos os modos de início de sessão, uma sessão do painel ou a identidade da CLI local. As chaves de API de qualquer âmbito e os tokens de acesso `oma_` não são credenciais de operador: recebem `403` sempre que alguma destas for exigida. A verificação está em `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Alterar as definições de início de sessão também é exclusivo do operador: `POST /api/settings/require-login` (definir a palavra-passe de gestão / ativar ou desativar `requireLogin`) aceita apenas estas credenciais depois de existir uma palavra-passe. A janela de bootstrap da primeira execução (ainda sem palavra-passe) mantém-se inalterada, e uma sessão do painel tem de enviar `currentPassword` para substituir a palavra-passe (`403` se faltar ou estiver errada, auditado como `settings.update_failed`). A CLI local e uma instância com o início de sessão desativado mantêm o caminho de recuperação e podem definir uma palavra-passe sem esse passo, pois ambos estão vinculados ao anfitrião que detém o diretório de dados.

## Gasoduto

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

Os cabeçalhos internos fiáveis (definidos em `src/server/authz/headers.ts`) são** removido das solicitações recebidas** antes da classificação, os clientes — não podem preencher previamente `x-omniroute-auth-*` para representar um sujeito.

### Contratos de apólices

Cada classe de rota tem uma política em `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — devolve sempre `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — extrai Bearer, valida através de `validateApiKey()`. Passa para anónimo apenas quando o sinalizador de recurso `REQUIRE_API_KEY` efetivo está desativado. O sinalizador efetivo é resolvido através de `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`) para que os sinalizadores de recursos do painel e as variáveis de ambiente governem `/api/v1/*`, `/api/v1beta/*` e aliases de forma consistente; falhas do resolvedor falham no fecho. Permite pedidos de sessão de painel nas rotas API do cliente (incluindo `/api/v1/models`, utilizado pelo catálogo de modelos de painel). Quando Entra ID SSO está habilitado, um Bearer que é estruturalmente um token Entra (três segmentos base64url, `RS*` alg, `kid`) é tratado pela ramificação SSO** antes** `validateApiKey()` e o seu veredicto é final — nunca passa pelo caminho da chave API ou pela ramificação degradada para anónima, pelo que uma interrupção do fornecedor de identidade não pode tornar-se acesso aberto. As chaves API estáticas não são afetadas. Consulte [Entrada ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — aceita sessão de painel, pedidos internos de sincronização de modelo (correspondidos a `/api/providers/[name]/(sync-models|models)`) ou ignora completamente se `isAuthRequired()` retornar falso. Retorna 403 (`AUTH_001`) quando um token Bearer está presente, mas é inválido, 401 caso contrário. Também impõe os níveis de proteção de rota (LOCAL_ONLY / ALWAYS_PROTECTED) antes de qualquer ramo de autenticação — consulte [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). Os caminhos LOCAL_ONLY em `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (hoje: `/api/mcp/`) podem ser acedidos sem loopback quando a chave Bearer carrega o escopo `manage` ; todos os outros caminhos LOCAL_ONLY permanecem em loopback estrito, independentemente do âmbito.

Uma política bem-sucedida retorna `AuthSubject` com `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Os manipuladores a jusante podem lê-lo via `assertAuth(request, "CLIENT_API")` no `src/server/authz/assertAuth.ts` em vez de executar novamente a lógica de autenticação.

## Lista de Rotas Públicas

`src/shared/constants/publicApiRoutes.ts` é a lista de permissões explícita:

A lista está dividida por** forma** , e a divisão é de suporte de carga (GHSA-74g9-q8f6-793h): um prefixo é combinado com `startsWith()`, pelo que corresponde também a todos os caminhos adjacentes que partilham os seus caracteres iniciais. `/api/usage/om-usage` como um prefixo marcado `/api/usage/om-usage<anything>` PUBLIC e Next resolve isto para `/api/usage/[connectionId]` — um manipulador sem autenticação própria.

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

As rotas somente leitura são públicas** apenas** para métodos seguros. Nota: `classifyRoute()` exclui `/api/v1/*` e `/api/v1beta/*` do PUBLIC fall-through — estes são sempre `CLIENT_API` pelo que a política da chave do portador ainda se aplica.

## Adicionar uma Nova Rota

### Padrão 1 — Endpoint público da API de cliente (autenticação Bearer)

As rotas em `/api/v1/` e `/api/v1beta/` são classificadas automaticamente como `CLIENT_API`. O middleware aplica a verificação Bearer; os handlers das rotas não precisam de a repetir, mas podem ler o sujeito se tal for útil.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... lógica do handler
}
```

### Padrão 2 — Endpoint de gestão (sessão ou Bearer + manage)

Utilize `requireManagementAuth()` de `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... lógica do handler
}
```

`requireManagementAuth()` devolve `null` em caso de sucesso ou uma `Response` de erro JSON:

- 401 `AUTH_001` "Autenticação necessária" — não existem quaisquer credenciais
- 403 — Bearer inválido **ou** Bearer presente, mas a chave não tem o âmbito `manage` / `admin`

`hasManageScope(scopes)` devolve true para `"manage"` ou `"admin"`.

### Padrão 3 — Adicionar à lista de permissões pública

Escolha o conjunto com base no formato, não na conveniência. Uma rota deve ser adicionada a `PUBLIC_API_ROUTES_EXACT` (ou a `PUBLIC_READONLY_CORS_API_ROUTES` se for apenas GET); apenas uma subárvore genuína deve ser adicionada a `PUBLIC_API_ROUTE_PREFIXES`, e esta **deve terminar em `/`**. Colocar uma única rota na lista de prefixos também torna público qualquer caminho adjacente que partilhe os respetivos caracteres iniciais — incluindo caminhos irmãos com segmentos dinâmicos adicionados posteriormente (GHSA-74g9-q8f6-793h). Atualize os testes unitários em `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` e `tests/unit/authz/classify.test.ts`.

## Âmbitos

Três espaços de nomes. Cada verificador lê apenas as suas próprias strings. A comparação lado a lado,
incluindo por que razão `manage` falha `scopeMatches` para `read:compression` e por que razão um
token de acesso `read` não pode `PATCH /api/keys/{id}`, está em
[Três espaços de nomes de âmbito](../frameworks/MCP-SERVER.md#three-scope-namespaces).

As chaves de API contêm um array `scopes` (armazenado como JSON em `api_keys.scopes`, veja `src/lib/db/apiKeys.ts`).

### Âmbito de gestão

- `manage` / `admin` — `hasManageScope`. Acesso de portador a rotas da API de gestão.
- `mcp:connect`, `self:usage`, `self:account-quota` e
  `policy:bypass-provider-quota` são âmbitos aditivos de correspondência exata. Eles situam-se
  fora de `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` abre apenas o
  recorte não-loopback `/api/mcp/`.

### Âmbitos da ferramenta MCP

Catálogo e regras de correspondência (string idêntica, ou um âmbito concedido que termina em `*`):
[Âmbitos da ferramenta MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` em `src/shared/constants/mcpScopes.ts` é o subconjunto tipado
original, não o catálogo completo. A aplicação é executada em
`open-sse/mcp-server/scopeEnforcement.ts` depois de `resolveCallerScopeContext()`
resolver os âmbitos a partir das informações de autenticação do MCP, metadados do pedido ou `OMNIROUTE_MCP_SCOPES`.
Permanece desativado a menos que `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Âmbitos do token de acesso

`read` / `write` / `admin` em tokens `oma_live_…`, classificados por `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Esta classificação aplica-se apenas à credencial
do token de acesso. Veja [Autenticação de Gestão](../guides/MANAGEMENT-AUTH.md).

## Alternador de autenticação obrigatória

`isAuthRequired()` em `src/shared/utils/apiAuth.ts` decide se **qualquer** autenticação é imposta a um pedido:

- `settings.requireLogin === false` → a autenticação fica desativada globalmente, exceto para o nível sempre protegido (ver [Níveis do Route Guard](../security/ROUTE_GUARD_TIERS.md)) e para as chamadas que entregam uma credencial que este aceita. Estas exigem a mesma credencial que com o início de sessão ativo: emitir tokens de sincronização, criar tokens de acesso da CLI de qualquer âmbito, criar uma chave de API com âmbito `manage`/`admin`, conceder esse âmbito a uma chave, ou regenerar ou revelar uma chave assim (`requireCredentialForManagementScopedKey()` em `src/lib/api/requireManagementAuth.ts`). As chaves apenas de inferência continuam abertas.
- Nenhuma palavra-passe configurada **e** nenhuma variável de ambiente `INITIAL_PASSWORD` → o modo de bootstrap permite o assistente de onboarding e os pedidos de loopback, mas os pedidos de rede expostos continuam a exigir credenciais.
- Qualquer erro da base de dados → falha em modo fechado (seguro por omissão).

A aplicação das chaves de API de cliente usa `isRequireApiKeyEnabled()` em `src/shared/utils/featureFlags.ts`, e não uma leitura direta de `process.env.REQUIRE_API_KEY`. Isto importa para instâncias implementadas: alterar `REQUIRE_API_KEY` em Dashboard → Feature Flags guarda uma substituição na base de dados e afeta de imediato `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` e as restantes verificações de autenticação da API de cliente que partilham este auxiliar. Se o armazenamento das feature flags não puder ser lido, a autenticação da API de cliente falha em modo fechado e exige uma chave.

## Alteração incompatível — v3.8.0

Os endpoints `/api/v1/agents/tasks/*` e `/api/resilience/model-cooldowns` **agora requerem autenticação de gestão** (commit `588a0333`). Os clientes que anteriormente enviavam uma chave de API normal sem o âmbito `manage` recebem `403`. Migração: atribua à chave o âmbito `manage` no painel API Keys ou utilize uma sessão autenticada no painel.

## Alteração de comportamento — v3.8.2

`/api/mcp/*` (o servidor MCP remoto) continua a ser LOCAL_ONLY por predefinição, mas agora aceita pedidos que não sejam de loopback quando o cabeçalho `Authorization: Bearer <api-key>` inclui o âmbito `manage`. A exceção é explicitamente controlada por caminho através de `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` em `src/server/authz/routeGuard.ts`; o prefixo LOCAL_ONLY relacionado `/api/cli-tools/runtime/*` não pode, intencionalmente, contornar esta restrição, pois pode iniciar subprocessos arbitrários. Os pedidos anónimos para `/api/mcp/*` que não sejam de loopback continuam a devolver `403 LOCAL_ONLY` — a predefinição para qualquer novo caminho LOCAL_ONLY continua a exigir estritamente loopback. Consulte [Níveis de proteção de rotas](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Testes

- Testes unitários: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Lista de permissões pública: `tests/unit/public-api-routes.test.ts`.
- Execução focada: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Depuração

O pipeline carimba sempre as respostas com:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Para pedidos autenticados, os cabeçalhos de pedido upstream (lado do manipulador) também incluem:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Use `assertAuth(req, expectedClass)` dentro dos manipuladores — lança `AuthzAssertionError` com código `AUTHZ_NOT_INITIALIZED` se o middleware foi ignorado (útil para capturar regressões de configuração em testes).

## Ver Também

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — marcador de autenticação por endpoint
- [COMPLIANCE.md](../security/COMPLIANCE.md) — registo de auditoria para eventos de autenticação
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — três namespaces de escopo e catálogo de escopo de ferramenta MCP
- Fonte: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
