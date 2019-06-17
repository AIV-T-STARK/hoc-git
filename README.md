# GIT - Các lệnh cơ bản 
## Repo
- gồm 2 loại: 
    + Remote Repo: hiểu như là server (github, gitlab)
    + Local Repo: Repo trên máy người dùng (thường được đồng bộ với Remote Repo)
- clone 1 repo : 
```
git clone <link repo>
```

###Working directory ----add---> ###index ----Commit----> Repo 
- Khai báo những gì đã thay đổi vào index để chuẩn bị cho việc index:
```
git add <ten file> 
or
git add .(add tất cả)
```
```
git checkout -- <ten file> (xóa những gì đẫ thay đổi khỏi working directory )
```
```
git reset HEAD (chuyển từ index về working dir)
```
```
git commit -m "message commit" (commit)
```
```
git commit --amend (sửa lại commit trước đó)
```
```
git reset <mã commit> (quay lại 1 commit nào dó)
```