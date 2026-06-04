# Papi酱短视频创作方法论 — Kimi Work Skill

> 蒸馏Papi酱（姜逸磊）的短视频创作能力，覆盖脚本节奏、热点捕捉、镜头调度、一人分饰多角、变声加速等核心技术。

## 安装

将本仓库克隆到 Kimi Work 的 skills 目录：

```bash
# 方式一：直接克隆到 skills 目录
git clone https://github.com/Chenyu0914/papi-shortvideo-creator.git \
  ~/.kimi/daimon/skills/papi-shortvideo-creator

# 方式二：下载 .skill 包后解压
# 1. 下载 Release 中的 papi-shortvideo-creator.skill
# 2. 解压到 ~/.kimi/daimon/skills/papi-shortvideo-creator/
```

重启 Kimi Work 后，Skill 会自动加载。

## 触发关键词

当用户提到以下内容时，Skill 会自动触发：

- Papi酱、短视频创作、吐槽视频、脚本写作
- 视频节奏、热点捕捉、镜头调度、分镜设计
- 一人分饰多角、变声加速、后期制作
- 短视频爆款、喜剧节奏、内容方法论

## 仓库结构

```
papi-shortvideo-creator/
├── SKILL.md                          # Skill 核心文件（工作流 + 触发指令）
└── references/
    └── methodology.md                # 完整方法论报告（详细拆解）
```

## 内容概览

### SKILL.md — 核心工作流
- 5步创作SOP（选题 → 脚本 → 录制 → 后期 → 迭代）
- 关键禁忌清单（5条红线）
- 核心公式：高密度吐槽 = 加速变声 × 短镜头切换 × 笑点密集轰炸

### references/methodology.md — 完整报告
- **脚本节奏**：三段式结构、喜剧技法、评分机制
- **热点捕捉**：三层漏斗、选题矩阵、积累机制
- **镜头调度**：一人分饰多角、剪辑技术、变声参数、表演体系
- **可复用框架**：完整SOP流程图、禁忌清单

## 使用示例

安装后，在 Kimi Work 中直接提问：

> "帮我写一个吐槽职场PUA的短视频脚本，参考Papi酱的风格"

Kimi 会自动加载本 Skill，按照 Papi酱 的方法论输出：
- 0-3秒强钩子设计
- 并列式吐槽矩阵
- 一人分饰多角的角色分配
- 后期加速和剪辑建议

## 打包为 .skill 文件

```bash
cd ~/.kimi/daimon/skills
zip -r papi-shortvideo-creator.skill papi-shortvideo-creator
```

## License

MIT — 自由使用、修改和分发。

## 贡献

欢迎提交 Issue 和 PR，补充更多 Papi酱 作品的分析案例。
