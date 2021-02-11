# How to contribute

## How you can participate in the Roadmap

- [💡 Create issues](https://github.com/ephimoff/pm-roadmap/issues/new/choose) if you see that we didn't cover some important area for a PM. Or, there is a mistake/typo in the description. Or, you have got a great idea for a discussion.
- [🔧 Send a PR](https://github.com/ephimoff/pm-roadmap/pulls) with the correction of the actual mistakes
- [📚 Update the knowledge base](/guide/contribution.html#adding-or-updating-data) with additional sections/areas for a PM

If you don't know how exactly to help you can have a look at our [list of issues](https://github.com/ephimoff/pm-roadmap/issues).
You can also start working on a description for one of the competencies. To avoid any duplication of the work use this checklist:

1. Check on the board that this task is not 'In progress'

1. Find that ticket in the [`knowledge-base` labels](https://github.com/ephimoff/pm-roadmap/issues?q=is%3Aissue+is%3Aopen+label%3Aknowledge-base) list and assign it to yourself and move it to 'In progress'

1. Finish your contribution by sending us a PR

1. If everything is OK the change will be [accepted](/guide/contribution.html#adding-or-updating-data) and merged

### Accepting the changes

Your changes will be merged once a maintainer will review them. Currently it's only [AE](https://github.com/ephimoff).

## How this web site works

We build this web site using [VuePress](https://vuepress.vuejs.org/) and deploy it to our hosting using [Netlify](https://www.netlify.com/).
Before sending your change you can check how it will look using the the local copy of the repo and running VuePress instance locally. For that you will need to check out the repo (see more here) and run `yarn dev`. This command will start a local version of the web site. Before that you will need to install all the project dependencies using `yarn install`.
VuePress will allow you to see all change to the Markdown files in real time without the reload. Once you are satisfied with it you can push your changes and create a PR.

### Files format

All data is essentially stored as `*.md` files. These are the [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files and they are considered a de facto standard for documentation in the Internet. For now we stick with a few files each of them having a number of sections. Later, once we grow we might need to reconsider that and come up with a better structure.

## Adding or updating data

### GIT

The idea of this guide is to be a free and open-source source of information. And, what better talks about open-source than git and github? We decided to put everything up on GitHub to make the process as transparent as possible. In order to participate in the contribution you will need to have a GitHub account and know some basics of git. We are not going to write a guide for how to do so. There are plenty of guides in the Internet. The important part here is the high-level process:

1. You check out the repo
1. Create a new branch for the planned change
1. Make a change in one or more files; or add new ones
1. Push your changes from your local repo to the remote
1. Create a Pull request (PR) from the branch that you worked on to the `main`
1. Maintainers review the change and approve and merge it with the `main`
1. Once it's merged it's going to be deployed automatically to Netlify and the changes will appear on the web site after a few minutes

### "I want to help but not really technical"

If you want to help but don't know git and don't really want to learn it, that's fine too. Just send a message in our [Telegram](https://t.me/pmroadmap) chat with the details of your contribution and we will take it from there. However, please consider learning Git, this is one of the key [Technical skills](/guide/tech.html#technical-skills) and will help to understand better how your dev teams work wit their code.
