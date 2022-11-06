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
| `latest` | `sha256:413892f4935dd9bb7772662308743a0545ed3bdfdbdd5fd9280598d4b7fadeb3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:413892f4935dd9bb7772662308743a0545ed3bdfdbdd5fd9280598d4b7fadeb3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:413892f4935dd9bb7772662308743a0545ed3bdfdbdd5fd9280598d4b7fadeb3"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "eb8d84deadff5e205f6e567698ba06b18b3837d7",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQDDCOgMOPvsds/PJZE/vCK35K96lOd1otVagnIhK6qlvwIhAMWlXk01a0n3ZwDKDTYWoZ5BJ/BzwLyOkXfwLLCHN8XF",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI3OTY5OGFkMTc1OGI0MmNiZDJiNjQwODYzMDY1NjYxYjhkZDg2ODAxNDNiZGQxNWNmYzZhMjA2OTQ0ZTIyZTE5In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUNSak5oa21mRUVBZHpkTy84TG14WlJ5M1ZZdTJwOVlPVVNiV2h6cnVJcHJ3SWhBTGpnWGxaam5LL25SNVFGZ3lmSXppNWRlVytZTDJmdEFYZkdNc1duVXUvSiIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwaFowRjNTVUpCWjBsVldHeHlWRGhJUnpoRE5YbExOMGRZUzJwSlFYSkxiRFJWVlZFMGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRKTlJFbDRUMFJGTTFkb1kwNU5ha2w0VFZSQk1rMUVTWGxQUkVVelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVV4V1VVeFQyNU5SRFpLYlZWeVprWlhRekZVZGpaaWEwTnJTbFpqYkVkVlJqWlRVM0VLY0Vodk1UQXlLMjh4Y1ZSSVMwMWFjVmg2VXk5Sk0wOU1aR0ZaVWxsbmVtdFdTMGxsYTFSUldIa3hPRXRsVXpOTldXRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlV5U2xOT0NrTlNSa2hyV2s1TWJGcE9UMk5aZVd4c1RuVjFaalZqZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd4WmFtaHJUMFJTYTFwWFJtdGFiVmt4V2xSSmQwNVhXVEphVkZVeVRucFpOVTlIU21oTlJGcHBDazFVYUdsTmVtZDZUakpSTTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEZjVGRSZG1kQlFVRlJSRUZGWjNkU1owbG9RVkJXTHpSSmFERUtaRmczWkU5VlRDc3pWRkZTTm0xV2EyTkxURmRLUkdkWk1VcFVabkZWWjBORmQyMTVRV2xGUVdsRFdHcENkazFZVkhWa01HMXZTbFkwWTI1MFFWUjNOQXAzWlVoR1UyVnRiMGxHU1VaemVEVlpTazgwZDBObldVbExiMXBKZW1vd1JVRjNUVVJoUVVGM1dsRkpkMFF4ZEhsWVVYQnhMMnd3YVVZdlUwWk5aWGN2Q2xJNFRsbERlbmhtZVVkc2NGcEZlaXN3YkVVNVpGWkZTMVJ4VFRKdVFWRldXa1ZZT1dsaGIySlFiR0UwUVdwRlFXOUJWbFowYWxGSWVEaHlOMnR3U0RJS2RrWkJRMkp1V1RBeWQyUkpNVE5GWldoYVlYSnJPVVJ1YjNoV1IyUTFlWFJJVG1jd2RXZFFWR3BLV1V4SFFYUTFDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667701128,
          "logIndex": 6593400,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "eb8d84deadff5e205f6e567698ba06b18b3837d7",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3402556513",
      "sha": "eb8d84deadff5e205f6e567698ba06b18b3837d7"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

