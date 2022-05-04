# Taro-hooks 案例

使用说明：

[编辑根目录的 cases.json 文件](https://github.com/taro-hooks/user-cases/edit/main/cases.json)，往对象里自行添加键值:

```json
{
  "projectNew": {
    "name": "（必填）用名",
    "url": "（必填）二维码图片地址",
    "description": "（必填）描述",
    "framework": "（可选） 开发使用的框架，例如： 'react' , 'vue2' , 'vue3' , 'nerv'",
    "taroVersion": "（可选）使用 Taro 的哪一个版本，例如 '1', '2', '3' 或者具体的版本又如 '3.2.0'",
    "screenshot": "(可选) 小程序截图 "
  }
  // ....
}
```

举例：

```json
{
  "taroHooksDemo": {
    "name": "示例小程序",
    "description": "taro-hooks 配套示例小程序",
    "url": "https://cdn.jsdelivr.net/gh/innocces/DrawingBed/2021-8-16/1629044960619-hooks.jpeg",
    "framework": "react",
    "taroVersion": "3.3.40",
    "screenshot": "https://cdn.jsdelivr.net/gh/innocces/DrawingBed/2022-05-04/1651597045121-taro-hooks-demo.PNG"
  }
},
```

修改完毕提交会提交 PR。合并后会在官网的使用案例中更新。

## 若无图片cdn. 可使用下方简单图床

[drawer-bed](https://general-tools.vercel.app/drawer-bed)
