# Google Analytics Bridge #
**Contributors:** danielbachhuber  
**Tags:** google analytics  
**Requires at least:** 4.5  
**Tested up to:** 4.9.8  
**Stable tag:** 0.1.0  
**License:** GPLv2 or later  
**License URI:** https://www.gnu.org/licenses/gpl-2.0.html  

API bridge between WordPress and Google Analytics.

### Set Google Analytics profile ID and client secret

```php
add_filter( 'gab_ga_profile_id', 'MY-PROFILE-IDT' );
add_filter( 'gab_ga_client_secret', 'MY-CLIENT-SECRET' );
```

See https://developers.google.com/analytics/devguides/config/mgmt/v3/authorization
