# Template Repository for Chainguard Images

This repository provides a template from which all images provided by the
[https://github.com/chainguard-images](Chainguard Images organization)
org should be based upon. It includes important workflows and common configuration that
are required for integration into our process and workflows.

## Image Configuration

To add a new image distribution to the chainguard-images org, create its repository
by clicking on the
"[Use this template button](https://github.com/chainguard-images/template/generate)".
This will create a new repository using the files contained here.
For more information about all the apko configuration options, please check
the documentation and the [examples](https://github.com/chainguard-dev/apko/tree/main/examples).

## Image Readme

This README.md will be overwritten automatically upon successful build using
[readme-generator](https://github.com/chainguard-images/readme-generator).

Note: the "Usage" section in the README will be populated by the contents of
 [`USAGE.md`](./USAGE.md). For more details on how the README is generated,
 please see the readme-generator
 [README](https://github.com/chainguard-images/readme-generator/blob/main/README.md).

## Release Workflow

By default, the new repository will contain a
[release workflow](.github/workflow/release.yaml) that builds and publishes the
image every day at midnight.
