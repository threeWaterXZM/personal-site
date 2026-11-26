# 域名：xuzhaomiao.com

已购买。本仓库根目录 `CNAME` 文件内容为：

```
xuzhaomiao.com
```

## DNS 配置（GitHub Pages）

在域名注册商添加：

| 类型 | 主机 / Name | 值 / Answer |
|------|-------------|-------------|
| A | `@` / 留空 | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `threeWaterXZM.github.io` |

## GitHub Pages

1. 仓库：`https://github.com/threeWaterXZM/personal-site`
2. Settings → Pages → Source：`main` → `/ (root)`
3. Custom domain：`xuzhaomiao.com` → Save
4. DNS 生效后勾选 **Enforce HTTPS**

## 校验

```bash
dig +short xuzhaomiao.com A
dig +short www.xuzhaomiao.com CNAME
curl -I https://xuzhaomiao.com
```
