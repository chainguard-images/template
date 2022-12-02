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
| `latest` | `sha256:4b790d7eedc4200cb04701a9b9397ac3e26ff127e4ff77e9d87efe0fef86676d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4b790d7eedc4200cb04701a9b9397ac3e26ff127e4ff77e9d87efe0fef86676d) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:4b790d7eedc4200cb04701a9b9397ac3e26ff127e4ff77e9d87efe0fef86676d"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "ce38412df92d7ae8e42c1dcfedf62959e14f76a4",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQD/UMedVGDTVWzPyFvMSnp79bIk+E66Qx6FO2MQQkQf/wIgNK47bjnZmzGEESTxUM/3khBAGmiLpn1BgVkNr/8N4EE=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyNGZiZGRmYjgxMzIwMDM4ZmVkMTU2NjlmNmVjYTQ3OTRjN2RlYTYyNTEzMTgzYTdkOTA5YzhhMzJhZTk4NjFkIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQmVZY2NhbzJuNkRtcExVVUV5U2VQeWxwSDhwNE03dkhxRVk1T0hvdHkvVEFpQUZ4QVVvRTZOcklzUW5mZGV2RjRsSEowVTlXQjRnSGJXbkZZN1RPOVNmdVE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwVFowRjNTVUpCWjBsVlJuWkhSbXRGVFhFeGMxUlpSek4yWWpaMVFXdDJRamt6THpScmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVhsTlJFRjVUWHBOTlZkb1kwNU5ha2w0VFdwQmVVMUVRWHBOZWswMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYwVEVGVFUxSk1hRmd4TTJOcmFVcGFhRlpoYWpWb1pYSlZaWHBYYkRoWGFYSnFUellLSzNsWFVEbE1UMWhuY1dFNVZtdHJUVWhIYlVkMWJDOXJWbWxETVU4NGVIQlRTMVJvWTJWelZTdE1UR0pJWkRkd0szRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZFY0VOeENrRk5hVXh6YkhrNGRqVk9PVzU2U0dGMGVGbE9MekpSZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdwYVZFMDBUa1JGZVZwSFdUVk5iVkV6V1ZkVk5GcFVVWGxaZWtacldUSmFiRnBIV1RKTmFtc3hDazlYVlhoT1Ixa3pUbTFGTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE9RVE54U1ZGQlFVRlJSRUZGV1hkU1FVbG5Wa1ZTVG5jMmR6SUtRV1pPYjBaMmFYUllTSE16TjFOeVZtVldPVVJDSzFnclVrZ3pjbGxzUXl0U2JHZERTVU5uTjFNM1ZIVnVWVFpuUVhreVYzWldUWGRWYTB0SmEzRkxVQXB2TjFaQlZFaHRTVXRZYkd4Q05tUm5UVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlhMEZOUjFsRFRWRkVNSE5CTkVkVlRXTnlUR2t5TlRjckswdE1abVp4Q2xaV1ZrbEpRVXA0Tm5FMlR6aEtjVmxEVmxoc05XRlZiMVU1ZW10TmVrNXJTME5PZFhSa1VIZDFVRWxEVFZGREt6TnpZelpxSzBRMlNXMVlWSE4xVjJRS1JqWk9VbUZHU0U5SVdHNTRTbWh5Vm1SVlJWbHJWRU5GTWxaQ1lVdG9WQzlwTjFoVldtdERjbEZrTnl0V01UQTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669940639,
          "logIndex": 8259095,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "ce38412df92d7ae8e42c1dcfedf62959e14f76a4",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3597717964",
      "sha": "ce38412df92d7ae8e42c1dcfedf62959e14f76a4"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

