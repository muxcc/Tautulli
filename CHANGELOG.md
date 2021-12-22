# Changelog

## v2.8.0 (2021-12-15)

* History:
  * Fix: Live TV history filter not working correctly when combined with other filters.
  * Fix: Direct Stream history filter not remembering the state when reloading the page.
  * Fix: History table not loading when no filters are selected.
  * New: Added watch time and user stats to media info pages. (Thanks @herby2212) (#1417, #1471)
* Notifications:
  * New: Added Microsoft Teams notification agent. (#1514)
  * New: Added Gotify notification agent. (#1584)
  * New: Add warning message that passwords are not copied when duplicating a notification or newsletter agent. (#1540)
* Newsletters:
  * Fix: Different album types not shown on newsletter. (#1559)
* Exporter:
  * New: Added album formats, subformats, and sonic analysis export fields.
* UI:
  * Fix: Docker config volume message overlapping modal windows. (#1567)
  * Fix: Different album types not shown on artist media info page.
  * New: Added show more/less toggle for summaries on media info pages. (#1546)
  * Change: Do not save datatable page or search states when reloading the page. (#1532)
  * Change: Improve the Plex log reader.
* API:
  * New: Added before and after parameters to the get_history API command.
* Other:
  * Fix: Updated Python dependencies. (#1499)
  * Fix: Some websocket connections not respecting the verify SSL setting. (Thanks @nmaggioni) (#1541)
  * New: Support for Python 3.10. (#1522)
  * New: Added dynamic anonymous redirect service setting. (#1526)
