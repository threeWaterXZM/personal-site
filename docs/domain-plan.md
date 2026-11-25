# 域名选购计划

我无法替你完成付款，但已核实以下域名**当前可注册**（以注册商结账页为准）：

| 域名 | 首年参考价 | 续费参考 | 推荐理由 |
|------|-----------|---------|---------|
| **xuzhaomiao.xyz** | ~$1.3（Porkbun） | ~$14 | 最便宜，完整姓名拼音 |
| **xuzhaomiao.me** | ~$2（Namecheap 促销） | ~$19 | 个人站常见后缀 |
| **xuzhaomiao.com** | ~$10–12 | ~$12 | 最正式，长期品牌最稳 |
| xzmao.xyz | ~$1.3 | ~$14 | 短，但辨识度略低 |
| zhaomiao.xyz | ~$1.3 | ~$14 | 短名备选 |

## 建议

1. **预算优先**：买 `xuzhaomiao.xyz`（Porkbun）
2. **长期品牌**：直接买 `xuzhaomiao.com`（Porkbun / Cloudflare Registrar）
3. 注册后开启 **WHOIS Privacy**，Nameserver 先指向 GitHub Pages 或 Cloudflare

## 购买步骤（Porkbun 示例）

1. 打开 https://porkbun.com
2. 搜索 `xuzhaomiao.xyz` 或 `xuzhaomiao.com`
3. 加入购物车 → 结账（支持信用卡）
4. DNS 添加：
   - `A` → `185.199.108.153` / `.109.153` / `.110.153` / `.111.153`（GitHub Pages）
   - 或 `CNAME` `www` → `threeWaterXZM.github.io`
5. 本仓库根目录放置 `CNAME` 文件，内容为你的域名

## 绑定 GitHub Pages 后

在仓库 Settings → Pages → Custom domain 填入域名，并勾选 Enforce HTTPS。
