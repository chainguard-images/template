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
| `latest` | `sha256:a4c241b733f2e4d7e368b84249786ad0cb2253b72fa3dd9ce4e8bd0b7cd18ad4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a4c241b733f2e4d7e368b84249786ad0cb2253b72fa3dd9ce4e8bd0b7cd18ad4) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:a4c241b733f2e4d7e368b84249786ad0cb2253b72fa3dd9ce4e8bd0b7cd18ad4"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "5e8c0be76fbed9157bb5618914d279911c7f618a",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQCYS3zdB2sMrzF13OU4bc/8C8txUhhb+Sd3wtsC5xRoVwIhAPC3+f1QrSGo0TCrgSk6WS70mj/P/8fo/fUix1i2vhbC",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIwODZiZTcwZDljMTAwNDkzNGMzZGM2NTU5YTAxNjk1NWU5ZWUyYjVkNmVkMzkwYTEzMGRmMzcyN2NkZWMzYzViIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURtdlVuaENVQ3EvREcyK0dGbjNvelZZanRaajFKdFhjTGNvTktPalQzUHVnSWdjRWF5ODFQQjFyOUNpQ2RhcFlCamJPYjUwMSsxTjhvdEp5S0gvbjBDeDRvPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlWRU5EUVhwTFowRjNTVUpCWjBsVlJVSXhhbmRITm5OVk16WklWRWN4U0hZMFpXWlpXWFJ5TkdkM2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRCTlZFMHdUWHBKTUZkb1kwNU5ha2w0VFZSQk1FMVVUVEZOZWtrd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ0UWpscFJHMXZXbVJXVURBdlpqRkVkSE5hV0doek9YQjRXWE5EU2t4YVdUaGhaRElLWlRRM1MzSTJLMVprVlhsWU0yNWhTbWR2UldzdmRubFpaazVQUkRSSFZYWnFWVVJ5WlV0NE0xUjNSWEJWZDA1cGVtRlBRMEZzUlhkblowcE9UVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlY2TmpsSENscG5ZVzlsTWpOTmQySTFPVVZRYTBReE1YQjBTa1pGZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGVFFtZHZja0puUlVWQldVOHZUVUZGUTBKQlVuZGtXRTV2VFVSWlJ3cERhWE5IUVZGUlFtYzNPSGRCVVUxRlMwUldiRTlIVFhkWmJWVXpUbTFhYVZwWFVUVk5WRlV6V1cxSk1VNXFSVFJQVkVVd1drUkpNMDlVYTNoTlYwMHpDbHBxV1hoUFIwVjNTRUZaUzB0M1dVSkNRVWRFZG5wQlFrSkJVVTlSTTBwc1dWaFNiRWxHU214aVIxWm9ZekpWZDB0QldVdExkMWxDUWtGSFJIWjZRVUlLUWxGUllWa3lhR2hoVnpWdVpGZEdlVnBETVhCaVYwWnVXbGhOZG1SSFZuUmpSM2hvWkVkVmQwaFJXVXRMZDFsQ1FrRkhSSFo2UVVKQ1oxRlFZMjFXYlFwamVUbHZXbGRHYTJONU9YUlpWMngxVFVsSFRFSm5iM0pDWjBWRlFXUmFOVUZuVVVOQ1NEQkZaWGRDTlVGSVkwRXpWREIzWVhOaVNFVlVTbXBIVWpSakNtMVhZek5CY1VwTFdISnFaVkJMTXk5b05IQjVaME00Y0Rkdk5FRkJRVWRGVVhWSVMwcG5RVUZDUVUxQlUwUkNSMEZwUlVFNVpXcHdXRlEyTVZabGRXWUtWbkpQTDFoS05WSnJaM1JVVmxkU2NTODRSa3RIYWxGQ2JtcFBWVFZPWTBOSlVVUmlabE5pVmtVMFEyZDRaVzVEWTJKbGFtZDJSVXRyTUdSR1JGTktUd28xTDNKQ2RXMXljWEpJV0ZsaWFrRkxRbWRuY1docmFrOVFVVkZFUVhkT2NFRkVRbTFCYWtWQk5ETkVXSFIyUmxaUmNrczVWMFpUYUc5dVFqSmliMWR2Q2pKNGRXVldOMDl0UTNjNFMyVlVhbloxVnpGU1RIZGtZa2swSzFWb09XaFdjVWROYTFnMGRtRkJha1ZCZEdOSGNqTTFhV2RxZFd4V2JsZE5kVlYyZEVjS1NsTlJTMEV4VFhsbU1ucFpSV2haVUdZeWFWQjBTRFJGVmpCVFpYQmpOSHBVTXpaWk1EWnBja1J0TXpJS0xTMHRMUzFGVGtRZ1EwVlNWRWxHU1VOQlZFVXRMUzB0TFFvPSJ9fX19",
          "integratedTime": 1667569426,
          "logIndex": 6493394,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "5e8c0be76fbed9157bb5618914d279911c7f618a",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3394234984",
      "sha": "5e8c0be76fbed9157bb5618914d279911c7f618a"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

