# pivota-e2e-fixture

Test fixture for Pivota's end-to-end suite. **Not a real project.**

Pivota derives phases from `.planning/ROADMAP.md`, read from a project's git
remote. The e2e seed points a project at this repository so phases — and
therefore kanban cards — exist deterministically.

Read-only from Pivota's perspective. Changing `.planning/ROADMAP.md` changes what
the suite sees, so treat edits as changes to test fixtures.
