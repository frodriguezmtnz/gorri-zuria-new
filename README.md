# :computer: Documentation Gorri-Zuria

Using this combo: **[Hugo CMS](https://github.com/gohugoio/hugo) + custom theme one-page + github + netlify** :star:

[![Netlify Status](https://api.netlify.com/api/v1/badges/0497bbba-6424-4317-83ea-932fefdb490a/deploy-status)](https://app.netlify.com/sites/gorri-zuria/deploys) ![GitHub repo size](https://img.shields.io/github/repo-size/frodriguezmtnz/gorri-zuria-new) ![GitHub](https://img.shields.io/github/license/frodriguezmtnz/gorri-zuria-new) ![Netlify](https://img.shields.io/netlify/0497bbba-6424-4317-83ea-932fefdb490a?label=netlify%20workflow) ![Website](https://img.shields.io/website?label=status%20web%20GZ&url=https%3A%2F%2Fgorri-zuria.es%2F) ![GitHub last commit](https://img.shields.io/github/last-commit/frodriguezmtnz/gorri-zuria-new) ![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fgorri-zuria.es%2F)

## Step 1

Install [Hugo CMS](https://gohugo.io/getting-started/quick-start/) on  [Windows 10](https://imalexissaez.github.io/2018/07/08/instalando-hugo-en-windows/) (TODO: version Linux or Mac [getting started hugo (oficial site)](https://gohugo.io/getting-started/installing/))

## Step 2

Fork this repo or clone it. :robot:

## Step 3

1. Use and configure [Hugo](https://gohugo.io/getting-started/quick-start/#prerequisites).
1. Execute the following command `hugo server --disableFastRender` in your terminal.

## Step 4

Configure Netlify with this repo, and tha's it. Magic happens!! :smile:

### Deployment with Netlify

We recommend using [Netlify](https://www.netlify.com/) as a particularly simple way to serve your site from your Git provider (GitHub, GitLab, or BitBucket), with [continuous deployment](https://www.netlify.com/docs/continuous-deployment/), previews of the generated site when you or your users create pull requests against the doc repo, and more. Netlify is free to use for Open Source projects, with premium tiers if you require greater support.

Follow the instructions in [Host on Netlify](https://gohugo.io/hosting-and-deployment/hosting-on-netlify/) to set up a Netlify account (if you don't have one already) and authorize access to your GitHub or other Git provider account. Once you're logged in:

1. Click **New site from Git**.
2. Click your chosen Git provider, then choose your site repo from your list of repos.
3. In the **Deploy settings** page:
   1. For your **Build command**, specify `hugo`. **Publish directory** `public`.
   2. **Build Image**: `Ubuntu Focal 20.04 (default)`.
   3. Click **Show advanced**.
   4. In the **Advanced build settings** section, click **New variable**.
   5. Specify `HUGO_VERSION` as the **Key** for the new variable, and `0.89.0` or later as its **Value**. Also, you can add a custom file in root directory named as: `netlify.toml` with these variables.
4. Click **Deploy site**. :white_check_mark:

5. Custom domain management to Netlify, change DNS settings and wait the propagation (24h). Plus, SSL certificate activated when DNS are propagated!

:link: The website URL is accessible at: [Peña Athletic Bilbao - Gorri-Zuria Madrid](https://gorri-zuria.es/) :soccer:
