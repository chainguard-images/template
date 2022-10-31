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
| `latest` | `sha256:5691f6e32cc724d961c85a305f726cc759262c052e420a5ff6aa991a60eec7dc`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5691f6e32cc724d961c85a305f726cc759262c052e420a5ff6aa991a60eec7dc) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:5691f6e32cc724d961c85a305f726cc759262c052e420a5ff6aa991a60eec7dc"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "8a49eff2e62fac0062bac0a1feb83a418eb13feb",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCICxbd7kadDXN/2+ykWq3VCPwbyOf1ITpvuvMfDXBdg3kAiEA+tfma/TzSZS7jzXLsXrk5lcNLj2Lwq3sm+qTZa2+eSo=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIwN2VmYzMzODY2OTFjMzdkZDQyOWMzMWJmNWY2OTM0Y2JiZTViYTJmMmMyODZjNjk0ZGRjNGFhMTNhNGE2NTYwIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUNoRVFMZ3dyam9nb3ZTbTVVSHY1ZSsySGprbDFWTEFNTk1DUGU2dkY2Nk5RSWhBTWx6SU5CU1RHUlkrN2hLdjllSmlwdFNRaEJUVEpReWR3a0FjdklMZEoyVyIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwaFowRjNTVUpCWjBsVlZXZHFjMUZCY3pWdVRVNHhNMGxLYW5sV05rMDBURXhMU2s1WmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFVFhoTlJFbDZUa1JOTTFkb1kwNU5ha2w0VFVSTmVFMUVTVEJPUkUwelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVU1TkVWb2NHSnZWUzhyVUU5bFJVZG9hVVozZFRoWUsyWlliMDFpWjFKMVVsYzRXWEVLV2pWQ01rWkdObUpZU25OaFlua3dka1JyYzBsVU1IQTVObFJKWlVOR01YQm5NSGgyTUVWR1kzVlJNMnRWUkVWR2EzRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZvYWxsbUNubFRaVE5wZUdObVdIWTFNRzRyY25ab1FWWlhUblE0ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpSWlZGRTFXbGRhYlUxdFZUSk5iVnBvV1hwQmQwNXFTbWxaVjAxM1dWUkdiVnBYU1RSTk1rVXdDazFVYUd4WmFrVjZXbTFXYVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaERkbXRGUkZsQlFVRlJSRUZGWjNkU1owbG9RVTFJTWtjdlRFUUtZWEozUW05d1VIbHFjM0JZWm5GcFJGSllNM2RJT1Vod1RtSjBUSGxyTm1nMFpYVm9RV2xGUVhRdmFsUmFUMVJNWm1oV1pWSm1lVUZFWjB4RWNXcGtMd28zVmxFNVNYZDZRMnRRTUVadVEycHRibmxaZDBObldVbExiMXBKZW1vd1JVRjNUVVJoUVVGM1dsRkplRUZMVDNsWFlreEliMUF5YTFSSGEza3lZWEFyQ2xsc2IwTlFaVEYwY0RVeE5HRmpRM1JOYVROMGQyZEpXQ3RETm5jeE9XRmhkRTlvUkVwSVR5OUpTR2hhWmtGSmQxTnFiQzlSWWxsd2JreE1MMjFQZDI0S1lXeExhRmhJYnpKcFRYUmtPRlphTkhZeWFVYzJOWGhCWTNoblpuRm1hbnBPZHk5aFJsRnpNakJCVkRBd01qUXlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667183700,
          "logIndex": 6194293,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "8a49eff2e62fac0062bac0a1feb83a418eb13feb",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3358142465",
      "sha": "8a49eff2e62fac0062bac0a1feb83a418eb13feb"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

