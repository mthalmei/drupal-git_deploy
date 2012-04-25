The git_deploy module requires the git command to be executable by the
webserver.

An alternative to using git_deploy is to install modules and themes
using the "drush pm-download" command with options
"--package-handler=git_drupalorg --gitinfofile". This performs a
git clone and checkout and then inserts the desired version
information into the .info file.
