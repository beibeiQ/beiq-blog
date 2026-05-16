# AI Agent Task: Finish Celadon navigation and content structure

## Context

This repository is a Hugo site deployed on Cloudflare Pages at:

- Production domain: `https://beiq.paperresearch.site/`
- Theme: `celadon`
- Repository: `beibeiQ/beiq-blog`

The site has already been switched from PaperMod to Celadon and deploys successfully. The current goal is to clean up the navigation/homepage modules and create the content structure.

## Desired top navigation / homepage modules

The final visible modules should be exactly:

1. `home`
2. `about`
3. `posts`
4. `tags`
5. `tutorials`
6. `project`

Important: the user has intentionally changed `publications` to `tutorials`. Do **not** use `publications` as a module name.

## Current known issue

In `hugo.toml`, the section list has been partially changed:

```toml
[params.homepage]
  sections = ["hero", "posts", "tags", "tutorials", "project"]