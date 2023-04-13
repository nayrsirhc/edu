---
date: 2023-04-11T16:56:59Z
title: "chainctl iam identity-providers list"
slug: chainctl_iam_identity-providers_list
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_iam_identity-providers_list/
draft: false
tags: ["chainctl", "Reference", "Product"]
images: []
type: "article"
toc: true
---
## chainctl iam identity-providers list

List identity providers.

```
chainctl iam identity-providers list [--output table|tree|json]
```

### Examples

```
  # List identity providers
  chainctl iam identity-providers list
```

### Options

```
  -h, --help   help for list
```

### Options inherited from parent commands

```
      --api string                   The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string              The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string                A specific chainctl config file.
      --console string               The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string                The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string                Output format. One of: ["", "table", "tree", "json", "id", "wide"]
      --timestamp-authority string   The url of the Chainguard Timestamp Authority endpoint. (default "http://tsa.timestamp-authority.svc")
  -v, --v int                        Set the log verbosity level.
```

### SEE ALSO

* [chainctl iam identity-providers](/chainguard/chainguard-enforce/chainctl-docs/chainctl_iam_identity-providers/)	 - customer managed identity provider management
