# Zamana Wiki — Progress & Build Log

**Owner:** Murat Özsaygılı
**Started:** 2026-04-24
**Target URL:** https://zamana.com.tr/wiki
**Language:** Turkish (primary)
**Status:** Setup phase — pre-scaffold

---

## Strategic Purpose

1. **SEO magnet** — rank for Turkish Claude queries, drive inbound leads to the retainer program
2. **Credibility artifact** — definitive Turkish-language Claude reference, proves depth to prospects
3. **Client resource** — living reference retainer clients use between sessions

Every wiki page ends with a CTA block pointing to Zamana's retainer offer.

---

## Infrastructure Stack (Decided)

| Layer | Choice | Why |
|---|---|---|
| Static site generator | **MkDocs Material** | Markdown-native, fast, Turkish-friendly, great defaults |
| Content format | Markdown `.md` | Claude authors natively, Murat edits in VS Code |
| Version control | **Git + GitHub** | History, backup, auto-deploy trigger |
| Hosting / CDN | **Cloudflare Pages** | Free, global CDN, Git-linked auto-deploy |
| URL structure | `zamana.com.tr/wiki` (subdirectory) | Better SEO than subdomain — consolidates domain authority |
| Path routing | **Cloudflare Worker** | Required to serve Pages under `/wiki` subpath |
| Local editor | VS Code | Already installed |
| Local preview | `mkdocs serve` (Python) | Live reload on localhost:8000 |

**Rejected alternatives:** WordPress (slow/plugin rot), Notion (weak SEO, ugly URLs), Docusaurus (React overkill), GitBook (lock-in), Obsidian Publish (paid + URL limits), subdomain `wiki.zamana.com.tr` (splits SEO authority).

---

## Accounts & Identities

| Service | Identifier | Status |
|---|---|---|
| GitHub | `zamana-murat` | ✅ Registered |
| Cloudflare | `murat@zamana.com.tr` | ✅ Registered |
| Google Workspace | `murat@zamana.com.tr` (email) | ✅ Active |
| Domain registrar | External hosting (not Cloudflare) | ⚠️ DNS needs migration to Cloudflare |

---

## Environment

- **OS:** Windows 11 PC
- **Git:** ✅ Installed & current
- **Python:** ✅ Installed & current
- **VS Code:** ✅ Installed
- **OneDrive:** Inactive on this machine (safe to work inside OneDrive folder)
- **Local repo path:** `C:\Users\murat\OneDrive\Masaüstü\Claude\ClaudeforEnterprise\wiki\`

---

## Build Phases

### Phase 0 — Scope & Stack (✅ Complete)
- [x] Strategic purpose defined (SEO + credibility + client resource)
- [x] Stack decided (MkDocs Material + Cloudflare Pages)
- [x] URL structure decided (`/wiki` subdirectory)
- [x] Wiki folder created
- [x] Progress log initialized (this file)

### Phase 1 — Scaffold & Local Preview (⬜ Next)
- [ ] Create `mkdocs.yml` config
- [ ] Create `requirements.txt` (Python deps)
- [ ] Create folder structure under `docs/`
- [ ] Create starter `index.md` (homepage)
- [ ] Create `.gitignore`
- [ ] Install MkDocs Material locally (`pip install -r requirements.txt`)
- [ ] Run `mkdocs serve` — preview at localhost:8000
- [ ] Verify Turkish search works

### Phase 2 — GitHub + Cloudflare Pages Deploy (⬜ Pending)
- [ ] `git init` in wiki folder
- [ ] Create GitHub repo (zamana-murat/zamana-wiki, private or public — TBD)
- [ ] First `git push`
- [ ] Connect Cloudflare Pages to GitHub repo
- [ ] Verify staging URL works (e.g. `zamana-wiki.pages.dev`)

### Phase 3 — DNS Migration to Cloudflare (⬜ Pending, blocker for `/wiki`)
- [ ] Add `zamana.com.tr` as site in Cloudflare
- [ ] Change nameservers at registrar → Cloudflare nameservers
- [ ] Wait for propagation (up to 24h)
- [ ] Verify existing DNS records (website, email MX, etc.) still work
- [ ] Confirm Google Workspace email forwarding unaffected

### Phase 4 — `/wiki` Path Routing (⬜ Pending)
- [ ] Write Cloudflare Worker to proxy `zamana.com.tr/wiki/*` → Pages deployment
- [ ] Attach Worker route
- [ ] Test live URL

### Phase 5 — Content Production (⬜ Pending)
- [ ] Write 10 seed pages (highest-SEO-value topics first)
- [ ] Retainer CTA block component
- [ ] Internal linking pass
- [ ] Sitemap & schema.org validation
- [ ] Google Search Console submission

### Phase 6 — Launch & Iterate (⬜ Pending)
- [ ] Announce on LinkedIn (Zamana page + Murat personal)
- [ ] Monitor Search Console for indexing
- [ ] Weekly content cadence (TBD)

---

## Content Architecture (Planned)

```
docs/
├── index.md                         # Ana sayfa
├── temeller/                        # Foundations
│   ├── claude-nedir.md
│   ├── modeller.md
│   ├── nasil-dusunur.md
│   └── claude-vs-chatgpt.md
├── araclar/                         # Tools
│   ├── claude-desktop.md
│   ├── cowork-modu.md
│   └── hangisini-ne-zaman.md
├── claude-md/                       # CLAUDE.md guide
│   ├── nedir.md
│   ├── nasil-yazilir.md
│   └── ornekler.md
├── prompting/
│   ├── 4d-cercevesi.md
│   ├── temel-ilkeler.md
│   └── yaygin-hatalar.md
├── skills/
│   └── katalog.md
├── mcp/                             # MCP connectors
│   └── baglanti-listesi.md
├── departmanlar/                    # 12 departments
│   ├── satis.md
│   ├── pazarlama.md
│   ├── finans.md
│   ├── operasyon.md
│   ├── insan-kaynaklari.md
│   ├── hukuk.md
│   ├── bilgi-teknolojileri.md
│   ├── musteri-hizmetleri.md
│   ├── idari-isler.md
│   ├── liderlik.md
│   ├── satinalma.md
│   └── ihracat.md
└── sozluk.md                        # Glossary
```

---

## Pages Created Log

*(Updated every time a page is added or meaningfully revised.)*

| Date | Page | Status | Notes |
|---|---|---|---|
| — | — | — | No pages yet |

---

## Open Decisions

- [ ] GitHub repo **public or private**? (Public = free Pages, inbound developer signal. Private = hides drafts.) Recommendation: **public**.
- [ ] Repo name? Recommendation: `zamana-wiki`.
- [ ] First 10 pages priority order? (Follow SEO keyword potential, not content completeness.)
- [ ] Retainer CTA block wording — reuse Brainstorm.md language or freshly written?
- [ ] Analytics: Google Analytics 4, Cloudflare Web Analytics (privacy-friendly, free), or both?

---

## Notes for Future Sessions

- Always update this file after any infra change or page added.
- Keep Brainstorm.md as the strategy source; this file is **execution-only**.
- If scaffold ever needs to be rebuilt from scratch, stack decisions in this doc are the source of truth.
