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
| `latest` | `sha256:f9b7eb715c529a10ca16ec4b2ae6bc256940335173f922fa0d608197adce1b9a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:f9b7eb715c529a10ca16ec4b2ae6bc256940335173f922fa0d608197adce1b9a) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:f9b7eb715c529a10ca16ec4b2ae6bc256940335173f922fa0d608197adce1b9a"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "280e9fc64801ac6b787627c7b78c0426b514c4d8",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIC+A9fOMQhaELZR/MkWNY+KC3ktg2TQIIG60rpEMy1vcAiBPywIKMjaIEGhitIVZzIGV627XuIpXoccZcyqH1Us8gw==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI3M2E2MjhmZGU4MTA2MmQ5NzlmZGU0ZWM2OGYxZGY5ZGExYWIyYTAxMzYxZGMwYThmNTEzNmVkNDQ4YzU4Y2EwIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQnhPOHo5TjZ5dExUcGVFVHc2dHh0MzJ4Nk04YkVGQVBjYklkRUY5MHgzVkFpRUFxd3NkQWlXenJIT3o0VVVNblEvNzB5a3RNb2JhWHdZSU5rMzRGL0pKK0FrPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlRFcHFUVnB2VkcxRGJXWlRVSFprZG5aemVUZzRUM3BxVWxaemQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1RSTlJFbDZUVlJCZWxkb1kwNU5ha2w0VFVSSk5FMUVTVEJOVkVGNlYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZsVWpsQ1pFcEtSa3hzYkdKdVQzbE5SRGxuTXpKMlpEZDNRMGd6TTJWMWRTOTVZbm9LYm5Cd1lrdFliVXRWUjJaNE4zSTVSa2RvVW5ocmJGRk9NVk52VjFsNFFuUlNWbU0yVERSbFVEbGFPWE5VU1Zsd2NYRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZaWWxBNENscDFOamhRZFU1a1N6WTNZbTFMV1VOeWVraDRRelpuZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNsUFJFSnNUMWRhYWs1cVVUUk5SRVpvV1hwYWFVNTZaek5PYWtreldYcGthVTU2YUdwTlJGRjVDazV0U1RGTlZGSnFUa2RSTkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaENlSFIwY21OQlFVRlJSRUZGWTNkU1VVbG5VVU5aTWpKb1RIUUtSMkpWZEVsUlFXbFdWamx2ZGxsTVRURklOWFpsVVhoNlUxWk9lbWRoZFRaT1FrRkRTVkZFY0dGaFRXRlpWRVJwWVVKM2NYbDFVekJ3VUhWTlEwNXFXQXBPUVZWUlRuY3lUeTlDUjBwWldHRmxTM3BCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcENZalZsTnpZd00wOW5kVE5IY0RSeE1YaHBXR2hKQ21KWlowVm5ObFpTYlVwaU5qUkhVak53UlZCdlYxWkpkRlJCUjJndlRXVTBiV1l5YWxaNWNqRTVZMjlEVFVkTmJXZDJkRzF6Wlhrd1JqUjFMeXREWTNvS1JIaDVWWHBOSzFaTWFWVkpWSGRoVlVrMmNtVXlaRzlJVGtoeGVVRkNLMUZFTm1KaWIzazVZbUV5VFRWVGR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666924287,
          "logIndex": 6017647,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "280e9fc64801ac6b787627c7b78c0426b514c4d8",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3342349710",
      "sha": "280e9fc64801ac6b787627c7b78c0426b514c4d8"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

