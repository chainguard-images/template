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
| `latest` | `sha256:d8a2a6efd9c31eaa87ea4c39fc4ff47da632810939f26ae8f8a085daff8b50b4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d8a2a6efd9c31eaa87ea4c39fc4ff47da632810939f26ae8f8a085daff8b50b4) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:d8a2a6efd9c31eaa87ea4c39fc4ff47da632810939f26ae8f8a085daff8b50b4"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "86163478d3f7c72ae3820b5fb2068ee5bd03acca",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCGLT0eLcXu7jNQxMRsxBpbxlv1mNRtfQMaNcqVP/jphgIgZN4jEwdnbkBs3gfVi0evwGWKGcD5+zRT75fvYderKgU=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiMmUzNzRjOTJlZjJiMmE3ZjBhMmM2ZTEzY2NiNDIyZTY2Zjg1ZTRhNzQwZGNkY2JiZDE3MGRiZjJhM2FlZjc0In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURmWnZrMnJHSEtvVTZvYjJ3L2w3TFJHSkVkNXFESDV3aXVjRStUb2JubDBRSWdCeE9xNzRDMFgzN1dSYyswa01xRmhyOEx5T2x1QWYxQ0NWUnN5bzExS21vPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlWRU5EUVhwTFowRjNTVUpCWjBsVlQyTmpTME01VTBwblZqSk1UbU5UUldnelYwSk5ZVWN3U0RodmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlhwTmFrRjRUbnBOTWxkb1kwNU5ha2w0VFVSRmVrMXFRWGxPZWsweVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVV4UmtkaVYyUk1iV1V3WkZwaEszVTViVWhqZEhSc2VFaFFlalF4VEhrdlZsQndOVzBLVUVWMU1XWm1jM0ZtWW1kTE9HNDJMekpTWTJWTFVtOWtRVFo1Tms0eU4yRkxUa2xEY1hCeWFUUllWMmRqVjBoRU0wdFBRMEZzUlhkblowcE9UVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZGZEV0dUNpODRlRWRLUW5sTVlXbFFla3hwUnpGM2VqRmpXVTlCZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGVFFtZHZja0puUlVWQldVOHZUVUZGUTBKQlVuZGtXRTV2VFVSWlJ3cERhWE5IUVZGUlFtYzNPSGRCVVUxRlMwUm5NazFVV1hwT1JHTTBXa1JPYlU0eVRUTk5iVVpzVFhwbmVVMUhTVEZhYlVsNVRVUlpORnBYVlRGWmJWRjNDazB5Um1wWk1rVjNTRUZaUzB0M1dVSkNRVWRFZG5wQlFrSkJVVTlSTTBwc1dWaFNiRWxHU214aVIxWm9ZekpWZDB0QldVdExkMWxDUWtGSFJIWjZRVUlLUWxGUllWa3lhR2hoVnpWdVpGZEdlVnBETVhCaVYwWnVXbGhOZG1SSFZuUmpSM2hvWkVkVmQwaFJXVXRMZDFsQ1FrRkhSSFo2UVVKQ1oxRlFZMjFXYlFwamVUbHZXbGRHYTJONU9YUlpWMngxVFVsSFRFSm5iM0pDWjBWRlFXUmFOVUZuVVVOQ1NEQkZaWGRDTlVGSVkwRkRSME5UT0VOb1V5OHlhRVl3WkVaeUNrbzBVMk5TVjJOWmNrSlpPWGQ2YWxOaVpXRTRTV2RaTW1JelNVRkJRVWRFTUhZM1NWUjNRVUZDUVUxQlUwUkNSMEZwUlVGcVZsVTRVWHA2WVVsQ1RUY0tVSGt3ZWxsVk1XUjFlUzh4Vm5GdlZETlVaRXBuSzJWa1FYWjZTbTFrVFVOSlVVTm1XVFphYkVSaWFrYzJlSEIxVkRnM0x5OWlWR2MzYkV3MFVFYzVad3BsTDNnclkxTXZURnBDVUhCM1ZFRkxRbWRuY1docmFrOVFVVkZFUVhkT2NFRkVRbTFCYWtWQmRpdHJla1ZCZVdsMFFWaGpPWFExTm1odlZ6aGFSSGxOQ2xOUGJqVTVSa1l4TURCeVExUlVPRGw2SzNOSldqUjZOSEUwUjFScFpsQllVRzg1U1hkTFJVeEJha1ZCYTJkcGJuUldXa3h5VlZkMlRWWkNWaXRFUjJVS1JXMVhhMDQyVkRoUlNuWTNNakpETkVkcGRWZFJUMGRIWW5KTVpVdElUbXc1WjJ4eGQwcHpPV1pRYm04S0xTMHRMUzFGVGtRZ1EwVlNWRWxHU1VOQlZFVXRMUzB0TFFvPSJ9fX19",
          "integratedTime": 1665692275,
          "logIndex": 5048942,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "86163478d3f7c72ae3820b5fb2068ee5bd03acca",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3245402641",
      "sha": "86163478d3f7c72ae3820b5fb2068ee5bd03acca"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

