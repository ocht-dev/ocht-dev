### Various projects for OCHT data migration and manipulation

<!--
**ocht-dev/ocht-dev** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->

Current projects:

cx_migration_db - all objects in the CX_MIGRATION database scripted as individual files

Loc8DataFetcher - a .Net5 / C# xconsole app for fetching Lo8 data from the API (see the README for meore details)

SSRS_reports - an archive of SSRS reports (.rdl files) pointing at the CxWarehouse and CxBI databases on the OCHT CX reporting server

cx_chrome_extension - a Chrome extension intended to provided additional functionality on the CX web app. It could be used for integrations between C and other external systems, e.g., dynamically adding a button to a CX asset page that shows photos from an external database relating to that asset (linked via a CX asset reference). Very much a work in progress (see the README for more details)

CxWarehouseChecker - a .Net5 / C# console app that tries to connect to the CxWarehouse database every 10 minutes and logs the result (was previously useful to get a history of when the database was available when it was going down frequently)

CxLookupUpdater - a .Net5 / C# to read Excel files in a directory containing exported CX general lookup data and updating a copy of that data in the CX_MIGRATION database (useful for data migration)

cx_migration - a collection of various python scripts for doing data manipulation that is not easy to do in SQL 




