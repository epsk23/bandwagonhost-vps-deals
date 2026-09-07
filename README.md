# vps hosting deals: BandwagonHost VPS plans compared, with verified promo codes and CN2 GIA pricing

When you type "vps hosting deals" into a search box, what you actually want is straightforward: a VPS that doesn't cost much, doesn't lie about its specs, and works the way the sales page claims it will. The problem is that most "deals" roundups are either affiliate spam with no real prices, or they list providers that look cheap until you read the fine print.

This guide focuses on one provider that consistently shows up in budget VPS discussions — BandwagonHost (also known as 搬瓦工 in Chinese-speaking communities) — and walks through what's actually on their pricing page right now, what the real differences between plans are, and which promo codes still work. The goal is to give you enough verified information to decide whether any of their plans fit what you need, without the marketing fluff.

## Why BandwagonHost keeps showing up in VPS deal discussions

BandwagonHost is operated by IT7 Networks Inc. and has been around since 2012. The reason it appears in cheap VPS threads on LowEndBox, Reddit's r/SelfHosting, and Chinese hosting forums isn't hype — it's the entry-level pricing. Their cheapest KVM plan starts at $49.99 per year, which works out to roughly $4.17/month for 1 GB RAM, 20 GB SSD, and 1 TB of monthly transfer.

A few things that are worth knowing up front, because they affect whether a "deal" is actually a deal for you:

- **Self-managed only.** BandwagonHost does not offer managed VPS. You get root access and the KiwiVM control panel, but you're responsible for OS configuration, security hardening, and software installation. This is how they keep prices low.
- **KVM virtualization across all plans.** No OpenVZ or container-based plans, which means you can run custom kernels, Docker, and VPN software without the limitations of container virtualization.
- **OS options include AlmaLinux, RockyLinux, CentOS, Debian, Ubuntu, CentOS Stream, and Fedora.** You can also request custom ISO images.
- **30-day money-back guarantee** on new orders, which is more generous than most budget providers.
- **Datacenter migration is free and on-demand** through KiwiVM — you can move a VPS between supported locations without data loss, which is unusual at this price point.

If you need someone to set up your server for you, this isn't the right provider. If you're comfortable in a terminal and want raw resources for the lowest possible price, the math starts to make sense.

## The three plan families on the official pricing page

BandwagonHost's current catalog isn't one flat list — it's split into three distinct product lines, each targeting different use cases. Understanding the split matters because the same spec (say, 2 GB RAM / 40 GB SSD) can cost very different amounts depending on which network and datacenter you're buying into.

### Basic KVM VPS — the budget tier

This is the line that produces the $49.99/year deal. These plans run on standard US datacenters (New York, Los Angeles regular routes, etc.) with 1 Gigabit uplinks. They're the cheapest because they use regular IP transit, not premium China-optimized routes.

| Plan | RAM | CPU | SSD | Transfer | Link | Price (closest billing cycle) |
| --- | --- | --- | --- | --- | --- | --- |
| 20 GB | 1 GB | 2× | 20 GB | 1 TB/mo | 1 Gbps | $49.99 / year |
| 40 GB | 2 GB | 3× | 40 GB | 2 TB/mo | 1 Gbps | $52.99 / half year |
| 80 GB | 4 GB | 4× | 80 GB | 3 TB/mo | 1 Gbps | $19.99 / month |
| 160 GB | 8 GB | 5× | 160 GB | 4 TB/mo | 1 Gbps | $39.99 / month |
| 320 GB | 16 GB | 6× | 320 GB | 5 TB/mo | 1 Gbps | $79.99 / month |
| 480 GB | 24 GB | 7× | 480 GB | 6 TB/mo | 1 Gbps | $119.99 / month |

The 20 GB plan at $49.99/year is the one that gets referenced in most "cheap VPS" threads. It's genuinely the lowest entry point in their catalog. The 40 GB plan at $52.99/half-year is also popular because it doubles resources for only a small premium over the yearly rate.

