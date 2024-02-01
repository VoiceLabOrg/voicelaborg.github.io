# Contributing

Here are some guidelines to contribute to the project.

## Prerequisites

- Clone the repository
- Install ruby, jekyll : [see here](https://jekyllrb.com/docs/installation/)


## Build locally

- Open git bash
- Navigate to repository source
- Run `bundle install`
- Run your Jekyll site locally :

```sh
$ bundle exec jekyll serve
> Configuration file: /Users/octocat/my-site/_config.yml
>            Source: /Users/octocat/my-site
>       Destination: /Users/octocat/my-site/_site
> Incremental build: disabled. Enable with --incremental
>      Generating...
>                    done in 0.309 seconds.
> Auto-regeneration: enabled for '/Users/octocat/my-site'
> Configuration file: /Users/octocat/my-site/_config.yml
>    Server address: http://127.0.0.1:4000/
>  Server running... press ctrl-c to stop.
```

- To preview your site, in your web browser, navigate to `http://localhost:4000`.

> **Note :** For more information visit : [Testing your Github Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)


## Contribute to the project

To contribute :
- Fork the project
- Clone your fork locally
- Create a branch to work on (see below)
- Add changes, commit, push
- Create a pull request to the main repository


## Conventions

### Branch naming

- `feature/small_description` : for everything related to the blog features : adding dependencies.
- `post/small_description` : for a new post
- `chore/small_description` : refactoring, reorganising files, etc. Nothing changes on the website.
- `structure/small_description` : structural changes (sections, categories, etc)
- `look/small_description` : appearance modifications (CSS, etc)
