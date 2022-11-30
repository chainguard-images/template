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
| `latest` | `sha256:fd9d091e95482799ae3bffb7ae957102a080f3ee0a1038f0f50e6251b28eb94e`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:fd9d091e95482799ae3bffb7ae957102a080f3ee0a1038f0f50e6251b28eb94e) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:fd9d091e95482799ae3bffb7ae957102a080f3ee0a1038f0f50e6251b28eb94e"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "28448ca79b8825e55fad4b0d20f17a134ec18552",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDPG/wr+1ZOxOUU8PuhWZQ1L5y/JfJ6B2HWTd3MJEBkYAIgTkOrWdnDMyCSiFeTbIQV26LWfMl4GeI8z5fD772SWNg=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyYTYyNGNlNjYwODYyNDY1NmI3ODZmNjI4ZWU5NTdmOTZhOGZhMTc5ZDdlNzIzNDVlMTY5OWVhNjAyNTc0NGYzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURHSmZuK29qZXQ4eVZiY3JNd0FvWGE3cmVwakVmWVdTRlBZR1d6dSt2dHlnSWdIUjNSWEorVktUNno0RWM3cStUZXRpQ0toN1hMQVJnYjUwdDFwcERjZ2RNPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlWRU5EUVhwVFowRjNTVUpCWjBsVlkxQTNaSGxxTmxFNUswaEVSVkJwTkM5d1RUWTVOVTFYYTFKVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVVFhkTlJFRjVUbXBCZUZkb1kwNU5ha2w0VFZSTmQwMUVRWHBPYWtGNFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZRVFhKa1QwbzRRbkIzYm01cU9VNUtWMjB5TWtzMVNEaHliV3hWWVZrMVkzSmpORVlLVDBwdWRGcDFTRTlFU0dGUVpXdDRZMU50WkUxbmIyVkdVM3BEU2k5eVpteEtNMnBaUW01NU5IRlNOamR0V25KTlowdFBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlUzY1RsQ0NuSlpTM2RpVEdFMmIyNUpZVWhWWmxObmJXZHpMMmRuZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNsUFJGRXdUMGRPYUU1NmJHbFBSR2Q1VGxkVk1VNVhXbWhhUkZKcFRVZFJlVTFIV1hoT01rVjRDazE2VW14WmVrVTBUbFJWZVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE5XSFJIYkhkQlFVRlJSRUZGV1hkU1FVbG5SbXd2ZVhOUU5Ia0tWVUY2WmtWcVltbFdlRGxWTTNScmRGaFlkemRVUkdscFZrOXVNQzhyWldoUU1qQkRTVVJTVW5ob2RsVkJWemM1ZFVKdWVrMW9NWFl6VEdkRFoyVlJWUXBHUlVoWmNVUjZkbk5aTW01MWMwVklUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlZMEZOUjFGRFRVSTNaRk40U1VWWldpOW1WMUJHZEcwd1dTOXRibGh3Q2tZd1NVRm9aMnBhYzA1U1RHUnBhVWhGUzFGSGJteHpaV0p6WTJoclUzcHhVMUJWZGtGSFMxUllaMGwzV1hwU1RtaE5kMnQxZWtKSlFtZFplRzlYY21zS1QzUTBWMDVZY2pKemJIQnRhVXhaYnk5ek9FTllORlJRYUV0SGQxbDRWemhyYjBac09WVnBMMnRqTjBNS0xTMHRMUzFGVGtRZ1EwVlNWRWxHU1VOQlZFVXRMUzB0TFFvPSJ9fX19",
          "integratedTime": 1669767982,
          "logIndex": 8122914,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "28448ca79b8825e55fad4b0d20f17a134ec18552",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3579165199",
      "sha": "28448ca79b8825e55fad4b0d20f17a134ec18552"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

