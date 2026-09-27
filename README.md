# Jiawei Image Prompts

嘉伟导演工作台的个人图像提示词技能，面向故事视觉开发与可复用资产制作。

## 支持范围

- Midjourney 8.2：文生图、参考图、风格化与参数微调。
- GPT Image 2 / 2.5：图像生成、参考图编辑和多图约束。
- Nano Banana：参考图驱动的生成与局部编辑。
- 角色、场景、道具资产，以及风格提取、迁移和一致性约束。

技能会先判断任务目标与参考图的作用，再组织模型适配的提示词；它负责提示词创作与检查，不会调用图像生成 API，也不会要求用户把密钥贴进聊天。

## 安装

将 `SKILL.md` 放进 Codex 的个人技能目录：

```text
~/.codex/skills/jiawei-image-prompts/SKILL.md
```

Windows 常见位置：

```text
%USERPROFILE%\\.codex\\skills\\jiawei-image-prompts\\SKILL.md
```

安装或更新后，按 Codex 的技能发现机制重新加载技能，或重启 Codex。

## 许可

本仓库未附带开源许可证。公开可见不等于授予额外的复制、修改或再分发许可。
