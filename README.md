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
| `latest` | `sha256:c2bed04597a60e24189f0fd522105ccc5caf3bfbdefc0d03b39a32687e60a9ee`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:c2bed04597a60e24189f0fd522105ccc5caf3bfbdefc0d03b39a32687e60a9ee) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:c2bed04597a60e24189f0fd522105ccc5caf3bfbdefc0d03b39a32687e60a9ee"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "71cf10096775a63824afdf0462739b5fad65e3ef",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIDn5QzQ+Pv/O22D27ZBtfYkM6BOvXZ48W7rsUrJxjWD7AiEApNV0yenyXjb7tqw0nXA91g4DfcgGGZcTFksJMl6bdec=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJhMWE5ZDRiZTc2ZWM1NDA2YjFjODZhYmZiMjhhNzZiNDU5ZjZkZjk5ZjhmZTVkYWUzZGY0YmVjZjdhNDhlNjkwIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQWV3ZGdmajBOZkRUa0lRendrVytNdy9pc0hSV3lSUXpKWVFhTGtURzllL0FpQlo1WnNMSHZueXV5NDc5L1c3eHczZGo5RjVPRFovNlp3bFlRVnljN1M1enc9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnhla05EUVhwSFowRjNTVUpCWjBsVlNVWXdiamxIUVRVeVIyeE1OR2RKVGxCQldTOVBhQzl5TDJWTmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1hkTmFrRjVUV3BCTTFkb1kwNU5ha2w0VFVSSmQwMXFRWHBOYWtFelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ1UlRoUVdGRnpaWFJyUmxGblVYcFJPVkZNVG5KSFV6WTNZVXBXU25aaGJVNWpXamdLTlZoamFqQlJjVGxVWlVkNFlXUkRjVVJKWVZaUVVrbHRjWGRDUTFsTGJGSjRlRlpaVVdRclZUVnFZbEppTHpVeE9XRlBRMEZzUVhkblowcE5UVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlU1U2pGRUNtWkVkMFZESzBJM2FHWlZSalZCWnl0cVYzSk1NVWxaZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGVFFtZHZja0puUlVWQldVOHZUVUZGUTBKQlVuZGtXRTV2VFVSWlJ3cERhWE5IUVZGUlFtYzNPSGRCVVUxRlMwUmplRmt5V1hoTlJFRTFUbXBqTTA1WFJUSk5lbWQ1VGtkR2JWcEhXWGRPUkZsNVRucE5OVmxxVm0xWlYxRXlDazVYVlhwYVYxbDNTRUZaUzB0M1dVSkNRVWRFZG5wQlFrSkJVVTlSTTBwc1dWaFNiRWxHU214aVIxWm9ZekpWZDB0QldVdExkMWxDUWtGSFJIWjZRVUlLUWxGUllWa3lhR2hoVnpWdVpGZEdlVnBETVhCaVYwWnVXbGhOZG1SSFZuUmpSM2hvWkVkVmQwaFJXVXRMZDFsQ1FrRkhSSFo2UVVKQ1oxRlFZMjFXYlFwamVUbHZXbGRHYTJONU9YUlpWMngxVFVsSFMwSm5iM0pDWjBWRlFXUmFOVUZuVVVOQ1NIZEZaV2RDTkVGSVdVRkRSME5UT0VOb1V5OHlhRVl3WkVaeUNrbzBVMk5TVjJOWmNrSlpPWGQ2YWxOaVpXRTRTV2RaTW1JelNVRkJRVWRFT1hjNWRXRlJRVUZDUVUxQlVucENSa0ZwUWpKcFRGSlNMMnh3Y0ZwcWVXTUtWRWg1VGxCSFdYSnpPRUpPV0hOR1FTdDZWRTl5WldkSEsySnZja3BuU1doQlRYTlpVR3Q2UkhZdk9WQkVjVE5zVUU5T1MwczBRVXQwYUVkNVdGSk1hd3B2VWpCV05HSTNiM0l3UnpCTlFXOUhRME54UjFOTk5EbENRVTFFUVRKblFVMUhWVU5OUTJsS1pYTkVNRlpJV1hGdVJtZHpWRWRYZVdWUVdubzJWMVpWQ2xsM1FsTnZTRkZpY21WSWExaG1Rbkp5TVdoMGNVOXRTeloxYTJNdmFGTmFhbVZwVGxWblNYaEJTbUZXT1VsaFdsVnNhR2hXWjB3MFZtaGpVV2RJVG5NS1ExcDZiMGhSZEdwQlJWbGpWVmxRZERGRWFuaDJWUzgzVFhneFdFUmlka2d5WmpOVFJuWTFjbmxCUFQwS0xTMHRMUzFGVGtRZ1EwVlNWRWxHU1VOQlZFVXRMUzB0TFFvPSJ9fX19",
          "integratedTime": 1666297370,
          "logIndex": 5517187,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "71cf10096775a63824afdf0462739b5fad65e3ef",
      "githubWorkflowTrigger": "push",
      "run_attempt": "2",
      "run_id": "3292627756",
      "sha": "71cf10096775a63824afdf0462739b5fad65e3ef"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

