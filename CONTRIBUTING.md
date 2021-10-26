# Contributing

> **Note:** In this document we define the contribution process for the Flux project and community. These guidelines apply to all git repositories in the `fluxcd` GitHub org.

Flux is [Apache 2.0 licensed](https://github.com/fluxcd/flux2/blob/main/LICENSE) and
accepts contributions via GitHub pull requests. This document outlines
some of the conventions on to make it easier to get your contribution
accepted.

We gratefully welcome improvements to issues and documentation as well as to
code.

## Welcome

We gratefully welcome all kinds of contributions, including code, issues, documentation, external tools, advocacy and community work. All members of the Flux community, including contributors, are expected to uphold the Flux community [Values](https://github.com/fluxcd/community/blob/main/GOVERNANCE.md#values) and [Code of Conduct](https://github.com/fluxcd/community/blob/main/GOVERNANCE.md#code-of-conduct).

## Communications

For realtime communications we use Slack: To join the conversation, simply
join the [CNCF](https://slack.cncf.io/) Slack workspace and use the
[#flux-contributors](https://cloud-native.slack.com/messages/flux-contributors/) channel.

To discuss ideas and specifications we use [Github
Discussions](https://github.com/fluxcd/flux2/discussions).

For announcements we use a mailing list as well. Simply subscribe to
[flux-dev on cncf.io](https://lists.cncf.io/g/cncf-flux-dev)
to join the conversation (there you can also add calendar invites
to your Google calendar for our [Flux
meeting](https://docs.google.com/document/d/1l_M0om0qUEN_NNiGgpqJ2tvsF2iioHkaARDeh6b70B0/view)).

## Semantic Versioning

The Flux project and community git repositories maintain a strong commitment to clear communication about backwards compatibility. For this reason, all code contributions must follow the Semantic Versioning 2.0.0 Specification (SemVer) per <https://semver.org/>, so that users can trust compatibility based on version scheme.

## Acceptance policy

These things will make a PR more likely to be accepted:

- a well-described requirement
- tests for new code
- tests for old code!
- new code and tests follow the conventions in old code and tests
- a good commit message (see below)
- all code must abide [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
- names should abide [What's in a name](https://talks.golang.org/2014/names.slide#1)
- code must build on both Linux and Darwin, via plain `go build`
- code should have appropriate test coverage and tests should be written
  to work with `go test`

In general, we will merge a PR once one maintainer has endorsed it.
For substantial changes, more people may become involved, and you might
get asked to resubmit the PR or divide the changes into more than one PR.

### Certificate of Origin

By contributing to this project you agree to the Developer Certificate of
Origin (DCO). This document was created by the Linux Kernel community and is a
simple statement that you, as a contributor, have the legal right to make the
contribution.

We require all commits to be signed. By signing off with your signature, you
certify that you wrote the patch or otherwise have the right to contribute the
material by the rules of the [DCO](https://github.com/fluxcd/community/blob/main/DCO):

`Signed-off-by: Jane Doe <jane.doe@example.com>`

The signature must contain your real name
(sorry, no pseudonyms or anonymous contributions)
If your `user.name` and `user.email` are configured in your Git config,
you can sign your commit automatically with `git commit -s`.

This is automatically checked by the [Probot](https://github.com/probot/dco/): DCO integration across all `fluxcd` GitHub org repositories.

Commit signoff is a simple statement that you, as a contributor, have the legal right to make the contribution. See `git help commit`:

> The meaning of a signoff depends on the project, but it typically certifies that committer has the rights to submit this work under the same license and agrees to a Developer Certificate of Origin (see <http://developercertificate.org/> for more information).

#### CLI

When signing commits with git commit -s, signoff is drawn automatically from your `user.name` and `user.email` git configs. If you choose to manually add a signoff line to your commit message, it must be properly formatted and match your commit information. For example, when using the GitHub [private email option](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address) you must set your git config email accordingly. For those who wish to ensure this is always done in your CLI, consider implementing something like [this gist](https://gist.github.com/scottrigby/0c043c0bfbbdb5949e2d824fc3adeaa4).

#### Browser

For contributions made with the GitHub UI — including [applying suggested changes](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) — the [scottrigby/dco-gh-ui](https://github.com/scottrigby/dco-gh-ui) browser extension is recommended. This pre-fills GitHub's commit textareas with a properly formatted signoff from your configured name and email. Otherwise, you will need to be sure to do so manually.

### Format of the Commit Message

For the GitOps Toolkit controllers we prefer the following rules for good commit messages:

- Limit the subject to 50 characters and write as the continuation
  of the sentence "If applied, this commit will ..."
- Explain what and why in the body, if more than a trivial change;
  wrap it at 72 characters.

The [following article](https://chris.beams.io/posts/git-commit/#seven-rules)
has some more helpful advice on documenting your work.

## Thank You

[Contributors](https://github.com/fluxcd/community/blob/main/GOVERNANCE.md#contributors) are crucial to ensuring the Flux project continues to fairly represent community interests. Thank you for all that you do.
