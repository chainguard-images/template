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
| `latest` | `sha256:adef8a6818dea77564652a8a5e272123a43d22508c771873d73886f6756c20b3`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:adef8a6818dea77564652a8a5e272123a43d22508c771873d73886f6756c20b3) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:adef8a6818dea77564652a8a5e272123a43d22508c771873d73886f6756c20b3"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "a7c60e40534a28d85133d2438d890603919c8a05",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCID8vBvzJlu/CNyoe8vvcozqHAz72pg4VMG7+RYNtS9ZjAiEA43FUsO5UxsoRo6MFwyokVcyFboXjIill+odEOcBrdbs=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI4OWMzMjBjN2NhNGYwODQwNThjNjBmOWNiMGFmZmNjN2RhNjBjMGRhNDg0ODdjNGIxMzIwNzEwYmExNjU0Y2Q3In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUQ5ZEdRTG9rUG1VL1hXbW82SnRqdytCSWVXWFhQVFpDSW9qSS94SForbENBSWdiUEFOazR5cnc1QkpkbFpFeHBNNDhUMDdHSVlDS1NPSFR0ZVBqdGdkQWhVPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnpSRU5EUVhwaFowRjNTVUpCWjBsVlNETlJiR05vU0U1bFZVeFVlVTl3VURSRGFYZDNTSEpyVjBwamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1RKTlJFRjVUV3BCTTFkb1kwNU5ha2w0VFZSSk1rMUVRWHBOYWtFelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZRVEVoWVEwMUxNbTlUT1hKWUswbEZielo0YlVkdU1tZEpOVzVyWm1JNUszSjFTbGtLT0dkTGFXbzNSVUpQYzBod2JuaEpaR3A1ZW1aRllXRkJkWFptTUV0NE4yNXlURUkyZUVkR1ZscFNPR1ZaZDBORlJIRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlUzTjFwM0NuSnBhU3R3YlhaM2NYbExMeXN3YTFKUVkzWkNhMEpOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdoT01rMHlUVWRWTUUxRVZYcE9SMFY1VDBkUk5FNVVSWHBOTWxGNVRrUk5ORnBFWnpWTlJGbDNDazE2YTNoUFYwMDBXVlJCTVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE1SbEZITWxsQlFVRlJSRUZGWjNkU1owbG9RVXhKUW14dlZWb0tlVmMwTTNwWmVtMVViRVZqVFZwc1lqVk5ieTlFYlZwSUx6Z3JhRk5YV0hSalIxTlRRV2xGUVRWdVNWQlhUREZMUkdkT1JEWTRRMngyUlU1WlIydEdTd3BqVmtaaFZEVkJhbkZETTBKUmMweEtTalJ2ZDBObldVbExiMXBKZW1vd1JVRjNUVVJoUVVGM1dsRkpkMDlsTmtkTGJXZElXVTVXZUU5clltdzVjMEk0Q2xRclltTlBUWEU0Y1VoMmNrSjBNbGN4VVhSblNVcFNVVGg2V2tobVYwaDFaVWx2U1dZd1dscHFXVVZLUVdwRlFYUnZhMFZJVUZCMVV5dHZVamRMYzNvS2IwUnhWVFE1VUVsV2QxaG5Nemc0TWxKamRUSlJjeTlWUzNnclZteHZhbUZuVTBkNlowMURSREJQSzBRd09URlRDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669422148,
          "logIndex": 7857426,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "a7c60e40534a28d85133d2438d890603919c8a05",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3551424759",
      "sha": "a7c60e40534a28d85133d2438d890603919c8a05"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

