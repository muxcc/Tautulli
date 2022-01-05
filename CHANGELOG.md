# Changelog

## v2.8.1 (2022-01-04)

* API:
  * New: Added grouping and query_days parameters to the get_item_watch_time_stats API command.
  * New: Added grouping parameter to the get_item_user_stats API command.
  * New: Added total_time to the get_library_user_stats, get_user_player_stats, and get_item_user_stats API command responses.
  * Removed: media_type parameter no longer required for the get_item_watch_time_stats, and get_item_user_stats API commands. The media type is determined automatically.
* Other:
  * Fix: Clean .pyc files automatically after updating.
  * New: Allow Snap package to access /media and /mnt locations. Refer to the FAQ for instructions on how to enable access.

