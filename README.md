                                    🕸️ Mô Phỏng Đồ Thị Hamilton & Cây Quay Lui (Backtracking Tree)
Một ứng dụng web tương tác trực quan giúp người dùng hiểu rõ về Đồ thị Hamilton và cách Thuật toán Quay lui (Backtracking) hoạt động để tìm kiếm đường đi. Ứng dụng không chỉ hiển thị kết quả mà còn vẽ ra toàn bộ không gian khám phá của máy tính (Cây Quay lui) với hiệu ứng phát sáng (Bloom) đồng bộ.

✨ Tính năng nổi bật
Vẽ đồ thị tương tác: Tự do thêm đỉnh, nối cạnh và kéo thả để sắp xếp đồ thị theo ý muốn ngay trên Canvas.

Mô phỏng Cây Quay lui (Backtracking Tree): Tự động tính toán và vẽ ra toàn bộ cấu trúc cây đệ quy, cho thấy rõ các nhánh thành công và các ngõ cụt.

Hoạt họa Step-by-Step: Mô phỏng từng bước đi của thuật toán chạy đồng thời trên cả Đồ thị và Cây Quay lui.

Hiệu ứng Phát sáng (Bloom Effect): Tự động làm nổi bật các nhánh đang được duyệt với hiệu ứng đổ bóng rực rỡ mang phong cách Cyberpunk / Neon trên nền màu tự nhiên.

Neo màu Đỉnh xuất phát: Đỉnh gốc luôn được đánh dấu bằng màu Xanh Lơ (Cyan) để người dùng không bị mất phương hướng khi các đường đi đan chéo phức tạp.

🚀 Hướng dẫn sử dụng
Bước 1: Vẽ Đồ thị
Thêm Đỉnh: Chọn chế độ ➕ Thêm Đỉnh. Click vào bất kỳ không gian trống nào trên khung vẽ phía trên để tạo một đỉnh mới (tự động đặt tên A, B, C...).

Di chuyển Đỉnh: Bạn có thể bấm giữ chuột vào bất kỳ đỉnh nào và rê để thay đổi vị trí.

Thêm Cạnh: Chọn chế độ 🔗 Thêm Cạnh. Click vào đỉnh thứ nhất (đỉnh sẽ chuyển màu vàng), sau đó click vào đỉnh thứ hai để tạo đường nối.

Bước 2: Phân tích Thuật toán
Bấm nút 🔍 Phân Tích & Tạo Cây. Hệ thống sẽ chạy thuật toán Backtracking ngầm để quét qua toàn bộ các đỉnh.

Nếu đồ thị có tồn tại đường đi Hamilton, danh sách các "Đỉnh xuất phát" hợp lệ sẽ hiện ra bên dưới.

Bước 3: Xem Không gian Khám phá (Cây Quay lui)
Click vào một nút Đỉnh X (n đường) bất kỳ.

Bảng vẽ thứ hai (Tree Canvas) sẽ xuất hiện, hiển thị toàn bộ Cây Quay lui xuất phát từ đỉnh đó.

Bước 4: Chạy Mô phỏng Phát sáng
Ngay dưới bảng vẽ Cây, bạn sẽ thấy danh sách các con đường cụ thể (Ví dụ: #1: A ➔ B ➔ D ➔ C).

Click vào một con đường để xem hoạt ảnh. Thuật toán sẽ chạy từng bước, làm phát sáng đồng bộ cả Đồ thị phía trên và Nhánh cây tương ứng phía dưới.

🎨 Chú giải Màu sắc (Legend)
Để theo dõi thuật toán dễ dàng, ứng dụng sử dụng hệ thống màu sắc có chủ đích:

Đỉnh Xanh Lơ (Cyan): Điểm xuất phát (Start Node). Bắt đầu của đường đi.

Cạnh & Đỉnh Vàng/Cam (Orange Bloom): Các bước di chuyển hiện tại đang được mô phỏng.

Đỉnh Xanh Lá (Green): Nút lá trên Cây biểu diễn một đường đi Hamilton thành công (đã đi qua tất cả các đỉnh).

Đỉnh Nâu Tối / Xám (Dark Brown): Nút trên Cây biểu diễn một ngõ cụt (Dead-end) hoặc nhánh khám phá thất bại.

🛠️ Công nghệ sử dụng
HTML5 Canvas: Dựng hình đồ thị và cây.

Vanilla JavaScript (ES6): Xử lý logic tương tác chuột, thuật toán đệ quy quay lui (Backtracking) và tính toán layout cây.

CSS3: Giao diện Dark Mode và hiệu ứng chuyển cảnh.

Không sử dụng bất kỳ thư viện bên ngoài nào (No Dependencies).

💡 Phù hợp cho
Sinh viên ngành Khoa học Máy tính học môn Toán Rời Rạc / Cấu trúc Dữ liệu & Giải thuật.

Giảng viên cần công cụ trực quan để trình bày trên lớp.

Bất kỳ ai yêu thích thuật toán đồ thị!
