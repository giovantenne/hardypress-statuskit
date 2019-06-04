+++
title = "Deploys unable to invalidate the CDN cache"
date = 2019-06-04T18:06:21.000Z
severity = "degraded-performance"
affectedsystems = [
  "CDN"
]
resolved = false
+++
Our CDN partner is experiencing an issue with the database server which is causing the API to not responding. The HardyPress dashboard reports deployments as failed, but the cache will be automatically invalidated as soon as the issue is resolved on the CDN side.