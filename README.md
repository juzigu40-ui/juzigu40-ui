# Hi, I'm Juzigu40

I work on backend integrations, deployment packaging, and validation-heavy changes that are easy for another engineer to review and rerun.

## What I focus on

- Backend and API integration work
- Deployment and environment wiring for web applications
- Validation tooling: smoke checks, CI paths, and hosted proof
- Small infrastructure changes that are easier to audit than broad rewrites

## Selected public work

- [FinMind deployment submission](https://github.com/rohitdash08/FinMind/pull/308): Docker, Kubernetes, and Tilt deployment packaging with a hosted Render proof path and review-oriented validation assets
- [kuberift OpenCost integration](https://github.com/syedazeez337/kuberift/pull/63): optional cost-awareness path for a terminal Kubernetes workflow
- [robin-base-tools Privy auth work](https://github.com/lbbcym/robin-base-tools/pull/3): server-side Privy authentication with replay protection
- [AMPTemplates code-server template](https://github.com/CubeCoders/AMPTemplates/pull/1848): new code-server template packaged as a focused contribution

## Recent small fixes

- [AgentOrchestration boolean env overrides](https://github.com/orchestration-agent/AgentOrchestration/pull/973): parse exact `true` / `false` overrides as booleans while leaving other strings alone
- [AgentOrchestration event decorator validation](https://github.com/orchestration-agent/AgentOrchestration/pull/1064): reject blank or non-string event names before metadata is written
- [Haven_Contracts bounty amount validation](https://github.com/HavenOnStellar/Haven_Contracts/pull/24): reject stolen-report bounty amounts below the minimum
- [Yuzu webhook internal-host guard](https://github.com/Tr3kkR/Yuzu/pull/1123): block local and private webhook hosts, including IPv4-mapped IPv6 forms
- [SecID subtype inventory](https://github.com/CloudSecurityAlliance/SecID/pull/70): complete a methodology subtype gap and add warn-only completeness checking
- [Rustchain setup miner CLI fix](https://github.com/Scottcjn/Rustchain/pull/6064): make `setup_miner.py --help` and unknown args exit before setup work
- [Omi Open-Meteo integration app](https://github.com/BasedHardware/omi/pull/7442): no-auth weather, forecast, and air-quality chat tools backed by public Open-Meteo APIs
- [Omi Frankfurter currency app](https://github.com/BasedHardware/omi/pull/7443): no-auth currency conversion and reference-rate chat tools backed by the public Frankfurter API
- [Omi Public Holidays app](https://github.com/BasedHardware/omi/pull/7445): no-auth public holiday, upcoming holiday, and long-weekend chat tools backed by Nager.Date

More context lives in [engineering-portfolio](https://github.com/juzigu40-ui/engineering-portfolio).

## How I work

- I prefer reviewable changes with explicit entry points and validation notes
- I keep deployment and runtime checks close to the code
- I try to leave a branch in a state where someone else can reproduce the same path quickly

## Current direction

- Hosted deployment proof and runtime verification
- Backend and auth integration work
- Infra-adjacent tooling for deployment and review workflows

## Small scoped help

I can also help clean up PR descriptions, issue reports, security report drafts, README first screens, and small product pages.

Typical small task: USD 50 / CNY 300 after the scope is clear.

Boundaries:

- No fake validation notes or fake user/customer claims
- No unauthorized security testing
- No merge, payout, ranking, or sales promises
