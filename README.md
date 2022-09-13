### Various projects for OCHT data migration and manipulation

<!--
**ocht-dev/ocht-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Current projects:

cx_migration_db - all objects in the CX_MIGRATION database scripted as individual files

Loc8DataFetcher - a .Net5 / C# xconsole app for fetching Lo8 data from the API (see the README for meore details)

SSRS_reports - an archive of SSRS reports (.rdl files) pointing at the CxWarehouse and CxBI databases on the OCHT CX reporting server

cx_chrome_extension - a Chrome extension intended to provided additional functionality on the CX web app. It could be used for integrations between C and other external systems, e.g., dynamically adding a button to a CX asset page that shows photos from an external database relating to that asset (linked via a CX asset reference). Very much a work in progress (see the README for more details)

CxWarehouseChecker - a .Net5 / C# console app that tries to connect to the CxWarehouse database every 10 minutes and logs the result (was previously useful to get a history of when the database was available when it was going down frequently)

CxLookupUpdater - a .Net5 / C# to read Excel files in a directory containing exported CX general lookup data and updating a copy of that data in the CX_MIGRATION database (useful for data migration)

cx_migration - a collection of various python scripts for doing data manipulation that is not easy to do in SQL 




