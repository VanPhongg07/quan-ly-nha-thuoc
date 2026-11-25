# quan-ly-nha-thuoc

Hệ Thống Quản Lý Nhà Thuốc
# Hệ Thống Quản Lý Nhà Thuốc (Pharmacy Management System)

## 1. Giới thiệu dự án
Phần mềm hỗ trợ quản lý hoạt động kinh doanh và kho dược phẩm tại nhà thuốc, tập trung vào các nghiệp vụ cốt lõi:
- Quản lý danh mục thuốc, hoạt chất, đơn vị tính (Hộp / Vỉ / Viên) và nhà cung cấp.
- Nhập kho theo từng **lô sản xuất** và theo dõi **hạn sử dụng**.
- Bán lẻ theo đơn hoặc không đơn, tự động xuất kho theo nguyên tắc **FEFO** (*First Expired, First Out* – hết hạn trước xuất trước).
- Cảnh báo thuốc cận hạn sử dụng và thuốc dưới mức tồn kho tối thiểu.
- Thống kê doanh thu, lợi nhuận theo ngày/tháng.

## 2. Thành viên nhóm

| STT | Họ và tên | MSSV | Vai trò dự kiến | GitHub |
| :---: | :--- | :--- | :--- | :--- |
| 1 | Lê Văn Phong | @VanPhongg07 | Nhóm trưởng (Scrum Master / Dev) |
| 2 | Mai Tiến Đạt | ... | Thành viên / Backend | [@tdat47](https://github.com/tdat47) |
| 3 | Tuấn Phan Công | 25S1020112| Thành viên/ Database Dev | [@pct2904](https://github.com/pct2904) | 
| 4 | Trần Phi Quân | quandaychang | Thành viên/ Database Dev) |

## 3. Công nghệ sử dụng & Kiến trúc
- **Mô hình kiến trúc:** Layered Architecture (3 tầng: Presentation – Business Logic – Data Access)
- **Ngôn ngữ / Framework:** *(Điền công nghệ nhóm chốt, ví dụ: Java / C# / Node.js + React)*
- **Cơ sở dữ liệu:** *(Ví dụ: SQL Server / MySQL)*

## 4. Quy trình làm việc trên Git (Git Flow)
1. `main`: Nhánh chính, chỉ chứa bản chạy ổn định cuối mỗi Sprint.
2. `develop`: Nhánh tích hợp chung của cả nhóm.
3. `feature/<ten-tinh-nang>`: Nhánh phát triển từng chức năng, tách từ `develop` và gửi Pull Request (PR) để review trước khi merge vào `develop`.



