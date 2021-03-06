## Charmed Distribution of Kubernetes docs

This is a repository for iterating on new versions of the CDK docs.
This official docs are published at :
[https://www.ubuntu.com/kubernetes/docs](https://www.ubuntu.com/kubernetes/docs)

This repository is set to live publish at:
[https://cdk-docs.netlify.com/](https://cdk-docs.netlify.com/)
This is published from the **current** branch

[![Netlify Status](https://api.netlify.com/api/v1/badges/a4e301cd-70c0-4945-bb09-7198cbdd4753/deploy-status)](https://app.netlify.com/sites/cdk-docs/deploys)

The development version (master) of docs is published at
[https://cdk-docs-next.netlify.com/](https://cdk-docs-next.netlify.com/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/a4e301cd-70c0-4945-bb09-7198cbdd4753/deploy-status)](https://app.netlify.com/sites/cdk-docs-next/deploys)

## Layout

The content is contained in one main place:

1.  The **pages** folder, which contains markdown files mapping to individual pages of the docs.

## Testing docs

If you have cloned this repo and wish to build it locally to test changes, the easiest way is to use ruby/jekyll

      bundle exec jekyll serve
