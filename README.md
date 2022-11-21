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
| `latest` | `sha256:06359a017ba394973de45fd93b451e5c1cb74b40ab849cc12e43cf6f72817f3d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:06359a017ba394973de45fd93b451e5c1cb74b40ab849cc12e43cf6f72817f3d) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:06359a017ba394973de45fd93b451e5c1cb74b40ab849cc12e43cf6f72817f3d"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "e0a1154d2ac6ae14810b0f1560d0d8d725415c54",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCZ9zFrplu7JcYYkC7+CzzLts5mW8aYJjiynI0uFNZToQIgU9rv0Lx3kvF/BSJZnLdevGodHCZWpD0bpZ1+rydFVNI=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2ZDc1NDI2NWE3ZDdhYmI0NjE5MWY0OTk2MmNjZTQ3Yjc2OTlkNDJiMTVhZjcxNDYzY2ZiZGYzYWY3M2VlZDFlIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUURFT0pqcVg3UytQUWlVQ2UrYmdUSE8xZTJBcFRoV0JyQnh1NjljTHN4ayt3SWhBT2FMVmYyWU5QSWtMMGxsS1JpQWVEbGhFVmV2dTMyVnpYdG9HVXhMUm52eCIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlpHTjZkRVU1WldveVJWQlNSVVp0UW0xNmF6UXhTVEIzVUVkWmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1hoTlJFbDNUWHBWTUZkb1kwNU5ha2w0VFZSSmVFMUVTWGhOZWxVd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYxY1ROaFFpOXJhekJSVTJscWJXdHdWMXA1TkhWQmVYSlVVRTE0V1hnelpXTlFWbFVLZUZKM04zcGxZbVZyVlVKUE1XdGFNemRUTkVrelRISlZkRTF0WnpSNGNWaHhVV0UyWTNGNU9YQlRlalZUU0VkWWNuRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZCTlhwRUNtUlNiME5RV1RsWFJtbG9TbU5JVW1jdk0xcE9hVk5yZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd4TlIwVjRUVlJWTUZwRVNtaFplbHBvV2xSRk1FOUVSWGRaYWtKdFRWUlZNazFIVVhkYVJHaHJDazU2U1RGT1JFVXhXWHBWTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEtablJtWmpSQlFVRlJSRUZGWTNkU1VVbG9RVTVKYWxwMVVIb0tNRlpCUkZaUWNTdElPVzlHUjFWaE4zWnVXbHBQSzJwVGVsaEVjRlYyVTNOMFpqTTNRV2xCVVUxbmRqSmlSbmh1Y20xVGRUQTVXVGs1TTA5a2FXVnZhd3A2VDJsUWVreGhNMVpIVkhkNFREQXpia1JCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEZRV2h4VVd4TmNsbDZNV2xtTWpGNGFFVTVVamhIQ2k5T1RHRjRkSFJ3YlRsWFJXbE9jakJIZUhKNWNFVmlLMGRaYVVzd1kwcEpLM1IwWWpKUVJYUTRXbFIzUVdwQ09YWm1OWGxtYWxack5IVkRWV00zTkZvS1UyUnJTV1kzVG01VVVqRmhRbFEyWXpsVlprSk1TSFl5VkZCQ1dtMU5TMlZ4TlZnNFZXSkVSbWhHVHpsV2JtODlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668996259,
          "logIndex": 7510842,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "e0a1154d2ac6ae14810b0f1560d0d8d725415c54",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3510847069",
      "sha": "e0a1154d2ac6ae14810b0f1560d0d8d725415c54"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

