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
| `latest` | `sha256:8e66db47d91fdfc0f891711a383ec171af2e4789363ad5fc77f136d579100811`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:8e66db47d91fdfc0f891711a383ec171af2e4789363ad5fc77f136d579100811) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:8e66db47d91fdfc0f891711a383ec171af2e4789363ad5fc77f136d579100811"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "66e3e77cf9aab9042a73e93400c4558d46209638",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIAJzUVmA5zmb5noZuAqCU684Vfu8mWAPVcVILD81VkpdAiBId6W6Ias86fq8VIn8ZiivUHYfO9PTMJLkHqKAwiO7dg==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyZjBkOGQxMWQ0ODY4YTRiNDk0NDFmMjg3MWVjYWJhMzg2NDVhODNiZjM2MjU3NzRjOGQwYTQ1MzNlOGFiNTA5In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJR1FzYzlQeVFjaVZMcEM5NmNHcEM2Uk5FcUt5dTBRUHltVjNsanJ5RWlxWkFpRUF2cTkxeVNoUDR5emVzcE5ocktnNWpUVlYxZHlCb25pdFZhb0QyTnZFQm9nPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlFrRlVXVXhtVldjeldWTjBWVnBRVkdObk5tOVBhMWxITXpOdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUVRSTlJFbDRUbFJSZWxkb1kwNU5ha2w0VFVSQk5FMUVTWGxPVkZGNlYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUxZVc1YUt5OHpTaXRUV2xOMEszbEpSak5EYUZKM04xaDZSekE1VEhObWRsazVkRXdLY2toVk5sQmxSWHBJT1hWU1Z5dHNaM0ZhVjFkQ1QwbGlUR2wzVTJWYWQxaFhPVWhRWmxoWGVqbG1iVEZFZDJobVZHRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZXTWpSYUNpdHFkMGRtWTJOR2EwNUZNR2hxYWtObk5tOUJkU3RKZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpKT2JWVjZXbFJqTTFreVdUVlpWMFpwVDFSQk1FMXRSVE5OTWxVMVRYcFJkMDFIVFRCT1ZGVTBDbHBFVVRKTmFrRTFUbXBOTkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzNWbWRtYTJkQlFVRlJSRUZGWTNkU1VVbG5TVXAwZGl0RWVFSUtXakIxYW5nelVHTm1aMWhEUkRJNFRFRkNlbk5yVnpaWVF6RjVWMWRDV25WMFZHZERTVkZFWVhVM05YcEZka1JCTm0xWmRVcHdWMFozVXpoNFQyUlBaUXB6TVhaR2QyaGxNRk56UVVsVmJVaFJTM3BCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcENNVk5OZG1GRFpXVkVVa3BVZWxseU5rVjBiMVV6Q2tSbE5ucHlObnBKWldRcmFqa3dlRU16ZFRKS1FtRlNURmRUVVRGc0wwd3JhVTExWTBOTFpqUkNlVzlEVFVOemNIb3ZkM2M1UTBkU1JEZFNTelUwV1ZvS1Z6SXpZVEUyTkdWUlIwSlNXa3hLUVhGRWFFVkdSSGxwTVU5R1MwSnRiRXN3UWpZeVUzUm1ZM29yUjFGNVp6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665195363,
          "logIndex": 4667966,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "66e3e77cf9aab9042a73e93400c4558d46209638",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3208773462",
      "sha": "66e3e77cf9aab9042a73e93400c4558d46209638"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

