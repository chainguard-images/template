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
| `latest` | `sha256:04f4fdaa1f1004f290d77a588824ce3ffe4647c7e3377ec1dc2ce5fb62a2cd4f`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:04f4fdaa1f1004f290d77a588824ce3ffe4647c7e3377ec1dc2ce5fb62a2cd4f) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:04f4fdaa1f1004f290d77a588824ce3ffe4647c7e3377ec1dc2ce5fb62a2cd4f"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "bd7efb93a471af34edfe60427e7eb35ade6ca0bd",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQDpspcW27LBFGNYcTGWBiPX+CbyHdpBLKjzu57wdIJEygIgdadrOrcPCAtyJbVk0hyY6zbfVEcfxn39uE02vVZU/vo=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJiNzczYmU2OWRjZGJmNDgzZWZlM2VmODIzNGYxYmMzZjA1YTkzODNiM2Y1MmZjZjQwOGViZjJmMDEwNzIyMzIzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQXc0ZnpyVzk0SFlRY2tUY1BGOUdXR2lzcFJDM2J5T2pPN202azF2R09uSEFpQTZJcjJTazJ2Z09iTkFHMXFTTWpHd1p2M3RiTlFIQytRS2ZQWFVwQkIvN1E9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlRtTkZObkZITUZSMGVuaHZlbUZvTTFwNWRqVnVhRTl5WkdNd2QwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRGTlJFbDNUMVJWTlZkb1kwNU5ha2w0VFZSQk1VMUVTWGhQVkZVMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ3V1VGcmRVSk5jbTFVTlV0YWRHTkViSE4wUmtaa1RqY3lOalJVVkRaeE5FSTBTbEVLWVRkVWFIVkdSV3hhUzJKV1dscFphR0pXY0hsUU9FUldSRTFpVFdGQlJVSldNMHhWSzBFeU9WWXdlVmRIYmxkS1FrdFBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZLUTBoUkNubG1LM1JvZEhWaFFYWnNLMFpyTDB0MmVscEJkRmN3ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdsYVJHUnNXbTFKTlUweVJUQk9la1pvV21wTk1GcFhVbTFhVkZsM1RrUkpNMXBVWkd4WmFrMHhDbGxYVW14T2JVNW9UVWRLYTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEZWMDVVYTJkQlFVRlJSRUZGV1hkU1FVbG5SR0kwVUVGMFkxb0tZazlNZVV0QlpWaDZWblpKY0RGaFZqbDRPREp5VlRodGNUQkhPR2wxZWtnclYwRkRTVWhCVm5WT09Gb3hOMkZMT1hWeVZYTlFaakJvY1RCRVlUQkZaUXB0VTFsSGVYbFNPVkV6TkdoMVNVOTRUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRWRkROVGN6YUM5Q1lVUmxVVGRrVW1VemIxaHFaM05YQ2pVMmNEUkZXa3BCY2xaU2IxUlBkemM0TW5RcmNYSkhOa3RrVUVwYWFqTmpTRTlVYVROV2JVeEZSVmxEVFVZNFIzZHZTMWMwWmxWVk1tWkNZa0ZCU0ZjS1JFZGpjRVZEVW5SUVdYbENaR05OYVRObVdrWnRNbU4zVjAxYUsydG1XbXhqVVdGM1EyUnFRMDV2VWtKVFVUMDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667614226,
          "logIndex": 6532583,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "bd7efb93a471af34edfe60427e7eb35ade6ca0bd",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3398280670",
      "sha": "bd7efb93a471af34edfe60427e7eb35ade6ca0bd"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

