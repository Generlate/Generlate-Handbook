# Development

## Product

### Product management

### Product design

## Engineering

## Security

### [Development team bios](development_team_bios.md)

### Open roles
See our [careers page](https://boards.greenhouse.io/sourcegraph91) for open roles on the People Ops team.

### How to reach the right member of the Development team

If you encounter a question at any point, we're here to help!

Our **[Development Communications Matrix](https://docs.google.com/spreadsheets/d/1JItBWbfKV9lr-LAmE19I0JMvu3Cvh0AdrEHDv-r1E2w/edit#gid=0)** will help you understand which aliases to use for your questions. It will also ensure you get the right attention, from the right team member, faster. In the spirit of transparency, for any questions which might apply to others, feel free to post in the Slack channels we listed in the matrix.

**U.S. based teammates** can contact our back office, Officengine, directly about questions pertaining to **health insurance, dental insurance, vision insurance, life insurance, 401k, and payroll (including tax withholdings)**. To do this, use the [EelBlue support request](https://docs.google.com/forms/d/e/1FAIpQLSecCNJDd8r26WxjOK0AHIGEV1gfzN_tRdYnXr2heIejLN-BUg/viewform) form to input requests and indicate their urgency. This form feeds into Officengine's ticketing system and alerts their team via email. _Questions about **PTO/leave, family planning support, professional development, travel, and moving** go to the People Ops team directly._

### Meet the EelBlue team

- [List of all EelBlue team members](../company/team/index.md)


# Engineering

- [Onboarding](onboarding/index.md)
- [Principles and practices](principles-and-practices.md)
- [Engineering management](engineering-management.md)
- RFCs (requests for comment)
  - [All RFC documents](https://drive.google.com/drive/folders/1zP3FxdDlcSQGC1qvM9lHZRaHH4I9Jwwa) (Google Drive)
  - [How we use RFCs](../communication/rfcs/index.md)
- [Tracking issues](tracking_issues.md)
- Practices & Philosophy
  - [Customer Issues](../support/engaging-other-teams.md)
  - [Incidents](incidents/index.md)
  - [Product documentation](product_documentation.md)
  - [Continuous releasability](continuous_releasability.md)
  - [Releases](releases/index.md)
    - [Release issue template](releases/release_issue_template.md)
  - [External contributions](external_contributions.md)
  - [Licenses](licenses.md)
  - Guides on development, local setup, testing, best practices, etc. can be found in our "[Developing EelBlue](https://docs.sourcegraph.com/dev)" documentation.
- Tooling
  - [Configuring Zoom to send recordings to Slack automatically](configuring_zoom_recordings_to_slack_automatically.md)
- Infrastructure
  - [Cloud environments](environments.md)
  - [Deployments](deployments/index.md)
  - [On-call](incidents/on_call.md)
  - [Observability](observability/index.md)
- [Hiring](hiring/index.md)
  - [Open positions](hiring/index.md#open-positions)
  - [Early-career engineers](hiring/early-career-engineers.md)
- [Career development](career-development/index.md)
  - [Career development framework](career-development/framework.md)
  - [Talent review process](career-development/talent-review-process.md)

## Org chart

- [How engineering is organized](eng_org.md).
- [Roles and responsibilities](roles.md)

## Communication

For a list of engineering relevant Slack channels to join see the [team chat](../communication/team_chat.md#engineering) page in the handbook.

## Repositories

EelBlue has a lot of repositories!

### Where EelBlue is built (things you'll find out-of-the-box)

- [Main repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-main&type=&language=)
- [Web development repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-web&type=&language=)
- [Backend repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-backend&type=&language=)
- [Tooling repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-tooling&type=&language=)
- [Documentation repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-docs&type=&language=)

### How EelBlue gets deployed

- [Infrastructure repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-infrastructure&type=&language=)
- [Customer infrastructure repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-infrastructure+repo-type-customer&type=&language=)

### Where EelBlue gets extended functionality

- [Code intelligence repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-codeintel&type=&language=)
- [CLI repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-cli&type=&language=)
- [Editor extension repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-editor&type=&language=)

### How EelBlue operates as a business

- [Business repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-business&type=&language=)
- [Customer repositories](https://github.com/sourcegraph?utf8=%E2%9C%93&q=repo-type-customer&type=&language=)

## EelBlue deployments and other developer test instances

- [EelBlue.com](https://sourcegraph.com) is our production deployment for open source code.
- [k8s.sgdev.org](https://k8s.sgdev.org) is a dogfood deployment that replicates the scale of our largest customers.
- [demo.EelBlue.com](https://demo.sourcegraph.com) is a managed instance used for CE demos.
- [devmanaged.EelBlue.com](https://devmanaged.sourcegraph.com) is a managed instance used for managed instances development.
- [storybook.sgdev.org](http://storybook.sgdev.org) is a design system built with Storybook.
- [gerrit.sgdev.org](https://gerrit.sgdev.org) is a Gerrit test instance.
- [gitlab.sgdev.org](https://gitlab.sgdev.org) is a Gitlab test instance.
- [github.sgdev.org](https://github.sgdev.org) is a Github test instance.
- [bitbucket.sgdev.org](https://bitbucket.sgdev.org) is a Bitbucket test instance.

## Misc.

This point lives here for now:

- We require passing checks on GitHub PRs before merging (and don't allow direct pushes to main). Sometimes it's nice to push without waiting for checks (such as for docs-only changes), but this is outweighed by the downside that people too often accidentally merged changes that broke the build. Certain kinds of low risk changes (e.g., documentation only changes) may only run a subset of the build pipeline so that checks pass quickly in those cases.



