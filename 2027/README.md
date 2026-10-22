# Jaffery Calendar 2027 assets

Each month has a `.jpg` calendar page and a `.json` event file.

JSON schema follows the 2026 assets:
- root: `month` (string), `events` (array)
- event: `date` (integer), `title` (string), `category` (string), `icon` (string)
- icon/category conventions reused from 2026: `wiladat` / 🎉, `shahadat` / ⚫, `historical` / 📜, `occasion` / 🕌

Validation performed: all 12 JSON files parse; required keys and value types are checked; dates are within each month's valid day range.

IMPORTANT: The 2027 PDF is a raster calendar. Event descriptions were transcribed from the page images and are not guaranteed to be exhaustive or fully accurate. Please review event names/dates against the original calendar before publishing. The JSON structure is schema-compatible, but content validation against your app's full expected semantics requires testing in the app.
