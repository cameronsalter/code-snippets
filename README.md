# code-snippets ReadMe

Quarto website to store reference code while learning R. Might also add some Python code snippets in future.

Published website: https://cameronsalter.github.io/code-snippets/

## Quarto publishing process
The website is published on GitHub Pages and is built on the gh-pages branc using the [Publshing Command](https://quarto.org/docs/publishing/github-pages.html#publish-command) process.

All development is (currently) on main, so always push to main. The gh-pages branch is only used for publishing. 

Command to publish is:
```{sh}
quarto publish gh-pages
```

## Using Quarto
Use a Quarto document (.qmd) for each webpage.