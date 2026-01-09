# 3D Model Gallery - Three.js

Một trang web đơn giản trưng bày 10 model 3D sử dụng Three.js với giao diện tối (dark mode).

## Tính năng

- ✅ 10 canvas 3D hiển thị song song
- ✅ Mỗi canvas chứa 1 model 3D riêng biệt (.glb/.gltf)
- ✅ Sắp xếp dạng grid 2x5 (2 hàng, 5 cột)
- ✅ Camera và ánh sáng riêng cho từng canvas
- ✅ OrbitControls để xoay, zoom, pan model
- ✅ Tự động phát animation nếu model có
- ✅ Nút Play/Pause và chuyển animation cho từng canvas
- ✅ Giao diện tối (dark mode), nền xám đậm
- ✅ Viền mỏng giữa các canvas
- ✅ Performance tối ưu cho 10 model cùng lúc

## Cách chạy

### Phương pháp 1: Sử dụng Python HTTP Server (Khuyến nghị)

```bash
# Chạy server trên port 8000
python -m http.server 8000

# Hoặc port khác
python -m http.server 8080
```

Sau đó mở trình duyệt và truy cập: `http://localhost:8000` hoặc `http://localhost:8080`

### Phương pháp 2: Mở trực tiếp file HTML

Double-click vào file `index.html` để mở trong trình duyệt (có thể bị hạn chế CORS với file local).

### Phương pháp 3: Sử dụng Node.js

```bash
npx http-server -p 8000
```

## Thay đổi model

Để thay đổi các model 3D, chỉnh sửa array `modelConfigs` trong file `index.html`:

```javascript
const modelConfigs = [
    { name: "Tên Model 1", path: "đường/dẫn/đến/model1.glb" },
    { name: "Tên Model 2", path: "đường/dẫn/đến/model2.glb" },
    // ... thêm 8 model nữa
];
```

## Model mẫu hiện tại

1. Robot - Robot biểu cảm
2. Parrot - Vẹt
3. Flamingo - Hồng hạc
4. Stork - Cò
5. Horse - Ngựa
6. Cerberus - Chó 3 đầu
7. Fox - Cáo
8. Soldier - Lính
9. Littlest Tokyo - Thành phố thu nhỏ
10. Damaged Helmet - Mũ bảo hiểm bị hỏng

## Điều khiển

- **OrbitControls**: Click và kéo để xoay, scroll để zoom, right-click để pan
- **Play/Pause**: Nút ⏸️/▶️ để dừng/bật animation
- **Next Animation**: Nút ⏭️ để chuyển sang animation tiếp theo (nếu model có nhiều animation)

## Performance

- Pixel ratio giới hạn tối đa 2 để tiết kiệm tài nguyên
- Shadow mapping tối ưu
- Animation mixer chạy ở 60fps cố định
- Damping controls để mượt mà

## Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Dependencies

- Three.js r128 (CDN)
- GLTFLoader
- OrbitControls

Không cần cài đặt gì thêm, tất cả dependencies được load từ CDN.
