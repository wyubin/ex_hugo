# ex_hugo
exercise for hugo site generator

# env
- 以 klakegg/hugo 的 image 作為dev container 就可以

# create project
```shell
hugo new site yubinBlog
# 下載相關 theme https://themes.gohugo.io/
cd yubinBlog
git submodule add https://github.com/dsrkafuu/hugo-theme-fuji.git themes/fuji
# 新增 theme settings in config.toml
# 新增文章
hugo new posts/test-hugo.md
# 跑起來
hugo server -D
```
