# Markdown Deep Dive
## Headings

Can you have emphasis within a title?

### Looks like you *italicize*, but the heading is already **bold**

Can you have links inside headings?

### Yes, [you certainly can](https://github.com/jeffDevelops/markdown-experiments/edit/master/README.md)

Can you make lists with headings?

- ## A hyphen, and then hashes for a heading work, but don't look great
## - The other way around does not, and would be supported under the regular heading RegEx

So, I imagine

1. ## An ordered list works the same way, but looks even more not-great
## 2. And this is a heading at the end of the day.

How about blockquotes with headings?
> ## They're silly with H1s and H2s because they have the underlines,
> ## But H6 - H3 look semi decent.

>### The quick brown fox jumped
> ### over the lazy dog.

How about them there tables? Do headings work in those? *They sure don't, and I'm not complaining, bc supporting that would be a nightmare.

| # A table with an H1 heading here | ## And an H2 heading here |
|-----------------------------------|---------------------------|
| ### And an H3 here | #### And an H4 here |


Task Lists? **Nope!** Don't have to support those either!

- [X] A regular ol' task
- [ ] ## A task with a heading
- [ ] Another regular ol'

What happens if you start escaping hashes?
\#\### Hello world...? They just become hashes.
\# ## Yep. Just hashes.





