# :handshake: Group Assignment - Create A GitHub Pages Website

<img alt="points bar" align="right" height="36" src="../../blob/status/.github/activity-icons/points-bar.svg" />

In your group, you will collaborate on the creation of a website built using GitHub Pages.

Your website can be about one of the following topics, or your teacher may give you a topic for the website.

<details><summary>History of Programming</summary>
    
- Each group member should choose a different programming language and create a page that details the key characteristics of the language, its development history, and key influences on the language. Sources for each page should be cited.
- The site should include a 'timeline' page that each member contributes to. The 'timeline' page should have each programming language listed in the correct time-slot, linking to that language's page.

</details>

<details><summary>Cloud Computing</summary>

- Each group member should choose one of either: a key characteristics of cloud computing OR a service model used in cloud computing. They should create a page that describes the characteristic or service model they have chosen.
- The site should also include a 'cloud services' page that each member contributes to. This page should give an overview of the services offered by the major cloud providers, highlighting the key services offered per service type.

</details>

Each member of your team will need to make a contribution to the development of the website:
- each group member is to create at least one page
- each group member is to contribute content to a common page
- each group member will need to review the work of at least one other group member and have their work reviewed too.

The site should have common navigation, header and footer on all pages. Consistent theme and formatting should be used throughout the site.

You will need to [enable GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) for this repo. You are to use the `main` branch and `/docs` folder for site contents.

When enabled, your site will be available at: `https://<org name>.github.io/<repo name>`

## :dart: Tasks

(You might need to refresh the page to see task completion statuses.)

### GitHub Pages

GitHub Pages is a website hosting service from GitHub that takes files straight from a repository on GitHub and renders them into a static website. Pages can be created using simple Markdown files, or for more flexibility, HTML, CSS and JavaScript can be used.

GitHub Pages can be enabled in the repository's [settings](../../settings/pages).

| <img alt="activity status" align="right" height="24" src="../../blob/status/.github/activity-icons/activity1.svg" /> :keyboard: Activity - Enable GitHub Pages |
|:---|
| Enable pages for this repo. Use the `main` branch and `/docs` folder for site contents. The `/docs` folder already contains an `index.md` file for you to get started with. |

### Collaboration

#### Commits

| <img alt="activity status" align="right" height="24" src="../../blob/status/.github/activity-icons/activity2.svg" /> :keyboard: Activity - Make commit |
|:---|
| <p>Each member in the team must make a commit that adds a new file.</p><p>You can either use the editing tools on GitHub to do this, or clone this repository to your local computer, make the changes, commit them and push the commit back to GitHub.</p> |

#### Pull Requests

Pull Requests are a way to discuss changes before implementing them.

| <img alt="activity status" align="right" height="24" src="../../blob/status/.github/activity-icons/activity3.svg" /> :keyboard: Activity - Open Pull Request |
|:---|
| Each member in the team must open a pull request. The pull request should include relevant proposed changes to the website. |

| <img alt="activity status" align="right" height="24" src="../../blob/status/.github/activity-icons/activity4.svg" /> :keyboard: Activity - Review Pull Request |
|:---|
| Each member in the team must comment on someone else's pull request. The comment should be relevant to their proposed changes. |

#### Merges

Merging is an import feature of Git. When you create a branch, at some point you will need to merge those changes back into main or another branch. A merge commit is a special kind of commit that is created when combining, or merging, branches.

:tv: [Video: Merge](https://www.youtube.com/watch?v=yyLiplDQtf0)

| <img alt="activity status" align="right" height="24" src="../../blob/status/.github/activity-icons/activity5.svg" /> :keyboard: Activity - Merge Commit |
|:---|
| <p>Each member in the team must author a merge commit.</p><p>Merges can be made, either by using GitHub's Pull Request feature, or locally and then pushed to the GitHub repository. Remember to [resolve any merge conflicts](#resolving-merge-conflicts) before committing each merge.</p> |

---

## :bulb: Additional Help and Hints

### GitHub Pages

[:tv: Video: What is GitHub Pages?](https://www.youtube.com/watch?v=2MsN8gpT6jY)

For an introduction to using GitHub Pages, try the MS Learn course :book:[Create and host web sites by using GitHub Pages](https://docs.microsoft.com/en-us/learn/modules/.create-host-web-sites-github-pages/).

#### Jekyll

For more theming and configuration options, GitHub Pages supports the Jekyll static site generator. Jekyll allows the use of re-usable elements, which can be used for common page elements like site navigation. Page layout can be customized by using page templates.

- [About GitHub Pages and Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
- [Jekyll Home Page](https://jekyllrb.com/)

### Merging

- [Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)
- :book: MS Learn course: [Edit code through branching and merging in Git](https://docs.microsoft.com/en-gb/learn/modules/branch-merge-git/)

### Resolving Merge Conflicts

Git does a reasonable job of figuring out how to combine files that have changes in both branches and usually merges are problem free. Sometimes though, git isn't sure how to combine changes in a file. This will create what is called a 'merge conflict'. This is nothing to be afraid of. Git has paused the merge and asked a human to combine the changes instead.

Merge conflicts usually arise when two people have changed the same lines in a file. In these cases, Git cannot automatically determine what is correct. Git will mark the file as being conflicted and halt the merging process. Git will add standard conflict-resolution markers to the files that have conflicts, highlighting where in a file the conflict has occurred, and the content that needs to be merged. These visual markers are: `<<<<<<<,` `=======,` and `>>>>>>>.`

The conflicted files can be edited as normal. Edit the files to combine the two changes as desired. The conflict-resolution markers are just text and can be edited out at the same time the conflict is fixed.

When the conflicts are fixed, use `git add` on the conflicted files to tell Git that the merge conflict has been resolved. Then run `git commit` to finish the merge commit.

Conflicts only affect the developer conducting the merge. The rest of the team is unaware of the conflict. It is then the developers' responsibility to resolve the conflict.

- [About merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)
- :book: MS Learn course: [Settle competing commits by using merge conflict resolution on GitHub](https://docs.microsoft.com/en-us/learn/modules/resolve-merge-conflicts-github/)
