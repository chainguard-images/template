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
| `latest` | `sha256:46b46e3d092a7b61c60384a2b4a6d0bcab2efd44bdf29ba18291c0d88e46af13`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:46b46e3d092a7b61c60384a2b4a6d0bcab2efd44bdf29ba18291c0d88e46af13) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:46b46e3d092a7b61c60384a2b4a6d0bcab2efd44bdf29ba18291c0d88e46af13"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "aebe70b11e57f775c1cab03db2f03da49b94aa99",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQDzqk+LsAHxQHesGy2vp6NEQ0nzQFtPJLv9b9ys5TghbgIhAI75FfSXBODS+GBykhFQviNqUTV4Nhx9aaBB3fLo5Y0L",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2OTljM2I5MjhmNWNhZDVmOWE2MTBiZWU4YTdiYTk4NDQ5ZTM0YWI5NDY3ZDFmNTcyNWFlMTNmZDQ0ZDM1YjdiIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJSC9zOEdLd0h3c2MxS2V1SjhITTcwZDlGSjRXZEp1RUJxTnN0Qk5vR3d3bUFpQVNRVzBEcnF5RVZXSC8xSTdHS2l0ZDVCNnl0eFV6amdFekxVUXB0S0pRTVE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVldqSXJiblZTUkV3eFVHOUhiVnBRWkdFeWQyNWlURzFNUzFOVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1RWTlJFbDRUV3BWTVZkb1kwNU5ha2w0VFVSSk5VMUVTWGxOYWxVeFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZuU0hGUU5FVTJUVk5IY2toNFZGUmxSVWxFTUZoUE5EVlZhM04yUWtsRlZrdEVabG9LUVRoSFQySkZNRGRKVkZaWU1tUk9iazh5WjFWQldXMU9ibEZQVVVobVIwOHpkalIxVVhaRWRHWlNUWFJ2TTJkWWQyRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlY0UlRSWENqaHRhMmRqVmxOVlpUUlJla1kxWmtoQ1FqWktjR1U0ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdoYVYwcHNUbnBDYVUxVVJteE9WR1J0VG5wak1WbDZSbXBaVjBsM1RUSlNhVTF0V1hkTk1sSm9DazVFYkdsUFZGSm9XVlJyTlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaERSMFJsSzNOQlFVRlJSRUZGWTNkU1VVbG5WRlJVTWsxQmNqUUtNMGcyYTBwb1VtYzRWR3BaUkRnMmVFZHdVeXN4Ym1oTlJVSlZjbUk0ZG05M05VMURTVkZFUWtJd1MxWXJZbkZVSzJ0SWJuRjZNQzl6WWtGbVJtNWFXZ3BvTlhCbVFuaDRUbXhzVTJGd2JqSllLMVJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEZRWEZhTlZreVlqZGlXSFJrUVZacWFEQnhVbEEwQ25kYVVtSnVUMkZYSzB4cWVsRk9kbWN3UVVzek1FVnhhMHR0YzFSUVduVktTMXAzYUVsU2RGUnZSRVJTUVdwQ1VuaGtUa2xLY0hGVldtZEtZbXhHYm5BS2JsbElObmhDYVV3M1JUaHZTV3N3YkhoWVVuRm5lalJ4ZUZaQ01HNUpVRkpGY2xSdmIzVndRV2g2YVVKTmMyODlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667009595,
          "logIndex": 6076855,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "aebe70b11e57f775c1cab03db2f03da49b94aa99",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3349680871",
      "sha": "aebe70b11e57f775c1cab03db2f03da49b94aa99"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

