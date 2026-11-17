# Giám sát nhiệt độ - độ ẩm (DHT22) và điều khiển quạt qua Firebase

Nhóm CR7 Team: Pham Gia Huy, Truong Thanh An

## Mô tả
Web hiển thị nhiệt độ, độ ẩm theo thời gian thực từ Firebase Realtime Database
và có nút ON/OFF điều khiển quạt.

## API (Firebase của nhóm)
Database URL:
https://dht22-4a670-default-rtdb.asia-southeast1.firebasedatabase.app

```js
const firebaseConfig = {
  apiKey: "AIzaSyBwUoBlPteHqIV-Uwiynuz7bf5jhf9du80",
  authDomain: "dht22-4a670.firebaseapp.com",
  databaseURL: "https://dht22-4a670-default-rtdb.asia-southeast1.firebasedatabase.app",
  projectId: "dht22-4a670",
  storageBucket: "dht22-4a670.firebasestorage.app",
  messagingSenderId: "931127044212",
  appId: "1:931127044212:web:9ca9247b9f1baa61204921"
};
```