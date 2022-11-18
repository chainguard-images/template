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
| `latest` | `sha256:0b9c4d617b931893633fc7012ba2c180e4fe81f3d7d4c3d7a6ee7bc8d811de48`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:0b9c4d617b931893633fc7012ba2c180e4fe81f3d7d4c3d7a6ee7bc8d811de48) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:0b9c4d617b931893633fc7012ba2c180e4fe81f3d7d4c3d7a6ee7bc8d811de48"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "c434517aec49baa57845db1afdf23ee748155370",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIAzzW6ZJ/qJlIi5+rzV+2/1l2nRLbVgjkUf7bdlhUXloAiBOYrmmMRDbLoOBRCKsr5JQ4C/kqgIQTbOek17phqOKfA==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJhYjhjZTA3NjUwNmNkZmE3NThhNzQxN2UyMTcyZjJmMWZlMTQyOTY4NTQwZTliZTM1MTI2ZTZiZmQyYmEwY2QzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJRVFhbytkQ2RPNnVjNUtvdlNhZHV1ZEc5cDl3bWZUcktwWGtLSWRLVHFyZUFpQjhRRlAyVmtpdFJKTU1UcmFOWU9HVHFLcGNIWlcxZXNFdWFpMnpkOFcrbnc9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwaFowRjNTVUpCWjBsVlZraFFWalZVTW1WaFowNHZkVzQ0Y2t0aVpuWm1MMlJ1ZVV3d2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlRSTlJFbDNUbnBCTWxkb1kwNU5ha2w0VFZSRk5FMUVTWGhPZWtFeVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZKY2k5YWNsYzBjemhCYjBwcU5IWjFNSGQ2VFVObVVUTTRURVZQVTNOWU1YZzNNVzhLY1VSUmJtMVNha1pTWjBZNFoxUm5lbVZyU0VaUVNXZHZjaTlDZGxsVkx6UTNVbFE1V21JM2JqZFFRV0Z4V0RGNWJqWlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlV6WmtsQ0NsUkhkSGt6WjJaamEzRmtURTkxUnpkaEsybDNLMjl6ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdwT1JFMHdUbFJGTTFsWFZtcE9SR3hwV1ZkRk1VNTZaekJPVjFKcFRWZEdiVnBIV1hsTk1sWnNDazU2VVRSTlZGVXhUWHBqZDAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEphRGxXTVZsQlFVRlJSRUZGWjNkU1owbG9RVXhRVEVNeVdUVUtSbm8zZG5Vdk5VdzFNbmRpSzFFdlVtSTRkamR2T0dKa2JrY3phWGR5TTI1SlluQkZRV2xGUVd0MlpuRlVhMlZZWmxGS09HOHlSRU5zVmk5TmJDOXVTUXBqWkVaWWJtbEVlSGt5VWtWV01XeG9XRmhCZDBObldVbExiMXBKZW1vd1JVRjNUVVJhZDBGM1drRkpkMUozTWk5Tk1Fa3hWSFJQTTBkWFUwaElablJxQ25GdFFWQnNObXRpYnpKaVIxUlpSazFCTUZsTVZUVXpVek5zTkd4TVozaDZVMjFZUXk5cVZXWmxWRTRyUVdwQ2RVMUtSSFowWVhscVZGRlJUMlJMYUdFS1R5OXVTMHR6ZGxOdU1UUjZWRk5sUzFOb1lqbEZVSFJYTlcxdlpVa3dOV1pXVUVKV09VOUdhakkyUlRoYWFtODlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668737261,
          "logIndex": 7313503,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "c434517aec49baa57845db1afdf23ee748155370",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3493576874",
      "sha": "c434517aec49baa57845db1afdf23ee748155370"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

