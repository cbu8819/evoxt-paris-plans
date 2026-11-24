# Evoxt Paris: Is the $2.99 Plan Worth Paying For, Does the 40% Code Still Work, and Which VM Do You Actually Need? (Full 11-Plan Table and Promo Check)

Evoxt's Paris location starts at $2.99/month, but most readers should skip that plan and take VM-1 at $5.99, or roughly $3.59 if a third-party promo code still applies at checkout. The extra 60 cents buys four times the RAM, four times the storage, double the monthly transfer, and a CPU running well above the 2.2 to 2.4 GHz that budget hosts usually rent out.

What follows covers all eleven plans sold in Paris's region, where the 40% discount code comes from and what it does not promise, the arithmetic that decides whether to upgrade a plan or buy add-ons, latency measured from Paris to Western Europe and to China, and the cases where a Paris box is the wrong purchase.

> **Quick pick:** VM-1 (1 vCore, 2 GB RAM, 20 GB storage, 1 TB transfer) at $5.99/month, about $3.59 with the recurring code EVOXT595 on orders from VM-1 upward.
> **Take VM-0.5 at $2.99 only if** you want a cheap machine to test the control panel, run a small proxy, or host one lightweight bot. It has 512 MB of RAM and cannot use the percentage discount.
> 👉 [Check the Paris plan list and test the code at checkout](https://bit.ly/EvoXt)

## All eleven Paris plans and what they cost

Paris sits in Evoxt's Standard region, which means the same specs and prices as Los Angeles, London, Frankfurt, Amsterdam and the rest of the 17 locations. The official France page prints nine plans up to VM-8; VM-12 and VM-16 appear on the wider Standard price list at identical specs and prices, so they can be ordered for Paris just like the smaller ones.

| Plan | vCPU + RAM | Storage + monthly transfer | Price | Order |
| --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB / 500 GB | $2.99/mo | [Order VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB / 750 GB | $4.99/mo | [Order VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB / 1 TB | $5.99/mo | [Order VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB / 1.5 TB | $6.95/mo | [Order VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB / 2 TB | $11.99/mo | [Order VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB / 3 TB | $14.99/mo | [Order VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB / 4 TB | $23.99/mo | [Order VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB / 5 TB | $29.99/mo | [Order VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB / 6 TB | $47.99/mo | [Order VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB / 8 TB | $60.95/mo | [Order VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB / 10 TB | $95.99/mo | [Order VM-16](https://bit.ly/EvoXt) |

Two details about that table. Storage is NVMe, and a third-party test of the VM-1 box measured average read and write around 2.7 GB/s; Evoxt's own France page only prints the word "Storage" without the NVMe label. The monthly transfer figures also come from third-party plan tables, since the official France page leaves that column out. Billing runs monthly, quarterly, half-yearly or yearly, and the listed price is the price on every renewal, with no cheap first-year rate that jumps later.

Every plan includes KVM virtualisation, IPv4 plus IPv6, an enterprise layer 3 firewall, a browser VNC console, and a free weekly offsite backup stored outside the primary infrastructure. Deployment is quoted at 2.5 minutes and the uptime target is 99.99%.

## Why the $2.99 plan is usually the wrong place to start

VM-0.5 gives you 512 MB of RAM and 5 GB of disk. A stock WordPress install with a database, PHP and a control panel will exhaust that before you finish configuring it; the third-party test that installed a Chinese hosting panel plus a default LNMP stack on the 2 GB plan was left with 1.5 GB of RAM and 14 GB of disk. On 512 MB you are running a proxy, a keepalive bot, or a WireGuard endpoint, and not much else.

VM-1 costs $2.99 more at list price, and with the recurring code the gap narrows to about 60 cents a month: $2.99 versus roughly $3.59. For that you move from 512 MB to 2 GB of RAM, from 5 GB to 20 GB of storage, and from 500 GB to 1 TB of transfer. Over a year the difference is about $7.20, which is less than one month of VM-1 at list price.

VM-0.75 at $4.99 is the harder plan to justify. It sits one dollar below VM-1 and halves both the RAM and the storage of that plan. Unless you specifically want a 1 GB box and refuse to pay six dollars, the extra dollar for VM-1 is the better trade.

The same logic applies one step up. VM-1.5 at $6.95 doubles the core count for 96 cents more than VM-1, and about $4.17 a month if the 40% code applies to it the way it applies to VM-1. If your workload is CPU-bound rather than RAM-bound, that is the cheapest route to a second core in the entire lineup.

## The 40% code: what EVOXT595 is, and what it is not

EVOXT595 shows up in several third-party write-ups and deal listings as a 40% recurring discount on VM-1 and above. Recurring is the part that matters: the discount is described as applying to every billing cycle rather than the first month only, which is rare among hosting promo codes. VM-0.5 is excluded, and one code applies per order.

None of this appears on Evoxt's own home page or France product page, so treat it as an unverified third-party claim and confirm the discount in the cart before you pay. If the field rejects the code, the same write-ups list two fallbacks: BHW595, described as another recurring 40% code, and AFF2261-btcvps, a 5% code that reportedly covers a wider range of products including dedicated servers. The 5% code is the more conservative option and cannot be combined with the 40% one.

At 40% off, the list prices land here:

| Plan | List price | With 40% recurring code |
| --- | --- | --- |
| VM-1 | $5.99/mo | ~$3.59/mo |
| VM-2 | $11.99/mo | ~$7.19/mo |
| VM-3 | $14.99/mo | ~$8.99/mo |
| VM-4 | $23.99/mo | ~$14.39/mo |
| VM-8 | $47.99/mo | ~$28.79/mo |

Promo codes get pulled without notice, and a code that worked last month can fail today. The correct move is to open the checkout, apply the code, and read the total before entering payment details. A rejected code costs you a minute; assuming it worked costs you 40% every month.

👉 [Start with VM-1 and apply EVOXT595 in the cart](https://bit.ly/EvoXt)

## Upgrade the plan or buy add-ons? Three sums that answer it

Evoxt sells individual resources on top of any plan: extra vCPU at $3/month per core, extra RAM at $2/month per GB, extra IPv4 at $3/month per address, and extra transfer at $3/TB in Standard regions. Those unit prices make most add-on purchases a bad deal compared with simply moving up a tier.

**Need one more core on VM-1?** VM-1 at $5.99 plus a $3 vCPU comes to $8.99. VM-1.5, which has two cores and 50% more transfer, costs $6.95. Upgrading is $2.04 cheaper every month.

**Need one more gigabyte of RAM on VM-1?** $5.99 plus $2 is $7.99, again above the $6.95 of VM-1.5, which throws in the second core and the larger transfer quota for free.

**CPU-bound on VM-2?** Moving from VM-2 (2 cores, 4 GB, $11.99) to VM-3 (4 cores, 4 GB, $14.99) costs $3 and doubles the core count. Buying two extra cores at the add-on rate would cost $6.

The pattern holds because the tier gaps are smaller than the sum of the individual resource prices. Add-ons make sense in narrow cases: a fifth IPv4 address, a burst of transfer on a plan you do not want to migrate, or a single extra core on the largest plans where the next tier is a much bigger jump.

## Latency and throughput from Paris, measured and claimed

Evoxt describes Paris as connected to France-IX and multiple Tier 1 providers, with low latency to France and Europe. Third-party latency ranges put Paris within 5 ms of major French networks, under 20 ms of Germany, the Netherlands, Belgium, Luxembourg, Switzerland and southern England, 20 to 40 ms of Poland, Czechia, Austria and Hungary, and 80 to 120 ms of the US East Coast. Those are measurements from one source, not contractual figures.

For Chinese visitors the picture is better than the usual European average. A third-party test of the $5.99 VM-1 configuration measured an average of 197 ms to China, against the 220 ms or more that European hosts typically show, with direct routing in both directions on all three carriers: China Telecom inbound via Germany and straight back from France, China Unicom via AS4837 through Germany, China Mobile inbound via the UK with a slightly higher figure. Paris is a Standard region rather than a China-optimised line, so 197 ms is a good result for direct routing, not the sub-50 ms you would see from a CN2 GIA setup in Hong Kong or Los Angeles.

Throughput on the same test machine went well past the advertised 1 Gbps port: downloads above 800 Mbps everywhere tested and up to 2 Gbps on some nodes, uploads around 400 Mbps to most locations, and both directions above 5 Gbps to a UK test node. That last number is why the reviewer flagged it as a relay for UK residential connections used for TikTok live work. One test machine proves what one test machine did, not what your box will do, but the headroom is clearly there.

CPU frequency is worth stating precisely, because three different numbers circulate. Evoxt's home page advertises up to 6.0 GHz turbo and prints a comparison chart against 2.4, 2.3 and 2.2 GHz chips, with a footnote that the data was collected in 2020 and may change. The France product page, as quoted by a Chinese review, states a 4.8 GHz+ processor. The independent test read 4.5 GHz on an AMD EPYC chip and guessed at a 4.8 GHz boost ceiling. Whatever the exact boost figure, single-thread performance is the reason to pick this host over a cheaper 2.2 GHz box.

## Who Paris suits, and who should look elsewhere

Paris works well for three groups. The first is anyone serving French or Western European users who wants a server inside the EU: under 20 ms to most of Western Europe is the practical benefit, and data stored in France keeps it inside French jurisdiction, which simplifies matters for projects with EU data residency requirements. The second is UK-facing live streaming or TikTok operations that need a European relay with serious bandwidth to UK endpoints. The third is anyone running single-threaded software (a WordPress site, a small API, a Discord bot, a game server) where clock speed beats core count, especially at the discounted VM-1 price.

It is a poor fit in four situations. If you need CN2-grade latency to China, Paris will not deliver it. If you want a dedicated server in France, Evoxt does not offer one; its dedicated line launched in the third quarter of 2024 and stock is concentrated in Malaysia. If you expect a support reply within the hour, tickets can take 4 to 8 hours at peak, though the official Telegram channel usually moves faster. And if a long operating history matters to you, the company was founded in 2020, which is young next to hosts that have been running since the late 1990s.

A note on payment: cards, PayPal, Bitcoin, Litecoin, Ethereum and USDT on Tron are the methods Evoxt lists. A Chinese review also reports Alipay working at checkout. If Alipay is your only option, confirm it on the payment page before committing.

## Questions that come up before ordering

**Does the Paris IP unlock French Netflix?** A third-party test of a randomly assigned box found a French native IP that unlocked French Netflix, French domestic streaming services and French AI platforms. TikTok resolved to the US region rather than France. IP quality checks classified it as a normal data-centre IP with decent cleanliness, and port 25 was open.

**Is there a free trial?** No. Third-party write-ups mention a 24-hour refund window, which is not stated on Evoxt's own pages. Budget for the first month as a test.

**Will the renewal price jump?** No. Evoxt prices every billing cycle at the same rate, so the number you see is what you pay in month two and month twelve. The 40% code is described as recurring, but the provider can withdraw a code at any time, so it is not a permanent contract term.

**What happens if the server breaks?** Every plan includes a free weekly offsite backup, restorable from the panel in a few clicks. Rescue mode and a browser VNC console cover the case where you lock yourself out of SSH.

## Picking your plan

Match the plan to the job rather than to the entry price:

- A single small site, a bot, or a VPN endpoint: **VM-1**, roughly $3.59 with the code. This is the default.
- Testing the platform or running one tiny service: **VM-0.5** at $2.99, accepting 512 MB of RAM.
- A CPU-heavy service that does not need much memory: **VM-1.5** at $6.95, or about $4.17 with the code.
- A production site with moderate traffic or a small shop: **VM-2** at $11.99, about $7.19 discounted.
- Several sites, staging environments or a database backend: **VM-3** or **VM-4**, from $14.99 and $23.99.

Before paying, confirm two things in the cart: that the promo code has been accepted and shows in the total, and that the region reads Paris rather than another Standard location. Everything else can be changed after deployment, including the plan itself.

👉 [Deploy a Paris VM-1 and confirm the discount at checkout](https://bit.ly/EvoXt)
