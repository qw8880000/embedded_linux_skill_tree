
git subtree 如何检出指定的 tag，我们使用以下命令来检出一个子仓库：
```sh
git subtree pull --prefix=<dir> <repository> <ref>
```

其中`<ref>` 可以是`commit id`, `branch`, `tag`.

假设我有一个仓库：`https://github.com/qw8880000/blog.git`，我如果要检出`v1.0.1` 这个tag，那么命令是：
```sh
git subtree pull --prefix=test_dir https://github.com/qw8880000/blog.git v1.0.1
```
