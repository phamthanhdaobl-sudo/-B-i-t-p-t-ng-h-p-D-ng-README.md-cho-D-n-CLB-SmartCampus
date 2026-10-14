# Ôn tập – Phần 4: Bẫy cú pháp Markdown

## 1. Hai lỗi cú pháp

**Lỗi 1 – Bảng thiếu dòng phân cách**

Sau hàng tiêu đề `| Tính năng | Trạng thái |` cần có một hàng phân cách, ví dụ:

`| --- | --- |`

Nếu thiếu hàng này, trình kết xuất Markdown có thể không nhận diện đúng cấu trúc bảng.

**Lỗi 2 – Task List thiếu khoảng trắng sau dấu gạch đầu dòng**

Cú pháp đúng cần có khoảng trắng sau dấu `-`:

- `- [x] Tra cứu lịch học`
- `- [ ] Push notification`

Đoạn sai là `-[x]` và `-[ ]`, vì thiếu khoảng trắng giữa dấu gạch đầu dòng và dấu ngoặc vuông.

## 2. Đoạn Markdown đã sửa

```markdown
| Tính năng | Trạng thái |
| --- | --- |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
```

## 3. Kết quả mong đợi

- Bảng có hai cột: **Tính năng** và **Trạng thái**.
- “Tra cứu lịch học” được đánh dấu hoàn thành.
- “Push notification” được đánh dấu chưa hoàn thành.
