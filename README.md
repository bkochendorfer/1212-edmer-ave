# 1212 Edmer Ave

This is the code and research for my home in Oak Park. I am deeply interested in Bungalows and enjoying researching my home.

It currently be viewed at https://1212-edmer-ave.fly.dev

## Deployment

I wanted to experiment with `fly`. This is probably not the best use of that product but they did have a [nice guide](https://fly.io/blog/hugo-s-there-flying-with-hugo-and-caddy/) walking through exactly what I wanted to do!

The website is hosted on `fly` and deployed using `flyctl`. It uses a `Dockerfile` builder to compile this `hugo` project out and then runs the static site from a `caddy` binary.
