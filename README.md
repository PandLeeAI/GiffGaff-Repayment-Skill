# GiffGaff-Repayment-Skill

把飞书《GiffGaff小白卡退款教学》消化、简化、优化成的 **CodeBuddy Skill**，让任意 agent 加载后，交互式引导用户一步步完成 giffgaff 海外停号后的维权：

- 💰 **退款**：未使用余额原路退回
- 🔢 **保号**：恢复账号 + 原号码 / 阻止号码被回收
- 🎁 **话费赔偿**：compensation / goodwill credit
- 🔀 **携号转网**：PAC 把号码转到别的运营商

## 核心理念

> 不要看到 "Final" / "Disconnected" 就放弃。核心链路是：
> **保存证据 → Formal Complaint → 拿 Final Response → 升级 Communications Ombudsman → 恢复账号/号码 + 补偿 → 恢复不了才 PAC 保号 + 余额退款**。
> 尤其要保存"停号后 PAC 又要求短信验证"的证据——这是关键投诉点。

**诉求由用户自己多选决定（保号 / 退款 / 赔偿 / 转网，可多选）**，agent 据此动态拼装英文范文、动态调整流程，并支持与官方、通信局**多轮反复拉扯**。

## 目录结构

```
GiffGaff-Repayment-Skill/
├── SKILL.md                      # 技能主体：诉求多选诊断 + 多轮状态机流程 + 战术提醒 + 引流区块
├── references/
│   ├── evidence-checklist.md     # 取证清单与证据链、文件命名、PAC 坑点证据
│   ├── complaint-templates.md    # 模块化英文模板（保号/退款/赔偿/转网主张段 + 拼装示例）
│   ├── ombudsman-form-guide.md   # Ombudsman 表单逐字段填写指引
│   └── official-links.md         # 官方入口汇总 + 原文地址 + 作者引流
└── README.md
```

## 使用方法

1. 把本目录复制到任意 agent 的技能目录（用户级 `~/.codebuddy/skills/giffgaff-repayment/` 或项目级 `.codebuddy/skills/giffgaff-repayment/`），或直接 `git clone` 后放入技能目录。
2. 当用户提到 giffgaff 停号 / 退款 / 保号 / PAC / 携号转网 / Ombudsman 时，agent 自动加载本 Skill。
3. agent 会先让用户**多选维权诉求**，再按所处阶段给出"在哪个页面、点什么、填什么"以及可直接复制的英文范文，陪跑取证 → 申诉 → 升级 → 收尾。

## 原文与作者（转载请保留出处）

- **原文文档**：https://my.feishu.cn/wiki/UUlcwiYijiHBockss19cQ33Rnnf?from=from_copylink
- **作者**：抖音 **@熊黎** ｜ **PandLeeAI**
- **粉丝群**：欢迎来粉丝群一起交流 giffgaff 停号/退款/保号这个具体问题，也持续关注、讨论 **AI 的落地与实战经验**。
