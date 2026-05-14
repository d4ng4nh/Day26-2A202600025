# Lab 2: Phân tích so sánh Perplexity và ChatGPT Search

**Nhiệm vụ**: Giải thích NĐ 13/2023 bảo vệ dữ liệu cá nhân của Việt Nam — áp dụng cho startup AI thế nào? Cho tôi 3 điều quan trọng nhất phải làm.

## S1 — Product Moment
*   **Perplexity**: Giao diện tối giản tập trung hoàn toàn vào ô tìm kiếm ("Where knowledge begins"). Trải nghiệm người dùng được thiết kế chuyên biệt cho việc tra cứu thông tin (Search-first).
*   **ChatGPT Search**: Giao diện chat truyền thống với biểu tượng "Web Search" tích hợp. Trải nghiệm được thiết kế theo hướng hội thoại (Chat-first), tính năng search đóng vai trò bổ trợ.

## S2 — Workflow Evidence (Frictions)
*   **Perplexity**: 
    *   *Ưu điểm*: Trình bày danh sách nguồn (Sources) to rõ ngay trên cùng, trước khi đọc câu trả lời. 
    *   *Friction*: Không hỗ trợ tốt các tác vụ đòi hỏi sự sáng tạo hoặc reasoning dài hơi ngoài luồng dữ liệu search.
*   **ChatGPT Search**:
    *   *Ưu điểm*: Văn phong tự nhiên, có khả năng suy luận sâu và liên kết với các framework khác (ví dụ: yêu cầu viết thêm code bảo mật).
    *   *Friction*: Trích dẫn nguồn (Citations) nhỏ, dạng `[1]`, `[2]` ẩn trong câu, người dùng phải tốn thêm thao tác click để mở thanh bên (sidebar) kiểm chứng nguồn.

## S3 — Output & Trust
*   **Perplexity**: Tín hiệu đáng tin (Trust signals) rất cao. Luôn hiển thị cụ thể trích xuất thông tin nào từ website nào. Khả năng Hallucination thấp do bị ép bám sát vào Context thu hồi được từ web.
*   **ChatGPT Search**: Tín hiệu đáng tin ở mức khá. Đôi khi model trộn lẫn kiến thức pre-training (đã học từ trước) với kiến thức Search được, khiến việc xác minh (verify) khó khăn hơn nếu câu trả lời không có trích dẫn rõ ràng.

## S4 — Business Signal
*   **Giá trị cốt lõi**:
    *   Perplexity ($20/tháng): Tốc độ (Speed) và Tính xác thực (Capability).
    *   ChatGPT Plus ($20/tháng): Sự đa dụng (Capability - Code, Data, Search, Voice).
*   **Mức giá so với Value**: Cả hai đều có gói Free cực kỳ hào phóng (giúp mở rộng phễu). Gói Pro $20/tháng là chuẩn mực của ngành B2C SaaS.

## S5 — Product Judgment

### S5.1 Verdict
*   **Perplexity**: **Strong** (Trong ngách Research/Search chuyên sâu).
*   **ChatGPT Search**: **Strong** (Cho mục đích sử dụng đa dụng hàng ngày).

### S5.2 User base + tăng trưởng
*   **Perplexity**: ~10-15 triệu MAU (Ước tính đầu 2024). Tăng trưởng nhanh nhưng tệp người dùng vẫn nhỏ so với Big Tech.
*   **ChatGPT**: Hơn 200 triệu WAU (Đang thống trị thị trường).

### S5.3 Doanh thu / pricing power
*   **Perplexity**: ~10-20 triệu USD ARR. Mô hình Freemium.
*   **ChatGPT**: >1.6 tỷ USD ARR. Khả năng định giá (Pricing power) cực cao nhờ hệ sinh thái khép kín.

### S5.4 Moat phân tích
*   **Perplexity**: *Data Moat* (Chỉ mục web theo thời gian thực tự build) và *Brand Moat* ("The AI Search Engine"). Tuy nhiên *Distribution Moat* rất yếu trước Google/Apple.
*   **ChatGPT**: *Brand Moat* khổng lồ (Synonym với AI). *Distribution Moat* đang mở rộng nhờ tích hợp mặc định vào iOS 18/macOS.

### S5.5 Data flywheel + feedback loop
*   **Perplexity**: Truy vấn người dùng -> Cải thiện thuật toán xếp hạng nguồn -> Trả lời chính xác hơn. Vòng lặp ngắn, ít compounding asset độc quyền từ user.
*   **ChatGPT**: Dữ liệu chat của user -> RLHF (Reinforcement Learning from Human Feedback) -> Cải thiện khả năng suy luận của model nền tảng (GPT-4/GPT-5). Compounding rất mạnh.

### S5.6 Niche Down + AI Feature Map
*   **Perplexity**: Niche rõ ràng (Information Retrieval). User Value: Tra cứu thông tin chính xác, có kiểm chứng.
*   **ChatGPT Search**: Không Niche Down. Là "Everything App".

### S5.7 Spark → Loop → System
Cả hai sản phẩm đều đã vượt qua Spark, đang ở giai đoạn **Loop** (người dùng quay lại hàng ngày) và tiến tới xây dựng **System** (Tích hợp API, Enterprise workspace).

### S5.8 Liên hệ Lab 1 case
Perplexity đang cố gắng disrupt Google Search (Marketplace thông tin lớn nhất thế giới) tương tự cách Midjourney đã làm với Shutterstock (Lab 1). Cả hai đều đánh vào **Shift 1 (Do the work for me)**: Thay vì bắt người dùng mở 10 đường link (Google) hoặc mở 100 trang ảnh (Shutterstock) để tự tổng hợp, AI làm thay việc đó và đưa ra kết quả cuối cùng.
