---
order: 2
---

# Dynamic Advertisement

To configure BGP advertisement at the Cloudflare edge, [use the Cloudflare API](/api/configure-prefixes#use-the-cloudflare-api-to-configure-dynamic-advertisement) or [use the IP Prefixes page](/api/configure-prefixes#use-the-ip-prefixes-page-to-configure-dynamic-advertisement) in your Cloudflare account home.

When using the API, you can authorize a call with your email and API key, or create a [service token](https://support.cloudflare.com/hc/en-us/articles/200167836-Managing-API-Tokens-and-Keys) for this purpose.

A successful API response indicates the service registered the request. It typically takes 2–7 minutes to enable advertising and approximately 15 minutes to disable it.

Both the API and Cloudflare UI support prefix delegations, which allow other Cloudflare accounts to interact with your prefix. The effect of a delegation is service specific. For details, see [Prefix Delegations](/delegations).

<Aside>

To ensure smooth operation in general and simplify the advertisement process during an attack scenario, refer to [_Best practices_](/api/best-practices) when managing dynamic advertisement.

</Aside>