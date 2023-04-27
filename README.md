This repository uses a YAML file to generate custom NDcPPv.3.0 test plans. Each v3.0 directory includes a set of .adoc files with each SFR's evaluation activities. You can delete any .adoc files you don't want included in your test plan. You can then run the GitHub Action to generate your custom test plan.

Follow the steps below to generate a custom test plan:

1. Select the 'Use this template' button (must be logged in), create a new repository, don't include all branches.
2. Check your repository permissions by going to Settings> Actions> General> WorkFlow permissions> select 'Read and write' permissions> save.
3. Delete any .adoc SFRs files from the v3.0 directories that you do not want included in your test plan. There are multiple ways to execute this step, (i.e., Git CLI, your local repository, in your browser).
4. Select the 'Actions' button from the menu.
5. Select the 'Combine Asciidoc, Convert to HTML, and Commit' workflow.
6. Select 'Run workflow'. You can watch the status of the workflow as it runs (30 to 60 seconds typically).
7. Return to your branch's main page and download the 'combined-testplan.adoc' and/or 'testplan.html' documents.

NOTE: It's recommended that you creating a new branch for each custom test plan you want to generate.
