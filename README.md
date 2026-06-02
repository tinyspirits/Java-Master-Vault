# Java Master Vault

A structured knowledge base for Java development, built with [Obsidian](https://obsidian.md).

---

## Mở bằng Obsidian

1. Tải và cài đặt [Obsidian](https://obsidian.md/download)
2. Mở Obsidian → chọn **Open folder as vault**
3. Chọn thư mục `Java-Master-Vault`
4. Obsidian sẽ tự nhận diện toàn bộ các file `.md` trong vault

---

## Cấu trúc Vault

```
Java-Master-Vault/
├── 00. Java Master MOC.md        # Map of Content — điểm bắt đầu
├── 01. Essentials/               # JVM, JDK, GC, WORA
├── 02. Core Syntax/              # OOP, Collections, Streams, Lambda...
├── 03. Project Structure/        # Spring Boot layout, Layered Architecture
├── 04. Build Tools/              # Maven, Gradle
├── 05. Testing/                  # JUnit 5, Mockito
├── 06. ORM/                      # JPA, Hibernate, Entity Relationships
├── _assets/                      # Hình ảnh, file đính kèm
└── _templates/                   # Template tạo note mới
```

---

## Cách dùng

### Điều hướng
- Mở **`00. Java Master MOC.md`** để xem toàn bộ bản đồ nội dung
- Dùng `Ctrl/Cmd + O` để tìm kiếm nhanh bất kỳ note nào
- Dùng `Ctrl/Cmd + Shift + F` để tìm kiếm toàn văn trong vault

### Graph View
- Nhấn `Ctrl/Cmd + G` để mở **Graph View** — xem mối liên kết giữa các note

### Tạo note mới
1. Nhấn `Ctrl/Cmd + N` để tạo note mới
2. Vào **Templates** → áp dụng `_templates/Note Template.md` để có cấu trúc chuẩn

### Backlinks
- Mỗi note đều có thể liên kết nhau bằng cú pháp `[[Tên Note]]`
- Mở panel **Backlinks** (góc phải) để xem note nào đang trỏ đến note hiện tại

---

## Plugins được khuyến nghị

| Plugin | Công dụng |
|---|---|
| **Dataview** | Tạo bảng/query động từ metadata của các note |
| **Templater** | Template nâng cao hơn core Templates |
| **Calendar** | Kết hợp daily notes theo lịch |
| **Obsidian Git** | Tự động commit & sync vault lên GitHub |

Vào **Settings → Community Plugins → Browse** để cài đặt.

---

## Sync & Backup

- **Obsidian Sync** (trả phí): đồng bộ đa thiết bị chính thức
- **Git + GitHub**: dùng plugin [Obsidian Git](https://github.com/denolehov/obsidian-git) để tự động push
- **iCloud / Google Drive**: đặt vault trong thư mục cloud để sync thủ công
