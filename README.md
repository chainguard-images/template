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
| `latest` | `sha256:30f256cce20e2e8e6539ca52d2f48102b77f0dcecd3d31192e55f903faf8a9ba`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:30f256cce20e2e8e6539ca52d2f48102b77f0dcecd3d31192e55f903faf8a9ba) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:30f256cce20e2e8e6539ca52d2f48102b77f0dcecd3d31192e55f903faf8a9ba"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "66b22da5526cef6c6cdb1a6fee563a1c9f6631fd",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIGjU8T4iNFAPoZags3V534pJBXDTFIKuQ+nKveKlRbCEAiBEOC9ESAqqXtdzfSKBDhACt9GttqYpQfx0FbKz1LtsZA==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2M2ViZjliZTI1NDMwYmI4MTdiMDY5Yjk2NGRjOTM0MGUwYTNjYjM5MTA3Mzk1NDAyYTNjMGM4YTI4ZWU5MjgyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQXY0NitWdE53NjB0QVh2ZjJSbUhlUnpLTkZCbkI3czJJSXcvT3JNVTh5ZkFpQnM1ejU2NjNqNFBnVjF4OWZrWnQ0OFc0aGo3cVhnbnc3aEZ1dUV5cGt2cVE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlZWRnZSME5yUzFWcmJrTjNTSFY2VEdVd1VHdHZSV1pXVmtVNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlRGTlJFbDNUWHBGZWxkb1kwNU5ha2w0VFZSRk1VMUVTWGhOZWtWNlYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZhYTFNcmVUZHRka000Y0dKUmFrbEJZVGRSUzNRd01HWkpjWFIxVjB0bFdVMXhUV2NLUTFoek1uUXphWGRMTjFNeWJGcG5Ua3QyTDNkM1lqWkVRVFJzUkN0WFpXSkJTVlo2YkhWRVlUWjNWMUYwTldSaFprdFBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZ6U0ZaQ0NuSlpiRlkxWjFJeUwyeEVVR0pJSzJ0cmFuVlNaVlpqZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpKT2JVbDVUVzFTYUU1VVZYbE9iVTVzV21wYWFrNXRUbXRaYWtab1RtMWFiRnBVVlRKTk1rVjRDbGw2YkcxT2FsbDZUVmRhYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaElhMGQwYW1OQlFVRlJSRUZGV1hkU1FVbG5aa1pzZHpkdlZXY0thazVQWm5WQldsZE5PVFI1SzJwTk4wNXFia0pEZUZGMWNrVm1kREpUVWs0eVZFbERTVUY0ZURKVWRWUnNVRk5pV0RCUFJrcFlkM0pwWTFOemVYVnRUQXA1VEU0d1YyZHlNMWcyTVVZM1ZrRmxUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRVaEpkVTFKVGpsS1FtWTBRbXB4Y1RCNVZHWk9TbmxpQ2paVGMxWjNlbU53TjJGclUwaDFOMGRXYlVwcFpXUnpZWEphZFhOMllqaHZja05LZERSaFdGVnhVVWw0UVU4ck1FVnZVbEl6Vm05Wk56QndNRWRUVVNzS1QwWjZSRzFuUjB0QldIcHJabWwwYkdsTGR6QklWVmsxTVZoeFR5dFlXbTFEU0U1UFNFUXlUVW92VjFSemR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668477826,
          "logIndex": 7096394,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "66b22da5526cef6c6cdb1a6fee563a1c9f6631fd",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3466795016",
      "sha": "66b22da5526cef6c6cdb1a6fee563a1c9f6631fd"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

