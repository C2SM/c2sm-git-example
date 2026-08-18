# Contributing

This repository is course material, so contributions are welcome by definition. It also follows
the same conventions as real C2SM repositories, which is the point of practising here.

## The workflow

1. **Open an issue first.** Describe what is wrong or missing before writing anything. It gives
   other people the chance to say "we already have that" or "do it this other way" before you
   spend time on it. Use one of the [issue templates](.github/ISSUE_TEMPLATE).

2. **Fork this repository** and clone your fork:

   ```bash
   git clone git@github.com:<your-username>/c2sm-git-example.git
   cd c2sm-git-example
   ```

3. **Add the original as `upstream`** so you can keep your fork current:

   ```bash
   git remote add upstream git@github.com:C2SM/c2sm-git-example.git
   ```

4. **Create a branch.** Never work on `main`:

   ```bash
   git switch -c add-my-page
   ```

5. **Make your change and commit it.** One logical change per commit.

6. **Push and open a pull request** against `main` of `C2SM/c2sm-git-example`. Reference the
   issue in the description with `Fixes #12` so it closes automatically on merge.

7. **Wait for the checks**, then request a review.

## Keeping your fork up to date

```bash
git fetch upstream
git switch main
git merge upstream/main
git push origin main
```

## Commit messages

Write a short summary line in the imperative mood, as if completing the sentence
"this commit will ...":

```
Add Anna to the participants list
Fix the broken link in models.md
```

If more explanation is needed, leave a blank line and write a paragraph below. Say **why**, not
what — the diff already shows what.

## What gets checked automatically

Every pull request runs [checks.yml](.github/workflows/checks.yml), which verifies that:

- every Markdown link resolves;
- no file has trailing whitespace;
- every file ends with a newline.

If a check fails, click through to the log to see which file and line caused it, fix it, and push
again. The pull request updates itself.

## Review

Reviews are about the change, not the person. As a reviewer, prefer questions to instructions,
and use GitHub's **suggestion** feature for anything you could simply write yourself. As an
author, reply to every comment, even if only to say you have done it.
