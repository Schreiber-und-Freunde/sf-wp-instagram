sf-wp-instagram
============

instagram API Integration for Wordpress

**Notice:** This is no complete API implementation. Only the features we need for www.schreiber-freunde.de are implemented. If you miss a feature feel free to implement it and send a pull request or file a feature request in the issues section.

## Usage
The following wrapper functions are implemented yet:
```
instagram_get_user_media_count($user_id);
```
Returns the media count for the given user.

```
instagram_get_hashtag_media_count($hashtag);
```
Returns the media count for the given hashtag.

* * *
**Be careful and cache the results. This plugin won't do this for you!**
