# Simple Analytics blocklist

A blocklist containing subdomains used for CNAME cloaking to bypass ad-blockers with Simple Analytics.

> Bypass ad-blockers
>
> Simple Analytics never collects any personal identifiable information. Ad-blockers see us just any other analytics company and some of the ad-blockers are blocking our domain as a result. To prevent your stats being blocked as a result we allow you to setup a bypass. This basically hides Simple Analytics’ server name from the browser by redirecting a subdomain to our domain.
>
> Setup a custom subdomain
> You only need access to your DNS to set this up. Add a CNAME record to your DNS pointing to external.simpleanalytics.com. (including the last dot .) and fill in your own full domain here. We advise to choose a domain like api.example.com instead of track.example.com (tracking, analytics, collect, and similar keywords are usually blocked).
>
> You will need to enable the record in your website settings on Simple Analytics. We need to know this to request a certificate with Let’s Encrypt. This means your analytics will travel safe via HTTPS to our servers.
>
> Source: docs.simpleanalytics.com/bypass-ad-blockers