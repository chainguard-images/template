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
| `latest` | `sha256:ead9f1e85d3aa5d02ef977ce7774ec281a08475418b3ccdf856e8332032a71f6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ead9f1e85d3aa5d02ef977ce7774ec281a08475418b3ccdf856e8332032a71f6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:ead9f1e85d3aa5d02ef977ce7774ec281a08475418b3ccdf856e8332032a71f6"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "d7de7da05f2f2767bf6c9c8129602020db3eb465",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIDBKrvtH458N7uMdAOROBxryqnBtIreNgWYQ9I+6w1VEAiEAsJSdRgYkk/f/Q2QVPX1eAZ01BxyP7rUU9QSbjqjPhAI=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI3NDZiZDM5NTY1NWY2MTA0MzNmZGY5Yjg3Yzg0M2ExOTYzZTJjYWVmNzYyODY3ZWRkYjYxM2YxNjA4NjE3ZDU5In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJSE5pa1JsekxZSmdFaGhsT0t5TmI0bDhTZmFISTNMS1FnZmw3YU85S1NqeEFpQU43NHlxak5QUzk4M01XR095VWIwQkpMWXR4ZTBaNURjRHVuOElFNnpscXc9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlRXOWhZM1o2UW5GS1pVNHdTMHhyY1RKUFlsTktkVmd5YUVocmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1RGTlJFRjVUa1JKTWxkb1kwNU5ha2w0VFZSSk1VMUVRWHBPUkVreVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVY2TVdkbmJHVndkVmxDTHpob2EyVjJWRXd3VTFCR1kwOTNkMmh5WkZaUU5YbE1kMllLZWtsSk1reExSblpxZVdSTVZsRXpOVzFQWW1GV05uUk5kVmM0S3pKU1VEaHdTRzlWV1ZaR1MzZDVLelYyTTJaQ2RYRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZTWWs0MkNsZG5ZMFZSZFV0VVZYQlFhR05FWlU5cE5GTnJkV0ZqZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd0T01sSnNUakpTYUUxRVZtMU5iVmw1VG5wWk0xbHRXVEpaZW14cVQwUkZlVTlVV1hkTmFrRjVDazFIVW1sTk1sWnBUa1JaTVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaExkM0l6YjBWQlFVRlJSRUZGWTNkU1VVbG5VVXB4YVV0RFNqVUtkbFZ2YXk4NWJ6WnZhelJZY3k5bGQyUkpVelF5WTFOTWRta3hVVlo1YTFSVFJVbERTVkZFVTB4dldXUnpOazlVT0hNeWNWaFNhSFp6UjBwbWFEY3ZRUW92YVZWeGJHZFZSMjlWT0RCWFkyZEZOSHBCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcEJaMkl5VlVKNVIyd3dkbkV4ZEVkaVdtNDFjbUpRQ25SbGFFdHlSMnh4VUVObk9FMXhPQzlRVkdGTU5XdFBOR2RpWVVkeE0weHlUSGh0WVRRd1NIWXJNemhEVFVaelRrdDVTelJYZVM4eVN6TXdZbXRSTVM4S2QyOXlNbVZzVlhBeVIya3ZUM0pDWjB4VVJuTk1VV0pVTDNGaVRHOTVWelZSVlZaelMzTlBPWE13ZFZkNmR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669335893,
          "logIndex": 7791963,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "d7de7da05f2f2767bf6c9c8129602020db3eb465",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3544392984",
      "sha": "d7de7da05f2f2767bf6c9c8129602020db3eb465"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

