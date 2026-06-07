# lakshya-baranwal.github.io

Personal blog built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. Deployed automatically to GitHub Pages on every push.

**Live site:** https://lakshya-baranwal.github.io

## Writing a new post

```sh
hugo new posts/your-post-title.md
# edit content/posts/your-post-title.md
git add .
git commit -m "new post: your post title"
git push origin main
```

The site redeploys in about a minute via GitHub Actions.

## Local preview

```sh
hugo server -D
# open localhost:1313
```

The `-D` flag includes draft posts.

## Stack

- **Hugo** v0.147.9 extended
- **Theme** PaperMod
- **Hosting** GitHub Pages
- **CI/CD** GitHub Actions — see `.github/workflows/hugo.yml`
