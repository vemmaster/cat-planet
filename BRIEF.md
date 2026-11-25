# Brief — Hành Tinh Mèo (Cat Planet)

> Cập nhật: 25/11/2026

Bản brief chuẩn duy nhất của dự án. Mọi quyết định về phạm vi, phong
cách và MVP đều chốt ở đây. Sổ ý tưởng đầy đủ nằm trong Obsidian
(`Hành Tinh Mèo/y-tuong.md`); brief này không nhân bản nó, chỉ tóm
tắt những gì đã chốt.

## 1. Dự án là gì

Thế giới 3D trên trình duyệt, nơi chủ tạo lại mèo đã mất từ ảnh thật,
thả vào đó, thỉnh thoảng vào thăm. Mèo sống đời tự chủ theo giờ thật
(ngày/đêm, nhật ký), gặp gỡ mèo nhà khác.

Triết lý: **"A world that never forgets them."** — quay lại bất cứ lúc
nào cũng thấy người bạn nhỏ vẫn nằm dưới tán cây quen thuộc.

## 2. Ranh giới đỏ (không bao giờ làm)

- Không giả vờ mèo còn sống thật — luôn ghi rõ đây là phiên bản kỷ
  niệm do AI dựng từ ảnh và lời kể của chủ.
- Không chatbot "mèo đã mất nói chuyện với chủ" — mèo chỉ hành động,
  không nói chuyện.
- Không paywall nỗi buồn — tạo mèo + thăm + nhật ký cơ bản miễn phí.
- Không để mèo "chết lần hai" — chủ tải về toàn bộ kỷ niệm bất cứ lúc
  nào.
- Chi tiết đầy đủ: `dieu-can-tranh.md` (Obsidian).

## 3. Phong cách đồ họa — ĐÃ CHỐT 25/11: PuffPals

Lấy từ PuffPals: phong cách đồ hoạ, tương tác môi trường, ánh sáng,
vibe, vật lý. Hình tròn trịa múp míp, mềm, pastel, sáng ấm, chill.

**Model mèo lựa chọn sau** — prototype dùng mèo procedural đơn giản
(tròn trịa, 3 mẫu lông) làm tạm, không lấy model mèo của PuffPals
mặc định.

Ứng viên chung kết đã loại: Sky: Children of the Light, Zelda.

## 4. MVP — Prototype v1 (đã build 25/11, chưa push)

- Sphere Đồng Cỏ Nắng: đồng hoa, cỏ, ao, cây, mây, sáng ấm.
- Mèo procedural tạm (3 mẫu lông: cam vằn / xám–trắng / đen), tự
  đi/ngủ/groom, tới quấn bóng mờ của chủ.
- Chủ chỉ là bóng mờ trong suốt trên mặt đất, không thấy người.
- Chạm để vuốt ve ("Meo~" + tim), nhật ký đơn giản (localStorage),
  nút ngày/đêm, nhạc piano (tắt mặc định).
- Chưa có: tài khoản, Supabase, AI phân tích ảnh, phai, chăm hộ,
  guest stray, NPC, affiliate. Những thứ đó ở phase sau.

## 5. Tech stack

- Three.js + Vercel (static) + Supabase + Gemini free tier (khi cần).
- Chi phí MVP ~0đ. Không cần Claude Code Pro để bắt đầu.
- Repo: `vemmaster/cat-planet` (GitHub, private).

## 6. Quy trình làm việc

- **Khầy — Product Owner + Art Director:** quyết định trải nghiệm
  muốn tạo ra, chọn hướng cuối, giữ phạm vi dự án.
- **GPT — thẩm mỹ + ý tưởng triển khai:** hướng visual, moodboard,
  ý tưởng cách triển khai.
- **Muse — triển khai trơn tru:** biến ý tưởng thành code/prototype,
  làm việc với repo, deploy, kiểm chứng; hỗ trợ tìm kiếm và đối chiếu
  tham khảo hình ảnh khi cần.
- Nhịp mỗi vòng: GPT đề xuất (thẩm mỹ/ý tưởng) → Muse triển khai →
  khầy duyệt.

## 7. Quyết định đã chốt

- 22/11/2026: concept + nghiên cứu thị trường/pháp lý; phai −10%/tháng
  + −25% ngày giỗ, không bao giờ biến mất; siêu thoát tự chọn; builder
  theo khối; preset cảnh.
- 24/11/2026: bắt đầu build; repo `vemmaster/cat-planet`; thư mục
  Obsidian dùng chung Muse + ChatGPT.
- 25/11/2026: chốt style chính PuffPals (model mèo chọn sau).

## 8. Link

- Repo: https://github.com/vemmaster/cat-planet
- Obsidian: vault VemOS → thư mục `Hành Tinh Mèo` (note `Tổng quan.md`
  dẫn tới đây, Pinterest board và quyết định mới nhất).
- Pinterest board: (chưa có link — bổ sung sau).
