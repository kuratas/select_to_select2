# Select To Select2 Plugin
This is a repository of 「Select To Select2 Plugin」 which is a Redmine plugin.  
This repository is forked from sf-cola/select_to_select2.
I fixed these issue.

- Issue list
  - "Add filter" select box was too small when apply A1 theme.
- Issue list -> Option
  - group select box was too small when apply A1 theme.

## Features

Replace all select tag to select2 in all Redmine's Pages.

![2017-10-09 21 50 40](https://user-images.githubusercontent.com/12267699/31339056-998c52f0-ad3c-11e7-88ea-bc7acf8cdf96.png)

## Installation

1.```git clone https://github.com/kuratas/select_to_select2.git```

2.Copy to ```apps/redmine/htdocs/plugins```

3.```bundle exec rake redmine:plugins:migrate NAME=select_to_select2 RAILS_ENV=production```
