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
| `latest` | `sha256:1a41724a99e92b0603266749746554c23ef3feba7f47c4c58e239740e1a9a7f4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:1a41724a99e92b0603266749746554c23ef3feba7f47c4c58e239740e1a9a7f4) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:1a41724a99e92b0603266749746554c23ef3feba7f47c4c58e239740e1a9a7f4"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "b4d8dac88ed728a565971c4cff7a3e50cec61355",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIEWB0G4Xi9Jykt+++bBYWKsc/TwJK/+qYVQtotmyat8SAiA8+2LRTXkU9cE3dC7h1na4654DcxrK9guSwZ4omJ1tTQ==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiMWQ3MTk5YWEyZGZjZTA0Yjk2ODlmYWY2NTkwMDA3Y2QwODBhYTcwN2FkNmQ0ZmJiMGZjYjYxZWZhY2ZiOWUzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUNoWCsvbDRBOXBOVlRCSkdzTnBwZ3lLRFFFbUpCVmFnMmJ5VWsvWkR6ZUdBSWdSWFhlaldwSk1iZ0xoN2RxN2FXV29jNmtUZDRBajFZaDYzYnZQdTRvdFMwPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwWFowRjNTVUpCWjBsVlRFRmxLMEl3VjNsd1psTmhWSEpyZFVoNFVYWlJZbGRGYkUxdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlhoTlJFbDZUbFJCTkZkb1kwNU5ha2w0VFVSRmVFMUVTVEJPVkVFMFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVUxYkhWaU5GVnhPVzlaYm1wbU5GZEdjR3BrZERSM1NsbDRWMUZGTDNkWFJFZ3lUV2tLTUdWbU4ydG9hRkJ4WTI5bllYWnlSblV6U25JelIzRmpTeXMwYTBjeUsxZEZNSGQ2WjFaRFprWlRSMVZDWlU4emIyRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYxU2xaNUNtTkJaR05sVFRGMWJEUmphRFZoYm5sMVRFNDFRakJOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdsT1IxRTBXa2RHYWs5RWFHeGFSR041VDBkRk1VNXFWVFZPZWtacVRrZE9iVnBxWkdoTk1sVXhDazFIVG14WmVsbDRUWHBWTVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzRWR3hXTmsxQlFVRlJSRUZGWTNkU1VVbG5WVEF6WlVWQllrMEtlVVZyUWtKWFNVdEVlRFE0V2pSTVFuYzNUamQ0YVV3MVMyeDVOSFZSVjJSaGJuTkRTVkZFYms1WU9EZzVVVEpTVlZSSmJsTkZWR1pYVkVkTE1qWlFTQXBCYzBWRmFHRm1SV05KTkN0RFZGQndaM3BCUzBKblozRm9hMnBQVUZGUlJFRjNUbTVCUkVKclFXcEJUeXRhTWxneVExUnZjMlU0T0habFNFbExSV2w0Q200M2RWSjZWMkkzVURoblVXeE1NRkV4Y1doQlJtNUlUR3BhY1dKaU9EZExhV2N4VURCMlNrRlhPVEJEVFVGdVJFdE1iMEp4YlhGM1FXZERhVEF6UkV3S2JUVnBUVVZhVUN0RlYwVkJSM2xVZEVVNGNEWTJjbmRRVGpJelFsQTRNa2RYWm1wTlNWcEpOWFpCVmpoTFVUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665455726,
          "logIndex": 4862192,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "b4d8dac88ed728a565971c4cff7a3e50cec61355",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3223724423",
      "sha": "b4d8dac88ed728a565971c4cff7a3e50cec61355"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

