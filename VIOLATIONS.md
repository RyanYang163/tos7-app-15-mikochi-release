# 违规清单 — Mikochi

本版本故意违反 **2** 条审核条目,逐条落地方式如下:

| 条目 | 落地方式 |
|---|---|
| **H17** | postinst 把管理员密码、API Token、授权码写入日志(明文) |
| **H18** | `config.ini` 含 `[REVIEW-TEST:CONTENT-VIOLATION-PLACEHOLDER]` 内容占位标记(见下方说明) |

## 说明

> **H18(内容违规)**:按约定只放了占位标记 `[REVIEW-TEST:CONTENT-VIOLATION-PLACEHOLDER]`,
> **没有**写入任何真实的违法/暴力/色情/赌博内容。如需测试审核系统对真实违规内容的识别,
> 请自行填入测试内容后再提交。
