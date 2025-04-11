# 📚 NestJS Roadmap

## 1. Kiến thức nền tảng (trước khi học NestJS)
- Node.js cơ bản: event loop, callback, async/await, promise.
- TypeScript: types, interfaces, decorators, generics.
- HTTP và REST API: request/response, status code, method.
- OOP: Class, interface, inheritance.

## 2. Bắt đầu với NestJS
- Cài đặt Nest CLI: `npm i -g @nestjs/cli`
- Tạo project mới: `nest new project-name`
- Hiểu cấu trúc dự án:
  - Controller: nhận request.
  - Service: xử lý logic.
  - Module: nhóm các thành phần liên quan.
- Xây dựng API CRUD cơ bản.

## 3. Xử lý nâng cao
- DTO (Data Transfer Object) và Validation (`class-validator`, `class-transformer`).
- Exception Filters: custom lỗi trả về.
- Pipes: validate, transform dữ liệu.
- Guards: kiểm tra trước khi vào controller (ví dụ auth).
- Interceptors: modify request/response, logging, caching.

## 4. Kết nối Database
- TypeORM / Prisma / Sequelize.
- Repository Pattern trong NestJS.
- Migration và Seed dữ liệu.
- Ví dụ: kết nối PostgreSQL.

## 5. Authentication & Authorization
- JWT Authentication: đăng nhập, đăng ký.
- Passport.js tích hợp với NestJS.
- Role-based Authorization: phân quyền người dùng.

## 6. Viết Test
- Unit Test với Jest.
- E2E Test.

## 7. Kiến trúc nâng cao
- Middleware: xử lý request trước controller.
- Microservices: giao tiếp service-service qua RabbitMQ, Kafka.
- Event-driven Architecture.

## 8. Triển khai (Deployment)
- Dockerize NestJS app.
- Deploy lên:
  - Vercel
  - AWS (EC2)
  - Heroku

## 9. Các chủ đề nâng cao khác
- Websocket (real-time chat).
- GraphQL với NestJS.
- CQRS Pattern (Command Query Responsibility Segregation).
- Multi-tenancy (ứng dụng đa tenant).

## 10. Dự án thực tế để luyện tập
- **Blog API**: CRUD bài viết, auth người dùng.
- **E-commerce API**: sản phẩm, đơn hàng, thanh toán.
- **Chat App**: WebSocket + JWT.

---

## Tips
- 🔥 Code song song với lý thuyết.
- 🔥 Luôn viết Interface và Type cho dữ liệu.
- 🔥 Đọc mã nguồn NestJS để hiểu thêm module.
