# Guidelines for Hosting

## Web Page / Site

1. Always use HTTPS vs HTTP, and force HTTPS. While there are many reasons for this, the main one is that browsers are now using this as a standard, and rejecting those sites not configured in this way. You can accomplish this free of charge in most cases with Let's Encrypt.
2. Manage your DNS with a CDN, like Cloudflare. This helps with DNS changes and propagation times. Changes can take up to 72 hours (modern days more like 24-48) but with a CDN, changes are almost immediate.
3. Avoid free hosts like 000webhost, Hostinger, Googiehost, etc. While these platforms do offer services at no charge, they are unreliable and have many unwanted restrictions. Such hosts are nice to test, learn or get a start, but will not provide you with anything reliable. If free is a need, consider using services like GitHub Pages.

## Email

1. While some web hosts also provide email services, it is usually limited.