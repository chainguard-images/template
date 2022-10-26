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
| `latest` | `sha256:2667d18df736413bdafe971a4b54371b0b9ed6a897be59521be895c1d3fe3829`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:2667d18df736413bdafe971a4b54371b0b9ed6a897be59521be895c1d3fe3829) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:2667d18df736413bdafe971a4b54371b0b9ed6a897be59521be895c1d3fe3829"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "5fa0e81bdcbfd0f650cd60a5a44439b8b5866760",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDwQv3vW1t19xUWKjuuzV8802sPu1iJLAZijrPX87kyPwIgXZZE8A0xEjiX9O1ZViUD9rtihv4ym404jcpml26duAY=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI3MjE3OWI5YTlhMjM3YTQzOTBlOTk0MGE1MGYzZDhlZTEyZGJmMTc1NmUwNWFiNzMxNjU2NTRjNTJlMjRkNTRlIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRkFsY3BKTXlSU1AwbTRuQk5Xc0JmYVlvUHhsVjVMKzQyTEZ2Mk9SeXhMZkFpRUFxaGhqbnZPV1pGcHM5R1FKeEJyR1RRNkw4TGVyNUxBellKNUxob2srd3BVPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwWFowRjNTVUpCWjBsVldGZ3dMMXBTUVdwVlUyZFRTME5UT0cxMFkwNWhNMmhpYUM5SmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1RKTlJFbDVUbFJOZVZkb1kwNU5ha2w0VFVSSk1rMUVTWHBPVkUxNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUwVm5kR09FZ3hWSEZOVkV4VmRESlhTV0V5V1RORldrczJVMEZCVFRocGJWcE1iRXNLTjJsUGFFZ3ZNMmxPTVM5TFNVdHVNM2hZU0RCQlIxTjFiRVl6VkcxdGRTdEpkbEI1YUdaa2J5dHBLME5KUVZOTE4zRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlV2WjJKVUNqTmhMMDkxVmxsMmJIa3hhU3RITDJkNGNVTnBTM0EwZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpGYWJVVjNXbFJuZUZsdFVtcFpiVnByVFVkWk1rNVVRbXBhUkZsM1dWUldhRTVFVVRCTmVteHBDazlIU1RGUFJGa3lUbnBaZDAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaENTV0k0TUVsQlFVRlJSRUZGWTNkU1VVbG9RVXBEYWxwVmRVZ0tRMlZzVkVGNlJXRjFRMVZzWWtSa1drdDFlR1pVTldjeWFqTjNVVzA0WVZsaWFEWlNRV2xDWm1SNFUzQlFVbTlZVm5OWFVWUkRhbTQwTkdkVWVrbFdPQXBvTlhsNlNXSk5aQ3NyV2t4SU1FeGpOa1JCUzBKblozRm9hMnBQVUZGUlJFRjNUbkJCUkVKdFFXcEZRVFpGYW1KWlNtVlZkV1J5UW05R1ptbEZkak5ZQ25scGJuSnRVa1pGZW1aUVRHaG5lWE51UkRsUlFXNXRRa1IyWldSWFNsQldjR1YyZEZWdlUxaFZRbkpaUVdwRlFUZE1hV2R1ZDFrcmExY3ZXRXR4YldJS2VFbG1WekJUYTBOQllXeENjRlpTTUV0RmRHNXlVM0ZyUVVNeWJWRlZiUzlGUm0weGFGazBjblUwVGtWWFdIUkNDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666751166,
          "logIndex": 5875217,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "5fa0e81bdcbfd0f650cd60a5a44439b8b5866760",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3325723364",
      "sha": "5fa0e81bdcbfd0f650cd60a5a44439b8b5866760"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

