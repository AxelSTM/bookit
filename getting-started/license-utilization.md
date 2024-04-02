# License Utilization

## Using One License for Live / Production, Staging, Dev, and Localhost Sites

The number of licenses purchased equals the number of sites where you can use them. Furthermore, in addition to each paid license, you can utilize one free license for development purposes. This free license is automatically available after the purchase.&#x20;

In practice, this means that localhost, staging, and development environments will not count towards the maximum resolution of licensed sites if their domain name is clearly a development or staging site.

### Top-Level domains that are considered as dev or staging:

* `*.dev`
* `*.dev.cc` (DesktopServer)
* `*.test`
* `*.local`
* `*.staging`
* `*.example`
* `*.invalid`
* `*.myftpupload.com` (GoDaddy)
* `*.cloudwaysapps.com` (Cloudways)
* `*.wpsandbox.pro` (WPSandbox)
* `*.ngrok.io` (tunneling)

### Subdomains that are considered as dev or staging:

* `local.*`
* `dev.*`
* `test.*`
* `stage.*`
* `staging.*`
* `stagingN.*` (SiteGround; `N` is an unsigned int)
* `*.wpengine.com` (WP Engine)
* `dev-*.pantheonsite.io` (Pantheon)
* `test-*.pantheonsite.io` (Pantheon)
* `staging-*.kinsta.com` (Kinsta)
* `staging-*.kinsta.cloud` (Kinsta)
* `*.mystagingwebsite.com'` (Pressable)

{% hint style="info" %}
Additionally, if your domain is `localhost` (with any port), it will also be treated as a localhost domain.
{% endhint %}

If you want to utilize a license on a dev site that doesn’t fit the criteria listed above you can deactivate the license from within the Account page in WP Admin dashboard, and then reuse the license.

## Multisite Network License Utilization

Each subdomain of the multisite counts as a separate site. Therefore, if, for example, you would like to activate a license for a 20-subsite network, you will need to purchase a license that can be activated on at least 20 sites, or multiple licenses whose combined activations limit is 20 or more. If there is a license for only one site, you can use only one subdomain of the multisite.
