<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 010 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 010

### 把照片压缩成近白纸面上的粗黑干媒介童书剪影

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种黑白童书逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 粗黑剪影 · 内部白色特征区 · 干媒介纸感 · 极少环境记号 · 童书编辑小字

XXD Panel 010 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它保留照片中的身份、轮廓、姿态、动作与关系，把主体或关键互动压缩成一个圆润、敦厚、略带稚拙感的粗黑剪影视觉单元；黑色内部突然切出一个源图专属的白色特征区，让极少信息仍能一眼辨认。

画面只有近乎纯白的纸面与浓黑蜡笔、炭笔或干擦痕迹。短促有力的反复涂抹保留纸粒、断笔、压痕、毛糙边缘、浓淡不均和局部露白；一条地面摩擦线或几枚环境记号就足以承托姿态、距离、温软、幽默与孤独。

## 为什么需要 010

普通“黑白童书风”很容易退化成光滑黑图标或可爱贴纸：轮廓过度精确、内部没有纸张呼吸，人物只剩一个可替换的萌系符号。

010 的顺序完全相反：

```text
锁定源图事实 → 压缩为一个圆润敦厚的互动单元 → 用粗黑干媒介反复涂抹 → 在黑色内部切出一个决定性白色特征区 → 让一个姿态／动作／距离／关系承担叙事 → 用极少环境记号与童书编辑小字完成
```

如果换成一张无关照片，剪影轮廓、内部白色特征区、姿态、互动、环境记号和文字仍然成立，这张图就不属于 010。

## 010 的视觉契约

- **一个剪影单元：** 至少三个源图专属线索保住身份、轮廓、姿态、动作、功能与关系。
- **圆润而敦厚：** 可适度放大头部、主轮廓或记忆点，多主体则保留最重要互动而不平均分焦点。
- **绝对黑白：** 只用近白纸面与浓黑干媒介；无彩色、彩色点缀、大面积灰色或灰阶渐变。
- **黑色必须粗糙：** 短促有力的蜡笔、炭笔或干擦痕迹保留真实纸粒、断笔、压痕与毛边。
- **一个白色特征区：** 在黑色内部切出脸、窗洞、开口、动物面部或物件核心等决定性识别结构。
- **环境极少：** 一条粗糙地面线、几根短线或少量符号即可提示草、雨、烟、桌面、道路或风。
- **一个关系叙事：** 只让一个姿态、动作、距离或互动承担故事，留白保持安静空旷。
- **童书编辑文字：** 克制印刷小字为主，只加入极少笨拙手写、蜡笔字或不规则字形。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090083230317945129) · 2026-08-19<br>
> GPT2 x 剪影 x 黑白 x 粗蜡笔 x 美学提示词 x VOL.010

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 010 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 010 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 010 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 010 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129">查看原推文与完整提示词 →</a></p>

这些样张用于展示 010 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，010 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，010 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 010 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 文字必须成为黑白童书构图的一部分

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从源图可见或有依据的情绪、动作、关系、时间或微小故事中提炼一个简短标题。它可以温软、克制、安静、幽默或孤独，但必须与当前画面高度绑定。

再按需增加一至两组极小辅助文字、金句式短句、编号或章节号。日期、地点、出处与编号必须由用户提供或可靠确认，绝不会为了显得高级而伪造。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。字体会在当地文字系统中寻找克制编辑小字与少量稚拙手作字的自然等价物，不会把拉丁手写规则生硬套过去。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-010.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-010" ~/.codex/skills/xxd-panel-010
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-010`。安装后重新启动 Agent 会话。

```text
$xxd-panel-010
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-010-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-010-prompt.en.md)
- [原始风格提示词](references/010-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-010/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-010-prompt.zh-CN.md
    ├── xxd-panel-010-prompt.en.md
    └── 010-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**黑要粗，白要净；一个动作和一块留白，就足够把关系留下。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
