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
| `latest` | `sha256:01cd0733455a905d32c091f6e700b88d83cd3f495b47e1cedb84525f090c2aaa`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:01cd0733455a905d32c091f6e700b88d83cd3f495b47e1cedb84525f090c2aaa) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:01cd0733455a905d32c091f6e700b88d83cd3f495b47e1cedb84525f090c2aaa"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "c5db73ae5dbe3000de35ec6191beb742f4c7125b",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDxOEFXb1iILLJQmEaOEqecfEz0vq2u2+14X9PtOdwy3wIgeXA5A1sYnBwJfFfPHV7sx9+AYpoQ/d504rvpSPBXSkw=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiODQzMDc4YzBiOWUxYWQzZWIwOTMzZWVjYTk5YjhlMTIzODJhZGFjNjRlMjA4MWRkODFiNjE2NGYyZTU2NTRkIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJSFFDUlgxNHFFVW1OekdMczU3WlBuN2d4L2hwNHM5TzZocXVTa1p1b0o0YkFpQTFKSE9VaTVTSmRNNHlMb0V1UGRtb0YzL1JybmVQNVF1bkE4Y0lLOEkwUUE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlNHdEZLM2N4UkdRM2NHWnJlVFJYT1VKclJETXhVRWgyTDJKamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVhoTlJFa3dUVlJSTWxkb1kwNU5ha2w0VFZSQmVFMUVTVEZOVkZFeVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUyT0dGd01sVkdUa3hNTWtJd05qVnJVSE5qSzBWc1pqQnhZMmxTYUdWRlJ6TjVVVzRLWTNOYWNVd3hPRFpXU21sTWNraHBPVzl6VHpVMVpWZ3dSblZrTUdZNUsxQXZOV1phTldwWFNpOHJRbEZGUTFRMU5YRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZFUVZCNENrWkVhRnBETjNoVVFuaERVV2RPUTBKTlpFRnJlSFkwZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdwT1YxSnBUbnBPYUZwVVZtdFpiVlY2VFVSQmQxcEhWWHBPVjFacVRtcEZOVTFYU214WmFtTXdDazF0V1RCWmVtTjRUV3BXYVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEVSVkU1ZUZsQlFVRlJSRUZGWTNkU1VVbG5UR3d6V25rdmRGWUtTRlpKWmxKclFqZENTaTlMUkM5bldGQjBieTk0VFdKUlRtWjNTVXBvWkRWcFFUaERTVkZFVjBkbFowMTNTSFpFVFhwSFdUQm9NRFpEZG5nMmMwcGlOd3BRTkROWE5VZFRNbkZaWWtsU1FXNTZLMnBCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEJiVlp1VkVjelpHWmtPVzV5UjA5aGJqSjVhMUptQ213emJEbDVkM2RST0ZVd1pHOWllRTAxU3prelkzTkRkMUJhVWxkTFdIUkhSemRwT0hOeGIxWkxWWGREVFZGRGRUTlVaa3BUVUVWT1pGTXpVelJ3WkVNS1R5dHdiRlYyVmpoMGVXVmtNSEF5WkV0dlYyMUZUMUZyYzNoVlduaHZhaTg0VHl0U2NtOWFjek16ZDB0VFJXYzlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667270532,
          "logIndex": 6264938,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "c5db73ae5dbe3000de35ec6191beb742f4c7125b",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3366377632",
      "sha": "c5db73ae5dbe3000de35ec6191beb742f4c7125b"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

