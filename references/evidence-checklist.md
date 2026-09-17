# 取证清单（Evidence Checklist）

> 在**做任何操作之前**先取证。尤其要趁 giffgaff 账号还能登录时，立刻截图保存。一旦账号被彻底关闭，很多证据就再也拿不到了。

## 一、必须保存的证据（逐项截图/导出）

1. **giffgaff 停号通知邮件**（收件邮箱最好别暴露成 QQ 邮箱；可 PS 处理、或不暴露收件邮箱、或浏览器 F12 自己改代码后再截图）
2. **giffgaff Account 页面**（显示手机号、Credit 余额、Active plan）
3. **手机号码**（如 `07561123456`）
4. **当前 Credit 余额**（如 `£9.40`）
5. **充值记录**（银行卡 / PayPal 扣款凭证）
6. **使用记录**（如有）
7. **客服聊天记录**（Help / Messenger 对话）
8. **Formal Complaint 内容**（提交时的正文）
9. **Complaint Ticket**（Reference + Ticket ID，状态变化 Submitted→In Progress→Resolved 都要截）
10. **giffgaff 后续 Final Response**（邮件或 Messenger 里的完整回复）

> 关键证明目标：**账户号码仍存在 + PAYG 余额仍存在 + 未使用余额金额**。例如账户里能看到 `Mobile number：07561123456` / `Credit：£9.40` / `Active plan：None`，就能证明"号码还在、余额还在、多少钱没用"。

## 二、证据文件命名（按时间顺序，方便提交 Ombudsman）

给文件直接编号，形成一条清晰证据链：

| 文件名 | 内容 |
|---|---|
| `01_Disconnection_Notice.pdf` | 最开始的停号通知 |
| `02_Account_and_Credit.png` | Account 页面，显示手机号和剩余余额 |
| `03_Formal_Complaint.pdf` | 正式投诉内容 |
| `04_Complaint_Ticket.png` | 显示 Ticket ID、Submitted/In Progress/Resolved |
| `05_Final_Response.pdf` | giffgaff 最终回复 |
| `06_PAC_SMS_Verification.png` | 证明 PAC 需要向已停用的号码发验证码（核心坑点） |
| `07_Topup_Payment.pdf` | 充值 / 银行卡支付记录 |

- Final Response 若只存在于 Messenger 里、没有独立 PDF：打开完整消息 → `Ctrl + P` → 存为 PDF，或完整截图保存。
- **不要为了显得证据多，上传几十份重复图片。** 最重要的是形成证据链：
  > 充值/正常账户 → 突然停号 → Formal Complaint → Final Response → PAC 要求短信验证但号码已被停 → 剩余余额/号码权益受影响。

## 三、核心坑点证据（务必单独留存）

**PAC 短信验证坑**：giffgaff 建议你"申请 PAC 保号"，但 PAC 流程要求向你的 giffgaff 手机号发 SMS 验证码——而号码已经被它停了，你根本收不到。把这一步的报错/提示页面单独截图存为 `06_PAC_SMS_Verification.png`，这是向 Ombudsman 投诉的强力证据点：**不是你拒绝 PAC，而是运营商停号导致它自己提供的 PAC 流程无法执行。**
