# Rebuild app/etc/config.php Automatically in Magento 2
Allows you to rebuild the app/etc/config.php based on currently installed modules and packages.

## Install via Composer
`composer require fishpig/magento2-app-etc-config-builder`

## Create app/etc/config.php (Dry run)
`vendor/bin/app_etc_config_builder`

## Create app/etc/config.php & update file
`vendor/bin/app_etc_config_builder --write`

## Create symlink in bin
`ln -s vendor/bin/app_etc_config_builder bin/app_etc_config_builder`
