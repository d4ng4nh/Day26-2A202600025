---
artifact: 1 — Tự nghiên cứu case
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Chọn case + tìm số liệu + nguồn
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác trong buổi)
input: prompts/01-research-case.md
nop-cuoi: Không — file trung gian
---

# 1 — Tự nghiên cứu: tìm 1 case bị big tech AI ảnh hưởng + số liệu thật

Mục tiêu: bạn tự chọn 1 sản phẩm hoặc 1 công ty bị ảnh hưởng nặng sau khi big tech AI (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...) ra mắt tính năng tương tự. Tự tìm số liệu cụ thể về case đó từ nguồn công khai. Mỗi số liệu phải có nguồn (URL + tên báo/tổ chức + ngày tháng). Lab 1 là phần cá nhân — mỗi học viên tự chọn case riêng và tự làm phần research trong repo cá nhân.

Lý do làm bước này: phân tích chỉ có sức nặng khi đứng trên số liệu thật. Bạn cần tự tìm ít nhất 8-10 số liệu cụ thể để có nền tảng phản biện cho 4 câu hỏi ở phase 2.

Quy tắc: **không có số liệu = không có nhận định**. Học viên tự tìm số liệu cho case mình chọn. Mỗi nhận định phải có nguồn (URL + ngày).

## Bước 0 — Chọn case (5 phút đầu)

Trước khi tìm số liệu, bạn quyết định case nào:

1. Sản phẩm/công ty bạn chọn là gì?
2. Big tech AI nào ra tính năng tương tự gây ảnh hưởng? (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...)
3. Vì sao bạn chọn case này? (Có số liệu công khai? Có mốc thời gian rõ? Có liên hệ với ngành bạn quan tâm?)

Ghi câu trả lời ngắn vào ô dưới đây trước khi bắt đầu tìm số liệu.

- **Tên case**: Stack Overflow (Nền tảng Q&A số 1 dành cho kỹ sư phần mềm, chuyên gia bảo mật và nhà phát triển).
- **Big tech AI tạo áp lực**: OpenAI (ra mắt ChatGPT tháng 11/2022) và Microsoft (ra mắt GitHub Copilot phiên bản chat đầu 2023).
- **Lý do chọn**: Đây là ví dụ điển hình nhất về một nền tảng bị AI tạo sinh thay thế trực tiếp hành vi người dùng, có số liệu sụt giảm traffic và sa thải rõ ràng.

## Quy trình 15 phút

```text
5 phút  — Chọn case + xác định 4 nhóm số liệu cần tìm cho case của mình
8 phút  — Tự tìm số liệu trên các nguồn chính (báo chí công nghệ, báo cáo tài chính, blog chính thức...)
2 phút  — Rà lại bảng số liệu, đánh dấu số chưa kiểm chứng
```

---

## Phần A — Các nhóm số liệu cần tìm

Bạn tự tìm đủ 4 nhóm số liệu dưới đây cho case mình chọn. Tên nhóm giữ nguyên — nội dung cụ thể bạn tự điền theo case.

### Nhóm 1 — Quy mô trước & sau (cổ phiếu, doanh thu, người dùng)

Tuỳ case, chọn các chỉ số phù hợp:

- Cổ phiếu / vốn hoá: đỉnh cao + hiện tại (nếu là công ty niêm yết).
- Doanh thu: trước khi big tech AI ra tính năng + sau đó (so sánh quý / năm).
- Người dùng trả tiền / hoạt động: đỉnh + hiện tại.
- Tỷ lệ giảm tổng cộng (%).

Nguồn nên dùng:

- Yahoo Finance, MacroTrends, Google Finance — cho công ty niêm yết.
- Báo cáo quý / 10-K filing (Investor Relations của chính công ty).
- Báo công nghệ: TechCrunch, CNBC, Bloomberg, Reuters, FT.

### Nhóm 2 — Mốc thời gian big tech AI ra tính năng tương tự

Tìm:

- Tính năng AI cụ thể của big tech (vd: ChatGPT, Gemini Code Assist, Copilot, …).
- Ngày ra mắt + ngày mở rộng người dùng.
- Tốc độ phổ cập của tính năng đó (số người dùng sau 6 tháng, 1 năm).
- Mức độ trùng lặp với sản phẩm của case bạn chọn (tính năng nào trùng?).

Nguồn nên dùng:

- Blog chính thức của big tech (OpenAI blog, Anthropic blog, Google blog, GitHub blog).
- Báo công nghệ.

### Nhóm 3 — Phản ứng của sản phẩm / công ty sau khi big tech AI ra mắt

Tìm:

- Sản phẩm AI / tính năng mới mà công ty đã ra: tên + ngày ra mắt.
- Đối tác AI: dùng model nào dưới mui xe.
- Thời gian từ khi big tech AI ra mắt đến khi công ty này có sản phẩm AI: ___ tháng.
- Đợt sa thải / cắt giảm / tái cơ cấu (nếu có): số người + tỷ lệ + ngày.
- Thông báo delisting / mua bán sáp nhập / đóng cửa (nếu có).

