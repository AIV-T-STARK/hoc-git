# GIT - Các lệnh cơ bản 
![](https://backlog.com/git-tutorial/vn/img/post/intro/capture_intro1_2_2.png)
- gồm 2 loại: 
    + Remote Repo: hiểu như là server (github, gitlab)
    + Local Repo: Repo trên máy người dùng (thường được đồng bộ với Remote Repo)
- clone 1 repo : 
```
git clone <link repo>
```

### Working directory ----add---> ### index ----Commit----> ###Repo 
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTnTKivF9m-xxnYMmXZjcnOvGYjqIvsttjy2qSi4738kZFeSt4Ctg)
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

### Branch
![](https://cdn-images-1.medium.com/max/2400/1*tnvRls6Dg7vFt0zGdtfu_w.png)

```
git checkout -b <tên branch> (tạo branch sau đó chuyển đến branch đó)
git checkout <tên branch> (chuyển branch)
git branch (liệt kê các branch hiện có)
git branch <tên branch> (tạo branch)
```

```
git merge <tên branch> (gộp branch khác vào branch hiên tại) 
```
- việc này thường xảy ra xung đột -> sửa thủ công -> commit những gì đã thay đổi

Chuc nang A
Chuc nang B
