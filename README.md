# drupal_new_project

    dir /drush dl drupal --drupal-project-rename="www"

# adminimal_theme
    dir /drush dl adminimal_theme
    dir /drush en adminimal_theme --yes

# devel
    dir /composer require drupal/devel
    dir /drush en devel --yes

# page_manager
    dir /composer require drupal/page_manager
    dir /drush en devel --yes

# panels
    dir /composer require drupal/panels
    dir /drush en panels --yes

# twig_tweak
    dir /composer require drupal/twig_tweak
    dir /drush en twig_tweak --yes
