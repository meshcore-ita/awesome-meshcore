# Contribution Guidelines

Thanks for helping keep this list useful.

## Adding an entry

- Open a pull request that adds one entry per line, in this format:
  `- [Name](https://example.com) - Short description.`
- Keep the description short, factual and ending with a period.
- Place the entry in the most specific existing section. Only propose a new
  section when several entries would live in it.
- Entries must be MeshCore-related, working and maintained. Dead links and
  abandoned projects are removed.
- Check that the entry is not already listed elsewhere in the readme; duplicate
  links fail CI.
- Do not add your own project more than once, and do not add affiliate links.

## Quality bar

An entry needs a reason to exist: firmware, client, library, tool, map,
documentation or community that a MeshCore operator would actually use.
Marketing pages, link farms and empty repositories are rejected.

## Before opening the pull request

- Run the linter: `npx awesome-lint`.
- Verify every link you added resolves (the `Dead links` workflow runs
  [lychee](https://github.com/lycheeverse/lychee) on all Markdown files).
- Use a descriptive pull request title, for example `Add MeshCore Foo`.

## Updating or removing an entry

Corrections, renames and removals of dead projects are welcome. Explain the
reason in the pull request description.
