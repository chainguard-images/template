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
| `latest` | `sha256:01fcaa9e566ca80675483c04a716854255b0d338cfe692d1dbb223482c3b680f`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:01fcaa9e566ca80675483c04a716854255b0d338cfe692d1dbb223482c3b680f) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:01fcaa9e566ca80675483c04a716854255b0d338cfe692d1dbb223482c3b680f"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "e8d47d7aa0a88faa6c59be7b155ffa392ab9fb14",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCrHZNeZD3m08X4ls+CCKb2s9ci6jRobC0JlkMLjDEnxAIgK5USUkLBif0Xaw5sSOFW3nNvRKGDveri2XbXxPGr5M4=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyMzg2YjJjMWY4MzQ2NWE4MGUyMmYwM2IyMTdlOTIxMzVjMmM4ZWNmMTVkNWUzOWY4ODA0Nzk3ZmYzOGVjMGExIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRjJMMWxWVTczN2VqdFBnbHpNSmd5bXhlbW5NK0FVSHBSSCtvS09tcXJuNUFpRUFwd2kyTjRuaVFVVG1EYktaaVRPYy8rVlI2Zi9rYm5YckVzcXdpWWQ1OXljPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwWFowRjNTVUpCWjBsVldtTkpRVzA1ZERsbGRGbGlSMmRaZFhKR2VqaE9lVmR6ZEdKdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlRKTlJFa3hUV3BOTUZkb1kwNU5ha2w0VFVSRk1rMUVUWGROYWswd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVY1Vlc0MFVtRnhOelppV1U5bmQxZEhLM1ZCU0hwTFRXUmFSWGwwUzI5a1pqWlJXRmtLT0RBeWIxSkJXazEwZGxOUVVUVXJVWEp4U0VaTU1GbG9UMlZTU1ZaRFVteFdiWE50YTFKeVUyUlZObW96TWxKUWQwdFBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZVU1VNd0NqRkpPRGx6UzFveVIycFVUeXQwV0ZCbGIzbEtibWxSZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd4UFIxRXdUakpSTTFsWFJYZFpWR2MwV20xR2FFNXRUVEZQVjBwc1RqSkplRTVVVm0xYWJVVjZDazlVU21oWmFteHRXV3BGTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzVOakZIY0RoQlFVRlJSRUZGWTNkU1VVbG9RVXRXUTFkRlVDOEthV2x0Y1U1WmEzSmlkVnBDVmxkSE9VZ3dWbEU1YlVoQ2VWSkJTRnAyU2xkTGNYUjFRV2xCYmxORmEwWmhNM0o1V2tGMVVrRmxkMFpJUm04MGRXcERNQXBoVm1wVWJHeENaMlJ1WTJaQmF6STFlR3BCUzBKblozRm9hMnBQVUZGUlJFRjNUbkJCUkVKdFFXcEZRWEJhVnpOcmMxTnZOR2hIYm5SYVUxcEdiRkJwQ21sTVFYTkhSV3h2TVU1V1RrSTBXVTFPVmtsT1ZrVkNka0pvYTNSTU1GTlFkbGh0Um1zMGJIbE1SbEV2UVdwRlFXNXJTV1V6Y1Zkd1JGZEliMU4wVDBVS1dVMXhiekZMV0ZGaWNVUkNRMVl4YUUxU1VuVm1lbUpsZERKaWVrcENhSGhhWTBaNFRuTktOR3hhU0VkR1pIUkRDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665888773,
          "logIndex": 5191988,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "e8d47d7aa0a88faa6c59be7b155ffa392ab9fb14",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3258013599",
      "sha": "e8d47d7aa0a88faa6c59be7b155ffa392ab9fb14"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

