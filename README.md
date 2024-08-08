# e2e-consumer-ruleset-workflow-public
This internal repo workflow aims to test Immutable Actions imposed by a ruleset

These are derived from the workflows in the [e2e-public-repo](https://github.com/immutable-actions/e2e-test-consumer-public) and are configued in the org settings. 

In order to fully test ruleset workflows, you must open a pr, which in turn verifies all the various bits and bobs kick off. 

Some of the tests *should* fail, this is by design. As of the time of this writing: 

- Consume Actions from a Tomstoned Package
- Consume Actions from Packages (internal and private) 
- Consume Inaccessible Package Actions
- Test no fallback to Repos for Semver tags

Are all expected to fail. d
