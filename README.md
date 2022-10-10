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
| `latest` | `sha256:7d7e728f2f8d7cb26ef7211c066f7751da4d500d6b7d26a7090c61794ac183f4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7d7e728f2f8d7cb26ef7211c066f7751da4d500d6b7d26a7090c61794ac183f4) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:7d7e728f2f8d7cb26ef7211c066f7751da4d500d6b7d26a7090c61794ac183f4"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "ed2422b33b5da75b040f0d8314d03c54ffcaa4d9",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQDYZxUE8CKUQnfPljhYpC6QZrI2QGe4f85g7NT4oWlJfgIhALdSt1vFcfq+XAyUu6SmEtTnhy/g31kQIXeojVZqslRt",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyYTMzNTMzYWE5OTdmMjY1YmE0OWFhOWE3YzM4YzFiZjFmNzc3NDNmMDI0NjA3OWUzZWYwZTFmNGJkNDVkOWE2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJSDV1enVHZVVyN1pucFBDbW9jVjRMeTIvd0l2VHpDM3lncU5SNGdrbkJmdkFpQWxVT2NNOGxWajUxc3ZzblAwWVpQWHp6SUdOcDdRZ01yc0VndStQeUd0M2c9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwVFowRjNTVUpCWjBsVlJUZElTMnd6SzNkblVXTmhURU5FYTJ0WE5XZHpWRzlRVURKbmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlhkTlJFa3dUVlJCZVZkb1kwNU5ha2w0VFVSRmQwMUVTVEZOVkVGNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZWYkRKSVUweHlVVzFJT1dVM2NFbGFZMkpzYlZGb2MyNDJOV1JTTjNWbE1GTnhjRWdLYVhrdldsaDFSRzlZYWpadFUyaGliMWRTZEdjMGNUUnhUVkZZVlZaRGRtSTJOVmszVTBWRVFqZE5XSGxxTUZWbGJtRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZzT0VSdkNsQlpRVzFyTTBaRVVtRklWME5WVW1aUlVHWlFTa2t3ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd4YVJFa3dUV3BLYVUxNlRtbE9WMUpvVG5wV2FVMUVVWGRhYWtKclQwUk5lRTVIVVhkTk1rMHhDazVIV20xWk1rWm9Ua2RSTlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzNMMFZaYlRCQlFVRlJSRUZGV1hkU1FVbG5RbUYzTURWbGRUUUtZamRZWlRCWlIwUm5TRGgyWlcwNWVIZzBPVk5HZDJwTE1WQXdaRlkzUzNwRmFFRkRTVVU1UkRoQ1VWUjRUMk16VVhRMmVFTTROSFZQTjNScmRHdEZjQXBGZWpCeGMzRTNkM3BySzNwc01FSk5UVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlhMEZOUjFsRFRWRkRabE5sTVdVMGVsTnRhbVpNUjBvelFUZDVTRlJYQ2xGTksyNWFNak5GU0dKdWFXMVFRV05WUmpGM1dHTlpiRXg2Y1VkcVRqa3plazR4UkhSS09EQkdkbmREVFZGRFpGQlpPSFZwWmxoNk1IQmplRzB3YVVZS05WQTJhak53YUVRMVdtUkdTM1ppZGtaQlNXVkhWMFZxTmxod1JVWXpaMmhpVjFwbVUyd3ZiRmw1TTI1RFdqQTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665369685,
          "logIndex": 4788929,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "ed2422b33b5da75b040f0d8314d03c54ffcaa4d9",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3216539120",
      "sha": "ed2422b33b5da75b040f0d8314d03c54ffcaa4d9"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

