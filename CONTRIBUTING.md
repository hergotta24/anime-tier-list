# Contribution workflow

This is a personal review journal. Contributions should preserve Alex’s authorship of ratings and opinions rather than supplying reviews on his behalf.

## Add a completed review

1. Create a branch from `main`.
2. Copy `reviews/_template.md` to a lowercase, hyphenated filename such as `reviews/example-title.md`.
3. Replace all placeholders with personal notes.
4. Add the review to exactly one tier in `README.md`.
5. Keep spoilers out of the summary or mark them clearly.
6. Commit the review and tier placement together.

Suggested commit format:

```text
review: add <anime title>
```

## Add an optional progress note

Progress notes may be added to a review while watching, but they are not required. A progress-only commit should identify the title and episode or milestone:

```text
progress: <anime title> through episode <number>
```

When the anime is completed, update the review and tier list in one focused commit.

## Pull-request checklist

- [ ] The review is based on Alex’s own viewing experience.
- [ ] No template placeholders remain in a real review.
- [ ] The README links to the review from exactly one tier.
- [ ] Spoilers are clearly labeled.
- [ ] The change contains no private account information or copyrighted episode media.
