# Git

## Sử dụng git cơ bản
Bây giờ, khởi tạo git
```bash
git init
touch README.md
git add .
git commit -m "first commit"
git checkout -b main
```

Có nhiều phiên bản code khác nhau, tạo ra các nhánh:
```bash
git checkout -b myBranch
```

Quay về nhánh cũ:
```bash
git checkout main
```