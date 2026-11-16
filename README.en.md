🇧🇷 [Português](README.md) | 🇺🇸 English

# Regression testing — Urban Routes

Sprint 1 project from the TripleTen QA Engineer program: regression testing of **Urban Routes**, a web maps and routes app, and documentation of the bugs found.

## Goal

Make sure the new version of Urban Routes did not introduce regressions in the main map features: navigation, zoom, address search, view modes (Map, Terrain, Satellite, Street View, full screen) and object display.

## What was done

- Executed **24 pre-written regression test cases**.
- Recorded the result of each case (Passed / Failed).
- Wrote **9 bug reports** for the failed cases, with title, steps to reproduce, expected result, actual result and priority.

## Results

| Metric | Total |
|---|---|
| Test cases executed | 24 |
| Passed | 15 |
| Failed | 9 |
| High-priority bugs | 6 |
| Medium-priority bugs | 1 |
| Low-priority bugs | 2 |

### Main bugs found

- The list of subway stations does not appear when searching "Subway" in the "To" field (High).
- The address pin does not appear after filling in the "From" and "To" fields (High).
- App information does not appear when clicking the Urban Routes logo (High).
- The zoom level changes when full-screen mode is turned on (Medium).
- Map area titles are clickable when they should not be (Low).

## Files

- [`casos-de-teste-e-bugs-urban-routes.xlsx`](casos-de-teste-e-bugs-urban-routes.xlsx): spreadsheet with two tabs (in Portuguese):
  - **Test cases**: ID, name, precondition, steps, expected result, status and bug ID.
  - **Bug reports**: ID, title, steps to reproduce, expected result, actual result and priority.

## What I learned

In this first project I learned essential skills for manual UI testing:

- **Smoke testing:** testing new software features.
- **Regression testing:** making sure software changes do not introduce new errors.
- **Bug reporting:** writing complete reports that describe software problems, with steps to reproduce, expected result, actual result and priority.
