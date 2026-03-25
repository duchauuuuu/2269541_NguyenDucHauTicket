# EventTickets

Project setup for ticket management with AWS S3 image upload.

## Prerequisites

- Node.js (>= 18)
- npm

## Install dependencies

```bash
npm install express ejs body-parser aws-sdk multer uuid dotenv nodemon
```
nếu lỗi npm i uuid@8 hoặc chỉnh package 8.3.2
## Environment variables

Tạo file `.env` ở `EventTickets` với:

```env
AWS_REGION=us-east-1
AWS_ACCESS_KEY_ID=your_access_key_id
AWS_SECRET_ACCESS_KEY=your_secret_access_key
S3_BUCKET_NAME=your-s3-bucket
```

## Chạy ứng dụng

```bash
npm run dev
```

Hoặc:

```bash
node app.js
```

## Lưu ý

- AWS SDK v2 đã lỗi thời, nên cân nhắc nâng cấp lên v3 trong tương lai.
- Đảm bảo S3 bucket tồn tại và AWS key có quyền đọc/ghi.
