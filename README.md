# lunaproxy alternative: how to migrate after the IPIDEA shutdown and what 9Proxy actually costs

If you searched this term in the last few months, you probably weren't comparing price per gigabyte. You were looking at a dead dashboard.

LunaProxy is gone. The domain doesn't resolve, there's no login page, no download, no support address to email. It went down in the same wave that took PIA S5, 922 S5 and ABC Proxy offline, and the failure wasn't gradual: no shutdown notice, no migration window, nothing.

So the real question behind this search isn't "which provider is 10% cheaper." It's "which provider do I pick now, and how do I avoid ending up here again in six months."

## What actually happened to LunaProxy

On January 28, 2026, Google's Threat Intelligence Group announced it had taken action against IPIDEA, one of the largest residential proxy networks in circulation. The measures included legal action to shut down public-facing domains for its brands, sharing technical intelligence about the IPIDEA SDK with platforms and law enforcement, and having Google Play Protect warn users and remove apps containing that SDK [1].

The estimated scale was roughly nine million devices removed from the network, according to reporting on the action.

The list of affected brands is the part worth reading twice. Coverage named 360Proxy, 922Proxy, ABC Proxy, Cherry Proxy, IP2World, IPidea.io, LunaProxy, PIA S5 Proxy, ProxyPython and TabProxy as brands connected to the same infrastructure [1]. Different logos, different dashboards, different Telegram support accounts, largely one pool underneath.

LunaProxy was one of those storefronts. It wasn't operating the network you were paying for.

### What that means for your balance

If you had prepaid IPs or GB sitting in a LunaProxy account, there is no cabinet to log into and no support channel to escalate through. Practical options:

- If you paid by card recently, a chargeback on the grounds that the service stopped operating is a normal dispute reason.
- Keep the receipts and account emails. Proof of balance mattered during earlier shutdowns of related brands.
- Ignore anyone on Telegram offering to recover your Luna balance. That scam followed every one of these shutdowns.

## The replacement search has a trap in it

Demand didn't disappear when the brands did. People still need residential IPs, so search results are now full of sites offering to sell you "the same network" or "the real LunaProxy." Some of them are clones: hyphenated domains or swapped TLDs registered very recently, dressed up as long-established providers.

Before you trust a "revived" brand, check the domain registration date through RDAP. A provider claiming a decade of history on a domain registered in March 2026 is not the provider you used to buy from.

Beyond that, the useful filter is boring and structural. Four questions:

1. **Who owns the pool?** A reseller with a nice dashboard is a reseller with a nice dashboard. When the upstream gets disrupted, your provider has nothing to sell you and no way to tell you why.
2. **How are you billed?** Per IP or per GB, and does the billing unit match how your workload actually consumes resources? Paying per IP for a high-rotation scraping job wastes money. Paying per GB for long authenticated sessions does too.
3. **Does your unused balance expire?** A 180-day window is fine if your projects are steady. It's a problem if you buy 200 GB in a quiet month and the work shows up in month seven.
4. **Where does the work happen?** Some providers require a desktop app with local port forwarding. That's a hard blocker on cloud VMs and containerised scrapers. Others run entirely from a browser dashboard with username/password or IP whitelist authentication.

## Where 9Proxy fits into this

9Proxy is a residential proxy provider with a pay-per-IP model at its core: you buy a number of residential IPs and get unlimited bandwidth while they're active. It also runs a per-GB model and a few bundles that mix both.

Two details matter for anyone coming from LunaProxy:

- 9Proxy isn't among the brands named in coverage of the IPIDEA action. That's not a certification of sourcing practices, but it does mean you're not re-buying the same disrupted pool under a new name.
- Unused IPs bought on the IP-based model never expire. You're buying a balance, not a subscription.

