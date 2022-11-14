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
| `latest` | `sha256:997415387ed793c78b6b3ff1200c4546b75bd82fe7c1b793287cab5e2f1db910`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:997415387ed793c78b6b3ff1200c4546b75bd82fe7c1b793287cab5e2f1db910) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:997415387ed793c78b6b3ff1200c4546b75bd82fe7c1b793287cab5e2f1db910"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "9c343e3fd1d3639cfef98ac8d34b90d2b2972ea4",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDGSWpv2MzyBqO9pDnYvC9sCF/XDGuEkIfVLZ9Aw0uSDAIgcSwwkJxM0Ej4ZktwqmruQyWpcyZOGOxu8yP5wAcvnMc=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIzYjM0YWFlZGM2MzFmZGNkOWU4NGRiOTFhZmFkN2JmMTg0ZDEzZmY1NjQzODc4M2M5ODRmMGE2OTkwYjg1NTUyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJRURoM3k1OXFxcm1TRGlFSVhNNDBRWnozemxZWXhsbjJYdjFOZS9oTWVwdUFpQU1BUnlULytLT3htUmZZaTJHQXRTUVU2MGZMR0xNcW1lY25rZ1ZZcGlOUFE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpWRU5EUVhwaFowRjNTVUpCWjBsVlFWUXJZMWwzTm05eEwyZ3JZVXN6ZEdsSFkzUllMemRUZDJwemQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlRCTlJFbDNUa1JOTVZkb1kwNU5ha2w0VFZSRk1FMUVTWGhPUkUweFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZKT1ZCblVqSnhZWEJIYUcxd2FEZEdPSE5zZUVseU9FdFVSVEZSYVVWRFZsa3ZjbWNLSzJ4UWFuWnpXamxGYzFSc2QySkRhRkpZV21WbmRYWnNZMEZVU0ZoeVowa3haa1JHZVhaRE5DODBNMjlZY1ZSdmJYRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlY1UlRFeENtNW9RMU15YmxwdVNHOWxOSEY0TWpCc2VHcGlRelYzZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpWWmVrMHdUVEpWZWxwdFVYaGFSRTB5VFhwc2FscHRWbTFQVkdob1dYcG9hMDE2VW1sUFZFSnJDazF0U1hsUFZHTjVXbGRGTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaElVR2h0VkVsQlFVRlJSRUZGWjNkU1owbG9RVXhVWVZSbFEwc0tLMEZyWVRjeFowWnFNVGh0V0U5UWRuTmtlSEZHZDNkRlJtRmxXbGxwVG1aMFowbFBRV2xGUVRaeU9XZHFVRlJ3VDFGV05raFlOR05HWW0wNU1VaENTQW8xUm5KbU5tZHVSbmRNVHl0VFFtUjFWbVZKZDBObldVbExiMXBKZW1vd1JVRjNUVVJoVVVGM1dtZEplRUZMWlV4TlFrdHhVRlZ1YlZaNlNqVXliV2xwQ2tnM0wzSm5jakYwY0VST2NEaHRUMkpFY21aUGR6ZERWeXRzVUZWWEx6azFTMDlDTVVSWVoyTXhNVkU1TjBGSmVFRk5VMDR3ZFcweWRIaEtOVU52T1ZZS1UyaFBjVkJvY3pFck5GcHFTVVp1YTJkcGRXNU5ibXRKZEZkMGFtRkRjME5wTVUxcmFqaHdWRWMzUkhsc04yaERaMmM5UFFvdExTMHRMVVZPUkNCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2c9PSJ9fX19",
          "integratedTime": 1668391494,
          "logIndex": 7024947,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "9c343e3fd1d3639cfef98ac8d34b90d2b2972ea4",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3457962186",
      "sha": "9c343e3fd1d3639cfef98ac8d34b90d2b2972ea4"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

