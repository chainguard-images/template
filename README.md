# Chainguard Images Template

This repo provides a basic template for a Wolfi-based image configured using
[apko](https://apko.dev).

After [creating your own repo from this
template](https://github.com/chainguard-images/template/generate), edit
`apko.yaml` to add or remove whatever packages you need.

The template includes two GitHub Actions workflows:

- [run a presubmit build](./.github/workflows/pre-submit.yaml) when a pull
  request is opened
- [publish a new image](./.github/workflows/release.yaml) when changes are
  pushed to `main`.
  - Images are pushed to `ghcr.io/$ORG/$REPO`, tagged with the date the image
    was published (e.g., `:20230103`).
  - Images are signed using the GitHub Actions' workload identity (`cosign
    verify <image>`).
  - Images have an SBOM attached (`cosign download sbom <image>`).
  - Images are scanned for vulnerabilities using Trivy, and signed
    vulnerability attestations are attached (`cosign download attestation
    <image>`). You can enable scanning with Grype and Snyk as well.
  - Images are also rebuilt nightly to pick up Wolfi package updates.
