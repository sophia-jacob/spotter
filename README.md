## file arch for now

```text
index.html             Homepage and local resource finder
how-you-can-help.html  Community support page
meet-the-team.html     Team page
```

each page currently has its own css styles which is a little inconsistent, ill probably refactor that in the future

## commit guidelines

each commit should generally be focused on one change, no 10k line pushes please

### commit titles

use a lowercase prefix with a description on the commit:
```text
type: description
```

start w/ action such as "add", "fix", "remove", "chore", don't end titles with periods

prefixes could be something like:

- `feat:` — add a feature or capability.
- `fix:` — correct broken behavior.
- `refactor:` — reorganize code without changing behavior.
- `style:` — change visual styling or presentation.
- `docs:` — update documentation.
- `perf:` — improve performance.

example pushes could be for instance:

```text
feat: add nearby shelter search
fix: correct resource finder link on team page
refactor: extract shared styles into a stylesheet
style: improve navigation spacing on mobile
docs: document file organization guidelines
perf: reduce image sizes on team page
```

for larger commits (if you have to), please leave a blank line after the title + add a short body explaining what changed, why, and verification methods

```text
fix: correct resource finder link on team page

points the navigation link to the homepage resource finder
the previous link targeted a section missing from the team page

verified navigation between all three pages
```
