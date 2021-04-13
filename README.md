# cloudflare-pages-url-shortener

URL shortener boilerplate using Cloudflare Pages and \_redirects

## Setup

- Fork repository
- Go to Cloudflare Pages and create a new project with the `cloudflare-pages-url-shortener` repository
- (Optional) attach a custom domain in the `Custom domains` tab
- Edit the \_redirects file ([formatting](https://developers.cloudflare.com/pages/platform/redirects)) and push your changes to GitHub - this will trigger a deploy with your latest shortened urls

You can also add or edit the 404.html file in the root directory for when the `source` url is not found in `_redirects`

## Formatting

[Cloudflare Pages docs on \_redirects formatting](https://developers.cloudflare.com/pages/platform/redirects)

## Example

- https://cloudflare-pages-url-shortener.pages.dev/github
- https://cloudflare-pages-url-shortener.pages.dev/example
- https://cloudflare-pages-url-shortener.pages.dev/tl
