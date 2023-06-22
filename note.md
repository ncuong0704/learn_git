# Terms

Repository (Repo) là cả thư mục learn-git
Branch
Conflict là khi mình lấy code mới về thì nó sẽ so sánh code hiện tại và code mới để xem có gì thay đổi giữa code hiện tại và code lấy về.
Local là những dữ liệu từ máy tính
Remote là những dữ liệu từ server

# Commands

- git init giúp dự án có thể sử dụng được git
- git status cho thấy những thay đổi của dự án
- git add lấy file ra chuẩn bị lưu
- git add . lấy tất cả file ra chuẩn bị lưu
- git reset bỏ tất cả các file đã chọn để lấy lại
- git commit -m 'initial commit' chính thức lưu file
- git commit không có ghi chú giúp mình lưu lại khi mình conflict code đã xong.
- git log giúp coi lại những thời điểm đã lưu
- git log --online giúp coi lại thời điểm đã lưu nhưng gọn hơn
- git checkout {brand name} giúp quay lại thời điểm đã lưu bằng brand name của thời điểm đó
- git branch giúp xem các nhánh hiện tại của dự án
- git checkout -b {branch name} giúp tạo nhánh mới cho dự án
- git merge {branch name} giúp lấy code của các nhánh phụ vào nhánh chính (vd: nhánh master)
- git branch -d {branch name} giúp xoá branch


- git remote add {đặt tên cho link github} {link remote của github}
- git push {tên đã gán cho link github} {branch name} đưa code lên github

- git clone {link của github} giúp clone 1 repo về local
- sau đó mình có thể push code lên bằng git push mà k cần link và nhánh

