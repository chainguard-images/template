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
| `latest` | `sha256:507388659683cdc78debcae679dd1d28632760c6ad4540521e361ce0b382df33`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:507388659683cdc78debcae679dd1d28632760c6ad4540521e361ce0b382df33) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:507388659683cdc78debcae679dd1d28632760c6ad4540521e361ce0b382df33"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "791c2939c641b47fcc89690bd27a14d77310c17a",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIDqcm7gJc4J96qXJ0uFJ3vES1Mp5dWKl1pk9TkD5ALV6AiBZqsHaf4UfIqp/cq8CWHJa5FfbNMaRsL/7SvGrf9RFcQ==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJmOTgwYjkxYjQyYmQxMjY4ODM2ZTA5ODViNTI0ODBkNjUyZThjNjc4NDFiMWQyOTA4ZmJiZWUwNTIwZmEzYjlhIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJRDJKTTdlZm9jWjhyNVl1SFlXU0J2bk5OZUlqN3pGK3U1enRjVEVmdmJrOEFpQndKR1huSXJxbHFWQ0tuUjNwaEZCTjYrOUgrOS9NeXF2SDRZem5MdFVHY3c9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwaFowRjNTVUpCWjBsVlJ6SkxWMHgzY2tOUVlYSmhRVmxLYVN0WVRHRmxRVzl1TUhGamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlRCTlJFa3hUVlJGTWxkb1kwNU5ha2w0VFVSRk1FMUVUWGROVkVVeVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZpVEVwNVptMXlTVWRZZERJMFJsZDZWRlZqVkRSRlRFRnVlbEZPU1U5NmFYRmFLMFFLU0RkNlpuTjRZVXA0VkRNNWVWSnhjMEpXTkV0cFJWaEZNM0V4VHpBdk0wUjNLMnBCTkV0dmNqSXdPSHBtV0ZONGQzRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZHTkhKbkNsaEVXbEptU3poMlUyMVRaMVozVmtKRUwyaHVNMnRqZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpOUFZFWnFUV3ByZWs5WFRUSk9SRVpwVGtSa2JWa3lUVFJQVkZrMVRVZEthMDFxWkdoTlZGSnJDazU2WTNwTlZFSnFUVlJrYUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzVVbTVOZEZsQlFVRlJSRUZGWjNkU1owbG9RVTEyWW1wSFpYY0tlWGQzZGtwR1JTOHJTR1ZrU2pBNGNUbFdNRGxLZWpFMVFUQXJNMHR4TlVGU1ZHYzVRV2xGUVdsMmVHUTNibTFtWXpab1lsWlZVSGxxTm13MGMxQjNTZ3AzUW1kbVZscEViMHBOTkVWSGNpOXVZV0kwZDBObldVbExiMXBKZW1vd1JVRjNUVVJhZDBGM1drRkpkMVJVT0hKNE1tUlVaRnA0Y0ZZd1p6ZHlSVWRNQ2xsWlJWVnFXRGR1ZEZkQmFYTjFPVEp3VlVrNVZTOUlZMk5pU0hJNFVrTkVPWEp1TDB4SWFISXlTR1V2UVdwQkswNW1XRFZDTldod1YxbzRWak5SY0VvS05WTnRUbU14VUN0YVdVdHZjVVZOUjFVM1MzWkxXamczZDNoYU5YQk1lbTlvTlZCbVJuVkJSRFJ0V2xRMGNrRTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665715895,
          "logIndex": 5067010,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "791c2939c641b47fcc89690bd27a14d77310c17a",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3247109304",
      "sha": "791c2939c641b47fcc89690bd27a14d77310c17a"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

