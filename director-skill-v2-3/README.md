# 导演 Skill V2.3

把一句话中心思想、脚本、分镜或表达简报转成可执行、可调整、可验证的导演方案。调用名保持为：`$director-skill-v2-2`。

## 能力

新增 `ONE_LINE_INTENT` 入口：从一句主题命题或创作意图出发，先建立意义合同与授权边界，再由最终证明画面反推开场，形成主视觉锚点、行为词典、信息权限和 3–5 个策略节拍。完整主线为：意义 → 终态 → 规则 → 演出 → 验收，并继续覆盖人物调度、机位与运镜、构图与焦点、光色、声音、剪辑、时长和连续性。

## 安装与使用

下载本仓库，将完整目录命名为 `director-skill-v2-2`，放入你的 Codex skills 目录（通常是 `~/.codex/skills/`），保留 `SKILL.md`、`agents/` 和 `references/` 的相对结构。

示例：

> 使用 $director-skill-v2-2，为一个10秒竖屏短片设计逐镜方案，表达忙碌后重新拥有自己的空间。请给出机位、运镜、焦点、声音与剪辑。

一句话意图示例：

> 使用 $director-skill-v2-2，把“真正的自由不是逃离，而是不再害怕留下”导演成一个3分钟无对白短片。

本仓库可独立用于导演思路与分镜。最终模型提示词编译依赖另外安装的 `prompt-skill`；本仓库不包含该技能，不直接生成视频。

## 文件

- [SKILL.md](SKILL.md)：入口与工作流。
- [一句话意图展开](references/one-line-intent.md)：从中心思想建立意义合同、终态证明、行为规则与策略节拍。
- [学习方法](references/learned-methods.md)：方法的适用范围和来源。
- [导演合同](references/director-lock-schema.md)：DIRECTOR_LOCK v1，Codex 兼容结构1.3。
- [来源说明](references/provenance.md)与[上游许可证](references/upstream-licenses.md)：保留原作者署名及对应许可证，未将不同来源统一改为单一授权。

## 验证边界

已进行 Skill 结构校验、本地引用检查、10 组一句话导演方案和 5 项旧能力回归验证；不代表实际视频生成、实拍可行性、观众理解或商业效果已经验证。
