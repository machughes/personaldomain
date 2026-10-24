# mccaslinhughes.com

Personal site and blog for McCaslin Hughes, built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Changing the bio or LinkedIn link

Edit `_config.yml` and change the `bio:` and `linkedin:` lines.

## Writing a new post

1. Open the `_posts` folder on GitHub and click **Add file → Create new file**.
2. Name it `YEAR-MONTH-DAY-short-title.md`, for example `2026-11-03-my-first-trip.md`.
3. Start the file with a title block, then write the post below it:

   ```markdown
   ---
   title: My First Trip
   ---

   The post text goes here. Leave a blank line between paragraphs.
   ```

4. Click **Commit changes**. The site updates by itself within a minute or two.

## Colors and fonts

The "Harbor slate" theme: sky blue leads, and everything else is a cool slate neutral.
All colors are defined at the top of `assets/css/style.css`, with a matching dark theme just below
that the site switches to when a visitor's device is in dark mode.

- Background `#f6f7f9`, text `#1a2230`, deep sky `#2f5d8a`, sky `#93bee9`
- Headings and small labels: Schibsted Grotesk. Post text: Literata. Both from Google Fonts.
