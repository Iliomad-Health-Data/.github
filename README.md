# Organization Defaults


### GitHub Actions


###### Available actions
- [build-push](/.github/actions/build-push/action.yml)
- [deploy-ecs](/.github/actions/deploy-ecs/action.yml)
- [notify-teams](/.github/actions/notify-teams/action.yml)
- [quality-control](/.github/actions/quality-control/action.yml)
- [setup-ecr](/.github/actions/setup-ecr/action.yml)
- [setup-local](/.github/actions/setup-local/action.yml)
- [setup-terraform](/.github/actions/setup-terraform/action.yml)
- [version](/.github/actions/version/action.yml)

###### Testing actions

[`act`](https://github.com/nektos/act) must be installed in order to test GitHub actions locally

```bash
brew install act
```

_See [configuration](https://github.com/nektos/act#configuration)._