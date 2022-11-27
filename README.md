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
| `latest` | `sha256:a0f15ad2b5eb793e131f3a21129d6d13cbdff0999a43734a7c8ec4fbadb14dcc`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a0f15ad2b5eb793e131f3a21129d6d13cbdff0999a43734a7c8ec4fbadb14dcc) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:a0f15ad2b5eb793e131f3a21129d6d13cbdff0999a43734a7c8ec4fbadb14dcc"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "9b1f2400a935dbded77c5dbaaef03bc7499df4e2",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDXhxMtge1jgETEv5RLIAHx7ef/VBLNHv5fs4M7HnJ8MQIgXtSmlE0ocLzBCZUwKCXATpe7kzk/vkMx8m1xH+6yN7g=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI0MWNkYTMxZWM4Mzk2OWQyMDA0ZWVmMmEyOWRmMTE4MDM2YjIxYjlmZDc4ZWE4MDI2MGM5MjhjZTkyODFkZWJmIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUN5cW1POVA3SFhuTHNIVTR0L3o5WWdlSmluanBOR3g1YW5OZUE4bTY2WnNBSWdXZ24vT3NpZCtMYnUvcmhzY1VCVzRoWWlJcDVzQ2o3VnlkQjk0QUJPWVB3PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwVFowRjNTVUpCWjBsVlZXRkNhU3RETlZkaWJESmhlVGRvYTBOd2QyVlhWSHB0V2tOdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1ROTlJFRjVUbXBGTUZkb1kwNU5ha2w0VFZSSk0wMUVRWHBPYWtVd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZYVldWd2FuTmFaMkZaWkhWNk9UaGtjMHd3VjJWTlVqbDJNV001UzJsbFJsUk1hakFLVVhKS04yUlNjMFJRTkdnd1QyMTBPVFJUVlVGRWFUaFpabk5YVFZCeGRIRklUR2xTUW5aaWEyOTNiRTlZV2t3NU1XRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZwT1U5cUNuQmpObE12Wm5JMk0wOWhhV3RFYm5aUmIxQktZelJOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpWWmFrWnRUV3BSZDAxSFJUVk5lbFpyV1cxU2JGcEVZek5aZWxacldXMUdhRnBYV1hkTk1rcHFDazU2VVRWUFYxSnRUa2RWZVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE1XalpQYVdkQlFVRlJSRUZGV1hkU1FVbG5RM1pEZG1RcmRra0tWRlZ2TTJadmFEUmFUekk1V0dSNGFXVkZOMGhzTWxrcmJXRkdZamhsYVcxNk56QkRTVVExYkV4bldHNDNaa3RFVHpoWU1qUlBMMGxLZENzMFp6aFFjQXBhYmtRMU1ETlVSR0ZXVkUxdlltWlVUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlhMEZOUjFsRFRWRkVZemt5YzJJNVprWm9la0ZwYTJKbVZIWmFhbTlGQ2s1clVHVTJjREZuVUU1dVpuTlNRM1YyVFdGUk9DOXlNRU5WVkhGbk5VMTVZa0p2Vm1vMVNUQnRSRUZEVFZGRWVHdE9ZWHBVYTBVeVoycHVObTFZT0drS2R6QXhNMGR0YWpBMWQxQklSMVUyUjFRMFZsWnVWWFptZFhOMmFHaHhlSE5UV2xWaWIyc3dURVV6U2pWeVdtczlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669508798,
          "logIndex": 7918103,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "9b1f2400a935dbded77c5dbaaef03bc7499df4e2",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3555986163",
      "sha": "9b1f2400a935dbded77c5dbaaef03bc7499df4e2"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

