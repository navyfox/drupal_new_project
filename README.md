# drupal_new_project

drush dl drupal --drupal-project-rename="www"

# adminimal_theme
drush dl adminimal_theme

drush en adminimal_theme --yes

# devel
composer require drupal/devel

drush en devel --yes

# page_manager
composer require drupal/page_manager

drush en devel --yes

# panels
composer require drupal/panels

drush en panels --yes

# twig_tweak
composer require drupal/twig_tweak

drush en twig_tweak --yes
