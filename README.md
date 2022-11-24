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
| `latest` | `sha256:b5ce33f4d510469d2d023477c23b9581a1f6f95489a7e9b40afb7380d0dc90ce`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b5ce33f4d510469d2d023477c23b9581a1f6f95489a7e9b40afb7380d0dc90ce) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:b5ce33f4d510469d2d023477c23b9581a1f6f95489a7e9b40afb7380d0dc90ce"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "da6b6c230076640dfe80fb6b635552d0042042d8",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIHrBzP9SPHzt5Wgdl/SXy9feQ4ubcAS5IZt/QzejVmjvAiBvTdloPGLVT1gKKwR6ixK5FfarXWAGjK5OZCoQqX1uAw==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIzZTk4MGVlYWM4YTQ5OWU1YzlmYzVmODEzYjY2MzUxNGFmYWFmZDAyZDEyYzkzYWNkYWQyMTZiMGE1M2QyZjIyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQTd3Ly9hekRiaFBhVk5FeGM4UGREdi9PZFk3eGZJTytBeE91MFZMRy9rTkFpQlFPWGl0OG5vZEo5OWc3UXdpVlVENkZTR1JheXFhQVJxUnVkZ2ZmSUhaa1E9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlZrSTNOV05vYldOYVVWaHFWbVZPZFZwdWNrNUxkRGRTTWtrNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1RCTlJFRjVUbnBCTUZkb1kwNU5ha2w0VFZSSk1FMUVRWHBPZWtFd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ5V2pONWNFVmFZbU5VVEZWbVVtUndlV2c1WnpoaVQxWXJhMDVCYUZKbFNFOTRlVFVLT1dWNlZIcDRMek4zV1RWalkwYzBlbVJNZGpnM1FuTnpRMVUyUVM5alVYQXdaRU1yVG5od05URkdSMkZ0ZG1sWFNYRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlY2TUUwM0NrbFBVRVpvWnpnM1NYcFlRbk5WWkhObkwyUmljbEJ2ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd0WlZGcHBUbTFOZVUxNlFYZE9lbGt5VGtSQ2ExcHRWVFJOUjFwcFRtMUpNazE2VlRGT1ZFcHJDazFFUVRCTmFrRXdUVzFSTkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaExZMGcyZFd0QlFVRlJSRUZGWTNkU1VVbG5TREZoZUVkQlRIY0tRbVJtYkhGSVVYVXpNRWxPU0hkUGNqTjNTRXg0TVZoR1lYZHNlV2xzVGtRd2NFbERTVkZEWkM5VVpuSXlZbEZQTVZvelFtdFNZMVZ4VWsxbFEwcHdiQXB2UW0xMFlXcFRTV3h0YlU5QlJVTTBTVlJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcENka1ZFVXpBeksyWmpTRE16ZVZSUVRXNHlTMDVOQ2t4M1kyRldPQ3N6V0dnM1drZEdlV2hJZVVkeldGZE5LekppYjB4TmJDdHBWbmxrUzNocU1FWnBRVTFEVFZGRVFrbG9PR1J6V1hwUGFGRlVZbEJWVHpnS1IwWjZXRUV4VnpodmN5OWhUMEY0UjNZdlRYRlpOSHBqT1VwR04zUTNhRXROZW1weVVHdEdhRlpSZEZSM2VsVTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669249650,
          "logIndex": 7723159,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "da6b6c230076640dfe80fb6b635552d0042042d8",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3536672349",
      "sha": "da6b6c230076640dfe80fb6b635552d0042042d8"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

