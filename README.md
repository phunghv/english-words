# English Words Datasource

Datasource cho ứng dụng **Learn English Word** — bộ từ vựng tiếng Anh chuyên ngành công nghệ / văn phòng, được định nghĩa theo cấu trúc chuẩn để ứng dụng đọc và hiển thị.

## Files

| File | Mô tả |
|------|-------|
| `new-words.md` | Danh sách từ vựng chính |
| `new-words-template.md` | Template hướng dẫn thêm từ mới |
| `words-version.txt` | Version hiện tại của datasource |

## Cách ứng dụng sử dụng

1. Ứng dụng đọc `words-version.txt` và so sánh với version đang lưu cục bộ.
2. Nếu version mới hơn, ứng dụng tải và parse `new-words.md`.
3. Từ vựng được hiển thị với đầy đủ phiên âm, nghĩa, cách dùng và ví dụ.

## Cấu trúc từ vựng

Mỗi từ bắt đầu bằng `## <word>`, theo sau là các trường thuộc tính:

```
## word
- phonetic: /IPA/
- difficulty: 1         (1 = Easy, 2 = Medium, 3 = Hard)
- meaning: Nghĩa tiếng Việt
- definition: English definition
- usage: Ghi chú ngữ pháp
- example: Câu ví dụ
```

### Multi-line `usage` / `example`

```
- usage:
  - **V + O**: ==accomplish== a goal / task
  - **V2/V3**: *accomplished* / *accomplished*
- example:
  - The team ==accomplished== the task ahead of schedule.
  - She ==accomplished== her goal of learning three languages.
```

### Inline styling (trong `usage` và `example`)

| Syntax | Hiển thị |
|--------|----------|
| `==text==` | Highlight (accent color + semi-bold) |
| `**text**` | In đậm |
| `*text*` | In nghiêng |

## Thêm từ mới

Tham khảo `new-words-template.md` để biết format chi tiết, sau đó thêm từ vào cuối `new-words.md` và push lên `main`.

## Auto Version Bump (CI)

Mỗi khi `new-words.md` được push lên branch `main`, GitHub Actions sẽ tự động tăng patch version trong `words-version.txt` (ví dụ: `1.0.0` → `1.0.1`) và commit lại.

Workflow: `.github/workflows/bump-version.yml`
