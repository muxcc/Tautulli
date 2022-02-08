# Changelog

## v2.9.2 (2022-02-08)

* Notification:
  * New: Added support for additional Telegram HTML tags.
  * Removed: Revert Telegram defaulting to MarkdownV2 and only support HTML. (#1635)
* Other:
  * Fix: The Local user being masked in the logs.


## v2.9.1 (2022-02-07)

* Other:
  * Fix: Incorrect changelog version number and date.


## v2.9.0 (2022-02-07)

* Notification:
  * New: Added track disc number notification parameter. 
  * Change: Default Telegram messages to MarkdownV2 when HTML is disabled. (#1635)
* Exporter:
  * Fix: Images not being included in export zip file download.
* UI:
  * Fix: Favicon missing from the newsletter authentication page.
  * Fix: IPv6 details not being shown in IP address modal. (#1629)
  * Fix: PWA not respecting device rotation settings. (#1633)
  * New: Added intermediary login page to the Plex XML shortcuts.
  * New: Added setting to mask usernames in logs (enabled by default).
  * New: Added location, secure connection, and Plex Relay details to IP address modal.
  * Change: Remove Plex token from the settings page.
  * Change: Increase verifying server timeout to 30 seconds.
* API:
  * New: Added get_tautulli_info API command.
  * New: Added location, secure, and relayed to get_history API response.
  * Change: Null pms_token and jwt_token in the response of the get_settings API command. (#1616)
* Other:
  * Fix: Better validation of config when saving settings.
  * Fix: Correct section_id and prevent rating_key collisions when updating metadata. (#1640)
  * Change: Proxy Plex token check and Plex downloads json through the Tautulli server.
  * Change: Remove tokens from downloaded database and config files.
  * Change: Do not import pms_token or jwt_secret when importing a config file.


