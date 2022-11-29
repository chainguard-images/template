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
| `latest` | `sha256:452a67d26fc4fa70aeb34f1ae185b36edaa65c9817ba8ab47a777e32b62e41f1`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:452a67d26fc4fa70aeb34f1ae185b36edaa65c9817ba8ab47a777e32b62e41f1) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:452a67d26fc4fa70aeb34f1ae185b36edaa65c9817ba8ab47a777e32b62e41f1"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "6b2849dca249048eddc7b16d927bb13fbf133b2d",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCICKE0Uly26VMWuIGUpkJqrNesBIemPc6J53sPqy72DihAiEA+Vd14TYN5QsZtdzq1V5ucSt1+5hZPqQBx6Zl7EeUmuM=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIwMTZiNTQ0NzJiY2Q2NDhkMjNmNjBlZmVlNDE5ZDczNmVlMjQxMDI1ZDdkM2NkMjk4NWQ4MjIyZGVjNWRhOGQxIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURZeFJSZ3Y1UUowbmlUaUJqMnk4Z2gwSHRoRm90d3czQmdnZSs3UStVbHZBSWdkZ21CZm0wajVVQ0FyWUF6MXozdzk1bTk1NW9qbkJrZENHVDJ3ak1uMllnPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlMySnBSWEZpVHpSb0wzcE5SbXN3SzJJckwzSjFTV3AyUm5oamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1RWTlJFRjVUbFJSZDFkb1kwNU5ha2w0VFZSSk5VMUVRWHBPVkZGM1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZwYkdWTE4yVlJXV1ZEZDBodmFUSjRiSGxQZUV0RlZHOUdOMlpNT1dsV1FWb3ZhRllLTDBsaFp6ZzFOM1ZOUVVad1pGTkhRM1IxVFhSR1RUTm5lbTV5YzFaYUswRkhhVTVSTm5oc1Yya3pWbGhNWWtwV2EzRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZCWkRSUUNrSkNXVXNyT0RCT2FuQnBRV3ByVkdWcVZ6bElOVFIzZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpKWmFrazBUa1JzYTFreVJYbE9SR3QzVGtSb2JGcEhVbXBPTWtsNFRtMVJOVTFxWkdsWmFrVjZDbHB0U20xTlZFMTZXV3BLYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE5SRWRpTlRoQlFVRlJSRUZGWTNkU1VVbG9RVXhZT0RNNFRWb0tWWEZrWjNCUlpuSkJaVE5IWVc1dE1FZDVjRUZpVlRaV1EzcExWbkJuY1VaemJsaHNRV2xDYjNsdVpYVm5Wbk0xYUVkNVNtRm9OVlkyUVhkd09WbHVkZ280ZW1aaU1VUmhlVkpYWkVjMWNVNWpXbFJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcEJXSFZ0TkVsRmRISk1iMEpxVG10TFN6UlZjMUEyQ2t4Q1JqSnBWSEJsTVRkcGVqVXZOWE1yVEhRMVZtaHhTbEUxWVhsck56ZHpZV0Y0UVZSUmRtWnNjVmxEVFVkc05FZE5hbXRMTjBOdmNrVjVSbmRLZWtRS1VtWXZWVFpvVERFNGRsbG1NRTlOU1hjMFZIUXJjbWRNUjA4NWVYaHFSSGRzYXpRNUsxaFBaRzVwYzBRMWR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669681562,
          "logIndex": 8048927,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "6b2849dca249048eddc7b16d927bb13fbf133b2d",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3569826918",
      "sha": "6b2849dca249048eddc7b16d927bb13fbf133b2d"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

