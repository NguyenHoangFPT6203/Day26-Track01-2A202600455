---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5 với S5 mở rộng 8 sub-mục)

Mục tiêu: dựng outline đầy đủ cho slide deck Analysis Report ngay trong file markdown — viết hết nội dung 5 mục ở đây trước, sau đó copy sang slide (pptx / Keynote / Google Slides). Không build slide trước khi outline xong.

Lý do làm bước này: dựng thẳng slide từ log dễ bị thiếu mục hoặc bị "đẹp ngoài rỗng trong". Outline markdown ép nhóm trả lời từng câu hỏi trước khi nghĩ về thiết kế slide. Khi giảng viên / nhóm khác hỏi "vì sao bạn xếp Sản phẩm A là Promising?" — câu trả lời đã có sẵn trong outline.

Quy tắc: mỗi nhận định trong outline phải nối được về bằng chứng cụ thể (ảnh / log / số liệu công khai). Nếu một sub-mục để trống → quay lại `1-research-notes.md` đào thêm trước khi sang slide.

## Quy trình 15 phút

```text
2 phút  — Đọc lại 2-comparison-table.md để có context
8 phút  — Điền outline 5 mục (S1 → S5)
4 phút  — Riêng cho S5: mở rộng 8 sub-mục (S5.1 → S5.8)
1 phút  — Đối chiếu bảng kiểm trước khi build slide
```

> Sau 15 phút outline + đối chiếu, mới mở pptx / Google Slides / Keynote và copy nội dung sang. Slide deck export thành `analysis-report.pdf` ở cùng folder này.

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**: 2A202600455 — Nguyễn Việt Hoàng + 2A202600381 — Lê Quang Minh
- **Ngành chọn**: A — Tìm kiếm
- **Nhiệm vụ chung đã test**: Tìm sự kiện công nghệ ở TP.HCM trong 2 tuần tới và liệt kê cụ thể 3 sự kiện kèm link nguồn.
- **Sản phẩm A** (tên + URL): Perplexity — https://www.perplexity.ai
- **Sản phẩm B** (tên + URL): Google Gemini Search — https://gemini.google.com/search
- **Câu prompt chính xác đã dùng**: "Có sự kiện công nghệ nào ở TP.HCM trong 2 tuần tới không? Liệt kê cụ thể 3 sự kiện, tên sự kiện, ngày giờ, địa điểm, và link nguồn."

---

## S1 — Product Moment (slide 1-2)

Mục đích: định danh rõ 2 sản phẩm, nhiệm vụ chung, điểm gặp đầu (entry point).

### S1.1 — Bảng so sánh nhanh

| Yếu tố              | Sản phẩm A                                  | Sản phẩm B                                              |
| ------------------- | ------------------------------------------- | ------------------------------------------------------- |
| Tên + URL           | Perplexity — https://www.perplexity.ai      | Google Gemini Search — https://gemini.google.com/search |
| Entry point         | Chat search interface, rõ ràng prompt input | Google Search quen thuộc với tuỳ chọn Gemini            |
| Ý định người dùng   | Tìm event công nghệ và dẫn nguồn            | Tìm event công nghệ nhanh, dễ đọc                       |
| Surface chính       | Chat-like search                            | Search bar + answer panel                               |
| Đăng nhập / paywall | Có paywall Pro Search                       | Miễn phí cho Google account                             |

### S1.2 — Bằng chứng (ảnh tham chiếu)

- `screenshots/product-A-1-entry.png` — entry chat search của Perplexity.
- `screenshots/product-B-1-entry.png` — entry Google Gemini Search.

### S1.3 — Nhận định so sánh entry point (2-3 câu)

Perplexity tạo cảm giác chuyên sâu hơn với citation ngay từ đầu, trong khi Google Gemini Search cho trải nghiệm search quen thuộc và dễ tiếp cận với số đông.

---

## S2 — Workflow Evidence (slide 3-4)

Mục đích: hiển thị luồng người dùng + 3 friction areas (Lens 3).

### S2.1 — Luồng người dùng (trước / trong / sau khi dùng AI)

TRƯỚC khi gặp AI:

- Người dùng cần tìm event công nghệ và muốn link nguồn chính xác.

TRONG khi dùng Sản phẩm A:

1. Vào Perplexity.
2. Dán prompt vào ô chat.
3. Nhận answer có citation, kiểm tra link.

TRONG khi dùng Sản phẩm B:

1. Mở Google Search.
2. Dán prompt vào thanh tìm kiếm.
3. Nhận answer Gemini và truy xuất link Google.

SAU khi dùng AI:

- Người dùng lưu lại 3 event, copy link và đánh giá tính chính xác.

### S2.2 — 3 Friction Areas (Lens 3)

| Friction         | Sản phẩm A                                    | Sản phẩm B                                   |
| ---------------- | --------------------------------------------- | -------------------------------------------- |
| Physical load    | Cần mở web app riêng và copy/paste để so sánh | Nằm trong Search quen thuộc, ít tab hơn      |
| Cognitive burden | Cần đánh giá citation và độ chính xác         | Dễ đọc nhưng cần kiểm chứng thêm             |
| User workarounds | Có thể mở thêm tab để kiểm tra link           | Có thể cần search thêm nếu nội dung không rõ |

### S2.3 — Bằng chứng

- `screenshots/product-A-2-input.png`, `screenshots/product-A-3-output.png`
- `screenshots/product-B-2-input.png`, `screenshots/product-B-3-output.png`

