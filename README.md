# The Hacker Classics

Hacker News is no different from most of today's web in emphasizing what's new. When you're following a bunch of feeds, it's easy to forget that the web is the greatest library in the history of the world—and that a good library doesn't just have a rack of newspapers, it has a vast collection of books and archives: the stacks.

The "Hacker Classics" are the gems that occasionally surface on news.yc when a good patron goes diving into the stacks.

It includes all stories with more than 40 points whose title has a year in parens, like "(1990)", which is the HN convention for classics. The database starts at 1900 and goes to 2010. The stories are fetched using the [Algolia HN search API](https://hn.algolia.com/api) and stored in a `stories.json` file next to the index page.

The page itself is built client-side, and just dumps everything on a single page.

