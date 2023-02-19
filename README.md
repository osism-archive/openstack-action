# openstack-action

**We have migrated from GitHub Actions to Zuul CI and no longer maintain this action.**

Our Devstack job for Zuul CI is available in https://github.com/osism/zuul-jobs.

GitHub Action for running OpenStack services as part of your workflows.

## Usage

```yaml
jobs:
  openstack:
    runs-on: ubuntu-latest
    steps:
      - uses: osism/openstack-action@main
        with:
          release: yoga
          services: keystone
```
