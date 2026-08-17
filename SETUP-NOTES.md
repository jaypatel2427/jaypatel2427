# Setup Notes (read this first, then you can delete this file)

Three things to do before this looks "live":

1. **Replace every `YOUR_USERNAME`** in `README.md` with your actual GitHub username.
   (Used in the stats widgets, the snake game link, and the profile-views counter.)

2. **Edit the `whoami` block** near the top of `README.md` with your real name/role/focus.

3. **Repo name must match your username exactly.**
   GitHub only turns a README into your profile page if the repo is named
   the same as your account, e.g. if your username is `abc123`, the repo
   must be named `abc123` (case-insensitive) and be **public**.

4. **The Snake game** needs one run of the Action before it shows up:
   push this repo → go to the "Actions" tab → run "Generate Snake Game
   From Contributions" manually once (or wait for the daily schedule) →
   it creates an `output` branch with the generated graphic, which is
   what the README links to.

Everything else (banners, dividers, skull, matrix rain, typing bio) is a
self-contained SVG in `assets/` — no external dependencies, so it'll
always render even if third-party badge services ever go down.
