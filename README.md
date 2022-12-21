# release-to-other-repo-to-demo

This is the `to` repo

This repo is responsible for providing a place for releases.

The repo will provide the secret for `from` repo. And the `from` repo will build artifacts and publish the releaes to `to` repo. The action `building artifacts` and `publish releases` are all happened in the `from` repo github workflow. The `from` repo only needs to provide a secret key to `to` repo.
