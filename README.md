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
| `latest` | `sha256:f836327710af88e73bed253a394810a7ef29a1740bca43e6b7d4eb0b8cc55aa2`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:f836327710af88e73bed253a394810a7ef29a1740bca43e6b7d4eb0b8cc55aa2) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:f836327710af88e73bed253a394810a7ef29a1740bca43e6b7d4eb0b8cc55aa2"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "ba47d12dc5c5353c0599c9d178174afb908ed888",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIDOYNu+H5WHR+IkNRFlK8jvPqkn4FtVG4NXiBVQODphvAiEAo4nNjObBztoyzymto+s8P9715UL1qD6druHBQOIzFkU=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJhN2JlNzU3ZjBiNzNlMWI0Y2M4ZTkwZDI5NTAzODA0NWNkOWM1YTcwZTNlOWZmYzU2YzVkZWQwM2VjYWVkN2M1In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJRStIUVgybXlqWVdDVG0xRXNDdHQ3Vm1zbWR6VUtYaXE2MzNSYzJRSFFzb0FpQWptNmFKSHI3aGZoS1Q4RVUwdUxmVjJQanZXV1JkbzhkdjlwVlJVREFvaHc9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlFrUnRVRVJqZEhVMEswaE5SMnBpUkZkNk4wUm1XWGN6TW1JMGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRCTlJFbDVUVlJGZVZkb1kwNU5ha2w0VFZSQk1FMUVTWHBOVkVWNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZVUjAxWGFsbGlhV2tyWVZKTlJIUTJjMG94YlhsdFdsSlRkRmRMYkdGM1Yzb3paMUFLYUVWeFdsQkVZM0pDU2k4NVQyVkVPV2swVmpGallsSktNVkZhYWpreVptSk9VVVp2YjNGWVRYVlVaRFIwUmtKVVRUWlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZUYzNKTUNuaHlWV3M1UjNvMU9WTkNWbEkxTUVSbGREUTVRa2wzZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdsWlZGRXpXa1JGZVZwSFRURlplbFY2VGxST2FrMUVWVFZQVjAwMVdrUkZNMDlFUlROT1IwWnRDbGxxYTNkUFIxWnJUMFJuTkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEZRbmhPZUZWQlFVRlJSRUZGWTNkU1VVbG5SR1ZTY2todEwxa0tVMmxFVWpWSU1GSjJZa2gwWldsTVNWZzViRVZ2UldKUWR6Vm9ZMU42UkZCYU5qUkRTVkZFTm14NmEwaHFUbTVWZVhKUGR6RnpaSFJwZUZOMGNVMDFhd281WTJaVFdqTTRTa1Z6WVRadFpWTjJkRlJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEZRVzFrVURoSWJuZGtNSE56VDFaS1lVUjVOMDFFQ2lzemNuTnhWME5hYzBsNVp6ZFRPVWhJY1M5Wk9XTk1WV3BEU3pCMVMyMTRXR3BQYVZKME56SmlOaTlNUVdwQmJYUm5TM2gxVm1OTGRWVmtSRFUzYzFBS1JrMDFTM2hLYzFCTFZrZ3pRa0o0ZW1KdVoxbzRURWRLUzFZdlJGSlphVFpUZGk5V2Ixa3ZXa1J4V1hSWE1sVTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667528496,
          "logIndex": 6462015,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "ba47d12dc5c5353c0599c9d178174afb908ed888",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3390756218",
      "sha": "ba47d12dc5c5353c0599c9d178174afb908ed888"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