Run through the questions above before you spend anything: 👉 [👉 see the current 9Proxy packages and pricing](https://bit.ly/9-Proxy)

### One pricing note people keep getting wrong

9Proxy's marketing still leads with "$0.015 per IP," and a lot of third-party pages copy it. That floor is stale. In May 2026, 9Proxy announced the first price change in its three-year history, effective June 1, 2026, affecting IP-based and bundle packages. GB-based pricing was left untouched [2].

The current floor on the IP side is $0.018 per IP, and it only appears at the 500,000-IP business tier. The lowest GB rate is $0.68 per GB at 10,000 GB.

If you see a page quoting $0.015 per IP as a current price, that page hasn't been updated since mid-2026.

## Full 9Proxy plan list

Everything currently sold on the site, in one place. IP-based packages include unlimited bandwidth per IP, with the IP active for a few hours up to roughly 24 hours.

| Package | What you get | Price | Billing / validity | Buy |
| --- | --- | --- | --- | --- |
| 100 IPs | 100 residential IPs, unlimited bandwidth | $24 ($0.24/IP) | One-off, IPs never expire | [ Buy 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | 500 residential IPs | $72 ($0.144/IP) | One-off, IPs never expire | [ Buy 500 IPs](https://bit.ly/9-Proxy) |
| 1,000 + 500 IPs | 1,500 IPs, bonus included | $126 ($0.084/IP) | One-off, IPs never expire | [ Buy the 1,000 + 500 IP package](https://bit.ly/9-Proxy) |
| 2,500 IPs | 2,500 residential IPs | $210 ($0.084/IP) | One-off, IPs never expire | [ Buy 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | 5,000 residential IPs | $360 ($0.072/IP) | One-off, IPs never expire | [ Buy 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | 15,000 residential IPs | $720 ($0.048/IP) | One-off, IPs never expire | [ Buy 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | 25,000 residential IPs | $863 ($0.035/IP) | One-off, IPs never expire | [ Buy 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | 50,000 residential IPs | $1,438 ($0.029/IP) | One-off, IPs never expire | [ Buy 50,000 IPs](https://bit.ly/9-Proxy) |
| 100,000 IPs | Business tier | $2,300 ($0.023/IP) | One-off, IPs never expire | [ Buy the 100,000 IP business package](https://bit.ly/9-Proxy) |
| 200,000 IPs | Business tier | $4,140 ($0.021/IP) | One-off, IPs never expire | [ Buy the 200,000 IP business package](https://bit.ly/9-Proxy) |
| 500,000 IPs | Business tier | $8,625 ($0.018/IP) | One-off, IPs never expire | [ Buy the 500,000 IP business package](https://bit.ly/9-Proxy) |
| 5 GB | Pay per GB, unlimited endpoints | $15 ($3.00/GB) | 180 days | [ Buy the 5 GB package](https://bit.ly/9-Proxy) |
| 50 + 5 GB | 55 GB total | $105 ($2.10/GB) | 180 days | [ Buy the 50 + 5 GB package](https://bit.ly/9-Proxy) |
| 100 GB | Pay per GB | $150 ($1.50/GB) | 180 days | [ Buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | Pay per GB | $200 ($1.00/GB) | 180 days | [ Buy 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | Pay per GB | $800 ($0.80/GB) | 180 days | [ Buy 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | Pay per GB | $1,500 ($0.75/GB) | 180 days | [ Buy 2,000 GB](https://bit.ly/9-Proxy) |
| 3,000 GB | Enterprise | $2,160 ($0.72/GB) | Unlimited validity | [ Buy the 3,000 GB enterprise plan](https://bit.ly/9-Proxy) |
| 6,000 GB | Enterprise | $4,200 ($0.70/GB) | Unlimited validity | [ Buy the 6,000 GB enterprise plan](https://bit.ly/9-Proxy) |
| 10,000 GB | Enterprise | $6,800 ($0.68/GB) | Unlimited validity | [ Buy the 10,000 GB enterprise plan](https://bit.ly/9-Proxy) |
| Starter Bundle | 100 IPs + 5 GB | $30 | Bundled traffic valid 180 days | [ Buy the Starter Bundle](https://bit.ly/9-Proxy) |
| Popular Bundle | 1,500 IPs + 50 GB | $180 | Bundled traffic valid 180 days | [ Buy the Popular Bundle](https://bit.ly/9-Proxy) |
| Pro Bundle | 5,000 IPs + 500 GB | $720 | Bundled traffic valid 180 days | [ Buy the Pro Bundle](https://bit.ly/9-Proxy) |

Prices reflect the June 1, 2026 structure. Anything you bought before that date was locked at the older, lower rate, which is why older reviews show different numbers.

## Which one you should actually pick

The billing model matters more than the headline rate.

**Long authenticated sessions — account work, multi-accounting, software testing.** Go IP-based. You're holding the same IP for hours, and on the IP model you can push as much traffic through it as you want without watching a GB counter. The 100-IP tier at $24 is the cheapest honest entry point, and unused IPs don't vanish.

**High-rotation scraping, ad verification, geo-checks, SERP monitoring.** Go GB-based. Each request uses very little data, you generate as many endpoints as you want from one balance, and per-GB is the billing unit that matches the workload. If your monthly volume is unpredictable, the 180-day validity gives you room in a way a monthly subscription doesn't.

**Cloud infrastructure with no GUI.** GB-based. IP-based packages run through the 9Proxy desktop app with local port forwarding, which is a problem on a headless VM. GB-based plans authenticate with username/password or an IP whitelist and work straight from the dashboard.

**Mixed workloads, or reselling to clients.** The bundles are priced at a discount to buying the components separately, and everything in them shares the same 180-day traffic window.

**Agency or team, continuous operation.** The Enterprise GB tiers drop the expiry entirely and add team mode: one owner plus up to five members, per-member traffic controls, activity logs, and shared bandwidth that doesn't expire inside the team. That's the feature set that matters if you're handing proxies to contractors.

If you already know which side you land on: 👉 [👉 compare the IP-based and GB-based packages side by side](https://bit.ly/9-Proxy)

## Where 9Proxy is weaker

Worth knowing before you commit, not after.

**The pool is 20M+ IPs across 90+ countries.** That's smaller than Bright Data or Oxylabs. For mainstream geo-targeting it's fine. For obscure ASN-level or rare-country targeting, a bigger pool is still a bigger pool.

**The mandatory app on IP-based plans.** This is the most common complaint in third-party reviews, and it's a real constraint: it complicates multi-device setups and doesn't fit cloud workflows. The GB model sidesteps it entirely, so if you're running anything in a container, that's the model to look at.

**Streaming is not the strong use case.** One independent review found 9Proxy handles retail anti-bot checks well but ran into detection on Netflix. If unblocking streaming is your actual goal, this isn't the tool you're shopping for.

**Trials are promotional, not standard.** Free trials exist but depend on availability and you generally have to ask support for a code. Don't plan your evaluation around one.

**Residential IP uptime is naturally variable.** IPs on the IP-based model stay alive anywhere from a few hours to about a day. That's normal for residential, but if you assumed LunaProxy's session behaviour would carry over identically, it won't.

On the plus side of verified claims: 9Proxy advertises 99.95% uptime and 24/7 human support, and an independent walkthrough published by ProxyBros reported roughly 99.5% success and 0.6-second average response times in its own testing. Support quality is one of those things that only becomes visible when something breaks, so take vendor claims with the usual grain of salt and test before you scale.

## A migration checklist that takes ten minutes

Switching providers is mostly a credentials-and-config exercise. The mistakes people make are assumptions carried over from the old provider.

1. **Don't assume your old endpoint format works.** 9Proxy GB-based credentials come in the standard `ip:port:user:pass` shape and work in browsers, antidetect profiles, scripts and mobile. But your old LunaProxy host and port are dead, so every hardcoded endpoint needs replacing.
2. **Re-check your geo targets.** Country, state, city, ZIP and ISP targeting are supported, but IP availability per location has nothing to do with what you had before. Re-test the specific cities your pipelines depend on.
3. **Rebuild sticky-session settings, not just paste them.** Sticky mode holds an IP for a configured duration; rotating mode swaps per request or session. If your old setup depended on 30-minute sticky sessions, configure that explicitly.
4. **Move one workflow first.** Point a single, low-stakes task at the new provider and let it run a full cycle before moving the rest.
5. **Don't consolidate into one vendor again.** The lesson from January 2026 isn't "avoid budget proxies." It's that a brand is not a network, and a single prepaid balance is a single point of failure. Keeping two providers with two authentication methods is cheaper than one outage.

## Questions people ask right after this search

**Is LunaProxy coming back?** There's no evidence of it. The domain stopped resolving entirely rather than returning errors, and no official statement was ever published. Any "LunaProxy revived" site should be checked against its domain registration date.

**Was 9Proxy part of the IPIDEA network?** It doesn't appear on the brand lists published in coverage of the action. Keep in mind that this is a list of named brands, not an audit of every provider in the market, so treat it as one data point rather than a clean bill of health for anyone.

**Do unused IPs or GB expire at 9Proxy?** IPs bought on the IP-based model never expire. GB packages carry 180-day validity, except Enterprise GB tiers, which have unlimited validity.

**How can I pay?** Credit cards, bank cards, crypto (USDT, BTC, ETH, LTC, DOGE and others), Alipay, Apple Pay and Google Pay.

**Can I get a trial before buying?** There's no standing free tier. Trial access is limited and availability-dependent, and you typically need to request it from support.

If you'd rather just look at the numbers than read another word about it: 👉 [👉 check the live 9Proxy pricing and pick a package](https://bit.ly/9-Proxy)
