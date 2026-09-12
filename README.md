# Road to Cologne — how to put it online

## 1. Put your files in this folder

Next to `index.html`, drop:

| File | What it does |
|---|---|
| `song.mp3` | plays for 25 seconds when the page opens |
| `cover.jpg` | the big photo on the welcome screen |
| `docs.jpg` | behind "Papers, money & visa" |
| `uni.jpg` | behind "University sign-up" |
| `home.jpg` | behind "Finding a home" |
| `fly.jpg` | behind "Flight week" |
| `land.jpg` | behind "First weeks in Germany" |

All of them are optional. Anything missing just leaves the colour gradient in place,
and a missing `song.mp3` means no music. Names must match exactly, lowercase.

## 2. Put the folder online

Go to **app.netlify.com/drop** and drag this whole folder onto the page.
No account needed to start. You get a link like `https://something-random.netlify.app`.
Netlify will offer to rename it to something nicer, e.g. `rona-parsa.netlify.app`.

GitHub Pages works too if you prefer: put the folder in a repo, then
Settings → Pages → Deploy from branch → main.

## 3. Turn on sharing

Open the link, and at the top press **Share with Parsa**. The address gains a `#room=…`
at the end. Send Parsa *that exact link*, including everything after the `#`.
From then on you both read and write the same list, and ticks appear on both sides
within about fifteen seconds.

If you skip this step the list still works, but it only lives in your own browser.

## 4. Choose where the song starts

On the welcome screen press **Set the song start**, slide to the part you like,
press **Hear it** to check, then **Keep this**. The choice is shared with Parsa too.

## Notes

- Browsers refuse to play sound before you touch the screen. If that happens the ♪
  button at the top blinks, and the first tap starts the song.
- The ticks are stored at jsonblob.com, a free service that needs no account. Anyone
  holding your link can see and edit the list, so treat it as unlisted rather than private.
- To change the tasks permanently, edit the `SECTIONS` block near the top of the
  `<script>` in `index.html`. Everyday edits are easier done in the page itself.
