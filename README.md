# Genesis · Municipal Website

The independent municipal portal for **Project Genesis**, a fictional city on the Lakeland map in *Cities: Skylines II*. It is unrelated to the prior Meridian Minecraft world.

## Website sections
- **Overview**: Founding story, civic priorities, last verified city-clock snapshot and optional simulated ticker.
- **Government**: Mayor Elias Mercer, the five Founder-appointed founding council members, their independent ChatGPT plugins, responsibilities, remote status, and expected June 2026–June 2030 term.
- **Projects**: Expandable electrical infrastructure milestone (GEN-INF-001/002), estimated timeline, quoted costs vs verified treasury figures, contractor roster, commissioning to-do list and five genuine Founder-supplied photo previews with a viewer.

## Timeline and accuracy
The game clock runs from 0 to 24 per in-game month. Last reported position is **June 2026, hour 14/24** (roughly June 18). Website ticker controls operate a **demonstration only**, not live in-game synchronization. It does not advance the actual project timeline or change any stored record.

The founding June treasury was **$6,250,000**, later reported balance **$6,216,612**. The **$33,388 change** is citywide, not an itemized project invoice. The first electrical works were physically **completed** but remain **uncommissioned** and the transformer is off.

The photo assets in `assets/photo-data.js` and `assets/photo-data-extra.js` are web-optimized reductions of the Founder's five real captures, **not** generated images. Full-resolution originals appear in the completed archival PDF in the Founder's private Google Drive **Finalized Projects** folder. No public access is implied.

## Site structure
- `index.html`: semantic static page with three tabs
- `assets/site.css`: responsive dark civic theme
- `assets/site.js`: client-only navigation, expandable project viewer and demonstration clock
- `assets/photo-data.js` + `assets/photo-data-extra.js`: embedded original-photo preview data

No framework, API credentials, build tools or external service dependencies are required. Google Fonts are optional. This is committed to a **private GitHub repository**, not yet hosted as a public site.

## Governance
The Founder retains reserved approvals for major construction and foundational policies. Mayor Mercer (GEN-AGT-001) manages municipal strategy and the City Council (GEN-AGT-002 through GEN-AGT-006) provides independent scrutiny. Members were **appointed**, not elected, while city population is zero. June 2030 mayoral re-election is expected, but detailed electoral procedures and the formal charter require ratification. The Council's president has not yet been elected.

Official city finance, governance and agent records are kept in separate Genesis Airtable bases. The site is a curated static snapshot, not a live ledger or inter-agent automation system.

## Hosting
The site is ready for review in the repository. Publishing via a hosting service or GitHub Pages is a distinct Founder-authorized step; private repository settings and access rules should be reviewed first.
