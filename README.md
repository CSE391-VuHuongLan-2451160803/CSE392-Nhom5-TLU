# CSE392 - Nhóm 5 - TLU

> **Học phần:** CSE392  
> **Đơn vị:** Trường Đại học Thủy Lợi (TLU)  
> **Nhóm thực hiện:** Nhóm 5  

---

## 🎯 1. Mục tiêu dự án

### 1.1. Mục tiêu chung
- Xây dựng và hoàn thiện sản phẩm phần mềm/hệ thống đáp ứng đầy đủ yêu cầu nghiệp vụ của đề tài học phần CSE392.
- Áp dụng các quy trình phát triển phần mềm chuẩn mực (Agile/Scrum hoặc Waterfall), quản lý mã nguồn hiệu quả qua Git/GitHub và rèn luyện kỹ năng làm việc nhóm chuyên nghiệp.

### 1.2. Mục tiêu cụ thể
- **Về nghiệp vụ & tính năng:**
  - Thiết kế và triển khai các chức năng cốt lõi (Core features) đảm bảo tính đúng đắn, tiện dụng và thân thiện với người dùng.
  - Xây dựng hệ thống xác thực, phân quyền người dùng và bảo mật thông tin cơ bản.
  - Lưu trữ, quản lý và xử lý dữ liệu tập trung, tối ưu hóa tốc độ truy vấn cơ sở dữ liệu.
- **Về kỹ thuật:**
  - Ứng dụng kiến trúc phân tầng rõ ràng (Client-Server, MVC hoặc Clean Architecture), dễ bảo trì và mở rộng.
  - Chuẩn hóa RESTful API phục vụ kết nối thông suốt giữa Frontend và Backend.
  - Thực hiện kiểm thử phần mềm (Unit Testing, Manual/Integration Testing) nhằm phát hiện và giảm thiểu lỗi tối đa.
- **Về sản phẩm bàn giao & kỹ năng:**
  - Nâng cao kỹ năng làm việc nhóm, phân chia công việc, giải quyết xung đột (conflict resolution) trên Git.
  - Hoàn thiện bộ tài liệu kỹ thuật (SRS, báo cáo tổng kết), slide thuyết trình và sản phẩm demo theo đúng tiến độ của giảng viên hướng dẫn.

---

## 👥 2. Thành viên & Phân công vai trò

| STT | Họ và tên | Vai trò chính | Nhiệm vụ chi tiết |
|:---:|---|---|---|
| 1 | **Vũ Hương Lan** | **Trưởng nhóm (Team Leader) & Phân tích hệ thống** | - Lập kế hoạch, phân chia công việc và theo dõi tiến độ tổng thể.<br>- Khảo sát, phân tích yêu cầu nghiệp vụ và đặc tả ca sử dụng (Use Cases).<br>- Tham gia xây dựng kiến trúc hệ thống và hỗ trợ Backend.<br>- Kiểm duyệt (Code Review) và hợp nhất mã nguồn (Merge Pull Request) trên GitHub. |
| 2 | **Ngọ Thị Thu Hà** | **Frontend Developer & Thiết kế UI/UX** | - Nghiên cứu trải nghiệm người dùng, thiết kế giao diện (Figma/Wireframe).<br>- Xây dựng giao diện người dùng (UI) đảm bảo tính thẩm mỹ, hiện đại và chuẩn Responsive.<br>- Tích hợp và gọi các API từ phía Backend vào giao diện.<br>- Tối ưu hóa hiệu năng hiển thị và tương tác phía client. |
| 3 | **Nguyễn Thị Hồng Hà** | **Backend Developer & Kỹ sư CSDL (Database)** | - Khảo sát, thiết kế mô hình thực thể liên kết (ERD) và lược đồ quan hệ CSDL.<br>- Cài đặt hệ quản trị CSDL, thiết lập chỉ mục (Indexes) và tối ưu truy vấn.<br>- Xây dựng các dịch vụ Backend, xử lý logic nghiệp vụ và cung cấp RESTful API.<br>- Đảm bảo tính toàn vẹn và an toàn dữ liệu. |
| 4 | **Nguyễn Thùy Dương** | **Đảm bảo chất lượng (QA/Tester) & Quản trị tài liệu** | - Xây dựng kế hoạch kiểm thử (Test Plan), kịch bản kiểm thử (Test Cases).<br>- Tiến hành kiểm thử chức năng, giao diện và lập báo cáo lỗi (Bug Report).<br>- Phụ trách biên tập và chuẩn hóa tài liệu báo cáo đồ án, biên bản họp nhóm.<br>- Chuẩn bị slide trình chiếu và kịch bản demo phục vụ buổi báo cáo/bảo vệ. |

---

## 🛠️ 3. Công nghệ sử dụng (Dự kiến)

> *Nhóm có thể tùy chỉnh danh sách công nghệ cho phù hợp với đề tài thực tế.*

- **Frontend:** HTML5, CSS3, JavaScript / TypeScript (React.js / Vue.js / Tailwind CSS)
- **Backend:** Node.js (Express), Java (Spring Boot), Python (Django/FastAPI) hoặc C# (.NET)
- **Cơ sở dữ liệu:** MySQL / PostgreSQL / MongoDB / SQL Server
- **Công cụ phát triển & Quản lý:** Git, GitHub, Postman, Figma, Trello/Jira, VS Code

---

## 📁 4. Cấu trúc thư mục dự án

```text
CSE392-Nhom5-TLU/
├── docs/               # Tài liệu phân tích thiết kế, đặc tả yêu cầu, test cases, báo cáo
├── frontend/           # Mã nguồn giao diện người dùng
├── backend/            # Mã nguồn xử lý nghiệp vụ và API
├── database/           # File script khởi tạo CSDL (.sql), migrations, dữ liệu mẫu
└── README.md           # Tài liệu giới thiệu và hướng dẫn tổng quan dự án
```

---

## 🚀 5. Hướng dẫn cài đặt & Khởi chạy

1. **Sao chép mã nguồn:**
   ```bash
   git clone https://github.com/<tai-khoan>/CSE392-Nhom5-TLU.git
   cd CSE392-Nhom5-TLU
   ```

2. **Cài đặt và chạy Backend:**
   ```bash
   cd backend
   # Cài đặt thư viện và khởi chạy theo framework sử dụng (vd: npm install && npm start)
   ```

3. **Cài đặt và chạy Frontend:**
   ```bash
   cd ../frontend
   # Cài đặt thư viện và khởi chạy (vd: npm install && npm run dev)
   ```

---

## 📅 6. Quy định làm việc & Quản lý mã nguồn

- **Quy tắc phân nhánh (Git Flow):**
  - `main`: Nhánh ổn định cao nhất, dùng để nộp bài hoặc triển khai bản demo cuối.
  - `develop`: Nhánh tích hợp chung phục vụ thử nghiệm nội bộ.
  - `feature/<ten-tinh-nang>`: Nhánh làm việc riêng của từng thành viên khi phát triển module mới.
- **Quy ước Commit:** Ghi rõ nội dung thay đổi theo chuẩn (ví dụ: `feat: thêm chức năng đăng nhập`, `fix: sửa lỗi hiển thị bảng`).
- **Họp nhóm:** Định kỳ hàng tuần hoặc sau mỗi mốc sprint để tổng kết và gỡ vướng mắc.
