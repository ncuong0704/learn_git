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

- git push -u origin {branch name} giúp push 1 branch lên trên github
- sau đó mình dùng git push để đẩy code lên

- Cách get 1 branch mới từ github về local
- b1: git fetch origin
- b2: git checkout -b {branch name} origin/{branch name}

- sau khi merge code từ các branch con vào nhánh master thì mình gõ git pull để lấy code từ github về lại local

- tạo file '.gitignore' trong file này mình để các tên file mà mình k muốn git quan tâm và theo dõi chúng.

- khi mình muốn chỉnh sửa code của 1 dự án của 1 tác giả nào đó. Mình vào github bấm vào "Fork" và chỉnh sửa code. Cuối cùng là tạo "Pull requests" và đợi tác giả accept và merge chúng.
