# kalimat-site

Public site for **كلمات متقاطعة (Kalimat)**, the Arabic crossword app: landing page, support
page and privacy policy, bilingual Arabic/English, served by GitHub Pages.

    Landing  https://smdash.github.io/kalimat-site/
    Support  https://smdash.github.io/kalimat-site/support.html
    Privacy  https://smdash.github.io/kalimat-site/privacy.html

## The privacy policy is not boilerplate

Written against the app's actual behaviour as of 2026-11-15. Apple cross-checks it against the
App Store privacy label; if either changes, both change in the same commit as the app. The app:

- stores puzzle progress, daily streak and settings on device only (no server, no account,
  no iCloud sync);
- has no analytics SDK;
- shows AdMob ads (home banner, interstitial after a completed puzzle, optional rewarded ad
  for hints) with UMP consent in EEA/UK/CH and ATT. Tracking is YES on the privacy label;
- sells a one-time Remove Ads non-consumable through Apple (Family Sharing on).

## app-ads.txt does NOT live here

Google reads it from the domain root, served by the `smdash.github.io` user-page repo, which
already carries the account's AdMob publisher line. Nothing to add per app.
