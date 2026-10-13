# Changelog

## 1.14.2 - 2026-10-13

- The Wi-Fi signal is now optional and off by default (Settings, Measurements). Windows 11 counts every reading of the
  Wi-Fi connection as a use of the location, because the answer also holds the network name and the access point
  address, and kept showing "location used by PC Monitor". PC Monitor never read or stored your location; with the
  option off it does not ask the Wi-Fi service at all. Traffic, ping and lost pings are measured as before.

## 1.14.1 - 2026-10-10

- The values of the tiles always fit in their tiles: all seven tiles in one row from a 1450 px wide window (4 + 3
  below), the forecast shows its change in brackets, the idle row its time (its cost is in the tip of the tile).
- The values next to the cursor on the other charts stay inside their charts, long lines wrap.
- Ranges longer than two months show months in the chart heads, so the titles of narrow cards are not cut.
- A hint no longer appears after the mouse has moved on, and no hint covers the tooltip of a chart.
- After a quick change of the period (or a note added just before it) the dashboard always shows the latest period.
- New screenshots.

## 1.14.0 - 2026-10-10

The first public release.

- Freeware licence (shown by the installer), the licences of the bundled components in the program folder.
- The year range of a narrow chart card shows readable dates.
- The costs in the energy table are right from the first moment the dashboard opens.
- Everything recorded and shown so far: CPU, GPU, memory, disk, network and battery readings every 2 seconds; power
  from the wall with its cost and a monthly forecast; charts from five minutes to a year with the previous period for
  comparison; energy per program, GPU sessions, uptime and history; notes on the charts; notifications, a weekly
  summary, backups and CSV export; battery wear and NVMe drive health; draggable, resizable and hideable cards with
  separate layouts for the compact and the normal view; English and Polish, light and dark themes.
