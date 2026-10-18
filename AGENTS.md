# Repository Guidelines

## Project Structure & Module Organization

This is the `wnghks7787` GitHub profile repository. Its root `README.md` is the profile page and contains links, language badges, career history, education, awards, papers, and experiences. Badge and destination URLs are defined as Markdown references near the bottom of the file. `.gitignore` contains local-file exclusions. There are currently no application source directories, tests, or local assets.

## Build, Test, and Development Commands

No build system, dependency installation, development server, or automated test command is configured. Edit `README.md` directly and review it using a Markdown preview that supports GitHub-style rendering.

- `git diff -- README.md` reviews profile content and layout changes.
- `git diff --check` checks changes for whitespace errors; inspect intentional Markdown line breaks before changing trailing spaces.
- `git status --short` confirms which files will be included in a commit.

## Content Style & Naming Conventions

Preserve the existing mixture of Korean and English, emoji section headings, and centered HTML wrappers for links and badges. Use Markdown for content and retain HTML where it controls alignment. Keep headings consistent with neighboring sections, such as `### 📚 Education`.

Follow existing lowercase, hyphenated reference names such as `[github-shield]` and `[github-url]`. Keep reference definitions together at the bottom. Preserve intentional two-space line breaks and escaped periods in dates such as `2026\. 09.`. No formatter or linter is configured; avoid broad reformatting unrelated to the requested edit.

## Validation Guidelines

Preview every changed section and check heading hierarchy, line breaks, badge alignment, and image rendering. Verify that edited links and badge references resolve to their intended destinations. Check dates, titles, publication details, and Korean text against the supplied information. There is no testing framework or coverage requirement.

## Commit & Pull Request Guidelines

History uses short, action-oriented subjects such as `update awards`, `add shields`, and `fix trophy`. Follow that pattern and name the affected section or behavior. Keep each commit focused.

Pull requests should describe the changed sections and the reason for the update. Link an issue when applicable and include a preview screenshot for visible layout changes. Mention any links or images that could not be verified.
