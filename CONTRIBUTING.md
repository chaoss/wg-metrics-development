# How to Contribute

## What is this document?

This document outlines a generic process of contributing and applies to all CHAOSS repositories. Each repository may have unique guidelines specific to the project.

* Metrics definition. For each metric, we have a document describing it,
all of them in the [metrics directory](metrics).
You can contribute by helping to refine those metrics definitions.

## Where can I contribute?

Anyone can contribute to CHAOSS on any of our communication channels. See <https://chaoss.community/participate/>.

* If you think something should be done (including a contribution by yourself), please open an issue in this repository. That will allow others to learn that you think some work should be done, and can comment on that. If you intend to do the job yourself, please say that.

* Everyone with an opinion on the matter should comment on the issue, explaining how they support the idea, propose some change to it, or think it is not worth / it is not the moment for doing it.

* If comments are positive, and a certain consensus is achieved, propose a pull request with the changes to the repository (new document, changes to existing documents).

* Everyone with an opinion on the pull request should comment on it, and detailed reviews should be done, maybe asking for new versions of the pull request. Once comments and reviews are positive, the change will be merged in the repository.

* If consensus is not reached at any of these points, or the process stalls, it can be raised during one of the Common Working Group meetings, or in the mailing list, to try to unblock it.

## Which channel should I use?
1. The mailing list
2. Issue submission
3. Pull requests

### Conversations and high-level contributions (email, call, f2f)

Strategic directions, clarifications of scope, and ideas in an early stage are best discussed on the mailing list, calls, and face-to-face meetings. See <https://chaoss.community/participate/>.

### Bug report and feature request contributions (issue)

Bug reports and specific feature requests are best discussed in an issue on the repository they pertain to.

### Code or document change contributions (pull request)

Changes to source code files or documents are best contributed and discussed in pull requests. Please look at the CONTRIBUTING.md files for repository specifics.

In this process, make sure your [GitHub account][ssh] is setup [fork][fork] then locally [clone][clone] the repo:

    git clone git@github.com:<your-username>/<repository>.git

Create a [feature branch][fb] in your local repository:

    git checkout -b <branch>

Make your change and commit the change:

    git add <changed file>
    git commit -m "<description of change>"

Push to your fork on GitHub:

    git push origin <branch>

Then, [submit a pull request][pr] on GitHub to the CHAOSS repository.

[ssh]: https://help.github.com/articles/connecting-to-github-with-ssh/
[fork]: https://help.github.com/articles/fork-a-repo/
[fb]: https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow
[pr]: https://github.com/thoughtbot/factory_girl_rails/compare/
[clone]: https://help.github.com/articles/cloning-a-repository/

At this point you are waiting on the CHAOSS repository maintainers. They will comment on your pull requests
within three business days (and, typically, one business day).

The CHAOSS repository maintainers will report on open issues and pull requests on the [calls and via the mail list][participate] to elicit feedback from the community.

[participate]: https://chaoss.community/participate/

## Committing back to the repository
## DCO and Sign-Off for contributions

The [CHAOSS Charter](https://github.com/chaoss/governance/blob/master/project-charter.md) requires that contributions
are accompanied by a [Developer Certificate of Origin](http://developercertificate.org) sign-off.
For ensuring it, a bot checks all incoming commits.

For users of the git command line interface, a sign-off is accomplished with the `-s` as part of the commit command: 

```
git commit -s -m 'This is a commit message'
```

For users of the GitHub interface (using the "edit" button on any file, and producing a commit from it),
a sign-off is accomplished by writing

```
Signed-off-by: Your Name <YourName@example.org>
```

in a single line, into the commit comment field. This can be automated by using a browser plugin like
[DCO GitHub UI](https://github.com/scottrigby/dco-gh-ui).

#### Steps to use the DCO browser plugin
The  [DCO browser plugin](https://github.com/scottrigby/dco-gh-ui) is a handy tool to automatically sign commits created using GitHub. 
To enable this plugin: 

- Go to the plugin page on the [chrome web store](https://chrome.google.com/webstore/detail/dco-github-ui/onhgmjhnaeipfgacbglaphlmllkpoijo).
- Alternatively, you could go to the [firefox addon page](https://addons.mozilla.org/en-US/firefox/addon/scott-rigby/) to add the extension to your browser.
- Once you add the extension, right click on the extension in the toolbar of your browser and select `Options`. 
- A dialog box will open up as shown below. Fill in your GitHub name (not the handle) and email-id. 

 ![Screenshot of settings for DCO GitHub UI](https://user-images.githubusercontent.com/31214064/55411911-194c8500-5584-11e9-8b56-c8f94b6fa213.png)

- Then, whenever you perform a commit on GitHub, the line `Signed-off-by: Your Name <Youremail>` will automatically appear in the commit description while making changes to a file as shown in the example below. A commit message can be added to the lines above the auto-generated sign-off. 

![Screenshot of GitHub UI with auto-generated sign-off in commit message](https://user-images.githubusercontent.com/31214064/55423206-127d3c80-559b-11e9-9a5e-6300105b8858.png)

- Once you perform the commit and send a pull request, the commit will be verified and approved by the DCO bot. 

 ![Screenshot of successful DCO check](https://user-images.githubusercontent.com/31214064/55415829-5f591700-558b-11e9-93ae-07b0ed432a53.png)



## Who is a CHAOSS repository maintainer?

The README.md of the repository contains a list of who is maintainer. Each CHAOSS repository brings together different people and they document in the repository specific CONTRIBUTING.md how somone becomes a maintainer on their repository.

## What about releases?

CHAOSS repository maintainers tag commits on the master branch as [releases][rl] (snapshots). Each CHAOSS repository has its own release cadence. Between releases, the master branch is under development.

[rl]: https://help.github.com/articles/about-releases/
