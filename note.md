# Terms

Repository (Repo) //thư mục dự án vd:TESTGIT
Branch - mỗi chữ năng chia ra thành một branch
Local - nằm trên máy tính
Remote - nằm trên server

# Commands
- git init 
- git status (tất cả các file trong dự )
- git add [cho phép chuẩn bị lưu lại thời điểm hiện tại của dự]
- git add {ten_file.c}} [lưu file đính]
- git add . [lưu toàn bộ file]
- git reset [bỏ cbi lưu]
- git commit -m'initial commit' [ghi chú trong đây '']
- git log [hiển thị id, người, thời gian, ghi chú ]
- git log --oneline [hiển thị trên 1 ]

- git checkout {id ở}} [trở về dự án id]
- git checkout master  [trở về phiên bản mới nhất]
- git branch

{nhớ git add. git commit xong rồi mới branch khác}
- git checkout -b {branch name} //tạo 1 branch khác

------
git remote add [tên_viết_tắt] [đường_link]: gán đường link vào tên viết tắt
git push [tên_viết tắt] [tên_nhánh_local]: đẩy lên remote 