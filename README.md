# Loxia

Loxia là ứng dụng chuyển giọng nói thành văn bản chạy hoàn toàn trên máy của bạn, hỗ trợ tiếng Việt và tiếng Anh. Không cần tài khoản, không gửi âm thanh lên mạng.

Trang chủ và hướng dẫn cài đặt: <https://loxia.dev>

## Kho này chỉ chứa bộ cài

Mã nguồn không công khai. Mỗi bản phát hành ở mục **Releases** gồm:

- `Loxia-mac-arm64.dmg` cho máy Mac chip Apple
- `Loxia-windows-x64-setup.exe` cho Windows
- `Loxia-windows-x64-cuda-setup.exe` cho Windows có card đồ họa NVIDIA
- `SHA256SUMS.txt` để kiểm tra tệp tải về

## Kiểm tra tệp tải về

macOS:

```bash
shasum -a 256 Loxia-mac-arm64.dmg
```

Windows (PowerShell):

```powershell
Get-FileHash .\Loxia-windows-x64-setup.exe -Algorithm SHA256
```

Chuỗi in ra phải trùng dòng tương ứng trong `SHA256SUMS.txt`.

## Báo lỗi

Cách nhanh nhất: trong Loxia, vào Settings › Help › **Report…**, viết vài dòng, có thể đính kèm ảnh chụp màn hình rồi bấm Send. Không cần tài khoản.

Nếu có tài khoản GitHub, bạn cũng có thể mở một [issue](../../issues/new/choose) và điền mẫu có sẵn; vào Settings › Help › Copy để lấy thông tin chẩn đoán rồi dán vào mẫu. Không gửi được thì viết thư tới hello@loxia.dev.
