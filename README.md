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
| `latest` | `sha256:d6275754474b522c3e5566625c3d282e9f77c0fee2fa23c2031993b44982a550`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d6275754474b522c3e5566625c3d282e9f77c0fee2fa23c2031993b44982a550) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:d6275754474b522c3e5566625c3d282e9f77c0fee2fa23c2031993b44982a550"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "5faa9e8798961a319ccfd336583c9772c6db8e3d",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCIjVlhdt/GbWIaupmigrfEw4J6791ZTnZTF1+MchqwqQIgJKxCzHvFZ811e/wWteozeoK7PbNtcyAQp1tVXvft8CA=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJhOTc2OTY1MWM3NWJhOGQ3MWQ5MjI4MGYwNTVkNTE0NTlmNzkyNGI0ZjMxMWE4Y2UxZDJhYzNlODNjMThhYTU0In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQlZZdFB2Z256OXh3UGZ6N0xHWXdpR2tGSG13cENtVWxEcjZEQVdOK0xpakFpRUFvbGRkdDdyLzVlL2UxVERCRXp1VFpGU1QvNHRTay9rMUVQdzVqQzRjWEdrPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlYzUlZkRFl6UW5KTGVHdDRaVlZ4TDI5c1drMW9ZVFp6TW5nd2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1hwTlJFa3dUV3BCTlZkb1kwNU5ha2w0VFVSSmVrMUVTVEZOYWtFMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVY2WVU0cksxRlVWVWRzVTBobmEyRXhkR1U0Ykhvd1oyaElSVXN2TVhadU0ybFhVRkVLVW1GT1ZrMDViak16YW1wQlFsQXZTbGxNTjFONFdtVXJjMWxJYkhwYWNVeEVLelJSZEVKd0wxaDBielUwTmxWcU9HRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlV5ZVV4UUNsVlNiRlpEYzBSdkwyTmpXazFLU2xOR1MzcEplVlJCZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpGYWJVWm9UMWRWTkU1NmF6UlBWRmw0V1ZSTmVFOVhUbXBhYlZGNlRYcFpNVTlFVG1wUFZHTXpDazF0VFRKYVIwazBXbFJPYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaEJTelJHWW1kQlFVRlJSRUZGWTNkU1VVbG5ZVVptT0c1c1JFRUtaa040ZURnNU1XNURWamM0TnpKaksyWTNlRGhTVkd4dVkxWjVkMHRDTTJsVmVHTkRTVkZFU25vM05YZGFLekpsTTNsV2JuTlhOQzlrV214blRHVklhQW96S3pRNVpsTklLelpXTkV4V1NYa3laRlJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEJjVWRsTUhWMVoxbEZiR1pRUVhwalFUbHlVbXBaQ25OaVlYSkZXRVEwVjFWTVlVWmFNRU01YzA5alJYTnJSWEpPT1RCeVQyOXlWMHhoS3k4M2VrdzFPVVZEVFZGRFJtRnZaV2hNY3pKaVIwMXJiM1ZNV0dVS1NUUm1SRzFFUTJnM1JVc3dTa2REZFdKR2JUVm9NVXBRUmxSNVNsWklRMnBMZG1oMVJuZHJPUzh4YVZoSVdHTTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666492949,
          "logIndex": 5674452,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "5faa9e8798961a319ccfd336583c9772c6db8e3d",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3305551398",
      "sha": "5faa9e8798961a319ccfd336583c9772c6db8e3d"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

