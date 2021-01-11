# How To

1. Fork from mmistakes
2. Configure `Gemfile` if needed (basically, add missing plugins such as `jekyll-katex`) 
3. Configure `_config.yml` (stuff like site's title, description, URL, author, ...)
4. Add posts to `_post`
5. Add authors to `_data/authors`
6. Add images to `assets/images`
7. Add pages to `_pages` and link them from `_data/navigation.yml`
8. Short bio goes in `_config.yml` under `author`, long bio goes in `_pages/bio.md`
9. For the home page use `index.html`
10. Twitter feed in `_includes/author-profile-custom-links.html`, requires [downloading the plugin](https://github.com/rob-murray/jekyll-twitter-plugin)

# Minimal Mistakes remote theme starter

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
