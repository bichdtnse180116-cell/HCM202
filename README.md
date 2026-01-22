# 3D Model Gallery - Sáng Tạo Nhóm 5

Một trang web trưng bày bộ sưu tập các mô hình 3D tương tác được tạo bởi **Nhóm 5** - môn học **HCM202** - Lớp **GD1817**.

## 📍 Truy cập trang web

🔗 **https://hcm-202-seven.vercel.app/**

Bạn có thể truy cập trang web trực tiếp từ đường link trên để xem toàn bộ các mô hình 3D.

## ✨ Tính năng chính

- 📊 Hiển thị 10 mô hình 3D sản phẩm sáng tạo của nhóm
- 🎥 Mỗi mô hình có camera, ánh sáng và điều khiển riêng
- 🔄 Hỗ trợ animation
- 🎯 Điều khiển xoay, zoom và pan mô hình bằng chuột

## 🎮 Cách sử dụng

### Điều khiển mô hình 3D

- **Xoay mô hình**: Click và kéo chuột
- **Zoom in/out**: Cuộn bánh xe chuột (scroll)
- **Pan camera**: Click chuột phải và kéo
- **Xem toàn màn hình**: Nhấp vào nút **⛶** trên mỗi mô hình

## 🛠️ Công nghệ sử dụng

- **Three.js** - Thư viện 3D JavaScript
- **GLTFLoader** - Tải mô hình 3D (.glb/.gltf)
- **OrbitControls** - Điều khiển camera 3D
- **Vercel** - Hosting & deployment

## 📁 Cấu trúc dự án

```
mln131/
├── index.html          # Tệp HTML chính
├── README.md           # Tài liệu này
└── models/             # Thư mục chứa các mô hình 3D
    ├── 1.glb
    ├── ly2.glb
    ├── ly3.glb
    ├── ly4.glb
    ├── ly5.glb
    ├── ly7.glb
    ├── ly9.glb
    ├── ly10.glb
    ├── ly11.glb
    └── ly12.glb
```

## 🚀 Cách chạy locally

### Cách 1: Python HTTP Server (Khuyến nghị)

```bash
cd mln131
python -m http.server 8000
```

Sau đó mở trình duyệt và truy cập: `http://localhost:8000`

### Cách 2: Node.js

```bash
npx http-server -p 8000
```

### Cách 3: Mở trực tiếp

Double-click file `index.html` (có thể bị hạn chế CORS với file local)

## 🎓 Thông tin môn học

- **Môn học**: HCM202
- **Lớp**: GD1817
- **Nhóm**: 5
- **Loại bài tập**: Sáng tạo web 3D tương tác

## 📝 Ghi chú

Đây là sản phẩm sáng tạo của nhóm trong quá trình học tập. Trang web được thiết kế để trưng bày các mô hình 3D sản phẩm snags tạo của nhóm trong quá trình học tập.

---

**Last Updated**: January 23, 2026
