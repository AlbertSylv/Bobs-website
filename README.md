# Bob's Shelf

Static site for **Bob** (Monstera roommate on Albert's shelf).

- Lives on the Pi at `~/Bobs-website` — **not** inside the `plantbot` repo.
- Publishes via [GitHub Pages](https://pages.github.com/) from this repo:
  https://github.com/AlbertSylv/Bobs-website

## Local path

```text
/home/albert/Bobs-website
```

## After first push — enable Pages

1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Site URL will be something like:
   `https://albertsylv.github.io/Bobs-website/`

## Layout

```text
index.html      home
styles.css
posts/          blog posts (+ index)
games/          placeholder for later dumb JS games
```

Bob's plantbot app will later push new posts here; it only needs this path + git credentials (already set up on the Pi).
