# Void Rush changelog

The Void Rush player changelog, published here for the website. It's updated from the game's
`VRPublicChangelog.md` by `tools/publish_changelog.py`; don't edit these files by hand.

| File | Contents |
|---|---|
| `CHANGELOG.md` | The full changelog, newest version first |
| `changelog.json` | Every version, parsed: `{"latest": "5.33", "versions": [...]}` |
| `latest.json` | Only the newest version |

Raw URLs (no login needed):

- https://raw.githubusercontent.com/Whyismy/voidrush-changelog/main/changelog.json
- https://raw.githubusercontent.com/Whyismy/voidrush-changelog/main/latest.json
- https://raw.githubusercontent.com/Whyismy/voidrush-changelog/main/CHANGELOG.md

## JSON shape

```json
{
  "version": "5.33",
  "date": "2026-10-30",
  "markdown": "* **New class: Priest**\n    * ...",
  "sections": [
    {
      "title": null,
      "entries": [
        { "text": "**New class: Priest**", "children": [ { "text": "...", "children": [] } ] }
      ]
    }
  ]
}
```

- `markdown` is that version's raw body, so the site can render it with any Markdown library.
- `sections` is the same content as a tree. `title` is `null` for the main list; a few old
  versions also have named sections (`### Graves`, ...). `text` is inline Markdown (`**bold**`,
  `` `code` ``) and can hold a table.
- Versions are newest first.
