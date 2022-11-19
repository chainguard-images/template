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
| `latest` | `sha256:1040d44c92a4b13274d1966e01586d93c4803a4a346a052683e89d11e7067ed7`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:1040d44c92a4b13274d1966e01586d93c4803a4a346a052683e89d11e7067ed7) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:1040d44c92a4b13274d1966e01586d93c4803a4a346a052683e89d11e7067ed7"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "1725951f0fe0a9330d6e6d23dd4c3cecf371ace1",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIAIAsFJjmTQOMvVw/cksHtgdlIXAMaxCrDbGRS11sjeiAiEA7I685ZW6HiJyNONyAt1gnvGfdQP/Q7WAlp83DMBrtZE=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI4ZDM4MWRhOWVlNWY2ZjgyNjQ2N2U3MzA1NjBmOTIzMGUzNTU1NmQ2YjNlMmIxNWM3YzI4MTk3ZGVjMDFiMzlmIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJR0FuZHJoSlM1Q2JkK253YkdSa25GQUgyc21HektET3pjaEtPNG1vWnpVQkFpRUEwZVhHby8vckJjd1I3WDBmOHR5V3RPaFV1clRvNFBacXgwM1JKQXhpNlQ0PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwaFowRjNTVUpCWjBsVldXZzVaVTU0TVM5TVprTmhkMDFtU0RBeFQzYzNla2RLTW5sTmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlRWTlJFVXhUMVJOZDFkb1kwNU5ha2w0VFZSRk5VMUVTWGRQVkUxM1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUwY0dzd01TdDZSMUJhTUdWVlVGZEhaMDlhVWpad09WVmlORXRyWTJWYWEyMTFSVWNLUnpKdVVsRXpOM1E1WTNkMmRubFhOemh3ZVV0UGJtMDRVRVEzS3pkVWNtRTBkV0poWTNFeWRHUlZPREZTVTJaNE4zRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYyUzI4eENqUm9kRnBhVXpGbmRYRXpabkZuYlhSVU5XVkdlVXcwZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNoT2Vra3hUMVJWZUZwcVFtMWFWRUpvVDFSTmVrMUhVVEphVkZwclRXcE9hMXBFVW1wTk1rNXNDbGt5V1hwT2VrWm9XVEpWZUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEpNbU4yUVRSQlFVRlJSRUZGWjNkU1owbG9RVkJXUlZWM00wc0tNbVpxZWxKelVYY3ZNVzVHWjJOc09GbEJVMUUxZEVVeFYyWkdUVGcwY1hoVGIwbERRV2xGUVc5dkwxQnlRMUl5YjFsUWMwbFNjQzlxYUdOb2FuWnBUUW95YUVGT2NHTmFTM0p6VkRoRk5sSndhVVl3ZDBObldVbExiMXBKZW1vd1JVRjNUVVJoUVVGM1dsRkplRUZQUVd3NGJHSnBTM1IwZFVjNVVWWndXbVZSQ21NeGIzaDNNV3RzWWxGRGN6WkhaazkyYVVweFRUTkNVRlpoYUZaeFRTczNkWGRGY0RGS1YxYzBhMHBqV2xGSmQwWndjMngxTnpWQ1UzSlNSMEp5V0hRS1RqaHpSa1UwUTBocWVqWkVMMGwwWTBRMk1qQlNSbHBWTlV4V2MxcGlWV2g0TlV4V04ySjNLMjAzT1Nzd1EzZE1DaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668823201,
          "logIndex": 7386421,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "1725951f0fe0a9330d6e6d23dd4c3cecf371ace1",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3501557706",
      "sha": "1725951f0fe0a9330d6e6d23dd4c3cecf371ace1"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

