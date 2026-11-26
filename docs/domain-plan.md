# 域名：xuzhaomiao.xyz

已购买。本仓库根目录 `CNAME` 文件内容为：

```
xuzhaomiao.xyz
```

## DNS 配置（GitHub Pages）

在域名注册商（如 Porkbun / Cloudflare / Namecheap）添加：

| 类型 | 主机 / Name | 值 / Answer |
|------|-------------|-------------|
| A | `@` / 留空 | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `threeWaterXZM.github.io` |

可选：若使用 Cloudflare，可将 Nameserver 切到 Cloudflare，再按上表配 DNS，并开启代理或仅 DNS。

## GitHub Pages

1. 仓库推送到 `https://github.com/threeWaterXZM/personal-site`（或 `threeWaterXZM.github.io`）
2. Settings → Pages → Source：`Deploy from a branch` → `main` → `/ (root)`
3. Custom domain：`xuzhaomiao.xyz` → Save
4. 勾选 **Enforce HTTPS**（DNS 生效后可用）

## 校验

```bash
dig +short xuzhaomiao.xyz A
dig +short www.xuzhaomiao.xyz CNAME
curl -I https://xuzhaomiao.xyz
```
