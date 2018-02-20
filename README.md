# Relase Checklist
These steps should be performed when making a new release.

## Pre-release Test Checklist
- [ ] Does the build pass on the CI server?
- [ ] Have the changelog and README been updated?
- [ ] Have all the version numbers been incremented?
- [ ] Has all new functionality been manually tested on a release build?
- [ ] Do the installation instructions work when creating an example app from scratch?
- [ ] Have the installation instructions been updated on the [dashboard](https://github.com/bugsnag/bugsnag-website/tree/master/app/views/dashboard/projects/install) as well as the [docs site](https://github.com/bugsnag/docs.bugsnag.com)?
- [ ] Have all Docs PRs been merged?

### Network Tests
- [ ] If a response is not received from the server, is the report queued for later?
- [ ] If no network connection is available, is the report queued for later?
- [ ] On a throttled network, is the request timeout reasonable, and the main thread not blocked?
- [ ] Are queued reports sent asynchronously?

## Post-release Test Checklist
- [ ] Do the installation instructions work using the released artefact?
- [ ] Can a freshly created example app send an error report from a release build, using the released artefact?
- [ ] Do the existing example apps send an error report using the released artefact?
