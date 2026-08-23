<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 010 プロジェクトバナー" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 010

### 写真を、白い紙に残る粗い黒の乾式画材による絵本シルエットへ

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#4つの出力を支えるひとつの白黒絵本ロジック)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#境界と信頼性)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 粗い黒シルエット · 内側の白い特徴 · 乾式画材と紙目 · 最小限の環境記号 · 絵本の小文字

XXD Panel 010 は、Codex と互換 Agent のための画像生成 Skill です。写真の主体、輪郭、姿勢、動き、関係を保ち、主役または重要な相互作用を、丸く厚みがあり少し素朴な粗い黒シルエット一体へ圧縮します。黒の内側に写真固有の白い特徴を一つ切り抜き、少ない情報でもすぐに識別できるようにします。

画面はほぼ純白の紙と濃い黒のクレヨン、木炭、乾擦だけです。短く力強い重ね塗りに紙目、途切れ、圧痕、毛羽立つ縁、濃度の揺れ、局所的な白を残します。一本の粗い地面線か数個の環境記号だけで、姿勢、距離、温かさ、ユーモア、孤独を支えます。

## なぜ 010 が必要なのか

一般的な「白黒絵本風」は、滑らかな黒アイコンや可愛いステッカーへ崩れがちです。輪郭が正確すぎ、形の内側から紙の呼吸が消え、主体が交換可能なマスコットになります。

010 は順序を逆にします。

```text
元写真の事実を固定 → 丸く厚い一つの相互作用単位へ圧縮 → 粗い黒の乾式画材で重ねる → 黒の内側に決定的な白い特徴を切る → 一つの姿勢／動き／距離／関係で語る → 最小限の環境記号と絵本の小文字で仕上げる
```

無関係な写真に替えてもシルエット、内側の白い特徴、姿勢、相互作用、環境記号、文言がほぼ成立するなら、それは 010 ではありません。

## 010 のビジュアル契約

- **シルエット一体：** 写真固有の手掛かりを三つ以上残し、身元、輪郭、姿勢、動き、機能、関係を保ちます。
- **丸く厚い形：** 頭、主輪郭、記憶点を必要な時だけ拡大し、重要な相互作用を一体として扱います。
- **完全な白黒：** ほぼ白い紙と濃い黒の乾式画材だけ。色、差し色、大きな灰色面、階調グラデーションはありません。
- **黒は粗いまま：** 力強いクレヨン、木炭、乾擦に紙目、途切れ、圧力、毛羽立つ縁を残します。
- **白い特徴は一つ：** 顔、窓、開口、動物の顔、物の中核などを黒の内側から切り抜きます。
- **環境は最小限：** 一本の地面線と少数の記号で草、雨、煙、机、道、風を示します。
- **関係の物語は一つ：** 一つの姿勢、動き、距離、相互作用が広い静かな余白で物語を担います。
- **絵本の編集文字：** 抑制した印刷小文字を中心に、ごく少量の不器用な手書きやクレヨン字を混ぜます。

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090083230317945129) · 2026-08-19<br>
> GPT2 x 剪影 x 黑白 x 粗蜡笔 x 美学提示词 x VOL.010

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 010 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 010 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 010 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 010 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090083230317945129">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 010 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 4つの出力を支えるひとつの白黒絵本ロジック

4つのモードは単独でも複数でも選択できます。`1`、`1+3`、`1、2、4`、`全部` と返信すると、Skill が重複を除き 1→4 の順で実行します。各モードは別々のタスクフォルダに独立出力され、一覧画像にはまとめません。`全部` は元写真1枚につき7点（通常3モード各1点＋壁紙4点）です。サイズはモード名付きで同時指定でき、未指定の通常モードは元画像に適応します。文案は既定で選択モード間に共通し、モード別指定も可能です。

| モード | サイズ方針 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 元画像適応 | 上に完全な元写真、下に 010 の粗い黒の乾式画材による絵本シルエット。両パネルは元画像サイズを保ち、厳密に 50/50 |
| `left-right` | 元画像適応 | 左に完全な元写真、右に 010 の粗い黒の乾式画材による絵本シルエット。両パネルは元画像サイズを保ち、厳密に 50/50 |
| `design-only` | 元画像適応 | 元写真を見せず、変化デザインだけを表示。元画像の比率と寸法を維持 |
| `wallpaper-pack` | 端末別4サイズ | スマートフォン、iPad、デスクトップ、子ども用ウォッチの PNG を個別出力 |

優先順位は、正確な指定ピクセル > 指定比率／用途 > 通常モードの元画像適応です。原稿 `010.md` の 3:4 は初期の制作画角であり、現在の暗黙の既定値ではありません。

ペアモードの写真は、抑制した調色と必要最小限の環境拡張だけで忠実さを保ちます。デザイン単独と壁紙では写真を根拠として使いますが、原片は表示しません。

### 壁紙セット：連動または独立

壁紙に暗黙のサイズ既定値はありません。一般プリセットはスマートフォン `1440×3200`、iPad `2048×2732`、デスクトップ `3840×2160`、ウォッチ `1024×1024`。端末別のカスタムサイズも指定できます。

- **連動セット（推奨）：** まず iPad の基準作品を生成・承認し、残り3枚は元写真＋同じ基準作品を参照して各画面に再構成します。
- **独立4作品：** 各端末は元写真だけを参照し、シルエット位置、白い特徴、乾式画材のリズム、環境記号、文字関係をそれぞれ探れます。

連動は切り抜きではありません。4枚を個別に生成、構成、検査し、iPad→スマートフォン→デスクトップ→ウォッチの順に参照を連鎖させません。

