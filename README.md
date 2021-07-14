# University of Washington Macroeconomics Review Sheet for Core Exams

___

[![Build Status](https://travis-ci.com/lukas-hager/Macro-Review-Sheet.svg?branch=main)](https://travis-ci.com/lukas-hager/Macro-Review-Sheet)

This is a LaTeX file that is converted to the file `main.pdf` under [Releases](https://github.com/lukas-hager/Macro-Review-Sheet/releases) whenever I remember to tag commits. The file is hosted on Overleaf, cloned to a GitHub repository, and compiled by Travis. To mirror this approach, I recommend using [this Stack Overflow answer](https://tex.stackexchange.com/questions/398830/how-to-build-my-latex-automatically-using-travis-ci) and [this GitHub](https://github.com/PHPirates/travis-ci-latex-pdf). The only edit: instead of installing `travis` using Gem, I recommend using Homebrew, since Gem didn't really work for me:

```bash
brew install travis
```

Further, within `travis`, I think most commands should be run (if you're connecting with GitHub) using the `--com` flag, meaning that to set up a GitHub API token, you should run

```bash
travis login --com --github-token mytoken
```

instead of the recommended

```bash
travis login --pro --github-token mytoken
```
