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
| `latest` | `sha256:a74d5ab265a11eabe3bc14a03b47f0d44fca023d09fdcb5f4e75a778d88075e1`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a74d5ab265a11eabe3bc14a03b47f0d44fca023d09fdcb5f4e75a778d88075e1) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:a74d5ab265a11eabe3bc14a03b47f0d44fca023d09fdcb5f4e75a778d88075e1"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "4dbe0a6085baebe67e027c009146392310414590",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIFpKY/K3TPRTriQ761lnCAySClYOmd8mgaOswANW2ZZuAiB+FOiHXFOXLVre6nD2nvS7YKMGeQSJLDOOTn/q/eBe4A==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiNTVjYmNkMWMxYzJjNzBmZGFmMDRlYjRkYzRjNmVkNjFmZGFkMWViOGE1MGU4ZjUwOTgzNGIwNWY4ZWMwMTUzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUNQdFU3VmlIZlBCTVFBdElkZFRsdUxLMEhxa1Vna20zTExMNk9rYmxhYVBBSWhBSndudUpWeUU1akxMczRrREVhM3d1cnFhVlpBUnNxeXhQMUZmdHNXcWQxZCIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlZHZDRRbVJUVkRRNVQwRnJla0phVEdSU1ZFbFhhbFlyYzBocmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlRKTlJFbDNUWHBSTkZkb1kwNU5ha2w0VFZSRk1rMUVTWGhOZWxFMFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYxYWpWM2JXWm1Sa1JHZG1ObVkxcFBkMUpDVWtsRFpFcEpUbEUzZGpWT1dYbFBabGdLTjJ4aU5UQmljVUpVV0VwdGNYZzFjSE4zUjBkVVIwVkZjekZCYTB3M2RGZEtNSFl3WkZwRmF6RkxaRnByZW1nNWRYRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZITUVFMENtbDJUMEZ1ZHpGTEsxcFpSakUxUmpaTmJUTjJURmxGZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpCYVIwcHNUVWRGTWsxRVp6RlpiVVpzV1cxVk1rNHlWWGROYW1ScVRVUkJOVTFVVVRKTmVtdDVDazE2UlhkT1JFVXdUbFJyZDAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaElOSFJ0VjFGQlFVRlJSRUZGWTNkU1VVbG5Wa0pzVnk4MGRGRUtLMjVhUkdsQ05ISllRMWt2YldWNVptSlNPVE5YVlNzM2MzcFZWekFyV0dWS2FHdERTVkZFVWk5ak1FUXhVMFJvTlhWb2N6bDZkV1EyVTNabFdETXJlUXB0WVRkaVRWaEhibFJ6YmtWRlpFNVVSM3BCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcEJhM0prY0RseVVtdDRXVlJ6V2pKM2JWbFNiRk56Q2xCS2NWTXZhVmtyTmxoYVpYTmphemhKVUZOSUx5OURSelZTT1RGQmRWVjZLMDh4YTNkWU5YWlpOWE5EVFVKSFNIRkNURUpTVm5KS01qSmtjbmRTWTI0S1JtaHViRmxqTlZWS1V6RndaVTA0TVZVMGMwMVJWbE5zUmxwdlJTOXJNemh6YTA1MWNFTnhVSGh3VGtocWR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668564252,
          "logIndex": 7171488,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "4dbe0a6085baebe67e027c009146392310414590",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3475751124",
      "sha": "4dbe0a6085baebe67e027c009146392310414590"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

