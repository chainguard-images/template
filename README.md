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
| `latest` | `sha256:b141a292980c093e6674efe050c51049950ee58c9dd441ea57424707baf47af0`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b141a292980c093e6674efe050c51049950ee58c9dd441ea57424707baf47af0) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:b141a292980c093e6674efe050c51049950ee58c9dd441ea57424707baf47af0"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "e394fe74d101ce56602233d55f4d3cdad4ccac52",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQD7+p+B5rnqnHoAmF1ji8GCkTFeVck1oD2xguLTv8nVfwIhAMyemvvprwavqQZU7Fpr+Yf9VSF8mXQ+GJmNVUhhyXy8",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJjYjIzZmE5ZTliNmI2ZDZkMjQ3OGVkY2E1MGIyODMwOWQ5YjkzZGQyNmUxYjIzOGFkM2U3ZTAxOWFmYjAxN2Q4In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUNoWnBuK2w1bzRROVQ5VGRYMUpNN2VsanV5QmNMUU5FaHlvUEYwQ3ZjS1lRSWdCeWJNaEF6UUZ4MmtoNkRGUlVEdVlvMU1JRkd3UlplTXJOQkM5U3RncUQwPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwVFowRjNTVUpCWjBsVlprVkRiR1E0TjFGVE5qbERNMVI2U1hwbGQxRjZVazVLWVVOUmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVhsTlJFbDZUVlJKTVZkb1kwNU5ha2w0VFZSQmVVMUVTVEJOVkVreFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZxWkdKREwwOHhObTF5Unl0eE1GQlBRbVZqVVRkMGNtbExhMDB2WmxZMlVuSjJNM1FLZEdoWVoxTkxkakJvZWpRclIxTldaRTVXVVdwWVNIaEdibTlyYVdoalMyTXhlbUpGVWxwWUwyWXpkMDVPY1cxQmVHRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZ6WVdaWkNqRlBlbXMxZGtoRFRWSTFhbkpRVmxGM1ltZHlkMGhaZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd4TmVtc3dXbTFWTTA1SFVYaE5SRVpxV2xSVk1rNXFRWGxOYWsxNldrUlZNVnBxVW10Tk1rNXJDbGxYVVRCWk1rNW9XWHBWZVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEVXWFF5YlhOQlFVRlJSRUZGV1hkU1FVbG5UMWhaTUVscmNFb0tWRmhzTkZKb1VqWllZVmxWWnpoMVYxZ3hXRUpCZVc4MWJYWkpOek5wU2tocVRtdERTVVl2V25NdmNrWjJSMFUyWjNkTWNDdDRUMk00VEhkU1MzcDVhZ3BxYzJOU2FrTkZhVFpNZHpKS2VIcERUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlhMEZOUjFsRFRWRkVMeXRyUW5WUFUwdFdMMmx3WjA5alp6TldaRVpMQ2xWSU5uVnhhM1JsTHpkWU1uRlJTRE55TW5KNlJtUnZkR1JuV0dSMk9XdHNaVk5VZHpsbFNubFFkbmREVFZGRFlWcFZXWFpPV1d4ck9UUTNTbG95TjBzS1NtNUJZazVNTjI4eFprbDZTMGx0TW1sSWIyeFNOVlF5YTBsNE1FdG9kMWx0ZERCSVQyVnJSMDU1VTNsSFNFMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667356324,
          "logIndex": 6328272,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "e394fe74d101ce56602233d55f4d3cdad4ccac52",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3374397847",
      "sha": "e394fe74d101ce56602233d55f4d3cdad4ccac52"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

