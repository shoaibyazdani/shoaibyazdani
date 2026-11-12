# Shoaib Latif

**SDET at RHK Properties · Playwright · Selenium · Appium · CI / E2E · Dubai, UAE**

I build and maintain test infrastructure for web and mobile apps, and ship the work back to the open-source ecosystem whenever I can. 18+ merged PRs in 2026 plus a merged PR and four commits in `NousResearch/hermes-agent`'s `main` — including **keychain**, my macOS-Keychain secret-source plugin, merged into their plugin catalogue after the Nov 2026 plugin hackathon.

---

## Selected OSS contributions (2026)

| Repo | PR | What I shipped |
|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [#153690](https://github.com/NousResearch/hermes-agent/pull/153690) | plugin catalogue: **keychain** — macOS Keychain as a Hermes secret source ([repo](https://github.com/shoaibyazdani/hermes-keychain), v0.1.1) |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [commit](https://github.com/NousResearch/hermes-agent/commit/0151c2f613c73a76a42b2b457f184f4c1ec6f642) | fix(telegram): retry webhook bootstrap on a transient Bot API failure |
| [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | [#10903](https://github.com/vitest-dev/vitest/pull/10903) | docs: `userEvent.keyboard` special-keys list |
| [sidereal-io/sidereal](https://github.com/sidereal-io/sidereal) | [#427](https://github.com/sidereal-io/sidereal/pull/427) | fix: e2e Playwright skeleton + CI gate (designed, reviewed, merged) |
| [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research) | [#6338](https://github.com/LearningCircuit/local-deep-research/pull/6338) | test: real-browser mXSS coverage across Chromium / WebKit / Firefox |
| [snapotter-hq/SnapOtter](https://github.com/snapotter-hq/SnapOtter) | [#2475](https://github.com/snapotter-hq/SnapOtter/pull/2475) | ci: regenerate darwin visual baselines on macOS |
| [prettier/prettier](https://github.com/prettier/prettier) | (2 PRs) | link + ternary formatting |
| [Pikselkroken/pixlstash](https://github.com/Pikselkroken/pixlstash) | merged | fix: warn on dependency without download URL |
| [Hebbian-Robotics/hflow](https://github.com/Hebbian-Robotics/hflow) | merged | fix: contextual ValueError on HF JSON decode failures |
| [martinhrvn/hive-pal](https://github.com/martinhrvn/hive-pal) | merged | migrate component tests to Playwright stories model |
| [neuron-workspace/Neuron](https://github.com/neuron-workspace/Neuron) | merged | test: e2e persistence across close/reopen |
| [EastSun5566/hackdesk](https://github.com/EastSun5566/hackdesk) | merged | ci: macOS lifecycle spec + packaged startup |
| [hashgraph-online/hol-guard](https://github.com/hashgraph-online/hol-guard) | [#5049](https://github.com/hashgraph-online/hol-guard/pull/5049) | draft: scoped package label regression test |

Full list of 28 PRs opened in 2026 → see [Pull requests tab](https://github.com/shoaibyazdani?tab=open-source-contributions).

---

## Shipped projects

- **[hermes-keychain](https://github.com/shoaibyazdani/hermes-keychain)** — macOS Keychain as a first-class Hermes secret source. A `SecretSource` plugin (`secrets.keychain`) so provider keys resolve from the OS keystore at startup instead of a plaintext `.env`; operator-only migration with verified readback, `.env` removal through core, append-only fetch audit. Merged into the Hermes plugin catalogue ([#153690](https://github.com/NousResearch/hermes-agent/pull/153690), v0.1.1) — 15 tests, `hermes plugins validate` clean.

---

## Stack

- **Test frameworks** — Playwright (multi-browser, visual, component, API), Selenium, Appium, Vitest, Jest
- **Languages** — TypeScript, JavaScript, Python
- **CI** — GitHub Actions (macOS lifecycle specs, darwin runners), Azure Pipelines
- **What I care about** — flaky-test triage, regression coverage, browser-automation ergonomics, CI on real macOS

---

## How I work

I prefer to land every fix with a **regression test or a CI guard** — never just a code change. AI assistance is part of my daily workflow; I disclose it in PR bodies and stick to maintainer-agreed plans. If I open a PR, the test usually fails for the right reason before the fix.

---

## Currently shipping

- `hashgraph-online/hol-guard#4809` — package review drops the npm scope
- `hashgraph-online/hol-guard#5049` (Draft) — scoped-package regression test
- `gravity-ui/graph#398` — extract Playwright page objects into `@gravity-ui/graph-playwright`
- `0xBakeer/TandemLLM#7` — `activity.spec.ts` long-task budget (50 ms) on GB10
- `vitest-dev/vitest#11743` — fix: batch console logs per macrotask (open, CI green)
- `NousResearch/hermes-agent#151948` — runtime footer token-usage + `/usage` modes

---

## Contact

- LinkedIn — [shoaib-latif](https://www.linkedin.com/in/shoaib-latif/)
- Email — shoaibyazdani7@gmail.com
- Open to: senior SDET / test-architect / staff-quality roles · remote · Dubai-based
