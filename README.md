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
| `latest` | `sha256:5ed7c4446cc51a7736014960eba142bbd8c1f209088a368d300725adc3156739`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5ed7c4446cc51a7736014960eba142bbd8c1f209088a368d300725adc3156739) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:5ed7c4446cc51a7736014960eba142bbd8c1f209088a368d300725adc3156739"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "36b84067fb972de23908a28ddb39d2358dce73f7",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDlVUK54CTPMYG7bLmSPfp5SHoAvZCxN+REjRKCMx1OFgIgBks76dr8DEKzim8ct/DXnSZI7NVPGcjWHW6gDa4rx8U=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIzNTc0NTQ5NGM0YWJjYzNkOTY5MmM4NGRiNzE1YjM3MDFjMmU0NzFkMDAxYzU4ZmM1MGJkNGU2YTJlZWY3ZTYyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQnRHd0dub3lpRjMwaG1kc0dRbjJkZVdqWWd0VjBIZHVDL2loUUdQaER2WkFpRUFrNC84bXJRR29QVnN1bzhTck5xd3NnazhYN1I4RllDVXpKYXJrOFE1R2I4PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlVISk5kbEppU25OV2RuTXJPSGhaZG5sTFlVdzJZVXhpZGxrd2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1hsTlJFbDZUVlJGTlZkb1kwNU5ha2w0VFVSSmVVMUVTVEJOVkVVMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZEY2pCVlNWUkdSMFZWYUhaSVlXSmxVQzkyTWtKRk1qTm9WVlpDV0RjMFEyZG9PR3NLV1hCR04wMHZhMjgzVDBOWE1YTk9ORXhhVUVKS04weFJZelJEUTBORU9VbHRMMmc1VTJoTFRYRXdjazU1UjNGcVVVdFBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZQYkV4dUNqWnVNRUp2TDFSWFZEVmxZbUZSYnpVdk9XTkNWMnRSZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNwT2JVazBUa1JCTWs0eVdtbFBWR041V2tkVmVVMTZhM2RQUjBWNVQwZFNhMWxxVFRWYVJFbDZDazVVYUd0Wk1sVXpUVEpaTTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtY3ZNa2g2WlVsQlFVRlJSRUZGWTNkU1VVbG9RVTAzWjNKRFRrUUtSelp2VURSS2NUZHBURzlJUmpOcEx5OXpRbmREUXpCRmFERk5hSGhaYVdWTmRVdDVRV2xDU1hGSWNERjNiakV4VVdSek5WVmFWMmRoVkhsVVJsYzVNd294ZFROTk9VdFFTMVEyTkhGRlUyWjNlWHBCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEZRV2xPU1hwcmJHbFhjV3B0T0habmNsaDNWR2xYQ2toNVJreGFXa1pXYjJWc1FVUk1kWGRTVTI1SlYzcEZhamhLWkhaWWRuUkhaVGxEYzA0MFR6Y3lUSGgxUVdwQ1RsaHRlWFEwYVVRMVZubGlPVTQ0V1UwS1FYQmhiSGRKT0VWRVpXUm1kaTlSU2taUlIyc3ZUWE5wVEU5d1pEZE9UVVJPZHl0TFlTczJObmxvY0dSU01HTTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666405910,
          "logIndex": 5612869,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "36b84067fb972de23908a28ddb39d2358dce73f7",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3301620399",
      "sha": "36b84067fb972de23908a28ddb39d2358dce73f7"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

