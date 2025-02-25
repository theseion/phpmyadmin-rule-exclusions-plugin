# OWASP ModSecurity Core Rule Set - phpMyAdmin Rule Exclusions Plugin

## Description

This plugin contains rule exclusions for [phpMyAdmin](https://www.phpmyadmin.net/),
a tool intended to handle the administration of MySQL over the Web, so it can be
run flawlessly togather with OWASP ModSecurity Core Rule Set (CRS).

## Installation

For full and up to date instructions for the different available plugin
installation methods, refer to [How to Install a Plugin](https://coreruleset.org/docs/configuring/plugins/#how-to-install-a-plugin)
in the official CRS documentation.

## Testing

After the plugin is enabled, your phpMyAdmin instance should work without any
problems possibly caused by CRS (for example, false positives while blocking
requests). If you are still having any problems, please file a new issue on
[github](https://github.com/coreruleset/phpmyadmin-rule-exclusions-plugin).

## License

Copyright (c) 2022 OWASP ModSecurity Core Rule Set project. All rights reserved.

The OWASP ModSecurity Core Rule Set and its official plugins are distributed
under Apache Software License (ASL) version 2. Please see the enclosed LICENSE
file for full details.
