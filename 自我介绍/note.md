[生成剧本指令]
请为我生成一个 1 分钟极致写实短剧剧本。

- 时长：60秒
- 画幅：--ar 16:9
- 核心概念：现代极简房间内，一个女生向镜头做极简自我介绍，坦白自己是 AI LLM 生成的虚拟存在。
- 视听特征：极致电影写实（Hyper-photorealistic）；窗外有大雨声与突发雷声（人物需有微观且自然的物理反应 beat，拒绝夸张表演）；彻底无旁白。
- 剧情与镜头：请自主安排剧情起伏与人物 movement。

请严格按《通用剧本生成器》的 Schema 契约输出：包含封面头（确定 Style Key）、角色 Manifest（含英文写实 Face Baseline 与造型 Prompts）、以及带三轨音频规划的正文幕段。


[生成分镜指令]
请读取上文生成的完整剧本 Markdown，严格按照《AI 视频物理分镜转换器》规范，将其转换为标准化的分镜列表（Shot List）。

要求：
1. 先发 Scene 1 Baseline 卡，锁定雨雷声的声音基准。
2. 每镜严格按 5 段式输出（静态首帧 Prompt、动态视频 Prompt [Visual Only]、音频 Prompt [Audio Only]、口型重绘策略、剪辑端）。
3. 动态 Prompt 注入写实电影 Style Key 串（cinematic photorealistic, Arri Alexa LF capture, naturalistic lighting contrast, 8k resolution）。
4. 雷声时刻在动态 [Visual Only] 中注入“主导面部微动作 ≤1/镜”的反应（如 pupil contracts for a split second），并在 Audio 区标注爆响与雨声 Foley。
5. 静态与动态 Prompt 末尾强制追加 `--ar 16:9`。
