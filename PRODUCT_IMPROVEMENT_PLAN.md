# Product Improvement Plan

Last updated: 2026-07-01

## Customer-language correction

Do not position this product as generic AI job matching. Customer language points
to wasted effort: stale postings, duplicate reposts, closed roles, low-signal
job pages, lost links, and forgetting which resume version was used.

Use language such as:

- stop wasting applications on stale or duplicated postings;
- verify company-site source links;
- track posting freshness;
- recover saved links;
- review high-fit roles before applying;
- keep application and resume-version context together.

## Product gap

The scanner already fetches and filters public employer postings. The next
product step is to become a trust and triage layer for target-company searches,
not just a search results fetcher.

## Capability backlog

1. Add repost/duplicate detection across title, company, location, and body
   fingerprint.
2. Add freshness scoring that distinguishes newly posted, old, reposted, and
   uncertain roles.
3. Add a company-site verification indicator for roles found through public ATS
   endpoints or helper links.
4. Add saved-link recovery and export fields for application status and resume
   version used.
5. Add a proof example showing how a user filters out stale, duplicate, or
   low-signal postings from a target-company list.

## Acceptance criteria

- Search output helps users decide whether a posting is worth manual review.
- Duplicate and stale-posting signals are visible before export.
- The app remains local-first, account-free, backend-free, and no-auto-apply.
- Exported CSV can support follow-up tracking outside the app.
