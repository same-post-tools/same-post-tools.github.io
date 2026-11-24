# SAME Post Tools

Free browser tools for SAME Post leaders and members. Live at **https://same-post-tools.github.io/**.

Volunteer-built; not an official SAME National site.

## Your files stay on your computer

Every tool runs entirely in the web browser. Files you open in a tool are read and processed on your own device and are never uploaded, sent, or stored anywhere else. There is no server, account, sign-in, analytics, or tracking.

Each page carries a Content Security Policy that blocks outside connections. The one exception is the events finder, which may read its own weekly event list (`events/data.json`) from this site so that saved copies stay current; it sends nothing.

## Tools

| Tool | Address | Status |
|---|---|---|
| SAME Events Near You | [/events/](https://same-post-tools.github.io/events/) | Available |
| Word to web page | | Coming |
| Newsletter block builder | | Coming |
| StarChapter attendance report | | Coming |
| PDH certificates | | Coming |

## What is here

- `index.html`: the home page.
- `events/index.html`: the events finder. One self-contained file; it also works when saved and opened offline.
- `events/data.json`: the current event list, updated weekly. Event facts and links come from public listings and from the Industry Days list Bobbi Jo Lang compiles by hand each week.
- `licenses/`: license texts for the third-party parts shipped inside the pages.
- `THIRD-PARTY-NOTICES.md`: what those parts are.

These files are built and published from a private working repository. Changes made directly here may be overwritten.

## License

The code in this repository is shared under the MIT License (`LICENSE`). The license covers the code only. It does not cover the event information in `events/data.json`, which is gathered from public listings and from the Industry Days list, or the SAME name and colors, which belong to the Society of American Military Engineers. No SAME logo is used. Third-party parts keep their own licenses (see `THIRD-PARTY-NOTICES.md`).

## Credits

SAME Post Tools grew out of the Industry Days list that Bobbi Jo Lang builds by hand, on her own time, every week, so Posts can plan their events around each other and members can plan their attendance. Her list is the foundation of this site.

The tools grew from an idea of Scott DeGaro's: group events that fall in the same week and region into one trip, first tried as a Gulf Coast trip in December 2026. Scott, a member of the SAME Membership Community of Interest, built them with the help of AI tools.

## Contact

same.post.tools (at) gmail.com
