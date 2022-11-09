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
| `latest` | `sha256:d2659eedea982ed36dde4ca905779b79c7ee7fd6987b91942a92b798f1bcdaaf`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d2659eedea982ed36dde4ca905779b79c7ee7fd6987b91942a92b798f1bcdaaf) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:d2659eedea982ed36dde4ca905779b79c7ee7fd6987b91942a92b798f1bcdaaf"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "bb5a95dc8058dc205a855f3b09dc6c15102564ee",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIHn0rQgU+2TIcINSyHyZn+aty9s7OkTaBoVfU2Rvb5XdAiAoeqXshKFgNQMy8AR0WaNr3vPJ4yZSgiAX3Y5kuV11nw==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJmZGQ1NDVhYmFhYjIyZjU0Njc0OWU2MGZlZDg5OTIxYWUyNDJjZjVkODVkN2M5NmNiMDZhZDhhNzI4M2U5ZDI5In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQms2VEsvYjY4bGhhdlJsb0thMmFFM0RyQ1pYZkJPL2IzNnFxOVd0ZWIrM0FpRUF6MjNBdUc0YWxXUUx6MVlKSU9oMDZrYlNxdFQxTzU4T1JXNUE5c0lpRldRPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlJWZGhlR3MzU25oMVpsVmpObUpWU0dreFZVRk9ha3BoT0d0VmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRWTlJFbDVUV3BGZVZkb1kwNU5ha2w0VFZSQk5VMUVTWHBOYWtWNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZSV1ZscE9HVklaM1lyVkdReWFXRjRiazk2VlM4NFkwMHJXbkpYZGtWVVdVeElUM1VLWkVSTlRtRnlabFZOYjFrMFdUaHFRbTQwUld0NVpHdGxWR28wYkV4aWRXdzVPVkF6VUM5eUwweFZXa3Q0YkUxVGFqWlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZMVFdoYUNsUjRibkExY0cwNVQzSnljV3RST0RaNVdWUXZSa0pOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdsWmFsWm9UMVJXYTFsNlozZE9WR2hyV1hwSmQwNVhSVFJPVkZadFRUSkpkMDlYVW1wT2JVMTRDazVVUlhkTmFsVXlUa2RXYkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEdiM2czVXpoQlFVRlJSRUZGWTNkU1VVbG9RVTlGVFhKclR6SUtUbnBUVUc5bFUwOXdUbkZrTjBGTFN6VlZibnBPY0d0M2IwTk1ka3BDV0RCS01TdFhRV2xDTDJKb1JIcFhXVEZyWTNwUk0wVk9MMGd5ZWxSQlpITTFlZ3BzZVVoV1ZsSTNTMlp0TVdWR1IxTjBjMFJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEZRV3REYW5WdVVIazNVMFpGUjNONFFVTnFUWFJ6Q2swM1YwVk5jblYwT0N0WU1qQkNkRmhHUm1ScmFIRkpkRTF5YVdkTVJXOURibWRPTW1WbGIwNVpNbkF5UVdwQlQxa3liSFk0ZUROM2IwVjVWR1pDVjJrS2JFZzRlbUYwVTJZdmN6bEZlRGgxWjFKWVNqaEJjbmhRTkdGc1NHWXJPRnBLZEZCSU9HcFJkbk5YTW0xR2RXczlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667960562,
          "logIndex": 6759025,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "bb5a95dc8058dc205a855f3b09dc6c15102564ee",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3424820079",
      "sha": "bb5a95dc8058dc205a855f3b09dc6c15102564ee"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

