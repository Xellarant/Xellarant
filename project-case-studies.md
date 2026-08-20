# Project Portfolio Copy

This file contains polished copy that can be reused in GitHub repo descriptions,
README introductions, portfolio cards, resumes, and application materials.

## Portfolio Positioning

Short version:

> Software engineer focused on .NET applications, legacy modernization,
> JavaScript/Node.js tooling, domain-heavy data systems, and practical release
> automation.

Slightly warmer version:

> I build software that helps complicated projects become usable: modern app
> clients for legacy workflows, JavaScript tools for messy content formats, and
> release pipelines that get testable builds into people's hands.

Communication is part of the work I enjoy most: helping turn rough ideas,
constraints, and wish lists into shared language, concrete scope, and
deliverables that solve the underlying problem while still feeling good to use.

Resume summary:

> .NET-focused software engineer with recent project work in MAUI/Blazor Hybrid
> app modernization, JavaScript/Node.js browser tooling, XML-to-SQLite data
> migration, rules/runtime evaluation, regression tooling, and GitHub Actions
> release automation.

## GitHub Repository Descriptions

Aurora Lights:

> Modern .NET MAUI/Blazor Hybrid continuation of the Aurora character builder,
> preserving legacy characters and XML content while adding a new app
> experience.

Aurora Translator:

> .NET 10 CLI and runtime toolkit for importing Aurora Builder XML into
> SQLite, evaluating rules, and producing app-facing character state.

Aurora Constellations (formerly Aurora XML Helper):

> Browser-based tool for converting text/OCR D&D supplement PDFs into
> Aurora-compatible XML with local deterministic parsing, review, validation,
> and export workflows.

Student Sherpa Light:

> Stakeholder-review prototype for a campus outreach/contact-management
> workflow, with requirements, assumptions, acceptance examples, and discovery
> planning.

The Book of Xellarant:

> Aurora-compatible content source that extends Aurora Lights and helped shape
> XML authoring and validation patterns used later in Aurora Constellations.

Wild Spirits:

> Visual novel project with GitHub Actions workflows for cross-platform alpha
> builds and tester-friendly prerelease distribution.

Idle Handz:

> Pop-culture and creative media hub for blogging, community updates, and
> public-facing storytelling outside the Aurora toolchain.

## Pinned Project Cards

### Aurora Lights

Modernizing a beloved legacy D&D character builder without breaking the
characters and content people already use.

**Role:** Application modernization, compatibility design, release workflow
support.

**Highlights:**

- .NET 10 MAUI / Blazor Hybrid client for desktop-first usage.
- Compatibility with existing `.dnd5e` files and Aurora XML content libraries.
- SQLite-backed content pipeline shared with modern builder workflows.
- Book of Xellarant content-source support, modeled from examples in
  `elements-1`.
- Windows installer/update path, with experimental Mac Catalyst and Android
  build targets.

**Tech:** C#, .NET 10, MAUI, Blazor Hybrid, SQLite, WPF compatibility, GitHub
Actions, Velopack.

### Aurora Translator

Turning Aurora's XML content ecosystem into a normalized, queryable runtime
layer while preserving source fidelity.

**Role:** Backend/data engineering, rules runtime design, CLI tooling,
regression safety.

**Highlights:**

- XML import into SQLite with source package and precedence handling.
- Expression parser shared between import-time and runtime requirements.
- Duplicate ID resolution, unresolved-link diagnostics, and source integrity
  checks.
- Character-state evaluator that emits application-facing choices, traits,
  effects, spellcasting profiles, warnings, and provenance.
- Regression baselines for first-party content and character-state fixtures.

**Tech:** C#, .NET 10, SQLite, XML, CLI tooling, data modeling, regression
fixtures.

### Aurora Constellations

Turning text/OCR supplement PDFs into editable Aurora-compatible XML without
requiring an external AI service.

**Role:** Browser tooling, deterministic parser design, XML generation,
validation workflow.

**Highlights:**

- Static browser app that extracts selectable PDF text locally.
- Deterministic parsers for spells, subclasses, items, feats, magic items,
  races, backgrounds, and classes.
- Review/edit workflow with Aurora shape validation before download.
- ZIP and single-file XML export paths for direct testing in Aurora.
- Parser patterns informed by hands-on Book of Xellarant content-source work
  and examples from `elements-1`.

