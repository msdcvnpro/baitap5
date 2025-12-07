# Ứng dụng Tìm kiếm Giá Sản phẩm

Ứng dụng Streamlit để tìm kiếm giá các sản phẩm nông nghiệp và thủy sản trên web.

## Cài đặt

1. Cài đặt các thư viện cần thiết:
```bash
pip install -r requirements.txt
```

## Chạy ứng dụng

```bash
streamlit run app.py
```

## Tính năng

- ✅ Giao diện đen với chữ trắng đậm
- ✅ Chọn ngày tháng để tìm kiếm giá
- ✅ Danh sách 24 sản phẩm nông nghiệp và thủy sản
- ✅ Tìm kiếm giá tự động trên nhiều nguồn web
- ✅ Hiển thị kết quả chi tiết (giá trung bình, min, max)
- ✅ Xuất kết quả ra file Excel với ngày tháng

## Danh sách sản phẩm

- Bầu
- Dịch vụ tưới, tiêu nước
- Tôm càng xanh (nhiều loại)
- Tôm sú (nhiều loại)
- Tôm thẻ chân trắng (nhiều loại)
- Cua bể thịt
- Cá tra giống
- Cá rô phi giống
- Cá trắm giống

## Lưu ý

- Ứng dụng tìm kiếm giá trên Google và các trang web Việt Nam
- Kết quả có thể thay đổi tùy theo thời điểm tìm kiếm
- File Excel xuất ra sẽ có tên: `gia_san_pham_YYYYMMDD.xlsx`

