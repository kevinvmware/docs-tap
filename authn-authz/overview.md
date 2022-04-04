# Overview

Tanzu Application Platform 1.1 includes:

- Documentation for [Integrating with your Existing Identity Management Solution](integrating-identity.md).
- Five new default roles to help you set up permissions for users and service accounts within a namespace on a cluster that runs one of the Tanzu Application Platform profiles.
- Tanzu Application Platform `rbac` [CLI plug-in](binding.md) for role binding.
- Documentation for [Logging in using Pinniped](pinniped-login.md).

## <a id="default-roles"></a> Default roles

Three of these roles are for users, including:

- app-editor
- app-viewer
- app-operator

The following roles are for service accounts associated with the Tanzu Supply Chain:

- workload
- deliverable

The default roles provide an opinionated starting point for the most common permissions that the users need when using Tanzu Application Platform. However, with [Kubernetes RBAC documentation](https://kubernetes.io/docs/reference/access-authn-authz/rbac/), you have flexibility in creating customized roles and permissions that better meet your business needs. VMware Tanzu Application Platform default roles are built by using aggregated cluster roles.

The default roles are installed with every Tanzu Application Platform profile. For an overview of the different roles and their permissions, see [Role Descriptions](role-descriptions.md).

## <a id="work-with-roles"></a>Working with roles using the `rbac` CLI plug-in

For more information about working with roles, see [Bind a user or group to a default role](binding.md).

## <a id="add-info"></a>Additional Information

-SCA scanning results](sca-scanning-results.md)