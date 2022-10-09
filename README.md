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
| `latest` | `sha256:eb983890962b76390512144fffdff4ae1caaae0cda40f93a9e312be126d6da41`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:eb983890962b76390512144fffdff4ae1caaae0cda40f93a9e312be126d6da41) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:eb983890962b76390512144fffdff4ae1caaae0cda40f93a9e312be126d6da41"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "8ff7afef0dd75b527980afd74506764d2c6aa35e",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDJ39xVJrYS1fRAhbz7S3u2Psc0RAiP7Lfj8pbUN1/WOAIgYhQVX9M25ZRsfLGFtLZgNVkIirXVr7fYxyvbdz7jjHs=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiZDkyNTY1YTY0Y2NkZTUwNjA5NGQ3NjllODQ1MDViZjBmMThmNjc2YTFkM2ViMGI5ZTYyMWIzMGE1NjEzNTQ4In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQVI1dzJySnpMT0t4NmZZcTZBeUQrdCt3Tkt1N3BSRExKYUhWUjJUTHBaUUFpQnhIdExucjFnL0c5UTVMM1NZUndLN1JFL1p3S0VWa0Mway9sUUFUaXNPbXc9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlQzY3dhMjl5VkZaeFdsWnhZVXQ2Wkd0NVFWRklTMGszWW5aVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUVRWTlJFa3dUVlJOTWxkb1kwNU5ha2w0VFVSQk5VMUVTVEZOVkUweVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUxVTJsbU9WbENZa3B6UTB4cmMyRkxNVVU0WW05dlREUlFZVGhxUkZaWFVFdzNUMDRLTm5FNWFsUjBWV2xzVlhNNFUxaHFZalZqVFVJeFRUQnBNVEZaVVd4UGRGTXhVVGx4YzJwcFJuQkRTWE5aVWpSRFRIRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZHTjFSMENtbDViVEpIY3pZeVZuazVkRFpaYTIxTk5UTjZRbTVOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpSYWJWa3pXVmRhYkZwcVFtdGFSR014V1dwVmVVNTZhelJOUjBadFdrUmpNRTVVUVRKT2Vsa3dDbHBFU21wT2JVWm9UWHBXYkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzNjV1ZxV0UxQlFVRlJSRUZGWTNkU1VVbG5SVzVTYVZCRFluRUtObGdyYzFCWWVGbG1RblUzUVVOd09DdE1UbXBSY1ZkNUwzaHFkRmR5Y0RWRmJUUkRTVkZEVGs5d1ZscHNVVmhCUTBGRE0wd3hSeXN5UjBSTU5sTlROQXB4TW01aWVpOW5hbVpaT1hsVVVtTXJSa1JCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEZRV2RITTJOUVQxWmhSR1pNY2taR1MxbE1lQ3N2Q2poSmFFcEhXSGxVVEZsb2RqZE5RU3QwVGpBNFdYZDVZMUZZVlZWTEszUXlkWFJWTXpCbmEyVjJXbm9yUVdwQlIxaFVNRGQ0V2pCVFowWm9XbVZyWXpJS1prWldhbGxMWnpjckx6QkNSWFF4Y2xoWGQyRjFMMU5WY1doWk1Ib3ZNVXMyVlU1a1ZYRnZNWE54ZDFaV00wazlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665283319,
          "logIndex": 4728853,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "8ff7afef0dd75b527980afd74506764d2c6aa35e",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3212623244",
      "sha": "8ff7afef0dd75b527980afd74506764d2c6aa35e"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

