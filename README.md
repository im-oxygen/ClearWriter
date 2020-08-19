# Welcome to Clear Writer，这是一个沉浸式 Markdown 写作软件。

## 为什么编写 Clear Writer

我开了我自己的博客之后，一直苦于 Windows 端没有我喜欢的 Markdown 编辑器。

> 其实写作，最需要的并不是很好很强大的工具，而是一个不易让人分心的环境。

Mac上的 iA Writer 固然能很好地做到这一点，但作为一个初二学生，我确实也没有那个经济实力去买正版。我也不打算用盗版。我找到了一个类似的软件，叫做 [4Me 写字板](http://write4Me.sinaapp.com/)。它基于 CodeMirror。但是，它和 iA Writer 的差距未免有点大……

但这却给了我一个启发：为什么不自己动手试着用 CodeMirror 制作一个 Markdown 编辑器呢？

于是我征求了原作者同意之后，借着这次因新冠疫情宅家的时间，尝试自己以 4Me 写字板为蓝本，制作自己的写作工具。于是我做出了这个 Markdown 编辑器 —— Clear Writer，意味着希望人们使用它时，可以让人理清自己的思维。

另外，Clear Writer 的一个很重要的一点是它支持实时 Markdown 语法。很多的所谓实时 Markdown，我都不是很喜欢——因为它们会把 Markdown 格式标记隐去。我不喜欢这样，我喜欢让格式牢牢掌控在使用者的手里。

## Clear Writer 的特点
- 全自动保存；
- 所见即所得的实时 MarkDown，以及标题悬挂；
- 支持亮色 / 暗色模式；
- 漂亮的隐藏式滚动条；
- 支持简体中文 / 繁体中文 / 英文三种语言；
- 支持开启 / 关闭行号；
- 高亮当前段落；
- 漂亮的光标闪动和跳动效果；
- 界面自适应；
- 内容全部在本地缓存，完全隐私保护；
- 支持导出 `.txt`、`.md`、`.doc`、`.html`、带 CSS 的 `html` 5 种格式；
- 平滑滚动；
- 基于 Github Gist 的云同步功能；
- 可让你立即进入状态的”闪念“功能。

## 屏幕截图

![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/1.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/2.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/3.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/4.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/5.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/6.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/7.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/8.png)
![](https://github.com/Henrylin666/ClearWriter/raw/master/screenshots/9.png)


## 使用技巧

- 点击顶栏上的全屏按钮或按下 `F11`（或 `Fn + F11`）切入全屏，安心写作；
- 鼠标移动至顶部时显示顶栏，其中可以切换亮/暗色模式、行号、语言等；
- 点击顶栏上的图钉 `??` 按钮可以固定顶栏，使其不自动隐藏；
- 右上角有 `另存为...` 按钮，点击可以将文字导出为其他格式文本；
- 点击左上角的 `Clear Writer` 会在侧边栏显示你现在正在看的这段文字，再次点击 `Clear Writer` 隐藏侧边栏；
- 可撤销最近的 2000 次操作，无惧修改；
- Clear Writer 全自动保存，正常情况下每 3 分钟自动保存一次，在关闭的时候也会再次自动保存一次。实在不放心，还可以 `Ctrl + S` 手动保存；
- 查找：`Ctrl + F`；
- 查找下一个：`Ctrl + G`；
- 查找上一个：`Shift + Ctrl + G`；
- 替换：`Shift + Ctrl + F`；
- 替换全部：`Shift + Ctrl + R`。

## 兼容性

Windows 7 及以上。

## 关于

Clear Writer 使用 GNU General Public License 3.0 进行许可。

编码工具：Visual Studio
安装包制作工具：NSIS

### Clear Writer 的诞生离不开：

- 西文字体：NeverMind（SIL Open Font License 1.1）；
- 中文字体：思源黑体（SIL Open Font License 1.1）；
- 编辑器基础：CodeMirror（MIT License）；
- Markdown 渲染：editor.md（MIT License）；
- 构建基础：Electron（MIT License）；
- 蓝本：4Me Writer，无协议状态，但已经开发者口头许可。

衷心感谢所有为本项目提供支持与帮助的人。

## 更新日志

### v2.0

- 新增亚克力效果选项（需要在“设置”中手动开启，仅支持 Win10 1803+，不支持全屏模式）；
- 弃用思源黑体，将内置默认字体改为更纱黑体 UI SC（仍基于思源黑体），提升字体渲染效果及字库大小；
- 全面支持多光标输入（按下 Ctrl 并左键单击可以新建光标）；
- 修复默认字体下输入代码块需要等待一会儿才能加载出等距字体的问题
- 上线全新反馈社区；
- 修复了使用微软拼音 IME 输入时拼音采用等距字体显示的问题；
- 修复了使用微软拼音 IME 输入时选字框遮挡当前拼音的问题；
- 修复了语言为英语时预览功能异常的问题；
- 优化了一些动画效果的速度曲线；
- 新增开发人员工具入口，方便使用时定位 bug；
- 优化程序图标显示，解决圆角部分的锯齿现象；
- 新增替换快捷键 `Ctrl+H`；
- 实现响应式 UI，优化在小窗口下的体验；
- 优化打开超长文件名的文件时标题栏的显示；
- 颠倒暗色模式的主背景色和副背景色，优化体验，同时进行了按钮样式的微调；
- 修复了选中多行文本的时候选中部分色块在左侧会溢出的状况；
- 修复了选中多行文本的时候出现色块堆积的状况；
- 新增右键菜单项目图标；
- 新增删除文件时的确认动画；
- 修复了启动时加载 logo 无法使用主题色的情况；
- 优化替换时的工具栏，使其与查找工具栏统一，同时在替换的时候增加高亮；
- 新增双色图标；
- 修复了使用微软拼音 IME 时，选字框会遮挡文字的情况；
- 新增英文下的自动括号匹配；
- 实现在文件资源管理器中双击 `.md` 文件后直接用 Clear Writer 打开；
- 修复了在暗色模式下删除线显示不明显的问题；
- 新增开启行号时，当前行行号高亮效果；
- 新增自定义 CSS 功能，允许用户自己定义 Clear Writer 的 CSS 代码；
- 修改字体存储方式，缩小程序大小，提高渲染速度；
- 优化打开右键菜单时的动画；
- 优化预览窗口内容样式，增强可读性；
- 优化预览中 To-do 列表复选框的样式；
- 优化弹窗关闭按钮的样式；
- 新增按钮鼠标悬浮提示；
- 优化左侧栏的动画效果；
- 修复顶栏左侧的彩色按钮在 Win 7 下显示为黑白的情况；
- 加入自动检查更新的组件；
- 新增设置面板中的图标；
- 实现利用 Github Gist 同步文件和设置；
- 新增语言：英语（英国）；
- 新增“预览”中外部超链接后面的提示图标；
- 修复点击“打开文件”按钮后保存模块出现问题的 bug；

### v1.8

- 引入等距更纱黑体作为等宽字体；
- 新增统一的设置面板；
- 支持在全局使用等宽字体；
- 新增查找时的工具条；
- 优化超长文件名的显示；
- 优化启动时长；
- 顶栏改版，引入 Font Awesome，使用图标代替文字，取消选项卡；
- 提高标题悬挂组件的稳定性。

### v1.7

- 新增新建文件时的回车快捷确认；
- 修复标题中插入 HTML 标签时的异常；
- 新增禁用动画选项，以保证能在低配置环境下运行；
- 新增查找栏的动画效果；
- 修复程序体积过大的问题；
- 大幅缩短程序加载时长；
- 新增 `html` 和 `带 CSS 的 html` 的文件另存支持。

### v1.6

- 优化主题色选择，支持直接跟随系统主题色（仅 Windows 10）；
- 优化亮色/暗色模式适配，支持跟随系统亮色/暗色模式（仅 Windows 10）；
- 新增全新的开始屏幕磁贴（仅 Windows 10）；
- 修复“预览”窗格中 HTML 代码块未被正常高亮的问题；
- 在正文编辑的代码块中使用等宽字体 Consolas，带来原汁原味的代码风；
- 新增对 Python、PHP、ruby 和 go 语言的代码块高亮支持；

### v1.5
- 修复两个弹窗并行时的一个 BUG；
- 修复“折叠”“剪切”按钮未翻译的问题；
- 修复了全屏模式下点击最大化/还原按钮无反应的 BUG；
- 新增打开、切换文件时标题栏的切换动画；
- 新增“另存为”格式：.md、.doc；
- 新增预览时的代码块高亮；
- 新增删除文件时的“取消”按钮；
- 新增覆盖输入模式下（按Insert键进入）的特有光标，以和插入模式区别开来

### v1.4
- 修复了在重命名文件之后文件内容丢失的 BUG； 
- 修复了在切换文件后快捷键定义重复现象的 BUG；
- 抛弃系统自带的标题栏，自己做了一个更漂亮的；
- 新增统计功能（统计的是最终生成的文本，不包含 Markdown 语法字符）。

### v1.3
- 更新内核为 Chromium 82；
- 支持更改主题色（”主题“组下），自定义你的 Clear Writer；
- 标题栏优化：鼠标悬停在组标题上时才显示按钮；
- 大幅缩短切换文件、切换语言的用时；
- 优化语言切换方式；
- 增加右键菜单项目，现支持 11 种操作，如加粗、斜体等，解救鼠标党；
- 在标题栏的”工具“组下新增”查找“”查找下一个“”替换“按钮，解救鼠标党；
- 新增 Markdown 标题段落折叠。

### v1.2
- 新图标；
- 新增预览窗口。

### v1.1
- 新增右键菜单；
- 新增“从文件新建”功能。