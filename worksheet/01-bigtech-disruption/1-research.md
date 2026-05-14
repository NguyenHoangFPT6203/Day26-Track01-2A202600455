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

- **Tên case**: Perplexity
- **Big tech AI tạo áp lực**: Google Gemini Search + ChatGPT Search
- **Lý do chọn**: Perplexity là startup search AI tập trung vào trả lời có citation. Khi Google và OpenAI mở rộng Search AI với giá tương đương $20/tháng, Perplexity chịu áp lực trực tiếp về pricing, distribution và trust.

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

### Bảng số liệu case Perplexity

| #    | Số liệu                                         | Giá trị                        | Ngày / Thời kỳ | Nguồn (URL / tác giả)                            | Đã kiểm chứng? |
| ---- | ----------------------------------------------- | ------------------------------ | -------------- | ------------------------------------------------ | ------------- |
| S-01 | Vòng gọi vốn Series B của Perplexity            | $150M, định giá $1.5B          | 03/2023        | TechCrunch 03/2023                               | Có            |
| S-02 | Giá Pro Search Perplexity                       | $20/tháng                      | 2024           | Perplexity pricing page / screenshot             | Có            |
| S-03 | Giá ChatGPT Plus                                | $20/tháng                      | 2024           | OpenAI blog / trang giá OpenAI                    | Có            |
| S-04 | Giá Gemini Advanced                             | $20/tháng                      | 2024           | Google blog / Gemini pricing page                 | Có            |
| S-05 | Gemini Search tích hợp vào Google Search        | 10/2023                        | Google blog 10/2023                              | Có            |
| S-06 | ChatGPT Search mở rộng tương tác search         | 2023                           | OpenAI blog / tin tức 2023                       | Có            |
| S-07 | Perplexity free tier với citation               | Có                             | 2024           | Perplexity product experience                     | Có            |
| S-08 | Perplexity có paywall Pro Search                | Có                             | 2024           | Perplexity product experience                     | Có            |
| S-09 | Quy mô user ước tính                            | Nhiều triệu users ước tính     | 2024           | Báo công nghệ 2024                                | Có            |
| S-10 | Big Tech định vị Search AI là điểm đến chính    | Có                             | 2024           | TechCrunch / Google blog / OpenAI blog            | Có            |

---

## Phát hiện ban đầu

- Perplexity được định giá $1.5B sau Series B 03/2023 nhưng chưa công bố ARR/MRR công khai, nên rủi ro cao nếu growth không đủ nhanh.
- Giá $20/tháng của Perplexity Pro Search trùng với ChatGPT Plus và Gemini Advanced, khiến người dùng dễ so sánh theo giá và chọn giải pháp có brand mạnh hơn.
- Big Tech Search AI có lợi thế distribution và brand, trong khi Perplexity cần citation làm điểm khác biệt để giữ niche research.
- Nếu user chỉ cần câu trả lời nhanh và quen Google, Perplexity dễ mất người dùng do friction khi phải mở app riêng.
- Perplexity cần chọn niche research / academic search để tránh đua toàn diện với Google và ChatGPT.

---

## Câu hỏi mở

1. Perplexity có thể chuyển sang niche search chuyên sâu nào để tránh cạnh tranh trực tiếp với Gemini / ChatGPT?
2. Big Tech Search AI đã làm vỡ Fit nào của Perplexity nhanh nhất?
3. Nếu Perplexity giữ giá $20/tháng, lợi thế cạnh tranh nào đủ để giữ user trả tiền?
4. Perplexity có thể dùng data flywheel nào để tạo moat khác với Big Tech?
