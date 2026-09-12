# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Phạm Cường Quốc
- Mã học viên: 2A202602469
- Nhóm: 6ae - Zone A
- Candidate problem nhóm chọn: Sinh viên năm 4 làm đồ án / khóa luận mất ~145 phút mỗi lượt để đọc một paper tiếng Anh 25-35 trang trước buổi họp tiến độ (2 lượt/tuần); bottleneck ở bước đọc kỹ + tra thuật ngữ. Mức chọn: Workflow, quyết định Go có điều kiện (pilot 2 tuần).

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems theo 4 lăng kính từ việc hằng tuần của mình (khóa luận, đồ án nhóm, xin việc); chọn top 3 Card: deadline rải rác nhiều kênh, đọc paper cho related work, họp nhóm không có biên bản | Đưa 3 candidate (#1, #2, #3) vào bảng 3.1 của nhóm |
| Pitch Problem Card | Pitch Card #1 (deadline ở LMS / email / Discord / Zalo, ~35 phút/tuần, bottleneck ở bước dò chat ~15'); tự đưa 2 câu hỏi cho nhóm challenge: "1 kênh #announcements có đủ không?" và "Zalo phải paste tay thì còn tiết kiệm không?" | Nhóm gom Card #1 vào cụm B và kết luận đúng như câu hỏi mình đặt ra: nên giải bằng No AI / Rule, không deep-dive AI |
| Challenge bài của bạn khác | Tôi challenge bài #10 của Bảo bằng câu hỏi: “210 phút là số liệu đã bấm giờ thực tế hay chỉ là ước lượng?” Tôi muốn kiểm tra xem baseline có đủ chắc để đưa vào so sánh hay chưa. | Bảo cần làm rõ nguồn của con số 210 phút. Nhóm nhận ra khi validation chưa có log hoặc đo thời gian thực tế thì không nên xem các con số ước lượng là evidence mạnh. |
| Gom trùng / cluster | Gom 18 candidate của 6 người thành 6 cụm (A-F); xếp #16 của Vinh vào cụm D nhưng ghi rõ actor là kỹ sư / PM nên không cộng vào evidence của #10; tạo cụm E (tra cứu / truy vết) và F (cảnh báo sớm) cho bài của Thiên và Vinh | Nhật ký hội tụ đủ 18 → 6 cụm → 3 shortlist → 1 |
| Chọn candidate problem | Card #2 của mình (đọc paper cho related work) trùng với #6 của Đại và #7 của Phi → góp phần tạo cụm A, cụm duy nhất có 3 người độc lập cùng gặp | Cụm A được chọn (34 điểm, cao nhất) |
| Validation / research | Tìm 5 nguồn / công cụ (3-pass của Keshav, Semantic Reader, NotebookLM, Elicit, Zotero), tự mở từng link kiểm; ghi rõ khoảng trống của từng cái; viết research takeaway "không build tool mới, chỉ thiết kế quy trình + prompt + checklist" | Nhóm chuyển từ ý "build tool" sang dùng công cụ có sẵn → pilot gần như không tốn chi phí build. Validation 4.1 (phỏng vấn) vẫn chưa xong |
| Workflow nhóm | Đại vẽ chính; mình đưa phương pháp 3-pass (từ research) vào bước 2 của future workflow thành bước Rule / process "Pass 1: lướt tiêu đề, abstract, heading, kết luận" trước khi dùng AI | Future workflow có lớp Rule làm nền trước bước AI; 3-pass cũng thành phương án rollback khi AI không giúp giảm thời gian |
| Problem Statement | Viết v0, nhờ Claude phản biện, rồi sửa thành v1: thêm baseline ~145 phút × 2 lượt/tuần, đổi "vẫn hiểu bài" thành bài tự kiểm 5 câu, tách boundary thành "AI được làm / không được làm" | PS v1 có metric trước / sau + guard metric hiểu bài |
| Rule / Workflow / Agent | Ủng hộ Workflow từ đầu: chỉ có một input (paper), đường đi cố định, AI chỉ cần ở bước giải thích thuật ngữ; Agent tự đọc + soạn nội dung họp là làm thay đúng việc SV cần học | Nhóm chọn Workflow, giữ Rule (3-pass + glossary) làm nền và rollback |
| Decision | Viết phần Go có điều kiện + exit / rollback (3 ngưỡng dừng) trong bản tổng hợp | Decision gắn điều kiện: validation 4.1 phản bác pain → chuyển Not Yet |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Bảng research 4.2 và takeaway "không build tool, chỉ thiết kế quy trình + prompt + checklist", cùng bước 3-pass
ở bước 2 của future workflow. Ngoài ra là bản tổng hợp 18 candidate của 6 người thành 6 cụm → shortlist → 1 bài.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ Claude gợi ý và soạn nháp danh sách problem theo 4 lăng kính cho bối cảnh SV năm 4 | Gợi ý được các ý mình có gặp thật: deadline nhiều kênh (#1), đọc paper (#2), biên bản họp (#3), điều kiện tốt nghiệp (#10) | Đưa ý quá rộng: "trợ lý AI quản lý toàn bộ việc học"; ý không phải pain của mình: "chatbot hỏi đáp quy chế trường"; số liệu trong nháp là ước lượng, chưa bấm giờ | Bỏ 2 ý không có trải nghiệm thật; chỉ giữ dòng có actor + số; ghi nhận số là ước lượng |
| Problem Card | Prompt "chỉ ra điểm yếu, đừng khen" cho Card #1 | Chỉ ra 4 điểm yếu thật: baseline 35' chưa bấm giờ, actor rộng, Zalo khó export, process fix có thể giải phần lớn | Không biết bối cảnh lớp mình (kênh nào thật sự có thông báo) | Thu hẹp actor thành "SV học 4-5 môn, nhận thông báo từ 6-8 kênh"; để Rule xử lý LMS + email trước; thêm fallback lấy LMS làm nguồn chính thức; đưa 2 câu hỏi yếu nhất vào phần nhờ nhóm challenge |
| Tổng hợp bản nhóm | Nhờ Claude gom bảng top 3 của 6 thành viên vào bảng 3.1, xếp cụm, viết lý do loại | Gom nhanh 18 candidate, nhận ra pattern chung để tạo cụm E / F | Tự điền vai trò cho Thiên và Vinh bằng suy đoán từ nội dung bài, không phải từ việc hai bạn thật sự làm | Giữ phần gom cụm và lý do loại; vai trò của Thiên, Vinh phải được hai bạn xác nhận trước khi nộp |
| Workflow | Nhờ AI chuyển bản workflow Đại vẽ thành sơ đồ ASCII + bảng Bước / Actor / Input / Output / Thời gian | Trình bày gọn, tách rõ handoff, bottleneck, human boundary và fallback cho từng bước | Thời gian từng bước (bước 3 ~90') là số ước lượng, chưa tách từ log bấm giờ của Phi; AI điền số cho đủ ô chứ không biết số thật | Đánh dấu "[thay bằng số tách bước từ log của Phi]" ở phần bottleneck; tự thêm bước 3-pass làm lớp Rule trước bước AI |
| Research | Dùng AI + search tìm công cụ đã có cho bài đọc paper, sau đó tự mở từng link | Tìm nhanh được Semantic Reader (tra thuật ngữ ngay trong paper) — đúng bottleneck của nhóm | Thông tin dễ lỗi thời (NotebookLM đã đổi tên); con số % độ chính xác của Elicit chỉ là claim của nhà cung cấp | Chỉ giữ link chính thức kiểm được; không đưa số % của vendor vào bài; loại Elicit vì thiên về review nhiều paper, không khớp bottleneck |
| Problem Statement | Nhờ Claude phản biện PS v0 | Chỉ đúng chỗ mơ hồ: Impact / Success Metric không có số, "vẫn hiểu bài" không đo được, boundary "AI không đọc thay" chưa nói AI được làm gì | Chỉ ra được field thiếu số nhưng không tự có số thật: baseline ~145 phút vẫn phải lấy từ log của Phi, AI không kiểm được | Thêm baseline, bài tự kiểm 5 câu (≥ 4/5), guard metric "GVHD phát hiện hiểu sai: 0 lần", tách boundary làm / không làm |
| Rule / Workflow / Agent | Không dùng | — | — | Tự lập luận: một input, đường đi cố định → Workflow; nhóm tự chấm và chốt, không để AI quyết thay |
| Decision | Nhờ AI góp ý phần Go, pilot nhỏ nhất và exit / rollback | Gợi ý cấu trúc pilot (data, cách chạy tay, đo 3 số) và đặt ngưỡng dừng cụ thể | Nghiêng về "Go" thẳng dù validation 4.1 (phỏng vấn ngoài nhóm) chưa làm | Đổi thành "Go có điều kiện": validation phản bác pain → chuyển Not Yet; giữ 3 ngưỡng rollback về 3-pass + glossary |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

<!--
DỮ KIỆN THẬT ĐỂ TỰ VIẾT (xóa khối này trước khi nộp):
- Mình pitch Card #1 (deadline) nhưng chính mình đã nghi "1 kênh thông báo là đủ"; nhóm cũng kết luận cụm B là No AI / Rule
  → bài mình muốn pitch nhất lại không phải bài đáng làm AI nhất. Card #2 (xếp hạng 2) mới là bài được chọn vì trùng Đại, Phi.
- Nghe bài của Thiên (IQC, TikTok Shop) và Vinh (CI/CD log, PR review): cả hai tự nhận "chưa chắc cần AI",
  baseline non-AI (safety stock, database, linter, regex) có thể đã đủ → pattern chung: dữ liệu phân tán ≠ cần AI.
- Solution-first: mình ủng hộ Workflow từ đầu; phương án Agent tự đọc paper + soạn nội dung họp bị loại vì làm thay
  việc SV cần học. Research cho thấy công cụ có sẵn đã đủ → "build" chỉ còn prompt + checklist.
- Challenge Bảo #10 "210 phút bấm giờ hay ước lượng?" → nhóm nhận ra số ước lượng không phải evidence mạnh
  (và chính Card #1 của mình cũng bị AI chỉ ra baseline 35' chưa bấm giờ).
- Khó nhất khi viết PS: metric "vẫn hiểu bài" — thời gian đo dễ, hiểu bài khó đo → thành bài tự kiểm 5 câu.
- Nếu làm lại: challenge mạnh hơn ở validation — Go vẫn dựa trên baseline của một người (Phi), phỏng vấn ngoài nhóm
  chưa làm; số 145 phút và ~90 phút bước 3 chưa tách từ log thật. Bài tự kiểm 5 câu do chính người đọc chấm → dễ thiên vị.
-->

**Reflection:**

```text
[TỰ VIẾT 8-12 câu bằng lời của mình, dựa trên các dữ kiện ở khối ghi chú phía trên.]
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards (10 problems, 3 Cards có workflow trước / sau)
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì — còn đoạn mục 3
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
