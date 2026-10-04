# buy dedicated proxies: how per-IP residential access actually bills, and which 9Proxy tier to pick without overspending

People searching "buy dedicated proxies" usually want one of three different products, and the confusion starts right there. You might want a static datacenter IP that never changes. You might want an ISP-registered IP that looks residential but behaves like a server — fast, permanent, quiet. Or you might want a large stack of real residential IPs assigned to you alone, which is what 9Proxy sells.

Getting this wrong is expensive. Buy the wrong type and you'll spend weeks blaming the provider for a product that was never designed for your job. So before any price table, here's the honest split.

## Three things "dedicated proxy" can mean

A **dedicated datacenter proxy** is a server-hosted IP that only you use. Fast, cheap per unit, and increasingly easy for anti-bot systems to fingerprint because the IP block belongs to a hosting provider, not a household.

A **static residential / ISP proxy** is hosted on server infrastructure but registered under a real internet service provider's ASN. It stays the same IP for as long as you're subscribed, which is what you want for account logins and long-lived sessions.

A **dedicated residential IP** is a real consumer connection handed to your account exclusively, with no other user sharing it. It behaves like an actual person browsing from a living room. The trade-off is that real residential connections don't sit still — they come and go on the household's schedule, not yours.

9Proxy is the third category. Its two product lines are residential proxies billed by IP and residential proxies billed by bandwidth. There's no datacenter product and no permanent static-ISP product in the current lineup, which matters if your workflow assumed a fixed endpoint for six months.

## What "dedicated" means on 9Proxy, precisely

Under the IP-based model, 9Proxy allocates a fixed number of residential IPs to your account and doesn't count your bandwidth against any cap. The company's own documentation states it plainly: you pay per IP, not per traffic, and the traffic limit is unlimited during the IP's active window.

Two details decide whether this fits you.

First, IP lifespan. Each residential IP is usable for a few hours up to roughly 24 hours, varying per IP. It's a genuine residential connection, so the exit doesn't stay alive indefinitely. If you need the same IP address next month, this is the wrong product line.

Second, unused IPs never expire. You're not renting a monthly subscription that resets — you're buying an inventory balance. IPs you haven't forwarded stay available until you use them, and the vendor confirmed that any package bought before its June 1, 2026 price adjustment is locked at the older rate permanently, with those IPs never expiring.

> The practical read: on the IP-based model you're buying consumable inventory, not a lease. That's good value if your work is project-based, and awkward if you assume a fixed proxy list.

Authentication on the IP-based side runs through the 9Proxy desktop app, which handles local port forwarding, with optional proxy authentication on top. The bandwidth-based line skips the app entirely — username/password or IP whitelist, straight from the dashboard.

## The two billing models are the actual buying decision

Most complaints about residential proxy pricing trace back to picking the wrong model, not the wrong vendor.

**IP-based (unlimited bandwidth).** Fixed package by number of IPs. Traffic within an active IP is unlimited. This is the right structure when a single session moves a lot of data: bulk page fetches from the same endpoint, long-running scrapes, anything where a gigabyte counter would make you nervous. You watch success rate per IP instead of a consumption meter.

**GB-based (pay per traffic).** Fixed package by total bandwidth, with unlimited endpoints generated from the 20M+ IP pool. IPs rotate automatically per request or hold sticky for a configured session length. This suits high-rotation work where each request is small — SERP checks, price monitoring, ad verification, API polling, lightweight scraping.

The mistake worth naming: buying an IP package for a job that rotates constantly, or buying GB for a job that needs one endpoint to stay put. Both feel like the provider is overcharging. Neither is.

## Full 9Proxy pricing — every package currently published

Prices below reflect the June 1, 2026 adjustment for IP-based and bundle packages. The GB-based line was explicitly left unchanged. Tier totals move as the vendor tunes them, so confirm the number at checkout before you pay.

### IP-based residential packages (unlimited bandwidth per IP)

