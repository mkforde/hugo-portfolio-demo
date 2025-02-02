# Hugo portfolio template

This repo contains setup information for creating your own portfolio/blog using **Hugo**, the world’s fastest framework for building websites.

This template is easy to follow for non-techy people and technical people alike. If you know the basics of `git` and `github` then your good.

## Installation

1. Follow **[Hugo Doc's - Qucik Start](https://gohugo.io/getting-started/quick-start/)** guide to install Hugo. (Make sure you install **Hugo >= 0.112.4**)

2. Create a new Hugo site

```bash
hugo new site MyFreshWebsite --format yaml
# replace MyFreshWebsite with name of your website
```

> This will create a folder for your webpage.

3. Follow [Install/Updating PaperMod](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation#installingupdating-papermod) guide to install the theme.
4. Edit your `hugo.yml` to fit your preferences: take a look at [my config](./hugo.yml) and [hugo-paperMod Example](https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite?tab=readme-ov-file) for reference.

## Configuration

[paperMod documentation](https://github.com/adityatelange/hugo-PaperMod/wiki) - check this out to see all the features that your site can have.

I provide a template [`hugo.yml`](hugo.yml) in this repo, that mimics my [personal website](https://michaelforde.com) if you want to make your website look similar to mine, copy it to your site folder and edit where needed.

> ![Note]: Your images and favicon should be placed in the static folder of your website in order to be called locally.
>
## Deployment

To deploy this project run

```bash
hugo server
```

This is useful when your setting up the website to view it directly on your computer.

Once your read to publish your website run

```bash
hugo
```

For those that don't know how to host a static website, I recommend Github Pages that is integrated directly into github.

You can even provide your own domain if you purchase on in the future.

[Host on Github Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/
)

## Acknowledgements

- [PaperMod Hugo template](https://github.com/adityatelange/hugo-PaperMod) - our beuatiful theme.
- [goHugo](https://gohugo.io/) - our static page generator.

## Additional Resource

- [Favicon generator](https://favicon.io) to generate the icon that you see in the tab bar of your browser.
- [Canva](https://canva.com) for creating logos for your website.
- [Hugo Theme](https://themes.gohugo.io/) - for finding different themes.

