# Historical PBs Demo Archive

Personal best demo archive for historical personal best records.

## Statistics

| Metric | Value |
| :-- | --: |
| Maps | 135 |
| Archived PBs | 728 |
| Latest Update | 2026-07-19 |

## Structure

| Path | Contents |
| :-- | :-- |
| `manifest.json` | Repository summary and per-map manifest pointers |
| `maps/<map>/manifest.json` | Runs archived for one map |
| `maps/<map>/*.zip` | Demo archive files |

## Access

Use `manifest.json` as the entry point. Each map manifest contains archive filenames and byte ranges for files inside each zip.