| Package | Price | Effective rate | Notes | Buy |
| --- | --- | --- | --- | --- |
| 100 IPs | $24 | $0.24/IP | Entry tier, good for pilots | [ start with the 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $72 | $0.144/IP | Solo operators, light multi-account work | [ grab the 500 IP tier](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $126 | $0.084/IP | Vendor flags this as the most popular tier | [ take the 1,000 + 500 IP deal](https://bit.ly/9-Proxy) |
| 2,500 IPs | $210 | $0.084/IP | Several verticals running at once | [ compare the 2,500 IP tier](https://bit.ly/9-Proxy) |
| 5,000 IPs | $360 | $0.072/IP | Agency-scale price/perf stacks | [ view the 5,000 IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $720 | $0.048/IP | Regional teams, heavier automation | [ open the 15,000 IP tier](https://bit.ly/9-Proxy) |
| 25,000 IPs | $863 | $0.035/IP | Resellers and automation labs | [ check the 25,000 IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | $1,438 | $0.029/IP | High-volume resale, platform ops | [ see the 50,000 IP tier](https://bit.ly/9-Proxy) |
| 100,000 IPs (Business) | $2,300 | $0.023/IP | Industrial-scale collection | [ price the 100,000 IP package](https://bit.ly/9-Proxy) |
| 200,000 IPs (Business) | $4,140 | $0.021/IP | Multi-region industrial workloads | [ view the 200,000 IP tier](https://bit.ly/9-Proxy) |
| 500,000 IPs (Business) | $8,625 | $0.018/IP | Where the "$0.015–0.018/IP" headline lives | [ enquire about the 500,000 IP package](https://bit.ly/9-Proxy) |

That last row is worth a sentence. 9Proxy's marketing quote of "from $0.015/IP" belongs to the half-million-IP end of the curve. At the 100-IP tier you're paying $0.24 per IP. Both numbers are real; they describe wildly different commitments, and any comparison table that puts only the headline rate next to a competitor's entry rate is doing you a disservice.

### GB-based residential packages (rotating or sticky, 180-day validity)

| Package | Price | Rate | Validity | Buy |
| --- | --- | --- | --- | --- |
| 5 GB | $15 | $3.00/GB | 180 days | [ buy the 5 GB test pack](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10/GB | 180 days | [ get the 50 + 5 GB pack](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50/GB | 180 days | [ choose the 100 GB tier](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00/GB | 180 days | [ compare the 200 GB tier](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80/GB | 180 days | [ view the 1,000 GB package](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75/GB | 180 days | [ open the 2,000 GB tier](https://bit.ly/9-Proxy) |
| 3,000 GB (Enterprise) | $2,160 | $0.72/GB | No expiry | [ ask about the 3,000 GB enterprise tier](https://bit.ly/9-Proxy) |
| 6,000 GB (Enterprise) | $4,200 | $0.70/GB | No expiry | [ price the 6,000 GB enterprise pack](https://bit.ly/9-Proxy) |
| 10,000 GB (Enterprise) | $6,800 | $0.68/GB | No expiry | [ enquire about the 10,000 GB enterprise pack](https://bit.ly/9-Proxy) |

The 180-day window is more useful than it sounds. Buying 200 GB, using 60 in a rushed two weeks, then shelving the rest for a quarter doesn't burn your balance. Enterprise tiers drop the deadline entirely.

### Bundle packages (IPs + bandwidth in one purchase)

| Bundle | What's inside | Price | Buy |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [ start with the Starter bundle](https://bit.ly/9-Proxy) |
| Growth | 1,500 IPs + 50 GB | $180 | [ pick the Growth bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [ compare the Pro bundle](https://bit.ly/9-Proxy) |

Bundles exist for teams that don't know their split in advance — some tasks want a stable endpoint, others want rotation, and one purchase covers both. Bundled traffic also runs on the 180-day clock.

## Which tier actually fits your job

You don't need a strategy deck for this. Four patterns cover most buyers.

**Testing the water.** The 5 GB pack at $15 or 100 IPs at $24. Both are cheap enough that a failed experiment costs less than lunch. Use the trial window to check success rates against *your* targets, not a generic benchmark page.

**One person doing multi-account work.** 1,000 + 500 IPs at $126, or 500 IPs at $72 if you're running a handful of profiles. The bonus-IP tier is the first point where the per-IP rate drops meaningfully without a five-figure commitment.

**An agency with live clients.** 5,000 IPs at $360, or the Growth bundle at $180 if you also need rotation bandwidth. At this level you're buying separation between client projects, not raw volume.

**Reselling or running platform-scale collection.** 25,000 IPs upward. The per-IP cost roughly halves between the 5,000 and 50,000 tiers, and the business packages push it under $0.025. This is also where you'd want the vendor's wholesale reseller terms rather than self-serve checkout.

If your workload is genuinely bursty — big data days alternating with idle weeks — the GB side usually wins on cost, because you're not holding IP inventory you aren't using.

## What comes with the IPs besides the IPs

The features that decide day-to-day usefulness are mostly about waste reduction.

**Today List.** Proxies accessed in the last 24 hours can be reused at no extra charge. If you're testing, or your session ends early, you stop paying twice for the same address.

**60-second replacement.** If a proxy fails within the first minute of activation, the credit comes back automatically. Longer-lived failures need a manual request, which one published review flags as minor friction.

**Auto-Refresh Proxy.** Swaps IPs on ports when they go offline, cutting the "connection refused" cascade when part of the pool drops.

**Auto-Rotation Proxy.** Rotates at intervals you set on selected ports — ten minutes, an hour, whatever the target tolerates.

**Quick Bind and port configuration.** Assign IPs to ports by country or filter, so each automation profile gets a predictable endpoint.

**Share codes and sub-accounts.** Hand proxies to teammates or clients without giving away dashboard access, and revoke when the project ends.

**Protocol coverage.** HTTP, HTTPS, and SOCKS5. SOCKS5 matters if you're running Puppeteer, Playwright, or Scrapy through an anti-detect browser, since those stacks often proxy non-HTTP traffic or need long-lived connections.

**Access paths.** Desktop app for OS-level routing, Proxy2Web for credential-based browser work with no install, ProxyHub for device management, and a public API for programmatic rotation and usage stats. Third-party reviews specifically call out clean integration with Dolphin Anty and AdsPower.

## Coverage, performance, and third-party verdicts

The advertised network is 20M+ residential IPs across 90+ countries. Per-location counts reported by one review put the deepest pools in the US (about 572,600), Canada (about 530,800), France (about 490,090), the UK (about 446,080), and Germany (about 385,590) — which tracks with where most scraping targets are hosted. Targeting reaches country, state, and city level, and the bandwidth line adds ISP-level filtering.

Published review scores sit around 3.9/5 in proxy directories and higher on individual review sites. One 2025 review reported 50–100 Mbps typical throughput and uptime near 99% for scraping and account management, with a caveat that streaming services like Netflix are a different story. Another notes peak-hour slowdowns in parts of Southeast Asia.

None of that is a substitute for testing your own targets. Residential performance is target-specific by nature.

## Where 9Proxy is the wrong purchase

Skipping this section would be selling, not explaining.

There's no datacenter product, no permanent static-ISP proxy, and no mobile proxy line. If your workflow is low-protection scraping where speed beats anonymity, or an account- bound job that needs the same IP for a year, you'll need a different provider or a second one alongside 9Proxy. Its IPs live for hours, not months.

There's also no standing free-trial button. The vendor's own sales threads say a limited trial is offered to new users depending on availability — you have to ask, and specify whether you want an IP-based or GB-based trial. Otherwise the cheapest honest way to evaluate is the $15 or $24 entry tier.

And the metro-level speed variance is real. If your primary targets sit in Southeast Asia and you need throughput at local peak hours, test that specifically before committing to a large IP package.

## How the purchase actually goes

1. Create an account from the referral link — email and password, no lengthy KYC gate before you can generate credentials.
2. Pick your model: IP-based, GB-based, or a bundle.
3. Pick the tier. If you're unsure, buy small and top up; the balance model means unused IPs don't evaporate.
4. Choose your access route — desktop app, Proxy2Web, or API.
5. Generate proxies from the dashboard, selecting country/state/city and protocol.
6. Test against real targets before scaling to a bigger tier.

Payments cover credit cards, bank cards, crypto (USDT, BTC, ETH, LTC, DOGE and others), Alipay, Apple Pay, and Google Pay. Crypto payments carry an IP bonus according to the vendor's published terms.

## Questions buyers ask before Checkout

**Is a 9Proxy IP truly mine alone?** Under the IP-based model, yes — the IP is allocated to your account and your traffic isn't metered. It just isn't permanent.

**Can I get the same IP address again tomorrow?** Not reliably on the IP line. If persistent identity is the requirement, look at static ISP proxies instead.

**Should I buy IPs or gigabytes?** If your job moves a lot of data per endpoint, buy IPs. If it rotates constantly with small payloads, buy gigabytes.

**Is there a discount for referred sign-ups?** 9Proxy runs a lifetime partner programme with commission tiers and a referral benefit for new users; the exact terms are worth confirming with support rather than trusting a coupon aggregator.

**Do I have to install the desktop app?** Only for IP-based proxies. The bandwidth line works straight from the dashboard with username/password or IP whitelist authentication.

## The short version

"Dedicated proxies" gets used as if it's one product. It isn't. 9Proxy sells dedicated *residential* access — real consumer IPs assigned to your account, unlimited bandwidth per IP on the IP-based line, no monthly subscription, and inventory that doesn't rot on a shelf. The trade-off is lifespan: hours per IP, not months.

If that matches your work, the entry tiers are cheap enough that arguing about it costs more than testing it.

👉 [Check 9Proxy's current tiers and start with a small package](https://bit.ly/9-Proxy)
