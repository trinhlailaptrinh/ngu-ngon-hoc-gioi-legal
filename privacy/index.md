---
title: Chính sách quyền riêng tư — Lullwise
---

# Chính sách quyền riêng tư — Lullwise

Nhà phát triển: TRINHNN · Cập nhật: 11/10/2026 (bổ sung tạo thẻ từ ảnh, Private Cloud Compute, thêm thẻ từ app AI của bạn qua Dán hoặc nút Chia sẻ, tải ảnh minh hoạ từ đường dẫn trong thẻ) · Bản công khai: https://trinhlailaptrinh.github.io/lullwise/privacy/

Lullwise ("ứng dụng") được làm để giúp bạn ngủ ngon và học tập trung. Chúng tôi không có máy chủ riêng, không có tài khoản đăng nhập, không theo dõi và không bán dữ liệu của bạn.

## Dữ liệu ứng dụng lưu

| Dữ liệu | Dùng để |
|---|---|
| Câu nói bạn tự thêm | Hiện trong Kho câu nói và widget |
| Trạng thái yêu thích / ẩn của từng câu | Lọc câu, chọn câu cho widget |
| Lịch sử phiên học (thời điểm bắt đầu, số phút) | Thống kê giờ học hôm nay và 7 ngày |
| Thẻ ôn tập bạn tự ghi (câu hỏi, đáp án, môn học, mẹo nhớ, ảnh minh hoạ nếu bạn thêm) | Ôn trước khi ngủ và kiểm tra buổi sáng |
| Lịch sử ôn (thời điểm ôn, nhớ hay chưa nhớ) | Lịch ôn giãn cách và báo cáo tuần |
| Cài đặt: âm thanh, hẹn giờ tắt, âm thanh nền khi tập trung, giờ nhắc | Mở lại đúng lựa chọn lần trước |
| Ngày bắt đầu dùng thử | Tính 7 ngày dùng thử miễn phí |

Ứng dụng không thu thập tên, email, số điện thoại, vị trí, danh bạ, micro hay mã định danh quảng cáo. Ứng dụng không đọc thư viện ảnh của bạn: chỉ những ảnh bạn tự chọn (qua bộ chọn ảnh của hệ thống) hoặc tự chụp cho một thẻ mới được lưu, sau khi thu nhỏ. Camera chỉ bật khi bạn bấm Chụp ảnh (trong thẻ, hoặc khi tạo thẻ từ ảnh).

Khi bạn tạo thẻ từ ảnh (trang sách, vở ghi, slide), chữ trong ảnh được đọc ngay trên thiết bị và thẻ đề xuất được soạn bằng model của Apple chạy trên thiết bị (trừ trường hợp Private Cloud Compute nêu bên dưới). Bạn xem lại từng thẻ trước khi lưu; ảnh trang sách chỉ được lưu vào thẻ nếu bạn chọn gắn ảnh.

## Dữ liệu được lưu ở đâu

- **Trên thiết bị của bạn**, trong vùng lưu trữ riêng (App Group) dùng chung giữa ứng dụng, widget và phần mở rộng Chia sẻ của nó (để bạn lưu thẻ ngay trong khung Chia sẻ của app khác).
- **Trong iCloud của chính bạn** (CloudKit, cơ sở dữ liệu riêng tư): câu nói tự thêm, trạng thái yêu thích/ẩn, lịch sử phiên học, thẻ ôn tập và lịch sử ôn được đồng bộ giữa các thiết bị đăng nhập cùng Apple ID. Dữ liệu này nằm trong tài khoản iCloud của bạn; nhà phát triển không đọc được. Nếu bạn không đăng nhập iCloud, dữ liệu chỉ nằm trên thiết bị.
- Cài đặt và ngày bắt đầu dùng thử chỉ nằm trên thiết bị, không đồng bộ. Ngày bắt đầu dùng thử được lưu thêm trong Keychain của thiết bị (chỉ thiết bị này, không đồng bộ iCloud) để tính đúng 7 ngày dùng thử kể cả khi bạn xoá rồi cài lại ứng dụng.

## Dữ liệu rời khỏi thiết bị khi nào

Chỉ trong các trường hợp sau:

1. **Đến iCloud của bạn** để đồng bộ, như trên.
2. **Đến Apple** khi bạn mua hoặc khôi phục giao dịch qua App Store (StoreKit). Apple xử lý thanh toán theo chính sách của Apple; ứng dụng chỉ nhận kết quả giao dịch để mở khoá.
3. **Đến Private Cloud Compute của Apple** khi bạn tạo thẻ từ ảnh trên iOS 27 trở lên và để bật "Dùng Private Cloud Compute": ảnh trang sách và chữ đọc được từ ảnh được gửi tới model của Apple chạy trên máy chủ Private Cloud Compute để soạn thẻ. Apple chỉ dùng dữ liệu để trả kết quả và không giữ lại; nhà phát triển không nhận được ảnh. Tắt lựa chọn này trên màn tạo thẻ thì ảnh chỉ được xử lý trên thiết bị.

