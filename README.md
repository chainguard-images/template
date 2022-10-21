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
| `latest` | `sha256:44319462800e447d7f8deda6b70f62e0899d9aba28df97ccb4ea4d0afbbec9b3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:44319462800e447d7f8deda6b70f62e0899d9aba28df97ccb4ea4d0afbbec9b3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:44319462800e447d7f8deda6b70f62e0899d9aba28df97ccb4ea4d0afbbec9b3"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "5604f2352a73d275367a308b664cebe551600eaf",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCpcHZD9W9MpUN7Xke1w5K3ujz6d82JS9I+CiSl5JoFhAIgMk8KfnBJKMV3iadFSWc9juWnDXI6AFd5Jqxd1Sa7/K0=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiZTI3YTc1ZDE0ZmM4ZGZmNjQzZmRiZGU0NWI2YjBjNjNmZmUyNzViMTQyYTMwMTIxM2MzZjc2ZTlkYjc1NDU1In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUM5RzA3ZjMwNVJjWnllaEN5RFI5cFl2WHZHczdtdTVWQkt0V1NWQkdiN1p3SWhBS2ZkTGRTOXBDT2lmTHcraStTVTJUYjNBL3RFcHorR2dPSXlORUcwMWF1QSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlJqbFlRbGwwZERWMlNTdHljRFoxYzNWMVVrSkhSbU5OUldsVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1hoTlJFbDRUV3BGTlZkb1kwNU5ha2w0VFVSSmVFMUVTWGxOYWtVMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ5Ums0d2FrRXhTSHB0WjNjcldGVnBZMU4yTm1Ga1pGZ3dWMGRvY0c5RmREUXJMMFlLUkRCTlJrbFJlbUZ4ZUhGU1R6RkdRVTlZSzJsVFZWVTJNSFZITDJKaGRUTldjaTlFT0dKWFNqbFNZbU55VFdsRGNtRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZQV21oTUNsUk9WMFJLTDBkaWExUnlXWGxaY1doTk5VOHJTR1JKZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpGT2FrRXdXbXBKZWs1VVNtaE9lazVyVFdwak1VMTZXVE5aVkUxM1QwZEpNazVxVW1wYVYwcHNDazVVVlhoT2FrRjNXbGRHYlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtY3ZhRkZFZEZWQlFVRlJSRUZGWTNkU1VVbG5TalpSVmt4alEya0tiVzFUU0RNMFMzSjZSalJIVjJkaGJHdFBXVlZLU2taMVVGbFZlbTFWUWxwdGJqUkRTVkZFWVRGWk1saG5iVXBzV1djMlJrd3lUMUp0TUc0eWNFbEZXZ3AwV1Rkb05qTkJZMDFLUlhOT01EY3pOMnBCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcENiWGgyWVUxdmFFOTFaWFJRVldKQ1pXeDNUSG80Q21VNVN5OHpiVFl2VW5ONlFrSnpWMVZ1T0RKTU5IQTRhMVpYY3k5RmRWa3lhazl2ZGxGSWVUTlNVMnREVFZGRFlrSmllRTVKTTBoU1ozWnpSbFZFTVZFS1RFTkhXSGt5TkhsaVRtVkRjbGRPWlM5bU1uQk5WV1ZET1ZkRWFDOVhhRmx3VTNJeFRuVnFUMmRqZVV4c0x6ZzlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666318361,
          "logIndex": 5532795,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "5604f2352a73d275367a308b664cebe551600eaf",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3294295598",
      "sha": "5604f2352a73d275367a308b664cebe551600eaf"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

