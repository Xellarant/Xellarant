# Xellarant

I build practical .NET applications, JavaScript/Node.js tooling, migration
systems, and release workflows for projects with real domain complexity.

My recent work has focused on the Aurora Lights Suite: modernizing a legacy
tabletop character builder, turning XML-heavy content systems into queryable
SQLite runtimes, building browser-local authoring tools, and shipping
cross-platform builds that people can actually test.

I also enjoy the communication side of software: helping turn rough ideas,
constraints, and wish lists into shared language, realistic scope, and concrete
deliverables that solve the underlying problem.

[Portfolio](https://xellarant.github.io/)

## Featured Projects: Aurora Lights Suite

The main showcase projects are related pieces of the Aurora Lights Suite for
tabletop character creation, content authoring, data migration, and
character-management workflows.

### Aurora Reflections

Modern MAUI / Blazor Hybrid client within Aurora Lights Suite.

- Builds the user-facing desktop-first character-management experience.
- Preserves existing `.dnd5e` character files and Aurora XML content libraries.
- Uses a SQLite-backed compendium and compatibility layer for a gradual
  migration path.
- Supports content-source work such as Book of Xellarant, modeled after
  `elements-1` examples.
- Includes Windows installer/update flow plus experimental Mac Catalyst and
  Android build targets.

[Repository](https://github.com/Idle-Handz/Aurora-Lights)

### Aurora Transpositions

Backend migration and runtime tooling for Aurora Builder content,
provisionally renamed from Aurora Translator.

- Imports Aurora XML into a normalized SQLite model.
- Preserves raw XML where fidelity matters while exposing builder-facing query
  surfaces.
- Includes expression parsing, package precedence handling, duplicate ID
  resolution, diagnostics, and regression baselines.
- Evaluates character state into application-facing contracts for choices,
  effects, spellcasting, traits, warnings, and provenance.

[Repository](https://github.com/Xellarant/AuroraTranslator)

### Aurora Constellations

Browser-based tool, formerly Aurora XML Helper, for converting text/OCR D&D
supplement PDFs into Aurora-compatible XML.

- Extracts selectable PDF text locally in the browser.
- Uses deterministic parsers for supported D&D element types.
- Provides review/edit tabs, Aurora shape validation, and ZIP/XML export.
- Uses Node.js scripts for Vitest regression coverage, local serving, browser
  smoke checks, vendoring, and corpus benchmarks.
- Grew from hands-on content-source work in Book of Xellarant and patterns from
  `elements-1`.

[Live app](https://xellarant.github.io/AuroraXMLHelper/) |
[Repository](https://github.com/Xellarant/AuroraXMLHelper)

## Technical Focus

- C# and .NET application development
- JavaScript browser tooling, Node.js automation scripts, PDF.js, Vitest, and
  Playwright smoke coverage
- MAUI, Blazor Hybrid, WPF modernization, and cross-platform packaging
- SQLite schema design, content import pipelines, and data integrity checks
- XML parsing, rules evaluation, compatibility layers, and regression fixtures
- GitHub Actions release workflows and practical tester distribution

## Related Ecosystem Work

- **Student Sherpa Light:** Stakeholder-review prototype for campus outreach
  and contact management, paired with requirements, assumptions, acceptance
  examples, and discovery planning.
- **The Book of Xellarant:** Aurora-compatible content source and direct plug-in
  for the Aurora Lights Suite, with XML patterns modeled from `elements-1`.
- **Wild Spirits:** Private visual novel project with GitHub Actions workflows
  for friend-facing alpha builds and cross-platform tester artifacts.
- **Idle Handz:** Pop-culture and creative media hub for blogging, community
  updates, and public-facing storytelling.

## What I Like Building

I enjoy projects where the work is more than a clean-room CRUD app: migration
paths, messy legacy data, compatibility contracts, domain rules, and tooling
that helps a real community keep using software they already care about. The
best version of that work usually starts with listening carefully, naming the
real problem, and making the next deliverable clear enough to build.
