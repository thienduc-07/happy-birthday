Dat anh ky niem vao thu muc nay.

Cach 1 (it anh, tuy bien caption):
- Chinh `CONFIG.memoryPhotos` trong `index.html`.

Cach 2 (nhieu anh, khuyen dung):
- Dat ten file theo mau: memory-001.jpg, memory-002.jpg, ...
- Trong `index.html`, dat:
  - `memoryAutoCount` = tong so anh
  - `memoryAutoPattern.padding` = 3 (neu ten co 3 so 0)
  - `memoryAutoPattern.ext` = "jpg" hoac "webp" / "png"

Khi `memoryAutoCount > 0`, he thong se tu tao danh sach anh theo pattern, khong can viet tay tung dong.

Day hoa 2 ben memories:
- Dat file vao: `assets/memories/garland.png`
- He thong se tu dung 1 file nay cho ca ben trai va ben phai (ben phai tu dong mirror).
