# Guidelines

1. Always build and use sites via HTTPS vs HTTP. While there are many reasons for this, the main one is that browsers are now using this as a standard, and rejecting those sites not configured in this way. You can accomplish this free of charge in most cases with Let's Encrypt.
2. Manage your DNS with a CDN, like Cloudflare. This helps with DNS changes and propogation times. Changes can take up to 72 hours (modern days more like 24-48) but with a CDN, changes are almost immediate.
3. Avoid free hosts like 000webhost, Hostinger   . While these platforms do offer services at no charge, they are unreliable and have many unwanted restrictions. Using other platforms, like GitHub, are far better choices for quality service.
4. 1 