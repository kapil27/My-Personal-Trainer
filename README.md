# My Personal Trainer

Personal fitness and nutrition planning — powered by the **personal-nutrient-trainer** Cursor skill.

## Weekly workflow

| When | Skill mode | Output |
|------|------------|--------|
| **Each week** | Weekly diet | `my Nutrients/weeks/week-NN/DIET.md` + shopping list |
| **Each week** | Weekly supplements | `my Nutrients/weeks/week-NN/SUPPLEMENTS.md` |
| **Each Sunday** | Health checkup | `health/checkups/DATE.md` + `health/LOG.md` |

### Example prompts

```
Week 2 diet — more paneer, less rice on rest days
Week 2 supplements — fish oil upset my stomach
Health checkup — weight 72.4 kg, sleep 7 hrs
```

## Folder layout

```
my Nutrients/
├── PROFILE.md              ← baseline macros & goals
├── BLOOD-WORK.md
├── TRAINING-DAY-GUIDE.md
├── health/
│   ├── LOG.md
│   └── checkups/
└── weeks/
    └── week-01/
        ├── DIET.md
        ├── SUPPLEMENTS.md
        └── SHOPPING-LIST.md
```

**Start here:** [my Nutrients/PROFILE.md](my%20Nutrients/PROFILE.md)

## Repo

https://github.com/kapil27/My-Personal-Trainer

## Privacy

Do not commit lab PDFs with personal identifiers.
