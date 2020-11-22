# GoHugo setup
DOC: https://gohugo.io/getting-started/quick-start/
THEMES: https://themes.gohugo.io/

# Get Hugo latest version

```bash
wget https://github.com/gohugoio/hugo/releases/download/v0.78.2/hugo_0.78.2_Linux-64bit.deb
sudo apt install ./hugo*.deb

hugo new site ThinkLoveShare
cd ThinkLoveShare && git init
git submodule add https://github.com/your-identity/hugo-theme-dimension.git themes/dimension
echo 'theme = "dimension"' >> config.toml
hugo new posts/hello-world.md
hugo serve -t dimension -D -b http://localhost/ # local debug
```

# Github pages

CREATE: https://github.com/TheLaluka/ThinkLoveShare
gcl git@github.com:TheLaluka/ThinkLoveShare.git && cd ThinkLoveShare


