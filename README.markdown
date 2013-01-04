#Ghost

Octopress theme that replaces solarized colors with a github-flavored color scheme.  Also takes some cues from [cparedes/octopress](https://github.com/cparedes/octopress.git).

The `sass/custom` entries have been removed so (re)installing the theme does not clobber them (my customizations live with my blog, not my theme). To make this work, you should have a `sass/custom/_before.scss` and `sass/custom/_after.scss` in your blog which are imported before and after (respectively) the base and partials from the theme.


##Install

Type the code below in terminal.

     $ cd octopress
     $ git clone git://github.com/michael-groble/octopress-theme-ghost.git .themes/ghost
     $ rake install[ghost]
     $ rake generate

