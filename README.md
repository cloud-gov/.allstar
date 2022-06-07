# Allstar configuration for cloud-gov

[Allstar](https://github.com/cloud-gov/allstar) is a security-policy GitHub app. It is
installed on this org, and this repo contains the configuration for that app. It
is configured to create issues on repos that do not comply with the configured
policy.

## Enabled Repos

Allstar is configured in opt-in. [See here for the list of enabled repos](allstar.yaml). Feel
free to submit a PR to enable/disable repos.

## Policy Configuration

These are the expected settings to be in compliance

### [Branch Protection](branch_protection.yaml)

| | |
| - | - |
| Branches enforced | default |
| Require approval | yes |
| Approvals required | 1 |
| Dismiss stale reviews | yes |
| Block force push | yes |

### [Outside collaborators](outside.yaml)

| | |
| - | - |
| Outside collaborators can have push access | false |
| Repos with no admins allowed? | false |
