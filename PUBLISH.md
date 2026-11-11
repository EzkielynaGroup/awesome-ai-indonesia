# Publish notes: awesome-ai-indonesia

Built locally on 11 Nov 2026. Nothing pushed. Owner runs the steps below.

## GitHub

- **Description (<= 120 chars):** `Daftar kurasi AI untuk developer & UMKM Indonesia: LLM bahasa Indonesia, dataset, NLP, suara, regulasi, API, MCP, n8n.`
- **Homepage:** leave empty (or the repo URL). Do not point it at ezkielyna.store: the list must stay neutral.
- **Topics (14):** `awesome`, `awesome-list`, `indonesia`, `bahasa-indonesia`, `artificial-intelligence`, `llm`, `nlp`, `indonesian-nlp`, `datasets`, `speech-recognition`, `mcp`, `n8n`, `umkm`, `ai-regulation`
  (`awesome` and `awesome-list` are required by awesome-lint's `awesome-github` rule.)

```bash
cd awesome-ai-indonesia   # the local repo folder
bash <path-to>/gh_public_check.sh .   # the org leak check; must print CLEAN
gh repo create EzkielynaGroup/awesome-ai-indonesia --public --source . --remote origin \
  --description "Daftar kurasi AI untuk developer & UMKM Indonesia: LLM bahasa Indonesia, dataset, NLP, suara, regulasi, API, MCP, n8n."
git push -u origin main
gh repo edit EzkielynaGroup/awesome-ai-indonesia --add-topic awesome,awesome-list,indonesia,bahasa-indonesia,artificial-intelligence,llm,nlp,indonesian-nlp,datasets,speech-recognition,mcp,n8n,umkm,ai-regulation
```

## Enable the parked entries (HTML comments in README.md)

The "MCP dan Agen AI" section has a comment block with EzkielynaGroup repos that were not public on 11 Nov 2026:
`mcp-bmkg`, `mcp-hari-libur-indonesia`, `mcp-qris`, `mcp-rupiah`, `mcp-wilayah-indonesia`, and the sister list `awesome-mcp-indonesia`.
When a repo is public: move its line out of the comment, keep alphabetical order, and for `mcp-rupiah` replace the TODO with the
final one-line description from its README. Then run `python3 scripts/check_links.py README.md CONTRIBUTING.md`.

## After publishing

1. Run `npx awesome-lint` in the repo: before publishing it reports exactly one error (`awesome-github`: needs a GitHub remote), which
   disappears once the repo exists with the two topics above. All other rules pass.
2. Enable GitHub Actions (default on); the `Link check` workflow runs weekly and opens an issue when a link dies. No secrets needed.
3. Submitting to sindresorhus/awesome is **not** possible right away: the list must be 30 days old, the owner must curate and review
   it by hand (their rules reject AI-generated lists and fully AI-generated PRs), and the PR author must review 4 other open PRs.
   Earliest date: about 12 Dec 2026. Their PR template is at https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md.
4. Good backlink spots (owner decides): `kmkurn/id-nlp-resource`, `GitIndonesia/awesome-indonesia-repo`, `fransallen/awesome-indonesia`
   accept PRs; link this list from the EzkielynaGroup org profile and from `tips-ai-indonesia`.

## Things to re-check before publishing

- Payment section facts (min top-up, methods) were read from each provider's site on 11 Nov 2026 and can change.
- "Status Rancangan Perpres AI" cites a Kontan report from Sep 2026; if a Perpres AI has been signed since, replace that entry with
  the JDIH link of the signed regulation and update the FAQ answer.
- `data.bmkg.go.id` answers browsers but blocks the Python checker (TLS/bot block), so it shows as WARN, not FAIL.
