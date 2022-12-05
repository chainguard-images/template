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
| `latest` | `sha256:3f7b14248d73d609416ddb2d8818e39763cb3fd561411abec3b5909ee98d50cd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3f7b14248d73d609416ddb2d8818e39763cb3fd561411abec3b5909ee98d50cd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:3f7b14248d73d609416ddb2d8818e39763cb3fd561411abec3b5909ee98d50cd"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "867ff6f0c70978b098c0df950544184b8ae474db",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCEQ86Koy3vGDmh6r55mvlcQBwBClB2DWOLTWEGCnp8mQIgcNgC3w6uSqgibAU+FZRRUR2C3wV7BaJAIirQFBa1+1A=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJkMDcyOGM2ZDc2NGU0ZWZlOTQzZjAyNjAzOWJmZWNmZGY0NGQ5MzA0ZDBmOGViMDkxNTg0NjdlMWM2MDgyM2U2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUURRTEhHTUJaNXlNZUVxSHV1eEMrMFluWFVqTDRidXVXdXNZcHZmeXVTZW9RSWhBSnc2eEhHZCtLK055UTUwNWNSait5Z25wMGVrYm9ZMlFVaVVZYnc1TzFvQSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwaFowRjNTVUpCWjBsVlFrVldjRVpHWlU5bWRFUlJRVzFMYkVZM05rOHlkVU5LVm1aSmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVRGTlJFRjVUV3BSTTFkb1kwNU5ha2w0VFdwQk1VMUVRWHBOYWxFelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZsUlRacGNrNXpVWFpwV2tKNWMwVXlPRVpSYTFSaWFGaFFXa1JWTmtKaFMxQkxVMWdLVm5ac0wwdHFXQ3M0TWxjd1luTmtRemR1YlM5U056WlVNV1I0Y1dWelQyTlJaaTgwT1ZWcU5HZHFVemQxUzIxT2RtRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZ1WVRSWUNqaFlWbEZOVHpCdFJHWnJOVFpHVGpabVEyaGxZamswZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpST2FtUnRXbXBhYlUxSFRUTk5SR3N6VDBkSmQwOVVhR3BOUjFKdFQxUlZkMDVVVVRCTlZHY3dDbGxxYUdoYVZGRXpUa2RTYVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE9LM0E0Y1hkQlFVRlJSRUZGWjNkU1owbG9RVXd5ZWpOcE5EY0taQ3N5UTJaTmFsWnFVakZaTkhoS1pqQmpRbXBPU0ZsSFJIWmFVVkJhZFRSU1kzRmlRV2xGUVRKWGNVVkJha2x3Y1ROT05UbG5hMUJIVGt0SmRqSm1NZ28wVGxabGVWRlhUVFkwTWxSTmFXRndjMDVqZDBObldVbExiMXBKZW1vd1JVRjNUVVJhZDBGM1drRkpkMDk2WVZsV1ZFZzBUUzlrVFc4MmFXNXVhVzVPQ2xGeE1WWnZhVlZQWmxseEwyZEhVWFpxVGtSSWEydFBWRTVhTlZoeEsxQmFTemsyWW14bVkwdDBiemxwUVdwQlpWVlBhelZRWWpWdWNVWm1iamRUVVRBS2VXVXpiM1JYWkdod1VXZGxWa1p2WjFGQk1uaE1lblZ3VkZKRFFWUkplbWxzYlhwTllVVmlhVEZGVEZkaWRYYzlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1670199786,
          "logIndex": 8418343,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "867ff6f0c70978b098c0df950544184b8ae474db",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3615780122",
      "sha": "867ff6f0c70978b098c0df950544184b8ae474db"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

