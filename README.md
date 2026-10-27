# Olayiwola's XP portfolio

Buildless HTML, CSS and JavaScript. Site files are in `dist/`.

Run locally from this directory:

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

Open http://127.0.0.1:4173/ in your browser.

Includes independent draggable/resizable windows, maximize/minimize/close, taskbar restoration, Start menu, project case studies, galleries, picture viewer with previous/next and arrow-key navigation, about/experience, skills, downloadable PDF résumé, email contact, and an empty Recycle Bin ready for abandoned projects. Small screens use compact windows.

Assets include the supplied XP wallpaper, Hoppaz screenshots, masked Adtivity derivatives, and OxygenX public-site screenshots. Only masked Adtivity images are included. OxygenX screenshots are labeled company context rather than evidence of authorship of that public website. Raw screenshot images are framed with browser chrome visually cropped using CSS; their image files retain the source chrome.

Validation: JavaScript syntax check passed; local HTTP response passed; project opening, screenshot tabs, picture viewer, image navigation, and taskbar behavior checked in the in-app browser. Desktop and phone viewport layouts inspected with the browser; one phone screenshot capture failed. No external email was sent. Contact copy-to-clipboard depends on browser permissions and displays a fallback when unavailable.

Publication is incomplete: automatic approval review rejected the required Sites source-helper input step twice with “approval required by policy,” including after additional Git-directory and network permission was granted. No source push or private deployment is claimed. The existing registered Site ID is preserved in `.openai/hosting.json`; reuse it on a later publication attempt.

Content remaining: GitHub/LinkedIn links, abandoned projects, and fuller Bankit details have not been supplied. The Adtivity images are AI-edited redacted derivatives, labeled accordingly. The public email is taken verbatim from the supplied CV.
