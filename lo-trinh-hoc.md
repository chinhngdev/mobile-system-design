# Lộ trình học Mobile System Design

## Hồ sơ

| | |
|---|---|
| Platform | iOS / Swift |
| Kinh nghiệm | 2–3 năm |
| Mục tiêu | Big Tech (Meta, Google, Apple) |
| Thời gian | 1–2 tháng |

---

## Lộ trình 7 tuần

### Tuần 1 — Nắm khung phỏng vấn

**Đọc:** [README.md](README.md) (toàn bộ)

Tập trung vào:
- Framework 45–60 phút: cách phân bổ thời gian
- Cách đặt clarifying questions (Big Tech rất chú trọng điểm này)
- API design patterns
- Cách trình bày trade-offs — **điểm phân biệt Senior vs Mid ở Big Tech**

Sau khi đọc, thực hành với [TEMPLATE.md](TEMPLATE.md) — dùng như tờ giấy nháp cho mọi bài luyện tập.

---

### Tuần 2 — Deep dive kỹ thuật cốt lõi

1. [topics/in-app-api-design-deep-dive.md](topics/in-app-api-design-deep-dive.md) — nền tảng cho mọi bài
2. [topics/restful-api-design-deep-dive.md](topics/restful-api-design-deep-dive.md)
3. [topics/mobile-pagination-deep-dive.md](topics/mobile-pagination-deep-dive.md)
4. [topics/caching-deep-dive.md](topics/caching-deep-dive.md)

---

### Tuần 3 — Image & File (hay gặp nhất ở Big Tech)

1. [topics/image-loading-deep-dive.md](topics/image-loading-deep-dive.md)
2. [topics/resumable-uploads.md](topics/resumable-uploads.md)
3. [topics/quality-of-service.md](topics/quality-of-service.md)
4. [topics/prefetching.md](topics/prefetching.md)

---

### Tuần 4 — Luyện tập bài tập 1 & 2

Dùng TEMPLATE.md, tự thiết kế trước khi xem đáp án:

1. [exercises/image-library.md](exercises/image-library.md) — rất phổ biến ở Meta/Apple
2. [exercises/file-downloader-library.md](exercises/file-downloader-library.md)

---

### Tuần 5 — Offline & Navigation

1. [topics/offline-first-architecture-deep-dive.md](topics/offline-first-architecture-deep-dive.md) — Apple đặc biệt hay hỏi
2. [topics/mobile-navigation-deep-dive.md](topics/mobile-navigation-deep-dive.md)

---

### Tuần 6 — Luyện tập bài tập 3 & 4

1. [exercises/caching-library.md](exercises/caching-library.md)
2. [exercises/chat-app.md](exercises/chat-app.md) — bài khó nhất, thường xuất hiện ở vòng cuối

---

### Tuần 7 — Tổng ôn & Mock interview

1. [common-interview-mistakes.md](common-interview-mistakes.md) — đọc kỹ, tránh các lỗi phổ biến
2. [BLOGPOSTS.MD](BLOGPOSTS.MD) — chọn 3–5 bài từ công ty mục tiêu để có ví dụ thực tế
3. Tự mock với mỗi bài exercise: **45 phút, không xem tài liệu**

---

## Lưu ý quan trọng cho Big Tech

Điều họ đánh giá cao nhất **không phải là đáp án đúng** mà là:

1. **Clarifying questions** — Bạn hỏi gì trước khi thiết kế?
2. **Trade-offs** — Mỗi quyết định đều có pros/cons được nêu rõ
3. **Scalability thinking** — Giải pháp hoạt động ở 10M users?
4. **iOS-specific depth** — Biết URLSession, NSCache, background fetch, memory pressure...
