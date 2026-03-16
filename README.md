# Công cụ tra cứu mã HS Code và thuế XNK — Spinoglobal 2026

![Spino Global](https://spinoglobal.vn)

Công cụ tra cứu mã HS Code và thuế nhập khẩu hàng Trung Quốc, được xây dựng bởi **Spino Global**.

## Tính năng

- **12.000 mã HS 8 chữ số** — Dữ liệu đầy đủ từ Biểu thuế XNK 2026
- **3 loại thuế NK**: MFN (NĐ 144/2024), ACFTA C/O form E (NĐ 118/2022), RCEP 2026 (NĐ 129/2022)
- **Thuế VAT chính xác** theo NĐ 174/2025 — giảm 10%→8% đến 31/12/2026, phân biệt rõ nhóm không được giảm (PL1+PL2)
- **AI nhận diện sản phẩm từ ảnh** — Upload ảnh, AI tự động đề xuất mã HS phù hợp
- **Máy tính thuế** — Nhập CIF, so sánh MFN vs ưu đãi, hiển thị số tiền tiết kiệm
- **Tìm kiếm tiếng Việt** — Hỗ trợ tìm không dấu
- **Responsive** — Hoạt động tốt trên mobile và desktop

## Cách sử dụng

### Nhúng vào website (iframe)

```html
<iframe 
  src="https://[your-github-username].github.io/spinoglobal-hscode/" 
  width="100%" 
  height="800px" 
  frameborder="0"
  style="border: none; border-radius: 8px;"
></iframe>
```

### Nhúng vào WordPress

Thêm block **Custom HTML** và paste đoạn iframe ở trên.

### Nhúng responsive (tự động chiều cao)

```html
<div style="position:relative;width:100%;padding-top:0">
  <iframe 
    id="hscode-frame"
    src="https://[your-github-username].github.io/spinoglobal-hscode/" 
    width="100%" 
    height="900px" 
    frameborder="0"
    style="border:none;border-radius:8px;box-shadow:0 2px 12px rgba(0,0,0,0.1)"
  ></iframe>
</div>
```

## Deploy lên GitHub Pages

1. Push repo này lên GitHub
2. Vào **Settings** → **Pages**
3. Source: chọn **Deploy from a branch**
4. Branch: chọn `main`, folder: `/ (root)`
5. Save → đợi 1-2 phút
6. URL sẽ là: `https://[username].github.io/spinoglobal-hscode/`

## Nguồn dữ liệu

| Loại thuế | Văn bản | Giai đoạn |
|-----------|---------|-----------|
| MFN (ưu đãi) | NĐ 144/2024/NĐ-CP | 2024+ |
| ACFTA (C/O form E) | NĐ 118/2022/NĐ-CP | 2022-2027 |
| RCEP | NĐ 129/2022/NĐ-CP | 2022-2027 |
| VAT giảm 8% | NĐ 174/2025/NĐ-CP | 01/07/2025 - 31/12/2026 |

## Lưu ý

- Thuế suất mang tính **tham khảo** ở cấp mã 8 số
- Tra cứu chính thức tại [customs.gov.vn](https://customs.gov.vn)

## License

© 2026 Spino Global — [spinoglobal.vn](https://spinoglobal.vn)
