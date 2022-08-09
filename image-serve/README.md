# gcs-bucket

## Description
kpt package for provisioning Google Cloud Storage

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] gcs-bucket`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree gcs-bucket`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init gcs-bucket
kpt live apply gcs-bucket --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
