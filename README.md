# Relase Checklist
These steps should be performed when making a new release.

## Pre-release Test Checklist
- [ ] Does the build pass on the CI server?
- [ ] Have the changelog and README been updated?
- [ ] Have all the version numbers been incremented?
- [ ] Has all new functionality been manually tested on a release build?
- [ ] Do the installation instructions work when creating an example app from scratch?
- [ ] Have the installation instructions been updated on the dashboard as well as the docs site?
- [ ] Have all Docs PRs been merged?

## Post-release Test Checklist
- [ ] Do the installation instructions work using the released artefact?
- [ ] Can a freshly created example app send an error report from a release build, using the released artefact?
- [ ] Do the existing example apps send an error report using the released artefact?
