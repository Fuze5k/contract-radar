# Contract Radar - privacy policy

Last updated: 18 November 2026.

Contract Radar is a Forge app for Jira Cloud. It runs entirely on Atlassian's Forge platform ("Runs on Atlassian").

**What the app stores.** The contracts people enter or import: vendor, product, category, what the tool covers,
team, owner (a name or role as typed, and optionally the Atlassian account ID picked as owner), annual cost and
currency, seats bought and in use, term dates, notice period, auto-renewal, notes, status and a short change
history with the Atlassian account ID of the person who made each change. It stores app settings chosen by a
site admin, the Teamwork Graph connection id, and the result of the last sync and daily check.

**What it writes in Jira.** Renewal work items in the project an admin chooses (summary, description, label,
due date, assignee) with a small work item property that links the work item to its contract.

**What it writes to the Teamwork Graph.** When a site admin connects the Contract Radar connector, one document
per contract (its title and a plain-text description of the facts above, without account IDs) so Rovo Search,
Rovo Chat and agents in the same site can find it. Disconnecting the connector stops the sync; removed
contracts are deleted from the graph.

**Where.** In Forge storage, in Jira and in the Teamwork Graph, on Atlassian's infrastructure, inside the
customer's site. The app sends no data to servers outside Atlassian, uses no third-party services and no
external analytics. The developer does not copy customer data into any other system.

**What it reads.** Jira work items and projects the user is allowed to see, to check a purchase request
against the register.

**Who sees it.** Users of the same Jira site. A site admin can limit who may change contracts.

**Deletion.** Contracts can be deleted in the app. Uninstalling the app removes its Forge storage according to
Atlassian's Forge data retention rules. Jira work items stay in Jira like any other Jira data and can be
deleted there.

**Contact.** [Open an issue](https://github.com/Fuze5k/contract-radar/issues) in this repository.
