# Authorization Guide (Ελληνικά)

🌐 **Languages:** 🇺🇸 [English](../../../../architecture/AUTHZ_GUIDE.md) · 🇪🇹 [am](../../../am/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇦 [ar](../../../ar/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇿 [az](../../../az/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇬 [bg](../../../bg/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇩 [bn](../../../bn/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇦 [bs](../../../bs/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇿 [cs](../../../cs/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇰 [da](../../../da/docs/architecture/AUTHZ_GUIDE.md) · 🇩🇪 [de](../../../de/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇸 [es](../../../es/docs/architecture/AUTHZ_GUIDE.md) · 🇪🇪 [et](../../../et/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇷 [fa](../../../fa/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇮 [fi](../../../fi/docs/architecture/AUTHZ_GUIDE.md) · 🇫🇷 [fr](../../../fr/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇪 [ga](../../../ga/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [gu](../../../gu/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ha](../../../ha/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇱 [he](../../../he/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [hi](../../../hi/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇷 [hr](../../../hr/docs/architecture/AUTHZ_GUIDE.md) · 🇭🇺 [hu](../../../hu/docs/architecture/AUTHZ_GUIDE.md) · 🇦🇲 [hy](../../../hy/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇩 [id](../../../id/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [ig](../../../ig/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇹 [it](../../../it/docs/architecture/AUTHZ_GUIDE.md) · 🇯🇵 [ja](../../../ja/docs/architecture/AUTHZ_GUIDE.md) · 🇬🇪 [ka](../../../ka/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇭 [km](../../../km/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [kn](../../../kn/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇷 [ko](../../../ko/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇹 [lt](../../../lt/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇻 [lv](../../../lv/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ml](../../../ml/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [mr](../../../mr/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇾 [ms](../../../ms/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇹 [mt](../../../mt/docs/architecture/AUTHZ_GUIDE.md) · 🇲🇲 [my](../../../my/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇵 [ne](../../../ne/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇱 [nl](../../../nl/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇴 [no](../../../no/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [or](../../../or/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [pa](../../../pa/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇭 [phi](../../../phi/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇱 [pl](../../../pl/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇹 [pt](../../../pt/docs/architecture/AUTHZ_GUIDE.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇴 [ro](../../../ro/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇺 [ru](../../../ru/docs/architecture/AUTHZ_GUIDE.md) · 🇱🇰 [si](../../../si/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇰 [sk](../../../sk/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇮 [sl](../../../sl/docs/architecture/AUTHZ_GUIDE.md) · 🇷🇸 [sr](../../../sr/docs/architecture/AUTHZ_GUIDE.md) · 🇸🇪 [sv](../../../sv/docs/architecture/AUTHZ_GUIDE.md) · 🇰🇪 [sw](../../../sw/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [ta](../../../ta/docs/architecture/AUTHZ_GUIDE.md) · 🇮🇳 [te](../../../te/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇭 [th](../../../th/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇷 [tr](../../../tr/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇦 [uk-UA](../../../uk-UA/docs/architecture/AUTHZ_GUIDE.md) · 🇵🇰 [ur](../../../ur/docs/architecture/AUTHZ_GUIDE.md) · 🇺🇿 [uz](../../../uz/docs/architecture/AUTHZ_GUIDE.md) · 🇻🇳 [vi](../../../vi/docs/architecture/AUTHZ_GUIDE.md) · 🇳🇬 [yo](../../../yo/docs/architecture/AUTHZ_GUIDE.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/architecture/AUTHZ_GUIDE.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/architecture/AUTHZ_GUIDE.md)

---

> **Πηγή αλήθειας:** `src/server/authz/`, `src/shared/constants/publicApiRoutes.ts`, `src/lib/api/requireManagementAuth.ts`, `src/shared/utils/apiAuth.ts`
> **Τελευταία ενημέρωση:** 2026-09-22 — οι χώροι ονομάτων εμβέλειας παραπέμπουν στο MCP-SERVER.md

Το OmniRoute διαθέτει μια διοχέτευση εξουσιοδότησης με επίγνωση διαδρομών, η οποία ελέγχει κάθε αίτημα API. Η ταξινόμηση είναι **ντετερμινιστική** και **fail-closed** — οτιδήποτε δεν μπορεί να ταξινομηθεί καταλήγει ως `MANAGEMENT` και απαιτεί συνεδρία ή διακριτικό επιπέδου διαχείρισης. Αυτή η σελίδα εξηγεί το μοντέλο για μηχανικούς που συντηρούν διαδρομές ή σχεδιάζουν νέα τελικά σημεία.

![Διοχέτευση AuthZ (3 κλάσεις διαδρομών + αξιολόγηση πολιτικής)](../diagrams/exported/authz-pipeline.svg)

> Πηγή: [diagrams/authz-pipeline.mmd](../diagrams/authz-pipeline.mmd)

## Δύο λειτουργίες Auth

### 1. Κλειδί API (Φορέας)

Χρησιμοποιείται για τον πελάτη OpenAI/Anthropic/Gemini-compatible APIs και μερικές διαδρομές διαχείρισης όταν το κλειδί έχει το εύρος `manage`.

```
Authorization: Bearer <api-key>
```

Επικυρώθηκε από `isValidApiKey()` / `extractApiKey()` σε `src/sse/services/auth.ts` και επανεξάχθηκε μέσω `src/shared/utils/apiAuth.ts`. Ο επικυρωτής δέχεται επίσης τα `OMNIROUTE_API_KEY` / `ROUTER_API_KEY` env vars ως μόνιμα κλειδιά διέλευσης (έκδοση #1350).

### 2. Συνεδρία πίνακα ελέγχου (cookie auth_token)

Για σελίδες πίνακα ελέγχου και λειτουργίες διαχειριστή.

```
Cookie: auth_token=<JWT signed with JWT_SECRET>
```

Ένα cookie είναι μια περίοδος λειτουργίας μόνο όταν το JWT επαληθεύει** και** φέρει `authenticated: true` (`src/shared/utils/dashboardSessionToken.ts` → `verifyDashboardSessionToken`). Κάθε καταναλωτής του cookie (προφύλαξη διαδρομής πίνακα οργάνων (`isDashboardSessionAuthenticated()`), ανανέωση αγωγού authz, χειραψία WebSocket, ζωντανός διακομιστής, `/api/settings/require-login`, `/api/auth/status`) περνά από αυτόν τον βοηθό. Άλλα JWTs υπογεγραμμένα με `JWT_SECRET` υπάρχουν — η διέλευση Cursor CLI νομίζει `iss "omniroute" / aud "cursor-cli"` tokens για κατόχους κλειδιών — και δεν είναι ποτέ περίοδοι σύνδεσης (#13298).

Επαληθεύτηκε από `isDashboardSessionAuthenticated()` στο `src/shared/utils/apiAuth.ts`. Ο αγωγός ανανεώνει αυτόματα το JWT όταν του απομένουν λιγότερες από 7 ημέρες στη διάρκεια ζωής του 30 ημερών.

Μια περίοδος σύνδεσης μπορεί επίσης να τελειώσει πριν από τη λήξη των 30 ημερών της, επειδή κάθε minter περνάει από `mintDashboardSessionToken` (έναν χρόνο έκδοσης `iat` και ένα id `jti`) και ο επαληθευτής ελέγχει δύο ρυθμίσεις: `sessionsValidAfter`, που ορίζεται από μια αλλαγή κωδικού πρόσβασης, ώστε κάθε περίοδος λειτουργίας να εκδίδεται πριν σταματήσει η επαλήθευση (το πρόγραμμα περιήγησης που άλλαξε τον κωδικό πρόσβασης λαμβάνει ένα νέο cookie) και `revokedDashboardSessions`, στην οποία `POST /api/auth/logout` -out προσθέτει την περίοδο `jti`. Οι περίοδοι σύνδεσης που κόπηκαν από μια παλαιότερη έκδοση δεν έχουν καμία αξίωση και παραμένουν έγκυρες μέχρι την πρώτη αλλαγή κωδικού πρόσβασης. Εάν δεν είναι δυνατή η ανάγνωση των ρυθμίσεων, η συνεδρία δεν είναι αξιόπιστη.

Ορισμένες διαδρομές διαχείρισης δέχονται** είτε** λειτουργία: cookie OR `Bearer <key>` όταν το κλειδί API έχει το εύρος `manage` (ή `admin`). Αυτό είναι που επιτρέπει τη ροή εργασίας "με δυνατότητα διαμόρφωσης μέσω κλήσεων API " που προστέθηκε στην έκδοση 3.8.

#### Προαιρετική πύλη σύνδεσης OIDC (#6973)

Η σύνδεση διαχειριστή του πίνακα ελέγχου υποστηρίζει επίσης ένα** συμμετοχή** Η ροή OIDC (OpenID Connect) παράλληλα με τον προεπιλεγμένο κωδικό πρόσβασης σύνδεσης Η σύνδεση με κωδικό πρόσβασης — δεν αφαιρείται ποτέ, αλλά συμπληρώνεται:

- Απενεργοποιημένο εκτός εάν `settings.oidcEnabled === true`** και** `oidcIssuer` / `oidcClientId` / `oidcClientSecret` έχουν ρυθμιστεί όλα (Ρυθμίσεις → Auth). `GET /api/auth/oidc/login` επιστρέφει `400` διαφορετικά.
- Το `GET /api/auth/oidc/login` ανακαλύπτει το `authorization_endpoint` από το `/.well-known/openid-configuration` του εκδότη (επιστρέφει στο `<issuer>/authorize`), δημιουργεί την ανακατεύθυνση URI από το εισερχόμενο αίτημα (`x-forwarded-proto` -aware) και ανακατευθύνει στο IdP με ένα τυχαίο `state` που είναι αποθηκευμένο σε ένα cookie `httpOnly` `oidc_state`.
- `GET /api/auth/oidc/callback` επικυρώνει `state`, ανταλλάσσει τον κωδικό εξουσιοδότησης και επαληθεύει την υπογραφή του διακριτικού ID μέσω του JWKS του εκδότη (`jose`'s `createRemoteJWKSet`, προσωρινά αποθηκευμένο ανά JWKS URI) με επιταγές `issuer`/`audience`. Η είσοδος στον πίνακα ελέγχου απαιτεί μια μη κενή λίστα `oidcAllowedSubjects`, μια πολιτική `oidcAdmissionClaim` ή και τα δύο. Η λίστα θεμάτων ταιριάζει `sub` ή `email` μόνο όταν `email_verified === true`. Η προαιρετική πολιτική αξίωσης παίρνει μια διαδρομή αξίωσης διακριτικού αναγνωριστικού διαχωρισμένη με κουκκίδες (για παράδειγμα, `realm_access.roles`) και μια σειρά αποδεκτών τιμών. η επιλυθείσα αξίωση πρέπει να είναι ένας πίνακας συμβολοσειρών που περιέχει τουλάχιστον μία αποδεκτή τιμή. Εάν έχουν ρυθμιστεί και οι δύο πολιτικές, πρέπει να περάσουν και οι δύο. Οι αξιώσεις Missing/malformed αποτυγχάνουν να κλείσουν και χωρίς καμία από τις δύο πολιτικές, η επανάκληση αρνείται τη σύνδεση (`not_configured`). Οι υπάρχουσες διαμορφώσεις μόνο για θέματα συνεχίζουν να παραμένουν αμετάβλητες.
- Το Keycloak συνήθως αντιστοιχίζει τους ρόλους του βασίλειου σε διακριτικά πρόσβασης, όχι απαραίτητα σε διακριτικά ID. Για να απαιτήσετε τον ρόλο σφαίρας `admin`, διαμορφώστε έναν αντιστοιχιστή πρωτοκόλλου για αυτόν τον πελάτη που περιλαμβάνει `realm_access.roles` στο**ID token** και μετά ορίστε `oidcAdmissionClaim` σε `{ "path": "realm_access.roles", "values": ["admin"] }`. Ελέγξτε την πραγματική αξίωση αναγνωριστικού αναγνωριστικού για αυτόν τον πελάτη πριν ενεργοποιήσετε την αποδοχή μόνο για ρόλους. η εφαρμογή δεν διαβάζει ρόλους με διακριτικό πρόσβασης. Η άρνηση διακριτικού από την πλευρά IdP μπορεί να συμπληρώσει, αλλά δεν αντικαθιστά αυτόν τον έλεγχο από την πλευρά της εφαρμογής.
- Στην επιτυχία σημαδεύει το** ακριβώς το ίδιο** `auth_token` JWT 30 ημερών προβλήματα σύνδεσης με τον κωδικό πρόσβασης (`src/app/api/auth/login/route.ts`), επομένως η υπόλοιπη διοχέτευση της περιόδου λειτουργίας του πίνακα εργαλείων (αυτόματη ανανέωση, σημαίες cookie) παραμένει αμετάβλητη. — OIDC αντικαθιστά μόνο τον τρόπο κοπής του cookie, όχι αυτό που χορηγεί. Οι αλλαγές στο IdP roles/groups δεν ακυρώνουν τις υπάρχουσες περιόδους σύνδεσης OmniRoute. η αποσύνδεση, η εναλλαγή κωδικού πρόσβασης ή η λήξη της περιόδου λειτουργίας εξακολουθούν να διέπουν τη διάρκεια ζωής τους.
- Κάθε ρύθμιση `oidc*` (`oidcEnabled`, `oidcDisablePasswordLogin`, `oidcIssuer`, `oidcClientId`, `oidcClientSecret`, `oidcAllowedSubjects`, `oidcAdmissionClaim`, `oidcRedirectPath`, `oidcScopes`) είναι σε `SECURITY_IMPACTING_SETTINGS_KEYS` (`src/shared/constants/securityImpactingSettings.ts`): `PATCH /api/settings` απαντά `400 PASSWORD_REQUIRED` εκτός εάν το σώμα φέρει τον κωδικό πρόσβασης διαχείρισης ως `currentPassword` (`401 PASSWORD_MISMATCH` όταν είναι λάθος). `oidcDisablePasswordLogin` αρνείται τον κωδικό πρόσβασης _login_ (`POST /api/auth/login`) αλλά διατηρεί τον αποθηκευμένο κατακερματισμό του κωδικού πρόσβασης και η επανεξέταση εξακολουθεί να ελέγχει `currentPassword` έναντι αυτού.
- `corsOrigins` και `bruteForceProtection` είναι επίσης στο `SECURITY_IMPACTING_SETTINGS_KEYS` : η χαλάρωση είτε αποδυναμώνει τις άμυνες σύνδεσης, οπότε παίρνουν την ίδια επανεξέταση `currentPassword` (το ζητά η καρτέλα Security) και η εισαγωγή JSON τα απορρίπτει.
- Κάθε κλειδί πολιτικής ασφαλείας — οι καταχωρήσεις `SECURITY_IMPACTING_SETTINGS_KEYS`, κάθε κλειδί `oidc*` και η κατάσταση περιόδου λειτουργίας πίνακα εργαλείων — είναι** μόνο για χειριστή** στο `PATCH /api/settings`: ένα κλειδί API με διαχείριση εύρους ή ένα διακριτικό πρόσβασης `oma_` απορρίπτεται με `403` ακόμα και όταν στέλνει το σωστό `currentPassword` και η άρνηση ελέγχεται ως `settings.update_failed` με `reason: OPERATOR_REQUIRED` (`requireOperatorCredential()` σε `src/lib/api/operatorCredential.ts`). Οι συνηθισμένες ρυθμίσεις (θέμα, προτιμήσεις οθόνης) παραμένουν εγγράψιμες για ένα κλειδί `manage` ή ένα διακριτικό πρόσβασης `admin`. Κάθε μετάλλαξη του ίδιου του `/api/settings` (και του `/api/settings/require-login`) χρειάζεται επίσης το εύρος διακριτικού πρόσβασης `admin` (`ADMIN_MUTATION_EXACT_PATHS` σε `src/server/authz/accessScopes.ts`, ακριβής αντιστοίχιση διαδρομής). `GET` παραμένει `read` και οι άλλες δευτερεύουσες διαδρομές `/api/settings/*` (διακομιστές μεσολάβησης, προεπιλογές συνδυασμού, ψευδώνυμα μοντέλων, συμπίεση, εκκαθαρίσεις…) διατηρούν το εύρος `write` που προκύπτει από τη μέθοδο.
- `POST /api/settings/import-json` παραλείπει την επανεξέταση, επομένως ρίχνει κάθε κλειδί στο `IMPORT_STRIPPED_SETTINGS_KEYS` (ίδιο αρχείο) πριν γράψει: τον κωδικό πρόσβασης και `currentPassword`, κάθε καταχώρηση `SECURITY_IMPACTING_SETTINGS_KEYS` και την κατάσταση περιόδου λειτουργίας του πίνακα εργαλείων (`sessionsValidAfter`, `revokedDashboardSessions`). Επομένως, η εισαγωγή ενός παλαιότερου αντιγράφου ασφαλείας δεν μπορεί να αναβιώσει μια περίοδο λειτουργίας όπου μια αλλαγή κωδικού πρόσβασης ή μια αποσύνδεση έχει ήδη τελειώσει.

#### Προαιρετική σύνδεση δύο παραγόντων TOTP (#16619)

Εγγράφηκε από τις Ρυθμίσεις → Security. απενεργοποιείται μέχρι να το ενεργοποιήσει ο χειριστής (`src/server/auth/dashboardMfa.ts`).

- **Τι καλύπτει:** κωδικός σύνδεσης (`POST /api/auth/login`, που στη συνέχεια χρειάζεται `POST /api/auth/mfa/verify`) και `omniroute connect` (`POST /api/cli/connect`, που αρνείται την ανταλλαγή μόνο με κωδικό πρόσβασης και παίρνει τον κωδικό ως `totp`).
- **Τι δεν καλύπτει:** Η είσοδος OIDC / SSO (`/api/auth/oidc/callback`) δεν ζητά το OmniRoute TOTP. Βασίζεται στον δεύτερο παράγοντα του ίδιου του παρόχου ταυτότητας, επομένως επιβάλετε MFA στο IdP εάν OIDC είναι ενεργοποιημένο.
- **Ανάκτηση** (χαμένη συσκευή, δεν έχουν απομείνει κωδικοί ανάκτησης ή ένας παράγοντας που δεν μπορεί πλέον να επαληθευτεί, για παράδειγμα μετά την αλλαγή `STORAGE_ENCRYPTION_KEY` ):
  1. Κάντε επανεκκίνηση του διακομιστή με `OMNIROUTE_DISABLE_MFA=true`.
  2. Στον ίδιο τον κεντρικό υπολογιστή (loopback peer και loopback `Host`, όπως `http://localhost:20128`), συνδεθείτε με τον κωδικό πρόσβασης. Ο δεύτερος παράγοντας παραλείπεται μόνο για αυτήν την προέλευση. κάθε άλλη προέλευση χρειάζεται ακόμα τον κωδικό.
  3. Στις Ρυθμίσεις → Security → Απενεργοποίηση, πληκτρολογήστε τον κωδικό πρόσβασης και αφήστε τον κωδικό κενό. `POST /api/auth/mfa/disable` δέχεται σώμα χωρίς `code` μόνο όταν η μεταβλητή έχει οριστεί και το αίτημα προέρχεται από τον κεντρικό υπολογιστή. εξακολουθεί να απαιτεί τη συνεδρία του πίνακα εργαλείων και τον τρέχοντα κωδικό πρόσβασης και ελέγχεται ως `auth.mfa.disabled` με `secondFactor: "recovery_switch"`.
  4. Καταργήστε τη ρύθμιση `OMNIROUTE_DISABLE_MFA`, κάντε επανεκκίνηση και εγγραφείτε ξανά εάν χρειάζεται.

## Κλάσεις διαδρομών

Το `src/server/authz/types.ts` ορίζει τρεις κλάσεις· κάθε διαδρομή που δεν μπορεί να ταξινομηθεί με βεβαιότητα επιστρέφει στην `MANAGEMENT`.

| Κλάση        | Περιγραφή                                                                                                                                                              | Απαιτούμενη αυθεντικοποίηση                                            |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `PUBLIC`     | Ρητά ασφαλείς διαδρομές — σύνδεση, αποσύνδεση, κατάσταση, αρχικοποίηση, υγεία, bootstrap του onboarding.                                                               | Καμία                                                                  |
| `CLIENT_API` | Endpoints εξυπηρέτησης μοντέλων — `/api/v1/*`, `/api/v1beta/*`, καθώς και τα ψευδώνυμα `/v1/*`, `/v1beta/*`, `/chat/completions`, `/responses`, `/models`, `/codex/*`. | Κλειδί Bearer όταν είναι ενεργή η σημαία λειτουργίας `REQUIRE_API_KEY` |
| `MANAGEMENT` | Σελίδες πίνακα ελέγχου, ρυθμίσεις, providers, κλειδιά, endpoints διαχειριστή και διαγνωστικών.                                                                         | Συνεδρία πίνακα ελέγχου Ή Bearer με scope `manage`                     |

Ορισμένες ενέργειες της `MANAGEMENT` είναι **μόνο για τον διαχειριστή**: ένα κλειδί `manage` δεν αρκεί. Η εξαγωγή αποθηκευμένων διαπιστευτηρίων (`GET /api/settings/export-json`, `GET /api/db-backups/export`, `GET /api/db-backups/exportAll`), η επαναφορά αντιγράφου πάνω στα ζωντανά δεδομένα (`POST /api/db-backups/import`, συμπεριλαμβανομένου του `dryRun=true`, `POST /api/db-backups` επαναφορά με βάση το id, `POST /api/settings/import-json`), η καταστροφή σημείων επαναφοράς (`DELETE /api/db-backups` για καθαρισμό και `PATCH /api/db-backups`, επειδή η διατήρηση που αποθηκεύει οδηγεί την αυτόματη διαγραφή μετά από κάθε αντίγραφο) απαιτούν συνεδρία πίνακα ελέγχου, το τοπικό υποκείμενο CLI ή απενεργοποιημένη σύνδεση. Η έκδοση ενός token συγχρονισμού (`POST /api/sync/tokens`) και η δημιουργία token πρόσβασης CLI με `admin` (`POST /api/cli/tokens`) απαιτούν συνεδρία πίνακα ελέγχου ή το τοπικό υποκείμενο CLI σε κάθε λειτουργία σύνδεσης. Τα κλειδιά API όλων των scopes και τα tokens πρόσβασης `oma_` δεν είναι διαπιστευτήρια διαχειριστή: λαμβάνουν `403` όποτε απαιτείται ένα τέτοιο. Ο έλεγχος βρίσκεται στο `src/lib/api/operatorCredential.ts` (`resolveOperatorCredential()` / `requireOperatorCredential()`). Η αλλαγή των ρυθμίσεων σύνδεσης είναι επίσης μόνο για τον διαχειριστή: το `POST /api/settings/require-login` (ορισμός του κωδικού διαχείρισης / εναλλαγή του `requireLogin`) δέχεται μόνο αυτά τα διαπιστευτήρια αφού υπάρξει κωδικός — το παράθυρο της αρχικής ρύθμισης (όταν δεν υπάρχει ακόμη κωδικός) παραμένει ως έχει — και μια συνεδρία πίνακα ελέγχου πρέπει να στείλει `currentPassword` για να αντικαταστήσει τον κωδικό (`403` όταν λείπει ή είναι λάθος, με καταγραφή ως `settings.update_failed`). Το τοπικό CLI και μια εγκατάσταση με απενεργοποιημένη σύνδεση διατηρούν τη διαδρομή ανάκτησης και μπορούν να ορίσουν κωδικό χωρίς αυτόν, αφού και τα δύο είναι δεσμευμένα στον υπολογιστή που κατέχει τον κατάλογο δεδομένων.

## Γραμμή σωλήνων

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

Οι αξιόπιστες εσωτερικές κεφαλίδες (που ορίζονται στο `src/server/authz/headers.ts`) είναι** απογυμνωθεί από εισερχόμενα αιτήματα** πριν από την ταξινόμηση, οι πελάτες — δεν μπορούν να συμπληρώσουν εκ των προτέρων `x-omniroute-auth-*` για να μιμηθούν ένα θέμα.

### Συμβάσεις πολιτικής

Κάθε κατηγορία διαδρομής έχει μια πολιτική στο `src/server/authz/policies/`:

- **`publicPolicy`** (`policies/public.ts`) — επιστρέφει πάντα `allow({ kind: "anonymous", id: "anonymous" })`.
- **`clientApiPolicy`** (`policies/clientApi.ts`) — αποσπάσματα Bearer, επικυρώνει μέσω `validateApiKey()`. Πέφτει σε ανώνυμη μόνο όταν η ενεργή σημαία χαρακτηριστικών `REQUIRE_API_KEY` είναι απενεργοποιημένη. Η αποτελεσματική επισήμανση επιλύεται μέσω `isRequireApiKeyEnabled()` (`DB feature flag override > process.env.REQUIRE_API_KEY > default`), επομένως οι σημαίες χαρακτηριστικών του πίνακα ελέγχου και οι μεταβλητές περιβάλλοντος διέπουν με συνέπεια `/api/v1/*`, `/api/v1beta/*` και ψευδώνυμα. οι αποτυχίες του επιλύτη αποτυγχάνουν να κλείσουν. Επιτρέπει αιτήματα συνεδρίας πίνακα εργαλείων σε διαδρομές πελάτη API (συμπεριλαμβανομένου του `/api/v1/models`, που χρησιμοποιείται από τον κατάλογο μοντέλων του πίνακα εργαλείων). Όταν το Entra ID SSO είναι ενεργοποιημένο, ένας φορέας που είναι δομικά ένα διακριτικό Entra (τρία τμήματα base64url, `RS*` alg, `kid`) αντιμετωπίζεται από τον κλάδο SSO** προτού** `validateApiKey()` και η ετυμηγορία του είναι οριστική — δεν περνά ποτέ στη διαδρομή κλειδιού API ή στον κλάδο υποβάθμισης σε ανώνυμο, επομένως μια διακοπή παροχής ταυτότητας δεν μπορεί να γίνει ανοιχτή πρόσβαση. Τα στατικά κλειδιά API δεν επηρεάζονται. Δείτε [Entra ID SSO](../security/ENTRA_SSO.md).
- **`managementPolicy`** (`policies/management.ts`) — αποδέχεται περίοδο λειτουργίας πίνακα εργαλείων, εσωτερικά αιτήματα συγχρονισμού μοντέλου (αντιστοιχίζονται σε `/api/providers/[name]/(sync-models|models)`) ή παρακάμπτει εντελώς εάν `isAuthRequired()` επιστρέψει false. Επιστρέφει 403 (`AUTH_001`) όταν υπάρχει ένα διακριτικό φορέα αλλά δεν είναι έγκυρο, 401 διαφορετικά. Επίσης, επιβάλλει τις βαθμίδες προστασίας διαδρομής (LOCAL_ONLY / ALWAYS_PROTECTED) πριν από οποιοδήποτε κλάδο εξουσιοδότησης — ανατρέξτε στο [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md). Τα μονοπάτια LOCAL_ONLY στο `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` (σήμερα: `/api/mcp/`) μπορούν να προσπελαστούν από non-loopback όταν το κλειδί Bearer φέρει το εύρος `manage`. όλα τα άλλα μονοπάτια LOCAL_ONLY παραμένουν αυστηρά-loopback ανεξάρτητα από το εύρος.

Μια επιτυχημένη πολιτική επιστρέφει `AuthSubject` με `kind ∈ { client_api_key, dashboard_session, management_key, anonymous, sso_user }`. Οι μεταγενέστεροι χειριστές μπορούν να το διαβάσουν μέσω `assertAuth(request, "CLIENT_API")` σε `src/server/authz/assertAuth.ts` αντί να εκτελούν ξανά τη λογική εξουσιοδότησης.

## Λίστα Δημόσιων Διαδρομών

`src/shared/constants/publicApiRoutes.ts` είναι η ρητή λίστα επιτρεπόμενων:

Η λίστα χωρίζεται κατά** σχήμα** , και η διάσπαση είναι φέρουσα (GHSA-74g9-q8f6-793h): ένα πρόθεμα αντιστοιχίζεται με `startsWith()`, επομένως ταιριάζει επίσης με κάθε γειτονικό μονοπάτι που μοιράζεται τους κύριους χαρακτήρες του. `/api/usage/om-usage` ως πρόθεμα σημείωσε `/api/usage/om-usage<anything>` PUBLIC και το Next επιλύει ότι για να `/api/usage/[connectionId]` — ένα πρόγραμμα χειρισμού χωρίς δική του ταυτότητα.

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

Οι διαδρομές μόνο για ανάγνωση είναι δημόσιες** μόνο** για ασφαλείς μεθόδους. Σημείωση: `classifyRoute()` εξαιρεί `/api/v1/*` και `/api/v1beta/*` από το PUBLIC fall-through — αυτά είναι πάντα `CLIENT_API` επομένως η πολιτική Bearer-key εξακολουθεί να ισχύει.

## Προσθήκη νέας διαδρομής

### Μοτίβο 1 — Δημόσιο τελικό σημείο API πελάτη (ταυτοποίηση Bearer)

Οι διαδρομές κάτω από τα `/api/v1/` και `/api/v1beta/` ταξινομούνται αυτόματα ως `CLIENT_API`. Το middleware επιβάλλει τον έλεγχο Bearer· οι χειριστές διαδρομών δεν χρειάζεται να τον επαναλάβουν, αλλά μπορούν να διαβάσουν το υποκείμενο εάν αυτό είναι χρήσιμο.

```typescript
// src/app/api/v1/your-route/route.ts
import { NextRequest, NextResponse } from "next/server";
import { assertAuth } from "@/server/authz/assertAuth";

export async function POST(req: NextRequest) {
  const subject = assertAuth(req, "CLIENT_API");
  // subject.kind === "client_api_key" | "anonymous" | "dashboard_session"
  // ... λογική χειριστή
}
```

### Μοτίβο 2 — Τελικό σημείο διαχείρισης (συνεδρία ή Bearer + manage)

Χρησιμοποιήστε τη `requireManagementAuth()` από το `src/lib/api/requireManagementAuth.ts`:

```typescript
import { requireManagementAuth } from "@/lib/api/requireManagementAuth";

export async function POST(request: Request) {
  const rejection = await requireManagementAuth(request);
  if (rejection) return rejection;
  // ... λογική χειριστή
}
```

Η `requireManagementAuth()` επιστρέφει `null` σε περίπτωση επιτυχίας ή ένα σφάλμα JSON τύπου `Response`:

- 401 `AUTH_001` "Απαιτείται ταυτοποίηση" — δεν υπάρχουν καθόλου διαπιστευτήρια
- 403 — μη έγκυρο Bearer **ή** υπάρχει Bearer, αλλά το κλειδί δεν διαθέτει το πεδίο εφαρμογής `manage` / `admin`

Η `hasManageScope(scopes)` επιστρέφει true για `"manage"` ή `"admin"`.

### Μοτίβο 3 — Προσθήκη στη δημόσια λίστα επιτρεπόμενων διαδρομών

Επιλέξτε το σύνολο βάσει μορφής και όχι βάσει ευκολίας. Μία διαδρομή τοποθετείται στο `PUBLIC_API_ROUTES_EXACT` (ή στο `PUBLIC_READONLY_CORS_API_ROUTES` αν είναι μόνο για GET)· μόνο ένα πραγματικό υποδέντρο τοποθετείται στο `PUBLIC_API_ROUTE_PREFIXES` και **πρέπει να τελειώνει σε `/`**. Η τοποθέτηση μιας μεμονωμένης διαδρομής στη λίστα προθεμάτων δημοσιοποιεί επίσης κάθε γειτονική διαδρομή που έχει τους ίδιους αρχικούς χαρακτήρες — συμπεριλαμβανομένων συγγενικών διαδρομών με δυναμικά τμήματα που θα προστεθούν αργότερα (GHSA-74g9-q8f6-793h). Ενημερώστε τις δοκιμές μονάδας στα `tests/unit/public-api-routes.test.ts`, `tests/unit/authz/public-route-exact-match.test.ts` και `tests/unit/authz/classify.test.ts`.

## Εμβέλειες

Τρεις χώροι ονομάτων. Κάθε ελεγκτής διαβάζει μόνο τις δικές του συμβολοσειρές. Η παράθεση,
συμπεριλαμβανομένου του γιατί το `manage` αποτυγχάνει στο `scopeMatches` για το `read:compression` και γιατί ένα
διακριτικό πρόσβασης `read` δεν μπορεί να εκτελέσει `PATCH /api/keys/{id}`, βρίσκεται στην ενότητα
[Τρεις χώροι ονομάτων εμβέλειας](../frameworks/MCP-SERVER.md#three-scope-namespaces).

Τα κλειδιά API περιλαμβάνουν έναν πίνακα `scopes` (αποθηκευμένο ως JSON στο `api_keys.scopes`, βλ. `src/lib/db/apiKeys.ts`).

### Εμβέλεια διαχείρισης

- `manage` / `admin` — `hasManageScope`. Πρόσβαση Bearer στις διαδρομές API διαχείρισης.
- Τα `mcp:connect`, `self:usage`, `self:account-quota` και
  `policy:bypass-provider-quota` είναι προσθετικές εμβέλειες ακριβούς αντιστοίχισης. Βρίσκονται
  εκτός του `MANAGEMENT_API_KEY_SCOPES`. Το `mcp:connect` ανοίγει μόνο την
  εξαίρεση μη loopback για το `/api/mcp/`.

### Εμβέλειες εργαλείων MCP

Κατάλογος και κανόνες αντιστοίχισης (πανομοιότυπη συμβολοσειρά ή μια εκχωρημένη εμβέλεια που λήγει σε `*`):
[Εμβέλειες εργαλείων MCP](../frameworks/MCP-SERVER.md#mcp-tool-scopes).
Το `MCP_SCOPE_LIST` στο `src/shared/constants/mcpScopes.ts` είναι το αρχικό υποσύνολο με τύπους,
όχι ο πλήρης κατάλογος. Η επιβολή εκτελείται στο
`open-sse/mcp-server/scopeEnforcement.ts` αφού το `resolveCallerScopeContext()`
επιλύσει τις εμβέλειες από τις πληροφορίες ελέγχου ταυτότητας MCP, τα μεταδεδομένα αιτήματος ή το `OMNIROUTE_MCP_SCOPES`.
Παραμένει απενεργοποιημένη εκτός εάν έχει οριστεί `OMNIROUTE_MCP_ENFORCE_SCOPES=true`.

### Εμβέλειες διακριτικών πρόσβασης

`read` / `write` / `admin` σε διακριτικά `oma_live_…`, ταξινομημένα βάσει του `scopeSatisfies`
(`src/lib/accessTokens/scopes.ts`). Αυτή η κατάταξη εφαρμόζεται μόνο στο διαπιστευτήριο διακριτικού πρόσβασης.
Βλ. [Έλεγχος ταυτότητας διαχείρισης](../guides/MANAGEMENT-AUTH.md).

## Εναλλαγή απαίτησης αυθεντικοποίησης

Η `isAuthRequired()` στο `src/shared/utils/apiAuth.ts` αποφασίζει αν επιβάλλεται **οποιαδήποτε** αυθεντικοποίηση σε ένα αίτημα:

- `settings.requireLogin === false` → η αυθεντικοποίηση είναι καθολικά απενεργοποιημένη, εκτός από το πάντα προστατευμένο επίπεδο (βλ. [Route Guard Tiers](../security/ROUTE_GUARD_TIERS.md)) και τις κλήσεις που χορηγούν ένα διαπιστευτήριο που αυτή αποδέχεται. Αυτές απαιτούν το ίδιο διαπιστευτήριο όπως με ενεργή σύνδεση: έκδοση tokens συγχρονισμού, δημιουργία tokens πρόσβασης CLI σε οποιοδήποτε scope, και δημιουργία κλειδιού API με scope `manage`/`admin`, χορήγηση αυτού του scope σε κλειδί, ή αναδημιουργία ή αποκάλυψη τέτοιου κλειδιού (`requireCredentialForManagementScopedKey()` στο `src/lib/api/requireManagementAuth.ts`). Τα κλειδιά μόνο για inference παραμένουν ανοιχτά.
- Δεν υπάρχει ρυθμισμένος κωδικός **και** δεν υπάρχει μεταβλητή περιβάλλοντος `INITIAL_PASSWORD` → η λειτουργία bootstrap επιτρέπει τον οδηγό onboarding και τα αιτήματα από το loopback, ενώ τα εκτεθειμένα αιτήματα δικτύου εξακολουθούν να χρειάζονται διαπιστευτήρια.
- Κάθε σφάλμα βάσης δεδομένων → αποτυγχάνει κλειστά (secure-by-default).

Η επιβολή του κλειδιού API πελάτη χρησιμοποιεί την `isRequireApiKeyEnabled()` στο `src/shared/utils/featureFlags.ts`, και όχι ανάγνωση απευθείας του `process.env.REQUIRE_API_KEY`. Αυτό έχει σημασία για τις αναπτύξεις: η αλλαγή του `REQUIRE_API_KEY` στο Dashboard → Feature Flags αποθηκεύει παράκαμψη στη βάση δεδομένων και επηρεάζει αμέσως τα `/v1/*`, `/v1beta/*`, `/models`, `/responses`, `/chat/completions`, `/codex/*` και άλλους ελέγχους αυθεντικοποίησης του client API που μοιράζονται αυτή τη βοηθητική συνάρτηση. Αν το κατάστημα των feature flags δεν μπορεί να διαβαστεί, η αυθεντικοποίηση του client API αποτυγχάνει κλειστά και απαιτεί κλειδί.

## Μη συμβατή αλλαγή — v3.8.0

Τα τελικά σημεία `/api/v1/agents/tasks/*` και `/api/resilience/model-cooldowns` **απαιτούν πλέον έλεγχο ταυτότητας διαχείρισης** (commit `588a0333`). Οι πελάτες που προηγουμένως έστελναν ένα κανονικό κλειδί API χωρίς το πεδίο εφαρμογής `manage` λαμβάνουν `403`. Μετεγκατάσταση: είτε εκχωρήστε στο κλειδί το πεδίο εφαρμογής `manage` από τον πίνακα ελέγχου API Keys είτε χρησιμοποιήστε μια συνδεδεμένη περίοδο λειτουργίας του πίνακα ελέγχου.

## Αλλαγή συμπεριφοράς — v3.8.2

Το `/api/mcp/*` (ο απομακρυσμένος διακομιστής MCP) εξακολουθεί να είναι LOCAL_ONLY από προεπιλογή, αλλά πλέον αποδέχεται αιτήματα εκτός loopback όταν η κεφαλίδα `Authorization: Bearer <api-key>` περιλαμβάνει το πεδίο εφαρμογής `manage`. Η εξαίρεση ελέγχεται ρητά ανά διαδρομή μέσω του `LOCAL_ONLY_MANAGE_SCOPE_BYPASS_PREFIXES` στο `src/server/authz/routeGuard.ts`· η συγγενική πρόθεση LOCAL_ONLY `/api/cli-tools/runtime/*` σκόπιμα ΔΕΝ μπορεί να παρακαμφθεί, επειδή μπορεί να εκκινήσει αυθαίρετες υποδιεργασίες. Τα ανώνυμα αιτήματα προς το `/api/mcp/*` εκτός loopback εξακολουθούν να επιστρέφουν `403 LOCAL_ONLY` — η προεπιλογή για κάθε νέα διαδρομή LOCAL_ONLY παραμένει αυστηρά loopback. Βλ. [Επίπεδα προστασίας διαδρομών](../security/ROUTE_GUARD_TIERS.md#manage-scope-carve-out).

## Δοκιμές

- Δοκιμές μονάδας: `tests/unit/authz/` — `classify.test.ts`, `pipeline.test.ts`, `client-api-policy.test.ts`, `management-policy.test.ts`, `public-policy.test.ts`.
- Δημόσια λίστα επιτρεπόμενων: `tests/unit/public-api-routes.test.ts`.
- Εκτέλεση εστιασμένης δοκιμής: `node --import tsx/esm --test tests/unit/authz/classify.test.ts`.

## Εντοπισμός σφαλμάτων

Ο αγωγός σφραγίζει πάντα τις απαντήσεις με:

```
x-request-id:               <correlation id, echoed in error bodies>
x-omniroute-route-class:    PUBLIC | CLIENT_API | MANAGEMENT
```

Για επικυρωμένα αιτήματα, οι κεφαλίδες αιτημάτων ανάντη (από την πλευρά του χειριστή) περιλαμβάνουν επίσης:

```
x-omniroute-auth-kind:      client_api_key | dashboard_session | management_key | anonymous | sso_user
x-omniroute-auth-id:        key_<last-4> | "dashboard" | "anonymous" | <entra-oid>
x-omniroute-auth-label:     (optional)
x-omniroute-auth-scopes:    comma-separated list
```

Χρησιμοποιήστε `assertAuth(req, expectedClass)` μέσα στους χειριστές — ρίχνει `AuthzAssertionError` με κωδικό `AUTHZ_NOT_INITIALIZED` εάν παρακαμφθεί το ενδιάμεσο λογισμικό (χρήσιμο για την καταγραφή παλινδρομήσεων διαμόρφωσης σε δοκιμές).

## Δείτε επίσης

- [API_REFERENCE.md](../reference/API_REFERENCE.md) — ένδειξη ελέγχου ταυτότητας ανά τελικό σημείο
- [COMPLIANCE.md](../security/COMPLIANCE.md) — αρχείο καταγραφής ελέγχου για συμβάντα ελέγχου ταυτότητας
- [MCP-SERVER.md](../frameworks/MCP-SERVER.md#three-scope-namespaces) — τρεις χώροι ονομάτων εμβέλειας και κατάλογος εμβελειών εργαλείων MCP
- Πηγαίος κώδικας: `src/server/authz/`, `src/lib/api/requireManagementAuth.ts`
