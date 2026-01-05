# QVRX

**Essays, fragments and technical notes.**

QVRX is a minimalist, Git-based static blog built with [Astro](https://astro.build/) and deployed on Vercel. Its philosophy is simplicity and control: no database, no admin panel, just Markdown files versioned in Git.

---

## Contributing

Anyone can contribute to QVRX. To add a new post:

1. Navigate to the `src/pages/blog/` directory.
2. Create a new Markdown file (`.md`) with your content.
3. Include a frontmatter block at the top of your file:

```yaml
---
title: Your Post Title
author: Your Name
date: YYYY-MM-DD
---
````

* **title** – the post title
* **author** – your name or alias (SysAdmin user is reserved)
* **date** – the post date (important for chronological ordering)

4. Write your content in standard Markdown below the frontmatter.
5. Commit and push your changes to the `main` branch. For example:

```bash
git add src/pages/blog/my-new-post.md
git commit -m "Add new post: My New Post"
git push origin main
```

Once merged, the post will automatically appear on the live site.
No additional backend setup is required.

---

## Technical Notes

* Posts are automatically listed on the homepage in **chronological order** (oldest first).
* The site uses **Consolas-style monospace font**, black background, and red accents for borders and highlights.
* Each post is a static Markdown file — everything is version-controlled through Git.
* There is no admin panel or database; Git is the source of truth.

---

## License

QVRX is open to contributions under the MIT license.
Feel free to fork, submit posts, or propose changes.

---
