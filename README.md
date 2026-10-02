# mealauchef-legal

Public hosting for the Meal au Chef app's **Privacy Policy** and **Terms of
Service**, as required by the Apple App Store and Google Play Store.

Served via GitHub Pages at:

- `https://attozoic.github.io/mealauchef-legal/` — landing
- `https://attozoic.github.io/mealauchef-legal/privacy-policy`
- `https://attozoic.github.io/mealauchef-legal/terms-of-service`

## How it works

GitHub Pages auto-builds this repo with Jekyll on every push to `main`.
Jekyll converts the `.md` files to styled HTML using the cayman theme
(configured in `_config.yml`).

## Updating a document

1. Edit `privacy-policy.md` or `terms-of-service.md`
2. Bump the **Effective date** and **Last updated** header lines
3. Commit to `main` → GitHub Pages republishes within ~1 minute
4. The URL stays the same — stores keep working

For material changes (that affect what data is collected, how it's used,
or users' rights), notify existing users in-app or via email at least
14 days before the change takes effect — standard GDPR practice.

## Source of truth

These documents mirror the drafts kept in the Flutter repo under
`meal_au_chef/docs/legal/`. If you want to track their evolution with the
app code, edit there first and copy over. Simpler: edit here directly,
and periodically sync back to the Flutter repo so future developers see
the current content next to the code.
