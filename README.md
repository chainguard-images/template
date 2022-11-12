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
| `latest` | `sha256:26e5d0f532223d344fbf3b63d06264e2273ca0b6026915827098f4b16ff89dea`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:26e5d0f532223d344fbf3b63d06264e2273ca0b6026915827098f4b16ff89dea) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:26e5d0f532223d344fbf3b63d06264e2273ca0b6026915827098f4b16ff89dea"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "862aa6fa7f2a109deac8cb33d53a270c03c9c73d",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQD1Yss2Uj1kK6pAtWxGp3E7L6xvn0u/50dvOfuG6bfaewIgKe9Ds81KPcmvu73bc6xouXV/GmQJe9xc8subXbWLPAQ=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJlYjdmMjRiMmRmNjBiODQ3OWEzMTE5NmQ2NmNlZjE2NWQ5MTc0N2M3YzRiNmNkMDIzNmM5MDNlMzViODEwMGM4In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRFJNR204N2tOd0pJQUpkYzU0WUcwbk1IRlBoTUN0b1ZhcTl4VXVZZ2hNYkFpRUF3ZmloeVNXb1kxanpuOHhvazhUZXRpNko1c0lnaWFFOUJBcjArY0E2TGFBPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlVsZHZRek42THpKeWNHSk9WSFIwZGsxRE9HTmtaREkxU0VSTmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlhsTlJFbDNUbXBGZDFkb1kwNU5ha2w0VFZSRmVVMUVTWGhPYWtWM1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYzYjJsQmVUbHFiemR6YTB0dkswdDJXR2RsU1hkWWVEbDBaMHBsU3paUk5UTnBjM2dLSzNOdlYzZFdOREJyTmpFdmNWSlVWbmhuVlVVemFHMUxObXh4VlZaWFVURnJURUpUVEdSU2JVbEdiMFpFWlZsRVNEWlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlY0Ym5kcUNsaFhaeXQ0V0V0UFJqQnVkRlpKVURSVE4xSkNTa2RaZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpST2FrcG9XVlJhYlZsVVpHMU5iVVY0VFVSc2ExcFhSbXBQUjA1cFRYcE9hMDVVVG1oTmFtTjNDbGw2UVhwWmVteHFUbnBPYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEhiVmRXV0d0QlFVRlJSRUZGWTNkU1VVbG9RVXcyUkZVMFFWQUtSRVIxVTFwdlkwdExTRlpIUjJaeWJuRnZPRTFrU0drNGJWZEdkekpVVmpCRVJVVXlRV2xCWm5kYVRuVndhVkV4V0hONEsyRTNSWFpGSzB0c1dFZEpZZ3BUVVUwMVRrSnVTV2t2TW5wTmRqUlJiMFJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcEJlVTFCTVZGbmJEQjZZV0Y1YmpKUGJHdDFia3BuQ2l0V05IQlhZVmN5Y3pScEwyeG5SVVpsV0RGcVdYaFNkbkJ6WnpFMlNXbDZjSGhHUTJoUFpqRXdhVWxEVFVGb05GZHdObXBxZVVsNWRGZzNUa2xOS3pnS1VVSlpkWFZGYW00eWVuQk1jSEJtZFc1SGQzSk5kbWR2Y0VkbE1qWjVhWFJOUVZoWGREbERWMkpuY25OR1FUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668218803,
          "logIndex": 6907085,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "862aa6fa7f2a109deac8cb33d53a270c03c9c73d",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3449139226",
      "sha": "862aa6fa7f2a109deac8cb33d53a270c03c9c73d"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

