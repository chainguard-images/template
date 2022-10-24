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
| `latest` | `sha256:9d9de374c98c00fa951af5cf5f0ee49d228e671cf3417eb4e14141e5f5a8d07a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:9d9de374c98c00fa951af5cf5f0ee49d228e671cf3417eb4e14141e5f5a8d07a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:9d9de374c98c00fa951af5cf5f0ee49d228e671cf3417eb4e14141e5f5a8d07a"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "7536a0d5227b2d0f4b6fc8b7894778703497fb34",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQD43JEVnSgzpce4eMzVE+eB0E1w1sEHvabZx53BNuEfeQIhAO9UzyRv8mUEcZUDp+VfAx+1ssdqLMvNtEM7r+TpJu07",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJhODMzMDQwZDc2MGFmODVhZTM3OTlhNjU0Mjc5YjI5YzBiZTk5OGIyYzFlMzQ3YzM0ODVjMjY3Y2FkZDk5YjA2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJSGNRenQyUW9rZ1piNS8rQkNhbUYxNmo1dHdNeXZVSTJUYUVrdFNndU41MkFpQWRvSUNaR0Vxam9KVUNGNFpwVDVjc243NUxrVEhWS3l2MlVjMlJKN1RpM2c9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlVWTmtiVzlQV1ZCQ2RWaDBObWRtYzBReWRIcHJNRmRCVlVkdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1RCTlJFa3hUa1JGTkZkb1kwNU5ha2w0VFVSSk1FMUVUWGRPUkVVMFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZvYkc4NWFtTjVabmhwYldjclQzSlNOamxXWWtWR1VrSTFVRzUzWTBadVdXMVpRWFFLZVRSME9IazJNRzUwWW1nMmVIaFZZWE5JUWtwUGMxZFBiRWwzUjBGVE1GaFFOMnc1WWxsQ2FVTnNURVJEZDNkVU9IRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZqSzA4eUNsWnFhakp1UVVKUGJqSjRWVFJ3VFdaMWRFeHJVRWhGZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpOT1ZFMHlXVlJDYTA1VVNYbE9Na2w1V2tSQ2JVNUhTVEphYlUwMFdXcGpORTlVVVROT2VtY3pDazFFVFRCUFZHUnRXV3BOTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaEJabkJyYW5OQlFVRlJSRUZGWTNkU1VVbG9RVTlzY1VoV05Fa0tObXRWUWxoRFpEZFdWV2s0ZGpkd1VFbDZMMmsyVnpaNlZUaFNTMVVyVkV0TWJtcHNRV2xCZG1JelIzcGtWRXhLZFd0SE16QnFTREpqTVhSeWVWUmxVUXBLTTBWalRHeDJkbU5rYkdKVllUaEVSa1JCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcENlVGRCYlVVdk4yUjNTRTUyVTA0MmFscERSWFYyQ2pabE5rdFVTbXAyZFVFMGEwdHNURkEyUVdkSE1HVlROa3d6VXl0WVluaHhUVVY1UVhkSlRtbDNaVEJEVFVoYVN5dFplbTVXU1ZaTFVFNXRaMWt3TldNS2EzbEdNMkZxTjFKUk9VaDBZeXR4ZVVGQ2JXSjVhVlU0U0ZWNlJreFZObUpOYjJodVlreElSR2t3V1RnMFVUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666580076,
          "logIndex": 5735056,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "7536a0d5227b2d0f4b6fc8b7894778703497fb34",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3309656039",
      "sha": "7536a0d5227b2d0f4b6fc8b7894778703497fb34"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

