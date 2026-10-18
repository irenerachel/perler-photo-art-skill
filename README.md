# 拼豆艺术化转绘 · Perler Photo Art

将照片或插画中的主体转绘为圆孔拼豆图形，配合平滑的二维插画环境，支持构图美化与像素字体海报。

Turn a subject from a photo or illustration into round, hole-centered perler bead art, paired with a smooth illustrated environment. Includes composition refinement and optional pixel-type posters.

[中文说明](#中文说明) · [English guide](#english-guide) · [案例 / Gallery](#案例--gallery) · [完整 Skill / Full skill](SKILL.md)

## 案例 / Gallery

四组原图与成图对照，保留选定版本的原始文件。左侧为输入，右侧为生成结果。

Four selected before-and-after pairs, preserving the original files of the chosen versions. Inputs are on the left; generated results are on the right.

### 1. 探头猫咪与像素海报 · Peeking cat poster

| 原图 / Input | 成图 / Result |
| :---: | :---: |
| <img src="examples/cat/before.jpg" width="360" alt="从门框后探头的虎斑猫原图 / Original tabby cat peeking around a doorframe"> | <img src="examples/cat/after.png" width="360" alt="探个头看看你像素字体拼豆猫咪海报 / Peeking cat perler poster with pixel typography"> |

圆脸、短身与简化条纹形成亲近的角色形象，配合像素字体和少量装饰。这是早期海报案例，背景保留较多摄影质感；新任务默认采用 Skill 中的二维插画背景规则。

A rounded face, compact body and simplified stripes create a friendly character, paired with pixel typography and small decorative accents. This early poster retains photographic background qualities. For new work, the skill defaults to a smooth illustrated background.

### 2. 蒸汽机车人物 V1 · Steam locomotive portrait, V1

| 原图 / Input | 成图 / Result |
| :---: | :---: |
| <img src="examples/train/before.jpg" width="360" alt="机车前抱臂抬腿的人物原图 / Original portrait in front of a steam locomotive"> | <img src="examples/train/after.png" width="360" alt="机车人物拼豆转绘 V1 / Selected V1 perler portrait with locomotive"> |

保留抱臂抬腿的姿态与奶油白、深棕服装配色，强化人物和机车的构图关系。收录的是选定的 V1，颗粒触感更饱满；它用于说明该版本的审美取舍，严格单层任务仍按 Skill 的平面结构约束执行。

Preserves the crossed arms, raised leg, cream jacket and dark trousers while strengthening the composition. The selected V1 has a fuller bead texture. It illustrates a specific aesthetic choice; tasks requiring a strictly single-layer structure still follow the skill's flat-form rules.

### 3. 水晶器皿 · Ornamental crystal vessel

| 原图 / Input | 成图 / Result |
| :---: | :---: |
| <img src="examples/vessel/before.jpg" width="360" alt="绿色展柜中的透明装饰器皿原图 / Original ornamental vessel in a green display cabinet"> | <img src="examples/vessel/after.png" width="360" alt="蓝金白色拼豆器皿与插画展柜 / Blue, gold and white bead vessel with illustrated display cabinet"> |

以奶白、冰蓝、金色和留空概括器身、装饰与透明感，背景简化为墨绿展柜和浅色展台。细小连接与镂空属于视觉表达，未作实体结构验证。

Cream, ice blue, gold and open spaces suggest the vessel's structure, ornament and transparency. The setting is simplified into a dark green cabinet and a light display stand. Fine connections and cutouts are visual interpretations, without physical construction validation.

### 4. 新艺术人物装饰画 · Art Nouveau figure

| 原图 / Input | 成图 / Result |
| :---: | :---: |
| <img src="examples/art-nouveau/before.png" width="360" alt="新艺术风格女性装饰画原图 / Original Art Nouveau figure illustration"> | <img src="examples/art-nouveau/after.png" width="360" alt="金发珊瑚色长裙人物拼豆装饰画 / Perler interpretation of a golden-haired figure in a coral dress"> |

保留修长坐姿、金色卷发、珊瑚色长裙与圆形装饰框，用色彩分区表达人物和裙褶。案例展示人物比例与装饰语言的延续；新任务仍需逐区检查背景及边框的材质。

Retains the elongated seated pose, golden curls, coral dress and circular ornament. Color regions describe the figure and folds. The example shows continuity of proportion and decoration; background and border materials still require region-by-region checks in new work.

## 中文说明

### 能做什么

- 从当前图片判断主体，保留身份、姿态、配色和关键结构。
- 将指定主体转为规整圆孔拼豆，区分整体平面结构与单颗颗粒触感。
- 将其余画面重绘为连续色面、流畅线条和柔和图形阴影构成的二维插画。
- 根据图片优化裁切、比例、留白与视觉重心。
- 默认输出无字纯图；明确要求海报时加入像素字体与场景合理的前景。

### 核心分区

| 区域 | 内容 | 表现方式 |
| --- | --- | --- |
| A：拼豆主体 | 本次明确选定的对象及部位 | 单层、规整、圆孔塑料拼豆 |
| B：平面环境 | A 之外的背景、前景、承托物、装饰、边框和空隙 | 平滑二维插画，无拼豆颗粒 |
| C：文字排版 | 明确要求的标题、文案与排版图形 | 平面像素字体及图形 |

A 与 B 覆盖全部内容画面且互不重叠，C 为可选叠加层。每张新图重新划分；实际生图提示词必须写出对象清单与边界。统一配色、构图和光向，让不同材质协调。

### 安装与使用

1. 下载本仓库 ZIP 并解压，将文件夹命名为 `perler-photo-art`。
2. 将文件夹放入你的 Agent 支持的 skills 目录。Codex 通常使用 `~/.codex/skills/perler-photo-art/`，Claude Code 通常使用 `~/.claude/skills/perler-photo-art/`；以当前平台的实际配置为准。
3. 上传要处理的照片或插画，指定使用 `perler-photo-art`。

支持 Skill 文件导入的 Agent 可以直接导入 `SKILL.md`。只有对话输入能力时，将完整正文作为指令提供给 Agent，并附上当前图片。全部执行规则、中文提示词模板和验收标准均内嵌在 `SKILL.md`，无需点击外部链接。案例图片可选。

**纯图示例**

```text
使用 perler-photo-art 处理我上传的图片。先确定拼豆主体与平面环境的范围，将主体转为圆孔拼豆图形，其余背景、前景和装饰统一重绘为平滑二维插画。保留身份与主要姿态，适当美化构图。输出一张无字纯图。
```

**海报示例**

```text
使用 perler-photo-art，将我上传的图片制作成像素字体海报。主体为圆孔拼豆图形，环境和装饰为平滑二维插画，文字使用平面像素字体。主标题写“今天也有小美好”，不添加其他文案。保留主体身份与主要动作，根据场景安排合理前景和留白。
```

### 文件与执行方式

- `SKILL.md`：完整中文 Skill、材质规则、模板、案例说明与验收标准。
- `agents/openai.yaml`：Codex 界面配置。
- `examples/`：四组原图与成图，共 8 张图片。
- `examples/manifest.json`：案例图片 SHA-256 校验值。

Skill 提供创作流程，需要使用所在 Agent 已有的图像生成或编辑能力。只有文字能力时，按 Skill 输出完整可用的提示词。案例属于风格探索结果；当前正文规则与用户当次要求决定新任务的执行方式。此 Skill 面向艺术化转绘，实体拼豆制作需要另做网格、色号、豆量及连接结构设计。

## English guide

### What it does

- Identifies the subject in the current input and preserves identity, pose, colors and recognizable structure.
- Converts selected subjects into regular, round, hole-centered perler bead graphics, separating overall flatness from the tactile surface of individual beads.
- Redraws the remaining scene as smooth color areas, flowing lines and soft graphic shadows.
- Refines cropping, scale, negative space and visual balance.
- Produces an image without added text by default. Explicit poster requests enable pixel typography and foreground elements grounded in the scene.

### Material regions

| Region | Content | Treatment |
| --- | --- | --- |
| A: bead subject | Specifically selected objects and parts | Regular, single-layer plastic beads with round holes |
| B: illustrated environment | Everything outside A, including background, foreground, supports, decoration, borders and gaps | Smooth 2D illustration without bead texture |
| C: typography | Explicitly requested titles, copy and layout graphics | Flat pixel typography and graphic elements |

A and B cover the entire content image without overlap. C is an optional overlay. Define these regions again for each new image, and include their object lists and boundaries in the actual image-generation prompt. Coordinate color, composition and lighting across the different materials.

### Installation and use

1. Download and extract the repository ZIP. Rename the extracted folder to `perler-photo-art`.
2. Place it in your agent's supported skills directory. Typical personal locations are `~/.codex/skills/perler-photo-art/` for Codex and `~/.claude/skills/perler-photo-art/` for Claude Code. Follow your platform's actual configuration.
3. Attach a photo or illustration and ask the agent to use `perler-photo-art`.

Agents that support skill-file imports can load `SKILL.md` directly. For chat-only interfaces, paste its full contents as instructions and attach the current image. All operating rules, Chinese prompt templates, case descriptions and review criteria are embedded in the file. No external document links are required, and example images are optional.

For a text-free result, ask the agent to select the bead subject, redraw the remaining scene as smooth illustration, preserve the main pose and refine the composition. For a poster, also specify the exact title, copy and desired aspect ratio. The executable skill and copy-ready prompt templates are written in Chinese; this README provides both Chinese and English documentation.

### Files and execution

- `SKILL.md`: complete Chinese instructions, material rules, templates, case descriptions and review criteria.
- `agents/openai.yaml`: Codex interface configuration.
- `examples/`: four before-and-after pairs, totaling eight image files.
- `examples/manifest.json`: SHA-256 checksums for the example images.

This skill defines a creative workflow and uses the image-generation or editing capabilities available in the host agent. A text-only agent returns a complete prompt. The gallery records selected exploratory results; the current written rules and the user's instructions govern new tasks. Physical bead construction requires separate grid, palette, bead-count and structural planning.
