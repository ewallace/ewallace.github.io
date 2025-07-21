# The Wallace Lab main website

This repository encodes the [lab website](https://ewallace.github.io/) with github pages / jekyll.

##


### TODOS

- See links (funders/collaborators) from home page, not just "About"
- Add funder logos on main page
- Make protocols point to the github protocols repository?

Also see Issues on [the github page](https://github.com/ewallace/ewallace.github.io).

## How to add content

1. Fork the repository to your own github account using the "fork" button on [the site](https://github.com/ewallace/ewallace.github.io). If you previously created a fork, be sure to synchronize your fork with the main repository first. Instructions at  [How To Ensure Your GitHub Fork Is Up To Date](https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/github-collaboration/update-github-repositories-with-changes-by-others/) explain how to do that from the command line or the github website.
2. Clone your fork to your local computer (`git clone`)
3. Create a new feature branch (`git branch feature-name`) and check it out (`git checkout feature-name`)
4. Make your edits in a new feature branch, for example
  - add image files, for example add a profile picture at `assets/images/team/vladimir-sanchez-2019-pic.jpg`
  - edit an existing page, for example change the image location in `team/_posts/2019-01-01-vladimir-sanchez.md'
  - create a new page, for example copy `news/_posts/2018-10-01-welcome-sam.md` to a new file `news/_posts/2019-01-01-welcome-vlad.md` and then edit.
5. Commit your changes
  - first add them, e.g. `git add assets/images/team/vladimir-sanchez-2019-pic.jpg`
  - commit with an informative message, e.g. `git commit -m "new vladimir sanchez picture"`
6. If possible, preview the website locally using `bundle exec jekyll serve` to create it, and then browse to [http://127.0.0.1:4000/](http://127.0.0.1:4000/)
  - [install jekyll first](https://jekyllrb.com/docs/installation/)
  - fix any errors or broken links and commit fixes.
7. Push changes to your fork with `git push feature-name`.
8. Make a [pull request](https://help.github.com/en/articles/about-pull-requests) into the `master` branch. Edward, will review the pull request and incorporate it into the website.

Most of these steps can also be done via the website of your github fork, avoiding the command-line clone and push steps. I don't know how to preview the website edits this way, though.

### News

## Updating the public site

All edits should be made in a branch and then pull-request to the `master` branch.

*Previously we tried to keep a separate `staging` branch, but that proved unworkable so we basically just use `master` now.*


## License

[MIT](http://opensource.org/licenses/MIT)
