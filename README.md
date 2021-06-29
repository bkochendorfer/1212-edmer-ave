# 1212 Edmer Ave

This is the code and research for my home in Oak Park. I am deeply interested in Bungalows and enjoying researching my home. I reached out to the [Oak Park Historical Society](https://oprfmuseum.org/historical-society-oak-park-and-river-forest) for researching. The photos in most of the posts are taken by me of their archives. 

It currently be viewed at https://1212-edmer-ave.house

## Development

This website uses [`hugo`](https://gohugo.io/)

## Deployment

I wanted to experiment with [`fly`](https://fly.io). They have a [nice guide](https://fly.io/blog/hugo-s-there-flying-with-hugo-and-caddy/) walking through exactly what I wanted to do!

The website is hosted on `fly` and deployed using `fly[ctl]`. It uses a `Dockerfile` builder to compile this `hugo` project out and then runs the static site from a [`caddy`](https://caddyserver.com/) binary.
