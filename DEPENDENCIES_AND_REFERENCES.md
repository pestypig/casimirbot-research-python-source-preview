# Dependency and upstream-reference review — private draft

This note covers the exact 359-file Python union in `SOURCE_SELECTION.json`, formed from the retained 345-file and 14-file inventories. It is a bounded static review, not a complete dependency lock, copied-code clearance, safe-run instruction, or scientific result. No external package, paper, dataset, observation, credential, or fetched upstream source is bundled.

## Python and data dependencies

Selected imports include NumPy, SciPy, mpmath, SymPy, h5py, Matplotlib, Astropy, pytest, `wilson`, `darkelf`, and `nuflux`. The isolated draft has no independently established dependency closure or supported execution environment. Many files read local configurations, tables, or earlier research outputs that are not in this selection. Their source visibility does not reproduce an analysis or validate an observation.

## Pinned WIMpy path

`docs/research/casimir-dp-spin-response-intake-2026-09-06.py` names four files in `bradkav/WIMpy_NREFT` at commit `50581c637069305a3def3865462ef1b4ed9a616d`, including `LICENSE.md`; if run, it fetches missing files from GitHub and checks their pinned SHA-256 hashes. `docs/research/casimir-dp-l10-joint-kernel-2026-09-06.py` and `docs/research/casimir-dp-axion-joint-spin-2026-09-07.py` read the resulting WIMpy Python files and compile selected function definitions. No such fetch or execution occurred during this review. The [upstream license at that exact commit](https://github.com/bradkav/WIMpy_NREFT/blob/50581c637069305a3def3865462ef1b4ed9a616d/LICENSE.md) is MIT, copyright Bradley J. Kavanagh. A future operator must retain its notice with any obtained upstream copy and review the runtime behavior before using these scripts. This draft contains the first-party intake and consumer source only; it does not redistribute WIMpy files.

## URLs and provenance limits

A bounded sweep found 108 `http(s)`-shaped strings in 72 files, largely paper links to arXiv, plus GitHub/API, NIST, Zenodo, DataCite, particle-data, and other research references. No parsed URL included userinfo or a query-parameter name containing `key`, `token`, `secret`, `password`, or `auth`. This does not inspect dynamic URLs, other credential forms, remote content, or the rights to referenced material. A word-boundary text search found no selected file with an explicit copyright, SPDX, adapted-from, ported-from, or copied-from cue; absence is not proof of independent authorship.

The original 24-file hold is now split: 14 parseable Python files were recovered after their email-shaped `@` matches proved to be matrix operators; the ten remaining files are byte-identical archives from QCDark2 (CC0), WIMpy (MIT with Bradley J. Kavanagh's notice), and nuflux (LGPL v3). Those ten are excluded from this first-party candidate and should be referenced through their pinned upstream projects. Any first-party MIT license, third-party notices, public exposure, and scientific claim must be decided against the exact final tree after owner rights and content review. Publishing source alone would not execute or advance an NHM2 proof gate, establish physical viability, or authenticate research data.