Nguồn nên dùng:

- Báo cáo quý của công ty.
- Báo công nghệ và báo kinh doanh.
- TechCrunch, Bloomberg, CNBC.

### Nhóm 4 — Đối thủ AI thay thế

Tìm:

- Big tech AI thay thế sản phẩm này ở use case cụ thể nào?
- Có đối thủ startup khác cũng đang thay thế không (tên + ngày ra mắt + giá)?
- So sánh giá: sản phẩm gốc vs big tech AI vs startup khác (giá/tháng).

Nguồn nên dùng:

- Trang giá chính thức của từng sản phẩm.
- Báo công nghệ.

---

## Phần B — Bảng tổng hợp số liệu

Sau khi tìm đủ 4 nhóm số liệu, bạn gộp vào bảng dưới đây. Mục tiêu: tối thiểu 8-10 số liệu có nguồn cụ thể.

### Bảng số liệu case Stack Overflow

| # | Số liệu | Giá trị | Ngày / Thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
|---|---|---|---|---|---|
| S-01 | Lượng truy cập website giảm | 14% đến 16% | Nửa đầu năm 2023 | [Similarweb](https://www.similarweb.com/blog/insights/ai-news/stack-overflow-chatgpt/) | Có |
| S-02 | Sa thải nhân sự (do lợi nhuận giảm) | 28% (~160 người) | Tháng 10/2023 | [Stack Overflow Blog](https://stackoverflow.blog/2023/10/16/a-message-from-prashanth-chandrasekar-ceo-stack-overflow/) | Có |
| S-03 | Big tech AI ra tính năng tương tự | ChatGPT | Tháng 11/2022 | Nguồn chung | Có |
| S-04 | Big tech AI ra tính năng code | GitHub Copilot Chat | Đầu 2023 | Nguồn chung | Có |

Bổ sung dòng nếu bạn tìm thêm số liệu nào liên quan.

---

## Phần C — Kiểm chứng nguồn

Trước khi chuyển sang phân tích, rà lại từng số liệu:

### Checklist kiểm chứng

- [x] Mỗi số liệu có URL nguồn cụ thể.
- [x] URL mở được, không 404.
- [x] Nội dung URL có khớp với số liệu mình ghi (ít nhất là cùng đơn vị, cùng năm).
- [x] Với số liệu quan trọng (quy mô, doanh thu, ngày tháng), kiểm chứng chéo 2 nguồn độc lập.
- [ ] Nếu chưa chắc, đánh dấu `[CHƯA KIỂM CHỨNG]` thay vì xoá.

### Quy tắc loại nguồn

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 — Nguồn gốc | Báo cáo tài chính, thông báo chính thức, hồ sơ pháp lý | 10-K filings, SEC filings, blog công ty |
| 2 — Báo lớn | Báo chí công nghệ/kinh doanh uy tín | CNBC, Bloomberg, TechCrunch, Reuters, FT |
| 3 — Báo cáo phân tích | Báo cáo tài chính độc lập | MacroTrends, Yahoo Finance, Google Finance |
| 4 — Tránh dùng | Bài đăng cá nhân, blog không nguồn, mạng xã hội | Reddit posts, Medium articles không có citation |

### Cảnh báo

AI có thể bịa cả nguồn — đặc biệt khi bạn hỏi AI số liệu thay vì tự tìm. Nếu dùng AI để gợi ý nơi tìm, vẫn phải tự mở URL và xác minh.

---

## Phần D — Phát hiện ban đầu

Sau khi có số liệu, ghi nhanh 3-5 phát hiện đáng chú ý nhất. Đây chưa phải nhận định cuối — chỉ là quan sát.

Phát hiện của bạn:

- Lượng truy cập website của Stack Overflow đã giảm 14% đến 16% chỉ trong nửa đầu năm 2023 (ngay sau khi ChatGPT bùng nổ).
- Tác động kinh doanh rất rõ rệt khi vào tháng 10/2023, Stack Overflow buộc phải sa thải 28% nhân sự (khoảng 160 người) do lợi nhuận mảng kinh doanh truyền thống bị thu hẹp đáng kể.
- Sự ra mắt của ChatGPT và GitHub Copilot trùng khớp với thời điểm bắt đầu đà suy giảm của Stack Overflow.

---

## Phần E — Câu hỏi mở (cho phân tích Phần 2)

Trước khi chuyển sang `2-analysis.md`, bạn liệt kê các câu hỏi cần đào sâu:

- Câu hỏi 1: Giả định nào về việc chia sẻ kiến thức cộng đồng của Stack Overflow không còn đúng trong kỷ nguyên AI?
- Câu hỏi 2: Kỳ vọng của lập trình viên về việc tìm kiếm và sửa lỗi code đã thay đổi thế nào?
- Câu hỏi 3: Stack Overflow có thể làm gì để pivot mô hình kinh doanh truyền thống?

Sau bước này, chuyển sang `2-analysis.md` để vận dụng Lens 1 (Customer Expectations + Four Fits) vào case bạn chọn.
