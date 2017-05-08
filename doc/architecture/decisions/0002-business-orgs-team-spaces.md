# 2. Scope Orgs to Business Units and Spaces to Teams

Date: 2017-05-04

## Status

Draft

## Context

Things scoped to Space:

- Service instances
- Quotas on
  - paid services
  - total services
  - total service keys
  - total routes
  - total reserved route ports
  - total memory
  - instance memory
  - total app instances
- Access controls for roles:
  - Manager – assign
  - Developer
  - Auditor

Things scoped to Organization:

- Quotas on everything from Spaces, plus
  - total private domains
- Access controls for roles:
  - Manager – view and assign quotas, roles; create and manage spaces, quotas
  - Auditor – view org quotas, roles
  - Billing manager – view org quotas, roles, utilization metrics

[1]: http://apidocs.cloudfoundry.org/258/organization_quota_definitions/creating_a_organization_quota_definition.html
[2]: http://apidocs.cloudfoundry.org/258/space_quota_definitions/creating_a_space_quota_definition.html
[3]: https://docs.cloudfoundry.org/concepts/roles.html
[4]: http://cloud.rohitkelapure.com/2016/05/structuring-orgs-spaces-and-quota.html

## Decision

Decision here...

## Consequences

Consequences here...
