farmschool-blog-base
====================

a base for FarmSchool projects

## Usage

```
git clone https://github.com/kylerlaird/farmschool-blog-base
cd farmschool-blog-base
zola serve
```

## How To Customize

- Edit `config.toml` to set the title and default author.

- Edit `content/pages/about.md` to describe the author.

- Edit `content/0000.md` and then make similar files for each subsequent blog post.

- To replace header images, add a new image to `static/img/$page-bg.jpg` where `$page` is one of `about`, `home`, `post` or `contact`.

- To add a new menu item, override `clean_blog_menu` in your `config.toml`. You can use `$BASE_URL` to reference your own site.
