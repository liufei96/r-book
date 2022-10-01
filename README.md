# r-book
书籍分享


# 上传大文件

```shell
# 1.在项目目录下，执行以下命令：
git lfs install

# 2. 选择您希望Git LFS管理的文件类型（或直接编辑.gitattributes）
git lfs track "*.pdf"

# 3. 添加并commit gitattributes文件
git add .gitattributes

# 然后再添加大文件到本地缓存区
git add demo.pdf
git commit -m "提交大文件"
git push
```