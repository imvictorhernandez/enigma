# Gmail Reorganization Action Plan

_Last updated: 2026-05-10_
_Status: NOT STARTED — execute in a separate session_

---

## Current Labels (18 user-defined)

| Label | Issue |
|---|---|
| `Ciudadania Espanola` | Spanish, not nested |
| `Lancelot LLC` | Not nested |
| `Best Buy` | Merchant, not categorized |
| `Traveling` | Not nested, wrong tense |
| `Malevich` | Not nested |
| `Other` | Vague catch-all |
| `Work` | Too broad |
| `LinkedIn` | Platform name, not categorized |
| `Aston` | Unclear — clarify before acting |
| `Family` | Not nested |
| `Friends` | Not nested (not in original plan — add) |
| `Google` | Platform name, not categorized |
| `Key Innovation` | Unclear — clarify before acting |
| `Health` | Not nested |
| `Residential` | Ambiguous — clarify before acting |
| `Banks` | Not nested |
| `Amazon` | Merchant name, not categorized |
| `Taxes` | Not nested |

### Labels to Clarify Before Acting
- **`Aston`** — is this Aston Martin (car), a person, or a company?
- **`Key Innovation`** — is this an employer, vendor, or business contact?
- **`Residential`** — is this home/apartment related? Which property?

---

## Target Label Structure (18 labels)

### System (unchanged)
`INBOX`, `SENT`, `DRAFTS`, `SPAM`, `TRASH`

### Personal
- `personal/finance`
- `personal/taxes`
- `personal/health`
- `personal/travel`
- `personal/immigration`
- `personal/family`
- `personal/friends` ← added (found Friends label in audit)

### Business
- `business/kitusa`
- `business/malevich`
- `business/sir-lancelot`

### Professional
- `professional/revenue-analytics`

### Admin
- `admin/legal`
- `admin/receipts`
- `admin/subscriptions`

### Noise
- `noise/newsletters`

---

## Phase 1 — Create New Labels
_Purely additive. Nothing is moved or deleted. Zero risk._

- [ ] 1.  Create `personal/finance`
- [ ] 2.  Create `personal/taxes`
- [ ] 3.  Create `personal/health`
- [ ] 4.  Create `personal/travel`
- [ ] 5.  Create `personal/immigration`
- [ ] 6.  Create `personal/family`
- [ ] 7.  Create `personal/friends`
- [ ] 8.  Create `business/kitusa`
- [ ] 9.  Create `business/malevich`
- [ ] 10. Create `business/sir-lancelot`
- [ ] 11. Create `professional/revenue-analytics`
- [ ] 12. Create `admin/legal`
- [ ] 13. Create `admin/receipts`
- [ ] 14. Create `admin/subscriptions`
- [ ] 15. Create `noise/newsletters`

---

## Phase 2 — Re-label Threads
_Old labels stay. Nothing deleted yet._

- [ ] 16. Re-label Revenue Analytics threads → `professional/revenue-analytics`
- [ ] 17. Re-label `Malevich` threads → `business/malevich`
- [ ] 18. Re-label `Lancelot LLC` threads → `business/sir-lancelot`
- [ ] 19. Re-label `Work` threads (RA-related) → `professional/revenue-analytics`
- [ ] 20. Re-label `Work` threads (KITUSA-related) → `business/kitusa`
- [ ] 21. Re-label `Banks` threads → `personal/finance`
- [ ] 22. Re-label `Taxes` threads → `personal/taxes`
- [ ] 23. Re-label `Health` threads → `personal/health`
- [ ] 24. Re-label `Traveling` threads → `personal/travel`
- [ ] 25. Re-label `Ciudadania Espanola` threads → `personal/immigration`
- [ ] 26. Re-label `Family` threads → `personal/family`
- [ ] 27. Re-label `Friends` threads → `personal/friends`
- [ ] 28. Re-label `Amazon` and `Best Buy` threads → `admin/receipts`
- [ ] 29. Re-label `LinkedIn` and `Google` threads → `noise/newsletters`
- [ ] 30. Re-label `Residential` threads → determine correct label first
- [ ] 31. Re-label `Aston` threads → determine correct label first
- [ ] 32. Re-label `Key Innovation` threads → determine correct label first
- [ ] 33. Review `Other` — archive or delete contents

---

## Phase 3 — Delete Old Labels
_Only after Phase 2 is fully verified._

- [ ] 34. Delete `Work`
- [ ] 35. Delete `Malevich`
- [ ] 36. Delete `Lancelot LLC`
- [ ] 37. Delete `Traveling`
- [ ] 38. Delete `Ciudadania Espanola`
- [ ] 39. Delete `Family`
- [ ] 40. Delete `Friends`
- [ ] 41. Delete `Banks`
- [ ] 42. Delete `Taxes`
- [ ] 43. Delete `Health`
- [ ] 44. Delete `Amazon`
- [ ] 45. Delete `Best Buy`
- [ ] 46. Delete `LinkedIn`
- [ ] 47. Delete `Google`
- [ ] 48. Delete `Other`
- [ ] 49. Delete `Residential` (after re-labeling)
- [ ] 50. Delete `Aston` (after re-labeling)
- [ ] 51. Delete `Key Innovation` (after re-labeling)

---

## Gmail MCP Info

- **MCP Server ID:** `fe4c5c30-0346-42c4-8e63-28f211c78c80`
- **Tools needed:**
  - `create_label` — Phase 1
  - `label_thread` / `unlabel_thread` — Phase 2
  - Search tool to find threads by label before re-labeling

---

## Completed Log

| Date | Step | Notes |
|---|---|---|
| 2026-05-10 | Gmail audit complete | 18 labels found, 3 need clarification |
