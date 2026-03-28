# new-words.md

Word data file for **Learn English Word** app.
Push this file (and `words-version.txt`) to your public GitHub repo.

---

## Format

Each word starts with `## <word>` followed by attribute lines.

### Inline text styling (works in `usage` and `example`)

| Syntax | Renders as |
|---|---|
| `==text==` | Highlighted (accent color + bold) |
| `**text**` | Bold |
| `*text*` | Italic |

### Single-line fields

```
## word
- phonetic: /IPA/
- difficulty: 1         (1 = Easy, 2 = Medium, 3 = Hard)
- meaning: Vietnamese   (required)
- definition: English definition
- usage: single-line grammar note
- example: single example sentence
```

### Multi-line `usage` and `example`

Use `- usage:` (empty value) then indent sub-bullets with two spaces:

```
## word
- phonetic: /IPA/
- difficulty: 2
- meaning: Vietnamese meaning
- definition: English definition
- usage:
  - **V + O** (transitive): ==accomplish== a goal / task / mission
  - **V2 / V3**: *accomplished* / *accomplished* (regular)
  - Giới từ: ==không cần giới từ==
  - Collocations: *successfully* accomplish, *fully* accomplish
- example:
  - She ==accomplished== her goal of learning three languages by 25.
  - The team accomplished the impossible within the deadline.
```

---

<!-- Add words below this line -->
