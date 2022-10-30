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
| `latest` | `sha256:104c0e908dec0c852a60a4147bc026f705f973843ba5fa356defe9e266e37d15`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:104c0e908dec0c852a60a4147bc026f705f973843ba5fa356defe9e266e37d15) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:104c0e908dec0c852a60a4147bc026f705f973843ba5fa356defe9e266e37d15"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "45131d27801bd7f7abf3cdb3f0c90cdbadebc456",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDY7TBQfMnr//dpZ/l6gY//xksYlH34+ydyCFLNGXdNpQIgE1AZ6nlrqnTNXG8jrSjowDzO/cJE+UW9AMfaM41OjXs=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIwMjc2ZDU0YWQyYjdjOWFmOTUwNDRmMzY1MTQ1MTA5ZjE2YTM2YzMyN2YyOWFjYThkYzNiZDhhMmQyYmE1MjMxIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQzArTFAzaVBjV0RlWHlQQ2JsQzRvNFNRQXNPTlkrZXh6RHJEQUFSNThqZ0FpQXNVUmUyQUxZMmRKTUUzNmZvbnorbGtJM0F6QytPSmE0Vk9jRjVyYU5zcFE9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlQzWnhWekV4SzFsdVJWUjVZVmR1YW14cWFXZHVkbkpwZEdrd2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFVFhkTlJFbDZUbnBSZUZkb1kwNU5ha2w0VFVSTmQwMUVTVEJPZWxGNFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYyU1ZrM1ZsbGFjSHBVVUVFeldIUktkWEFyUXk4d1pIcG5LMU40V25KaFNGZGlLMnNLYVdsalZEbDBWMWgxUWtKV2RTczJSRWRXZVVKWU0zQmhaa3BzTHpGUWEzWXdNSHBMT0ZkdU1GbENiRmRWU0ROMlpIRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZuTDFWR0NscEJZbm8yWTFrM2QzTTJiazh5YWpWTVduWXpjM1pSZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpCT1ZFVjZUVmRSZVU1NlozZE5WMHByVGpKWk0xbFhTbTFOTWs1cldXcE9iVTFIVFRWTlIwNXJDbGx0Um10YVYwcHFUa1JWTWsxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaERZa0ZuZFdkQlFVRlJSRUZGWTNkU1VVbG9RVXhaUTBoMmJXOEthbTlWUm1SdmMyNHJia1pNZFhRNGFqZzBXV3MyVEdkR1dub3dLMlowVWtkQ1R6bEJRV2xDZERCcE5DdEdNbk0wVGs1WVRrcFJUWE5qWlhkUlMxWXpVZ3AxUWpaQ0szZGhLM1JaUjJJMlRrTm5PWHBCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcENjRnBZYjIxMFJIazFUbE5FUTFOeFoyRTRTV3BzQ25KWE5EZGhURmdyWms1WFZHdFVkamt2U0VoUFkwNXRVVVJZTUdoV1ducHZMM0ZpUW5KUlUwbEZXRVZEVFVjdmF6TlJhSFYxYWtaNVNqZExZbE1yTHprS1V6Rnpka3MzV1RCa1IwUkRWbmwyWmtWUFdqa3lLMHR1WnpNMFUzQlNZbXhNUmtWaFJXRnphR0kyTWt4dmR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667097497,
          "logIndex": 6136340,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "45131d27801bd7f7abf3cdb3f0c90cdbadebc456",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3353810094",
      "sha": "45131d27801bd7f7abf3cdb3f0c90cdbadebc456"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

