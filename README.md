# Stop Referrer Spam
Tools and steps to stop referrer spam in your analytics brought to you by [42rev.com]

## Steps To Success

1. Block Referrer Traffic
    * Copy and paste the htaccess file contents into your site .htaccess file.
2. Filter Out Spam in Google Analytics
    * Create filters for your Google Analytics view using google-analytics-filter.txt.
    * Example screenshot: ![Google Analytics Filter Screenshot](/readme/google-analytics-filter-screenshot.jpg?raw=true "Google Analytics Filter Screenshot")

* GA filter patterns are limited to 255 characters so you may need to create multiple.
* Filters are destructive. Filtering your incoming hits permanently changes those hits in that view, according to the type of filter. Therefore, you should ALWAYS maintain an unfiltered view of your data. https://support.google.com/analytics/answer/1033162?hl=en
* Filters require up to 24 hours before they are applied to your data. https://support.google.com/analytics/answer/1033162?hl=en


### Resources / Inspiration

* https://github.com/piwik/referrer-spam-blacklist domain list of known spammers
* http://blog.raventools.com/stop-referrer-spam/ inspiration
* https://moz.com/blog/how-to-stop-spam-bots-from-ruining-your-analytics-referral-data inspiration


[42rev.com]:https://www.42rev.com
