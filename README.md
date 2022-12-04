# template

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/chainguard-images/template/actions/workflows/release.yaml/badge.svg)](https://github.com/chainguard-images/template/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/template:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `latest` | `sha256:29e31866b96853a0da9eb48205df0dd01d9bb49d092e719ad6363ad960f651ea`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:29e31866b96853a0da9eb48205df0dd01d9bb49d092e719ad6363ad960f651ea) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


## Usage

WORK IN PROGRESS


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/template:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/template:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/template"
      },
      "image": {
        "docker-manifest-digest": "sha256:29e31866b96853a0da9eb48205df0dd01d9bb49d092e719ad6363ad960f651ea"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "7c6c469ba11a0eae335fe9090af68273116bd050",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCwXOMwCZshNKVmT6S4rEbTsS9qG3n1F5pjLLx5c7ZoJQIgfHlmvFf03IJYj855etvCJybLIaKiis+ydl+zqAknUXA=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIxMzBhN2I5MGNhY2ZjNTY0ZDExMjRjM2E5ZDk0ZDQ2YTRjY2ZlODVlOWQ2ODViZWM1Y2RlZjJmMmI5NTRmZmMxIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQkIxQnVQOGZGYXp5TkpTMEx6RjZKbDF2N25FVXRRdDBNemR6Mk81ODdnSUFpRUF1ejQweXJiZjN4aUZCVFVyQVhaQkxWenhpZlRsY25UYTlCUVBYcm85YVMwPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlSRU5EUVhwWFowRjNTVUpCWjBsVlkwSkNLMVpSUmxGa2FEUlBSVWg1YVU5WFFWSk9ka2h5UkU0NGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVRCTlJFRjVUV3BSZDFkb1kwNU5ha2w0VFdwQk1FMUVRWHBOYWxGM1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZJVGtKMlZqQkpaVGxoYm1GWVUyTTFjM1ZOVnpkNE9URnhhVTVzYkV0R1RFRnJNMFVLT0ZOWk4weHlhV05ZV0hocFNEZDNSM1I0VDBoNE9VWlNRVlUzV2pGTGNXNUtkM0J2VTFGVlRuZGFNVVk0WjNrM0wwdFBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYyUW1SU0NuUlVORVJXYTJWTk5HcHlRa3htVGxGWGNVVXpkU3QzZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpOWmVscHFUa1JaTlZsdFJYaE5WMFYzV2xkR2JFMTZUVEZhYlZVMVRVUnJkMWxYV1RKUFJFa3pDazE2UlhoT2JVcHJUVVJWZDAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE9jVVJtUm5OQlFVRlJSRUZGWTNkU1VVbG5VbWRuVTI5cVV6TUtZMDAxY20xclpYSk9hRlV6YjJkdGVVcFhjRGgzU204dlVrTklOMkZIT0d0V1JWVkRTVkZEWlVkSVNWWmxNV1ZhU1dodVQyRm5RaTlVWVc1dGIyNVNZZ3BCVVVKUk1FbGtabWxTUWpkbGRTODVlV3BCUzBKblozRm9hMnBQVUZGUlJFRjNUbXhCUkVKcFFXazFlVWR4UlZOQ1p6RjFNa2RRY1VSSFNtSkxXa1JyQ25Sb2RGbDNXWEF3WlNzMVN6WlJTU3RaVEZwcGFXb3JkSFpMV21RMVkxWnBLMDk1T0RSblNGbEJha0ZXVWpSd2MwTmhaWE5vVDNkU05GYzFZMEZXY1VjS05HSXlXRnBxZFdSUlRHZzViMkpxZEZCVFUxQXlla2hpZUZGbGNHZG9lbGRTZFd4NldrWlRTRk5rV1QwS0xTMHRMUzFGVGtRZ1EwVlNWRWxHU1VOQlZFVXRMUzB0TFFvPSJ9fX19",
          "integratedTime": 1670113380,
          "logIndex": 8386012,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "7c6c469ba11a0eae335fe9090af68273116bd050",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3610876035",
      "sha": "7c6c469ba11a0eae335fe9090af68273116bd050"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

