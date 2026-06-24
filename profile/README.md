# Team Castaldi

Nathan Castaldi — IT professional, homelab builder, amateur one-man software shop. The projects here started as real problems and turned into things that actually run.

---

## Projects

### homelab-registry-mcp

A Model Context Protocol server that acts as the authoritative service catalog for a homelab. It discovers services from Traefik, Docker, and Authentik; reconciles them against a curated SQLite registry; and exposes the whole thing as MCP tools, resources, and prompts for AI agents.

Discovery is read-only. The write path — when there's a finding worth acting on — opens a PR, attaches a DSPy-generated remediation patch, and waits for a human to merge it. Nothing ships automatically.

Current state: hardware node inventory and git-crypt secrets integration are complete. CD runs on a GitHub Actions self-hosted runner on the homelab itself — new image, deploy verified in 18 seconds.

**Status:** Active development · Private

---

### jobsquatch

A job search tool built around the idea that AI-assisted cover letters shouldn't sound like everyone else's AI-assisted cover letters. The first piece is a short conversational interview that captures how a person actually communicates and produces a reusable voice profile. Everything generated downstream is constrained by that profile.

It's not an ATS optimization tool. That approach is explicitly out of scope.

Running in closed beta at [jobsquatch.us](https://jobsquatch.us). Stack: FastAPI + React + PostgreSQL + Redis + Stripe, deployed on panoptichron via Cloudflare Tunnel.

**Status:** Closed beta · Live

---

### clasp.pet

A platform built around a physical thing: a 3D-printed QR collar tag that links to a digital pet profile. When a stranger finds a lost pet, they scan the tag, land on the profile, and can contact the owner without either side exchanging phone numbers.

The tag geometry is parametric OpenSCAD — three shapes (hexagon, capsule, crest), two-color filament, color-change pause baked into the G-code. The marketing landing page is live and the waitlist is open. The platform itself (pet profiles, finder contact relay, owner dashboard) is next.

**Status:** Early stage · Private

---

### tv-as-a-service

A B2B2C platform for managed in-room entertainment in short-term rentals. Property owners get premium hardware and support; guests get a setup that works without calling anyone. The gap between "smart home" and "reliably working home" is a real problem in the STR space.

**Status:** Early stage · Private

---

## Contact

| | |
|---|---|
| Email | [nathan@castaldifamily.com](mailto:nathan@castaldifamily.com) |
| LinkedIn | [Nathan Castaldi](https://www.linkedin.com/in/nathancastaldi/) |

---

<sub>Atlanta, GA</sub>
