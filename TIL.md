# 2025-10-03 
# Học `git add` command
# 1. TỔNG QUAN (DESCRIPTION)
`git add` **là lệnh cập nhật index (staging area)** bằng cách sử dụng nội dung hiện tại từ working tree, để chuẩn bị nội dung cho lần commit tiếp theo.

Khái niệm quan trọng:

- Working Tree: Thư mục làm việc hiện tại trên máy tính của bạn
- Index (Staging Area): Khu vực trung gian giữa working tree và repository, là "ảnh chụp" nội dung sẽ được commit
- Repository: Nơi lưu trữ lịch sử commit

Quy trình làm việc:
 
| Working Tree → (git add) → Index/Staging Area → (git commit) → Repository  |
| :---- |

### Thêm tất cả file .txt trong thư mục Documentation và các thư mục con
```bash 
  git add Documentation/\*.txt
```
Giải thích tại sao phải có 2 dấu gạch

```java
    public static List<List<Integer>> subsetSum(int[] nums, int target) {
        List<List<Integer>> res = new ArrayList<>();
        List<Integer> path = new ArrayList<>();
        dfs(nums, target, 0, res, path);

        return res;
    }
```

:question: làm sao clone local project

? dấu xuống dòng thay đổi khi commit từ máy win/mac