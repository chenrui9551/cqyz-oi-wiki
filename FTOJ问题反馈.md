### 管理员无法查看赛时全榜（只能看到普通用户）

由于部分学生作为管理员需要传题，但目前默认只显示非 `Super admin` 的用户排名


### `MLE` 误判为 `RE`
[record from tyl](http://oj.cqyz.cn/status/c3949c0411d234b6714f18e5b77280c2)
[record from lrc](http://oj.cqyz.cn/status/f6c70c61b7f5ebb4dac747b3e3832d94)

**初步调研查到 `judger/src/runner.c run()`**


### `markdown` 的 `\neq` 渲染比较糟糕
from nyh


### 题目描述里面公式后面的空格第一次编辑的时候会被吞，要再单独改一次
from nyh


### `__int_128` 编译失败
from lrc

**`clang` 不支持 `__int128`，暂时下掉 `clang`，未来改成单独的语言**
