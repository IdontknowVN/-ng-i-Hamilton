# Mô phỏng đường đi Hamilton
  Một web tương tác trực quan giúp người dùng hiểu rõ về đường đi Hamilton và cách thuật toán quay lui (Backtracking) hoạt động để tìm kiếm đường đi.
  
<img width="861" height="736" alt="Screenshot 2026-04-07 164809" src="https://github.com/user-attachments/assets/0eee96c3-24f3-4662-8dec-d6ffba6ef3cb" />


# Ngôn ngữ
HTML
### Không sử dụng bất kỳ thư viện bên ngoài nào (No Dependencies).
# Tính năng
Vẽ đồ thị tương tác: Thêm đỉnh, nối cạnh và kéo thả để sắp xếp đồ thị theo ý trên Canvas.

Mô phỏng cây quay lui (Backtracking tree): Tự động tính toán và vẽ ra toàn bộ cấu trúc cây đệ quy, cho thấy rõ các nhánh thành công và các ngõ cụt.

Hoạt họa Step-by-Step: Mô phỏng từng bước đi của thuật toán chạy đồng thời trên cả đồ thị và cây quay lui.

# Hướng dẫn sử dụng
## Tải file Hamiltonver2 về, đúp chuột để khởi chạy.
## Bước 1: Vẽ đồ thị
Thêm Đỉnh: Chọn chế độ "Thêm đỉnh". Click vào bất kỳ không gian trống nào trên khung vẽ phía trên để tạo một đỉnh mới (tự động đặt tên A, B, C...).

Di chuyển đỉnh: Bạn có thể bấm giữ chuột vào bất kỳ đỉnh nào và rê để thay đổi vị trí.

Thêm Cạnh: Chọn chế độ "Thêm cạnh". Click vào đỉnh thứ nhất (đỉnh sẽ chuyển màu vàng), sau đó click vào đỉnh thứ hai để tạo đường nối.


## Bước 2: Phân tích Thuật toán
Bấm nút "Phân tích và tạo cây". Hệ thống sẽ chạy thuật toán Backtracking ngầm để quét qua toàn bộ các đỉnh.

Nếu đồ thị có tồn tại đường đi Hamilton, danh sách các "Đỉnh xuất phát" hợp lệ sẽ hiện ra bên dưới.

<img width="841" height="90" alt="Screenshot 2026-04-07 164837" src="https://github.com/user-attachments/assets/a5c3bb7b-6fff-4098-ab89-a2749b060019" />

## Bước 3: Xem Không gian Khám phá (Cây Quay lui)
Click vào một nút Đỉnh X (n đường) bất kỳ.
Bảng vẽ thứ hai (Tree Canvas) sẽ xuất hiện, hiển thị toàn bộ Cây Quay lui xuất phát từ đỉnh đó.

<img width="835" height="637" alt="Screenshot 2026-04-07 164910" src="https://github.com/user-attachments/assets/12ea9616-7ae6-4bfb-b40f-5b476270bc2f" />

## Bước 4: Chạy Mô phỏng Phát sáng
Ngay dưới bảng vẽ Cây, bạn sẽ thấy danh sách các con đường cụ thể (Ví dụ: #1: A ➔ B ➔ D ➔ C).

Click vào một con đường để xem hoạt ảnh. Thuật toán sẽ chạy từng bước, làm phát sáng đồng bộ cả Đồ thị phía trên và Nhánh cây tương ứng phía dưới.

<img width="833" height="377" alt="Screenshot 2026-04-07 164945" src="https://github.com/user-attachments/assets/5bfea34d-f64e-46e4-9508-5cca9cf30a25" />

Demo


https://github.com/user-attachments/assets/160425ad-84a6-4c97-840b-95a4bc5c04d3


