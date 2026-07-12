# 小红书轮播图生成提示词

## 生成方式

- 使用 `imagegen` 内置图像生成工具。
- 每张轮播图单独调用一次，不使用拼图批量生成。
- 图片和图片内文字均由 `imagegen` 生成。
- 未使用 CLI/API 回退路径。

## 统一视觉提示

```text
Use case: ads-marketing
Asset type: Xiaohongshu carousel post illustration, vertical 3:4 portrait poster.
Input images: approved father-and-toddler watercolor artist scene; approved text-free toddler Q-version character; approved existing sticker work grid.
Style/medium: premium Xiaohongshu marketing poster combined with the approved Q-version watercolor character style; warm paper texture, clear modern information-card layout, polished original illustration.
Color palette: warm white, coral orange, olive green, charcoal brown, and small yellow accents; no dominant purple or blue gradient.
Typography: large rounded bold Simplified Chinese, high contrast, mobile-readable.
Composition/framing: exact 3:4 portrait canvas, 8% safe margins, clear hierarchy, no cropped text or characters.
Constraints: render only the listed text verbatim; no QR code, phone number, external account, watermark, lorem ipsum, random English, invented UI text, exaggerated commercial promise, or unrelated logo.
```

## 01 封面

```text
Primary request: Create a cover poster for custom sticker commissions. Show the approved father and toddler Q-version characters in a warm creative studio with three text-free expression sample cards.
Text (verbatim):
"接表情包定制"
"真人照片变Q版"
"价格优惠 方案可谈"
"欢迎私信聊需求"
```

## 02 照片变 Q 版

```text
Primary request: Show a clear visual transformation from an original father-and-toddler photo card to the approved Q-version characters and then to a small set of expression cards.
Text (verbatim):
"你的照片 可以这样变"
"保留人物特征"
"统一Q版画风"
"表情文字一起设计"
"聊天场景更实用"
"一套专属于你的表情包"
```

## 03 可定制类型

```text
Primary request: Create a 2x2 service-category poster with original Q-version illustrations representing an individual, a parent-child family, a couple/friends, and pets.
Text (verbatim):
"这些都可以定制"
"个人Q版"
"亲子家庭"
"情侣好友"
"宠物萌化"
"也可做品牌形象和社群表情"
```

## 04 现有作品展示

```text
Primary request: Create a polished six-card gallery based on the supplied existing sticker grid. Preserve the recognizable toddler/father characters, expressions, and visual actions from the reference work.
Text (verbatim):
"现有作品展示"
"父子Q版表情包"
"16张完整表情"
"覆盖日常聊天场景"
The six reference sticker cards may retain their original short sticker phrases, but do not invent unrelated text.
```

## 05 定制流程

```text
Primary request: Create a clear four-step commission workflow poster with friendly icons and the approved father-and-toddler characters.
Text (verbatim):
"定制流程很简单"
"1 发参考照片"
"2 确认风格文案"
"3 制作并沟通修改"
"4 交付高清成品"
"价格按数量和需求沟通"
```

## 06 私信行动

```text
Primary request: Create a warm closing CTA poster. The approved toddler waves while the father smiles beside him, surrounded by a few text-free expression cards. The CTA should feel friendly rather than aggressive.
Text (verbatim):
"想做自己的表情包？"
"欢迎私信聊需求"
"价格优惠"
"方案可谈"
"一对一沟通"
"私信关键词：表情包"
```
