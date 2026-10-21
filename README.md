# Morning study

Public Traditional Chinese educational briefing text for a reader-configured morning audio shortcut.

## Format

`latest.txt` contains a dated short edition: three recall keywords, one recall question, and a brief public-literature news flash. Older papers are explicitly labeled as retrospectives. `latest_sources.md` records public sources and caveats.

The target is approximately 140–170 Chinese characters, not a guaranteed audio duration. Voice and speed affect timing. Check that the complete ending is audible; Intercom may truncate long input. This is a short briefing, not a long podcast.

## Publication scope

Only general educational principles, original summaries of public literature, and explicitly hypothetical examples belong here. Do not include personal information, private conversations, unpublished research, project identifiers, project-specific molecules, raw data or results. Do not reproduce full copyrighted papers. Avoid combinations of details that indirectly identify private projects.

## Reading the feed

The file stays at `latest.txt` on `main`:
https://raw.githubusercontent.com/anankaku/morning_study/main/latest.txt

A client may alternatively retrieve the GitHub Contents API endpoint with `Accept: application/vnd.github.raw+json`. No access token is needed for this public file.

Example shortcut: URL → Get Contents of URL → Get Text from Input → Make Spoken Audio from Text (explicit Chinese voice) → Intercom (generated audio, not text).

Check the spoken date before treating an edition as current. A robust client should reject missing, stale or invalid content rather than replay an old edition; this repository does not itself enforce client-side checks. Public content and Git history may be read and copied by anyone.
