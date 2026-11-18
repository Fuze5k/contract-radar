# Contract Radar

A Forge app for Jira: the software contract and renewal register for business teams.

- **Renewal radar.** Every contract gets a decide-by date (term end minus notice period). A daily job opens a
  Jira work item for the owner before that date, so nothing renews on its own by surprise.
- **"Do we already pay for this?"** A panel on every work item checks a purchase request against the register
  and explains why: same kind of tool, what the contract already covers, free seats, same team.
- **Teamwork Graph connector.** The register is pushed into the Atlassian Teamwork Graph, so Rovo Search and
  Rovo Chat answer contract questions with the cost, owner and dates.
- **Rovo agent.** Finds contracts, checks requests, lists renewals due and drafts a renewal brief with usage,
  overlaps and a right-sizing option.
- **CSV import** from the spreadsheet most teams already keep.

Built for Codegeist 2026. Runs entirely on Atlassian Forge ("Runs on Atlassian"): no external servers.

## Try it

1. Install the app on a Jira Cloud site from the install link in the Devpost entry (site admin needed).
2. Jira > Apps > **Contract Radar**: click **Add sample contracts** (11 invented vendors).
3. Jira settings > Apps > **Contract Radar settings**: pick a project for renewal work items, then
   **Check renewals now** and **Create requests** (two sample purchase requests).
4. Open a sample request and the **Contract Radar** panel: it says whether the company already pays for it.
5. Ask Rovo > **Contract Radar** agent: "Which contracts need a renewal decision in the next 30 days?"
6. Optional, org admin: Atlassian Administration > Apps > Sites > your site > Connected apps > Contract Radar >
   Connections > Teamwork Graph connectors > **Connect**. Rovo Search then lists the contracts.

## Privacy

See [PRIVACY.md](PRIVACY.md). Support: [open an issue](https://github.com/Fuze5k/contract-radar/issues).
