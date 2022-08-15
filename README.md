# openstack-action

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
