# ChangeLog

## Version 0.8.3

- Closes issue #23 related to 301 redirects when scheme and host is not present.

## Version 0.8

- Added [andreskrey/readability.php](https://github.com/andreskrey/readability.php) library as the default method of article parsing, using prior methods as a backup.
  - This closes multiple issues related to article reading including #6, #7, #8, #17, #18
- Changed the call to parse a URL from `getArticleText to `processURL`
- Added README.md
- Upgraded to PHPUnit 6.x for testing


## Version 0.7

- Started CHANGELOG
- Moved PHP DOM Parser dependency to [thesoftwarefanatics/php-html-parser](https://github.com/thesoftwarefanatics/php-html-parser) for support of PHP 7.2+
