# typescript-preview README

Preview the '.ts' file with '.js' in moment.（实时预览ts文件编译出的js）
> If you have some issue, just let me know https://github.com/win7killer/vscode-ts-preview [welcome star]

## preview version, welcome to try. (预览版本，欢迎尝鲜)
<img src="https://raw.githubusercontent.com/win7killer/vscode-ts-preview/master/images/command.gif" alt="command" width=600/>


## Features


## Requirements


## Extension Settings
```json
"ts-preview.mode": {
    "scope": "window",
    "type": "string",
    "enum": [
        "editor",
        "webview"
    ],
    "default": "editor",
    "description": "预览模式，编辑器模式和webview模式"
}
```

## Known Issues


## Release Notes

[see release log](https://github.com/win7killer/vscode-ts-preview/blob/master/./CHANGELOG.md)
-----------------------------------------------------------------------------------------------------------

**Enjoy!**

## To do list
- 修改文件后，预览文件关闭前会提醒是否保存，待处理
-  webview 版本的阅览处理  // done
- markdown.preview 模式
- 本地资源文件尝试引入【解决多主题样式文件】 // next
- 多栏情况测试，可能会有异常，比如原文件在第2栏，预览出现在第2栏
- 增加相应配置：
    - 字号
    - 提供几种主题色
    - 模式选择： editor | webview // done
    - ts编译配置：项目文件下优先配置tsconfig支持

