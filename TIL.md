# 2025-10-03 
## Học `git add` command
### 1. TỔNG QUAN (DESCRIPTION)
`git add` **là lệnh cập nhật index (staging area)** bằng cách sử dụng nội dung hiện tại từ working tree, để chuẩn bị nội dung cho lần commit tiếp theo.

Khái niệm quan trọng:

- Working Tree: Thư mục làm việc hiện tại trên máy tính của bạn
- Index (Staging Area): Khu vực trung gian giữa working tree và repository, là "ảnh chụp" nội dung sẽ được commit
- Repository: Nơi lưu trữ lịch sử commit

Quy trình làm việc:

---
|Working Tree → (git add) → Index/Staging Area → (git commit) → Repository|
---
