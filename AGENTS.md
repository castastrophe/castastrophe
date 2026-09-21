# castastrophe/castastrophe

The GitHub profile README — the page shown at github.com/castastrophe. There is no
build, no package, and no tests. `README.md` is the entire deliverable.

## Do not edit the activity section

Everything between `<!--START_SECTION:activity-->` and `<!--END_SECTION:activity-->`
is regenerated every 30 minutes by
[`.github/workflows/update-readme.yml`](.github/workflows/update-readme.yml), which
runs `jamesgeorge007/github-activity-readme`. Hand edits there are overwritten within
the half hour, and a commit that touches them just adds noise to the history.

Everything outside those markers is hand-written and safe to edit.

## Voice

This is the personal profile, not studio copy — first person ("I", "me") is correct
here. The pronoun-free voice in
[`allonsy-studio/.github`](https://github.com/allonsy-studio/.github) applies to
client-facing studio material, not to this page. Don't "fix" one to match the other.

Chicago Manual of Style otherwise, with the studio's exceptions: sentence-case
headings, `&` over "and", numerals over spelled-out numbers, en dashes in ranges.

## Conventions

- Badges and the funding block are raw HTML on purpose — GitHub's profile renderer
  needs the alignment attributes that markdown can't express. Leave them as HTML.
- Renovate keeps the workflow's action versions current; don't pin them by hand.

Never add AI attribution to a commit or a PR: no `Co-Authored-By` trailer, no
"Generated with …" footer, no session URLs.
