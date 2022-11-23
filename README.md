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
| `latest` | `sha256:f55ae16fa7a48998b3b7491eadf9e4930770e306b1c7b286efb8341942e6af8a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:f55ae16fa7a48998b3b7491eadf9e4930770e306b1c7b286efb8341942e6af8a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:f55ae16fa7a48998b3b7491eadf9e4930770e306b1c7b286efb8341942e6af8a"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "2ebc74337223687d9e662eae610360abc290e4d8",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQD/Xrllby/5zvX/0B2GbfQLnaFSkWuEQs2h/ChCaZBA8gIhAKop+MLVbRau1MfP6uwQ3Xcveua4lnRvkxdQbsOzuAby",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJhMWRiMzZmNGVmMjNmMDAxZWRjOTNlMzUwOGVkMDllODYxNTBjYzYwNmI3Y2EzMmFlMGZlOGRlMjI0MDQ0MDRhIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRjFUSXpGSGU4SjlPblphd1BSRDhSZThweWZOc3NQSFkxekpwNUtZdTU4cUFpRUFoMDB1bkllRWRiK1BWZmxOL2ptTkFJYU1ORzQ5VUhXRzZaS0FDcCtxRG5NPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlZpdHhiRVZJVkN0Sk1GVXhTbms1SzBSNGFubzFXVVZWSzFaRmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1hwTlJFRjVUV3BOTWxkb1kwNU5ha2w0VFZSSmVrMUVRWHBOYWsweVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVV5WjA1RGNVcEJWa2d3VVhKM2VXNWtLMHhXYVZwTVFtUjRZbloxYzJrMmNpOXljVGNLWTJ0SE0zVjRNMFU0TUVKTlVFOHpZazF6WW1abGREbFFabkpSTXpGRVpVVlRkM0oyU2xkclEwWkRibmhoTTI1V1IzRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlV6VlRJM0NqUkVaRGxKTW1RdlpTdE1aM1pYT0U1NFFUUlhWSFpOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNsYVYwcHFUbnBSZWsxNlkzbE5hazB5VDBSa2EwOVhWVEpPYWtwc1dWZFZNazFVUVhwT2FrSm9DbGx0VFhsUFZFSnNUa2RSTkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaExTR1JrY0hOQlFVRlJSRUZGV1hkU1FVbG5VVzB4ZDJ0WWIyc0tkV1ZtV21aRE1IVktWa3RwVUc1YWRUaFhLekk0WWpKamIxVjNVMEpoVjI1Q09EaERTVWhKTUZOdlZXZEhWbUUzYW1WdFFuWm9XVlZwYzNWa1Z6TXZWd3BTWkVKcVExVTJTMDVtVjNkUlFuTTVUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRWRkVTRzkzYkM5dEwwRmxLMDlHWVhKdE0xSnliamhZQ2xkMVprMDVVSHBhU1VKQkt6bHlhV1JCTUZaR1prUkZOSFphUW1GemFURnNTbWxhUVVNdlVEQlJkazFEVFVORloxSnVhWFJ6YWxoUlZXNXFXVFIxYlVVS0wwbFhiMnRhZHpKSGFuVk5Ubm8zVmpOeWQwNU9WbE55Yld4U1VFRnBTRzFXY2sxWVRYUnZOMk5HV2toMFVUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669162989,
          "logIndex": 7652242,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "2ebc74337223687d9e662eae610360abc290e4d8",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3528172171",
      "sha": "2ebc74337223687d9e662eae610360abc290e4d8"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