**Tech:** JavaScript, Node.js scripts, PDF.js, JSZip, Vitest, Playwright, static
browser app, XML generation, Aurora XML validation, regression tests.

## Additional Work Cards

### Student Sherpa Light

Turning a rough campus outreach idea into a clickable review prototype and a
clear first-release requirements package.

**Role:** Product scoping, stakeholder communication, prototype design,
requirements framing.

**Highlights:**

- Review-only prototype for attention queues, searchable student records,
  ownership, contact timelines, events, team hierarchy, and mobile concepts.
- Concise stakeholder requirements brief with explicit assumptions, exclusions,
  open decisions, and acceptance examples.
- Google Workspace sign-in framed as an identity option while keeping roles,
  campuses, domains, groups, and allowlists as separate authorization decisions.
- Discovery and implementation paths described without treating the prototype
  as a production commitment.

**Tech:** Product prototyping, Next.js/static publishing, requirements writing,
Google Workspace planning, stakeholder discovery.

### The Book of Xellarant

An Aurora-compatible content source and direct plug-in for Aurora Lights,
modeled after real examples from the `elements-1` ecosystem.

**Role:** Content modeling, XML authoring, source compatibility, validation
feedback.

**Highlights:**

- Custom Aurora source/index files that can be consumed by Aurora Lights.
- XML structure modeled against existing `elements-1` content-source patterns.
- Practical authoring experience that exposed repeatable parser and validation
  needs later carried into Aurora Constellations.

**Tech:** Aurora XML, source indexes, content validation scripts.

### Wild Spirits

Building a visual novel project with a release process that supports early
testing across desktop and mobile targets.

**Role:** Project build automation, release packaging, tester distribution
workflow.

**Highlights:**

- Manual GitHub Actions workflows for Windows, macOS, Android, and iOS-oriented
  builds.
- Friend-facing alpha release workflow that creates cleaner prerelease assets.
- Android APK sharing path separated from store-oriented app bundle concerns.
- iOS workflow that generates an Xcode project and unsigned device-target app
  artifact for later signing work.

**Tech:** GitHub Actions, cross-platform build automation, release packaging,
Android/iOS build artifacts.

### Idle Handz

Maintaining a public creative/community hub for pop-culture writing, updates,
and digital storytelling.

**Role:** Site ownership, content direction, community-facing communication.

**Highlights:**

