# Sekiro Savegame

Một công cụ đơn giản giúp người chơi Sekiro: Shadows Die Twice dễ dàng quản lý, sao lưu và khôi phục (revert) các tệp lưu trữ (savegame) của mình.

## ✨ Tính năng chính

Công cụ được thiết kế để đơn giản hóa quá trình quản lý savegame, đặc biệt hữu ích cho những ai muốn thử nghiệm nhiều bản lưu hoặc phòng ngừa lỗi.

* **Sao lưu dễ dàng (Backup):** Nhanh chóng tạo bản sao lưu tệp lưu trữ hiện tại với tên tùy chỉnh.
    * Phím tắt: `CTRL + B`
* **Khôi phục nhanh chóng (Revert):** Dễ dàng quay lại bất kỳ bản sao lưu nào đã chọn.
    * Phím tắt: `CTRL + R`
* **Nhập tệp lưu trữ ngoài (Import):** Cho phép nhập tệp lưu trữ từ nguồn khác để sử dụng trong game.
* **Quản lý tệp lưu trữ:**
    * Đổi tên bản sao lưu đã chọn.
    * Xóa bản sao lưu không cần thiết.
* **Tùy chọn nâng cao:**
    * `Patch game to load unimported foreign/modified save files`: Vá game để tải các tệp lưu trữ nước ngoài/đã chỉnh sửa chưa được nhập.
    * `Enable hotkey shortcuts`: Bật/Tắt các phím tắt nhanh.

## 📥 Cách sử dụng

### 1. Vị trí tệp lưu trữ

Công cụ sẽ tự động phát hiện và hiển thị đường dẫn đến tệp lưu trữ Sekiro của bạn. Thông thường, nó sẽ nằm ở:

`[Tên người dùng]\AppData\Roaming\Sekiro\[ID Người dùng]\S0000.sl2`

*(Ví dụ trong hình: `ADMIN\AppData\Roaming\Sekiro\76561197960267366\S0000.sl2`)*
<img width="524" height="549" alt="image" src="https://github.com/user-attachments/assets/bb800466-aea6-442d-8d32-6a058964bf01" />

### 2. Hướng dẫn cơ bản

1.  **Chạy ứng dụng:** Khởi động `Simple Sekiro Savegame Helper.exe`.
2.  **Sao lưu lần đầu:**
    * Nhập tên bản sao lưu vào ô **"Backup name..."** (Ví dụ: `NewGame_Run1`).
    * Nhấn nút **"Backup savegame (CTRL + B)"**. Bản sao lưu sẽ được thêm vào danh sách thả xuống.
3.  **Nhập tệp lưu trữ ngoài (Import Foreign Savegame):**
    * Nhấn nút **"Import foreign savegame"**.
    * Một cửa sổ duyệt tệp sẽ hiện ra. Chọn tệp lưu trữ Sekiro có định dạng `.sl2` (hoặc định dạng tương đương) mà bạn muốn sử dụng.
    * **Lưu ý:** Tệp này sẽ được đưa vào làm tệp lưu trữ chính của game, thay thế tệp hiện tại.
4.  **Khôi phục (Revert):**
    * Chọn bản sao lưu bạn muốn quay lại từ danh sách thả xuống (ví dụ: `11/19 21:37:43`).
    * Nhấn nút **"Revert to selected backup (CTRL + R)"**. Tệp lưu trữ chính của game sẽ được thay thế bằng bản sao lưu này.
5.  **Các thao tác khác:** Sử dụng các nút **"Set new name for selected backup"** và **"Delete selected savegame"** để quản lý các bản lưu của bạn.

## 🛠 Yêu cầu hệ thống

* Hệ điều hành: Windows (Vì đường dẫn savegame sử dụng cấu trúc `AppData\Roaming`)
* Game: Sekiro: Shadows Die Twice phải được cài đặt.

## 🛑 Lưu ý quan trọng

* **Luôn sao lưu tệp gốc:** Mặc dù công cụ được thiết kế để quản lý savegame, bạn nên sao lưu thủ công tệp `S0000.sl2` gốc của mình ở một nơi an toàn trước khi sử dụng công cụ lần đầu.
* **Sử dụng có trách nhiệm:** Việc sử dụng các tệp lưu trữ đã chỉnh sửa hoặc của người khác có thể ảnh hưởng đến trải nghiệm game.

---
