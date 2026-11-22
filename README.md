# vps under 5 euro: your own IPv4, enough RAM, and the VAT question — what €5 actually buys (AVA Hosting plans compared)

Five euro a month buys a 1 vCPU / 1 GB VPS almost anywhere in Europe, and two providers will sell you 2 vCPU / 4 GB for €4.54 and €4.92 if you sort purely by price. AVA Hosting's lineup has a different shape: €2 for the entry tier, €5 for 2 GB of RAM on a 1 Gbps port with unlimited traffic, weekly backups and DDoS protection listed on every plan. If the box exists to terminate WireGuard so you can reach a CG-NAT home network, the €2 plan covers it. If the same machine will also serve a site, €5 buys 2 GB at AVA where much of the market charges the same for half that.

What follows: both AVA lineups in full, the €5 tier as sold by everyone else, the IPv4 catch that price tables skip, and the VAT arithmetic that decides whether your €5 budget is really €5.

> **Quick pick:** VPS One at €5/mo — 1 vCPU, 2 GB ECC RAM, 25 GB NVMe, 1 Gbps port with unlimited traffic, weekly backups included. It's the cheapest AVA tier with room for a web server next to the tunnel. 👉 [See VPS One's current price and order it](https://my.ava.hosting/aff.php?aff=15562)

## The full AVA Hosting lineup

AVA sells two parallel product lines, both priced in euro. The VPS/VDS line is monthly except for VPS Nano, which is listed per year.

| Plan | vCPU · RAM | Storage | Port / transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Nano | 1 · 512 MB ECC | 20 GB NVMe | 100 Mbps, unlimited | €11/year | [VPS Nano](https://my.ava.hosting/aff.php?aff=15562) |
| VPS One | 1 · 2 GB ECC | 25 GB NVMe | 1 Gbps, unlimited | €5/mo | [VPS One](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Basic | 2 · 4 GB ECC | 50 GB NVMe | 1 Gbps, unlimited | €10/mo | [VPS Basic](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Lucky | 2 · 6 GB ECC | 70 GB NVMe | 1 Gbps, unlimited | €15/mo | [VPS Lucky](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Power | 4 · 8 GB ECC | 90 GB NVMe | 1 Gbps, unlimited | €20/mo | [VPS Power](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Extra | 6 · 12 GB ECC | 120 GB NVMe | 1 Gbps, unlimited | €30/mo | [VPS Extra](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Ultra | 8 · 16 GB ECC | 160 GB NVMe | 1 Gbps, unlimited | €40/mo | [VPS Ultra](https://my.ava.hosting/aff.php?aff=15562) |

Every plan on that list carries Intel Xeon E5 hardware, NVMe storage, free DDoS protection, a weekly backup, full root access, a control panel, a 99.9% SLA and 24/7 support. VPS Nano is the exception on two counts: 100 Mbps instead of 1 Gbps, and its page states outright that port 25 is closed. It also showed 0 available when I checked, so the €11/year headline may not be orderable on any given day.

The second line, Self-hosted Start, overlaps the first at every price point:

| Plan | vCPU · RAM | Storage | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Start | 1 · 1 GB | 15 GB NVMe | Unlimited | from €2/mo | [Start](https://my.ava.hosting/aff.php?aff=15562) |
| Mini | 1 · 2 GB | 25 GB NVMe | Unlimited | from €5/mo | [Mini](https://my.ava.hosting/aff.php?aff=15562) |
| Basic | 2 · 4 GB | 50 GB NVMe | Unlimited | from €10/mo | [Basic](https://my.ava.hosting/aff.php?aff=15562) |
| Pro | 4 · 8 GB | 100 GB NVMe | Unlimited | from €20/mo | [Pro](https://my.ava.hosting/aff.php?aff=15562) |
| Business | 6 · 12 GB | 150 GB NVMe | Unlimited | from €30/mo | [Business](https://my.ava.hosting/aff.php?aff=15562) |
| Power | 8 · 16 GB | 200 GB NVMe | Unlimited | from €40/mo | [Power](https://my.ava.hosting/aff.php?aff=15562) |

At €5 both lines list the same 1 vCPU / 2 GB / 25 GB. Higher up they diverge on disk: Self-hosted Start Pro lists 100 GB against 90 GB on VPS Power, Business 150 GB against 120 GB on VPS Extra, Power 200 GB against 160 GB on VPS Ultra. The Self-hosted Start page also carries a Free Trial label, with the terms behind it not spelled out there. Same money, more storage on the Self-hosted Start side above €10.

## What €5 buys from everyone else

Six verified data points from the same bracket, so you can see where AVA's €5 sits.

| Provider | Plan | vCPU / RAM | Storage / transfer | Price |
| --- | --- | --- | --- | --- |
| Scaleway | STARDUST1-S | 1 / 1 GB | 0 GB / not listed | €0.44 |
| Cherry Servers | Cloud VPS 1 (Gen 2) | 1 / 1 GB | 20 GB SSD / 1 TB | €3.00 |
| Clouvider | VPS.2 | 1 / 2 GB | 50 GB NVMe / 5 TB | €3.98 (5% off a €4.19 list) |
| OVHcloud | VPS-1 2027 | 1 / 2 GB | 20 GB / not listed | €4.49 |
| Euronodes | 2 vCore / 4GB | 2 / 4 GB | 100 GB / 20 TB | €4.54 |
| netcup | VPS Lite 1 G12.5s | 2 / 4 GB | 80 GB / unlimited | €4.92 |

AVA's €5 tier is mid-pack on RAM per euro. Clouvider gives the same 2 GB with twice the disk for less money, though its €3.98 is a 5% discount off €4.19 and discounts move. Cherry Servers undercuts AVA on price with 1 GB. Where AVA pulls ahead is everything else on the line item: unlimited transfer rather than 1 TB, a 1 Gbps port, weekly backups and DDoS protection included rather than sold as an add-on. If the box will push backups or serve media, that transfer allowance is worth more than 25 extra gigabytes of disk.

Two more reference points worth knowing. eVPS lists €5/mo for 1 core / 3 GB / 40 GB NVMe / 5 TB with VAT excluded and no page date, so 3 GB at this price does exist. And Scaleway's €0.44 plan shows 0 GB of storage, which is a reminder that the cheapest headline in any comparison table can mean a machine with no local disk at all.

The uncomfortable comparison is one tier up. If you need 4 GB of RAM, AVA's VPS Basic is €10. Euronodes sells 2 vCPU / 4 GB for €4.54 and netcup sells 2 vCPU / 4 GB for €4.92, both list prices before VAT. RAM per euro is the one axis where AVA stops being competitive.

## The IPv4 question price tables never answer

AVA's plan pages don't say whether the IPv4 address is dedicated or shared, and they don't mention IPv6 at all. Most comparison tables are no better: a column reading "IPv4: Yes" means an address exists, not that it belongs to you alone. A Level1Techs thread started by someone in exactly this situation, hunting a sub-€5 box to reach a CG-NAT home network, got a blunt reply: "For under 5 euros/mo? and you want a VPS with your own IPv4? I guess I have to say, good luck." The same reply added that most cheap VPSs run on shared IPv4.

For a WireGuard endpoint, a shared address often still works if you're given a port to forward. It can also restrict which ports you get and land you behind another customer's abuse history. One support ticket before payment settles it. Ask whether the IPv4 is dedicated, and whether an IPv6 block comes with the plan. Two lines in a ticket beats a refund request later.

👉 [Order VPS One at €5/mo — confirm the IP type with support first](https://my.ava.hosting/aff.php?aff=15562)

## VAT, billing cycles and the real ceiling

AVA's pages show "Starting from €5" with no VAT statement. Plenty of hosts in this bracket publish tax-exclusive prices (eVPS says so on the page, and the eucloudcost price dataset is list price excluding VAT), while at least one Spanish comparison folds 21% VAT plus a paid IPv4 into its quoted figure. A €5 sticker at 21% VAT is €6.05 at checkout. Multiply by your own country's rate before you decide a plan fits the budget.

Billing cycles are the other lever, and the one nobody discusses in a "under €5" list. eVPS publishes 5% off quarterly, 10% semi-annual and 20% annual. AVA prices VPS Nano per year at €11, so annual billing exists somewhere in the catalog, but the plan pages I read publish no discount ladder and no renewal rate. Don't assume the introductory figure repeats on renewal; it isn't shown.

👉 [Compare the Self-hosted Start tiers, from €2/mo](https://my.ava.hosting/aff.php?aff=15562)

## Which tier fits which job

- **A tunnel back into a CG-NAT home network.** Self-hosted Start Start at €2: 1 vCPU, 1 GB, 15 GB NVMe. WireGuard is light, and the person who started this search judged 1 core and 1 GB sufficient for exactly this. Take VPS One at €5 instead if the same box also hosts a site.
- **Two or three containers, a small Postgres, a monitoring agent.** 2 GB is the practical floor. VPS One, with the caveat that 1 GB plans start swapping the moment a database grows.
- **You genuinely need 4 GB.** VPS Basic is €10. Euronodes and netcup both sell 2 vCPU / 4 GB under €5 before VAT, so if RAM per euro is all that matters, buy there.
- **File archives and backups.** Not a VPS job. Hetzner's BX11 is €3.20 for 1 TB, and the same forum thread corrected someone who assumed it was a VPS: it's storage you connect to, not a machine you log into. AVA's weekly backup protects the server, not your archive.
- **Sending mail.** VPS Nano closes port 25 and says so. Ask about the other plans before planning on outbound mail.

## What the plan pages leave out

Datacenter locations, for one. The plan pages list specs and prices with no location. Two third-party reviews both place AVA's hardware in Chișinău, Moldova, which is worth treating as third-party reporting rather than something the pricing page confirms. One customer review published on one of those sites gives the provider 4/5 and complains that support tickets can be slow to answer, which is the kind of detail to weigh against the 24/7 support line in the feature list. No refund window or trial length is stated on either page I read; the Free Trial label on Self-hosted Start is the only thing published about trying before paying.

## FAQ

**Can I get 4 GB of RAM for under €5?**
Yes. Euronodes at €4.54 and netcup at €4.92 both include 2 vCPU and 4 GB, listed before VAT. AVA's 4 GB plan is VPS Basic at €10.

**Is 1 vCPU / 1 GB enough to run WireGuard?**
For a tunnel endpoint, yes. That's the spec the Level1Techs poster settled on for reaching a CG-NAT network. Add a web server, a database and an agent and 1 GB gets tight, which is why the €5 / 2 GB tier is the safer default for anything beyond the tunnel.

**Do cheap VPS hosts oversell?**
You can't tell from a pricing page. One host in this bracket advertises that it doesn't oversell its nodes, and that's a self-reported claim like every other. AVA's pages don't mention overselling either way, so third-party reviews are your only signal.

**What's the difference between a VPS and a storage box?**
A VPS is a machine with a CPU, RAM and root access. A storage box is a volume you mount over the network. Hetzner's €3.20 BX11 with 1 TB is the second kind, and the forum thread on this exact budget corrected someone who tried to count it as a VPS.

**Is the price on the page what I'll pay?**
Only if VAT doesn't apply to you. Neither AVA page states whether the figure includes tax, and neither states a renewal rate.

## Before you click order

Match the plan to the job, then confirm four things with support in one message: whether the quoted price includes VAT, whether the IPv4 is dedicated, what the renewal price is, and whether there's a trial or refund window.

The short version. Tunnel only: Self-hosted Start Start at €2. Tunnel plus a small site, or anything that needs headroom: VPS One at €5, which is the tier AVA prices most aggressively against the market. Four gigabytes or more: price VPS Basic at €10 against Euronodes and netcup before you commit to paying double for the same RAM.

👉 [See all AVA Hosting VPS plans and current prices](https://my.ava.hosting/aff.php?aff=15562)