- Public site at [idlehandz.com](https://idlehandz.com/).
- Blog and update channel for community-oriented creative work.
- Useful counterweight to the engineering-heavy Aurora projects because it
  shows public-facing voice, audience awareness, and ongoing communication.

**Tech:** Website publishing, content strategy, community communication.

## README Introduction Drafts

### Aurora Lights

```markdown
## Portfolio Summary

Aurora Lights is a modernization effort for the legacy Aurora character
builder. The project preserves existing `.dnd5e` character files and Aurora XML
content libraries while moving the user experience toward a modern .NET 10
MAUI / Blazor Hybrid client.

From an engineering standpoint, the interesting work is the migration path:
keeping legacy workflows alive, introducing a SQLite-backed content pipeline,
sharing compatibility logic across clients, and shipping testable beta builds
with a practical installer/update story.
```

### Aurora Translator

```markdown
## Portfolio Summary

Aurora Translator is the data and runtime foundation behind the Aurora
modernization work. It imports Aurora Builder XML into a normalized SQLite
model, evaluates expression/rules behavior, and emits application-facing
character-state contracts for modern clients.

The project is intentionally compatibility-first: raw XML is preserved where
fidelity matters, relational projections support fast builder queries, and
regression baselines protect behavior as more rules and content families are
implemented.
```

### Wild Spirits

```markdown
## Portfolio Summary

Wild Spirits is a visual novel project with release automation designed for
early alpha testing. The repository includes manual GitHub Actions workflows for
building desktop and mobile-oriented artifacts, plus a friend-facing prerelease
flow that packages builds with clearer asset names.

The engineering focus is practical distribution: making it easy to produce test
drops, keeping Android installable APK sharing separate from store app bundles,
and leaving room for later iOS signing/TestFlight work without blocking early
feedback.
```

### Aurora Constellations

```markdown
## Portfolio Summary

Aurora Constellations is a static JavaScript browser tool, formerly Aurora XML
Helper, for turning text-based or OCR-processed D&D supplement PDFs into
Aurora-compatible XML. It extracts selectable PDF text locally with PDF.js,
applies deterministic parsers for supported element types, lets users review
and edit the generated records, validates Aurora XML shape, and exports
ready-to-test XML packages. Its Node.js tooling covers regression tests, local
serving, browser smoke checks, and corpus benchmark scripts.

The project grew out of hands-on content-source work in Book of Xellarant, where
real examples from `elements-1` helped clarify which XML patterns were stable
enough to generate and which needed human review.
```

## Case Study Drafts

### Aurora Lights Case Study

**Problem**

Aurora users have years of character files and XML content tied to a legacy
desktop application. A rewrite that ignored those files would strand the
existing community, but leaving the app untouched would make long-term
maintenance harder.

**What I Built**

Aurora Lights approaches the rewrite as a gradual modernization. The modern
client, Aurora Reflections, reuses the familiar storage model, preserves
existing content, and introduces a MAUI / Blazor Hybrid app backed by shared
logic and SQLite content infrastructure.

**Engineering Notes**

- Compatibility is treated as a product requirement, not an afterthought.
- The project keeps legacy and modern clients side by side while shared logic
  matures.
- Book of Xellarant provides a direct content-source plug-in and a practical
  test case for Aurora-compatible XML.
- Release workflows produce practical Windows beta builds and experimental
  cross-platform artifacts.

**Result**

The project gives Aurora users a bridge from the old desktop app toward a
modern client without requiring an immediate content migration.

### Aurora Translator Case Study

**Problem**

Aurora XML is both structured content and a rules DSL. A modern character
builder needs fast, queryable runtime data without losing the fidelity of the
source format.

**What I Built**

Aurora Translator imports Aurora XML into SQLite, resolves package precedence and
duplicates, parses requirements/support expressions, and evaluates character
state into contracts that an application can consume directly.

**Engineering Notes**

- Raw XML is retained where flattening would lose meaning.
- SQLite views expose app-facing surfaces for choices, effects, spellcasting,
  and content catalogs.
- Regression baselines protect first-party content behavior and character-state
  examples as the runtime grows.

**Result**

The project turns a legacy XML ecosystem into a builder-ready runtime layer
while keeping compatibility with existing authoring and distribution formats.

### Aurora Constellations Case Study

**Problem**

Aurora content authors often start from PDFs or OCR text, but hand-authoring
valid Aurora XML is slow and easy to get subtly wrong. A useful helper needs to
speed up the repetitive parts while preserving human review.

**What I Built**

Aurora Constellations runs as a static browser app. It extracts selectable PDF
text locally, applies deterministic parsers for supported D&D element types,
gives the user review/edit tabs, validates Aurora XML shape, and exports single
XML or ZIP packages.

**Engineering Notes**

- Parsing is deterministic and local instead of model-dependent.
- Node.js scripts support Vitest regression coverage, browser smoke checks,
  corpus benchmarking, dependency vendoring, and static serving.
- The review step is treated as part of the product, not a failure mode.
- Book of Xellarant and `elements-1` examples helped identify repeatable XML
  shapes, source/index conventions, and validation rules.

**Result**

The project gives Aurora content work a faster authoring loop while keeping
the final XML visible, editable, and compatible with Aurora Lights.

## Additional Work Case Study Drafts

### Wild Spirits Case Study

**Problem**

Early game projects need a lightweight path from development to tester builds.
Manual packaging is easy to forget, while production-grade app store release
work is too heavy for early alpha feedback.

**What I Built**

Wild Spirits uses GitHub Actions workflows to produce desktop and mobile
artifacts on demand. A dedicated alpha release workflow creates friend-facing
prerelease assets, including an installable Android APK for easier sharing.

**Engineering Notes**

- Build workflows are manual so releases happen intentionally.
- Mobile signing concerns are documented and separated from alpha sharing.
- Tester asset names are cleaner than raw build outputs.

**Result**

The project has a repeatable path for sharing alpha builds without pretending
the game is already ready for store distribution.
