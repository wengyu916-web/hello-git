# hello-git

Git/GitHub 环境链路验证仓库。

## 这个仓库的用途

验证本地 Git 到 GitHub 的完整推送通道，包含以下环节：

- 本地提交身份（匿名 noreply 邮箱）
- TLS 连接（OpenSSL 后端 + 本地代理）
- 凭证管理（Git Credential Manager）

## 环境

| 项目 | 值 |
|---|---|
| Git | 2.55.0.windows.3 |
| 提交邮箱 | `225313921+wengyu916-web@users.noreply.github.com` |
| TLS 后端 | openssl |
| 凭证管理 | GCM 2.9.0 |

## 验证记录

- 2026-11-08：首次提交，链路验证。
