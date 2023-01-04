
# alistdown

alistdown是一个直接获取alist指定文件路径的下载链接接口


## 使用说明

使用前请在代码中补充alist的网址、账户、密码
#### 获取所有项目

```http
  GET
```

| 参数 | 类型     | 描述                |
| :-------- | :------- | :------------------------- |
| `d` | `string` | **必选**. alist文件路径 |
| `p` | `string` | **可选**. slist文件路径密码 |

#### 返回值为下载链接
