<div align="center">

<a href="https://github.com/ii-reviewer">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=560&lines=%3E+who+are+you%3F;%3E+just+review%2C+nothing+special;%3E+approve+or+request+changes%3F" alt="who are you?" />
</a>

<sub><code>Go · Java · backend · code review</code></sub>

<br/><br/>

## The Ratio

<table>
  <tr>
    <td align="center" width="200">
      <h1>~50K</h1>
      <sub>lines <b>written</b></sub><br/>
      <sub><code>+50 113 / −7 489 · 49 commits</code></sub>
    </td>
    <td align="center" width="80"><h1>:</h1></td>
    <td align="center" width="200">
      <h1>~484K</h1>
      <sub>lines <b>reviewed</b></sub><br/>
      <sub><code>839 PRs · 10 272 files</code></sub>
    </td>
  </tr>
</table>

<b>1 : 10</b> — ten lines read for every one written.

<sub>883 issues opened · 24 repos · 13 orgs · ~1.3 PRs/day · median PR 264 lines · since Dec 2024</sub>

<br/>

## Stack

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=gnu&logoColor=white" />
<img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />

<sub>reviewed: <b>Go 64%</b> · <b>Java 36%</b> — by PRs</sub>

<br/>

## Live

<img src="https://github-readme-stats.hackclub.dev/api?username=ii-reviewer&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&hide_title=true&bg_color=0d1117" height="165" alt="stats" />
<img src="https://streak-stats.demolab.com?user=ii-reviewer&theme=github-dark-blue&hide_border=true&background=0d1117" height="165" alt="streak" />

<img src="https://ghchart.rshah.org/58a6ff/ii-reviewer" width="100%" alt="contributions" />

<sub>widgets see public repos only — most of the 484K lives in private ones</sub>

<br/>

## Featured

<a href="https://github.com/ii-reviewer/go-backend-standards">
  <img src="https://github-readme-stats.hackclub.dev/api/pin/?username=ii-reviewer&repo=go-backend-standards&theme=github_dark&hide_border=true&bg_color=0d1117" alt="go-backend-standards" />
</a>

<sub>Go backend standards as a Claude Code skill — everything I keep flagging in review, written down once.</sub>

<br/><br/>

<sub>Pronouns: <code>reviewer</code> · Fun fact: still like pasta</sub>

</div>

<details>
<summary><sub>how these numbers were counted</sub></summary>

```bash
# lines written — unique commits by sha, summed via /repos/{r}/commits/{sha}.stats
gh api --paginate 'search/commits?q=author:ii-reviewer'

# lines reviewed — additions/deletions of every PR with a review from me
gh api graphql -f query='{ search(type:ISSUE, query:"reviewed-by:ii-reviewer is:pr", first:100) {
  nodes { ... on PullRequest { additions deletions changedFiles } } } }'

# issues opened
gh api 'search/issues?q=author:ii-reviewer+is:issue' --jq .total_count
```

Snapshot: 2026-09-15. Private repos included.

</details>
