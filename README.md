# 📒 Simple Note App (Flutter)

Ứng dụng ghi chú đơn giản được xây dựng bằng Flutter.

---

## 🚀 Chức năng chính

- ✅ Thêm ghi chú (Title + Content)
- ✅ Hiển thị danh sách ghi chú
- ✅ Sửa ghi chú
- ✅ Xóa ghi chú (có xác nhận)
- ✅ Lưu dữ liệu cục bộ bằng SQLite (Sqflite)
- ✅ Hiển thị thời gian cập nhật

---

## 🛠️ Công nghệ sử dụng

- Flutter
- Sqflite (SQLite local database)
- Provider (State Management)
- path_provider
- intl

---

## 📂 Cấu trúc project


lib/
├── models/
│ └── note.dart
├── database/
│ └── db_helper.dart
├── providers/
│ └── note_provider.dart
├── screens/
│ ├── home_page.dart
│ └── note_editor_screen.dart
├── widgets/
│ └── note_card.dart
└── main.dart


---

## 📸 Demo ứng dụng

### 🏠 Màn hình chính
![Home](0.png)

### ➕ Thêm ghi chú
![Add](1.png)

### ✏️ Nhập nội dung
![Edit](2.png)

### 📋 Danh sách ghi chú
![List](3.png)

---

## ⚙️ Cách chạy project

```bash
flutter pub get
flutter run
📌 Ghi chú
Dữ liệu được lưu offline (SQLite)
Không cần internet
Không dùng Firebase hay API
