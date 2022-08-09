# managed-accelerators

```
managedAccelerators:
  include: true
  git:
    url: https://github.com/sample-accelerators/managed-accelerators
    ref: origin/main
    secretRef:
      name: secret-name
    subPath: resources
  image:
    url: host.com/username/image:v0.1.0
    secretRef:
      name: secret-name
    subPath: resources
  imgpkgBundle:
    image: host.com/username/image:v0.1.0
    secretRef:
      name: secret-name
```
