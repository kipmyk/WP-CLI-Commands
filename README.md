# WP CLI Commands

This is a list of the WP CLI commands. As I test it out, I am updating the lists here.

# WP Core <command>

The [`wp core`](https://developer.wordpress.org/cli/commands/core/) command helps to download, install, update, and manage WordPress installation.

## Delete the core updater lock option

wp option delete core_updater.lock

## Update WordPress to Specific version forcefully

wp core update --version=<version-number> --force

For example : `wp core update --version=6.1.1 --force`, this will update to the WP 6.1.1

## Display the WordPress version

wp core version

## Checks for WordPress updates via Version Check API.

wp core check-update

## Update the WordPress database

wp core update-db

# wp theme <command>

The [`wp theme`](https://developer.wordpress.org/cli/commands/theme/) helps in managing themes, including installs, activations, and updates.

## Update multiple default themes from wordpress.org

wp theme update twentynineteen twentytwenty twentytwentyone twentytwentytwo twentytwentythree

## Delete older default themes

wp theme delete twentysixteen twentyseventeen

## Update all themes

wp theme update --all

## Install the new default theme

wp theme install twentytwentyone
