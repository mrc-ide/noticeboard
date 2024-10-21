# Introduction to orderly2

*24 October 2024, Rich FitzJohn*

A gentle introduction to [orderly2](https://mrc-ide.github.io/orderly2), explaining the key concepts and working towards efficiently collaborating on a shared piece of analysis.  This is the first time we have taught the new version, so come along and help us work out how to explain it!

Email as sent with instructions and context below:

---

Hi all,

Next Thursday, the 24th of October we are running an "Introduction to orderly2" session as part of the IDE training series.  This is the first time we have tried teaching the new version, so this session will be useful for us to find and iron out bugs and weirdnesses, as well as hopefully useful to people who want to learn about the package.

No prior experience with orderly1 is needed, and indeed those **without** prior experience may find it easier!  We will cover what orderly tries to do (and tries not to do) and focus on patterns of collaborative work within an ongoing research project (e.g, outbreaks, or regular reporting to stakeholders).

The session will be run using the R version of orderly, so bring a laptop and please ensure that you have a **recent version of R** 4.4.x ideally, but 4.3.x should work too.  If you use RStudio, consider updating that too as we see some very old versions in use.

We do have a Python version of the package and adventurous users might want to try that out.  This may or may not be possible, but let me know if you are interested in trying (please, only if you a *already* a proficient Python user, while we work out how this will work).

You can install orderly2 by running

```
install.packages(
  "orderly2",
  repos = c("https://mrc-ide.r-universe.dev", "https://cloud.r-project.org"))
```

However, we may well do this at the first bit of the workshop too if we make changes in the week beforehand.  The current version is `1.99.43` and you can find out what you have installed by running `packageVersion("orderly2")`.  It's a good idea to install now anyway as that will mean you know you have all the dependencies and your computer can run orderly.

We will probably be using a little git and GitHub during the session, so consider checking/updating your git installation (https://github.com/richfitz/git-intro/blob/master/installation.md), making sure you know your GitHub username and can log into GitHub, and are part of the `mrc-ide` organisation (check here: https://github.com/settings/organizations and email/message me with your GitHub username if you are not in the org).

Cheers,
Rich, Wes and Katy

---

[Back](..) to list of sessions
