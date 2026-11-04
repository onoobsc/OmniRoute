# Authorization Guide (Français)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇷 [el](../../../el/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Source de vérité :** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Dernière mise à jour :** 2026-09-22 — les espaces de noms de portée pointent vers MCP-SERVER.md

OmniRoute dispose d'un pipeline d'autorisation sensible aux routes qui filtre chaque requête API. La classification est **déterministe** et **fermée par défaut** — tout ce qui ne peut pas être classifié est considéré comme `MANAGEMENT` et exige une session ou un jeton de niveau gestion. Cette page explique le modèle aux ingénieurs qui maintiennent des routes ou conçoivent de nouveaux points de terminaison.

![Pipeline d'autorisation (3 classes de routes + évaluation des politiques)](../diagrams/exported/authz-pipeline.svg)

> Source : [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Deux modes d'authentification

### 1. Clé API (Porteur)

Utilisé pour le client OpenAI/Anthropic/Gemini-compatible APIs et quelques routes de gestion lorsque la clé a la portée `manage`.

```
Authorization: Bearer <api-key>
```

Validé par `isValidApiKey()` / `extractApiKey()` dans `src/sse/services/auth.ts` et réexporté via `src/shared/utils/apiAuth.ts`. Le validateur accepte également les variables d'environnement `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` comme clés de relais persistantes (problème #1350).

### 2. Session de tableau de bord (cookie auth_token)

Pour les pages de tableau de bord et les opérations d'administration.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Un cookie est une session uniquement lorsque le JWT vérifie** et** porte `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Chaque consommateur du cookie (dashboard route guard (`isDashboardSessionAuthenticated()`), actualisation du pipeline authz, poignée de main WebSocket, serveur en direct, `/api/settings/require-login`, `/api/auth/status`) passe par cet assistant. D'autres JWTs signés avec `JWT_SECRET` existent — le Cursor CLI passthrough crée des jetons `iss "omniroute" / aud "cursor-cli"` pour les détenteurs de clés — et ne sont jamais des sessions (#13298).

Vérifié par `isDashboardSessionAuthenticated()` dans `src/shared/utils/apiAuth.ts`. Le pipeline actualise automatiquement le JWT lorsqu'il lui reste moins de 7 jours au cours de sa durée de vie de 30 jours.

Une session peut également se terminer avant la fin de ses 30 jours, car chaque contrôleur passe par `mintDashboardSessionToken` (une heure d'émission `iat` et un identifiant `jti`) et le vérificateur vérifie deux paramètres : `sessionsValidAfter`, défini par un changement de mot de passe afin que chaque session émise avant d'arrêter la vérification (le navigateur qui a modifié le mot de passe reçoit un nouveau cookie), et `revokedDashboardSessions`, auquel `POST /api/auth/logout` ajoute le `jti` de la session déconnectée. Les sessions créées par une version plus ancienne ne comportent aucune revendication et restent valides jusqu'au premier changement de mot de passe. Si les paramètres ne peuvent pas être lus, la session n'est pas approuvée.

Certaines voies de gestion acceptent** soit** mode : cookie OR `Bearer <key>` lorsque la clé API a la portée `manage` (ou `admin`). C'est ce qui permet le workflow « configurable via les appels API » ajouté dans la v3.8.

#### Porte de connexion OIDC en option (#6973)

La connexion administrateur du tableau de bord prend également en charge un** s'inscrire** Le flux OIDC (OpenID Connect) parallèlement à la connexion par mot de passe par défaut la connexion par mot de passe — n'est jamais supprimé, seulement complété :

- Désactivé sauf si `settings.oidcEnabled === true`** et** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` sont tous configurés (Paramètres → Auth). `GET /api/auth/oidc/login` renvoie `400` sinon.
- `GET /api/auth/oidc/login` découvre le `authorization_endpoint` à partir du `/.well-known/openid-configuration` de l'émetteur (revient à `<issuer>/authorize`), construit le URI de redirection à partir de la requête entrante (`x-forwarded-proto` -aware) et redirige vers le IdP avec un `state` aléatoire stocké dans un cookie `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` valide `state`, échange le code d'autorisation et vérifie la signature du jeton ID via le JWKS de l'émetteur (`jose` de `createRemoteJWKSet`, mis en cache par JWKS URI) avec des contrôles `issuer`/`audience`. L'admission au tableau de bord nécessite une liste `oidcAllowedSubjects` non vide, une stratégie `oidcAdmissionClaim` ou les deux. La liste de sujets correspond à `sub` ou `email` uniquement lorsque `email_verified === true`. La stratégie de revendication facultative prend un chemin de revendication de jeton d'identification séparé par des points (par exemple, `realm_access.roles`) et un tableau de valeurs acceptées ; la revendication résolue doit être un tableau de chaînes contenant au moins une valeur acceptée. Si les deux stratégies sont configurées, elles doivent toutes deux réussir. Les réclamations Missing/malformed échouent et sans aucune des deux politiques, le rappel refuse la connexion (`not_configured`). Les configurations thématiques existantes restent inchangées.
- Keycloak mappe normalement les rôles de domaine en jetons d'accès, pas nécessairement en jetons ID. Pour exiger le rôle de domaine `admin`, configurez un mappeur de protocole pour ce client qui inclut `realm_access.roles` dans son** jeton ID** , puis définissez `oidcAdmissionClaim` sur `{ "path": "realm_access.roles", "values": ["admin"] }`. Vérifiez la réclamation réelle du jeton d'identification pour ce client avant d'activer l'admission de rôle uniquement ; l'application ne lit pas les rôles de jeton d'accès. Le refus de jeton côté IdP peut compléter mais ne remplace pas cette vérification côté application.
- En cas de succès, il frappe le** exactement pareil** 30 jours `auth_token` JWT les problèmes de connexion par mot de passe (`src/app/api/auth/login/route.ts`), de sorte que le reste du pipeline de session du tableau de bord (actualisation automatique, indicateurs de cookie) reste inchangé — OIDC remplace uniquement la façon dont le cookie est créé, pas ce qu'il accorde. Les modifications apportées à IdP roles/groups n'invalident pas les sessions OmniRoute existantes ; la déconnexion, la rotation des mots de passe ou l’expiration de la session régissent toujours leur durée de vie.
- Chaque paramètre `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) est en `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`) : `PATCH /api/settings` répond `400 PASSWORD_REQUIRED` sauf si le corps porte le mot de passe de gestion comme `currentPassword` (`401 PASSWORD_MISMATCH` lorsqu'il est erroné). `oidcDisablePasswordLogin` refuse le mot de passe _login_ (`POST /api/auth/login`) mais conserve le hachage du mot de passe stocké et la réauthentification vérifie toujours `currentPassword` par rapport à celui-ci.
- `corsOrigins` et `bruteForceProtection` sont également dans `SECURITY_IMPACTING_SETTINGS_KEYS` : le relâchement affaiblit les défenses de connexion, ils prennent donc la même ré-authentification `currentPassword` (l'onglet Sécurité le demande) et l'importation JSON les supprime.
- Chaque clé de politique de sécurité — les entrées `SECURITY_IMPACTING_SETTINGS_KEYS`, chaque clé `oidc*` et l'état de session du tableau de bord — sont** réservé à l'opérateur** sur `PATCH /api/settings`: une clé API de portée gérée ou un jeton d'accès `oma_` est refusé avec `403` même lorsqu'il envoie le bon `currentPassword`, et le refus est audité comme `settings.update_failed` avec `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` in `src/lib/api/operatorCredential.ts`). Les paramètres ordinaires (thème, préférences d'affichage) restent accessibles en écriture pour une clé `manage` ou un jeton d'accès `admin`. Chaque mutation de `/api/settings` lui-même (et de `/api/settings/require-login`) nécessite également la portée du jeton d'accès `admin` (`ADMIN_MUTATION_EXACT_PATHS` in `src/server/authz/accessScopes.ts`, correspondance exacte du chemin) ; `GET` reste `read`, et les autres sous-routes `/api/settings/*` (proxys, combos par défaut, alias de modèle, compression, purges…) conservent la portée `write` déduite de la méthode.
- `POST /api/settings/import-json` ignore cette réauthentification, il supprime donc chaque clé de `IMPORT_STRIPPED_SETTINGS_KEYS` (même fichier) avant d'écrire : le mot de passe et `currentPassword`, chaque entrée `SECURITY_IMPACTING_SETTINGS_KEYS` et l'état de la session du tableau de bord (`sessionsValidAfter`, `revokedDashboardSessions`). L'importation d'une sauvegarde plus ancienne ne peut donc pas relancer une session déjà terminée par un changement de mot de passe ou une déconnexion.

#### Connexion facultative à deux facteurs TOTP (#16619)

Inscrit à partir des paramètres → Security ; éteint jusqu'à ce que l'opérateur l'allume (`src/server/auth/dashboardMfa.ts`).

- **Ce qu'il couvre :** connexion par mot de passe (`POST /api/auth/login`, qui a alors besoin `POST /api/auth/mfa/verify`) et `omniroute connect` (`POST /api/cli/connect`, qui refuse un échange de mot de passe uniquement et prend le code comme `totp`).
- **Ce qu'il ne couvre pas :** La connexion OIDC / SSO (`/api/auth/oidc/callback`) ne demande pas le OmniRoute TOTP. Il s'appuie sur le deuxième facteur du fournisseur d'identité, donc appliquez MFA dans le IdP si OIDC est activé.
- **Récupération** (appareil perdu, aucun code de récupération restant ou un facteur qui ne peut plus être vérifié, par exemple après la modification `STORAGE_ENCRYPTION_KEY` ) :
  1. Redémarrez le serveur avec `OMNIROUTE_DISABLE_MFA=true`.
  2. Sur l'hôte lui-même (loopback peer et loopback `Host`, tel que `http://localhost:20128`), connectez-vous avec le mot de passe. Le deuxième facteur est ignoré pour cette origine uniquement ; toute autre origine a toujours besoin du code.
  3. Dans Paramètres → Security → Disable, entrez le mot de passe et laissez le code vide. `POST /api/auth/mfa/disable` accepte un corps sans `code` uniquement lorsque la variable est définie et que la requête provient de l'hôte ; il nécessite toujours la session du tableau de bord et le mot de passe actuel, et est audité comme `auth.mfa.disabled` avec `secondFactor: "recovery_switch"`.
  4. Désactivez `OMNIROUTE_DISABLE_MFA`, redémarrez et inscrivez-vous à nouveau si nécessaire.

## Classes de routes

`src/server/authz/types.ts` définit trois classes ; toute route qui ne peut pas être classée de façon déterministe revient à `MANAGEMENT`.

| Classe       | Description                                                                                                                                                                      | Authentification requise                                                                |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| `PUBLIC`     | Routes explicitement sûres : connexion, déconnexion, statut, initialisation, vérification de l'état et amorçage de l'onboarding.                                                 | Aucune                                                                                  |
| `CLIENT_API` | Points de terminaison de service des modèles : `/api/v1/*`, `/api/v1beta/*`, ainsi que les alias `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Clé Bearer lorsque l'indicateur de fonctionnalité `REQUIRE_API_KEY` effectif est activé |
| `MANAGEMENT` | Pages du tableau de bord, paramètres, fournisseurs, clés, points de terminaison d'administration et de diagnostic.                                                               | Session du tableau de bord OU Bearer avec la portée `manage`                            |

Quelques actions de `MANAGEMENT` sont **réservées à l'opérateur** : une clé `manage` ne suffit pas. L'export des identifiants stockés (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), la restauration d'une sauvegarde par-dessus les données en service (`POST /api/db-backups/import`, y compris avec `dryRun=true`, `POST /api/db-backups` avec restauration par identifiant, `POST /api/settings/import-json`), et la suppression des points de restauration (nettoyage par `DELETE /api/db-backups` et `PATCH /api/db-backups`, car la rétention qu'il enregistre pilote l'élagage automatique après chaque sauvegarde) exigent une session du tableau de bord, l'identité de la CLI locale, ou une connexion désactivée. L'émission d'un jeton de synchronisation (`POST /api/sync/tokens`) et la création d'un jeton d'accès CLI de portée `admin` (`POST /api/cli/tokens`) exigent, quel que soit le mode de connexion, une session du tableau de bord ou l'identité de la CLI locale. Les clés d'API de toute portée et les jetons d'accès `oma_` ne sont pas des identifiants opérateur : ils reçoivent `403` chaque fois que l'un de ces identifiants est requis. La vérification se trouve dans `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). La modification des réglages de connexion est également réservée à l'opérateur : `POST /api/settings/require-login` (définir le mot de passe de gestion / activer ou désactiver `requireLogin`) n'accepte ces identifiants qu'une fois un mot de passe existant ; la fenêtre d'amorçage de la première exécution (pas encore de mot de passe) reste inchangée. Une session du tableau de bord doit envoyer `currentPassword` pour remplacer le mot de passe (`403` s'il est absent ou erroné, audité comme `settings.update_failed`). La CLI locale et une instance à connexion désactivée conservent le chemin de récupération et peuvent définir un mot de passe sans cette étape, car tous deux sont liés à l'hôte qui possède le répertoire de données.

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

Les en-têtes internes de confiance (définis dans `src/server/authz/headers.ts`) sont** supprimé des demandes entrantes** avant la classification, les clients — ne peuvent pas pré-remplir `x-omniroute-auth-*` pour usurper l'identité d'un sujet.

### Contrats de politique

Chaque classe de route a une politique dans `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — renvoie toujours `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — extrait Bearer, valide via `validateApiKey()`. Passe à l'anonymat uniquement lorsque l'indicateur de fonctionnalité `REQUIRE_API_KEY` efficace est désactivé. L'indicateur effectif est résolu via `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), de sorte que les indicateurs de fonctionnalités du tableau de bord et les variables d'environnement régissent `/api/v1/*`, `/api/v1beta/*` et les alias de manière cohérente ; les échecs du résolveur échouent. Autorise les requêtes de session de tableau de bord sur les routes API du client (y compris `/api/v1/models`, utilisé par le catalogue de modèles de tableau de bord). Lorsque Entra ID SSO est activé, un porteur qui est structurellement un jeton Entra (trois segments base64url, `RS*` alg, `kid`) est géré par la branche SSO** avant** `validateApiKey()` et son verdict est définitif — il ne passe jamais par le chemin de la clé API ou la branche de dégradation vers anonyme, donc une panne du fournisseur d'identité ne peut pas devenir un accès ouvert. Les clés API statiques ne sont pas affectées. Voir [Entrée ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — accepte la session de tableau de bord, les demandes de synchronisation de modèle internes (correspondantes à `/api/providers/[name]/(sync-models|models)`) ou les ignore complètement si `isAuthRequired()` renvoie false. Renvoie 403 (`AUTH_001`) lorsqu'un jeton Bearer est présent mais invalide, 401 sinon. Applique également les niveaux de garde de route (LOCAL_ONLY / ALWAYS_PROTECTED) avant toute branche d'authentification — voir [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). les chemins LOCAL_ONLY dans `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (aujourd'hui : `/api/mcp/`) sont accessibles depuis le non-bouclage lorsque la clé Bearer porte la portée `manage` ; tous les autres chemins LOCAL_ONLY restent en bouclage strict, quelle que soit la portée.

Une politique réussie renvoie `AuthSubject` avec `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Les gestionnaires en aval peuvent le lire via `assertAuth(request, "CLIENT_API")` dans `src/server/authz/assertAuth.ts` au lieu de réexécuter la logique d'authentification.

## Liste des itinéraires publics

`src/shared/constants/publicApiRoutes.ts` est la liste blanche explicite :

La liste est divisée par** forme** , et la division est porteuse (GHSA-74g9-q8f6-793h) : un préfixe correspond à `startsWith()`, il correspond donc également à chaque chemin adjacent partageant ses caractères principaux. `/api/usage/om-usage` comme préfixe marqué `/api/usage/om-usage<anything>` PUBLIC, et Next résout cela en `/api/usage/[connectionId]` — un gestionnaire sans authentification propre.

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

Les itinéraires en lecture seule sont publics** seulement** pour des méthodes sûres. Remarque : `classifyRoute()` exclut `/api/v1/*` et `/api/v1beta/*` du PUBLIC fall-through — ceux-ci sont toujours `CLIENT_API` donc la politique de clé du porteur s'applique toujours.

## Ajout d’une nouvelle route

### Modèle 1 — Point de terminaison public de l’API cliente (authentification Bearer)

Les routes sous `/api/v1/` et `/api/v1beta/` sont automatiquement classées `CLIENT_API`. Le middleware applique la vérification Bearer ; les gestionnaires de routes n’ont pas besoin de la répéter, mais peuvent lire le sujet si nécessaire.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... logique du gestionnaire
}
```

### Modèle 2 — Point de terminaison de gestion (session ou Bearer + manage)

Utilisez `requireManagementAuth()` depuis `src/lib/api/requireManagementAuth.ts` :

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... logique du gestionnaire
}
```

`requireManagementAuth()` renvoie `null` en cas de succès, ou une `Response` d’erreur JSON :

- 401 `AUTH_001` « Authentification requise » — aucun identifiant fourni
- 403 — Bearer non valide **ou** Bearer présent, mais la clé ne possède pas la portée `manage` / `admin`

`hasManageScope(scopes)` renvoie true pour `"manage"` ou `"admin"`.

### Modèle 3 — Ajout à la liste d’autorisation publique

Choisissez l’ensemble en fonction de la forme, et non par commodité. Une route individuelle doit être placée dans `PUBLIC_API_ROUTES_EXACT` (ou dans `PUBLIC_READONLY_CORS_API_ROUTES` si elle accepte uniquement GET) ; seule une véritable sous-arborescence doit être placée dans `PUBLIC_API_ROUTE_PREFIXES`, et elle **doit se terminer par `/`**. Placer une route individuelle dans la liste des préfixes publie également tous les chemins adjacents qui partagent ses premiers caractères — y compris les routes sœurs à segment dynamique ajoutées ultérieurement (GHSA-74g9-q8f6-793h). Mettez à jour les tests unitaires dans `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` et `tests/unit/authz/classify.test.ts`.

## Portées

Trois espaces de noms. Chaque vérificateur ne lit que ses propres chaînes. La comparaison côte à côte, y compris pourquoi `manage` échoue `scopeMatches` pour `read:compression` et pourquoi un jeton d'accès `read` ne peut pas `PATCH /api/keys/{id}`, se trouve dans [Trois espaces de noms de portée](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Les clés API contiennent un tableau `scopes` (stocké au format JSON dans `api_keys.scopes`, voir `src/lib/db/apiKeys.ts`).

### Portée de gestion

- `manage` / `admin` — `hasManageScope`. Accès Bearer aux routes de l'API de gestion.
- `mcp:connect`, `self:usage`, `self:account-quota`, et
  `policy:bypass-provider-quota` sont des portées additives à correspondance exacte. Elles se situent
  en dehors de `MANAGEMENT_API_KEY_SCOPES`. `mcp:connect` ouvre uniquement la
  découpe non-loopback `/api/mcp/`.

### Portées des outils MCP

Catalogue et règles de correspondance (chaîne identique, ou une portée accordée se terminant par `*`) :
[Portées des outils MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
`MCP_SCOPE_LIST` dans `src/shared/constants/mcpScopes.ts` est le sous-ensemble typé original,
et non le catalogue complet. L'application s'exécute dans
`open-sse/mcp-server/scopeEnforcement.ts` après que `resolveCallerScopeContext()`
résolve les portées à partir des informations d'authentification MCP, des métadonnées de requête ou de `OMNIROUTE_MCP_SCOPES`.
Elle reste désactivée à moins que `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Portées des jetons d'accès

`read` / `write` / `admin` sur les jetons `oma_live_…`, classés par `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Ce classement s'applique uniquement aux identifiants
du jeton d'accès. Voir [Authentification de gestion](../guides/MANAGEMENT-AUTH.md).

## Bascule « authentification requise »

`isAuthRequired()` dans `src/shared/utils/apiAuth.ts` décide si **une quelconque** authentification est imposée à une requête :

- `settings.requireLogin === false` → l'authentification est désactivée globalement, à l'exception du niveau toujours protégé (voir [Niveaux du Route Guard](../security/ROUTE_GUARD_TIERS.md)) et des appels qui délivrent un identifiant accepté par celui-ci. Ces appels exigent le même identifiant qu'avec la connexion activée : émettre des jetons de synchronisation, créer des jetons d'accès CLI de n'importe quelle portée, créer une clé d'API de portée `manage`/`admin`, accorder cette portée à une clé, ou régénérer ou révéler une telle clé (`requireCredentialForManagementScopedKey()` dans `src/lib/api/requireManagementAuth.ts`). Les clés réservées à l'inférence restent ouvertes.
- Aucun mot de passe configuré **et** aucune variable d'environnement `INITIAL_PASSWORD` → le mode d'amorçage autorise l'assistant d'onboarding et les requêtes loopback, mais les requêtes réseau exposées exigent toujours des identifiants.
- Toute erreur de base de données → échec fermé (sécurisé par défaut).

L'application des clés d'API client utilise `isRequireApiKeyEnabled()` dans `src/shared/utils/featureFlags.ts`, et non une lecture directe de `process.env.REQUIRE_API_KEY`. Cela compte pour les instances déployées : activer ou désactiver `REQUIRE_API_KEY` dans Dashboard → Feature Flags enregistre une surcharge en base et affecte immédiatement `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` et les autres vérifications d'authentification de l'API client qui partagent ce helper. Si le magasin des feature flags ne peut pas être lu, l'authentification de l'API client échoue en mode fermé et exige une clé.

## Changement incompatible — v3.8.0

Les points de terminaison `/api/v1/agents/tasks/*` et `/api/resilience/model-cooldowns` **nécessitent désormais une authentification de gestion** (commit `588a0333`). Les clients qui envoyaient auparavant une clé d’API normale sans la portée `manage` reçoivent une réponse `403`. Migration : attribuez la portée `manage` à la clé dans le tableau de bord API Keys, ou utilisez une session de tableau de bord authentifiée.

## Changement de comportement — v3.8.2

`/api/mcp/*` (le serveur MCP distant) reste LOCAL_ONLY par défaut, mais accepte désormais les requêtes ne provenant pas de la boucle locale lorsque l’en-tête `Authorization: Bearer <api-key>` comporte la portée `manage`. Cette exception est explicitement contrôlée pour chaque chemin via `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` dans `src/server/authz/routeGuard.ts` ; le préfixe LOCAL_ONLY apparenté `/api/cli-tools/runtime/*` ne peut intentionnellement PAS être contourné, car il peut lancer des sous-processus arbitraires. Les requêtes anonymes vers `/api/mcp/*` ne provenant pas de la boucle locale continuent de renvoyer `403 LOCAL_ONLY` — le comportement par défaut de tout nouveau chemin LOCAL_ONLY reste limité strictement à la boucle locale. Voir [Niveaux de protection des routes](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Tests

- Tests unitaires : `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Liste d’autorisation publique : `tests/unit/public-api-routes.test.ts`.
- Exécution ciblée : `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Débogage

Le pipeline marque toujours les réponses avec :

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Pour les requêtes authentifiées, les en-têtes de requête en amont (côté gestionnaire) incluent également :

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Utilisez `assertAuth(req, expectedClass)` dans les gestionnaires — il lance `AuthzAssertionError` avec le code `AUTHZ_NOT_INITIALIZED` si le middleware a été contourné (utile pour détecter les régressions de configuration dans les tests).

## Voir aussi

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — marqueur d'authentification par point d'accès
- [COMPLIANCE.md](../security/COMPLIANCE.md) — journal d'audit pour les événements d'authentification
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — trois espaces de noms de portée et catalogue de portée d'outil MCP
- Source : `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
