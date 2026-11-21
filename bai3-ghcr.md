### Các câu lệnh CLI đã thực hiện:
1. Đăng nhập vào GitHub Container Registry:
echo "<YOUR_PAT>" | docker login ghcr.io -u vantruongnguyen-cell --password-stdin

2. Gắn tag image theo chuẩn namespace GHCR:
docker tag cart-service:multistage ghcr.io/vantruongnguyen-cell/payment-service:1.0.0

3. Đẩy image lên GHCR:
docker push ghcr.io/vantruongnguyen-cell/payment-service:1.0.0

### Đường dẫn Package trên GitHub:
https://github.com/vantruongnguyen-cell?tab=packages
