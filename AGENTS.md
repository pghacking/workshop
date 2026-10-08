# Agent instructions

This repo lists PostgreSQL Hacking Workshop sessions. Each session is a GitHub issue, and `README.md` links to those issues under **Previous workshops**.

## When the user gives you a video

Do these steps in order.

### 1. Create the issue

Open an issue in `pghacking/workshop` for that video.

- **Title:** the talk title.
- **Label:** `scheduled`.
- **Body:**

```markdown
## Workshop Title

Speaker at Conference Talk Title

Time: Month Year

## Resources

- **Video**: https://...
```

Take the speaker, conference, and title from the video or from what the user already told you. Use the workshop month the user gives. If they do not give one, use the month after the latest workshop in the README. `scheduled` means the workshop has not happened yet.

Add **Slides** or **Related Discussion** under **Resources** only when the user supplies those links.

```bash
gh issue create --repo pghacking/workshop --title "<talk title>" --label scheduled --body "<body>"
```

### 2. Update the README

Add the new workshop under **Previous workshops**, in the matching year, newest first:

```markdown
    - [Talk Title - Month](https://github.com/pghacking/workshop/issues/N)
```

Use the issue title as the link text, then the month. Spell the month in full (`October`, not `Oct`). If the issue time spans two months, keep both (`June/July`). Link to the issue created in step 1.

Leave existing skip notes in place. A skipped month looks like this:

```markdown
    - *no hacking workshop in May due to [2026.pgconf.dev](https://2026.pgconf.dev/)*
```

### 3. Archive workshops that have already finished

After the new issue exists, update every older workshop issue whose month is already over:

- Add the `archived` label.
- Remove the `scheduled` label.

A workshop is finished when its month (or the end of a range such as `June/July`) is before the current month. Leave the issue open. Do not archive the issue you just created, and do not change issues that are already `archived` and have no `scheduled` label.

```bash
gh issue edit <number> --repo pghacking/workshop --add-label archived --remove-label scheduled
```
