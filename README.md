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
| `latest` | `sha256:925d1d0b66c8a173f14cb709cce438fb9b8e75fb0b66c74c531d6b6127c7d13e`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:925d1d0b66c8a173f14cb709cce438fb9b8e75fb0b66c74c531d6b6127c7d13e) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:925d1d0b66c8a173f14cb709cce438fb9b8e75fb0b66c74c531d6b6127c7d13e"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "c0772a742bb4bbdcd8fbbf5a28d23b9a46bbc0bd",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIB6MoBCmJrSJQuqSepAC3ybOH77sJ1tgiohpgFcxjcfFAiEA1/2NRi9o2hPV0sb9vB6m1INY0aSsJbO4f1gwAoW6lao=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJlZjVlYmZiZGQyNDI2MGI4MjkzMzA0M2E5NjI5NTNmZTg0MWUxOGVhZTc4YzEwNTlhMmYzMzUyNDJkOTY5NjgzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRUNUenBTcWd2aXVwWUdpQXVOcjdKZkJUNlJyd29IZmd0VkRuYWt6Q0ZlaUFpRUE1cjBjS1pOa3FTVzlvQmUxbG1GZkRXT21HcUNPa2RSZnN1T0FqeE9GWElVPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwaFowRjNTVUpCWjBsVlZXOXNiVGNyZEhwWVZuVnlLMmt3TW1OeVFXNDNVWGhIUlU5QmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlRWTlJFa3dUVlJSZUZkb1kwNU5ha2w0VFVSRk5VMUVTVEZOVkZGNFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZEVW0xV1ZGWmlTM0IxVDJOd1NWVTFSRWhJTUVkRmJ6WlZiRTl6ZWpNM2MwdEpjV3dLVkRJMlVFWk9OMGt2WVVOTVExbG5RVUYyUzB4NmRHZEtaa3hpT1dsb1RXcHhSek4xYVZwd1dqUnBRMmxUVGtRNVNYRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZsY0ZaeENrbG1SVmxFTXpkWE5HWkpVa050Y1V0cVNqbFVSRWRWZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdwTlJHTXpUVzFGTTA1RVNtbFphbEpwV1cxU2FscEVhRzFaYlVwdFRsZEZlVTlIVVhsTk1razFDbGxVVVRKWmJVcHFUVWRLYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtY3JOR1ZQWlc5QlFVRlJSRUZGWjNkU1owbG9RVTlwY2s5VVQxTUtZVGgwY20xRFJtWkdjalJ0Y21oNVJFbHVOWGhTVjBST1dFczRaR0p6ZUU5MlptaENRV2xGUVhaeFJqWlhWVVpaT1dkMVZXbFROMnBTV1ZkaU1tWkdXZ3BRUW5Kb1ZUQk5iUzlvV2xvd01VaDVURWgzZDBObldVbExiMXBKZW1vd1JVRjNUVVJoUVVGM1dsRkplRUZMZERsalJFc3JWalUxTDNWMk4ySmFaa2RPQ210WVNuTXhXVGc1UlZsTmVuaGtkMFZEUWxack0zQnVRWEkzZVZRMkszQXJkRlZ5YXpWbVVIRk9kaTlwT0dkSmQxUkZVblJwZDFwYWVtTTVRV1ozV0hvS2NtRk5kMU40ZFdKcWJrVmxWVkJtTkdOT1NGVTNiMng2Y21nNWVUbFVablZCU0ZGSGRXUlJZMWRsYmtGSGNtaFhDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666147323,
          "logIndex": 5403000,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "c0772a742bb4bbdcd8fbbf5a28d23b9a46bbc0bd",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3278412005",
      "sha": "c0772a742bb4bbdcd8fbbf5a28d23b9a46bbc0bd"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

