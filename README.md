# Markdown Viewer

A single-page Markdown viewer. Paste the text from any `.md` file into the
top box and see it rendered with nice styling below it. No accounts, no
saving, no storing — everything happens in your browser.

Built to match the look and feel of the
[clipboard-converter](https://github.com/vigrenm-partmaster/clipboard-converter)
page, including the **Win 3.1**, **Crystal White**, and **Crystal Black**
themes.

## How your colleagues use it

1. Open the `.md` file in Notepad (or any text editor)
2. Select all (Ctrl+A) and copy (Ctrl+C)
3. Paste into the input box on the page (Ctrl+V) — it renders automatically
4. Optionally click **Print / Save PDF** for a clean printable copy

## Hosting it on GitHub Pages

1. Push this repository to GitHub (already done if you're reading this there).
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the branch (e.g. `main`) and the `/ (root)` folder, then **Save**.
5. After a minute the page is live at
   `https://<your-username>.github.io/markdown/`.

Share that link with your colleagues — that's all they need.

## Notes

- The page uses [marked](https://github.com/markedjs/marked) to parse Markdown
  and [DOMPurify](https://github.com/cure53/DOMPurify) to sanitize the output,
  both loaded from a CDN — so an internet connection is required.
- Nothing you paste is uploaded or stored anywhere.
