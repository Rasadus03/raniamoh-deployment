# gke-clone

## Description
gke-clone description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] gke-clone`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree gke-clone`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init gke-clone
kpt live apply gke-clone --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
