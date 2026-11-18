# Chocolate Sales Power BI Dashboard

This repository contains the Power BI dashboard supplied as `BI DASH CHOCO.pbix`,
along with the report-definition JSON and static resources embedded in that file.

## Contents

- `BI DASH CHOCO.pbix` — original Power BI report file (includes its embedded data model).
- `powerbi-source/definition/` — report definition, page definitions, and visual configuration extracted from the PBIX.
- `powerbi-source/StaticResources/` — report images and shared theme resources.

## Open the dashboard

1. Download or clone this repository.
2. Open `BI DASH CHOCO.pbix` in Microsoft Power BI Desktop.
3. If Power BI prompts for data-source credentials or a refresh, configure the required access in Power BI.
4. To publish the report, use **Home → Publish** in Power BI Desktop and select your Power BI workspace.

## About the source files

The `powerbi-source` folder is a companion copy of the report-definition assets found inside the
provided PBIX. The `.pbix` remains the primary, ready-to-open report. The embedded semantic model
is retained inside the PBIX; it has not been converted into separate editable model source files.

## GitHub

The PBIX is approximately 1.5 MB, below GitHub's 100 MB per-file limit for regular Git repositories.
You can upload the ZIP contents through **Add file → Upload files**, or clone the repository and commit them.

## File provenance

The dashboard file was provided as `BI DASH CHOCO.pbix`. No external data or credentials were added.