### S2.4 — Nhận định: sản phẩm nào giảm friction tốt hơn? Tại sao? (3-4 câu)

Google Gemini Search giảm friction tốt hơn với trải nghiệm Search quen thuộc và không yêu cầu mở app mới; Perplexity mạnh ở output trust nhưng có friction vì phải chuyển đổi kênh.

---

## S3 — Output & Trust (slide 5-6)

Mục đích: đánh giá chất lượng output + 6 tín hiệu đáng tin.

### S3.1 — Chất lượng output

- **Sản phẩm A**: Output trả lời cụ thể, có citation; phù hợp user cần file nguồn.
- **Sản phẩm B**: Output nhanh, thân thiện, nhưng citation ít rõ ràng hơn.

### S3.2 — 6 Tín hiệu đáng tin (đối chiếu)

| Tín hiệu     | Sản phẩm A | Sản phẩm B |
| ------------ | ---------- | ---------- |
| Dẫn nguồn    | Có         | Một phần   |
| Disclaimer   | Có         | Có         |
| Fallback     | Có         | Có         |
| Consistency  | Một phần   | Một phần   |
| User control | Có         | Có         |
| Explanation  | Ít hơn     | Ít hơn     |

### S3.3 — Nhận định: sản phẩm nào tạo trust mạnh hơn? Vì sao? (3-4 câu)

Perplexity tạo trust tốt hơn nhờ citation rõ ràng, nhưng Google Gemini Search có trust về hệ sinh thái và độ tin cậy của Google. Perplexity phải chứng minh giá trị citation đủ cao để người dùng trả tiền.

---

## S4 — Business Signal (slide 7)

Mục đích: định vị 2 sản phẩm trên Cost-Capability-Speed + pricing pattern.

### S4.1 — Định vị tam giác

- **Sản phẩm A**: mạnh-đắt — giá $20/tháng nhưng cung cấp citation và search AI chuyên sâu.
- **Sản phẩm B**: cân bằng — miễn phí cơ bản + premium tier, phù hợp đông đảo user.

### S4.2 — Pricing pattern

| Yếu tố                  | Sản phẩm A                          | Sản phẩm B              |
| ----------------------- | ----------------------------------- | ----------------------- |
| Mô hình giá             | Freemium + Pro Search               | Freemium + Advanced     |
| Giá entry               | Free                                | Free                    |
| Giá trả phí             | $20/tháng                           | $20/tháng               |
| Paywall xuất hiện ở đâu | Tới giới hạn hoặc tính năng cao cấp | Khi cần Gemini Advanced |

### S4.3 — Nhận định: chiến lược kinh doanh của 2 sản phẩm khác nhau thế nào? (2-3 câu)

Perplexity định vị vào người dùng research và trả tiền cho citation, trong khi Google Gemini Search tập trung vào lượng user lớn với tầng free và upsell premium.

---

## S5 — Product Judgment (slide 8-12)

Mục đích: ra verdict + vận dụng 4 Lens + Spark/Loop/System + Niche/Feature Map + liên hệ Lab 1.

### S5.1 — Verdict

- **Perplexity**: Promising — giữ niche citation, nhưng cần tăng distribution.
- **Google Gemini Search**: Strong — lợi thế System lớn hơn.

### S5.2 — User base + tăng trưởng

- Perplexity: chưa có số liệu công khai rõ về MAU/DAU | nguồn: không có.
- Google Gemini Search: hưởng lợi từ Google Search, nhưng chưa có số liệu public cụ thể.

### S5.3 — Doanh thu / pricing power

- Perplexity: pricing $20/tháng; chưa công bố ARR/MRR.
- Google Gemini Search: free tier lớn, premium $20/tháng; pricing power dựa vào hệ sinh thái.

### S5.4 — Moat phân tích

| Moat           | Perplexity | Google Gemini Search |
| -------------- | ---------- | -------------------- |
| Data           | Trung bình | Mạnh                 |
| Network        | Yếu        | Mạnh                 |
| Switching cost | Thấp       | Trung bình           |
| Brand          | Trung bình | Mạnh                 |
| Distribution   | Yếu        | Mạnh                 |

### S5.5 — Data flywheel + feedback loop

- Perplexity: loop có thể phát triển nếu dùng feedback citation, nhưng chưa rõ compounding.
- Google Gemini Search: loop mạnh nhờ lượng truy vấn search lớn.

### S5.6 — Niche Down + AI Feature Map

- Perplexity: niche research, citation. User Value cao, User Alignment trung bình, Business Value trung bình.
- Google Gemini Search: niche rộng, user phổ thông. User Value cao, User Alignment cao, Business Value cao.

### S5.7 — Spark → Loop → System

- Perplexity: Spark — còn cần hoàn thiện loop.
- Google Gemini Search: System — đã có hệ sinh thái lớn.

### S5.8 — Liên hệ Lab 1

- Perplexity tương tự case Lab 1 vì cùng bị Big Tech Search AI áp lực.
- Google Gemini Search là một trong Big Tech gây disruption.

---

## Bảng kiểm trước khi build slide

- [ ] S1 → S4 đã điền đầy đủ.
- [ ] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành.
- [ ] S5.2 → S5.5 đã hoàn thành hoặc ghi rõ không có nguồn.
- [ ] Mỗi nhận định nối được về ảnh / log.
- [ ] Verdict nhất quán với moat và Spark/Loop/System.
