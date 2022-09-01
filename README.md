# managed-accelerators

In `tap-values.yaml` configure:

```
accelerator:
  managed_resources:
    enable: true
    git:
      url: https://github.com/trisberg/managed-accelerators
      ref: origin/main
      sub_path: resources
      secret_ref: null
```