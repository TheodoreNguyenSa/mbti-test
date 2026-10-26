# MBTI Test v1.0.1 — Android TV

Trắc nghiệm tính cách MBTI cho TV: 32 câu hỏi tiếng Việt (8 câu cho mỗi cặp
đối lập E/I, S/N, T/F, J/P), mỗi câu 2 đáp án. Kết quả: 4 chữ cái + biệt
danh + 4 thanh % + mô tả ngắn, rồi 4 mục gợi ý riêng cho nhóm đó: Điểm mạnh,
Khó khăn thường gặp, Ngành nghề phù hợp, Cần điều chỉnh để thuận lợi hơn.
Chạy offline hoàn toàn.

## Cài đặt

- **Downloader:** 9498201 (mở app Downloader trên TV, gõ 9498201)
- **GitHub:** https://github.com/TheodoreNguyenSa/mbti-test (repo chưa tạo —
  auto-update trong app sẽ im lặng bỏ qua cho tới khi có release)
- Hoặc chép file APK qua USB / Send Files to TV rồi cài.

## Điều khiển (remote TV)

- Màn bắt đầu: DPAD chọn nút "Bắt đầu" / pill Music / pill "Buy me a coffee",
  OK xác nhận, BACK thoát app.
- Màn câu hỏi: DPAD lên/xuống chọn đáp án A/B, OK xác nhận và sang câu sau,
  BACK quay lại câu trước (đáp án đã chọn được giữ).
- Màn kết quả (v1.0.1, cuộn được): DPAD lên/xuống cuộn nội dung (mỗi lần
  ~1/3 màn hình), thanh chỉ báo cuộn mỏng ở mép phải. Hai nút "Chơi lại" /
  "Lưu kết quả" nằm cuối nội dung — cuộn xuống cuối mới thấy. DPAD trái/phải
  đổi nút đang chọn, OK xác nhận, BACK về màn bắt đầu. "Lưu kết quả" lưu vào
  máy để màn bắt đầu hiện "Kết quả lần trước: XXXX".
- Phím MUTE: bật/tắt nhạc nền.

## Tính điểm

Mỗi cặp đối lập đếm số đáp án nghiêng về mỗi phía (tối đa 8 câu).
% = số câu / 8 × 100. Chữ cái = phía nhiều hơn. Hòa 4–4 thì lấy chữ cái
đầu tiên của cặp (E, S, T, J).

## Tính năng chung

- Nhạc nền + MUTE (watchdog 2 giây, tắt khi app ở nền — cùng pattern với
  School Quiz v1.1.3 / Trắc nghiệm v1.1.1).
- Nút "Buy me a coffee" mở bảng QR (quét bằng điện thoại), OK mở trình duyệt.
- Auto-update: kiểm tra GitHub releases/latest tối đa 1 lần/ngày, có bản mới
  thì hỏi trước khi tải.

## Thay đổi v1.0.1 (so với v1.0.0)

- Màn kết quả mở rộng: giữ nguyên 4 chữ cái + biệt danh + 4 thanh % + mô tả
  ngắn ở đầu, thêm 4 mục gợi ý cho đúng nhóm tính cách (Điểm mạnh 2-3 dòng,
  Khó khăn thường gặp 2 dòng, Ngành nghề phù hợp 3-4 ngành, Cần điều chỉnh
  2-3 hành vi cụ thể) + dòng "Gợi ý chỉ mang tính tham khảo, không phải tư
  vấn nghề nghiệp chuyên môn."
- Màn kết quả cuộn dọc bằng DPAD lên/xuống (cuộn mượt, mỗi lần ~1/3 màn
  hình), có thanh chỉ báo cuộn ở mép phải; 2 nút nằm cuối nội dung.
- Màn bắt đầu và màn câu hỏi không đổi.

## Lưu ý

MBTI chỉ mang tính tham khảo và giải trí, không phải công cụ chẩn đoán tâm lý.
Nội dung 32 câu hỏi và 16 hồ sơ nhóm do Bột tự viết bằng tiếng Việt, không
copy từ 16Personalities hay bài test MBTI chính thức.

## File

- `MBTITest-ToanNguyen-v1.0.1.apk` — 1.733.522 byte,
  sha256 `9c0c348f4faa9206907308f9411622172e0cd5b44d62488c92417b60f591848a`
- `MBTITest-ToanNguyen-v1.0.0.apk` — bản trước (giữ lại)
- `banner.png` — banner 1280×720
- `CONTENT-v1.0.1.md` — toàn bộ 32 câu hỏi + 16 hồ sơ đầy đủ 4 mục gợi ý
  (xuất từ class đã compile, để đối chiếu)
- `CONTENT.md` — nội dung v1.0.0

Package: `com.toannguyeninoz.mbti`, versionCode 2, versionName 1.0.1.
Source: `vodafone-tvbox-cleanyourtv/mbti/` (keystore riêng `mbti.keystore`).
