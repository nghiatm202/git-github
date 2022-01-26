# Định nghĩa: Git là 1 version control (kiểm soát phiên bản) - là 1 hệ thống ghi chú lại tất cả hoạt động trên dự án của chúng ta.

=> Nói đơn giản git như 1 thẻ nhớ cho dự án của chúng ta và chúng ta có thể lựa chọn bất kỳ thời điểm nào trên dự án để kiểm soát lại code của chúng ta.

## Terms - danh từ

- Repository (repo): 1 thư mục, dự án của chúng ta.
- Branch: cành, nhánh

## Commands - lệnh

- git init: khi gõ lệnh này thì dự án của chúng ta có thể sử dụng được git (hoặc dự án của chúng ta trở thành git rebository).
- git status: cho chúng ta thấy được trạng thái dự án của mình (tất cả thay đổi gì chúng ta có thể thấy được).
- git add: cho phép chúng ta chuẩn bị lưu lại thời điểm hiện tại của dự án

* nếu lưu 1 file: git add index.html [tên file].
* nếu lưu tất cả file: git add .

- git reset: để hủy lưu file.
- git commit -m 'ghi chú': chính thức lưu.
- git log: xem lại các thời điểm chúng ta lưu file.
- git log --oneline (shorthand của git log).
- git checkout [id]: muốn quay lại 1 thời điểm nào đó.
- git checkout [branch-name]: muốn trở lại hiện tại.
- git branch: kiểm tra xem đang ở branch nào.
- git checkout -b [branch-name]: tạo ra 1 branch mới.
- git merge [branch-name]: muốn tổng hợp branch.
- git branch -d [branch-name]: xóa đi 1 branch.

# Định nghĩa: Github là 1 dịch vụ trên mạng để chúng ta đẩy lên dự án của mình và github sẽ chứa dự án của chúng ta đặc biệt hơn github sẽ cho phép chúng ta làm việc chung với nhau và kiểm soát được người nào đang làm cái gì trên dự án
