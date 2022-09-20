---
date: 2022-08-29T10:58:14-04:00
title: "chainctl events subscriptions delete"
slug: chainctl_events_subscriptions_delete
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_events_subscriptions_delete/
draft: false
images: []
type: "article"
toc: true
---
## chainctl events subscriptions delete

Delete a subscription.

```
chainctl events subscriptions delete SUBSCRIPTION_ID [--yes] [--output id] [flags]
```

### Options

```
  -h, --help   help for delete
  -y, --yes    Automatic yes to prompts; assume "yes" as answer to all prompts and run non-interactively.
```

### Options inherited from parent commands

```
      --api string        The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string   The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string     A specific chainctl config file.
      --console string    The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string     The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string     Output format. One of: ["", "table", "tree", "json", "id", "wide"]
```

### SEE ALSO

* [chainctl events subscriptions](/chainguard/chainguard-enforce/chainctl-docs/chainctl_events_subscriptions/)	 - Subscription interactions.
