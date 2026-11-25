# 小火箭广告拦截模块

给 Shadowrocket（小火箭）用的广告拦截模块，只拦广告和跟踪域名，**不动你现有的订阅和分流，也不需要装证书**。

拦截名单（都自动更新，不用手动维护）：

- [anti-AD](https://anti-ad.net/)：十万级广告/隐私跟踪域名名单
- [AWAvenue Ads Rule](https://github.com/TG-Twilight/AWAvenue-Ads-Rule)：约一千条补充广告域名

## 导入方法（在 iPhone 上）

1. 复制这个链接：
   `https://cdn.jsdelivr.net/gh/ruisuskill/shadowrocket@main/adblock.sgmodule`
2. 打开小火箭 → 底部「配置」→「模块」→ 右上角「+」
3. 粘贴链接，保存，然后把这个模块的开关打开

备用链接（上面那个打不开时用）：
`https://raw.githubusercontent.com/ruisuskill/shadowrocket/main/adblock.sgmodule`

## 说明

- 这是域名级拦截：App 和网页里大部分广告、开屏广告的加载域名、统计跟踪都会被拦掉。
- 少数 App 把广告和正文走同一个接口下发（如部分信息流），这类拦不干净，需要更深的方案（要装证书），有需要再单独处理。
- 如果某个 App 出现打不开或功能异常，先把这个模块关掉试试，能恢复就是名单误伤，告诉 Marley 加白名单。
