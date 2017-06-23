### this is a DUMMY RELEASE REPO used by the dedicated-mysql team's PCF tile Concourse pipeline

Original README.md of forked repo is below

------------------------------------------

# Zookeeper BOSH release

Uses BOSH [links](https://bosh.io/docs/links.html) as an example.

# Useful commands

```
$ bosh -d zookeeper run-errand smoke-tests
$ bosh -d zookeeper ssh -c '/var/vcap/jobs/zookeeper/bin/ctl status' -r
```
