# OBS Level Editor (art thật)

Editor dựng level cho Ocean Block Shoot — một file HTML, mở bằng trình duyệt là dùng.

**Mở online:** https://hieunm3-lab.github.io/obs-level-editor/

## ☢ Nuclear Bomb (id 240) — chỉnh độ bền

1. Chọn **Nuclear bomb** ở nhóm ☢ trong bảng khối bên trái, vẽ lên bàn (chỉ cỡ 1×1×1, mặc định độ bền 5).
2. Công cụ **✋ Di chuyển** → bấm vào quả bom.
3. Cột phải, panel **☢ NUCLEAR BOMB · ĐỘ BỀN** → nhập số phát bắn → Enter. Ctrl+Z để hoàn tác.
4. **⬇️ Tải về** → file ghi `"metadata":"{\"shots\":N}"`.

Luật trong game: mỗi phát bắn (trúng hay trượt) −1 · về 0 → nháy 2 giây → nổ = **thua** · bom chạm mặt nước là gỡ ngòi.
Cảnh báo cam: độ bền ≥ số đạn (bom vô hại) · bom ở Stage 2+ (game đếm cả phát bắn của stage trước).

## Cập nhật

File `index.html` được sinh từ `level_editor_v2.html` bằng `Levels\_tools\obs_make_art_editor.py`, không sửa tay.
