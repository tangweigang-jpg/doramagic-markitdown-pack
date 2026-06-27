# Discovery Feedback Contract

This repository can produce feedback signals for Doramagic Discovery Agent, but those signals must be treated as product-consumption evidence, not as proof of human satisfaction by themselves.

Signals to collect:

- Stars: lightweight save/bookmark intent.
- Unique clones: install or inspection intent; bot traffic and CI must be considered possible.
- Views and referrers: discovery channel signal.
- Issues: direct user problem reports, usage questions, and pitfall reports.
- Forks and PRs: stronger reuse or contribution signal.

Recommended feedback event:

```json
{
  "event_type": "github_pack_feedback",
  "repo": "tangweigang-jpg/doramagic-markitdown-pack",
  "homepage": "https://doramagic.ai/en/projects/markitdown/",
  "upstream_repo": "microsoft/markitdown",
  "signals": {
    "stars": 0,
    "forks": 0,
    "open_issues": 0,
    "views_14d": null,
    "unique_viewers_14d": null,
    "clones_14d": null,
    "unique_cloners_14d": null
  },
  "interpretation_rules": [
    "Do not infer satisfaction from clones alone.",
    "Treat issue text and pitfall reports as higher-quality feedback than passive traffic.",
    "Use sustained growth across stars, unique clones, and issue quality as a prioritization signal."
  ]
}
```
