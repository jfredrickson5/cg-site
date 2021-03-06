---
menu:
  docs:
    parent: experimental
title: Experimental services
slug: services
aliases:
- /docs/services/uaa-auth
---

[**This is an experimental feature.**]({{< relref "docs/apps/experimental/experimental.md" >}})

Here are experimental services we've released to get feedback. Use them at your own risk. Don't use them for production, since they may be unreliable, not tested, or stop being available.

To enable any of these services, [ask support]({{< relref "docs/help.md" >}}). 

### Elasticsearch and Redis

Elasticsearch and Redis are available in the `cf marketplace`, and they can be instantiated for your application. You can see the plans and their information in the marketplace. To create an instance, you can use:

{{% eastwest %}}
```sh
cf create-service elasticsearch-swarm-1.7.5 1x mysearch
```

or

```sh
cf create-service redis28-swarm standard myredis
```
{{% /eastwest %}}

{{% govcloud %}}
```sh
cf create-service elasticsearch24 1x mysearch
```

or

```sh
cf create-service redis28 standard myredis
```
{{% /govcloud %}}
