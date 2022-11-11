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
| `latest` | `sha256:fcd86a14b0853cdc620c86096d7437bc103f69f68f7cb6005e8d7242f8635a48`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:fcd86a14b0853cdc620c86096d7437bc103f69f68f7cb6005e8d7242f8635a48) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:fcd86a14b0853cdc620c86096d7437bc103f69f68f7cb6005e8d7242f8635a48"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "1ab7bd49c3eb2837aa57a060adf01d0c41e0a87a",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIDwA6Z4ZAOzquMgTD1b9Fr07fp7x/EA98QvlrvZ7gkQpAiBxDct9ciOFwNeeL3AxTvQ0TLw9G8hUnKD9jwHMCM5Luw==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIxMzNhNzZmYWFhN2VlZTUxOTNjNGQ4Yzc4ZDM2MTFmZWIzMjRkYzdlZmFkZWRkOTNmM2Y0ODYxOGFhMWJiZTQ4In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUNoZWppWUxMOHQ2TkhLQkdWYmlhN095R0NwVWxNbjlUR01JbjhWUWhWOE5RSWdZSXVMamROVmtUclgwRmhCZ0l2eWIyREhtbTdNNlpRT3loK2t4YURiZG5VPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlIzWmxOVnB2ZFc5VlIwaFNjVmxOUzJ4dldYRlpjRlpGUVdFNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlhoTlJFbDRUV3BGTWxkb1kwNU5ha2w0VFZSRmVFMUVTWGxOYWtVeVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVV2WWs5R05rd3dVMGMxYTJKTlowOHlhVTF4Uld4bllsTkpRalV5VmxKUlVGbGpNRUVLYm5CUU4waDFWSE5wVG1kUlVYaFJhMGhRUmpKd01HUmxNRWs1TW5NMWJXUTFhRVZhUXpCdVl6RnpZbVp3UlZRd1EzRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZDWkZGQkNucHplbGh4VURSaGNFODFWMUp4VDAwNWNISjVPRWRGZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNoWlYwa3pXVzFSTUU5WFRYcGFWMGw1VDBSTk0xbFhSVEZPTWtWM1RtcENhRnBIV1hkTlYxRjNDbGw2VVhoYVZFSm9UMFJrYUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEhVakZxYkdOQlFVRlJSRUZGWTNkU1VVbG9RVXBuWjI4clNGY0tlR3hOTTJZeVUydExZMUIzZVdSbFVVdDJXa2hsVm5aSloyWnFTVEl4U2s5WVVHWm5RV2xDU2pseVdXb3ZVak5VTm1sSVVFcHZkMFpQTkcxUWNHTkdTUW8yVGt4V1JYQnhVVEpQUlZaSlMzaDRPVVJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcENLMUpWU210dVQyOUNTSGQwVG5wbWVGZzBaRWRuQ210NVlXTldOMmxKWkRSeFdrcG1hV3gwYTNSa1lsRTVVVTAxUkVkdWRHSkVPV0Z0WTB4dEwzVlhSVTFEVFVNeFMzaE1TMHR2Ykc5MFpYRXlSWEZxUzNRS01UQnZjbXAyZERoRVZuZDRMMDEyWWxRd0x6UlZRVXd2Y0dwR1psVmFWSE4yUnk4MWRuZFdhMVZLVW1oT1FUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1668132758,
          "logIndex": 6850695,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "1ab7bd49c3eb2837aa57a060adf01d0c41e0a87a",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3441955202",
      "sha": "1ab7bd49c3eb2837aa57a060adf01d0c41e0a87a"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

