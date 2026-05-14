---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu: gộp toàn bộ quan sát ở Bước 1 thành **một bảng so sánh nén** — cùng cấu trúc 5 mục mà slide deck cuối sẽ dùng. Sau bước này, nhóm có "khung xương" của slide deck.

Lý do làm bước này: nhảy thẳng từ log sang slide deck dễ bị bỏ sót mục. Bảng so sánh ép nhóm trả lời từng mục cho cả 2 sản phẩm song song — phát hiện ngay nếu mục nào còn thiếu bằng chứng.

Quy tắc: mỗi ô của bảng dài tối đa 2 câu. Nếu ô nào để trống → quay lại `1-research-notes.md` đào thêm trước khi sang Bước 3.

## Quy trình 5 phút

```text
3 phút  — Điền bảng so sánh 5 mục (5 dòng × 2 cột)
1 phút  — Đánh dấu ô nào còn thiếu bằng chứng
1 phút  — Quyết định: cần test thêm hay đủ để sang slide?
```

---

## Bảng kiểm trước khi sang Bước 3

- [ ] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [ ] Mỗi nhận định đều có thể chỉ về ảnh / log trong `1-research-notes.md` làm bằng chứng.
- [ ] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [ ] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [ ] Còn ô nào thiếu bằng chứng → đã đánh dấu để Phase 3 đào thêm.

Sang `3-FINAL-analysis-outline.md` để dựng outline 5 mục đầy đủ (với S5 mở rộng 8 sub-mục) trước khi build slide.

## Phần A — Bảng so sánh 5 mục

| Mục                                                                                   | Sản phẩm A                                                                        | Sản phẩm B                                                                   |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính</sup> | Perplexity có entry chat search rõ ràng, trọng tâm vào citation.                  | Google Gemini Search xuất hiện trong Search, familiar với người dùng Google. |
| **S2 — Workflow Evidence**                                                            | Cần mở web app riêng, nhập prompt, copy/paste link nếu cần so sánh nhiều sự kiện. | Mở Search bình thường, ít friction chuyển đổi vì đã quen Google Search.      |
| **S3 — Output & Trust**                                                               | Output có citation rõ ràng, trust tốt cho research.                               | Output dễ tiếp cận, nhưng citation ít rõ ràng hơn.                           |
| **S4 — Business Signal**                                                              | Freemium + Pro Search $20/tháng; paywall rõ ràng.                                 | Miễn phí cơ bản, Gemini Advanced $20/tháng; distribution lớn.                |
| **S5 — Product Judgment**                                                             | Promising — tốt cho niche research, nhưng distribution yếu.                       | Strong — tận dụng ecosystem Google, phù hợp đại trà search AI.               |

---

## Phần B — Đối chiếu 3 friction areas

- **Physical load**: Perplexity cần mở web app riêng và copy/paste nếu so sánh nhiều event; Gemini Search giảm friction vì nằm trong Google Search quen thuộc.
- **Cognitive burden**: Perplexity yêu cầu người dùng đánh giá nguồn citation; Gemini Search dễ dùng hơn với câu trả lời trực tiếp.
- **User workarounds**: Với Perplexity, user cần lưu nhiều link và kiểm chứng; với Gemini Search, user có thể quay lại Google Search nhanh hơn.

---

## Phần C — Đối chiếu 6 trust signals

| Tín hiệu đáng tin                                              | Sản phẩm A                 | Sản phẩm B                      |
| -------------------------------------------------------------- | -------------------------- | ------------------------------- |
| 1. Dẫn nguồn (citation) — link mở được, đúng nội dung          | Có — citation rõ ràng      | Một phần — trích dẫn kém rõ hơn |
| 2. Disclaimer khi không chắc                                   | Có / có ghi chú kiểm chứng | Có / có cảnh báo, nhưng ít      |
| 3. Fallback / dừng lại khi out-of-scope                        | Có                         | Có                              |
| 4. Consistency — chạy 2 lần cùng prompt, output có giống không | Một phần — cần test thêm   | Một phần — cần test thêm        |
| 5. User control — sửa lại, dừng, regenerate, undo              | Có                         | Có                              |
| 6. Explanation — giải thích "tại sao AI nói thế"               | Ít hơn                     | Ít hơn                          |

---

## Phần D — Định vị 2 sản phẩm trên Cost-Capability-Speed

- **Sản phẩm A nghiêng về**: mạnh-đắt — giá $20/tháng nhưng có citation rõ, phù hợp user research.
- **Sản phẩm B nghiêng về**: cân bằng — free tier lớn, premium tier $20/tháng, lợi thế distribution.

---

## Phần E — Verdict sơ bộ

- **Sản phẩm A — verdict sơ bộ**: Promising
  - Lý do 1 câu: Perplexity có trust tốt cho người cần citation, nhưng thiếu distribution.
- **Sản phẩm B — verdict sơ bộ**: Strong
  - Lý do 1 câu: Google Gemini Search dễ tiếp cận, phù hợp đa số người dùng search.
