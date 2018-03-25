

## effectTag的所有含义与可应用的组件

| 操作     | 含 义          | No | class Component | stateless | native Component | native text |
|----------|----------------|----|-----------------|-----------|------------------|-------------|
| RLACE    | 插入DOM树      | 2  | ✖️              | ✖️        | ✔️               | ✔️          |
| ATTR     | 修改属性       | 3  | ✖️              | ✖️        | ✔️               | ✖️          |
| CONTEXT  | 修改文本       | 5  | ✖️              | ✖️        | ✖️               | ✔️          |
| NULLREF  | 清除引用      | 7  | ✔️              | ✔️        | ✔️               | ✖️          |
| HOOK     | 生命周期回调   | 11  | ✔️              | ✖️        | ✖️               | ✖️          |
| REF      | 设置引用 | 13 | ✔️              | ✔️        | ✔️               | ✖️          |
| DETACH   | 移出DOM树      | 17 | ✖️              | ✖️        | ✔️               | ✔️          |
| CALLBACK | 方法回调       | 19 | ✔️              | ✔️        | ✔️               | ✔️          |
| CAPTURE  | 错误处理       | 23 | ✔️              | ✖️        | ✖️               | ✖️          |