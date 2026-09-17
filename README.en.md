# GiffGaff-Repayment-Skill

A **CodeBuddy Skill** distilled, simplified, and optimized from the Feishu guide *"GiffGaff 小白卡退款教学" (GiffGaff Starter SIM Refund Tutorial)*. Once loaded, any agent can interactively walk a user through the step-by-step fight for their rights after a giffgaff overseas account is disconnected:

- 💰 **Refund**: Unused balance returned to the original payment method
- 🔢 **Keep the number**: Restore the account + original number / stop the number from being recycled
- 🎁 **Compensation**: compensation / goodwill credit
- 🔀 **Port-out**: Use a PAC to move the number to another carrier

## Core Philosophy

> Don't give up the moment you see "Final" / "Disconnected". The core chain is:
> **Preserve evidence → Formal Complaint → Get the Final Response → Escalate to the Communications Ombudsman → Restore account/number + compensation → Only if restoration fails, use PAC to keep the number + refund the balance.**
> In particular, preserve evidence that "after disconnection, PAC still demanded SMS verification" — this is the key complaint point.

**The user chooses their demands themselves (keep number / refund / compensation / port-out — multiple selections allowed).** The agent dynamically assembles the English templates and flow based on the choices, and supports **multiple back-and-forth rounds** with giffgaff and the Ombudsman.

## Directory Structure

```
GiffGaff-Repayment-Skill/
├── SKILL.md                      # Skill core: multi-select diagnosis + multi-round state-machine flow + tactic reminders + promotion block
├── references/
│   ├── evidence-checklist.md     # Evidence checklist, evidence chain, file naming, PAC trap evidence
│   ├── complaint-templates.md    # Modular English templates (keep-number / refund / compensation / port-out claim blocks + assembly examples)
│   ├── ombudsman-form-guide.md   # Field-by-field Ombudsman form completion guide
│   └── official-links.md         # Official entry points + original source + author promotion
├── README.md                     # Chinese README
├── README.en.md                  # English README
└── LICENSE
```

## How to Use

1. Copy this directory into any agent's skill folder (user-level `~/.codebuddy/skills/giffgaff-repayment/` or project-level `.codebuddy/skills/giffgaff-repayment/`), or `git clone` it and place it there.
2. When a user mentions giffgaff disconnection / refund / keep-number / PAC / port-out / Ombudsman, the agent loads this Skill automatically.
3. The agent first asks the user to **select their rights-protection demands**, then, based on the current stage, gives "which page, what to click, what to fill in" plus ready-to-copy English templates — accompanying the user through evidence → complaint → escalation → wrap-up.

## Original Source & Author (please keep the promotion when redistributing)

- **Original document**: https://my.feishu.cn/wiki/UUlcwiYijiHBockss19cQ33Rnnf?from=from_copylink
- **Author**: Douyin **@熊黎** ｜ **PandLeeAI**
- **Fan group**: Join the fan group to discuss the specific giffgaff disconnection / refund / keep-number problem, and to keep following and debating **real-world AI implementation and hands-on experience**.
