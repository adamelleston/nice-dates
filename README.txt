Nice dates is designed to simply add a Day, Month and Year date format and format type to your Drupal site.

This means that you can easily create URLs such as this in pathauto by using the tokens generated for the date formats.

blog/2012/01/23/page-title

CONFIGURATION STEPS:

1. Visit admin/config/regional/date-time then make sure Day, Month, Year and mapped to use the correct formats and hit save.

2. Visit admin/config/search/path/patterns and change your node patterns to something like this example

blog/[node:created:nice_dates_year]/[node:created:nice_dates_month]/[node:created:nice_dates_day]/[node:title]
