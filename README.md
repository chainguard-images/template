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
| `latest` | `sha256:20ed65c99e0efc6a1171a7cde9156438e8763b0d9abc1dfb8ef75197a4b848b9`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:20ed65c99e0efc6a1171a7cde9156438e8763b0d9abc1dfb8ef75197a4b848b9) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:20ed65c99e0efc6a1171a7cde9156438e8763b0d9abc1dfb8ef75197a4b848b9"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "98cac9c126fa069b6c77eb04b1d477b96fe517d9",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIGDnJkjkRxJ7BVueWkGA7GJ8CRZ9wqoIITtQN2OTkUiMAiEAk92DVr8BTXJMGGR6diHtgI2tPENNZrWtpdePcJnUqss=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJkMTQ1NmRmNzEwZjM3MjliMzM3OWNhZGEwNDcwMGUxMTJjNmIxYTY4YTI0MTAxNjZhNmJlN2QxNDIwMTYyZWQ1In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQVViZWwydk4rdThiVVl5MHAzdk5jekFzRnEybFZGWXJnSXo0bkQvSE1hZUFpQjFUWnYyMFZ6ZzExUWFHdXFHMzgwSTE3aEJJVUFDZTYvNzBnQ3B3N2liRFE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlZtRlZTMmxyVkRGcEt6VllPRzR6T1dab2VXUm9TWE5PWjB4M2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRSTlJFbDNUMFJCZVZkb1kwNU5ha2w0VFZSQk5FMUVTWGhQUkVGNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYxWXpoWmMzSlJLeXN3YkRoS1YxRkVTV1ZxV210TE1YZFVXaXRuT1VwcVdtSjZTMHdLVDNwNVJGZDRPSEZ3ZVZRcmJUSmhVWFY0YVZsWVowZzRXQ3RJUlVwQ1NqbEZha0pTVFM5SVZXbEhlR2RyYVVGVVdEWlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZxTm5kbUNsWjZZblpxT1dGYWRtNHdTbFpxTDNRek9EaGhRVTEzZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpWUFIwNW9XWHBzYWsxVVNUSmFiVVYzVG1wc2FVNXRUVE5PTWxacFRVUlNhVTFYVVRCT2VtUnBDazlVV20xYVZGVjRUakpSTlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEdWQ3R0WjBsQlFVRlJSRUZGWTNkU1VVbG9RVXBtVW10eVVFMEtWR3QwUTBSTVptOVlNSGszUTBKNFFsbHNVM0kzT1ROSFUyYzJNMUkxY1RaaVFtUkRRV2xDVDNaS1ZraEtRVW8xVms5NFQweDFRakJSVjFBeVNFNUxLd280U2l0d2JHMXFaVGN2YWxoeVNHNWFORlJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEJlbFZHWWl0NWIyb3ZTbEZNTWtGWmNXTnVUVlJ6Q2xaWE1VdDVUVGN2ZEVGWVZIcEJlV2dyZEhGcVNrUXZRelJzVlROMlRVb3pTWFpQYmxkUlpXdGpha2xEVFZGREsxaHlSbVZDWTJKak1GUlRjRWxRUm1ZS2QzbE5aR0ZJWW1OUE1FSndlbFZJVDJvM1NqSnlNak5hYkU5aFEycEVPRzV0YkZOV1pGRjJRalZ1YlhkamQxRTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667873308,
          "logIndex": 6705505,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "98cac9c126fa069b6c77eb04b1d477b96fe517d9",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3415755447",
      "sha": "98cac9c126fa069b6c77eb04b1d477b96fe517d9"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

