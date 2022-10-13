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
| `latest` | `sha256:ea4e52b2eb6f8339e868fc7c713af976b4f8c4be51f6c454c9383597a015ad77`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ea4e52b2eb6f8339e868fc7c713af976b4f8c4be51f6c454c9383597a015ad77) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:ea4e52b2eb6f8339e868fc7c713af976b4f8c4be51f6c454c9383597a015ad77"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "d820d402e50b8ba4ca50888d46e42a84ba2721fb",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIEEWAx6ApRuJD1RN+2XDyAg1uteHxcUFPcjuosl2RCLwAiARvgDHY+TeThBXA+quyE3lMyQY1X60Lp3Oai0Ln4I3lg==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJkNjU5YzhjMDhjOTg1NTFmNGI4YzZkZGVmZmU4Y2E2MDQ1OGNmOGZiNzU0MWZjMDJiNzYwMWU1ODU5Y2I0NzJmIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQUZqMCsyUXBlYXVYNFBDeXRaemRiZXVPVHJaTUR1VS9rbG44akJndVRiNEFpRUEwS3dkQUNiUEJTS0ZUa2xWNE9VVGQzU3VFaUdoVXh2QlRFc29jSmhYU2g0PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnhla05EUVhwSFowRjNTVUpCWjBsVlRXSXpSbko2VGxRMU1td3JObWhtT0V0eE1uUnRNRTVpVDI1RmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlhwTmFrRjVUMFJOTUZkb1kwNU5ha2w0VFVSRmVrMXFRWHBQUkUwd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZXVFhKdk5XeHRhSFJTVFdSNFNtUmliVWRHTm5aQ1IxaDRNSGhRZDNBMFRtaEpUVmtLUldkWVdWWkxaRkpqV205VE1uWjJibXRLU1dGWmJtbHFUWEpCT1ZWWlUwYzFhRkZhT0RGdFdYWlBSMjFsSzFoV01YRlBRMEZzUVhkblowcE5UVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZRYnpSd0NtTXlibTR5UzNsWlYxWkhkalpoUnpRMVRWSTVkRWswZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGVFFtZHZja0puUlVWQldVOHZUVUZGUTBKQlVuZGtXRTV2VFVSWlJ3cERhWE5IUVZGUlFtYzNPSGRCVVUxRlMwZFJORTFxUW10T1JFRjVXbFJWZDFscWFHbFpWRkpxV1ZSVmQwOUVaelJhUkZFeVdsUlJlVmxVWnpCWmJVVjVDazU2U1hoYWJVbDNTRUZaUzB0M1dVSkNRVWRFZG5wQlFrSkJVVTlSTTBwc1dWaFNiRWxHU214aVIxWm9ZekpWZDB0QldVdExkMWxDUWtGSFJIWjZRVUlLUWxGUllWa3lhR2hoVnpWdVpGZEdlVnBETVhCaVYwWnVXbGhOZG1SSFZuUmpSM2hvWkVkVmQwaFJXVXRMZDFsQ1FrRkhSSFo2UVVKQ1oxRlFZMjFXYlFwamVUbHZXbGRHYTJONU9YUlpWMngxVFVsSFMwSm5iM0pDWjBWRlFXUmFOVUZuVVVOQ1NIZEZaV2RDTkVGSVdVRkRSME5UT0VOb1V5OHlhRVl3WkVaeUNrbzBVMk5TVjJOWmNrSlpPWGQ2YWxOaVpXRTRTV2RaTW1JelNVRkJRVWRFTUhkcVZXMVJRVUZDUVUxQlVucENSa0ZwUlVGclVVcDBNSGhYWmpSQlRWTUtTakZ2VVhoa2FUTm1jRTVWYldkamRWVjVSME4wYlZGVVNuRXlNVnBSYzBOSlIzQmFNRlZLWTJKeWVrRklTSE5PTkdObE0zcEJiRmRNV21KbWRHbGtTUXBPV214Q1JUQjVNbFpyWjNWTlFXOUhRME54UjFOTk5EbENRVTFFUVRKblFVMUhWVU5OUVVSVmFGWmxjWEk1Vm5SWFUwdDFjbFJZTkZGcFJWZG9TR28zQ2xWaFEwOHllWE5tVWl0R2JVcEhZa04wUjJ0dlJFTlBLMUZtVVZGeVYzaFRNR0pJYVhOM1NYaEJTMFpRVTNSQmFsUTJaRU5FTjBWYVVFUjVhRWhUSzNjS1FXZDJZMnhNWXpKSmVUZEJUMjR4UVZwd05YTm9lRk01YkUxdWJWa3JPRkIyU2toRlFrRkJMelZCUFQwS0xTMHRMUzFGVGtRZ1EwVlNWRWxHU1VOQlZFVXRMUzB0TFFvPSJ9fX19",
          "integratedTime": 1665692935,
          "logIndex": 5049709,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "d820d402e50b8ba4ca50888d46e42a84ba2721fb",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3245465785",
      "sha": "d820d402e50b8ba4ca50888d46e42a84ba2721fb"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

