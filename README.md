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
| `latest` | `sha256:c8181850f13961419a3ea5f7b173653588e3ebe30b71a683bcfe358849e0a8fb`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:c8181850f13961419a3ea5f7b173653588e3ebe30b71a683bcfe358849e0a8fb) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:c8181850f13961419a3ea5f7b173653588e3ebe30b71a683bcfe358849e0a8fb"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "afe75c9369e3c524f7645739c2f2835894ba58ff",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIAV8TcW6SjzV/yQ8L0XrIctJYW/lPNseY/DFj/puEyfqAiBmRFdZerSGwFI5SGbjpIB/CucvJuAMB4BtiMKsa0HvtA==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJmZThkYzQ1YjQ5MTM2OGRmOTUzZDk5ZmViYTZlMmE2MTExMjMzZmM0MjEwYTM3NzViY2ExYTdkNTU3Nzk2NGFjIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURyRXVaVU03M2JlbU84RTR3bnFKbXNRblZNM25jWWk4TWFEaHA1WWF0cFBnSWdac3FRNmhNTUxCeWlkZGRPbUJwNnJFZ0kwNTIzUWJDK0w4dlN4L0I2NGpjPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlVVbDBRM2hUVG1acVVGaFNOazVOUVdob01EaHdSV3hhWVhOcmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlhwTlJFa3dUVVJGZVZkb1kwNU5ha2w0VFVSRmVrMUVTVEZOUkVWNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYyVDJsdE5IQlFjamRXV0RSNVEwVXlRWEpUWmtGdGRHd3hNbVpYTTFoTFZGaHZVMWtLYWt4cGRYSlBORXRIZVdOSGNuZDBTRkp1WlZGS1VYWTVZbWRyZURaM09HNXZja2hDTVU1M01IbFBUVmM1YlVaVlRYRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlUwZURGRENuaHZSbEo2VDB0Qk0yOWxaSFF2VTFkaFZuRkdZMjVCZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdoYWJWVXpUbGROTlUxNldUVmFWRTVxVGxSSk1GcHFZekpPUkZVelRYcHNhazF0V1hsUFJFMHhDazlFYXpCWmJVVXhUMGRhYlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzRPREowUTFGQlFVRlJSRUZGV1hkU1FVbG5XVkpUZUZkaGVtb0tkVlpaYTJsMmRqaERjR2RhWnpNd1MwOU5lVzAwU2pGV1NVNTJSbFJzUzJoRFEyZERTVWRRVVRSRGMyOVVRekZpTmpSTWRYaEJOVVkxV21kcFRIRm9hUXAzWjIxaFdGRjFOSEJxZVU0MFFtbzFUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRWRkVRalYzZG1wcVJtY3ZXVlJNU2pCcFlWQnlZalZzQ2pkSlpTOUlRbUl3T1dGSWVIVnJLMHAzVWtWd1RXdHRjRzFJVEdsRlpHcEROM1pFVFdoRVdUSnRibU5EVFVkNVRUWkpPVWRaZG1oeWRWZ3ZSMFpIWm1rS1JVaEtVbWhYVTFaM1JYRlFaR2xIV0dNNWJGRjJTREFyWVVoMlVsZFFjalJKVnpOeVZIZFVVa2R4WmtaMVFUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665628831,
          "logIndex": 5000233,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "afe75c9369e3c524f7645739c2f2835894ba58ff",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3239297277",
      "sha": "afe75c9369e3c524f7645739c2f2835894ba58ff"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

