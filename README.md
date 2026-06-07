# Mô hình 3D: Tư tưởng Hồ Chí Minh về văn hóa

Đây là mô hình triển lãm 3D chạy trên trình duyệt, dùng Three.js để tạo không gian bảo tàng số mang phong cách điện ảnh. File chính của dự án là `mohinh_cinematic.html`.

## Cách chạy

Mở PowerShell tại thư mục dự án:

```powershell
cd C:\Users\Th0w0\Desktop\LSD
```

Chạy static server:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Mở trình duyệt và truy cập:

```text
http://127.0.0.1:8000/mohinh_cinematic.html
```

Không nên mở trực tiếp bằng double-click hoặc đường dẫn `file://`, vì trang dùng ES module và import Three.js từ thư mục `vendor/`.

## Cấu trúc file cần thiết

```text
LSD/
+-- README.md
+-- mohinh_cinematic.html
+-- president_ho_chi_minh_statue.glb
+-- bac_ho.jpg
+-- vendor/
    +-- three.module.js
    +-- OrbitControls.js
    +-- GLTFLoader.js
    +-- BufferGeometryUtils.js
```

## Điều khiển

- Bấm `TỔNG QUAN` để xem toàn bộ không gian.
- Bấm `CUNG 1` đến `CUNG 5` để camera bay đến từng khu trưng bày.
- Kéo chuột trái để xoay góc nhìn.
- Kéo chuột phải để di chuyển khung nhìn.
- Lăn chuột để phóng to hoặc thu nhỏ.

## Ideas của mô hình

Mô hình được thiết kế như một bảo tàng số gồm 5 cung triển lãm xếp theo hình cánh sen. Trung tâm là tượng Chủ tịch Hồ Chí Minh, đặt trong lõi ánh sáng vàng, tượng trưng cho vị trí hạt nhân của tư tưởng Hồ Chí Minh trong nền tảng văn hóa Việt Nam.

## Ý nghĩa tổng thể

Bố cục cánh sen tạo cảm giác trang trọng, gắn với biểu tượng sen trong văn hóa Việt Nam: thanh cao, gần gũi và bền bỉ. Năm cung triển lãm tỏa ra từ trung tâm để thể hiện các lớp ý nghĩa của tư tưởng văn hóa Hồ Chí Minh: từ nguồn gốc, nền tảng xây dựng đất nước, vai trò của văn hóa, niềm tin vào thế hệ trẻ, đến sự vận dụng của Đảng trong thực tiễn hiện đại.

Ánh sáng vàng, vật liệu kính, kim loại và các hiệu ứng neon được dùng để kết hợp hai tinh thần: sự trang nghiêm của lịch sử và cách tiếp cận số hóa hiện đại.

### Cung 1: Khởi nguồn tư tưởng văn hóa

Cung này thể hiện nền tảng hình thành tư tưởng văn hóa của Hồ Chí Minh. Ý nghĩa chính là sự kết hợp giữa truyền thống dân tộc, tinh hoa văn hóa nhân loại và trải nghiệm cách mạng của Người.

Không gian mở đầu giúp người xem hiểu rằng tư tưởng văn hóa không xuất hiện tách rời, mà được hình thành từ lòng yêu nước, nhân nghĩa, tinh thần học hỏi và khả năng tiếp thu có chọn lọc các giá trị tiến bộ.

### Cung 2: Bốn trụ cột xây dựng quốc gia

Cung 2 tập trung vào bốn trụ cột: chính trị, kinh tế, xã hội và văn hóa. Ý tưởng trưng bày nhấn mạnh quan điểm văn hóa không phải phần trang trí bên ngoài, mà là một thành tố cấu thành sức mạnh quốc gia.

Ý nghĩa của khu này là cho thấy văn hóa cần song hành với phát triển đất nước. Một quốc gia bền vững không chỉ cần kinh tế và thể chế, mà còn cần đời sống tinh thần, đạo đức, giáo dục và bản sắc.

### Cung 3: Vai trò, mục tiêu và động lực của văn hóa

Cung 3 trình bày văn hóa như một mục tiêu, một động lực và một mặt trận. Các biểu tượng như ngôi nhà, ngọn đuốc, ánh sáng hoặc cột trưng bày gợi ý văn hóa vừa là nơi con người hướng đến, vừa là năng lượng thúc đẩy xã hội tiến bộ.

Ý nghĩa của cung này là làm rõ tầm nhìn của Hồ Chí Minh: văn hóa phải soi đường cho quốc dân đi, phải góp phần xây dựng con người mới, và phải tham gia vào công cuộc đấu tranh vì độc lập, tự do, hạnh phúc.

### Cung 4: Cây điều ước và thế hệ trẻ

Cung 4 dùng hình ảnh cây phát sáng như một biểu tượng của niềm tin vào tương lai. Mỗi tán lá, ánh sáng và nhánh cây gợi ý những ước mơ, lý tưởng và trách nhiệm của thế hệ trẻ trong việc tiếp nối giá trị văn hóa dân tộc.

Ý nghĩa của khu này là nhấn mạnh văn hóa chỉ thực sự sống khi được trao truyền. Thế hệ trẻ không chỉ là người tiếp nhận di sản, mà còn là người làm mới, sáng tạo và đưa giá trị Hồ Chí Minh vào đời sống hiện đại.

### Cung 5: Sự vận dụng của Đảng trong thực tiễn

Cung 5 mang tính trực quan và dòng thời gian, gắn các mốc văn kiện, chủ trương và quá trình phát triển văn hóa Việt Nam. Không gian này kết nối từ nền tảng tư tưởng đến hành động chính sách.

Ý nghĩa của cung này là cho thấy tư tưởng Hồ Chí Minh về văn hóa không dừng lại ở lý thuyết. Tư tưởng đó được tiếp tục vận dụng trong xây dựng nền văn hóa Việt Nam tiên tiến, đậm đà bản sắc dân tộc, đồng thời thích ứng với chuyển đổi số và công nghiệp văn hóa hiện nay.

## Thông điệp chính

Mô hình muốn truyền tải rằng văn hóa là nền tảng tinh thần của xã hội, là sức mạnh nội sinh của dân tộc và là động lực cho phát triển bền vững. Tư tưởng Hồ Chí Minh về văn hóa vừa gắn với lịch sử, vừa có giá trị hiện đại, đặc biệt trong bối cảnh giáo dục, sáng tạo và chuyển đổi số.
