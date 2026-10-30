# huudung-wp-cron

Gọi `https://huudung.net/wp-cron.php` mỗi 15 phút bằng GitHub Actions, để bài hẹn giờ trên WordPress lên đúng giờ kể cả lúc không ai vào web.

- Không có mật khẩu, không có dữ liệu. Repo để public vì GitHub Actions miễn phí không giới hạn cho repo public.
- Lịch chạy của GitHub thường trễ 5–15 phút so với giờ hẹn.
- Xem kết quả: tab **Actions**. Chạy tay: Actions → *wp-cron huudung.net* → **Run workflow**.
- `nhip.txt` tự cập nhật mỗi 30 ngày để GitHub không tắt lịch (repo public không có commit 60 ngày thì bị tắt).
