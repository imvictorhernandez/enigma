# 02 — REORGANIZATION PLAN: New Drive and Gmail Structure

_Last updated: 2026-05-10_
_Reflects final agreed structure after naming corrections (Education, Business entities)_

---

## New Drive Folder Tree (Target State)

```
My Drive/
├── Business/
│   ├── KITUSA/
│   │   ├── Documents/
│   │   ├── Financials/
│   │   └── Legal/
│   ├── Malevich/
│   │   ├── 4810 Lafayette/
│   │   │   ├── Lease Agreements/
│   │   │   ├── Maintenance/
│   │   │   └── Financials/
│   │   └── General/
│   └── Sir Lancelot/
│       ├── Documents/
│       ├── Financials/
│       └── Legal/
├── Personal/
│   ├── Finance/
│   │   ├── Banking/
│   │   ├── Taxes/
│   │   └── Investments/
│   ├── Health/
│   ├── Travel/
│   ├── Pets/
│   └── Immigration/
│       └── Spanish Citizenship/
├── Education/
│   ├── Courses/
│   └── Certificates/
└── Professional/
    └── Revenue Analytics/
        ├── Contracts/
        └── Payroll/
```

---

## Naming Conventions Applied

- **Title Case** for all folders and files
- **No parentheses** — use plain names only
- **Short names** — drop generic suffixes like "Records", "History", "Analysis"
- **Address-based** names for properties (e.g. "4810 Lafayette" not "Property 1")
- **No mixed languages** — English only

---

## File Migration Map

| Current Location | New Location | Notes |
|---|---|---|
| `KITUSA/` | `Business/KITUSA/` | Move entire folder |
| `Malevich/` | `Business/Malevich/` | Move entire folder |
| `Sir Lancelot LLC/` | `Business/Sir Lancelot/` | Move + rename (drop "LLC") |
| `Personal/Finance/` | `Personal/Finance/` | No change |
| `Personal/Health/` | `Personal/Health/` | No change |
| `Personal/Travel/` | `Personal/Travel/` | No change |
| `Personal/Pets/` | `Personal/Pets/` | No change |
| `Personal/Immigration/` | `Personal/Immigration/` | No change |
| `Education/` | `Education/` | No change (renamed from "University" if applicable) |
| `Professional/Revenue Analytics/` | `Professional/Revenue Analytics/` | No change |

---

## New Gmail Label Map (Target: 18 labels)

### System (unchanged)
- Inbox, Sent, Drafts, Spam, Trash

### Personal
| New Label | Replaces |
|---|---|
| `personal/finance` | `Finance` (split: personal only) |
| `personal/taxes` | Subset of old `Finance` |
| `personal/health` | `Health` |
| `personal/travel` | `Travel` |
| `personal/immigration` | `Immigration` |
| `personal/family` | `Family` |

### Business
| New Label | Replaces |
|---|---|
| `business/kitusa` | `KITUSA` + part of `Work` |
| `business/malevich` | `Malevich` + `Real Estate` |
| `business/sir-lancelot` | Part of `Work` |

### Professional
| New Label | Replaces |
|---|---|
| `professional/revenue-analytics` | Part of `Work` |

### Admin
| New Label | Replaces |
|---|---|
| `admin/legal` | `Legal` |
| `admin/receipts` | `Receipts` |
| `admin/subscriptions` | `Subscriptions` |

### Noise
| New Label | Replaces |
|---|---|
| `noise/newsletters` | `Newsletters` |

### Retired Labels (to delete after migration)
- `Work` → split into business/ and professional/
- `Real Estate` → merged into `business/malevich`
- `Legal` → renamed to `admin/legal`
- `Misc` → nothing migrates here; archive or delete contents

---

## What Gets Relabeled

| Thread type | Old label | New label |
|---|---|---|
| Revenue Analytics HR, payroll, benefits | `Work` | `professional/revenue-analytics` |
| KITUSA contracts, ops | `Work` or `KITUSA` | `business/kitusa` |
| Malevich / 4810 Lafayette | `Malevich` or `Real Estate` | `business/malevich` |
| Sir Lancelot | `Work` | `business/sir-lancelot` |
| Personal legal | `Legal` | `admin/legal` |
| Business legal | `Legal` | relevant `business/*` label |
| Personal finance | `Finance` | `personal/finance` |
| Tax correspondence | `Finance` | `personal/taxes` |