Khi bạn thêm thẻ từ câu trả lời của app AI bạn tự dùng, nội dung bạn dán hoặc chia sẻ vào Lullwise chỉ được xử lý trên máy. Nếu câu trả lời có đường dẫn ảnh minh hoạ (https), ứng dụng tải ảnh đó trực tiếp từ địa chỉ ấy để gắn vào thẻ: máy chủ của trang đó nhận yêu cầu tải ảnh như khi bạn mở ảnh bằng trình duyệt (thấy địa chỉ IP của bạn), ứng dụng không gửi kèm dữ liệu nào khác và không dùng cookie.

Lời nhắc ôn tối và kiểm tra sáng là thông báo cục bộ do ứng dụng tạo ngay trên máy (chỉ khi bạn bật), không đi qua máy chủ nào. Báo cáo tuần được tính ngay trên máy.

Ứng dụng không gửi dữ liệu đến máy chủ của nhà phát triển hay bên thứ ba nào, không dùng công cụ phân tích (analytics), không quảng cáo, không theo dõi bạn qua ứng dụng hay trang web khác.

## Xoá dữ liệu

- Xoá từng câu tự thêm trong Kho câu nói (vuốt sang trái → Xoá).
- Xoá ứng dụng để xoá dữ liệu trên thiết bị. Riêng ngày bắt đầu dùng thử trong Keychain vẫn còn sau khi xoá ứng dụng (đây là một mốc thời gian, không chứa thông tin cá nhân); nó bị xoá khi bạn đặt lại thiết bị (Cài đặt → Cài đặt chung → Chuyển hoặc đặt lại iPhone → Xoá tất cả nội dung và cài đặt).
- Xoá dữ liệu đã đồng bộ trong iCloud: Cài đặt → [tên bạn] → iCloud → Quản lý dung lượng → Lullwise → Xoá dữ liệu.

## Trẻ em

Ứng dụng không thu thập thông tin cá nhân của bất kỳ ai, kể cả trẻ em.

## Thay đổi chính sách

Khi chính sách thay đổi, chúng tôi cập nhật trang này và ngày cập nhật ở đầu trang.

## Liên hệ

Câu hỏi về quyền riêng tư: [trang hỗ trợ](../support/)

---

# Privacy Policy — Lullwise (English summary)

Last updated: October 11, 2026

- **What the app stores:** quotes you add, favorite/hidden flags on quotes, study-session history (start time, minutes), study cards you write (question, answer, subject, memory hint, and a picture if you add one — only photos you pick or take for a card; the app never reads your photo library) and review history (when, remembered or not), settings (sounds, sleep timer, focus sound, reminder times), and your free-trial start date. No name, email, location, contacts, photos, microphone or advertising identifier. The camera turns on only when you tap Take a Photo (for a card, or to create cards from a photo). When you create cards from a photo, the text is read on your device and suggested cards are drafted by Apple's on-device model (except Private Cloud Compute, below); the page photo is saved to a card only if you choose to attach it.
- **Where it is stored:** on your device in the app's App Group container (shared with its widget and its Share extension, so you can save cards right in another app's Share sheet), and — for your quotes, favorite/hidden flags, study sessions, study cards and review history — in your own iCloud private database via CloudKit. Evening and morning reminders are local notifications created on your device; the weekly report is calculated on your device. The developer cannot read it. Without iCloud, data stays on the device. The trial start date is also kept in this device's Keychain (not synced) so the 7-day trial is counted correctly after reinstalling.
- **When data leaves your device:** only to your iCloud (sync), to Apple when you buy or restore purchases through the App Store (StoreKit), and — on iOS 27 or later, when you create cards from a photo with "Use Private Cloud Compute" on — to Apple's Private Cloud Compute, where an Apple model turns the photo and its text into suggested cards without keeping them. When you add cards from your own AI app's reply, the text and pictures you paste or share are processed on your device; if a card contains an https link to a picture, the app downloads that picture directly from that address (the site sees an ordinary download request, no cookies or other data). No developer servers, no third parties, no analytics, no ads, no tracking.
- **Deleting data:** delete your quotes in the app, delete the app to remove on-device data (the trial start date in the Keychain remains until the device is erased), and remove synced data in Settings → [your name] → iCloud → Manage Storage → Lullwise.
