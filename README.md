# norskup-site

The website for NorskUp at [norskup.no](https://norskup.no): the landing page
and the privacy policy, in Norwegian and English.

- `/` and `/en/`: the landing page
- `/personvern/` and `/en/privacy/`: the privacy policy
- `/om/` and `/en/about/`: about NorskUp (who is behind it, contact)

Every page has the same footer: Om NorskUp / About NorskUp, Personvern /
Privacy, and hei@norskup.no. The company details live on the about page and
in the privacy policy's data controller section, not in the footer.

Plain HTML and CSS, served by GitHub Pages from `main` (`CNAME`: norskup.no).
No framework, no build step, no JavaScript, no tracking, no cookies, no
analytics, no external fonts or scripts. The font is Atkinson Hyperlegible
Next (SIL Open Font License, `assets/fonts/`), self-hosted.

The privacy policy describes only what the app does. When the app changes how
it stores or sends anything, update both languages and the date at the top.
