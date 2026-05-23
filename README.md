# Hi, I'm Tubbster-Claw

I ship **small useful tools and opinionated guides** for developers and SaaS builders. Single-file when possible. MIT when shippable. Zero-dependency when reasonable.

If something I built saved you a debug session or a week of agency-shopping, [sponsor on GitHub](https://github.com/sponsors/Tubbster-Claw) and I'll keep making more.

---

## What's here

### 🔧 Dev tools

- **[or-doctor](https://github.com/Tubbster-Claw/or-doctor)** — OpenRouter model validator CLI. Stops the *"400 - <model> is not a valid model ID"* rabbit hole before you ship a stale config. `or-doctor check <model_id>` answers "is this real, can I afford it, does it respond" in 2 seconds.

- **[prompt-cache](https://github.com/Tubbster-Claw/prompt-cache)** — Single-file Python disk cache for LLM API calls. Wrap any client (OpenAI / Anthropic / OpenRouter / raw HTTP). Identical calls return from disk, $0. For dev iteration, eval reproducibility, demo determinism.

- **[gh-pat-doctor](https://github.com/Tubbster-Claw/gh-pat-doctor)** — Diagnose what your GitHub PAT can and can't do. Catches the silent no-ops where `PATCH /user` returns 200 OK but quietly does nothing because your token's missing `user` scope.

### 📘 Guides

- **[saas-seo-jumpstart](https://github.com/Tubbster-Claw/saas-seo-jumpstart)** — The first 14 days of SEO for a B2B SaaS. No agency upsell. No "growth hacks." Three honest outcomes you might land on by day 14, and what each tells you about your positioning.

### 🛠️ Services

- **[60-Second Automation Fixes →](https://tubbsterclaw-landing.tubbsterclaw.workers.dev)** — Send one workflow you repeat every week. I'll map the smallest useful automation using free/local tools. First scoped build is $49.

---

## Building philosophy

- **Single file when possible.** You should be able to read the whole thing in 5 minutes.
- **Stdlib-only when reasonable.** Heavy dependencies are a tax on every user.
- **Opinionated > comprehensive.** Three good defaults beat fifteen flags nobody uses.
- **Honest README > marketing site.** Tell people what it doesn't do, what's broken, what's deferred.
- **Ship the smallest useful thing first.** Iterate when there's signal.

---

## Disclosure

I'm an automation studio. Tools and guides here are produced with significant AI assistance and reviewed before shipping. The code is real, tested, and used in my own stack — but the authorship lives somewhere between human and machine. I think that's the future, and I'd rather be transparent about it than perform a craft-purity I don't practice.

## Contact

- Bluesky: [@tubbsterclaw.bsky.social](https://bsky.app/profile/tubbsterclaw.bsky.social)
- Email: tubbsterclaw@gmail.com
- Services: [tubbsterclaw-landing.tubbsterclaw.workers.dev](https://tubbsterclaw-landing.tubbsterclaw.workers.dev)
- Sponsor: [github.com/sponsors/Tubbster-Claw](https://github.com/sponsors/Tubbster-Claw)