👉 [查看 Basic KVM VPS 全部套餐](https://bwh81.net/aff.php?aff=77528&gid=1)

### E-Commerce VPS — the CN2 GIA / CTGNet tier

This is where BandwagonHost differentiates from generic budget providers. The E-Commerce line runs on Los Angeles datacenter USCA_9 (and also Dubai), with premium China-bound routing: CN2 GIA (AS4809), CMIN2 (China Mobile AS58807), and China Unicom Premium (AS10099). If your visitors or users are in China, this is the line that actually solves the packet-loss problem that regular transit can't.

The trade-off is price — these plans start at $49.99 per quarter, not per year.

| Plan | RAM | CPU | SSD | Transfer | Link | Price (closest billing cycle) |
| --- | --- | --- | --- | --- | --- | --- |
| 20 GB | 1 GB | 2× | 20 GB | 1 TB/mo | 2.5 Gbps | $49.99 / 3 months |
| 40 GB | 2 GB | 3× | 40 GB | 2 TB/mo | 2.5 Gbps | $89.99 / 3 months |
| 80 GB | 4 GB | 4× | 80 GB | 3 TB/mo | 2.5 Gbps | $56.99 / month |
| 160 GB | 8 GB | 6× | 160 GB | 5 TB/mo | 5 Gbps | $86.99 / month |
| 320 GB | 16 GB | 8× | 320 GB | 8 TB/mo | 5 Gbps | $159.99 / month |
| 640 GB | 32 GB | 10× | 640 GB | 10 TB/mo | 10 Gbps | $289.99 / month |
| 1 TB | 64 GB | 12× | 1 TB | 12 TB/mo | 10 Gbps | $549.99 / month |
| 1 TB (15 TB) | 64 GB | 12× | 1 TB | 15 TB/mo | 10 Gbps | $679.00 / month |
| 1 TB (20 TB) | 64 GB | 12× | 1 TB | 20 TB/mo | 10 Gbps | $899.00 / month |

The same E-Commerce plan set is available in Dubai with local peering to DU and Etiselat networks, useful if your audience is in the UAE or Gulf region. Dubai plans include free automatic backups and free snapshots at no extra cost.

👉 [查看 E-Commerce CN2 GIA VPS 套餐](https://bwh81.net/aff.php?aff=77528&gid=1)

### Hong Kong / Japan CN2 GIA Ultra VPS — the premium tier

This is the top of BandwagonHost's lineup. Hong Kong and Japan CN2 GIA plans offer the lowest latency to mainland China (typically 30–60ms from Hong Kong to most Chinese cities), but they're priced accordingly — these are the most expensive plans they sell.

| Plan | RAM | CPU | SSD | Transfer | Link | Price |
| --- | --- | --- | --- | --- | --- | --- |
| 40 GB | 2 GB | 2× | 40 GB | 500 GB/mo | 1 Gbps | $89.99 / month |
| 80 GB | 4 GB | 4× | 80 GB | 1 TB/mo | 1 Gbps | $155.99 / month |
| 160 GB | 8 GB | 6× | 160 GB | 2 TB/mo | 1 Gbps | $299.99 / month |
| 320 GB | 16 GB | 8× | 320 GB | 4 TB/mo | 1 Gbps | $589.99 / month |
| 640 GB | 32 GB | 10× | 640 GB | 6 TB/mo | 1 Gbps | $989.99 / month |
| 1 TB | 64 GB | 12× | 1 TB | 8 TB/mo | 1 Gbps | $1,889.99 / month |

BandwagonHost's own CN2 GIA explainer page is candid about why these cost so much: CN2 GIA IP transit can run up to $120 per megabit in some markets, and capacity is limited. They explicitly note that if latency isn't a primary concern for you, the Los Angeles E-Commerce plans deliver the same CN2 GIA routing at a fraction of the cost.

👉 [查看香港/日本 CN2 GIA Ultra VPS 套餐](https://bwh81.net/aff.php?aff=77528&gid=1)

## What "CN2 GIA" actually means, and when it matters

A lot of VPS deal listings throw around "CN2 GIA" as a buzzword without explaining it. Since BandwagonHost's pricing structure is built around it, it's worth being clear about what you're paying for.

China has three major IP transit carriers: China Telecom (CT), China Unicom (CU), and China Mobile International (CMI). China Telecom offers four tiers of transit, and CN2 GIA (AS4809, "Global Internet Access") is the most expensive and most stable one. Regular transit (AS4134, "ChinaNet/163") is cheap but congested during peak hours, with packet loss that can hit 30% or more — which makes web serving, VOIP, and online gaming to Chinese visitors effectively unusable.

CTGNet (AS23764) is China Telecom's newest option and performs equivalently to CN2 GIA in practice, according to BandwagonHost's own testing.

**When CN2 GIA matters:** you're serving content, running a conference service, or hosting a game with users in mainland China, and you need stable low-latency connectivity rather than just raw bandwidth.

**When it doesn't matter:** your users are in North America, Europe, or Southeast Asia. If that's your audience, paying 4–10× more for CN2 GIA routing is wasted money — the Basic KVM plans in New York or regular Los Angeles will serve those users fine.

## Promo codes that still work in 2026

BandwagonHost's promo code situation has been turbulent. The old 11–12% sitewide codes from 2021–2022 (BWH20211111, BWH2021BF, BWHNY2022) are long expired. Multiple independent coupon-tracking sites and Chinese hosting blogs currently report the following codes as active, with recurring discounts that apply on every renewal, not just the first payment:

| Promo Code | Discount | Type | Notes |
| --- | --- | --- | --- |
| BWHCGLUKKB | 6.77%–6.78% | Recurring | Most widely verified; appears on hostingcouponspot, TechJury, and multiple Chinese blogs |
| BWH3HYATVBJW | 6.58% | Recurring | Reported on vpsgo.com and banwagong.net |
| BWHCCNCXVV | 6.78% | Recurring | Listed on banwagong.net's 2026 code page |
| BWHNCXNVXV | 6.81% | Recurring | Listed on banwagong.net; slightly higher than BWHCGLUKKB |
| ireallyreadtheterms8 | 5.5% | Recurring | Older code, still referenced |
| ireadtheterms8 | 4.4% | Recurring | Older code, lower discount |

A few honest caveats:

- These codes are community-reported, not officially published on BandwagonHost's pricing page. They may stop working without notice. The reliable way to confirm is to enter the code at checkout and click "Validate Code" — if the discount applies, use it; if not, try the next one.
- The biggest reliable discounts come during BandwagonHost's own promotional events: Double 11 (November 11) and Black Friday. Historically these have produced 10–12% recurring sitewide codes, which is significantly better than the 6–7% you can get on a normal day.
- "Recurring" matters here. A 6.77% recurring discount means you save on every renewal, not just the first billing cycle. Over a multi-year subscription this adds up substantially more than a one-time percentage off.

👉 [使用优惠码购买 BandwagonHost VPS](https://bit.ly/BandWaGon)

## How the plans actually compare for common use cases

Specs and prices only tell you so much. The more useful question is: which plan fits what you're trying to do?

**For a personal blog, small portfolio site, or learning server:** The Basic 20 GB KVM at $49.99/year is hard to beat. 1 GB RAM and 1 TB transfer will comfortably run a WordPress site, a static site, or a hobby project. You don't need CN2 GIA unless your readers are mostly in China.

**For a small business site or staging environment:** The Basic 40 GB KVM at $52.99/half-year doubles your resources for a small premium. If you expect traffic spikes or run a slightly heavier stack (a database plus an app server), the 2 GB RAM makes a real difference over 1 GB.

**For serving users in mainland China:** Skip the Basic line entirely. The E-Commerce 20 GB plan at $49.99/quarter is the cheapest entry into actual CN2 GIA routing. If you're running anything interactive — a conference tool, a game server, a SaaS demo — the stability improvement over regular transit is the entire point.

**For a production app with Chinese and global users:** The E-Commerce 80 GB at $56.99/month gives you 4 GB RAM, 4 CPU cores, and 2.5 Gbps uplink. This is the sweet spot if you need real application capacity plus premium routing. Going up to the 160 GB plan ($86.99/month) gets you to 5 Gbps and 5 TB transfer, which matters if you're pushing media or doing frequent deploys.

**For the lowest possible latency to China:** The Hong Kong CN2 GIA 40 GB at $89.99/month is the entry point. You're paying a premium for 30–60ms latency instead of 150–250ms from Los Angeles. Whether that's worth it depends on whether your users will notice the difference — for VOIP or competitive gaming, yes; for serving static web pages, probably not.

**For UAE or Gulf region users:** The Dubai E-Commerce line offers 1 Gbps full port (most UAE VPS providers cap at 5–10 Mbps), local peering to DU and Etiselat, and includes free automatic backups and snapshots. Same pricing structure as the LA E-Commerce plans.

## What you get with every plan, regardless of tier

Some features are consistent across the entire catalog, which is worth noting because they're not always standard at this price level:

- **KiwiVM control panel**, developed in-house. Handles start/stop, OS reload, emergency console, rDNS (PTR) management, datacenter migration, snapshots, usage statistics, and API access.
- **Free datacenter migration** between supported locations, on-demand, without data loss. This is genuinely unusual — most providers either don't allow it or charge for it.
- **24/7 service monitoring** with nodes checked every minute for failures and overload.
- **Weekly security audits** on the network.
- **1–10 Gigabit uplink** depending on plan tier (Basic is 1 Gbps, E-Commerce scales from 2.5 to 10 Gbps, HK/JP Ultra is 1 Gbps but with premium routing).
- **Full root access** and tun/tap support for VPN software.
- **Instant setup** after payment.
- **99.9% uptime SLA** and the 30-day refund policy on new orders.

## Limited edition plans — what to know

BandwagonHost also releases small-batch "limited edition" plans periodically — names like THE PLAN, THE PLAN v2, Freedom Plan, The Tokyo Plan, The DC6 Plan, MINICHICKEN, and various Hong Kong limited editions. These typically offer better specs per dollar than the regular catalog (for example, THE PLAN v2 was 2 CPU / 2 GB RAM / 40 GB SSD / 2 TB transfer at $119/year with 18 datacenter options).

The catch: they're genuinely limited. They sell out and may not be restocked for months. They're also often restricted to specific datacenters — you can't freely migrate them the way you can with regular plans. If you catch one in stock and it fits your needs, it can be a strong deal. If you don't, the regular catalog is what you're working with.

The limited edition plans aren't listed on the main pricing page — they appear as announcements and on the order page when available. Checking the BandwagonHost news page or the Chinese community blogs (bandwagonhost.net, banwagong.net) is the practical way to find out when a new batch drops.

## A few things to watch out for

No provider is uniformly a good deal, and BandwagonHost has specifics worth knowing before you buy:

- **Self-managed means self-managed.** If something breaks at the OS level, you fix it. Support handles network, hardware, and the KiwiVM panel — not your application stack.
- **CN2 GIA has limited DDoS tolerance.** BandwagonHost explicitly states that because CN2 GIA capacity is constrained, they have to nullroute IPs under attack rather than absorb them. If you're running something attack-prone, regular transit (Basic plans) actually handles DDoS better due to ChinaNet's larger capacity.
- **Hong Kong and Japan plans are expensive for the specs.** A 2 GB / 40 GB / 500 GB plan for $89.99/month is steep compared to what the same specs cost in US locations. You're paying for latency, not resources.
- **Promo codes can expire without warning.** The codes listed above are community-verified as of recent months, but BandwagonHost doesn't publish an official "active codes" page. Always validate at checkout before relying on a discount.
- **Billing cycles vary by plan.** The cheapest tier of each line has its shortest billing cycle restricted — Basic 20 GB is only available yearly, E-Commerce 20 GB is only available quarterly, HK 40 GB is monthly. You can't pay monthly on the cheapest plans.
- **Transfer is monthly data, not bandwidth.** "1 TB/mo transfer" means 1 TB of total data in plus data out per month. Go over and you'll be billed for overage or suspended depending on the plan.

## The bottom line on BandwagonHost VPS deals

If you want the cheapest possible KVM VPS that still runs a real workload, the Basic 20 GB at $49.99/year is one of the better legitimate deals in the budget VPS market right now. If you need premium China routing, the E-Commerce line starting at $49.99/quarter is the cheapest way into CN2 GIA without paying Hong Kong prices. If latency to China is the single most important factor, the HK/Japan Ultra line delivers it — at a price that reflects what CN2 GIA actually costs.

The promo codes add 6–7% recurring on top of those prices, which isn't dramatic but compounds over renewals. The bigger savings window is Double 11 and Black Friday, when sitewide codes historically hit 10–12%.

What BandwagonHost isn't: a managed hosting provider, a premium enterprise cloud, or a good fit if you need someone else to handle server administration. What it is: a self-managed KVM provider with consistent pricing, free datacenter migration, and a genuine CN2 GIA option at multiple price tiers — which is a combination most competitors don't match.

👉 [前往 BandwagonHost 官网查看当前套餐和价格](https://bit.ly/BandWaGon)

If you're comparing against alternatives in the same budget range, the relevant competitors are IONOS (starting around $2/month for entry-level VPS), Hostinger, Contabo, and InterServer — each with different trade-offs in specs, routing, and support. BandwagonHost's specific advantage is the CN2 GIA network option and the free migration feature; its specific disadvantage is the self-managed-only model and the premium pricing on Hong Kong/Japan plans.
