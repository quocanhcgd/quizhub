# QuizHub Display

Trang hiển thị bảng xếp hạng thời gian thực cho giải đấu Quiz.

## Tính năng

- 🏆 Hiển thị tên giải đấu từ settings
- 🌓 Chuyển đổi theme sáng/tối
- 📊 Bảng xếp hạng thời gian thực
- 📱 Responsive design (mobile, tablet, desktop)
- ⚡ Real-time updates với Supabase

## Cài đặt

1. Cài đặt dependencies:
```bash
npm install
```

2. Tạo file `.env` từ `.env.example` và cập nhật thông tin Supabase:
```bash
cp .env.example .env
```

3. Chạy development server:
```bash
npm run dev
```

4. Mở trình duyệt tại: http://localhost:5173

## Build

```bash
npm run build
```

## Tech Stack

- React 18 + TypeScript
- Vite
- TailwindCSS
- Supabase
- Lucide React Icons