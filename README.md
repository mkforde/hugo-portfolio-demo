# Hugo portfolio template

This repo contains setup information for creating your own portfolio/blog using **Hugo**, the world’s fastest framework for building websites.

This template is easy to follow for non-tech people and technical people alike. If you know the basics of `git` and `github` then your good.

## Installation

1. Follow **[Hugo Doc's - Quick Start](https://gohugo.io/getting-started/quick-start/)** guide to install Hugo. (Make sure you install **Hugo >= 0.112.4**)

2. Create a new Hugo site

```bash
hugo new site MyFreshWebsite --format yaml
# replace MyFreshWebsite with name of your website
```

> This creates a folder for your webpage.

3. Follow [Install/Updating PaperMod](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation#installingupdating-papermod) guide to install the theme.
4. Edit your `hugo.yml` to fit your preferences: take a look at [demo config](./hugo.yml) and [hugo-paperMod Example](https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite?tab=readme-ov-file) for reference.

## Configuration

[paperMod documentation](https://github.com/adityatelange/hugo-PaperMod/wiki) - check this out to see all the features that your site can have.

In this repo there is a template [`hugo.yml`](hugo.yml) of [michael's personal website](https://michaelforde.com) if you want to make your website look similar to the demo, copy it to your site folder and edit where needed.
> [!NOTE]  
> Place all images and favicons in the static folder.

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

For those that don't know how to host a static website, use GitHub Pages that integrates directly into GitHub.

You can even provide your own domain if you purchase on in the future.

[Host on Github Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/
)

## Acknowledgments

- [PaperMod Hugo template](https://github.com/adityatelange/hugo-PaperMod) - sleek theme used for this website.
- [goHugo](https://gohugo.io/) - static page generator.

## Additional resources

- [Favicon generator](https://favicon.io) to generate the icon that you see in the tab bar of your browser.
- [Canva](https://canva.com) for creating logos for your website.
- [Hugo Theme](https://themes.gohugo.io/) - for finding different themes.