## 文字は白黒絵本構図の一部になる

生成前に、自動文案、カスタム文案、文字なしを選びます。文字を入れる場合は対象言語または地域も指定します。

自動文案は、写真から見える、または根拠のある感情、動き、関係、時間、小さな物語から短い題を作ります。温かく、抑制され、静かで、可笑しく、あるいは孤独でも、この画像と強く結びついていなければなりません。

必要に応じて1〜2組の小文字、根拠ある短句、番号、章記号を加えます。日付、場所、出典、番号はユーザー提供または確実な根拠が必要で、洗練を装うために捏造しません。

ユーザーが完成稿を渡した場合は一字一句保ちます。方向や編集可能な草稿の場合だけ、対象、目的、必須語、語調、含意を守りながら磨きます。

言語は命令文ではなく、想定する読者に従います。

```text
対象市場・読者 > 指定された成果物言語 > 方向指示の言語；不明なら生成前に確認
```

日本版は自然な現代日本語、韓国向けは自然な韓国語と正しい分かち書き、英国版は英国英語、アラビア語版は原則として自然な現代標準アラビア語と正しい右から左の組版を使います。外見、服装、風景、看板から国籍を推測せず、雰囲気づくりの偽外国語も使いません。

## 正確な幾何はコード、作品は画像生成

画像モデルが写真に結びついた粗い黒シルエット、決定的な白い特徴、実在感のある乾式画材と紙、最小限の環境記号、一つの関係物語、絵本の編集文字を作ります。`scripts/compose_panel.py` は画布計画、厳密な 50/50 ラスター合成、最終寸法、監査だけを担当し、プログラム描画で作品を偽装しません。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

正確な上下構成は総高さ、左右構成は総幅が偶数である必要があります。指定ピクセルは勝手に変更されません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-010.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-010" ~/.codex/skills/xxd-panel-010
```

Claude Code では同じフォルダを `~/.claude/skills/xxd-panel-010` にリンクできます。インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-010
この写真を左右二連にしてください。文案は写真の意味から作り、自然な韓国語を使ってください。
```

写真だけでも呼び出せます。番号付きの複数行メニューでモードと文字設定を確認し、壁紙では連動／独立と端末サイズも確認します。

詳細仕様：

- [Skill ワークフロー](SKILL.md)
- [中国語の完全プロンプト](references/xxd-panel-010-prompt.zh-CN.md)
- [英語の完全プロンプト](references/xxd-panel-010-prompt.en.md)
- [元のスタイル指示](references/010-source.md)

## 境界と信頼性

- 各写真は独立したタスク内だけで使い、他の入力、旧成果物、作例の主題、色、文案、構図を借りません。
- 呼び出すたびに新しいタスクフォルダを作り、同じ原画像と条件でも新たに生成します。
- 成果物は PNG ビットマップであり、SVG、HTML、Canvas、プログラム描画の代替物ではありません。
- 設定済みビットマップブリッジは匿名化した状態だけを返し、プロバイダー、エンドポイント、ヘッダー、認証情報、プロンプト、応答本文を表示しません。
- 選択した通常モードごとに1点を返し、`wallpaper-pack` を選ぶと独立壁紙4点を追加します。`全部` は元写真1枚につき7点を4つの同階層モードフォルダへ出力し、一覧コラージュにはまとめません。

ローカル合成には Python 3 と Pillow が必要です。安全なビットマップブリッジは Python 3.11+ の `tomllib` を使用します。画像生成には、ホスト Agent の内蔵ラスター生成機能または設定済みの互換ルートが必要です。

## リポジトリ

```text
xxd-panel-010/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/banner.svg + examples/（今後のローカル作例用）
├── scripts/compose_panel.py + configured_imagegen.py
└── references/xxd-panel-010-prompt.zh-CN.md + xxd-panel-010-prompt.en.md + 010-source.md
```

## XXD について

XXD は小小東（Xiaoxiaodong）のブランド名の略称です。このプロジェクトは [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) が制作・管理しています。

## サポートと会員制度

### 個別深度相談 · 1時間 CNY 299

Skills 利用に関する一対一相談は1時間 CNY 299です。下の WeChat QR コードから予約してください。

### Xiaoxiaodong Skills ユーザー交流グループ · CNY 99

一度 CNY 99 を支払うと、ワークフロー共有、作品相談、ユーザー同士の支援を行う交流グループに参加できます。時間制の個別相談は含まれません。

### 知識星球＋会員プロンプトライブラリ · 年額 CNY 699

[知識星球](https://wx.zsxq.com/group/15554814142882)と[XXD 会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)は同じ会員権です。**一度の年額決済で両方を利用でき、二重の購入は不要です。**

1. 知識星球で加入後、WeChat でプロンプトライブラリの交換コードを受け取る。
2. プロンプトライブラリで加入後、WeChat で知識星球への招待を受け取る。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD 有料サービス WeChat QR コード" width="320"></a>
</p>

<div align="center">

**黒は粗く、白は清く。一つの動きと一面の静けさだけで、関係は残せる。**

</div>

---

<div align="center">
  <h2>☕ オープンソースプロジェクトを支援</h2>
  <p>このプロジェクトが時間の節約になったなら、Star、共有、コーヒー一杯で継続を支援できます。</p>
  <table><tr><td align="center" width="240">
    <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee で Xiaoxiaodong を支援" width="180"></a><br>
    <strong>Buy me a coffee</strong><br><sub>QR コードを読み取るか開いて支援できます</sub>
  </td></tr></table>
  <p><sub>支援は任意であり、このオープンソースプロジェクトの利用権には影響しません。</sub></p>
</div>
