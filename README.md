# AI Offline Chat Multi-Device

Ứng dụng **AI Chat Offline + Multi-Device** chạy trực tiếp trên trình duyệt, hỗ trợ:

- Chat AI cơ bản offline (tính toán, tìm kiếm, giải thích thuật toán)
- Đồng bộ chat giữa các thiết bị qua Firebase
- Dark/Light mode, responsive, auto-expand textarea
- Export lịch sử chat sang JSON
- Clear chat dễ dàng
- PWA hỗ trợ offline

---

## **Cách dùng nhanh**

1. **Cấu hình Firebase**  
   Thay các thông tin trong `firebaseConfig` trong file HTML:
   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_PROJECT.firebaseapp.com",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_PROJECT.appspot.com",
     messagingSenderId: "SENDER_ID",
     appId: "APP_ID"
   };
