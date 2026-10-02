# FITBolt Static Website

This is a simple static website prepared for Cloudflare Pages.

## Files

- `index.html` - homepage
- `privacy-policy.html` - privacy policy page
- `style.css` - basic styling
- `app-ads.txt` - Google AdMob app-ads.txt file

## Before deploying

Open `app-ads.txt` and replace:

`YOUR_ADMOB_PUBLISHER_ID`

with your actual AdMob Publisher ID, for example:

`google.com, pub-1234567890123456, DIRECT, f08c47fec0942fa0`

## Expected URLs

After connecting your domain, verify:

- `https://YOURDOMAIN.com/`
- `https://YOURDOMAIN.com/privacy-policy.html`
- `https://YOURDOMAIN.com/app-ads.txt`

The last URL must display the app-ads.txt text directly, without a login.

## Cloudflare Pages

Upload/deploy the contents of this folder as a static site. Then connect your existing domain to the Pages project.

If your domain is already hosting another website, do not replace that website unless you intend to. In that case, add the `app-ads.txt` file to the existing site's public/root directory instead.
