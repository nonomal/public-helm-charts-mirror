# public-helm-charts-mirror

![Sync](https://github.com/DaoCloud/public-helm-charts-mirror/raw/gh-pages/daocloud-sync-badge.svg)

This repository contains Helm charts served by DaoCloud

| Helm RepoName      | Helm Repo URL |
| ----------- | ----------- |
| Addon      | https://release.daocloud.io/chartrepo/addon       |
| System   | https://release.daocloud.io/chartrepo/system        |
| Partner  | https://release.daocloud.io/chartrepo/partner        |
| Community  | https://release.daocloud.io/chartrepo/community      |

# Usage

`````````
helm repo add community https://release.daocloud.io/chartrepo/community 
helm install dao-2048 community/dao-2048
`````````

# Add New Repo/Charts

Create New PR , like https://github.com/DaoCloud/public-helm-charts-mirror/pull/2

Example:

  If your helm chart repo URL `is https://release.daocloud.io/chartrepo/community/dao-2048`
  you can add one line to mirror.yaml : `dao-2048: https://release.daocloud.io/chartrepo/community`
