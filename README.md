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
| `latest` | `sha256:08f43d8bedea07745e9889cb0aabcd58717a10ad3baa271059f0df90ba7173da`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:08f43d8bedea07745e9889cb0aabcd58717a10ad3baa271059f0df90ba7173da) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:08f43d8bedea07745e9889cb0aabcd58717a10ad3baa271059f0df90ba7173da"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "f54b4f0d97fd9bd6160c6e737bb452586414680d",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDXjNXc72NWGcZohO1VZ7He4uGh0zDRcpmsxOut3CH4AAIgGKAHT3LmHioQOgRMbjcwrBHK0P9SBgEq2HCt8cUW49A=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2MjUxOTRhZjU2ZmQzMDUzNGU4OWVhNDMxZDExYWFlN2NhNWZiNzNlMDA1MWVlMmY4ZTQ1NGE1YmE4MWMyOTAxIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUR5QUl3V2NzU054UmcvZys0NWJoTWpyRERrUDBIK3lCa2hRZTZRTkw0ak13SWdLZkcwMExNSlp3Zmk4N1VjZTlJZDVPbWtQVkg3RFhkYWdwa01NcGFQZ01vPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlVIUkpXbU56ZVZWaE9WaE9RbVV2TVcxb2RXaFBaSEkzY2xaVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlRSTlJFa3dUbFJCZVZkb1kwNU5ha2w0VFVSRk5FMUVTVEZPVkVGNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZGV0c5WFVVTjBURGQ0V25GalpVOVliMlJ3UjJ4WWFHUkhNR2d4TDFweVIydG5lV1lLTjFaWlVDdFlXRXd4WmxsQ2FGUk1SMEpQY0c5Vk9WQTRaR013VDJOR1JuTkxZVU5HUVZaV2RFWlJNemRyYlZkQ2FFdFBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlU1VGtaWUNsWlRWSEJRTlVwRE1uSkNSVE5OYW5sWlIwTTNXaTg0ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUcxT1ZGSnBUa2RaZDFwRWF6TmFiVkUxV1cxUk1rMVVXWGRaZWxwc1RucE5NMWx0U1RCT1ZFa3hDazlFV1RCTlZGRXlUMFJDYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtY3JhalkzV210QlFVRlJSRUZGV1hkU1FVbG5WM0pyTUd4dlFUTUtSak5SWVRaWVltWkVVbFpsWTJWclJsaFZaMjB2V2s5cE5VWk5Razh5VGpVeFdIZERTVU5LYXl0RGRXUlhOREU1TUhwMU1uUnZiMHh2T1RsUFRESlVkQXBaZFRkS2JXWm9jbmwzTmxKbE1FMWtUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRWRkVjV1pZVnpSSVJscEtkSGhpUlVoQ2JESTNOM1JEQ204d2NsazNTREUxVkRaYVZEWTBibWRzV0UxcFFXeGlMeTh4TTB4emIxRlNhemhTTDNRd1lVaFNlbXREVFVSWU4zTkJhRzE1UTFOM2NWSmFWMlJWYkhjS1RXcDVVSGRyYUd0elduUmlhMWhFWms1WkswVllWbUo2Y0c4d2FtVnRLMWhLTkROclpEbE1kWFl2VUZoblVUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666061121,
          "logIndex": 5321239,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "f54b4f0d97fd9bd6160c6e737bb452586414680d",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3270218899",
      "sha": "f54b4f0d97fd9bd6160c6e737bb452586414680d"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

