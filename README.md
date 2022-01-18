# MoonLink-Release
MoonLink release repo.

## Release steps 

Refer the guide of [Creating a release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository#creating-a-release) of GitHub docs to create a release.

:rotating_light: **Please attention:**

Each time before you create a release, respect the following steps:
- create a empty commit with release message 

  ```
  # release 1.0.0 version: empty commit with release messege
  git commit --allow-empty -m 'release 1.0.0' 
  ```
- create a tag based on the empty release commit, such as `v1.0.0`

- create a release based on this tag with notes and deliveries (installer packages)


## An example of the release notes

> # 🚀 Features
> - Improved UX!
>
> # 🐛 Fixes
> - Fixed translation bugs and improved experience

