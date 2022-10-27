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
| `latest` | `sha256:44c70e876b3ad072a10a9262c2fc2baa1815bb5faca00a8c1d9c70879022f9c4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:44c70e876b3ad072a10a9262c2fc2baa1815bb5faca00a8c1d9c70879022f9c4) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:44c70e876b3ad072a10a9262c2fc2baa1815bb5faca00a8c1d9c70879022f9c4"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "22e1d36655a8e1f81389aab27fca2d337d42da5f",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIGuiXRBxnrCntMySSc6evLZmRUVXsXyXJJWI9h4nPCyTAiAeNE9E8LVux1vlewBdWCQZuVWLc/sHu93i3KR/bKLRAQ==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJkNDc1NGQyZmMyMjdlODVlNTdmMDFhMDk5YTljYTMxNGU4NzcwYWRhODYwZDk0MmQ2ZWE0Y2Q5ZTdkM2Q2ZWI2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQlc0eHRPZjdhbWpHdy9Ic1R6akd4NW01VERxWXorU09PaWZnUEwzaXpyR0FpRUF2eGdwUUpOZkQ2blYzZjlGdFk0OVlsdktyR0dkUXdrNEFKQmRkUlZMZi9NPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwVFowRjNTVUpCWjBsVlZ5dHZlR1o2WVRKMlMxaEJheXR4UldkSU1EZDNhMFJXTDFoUmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1ROTlJFbDVUV3BCTVZkb1kwNU5ha2w0VFVSSk0wMUVTWHBOYWtFeFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVY2Y1RsRGFEQmlXbXBHT1VwRmVEbGFkRFZhTkZsNldFWm5lVEpYYUdST1NtZGtNRXNLY3pSeGVsTkVTRGg2YWxwclFqVm9PV1pGZVROT1IxRnVOREV5Wkd4alZtSktUMDF5Ykd0V1FrUmxaRzQ1WW5KWlEzRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZUWW5WekNsSjZjVUZyZW10MlJsTm5Ramg2YmpabFFtdDNZbTFSZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWjNsTmJWVjRXa1JOTWs1cVZURlpWR2hzVFZkWk5FMVVUVFJQVjBab1dXcEpNMXB0VG1oTmJWRjZDazE2Wkd0T1JFcHJXVlJXYlUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtaENZeTlMU2xGQlFVRlJSRUZGV1hkU1FVbG5ZbWRXVFRSU1RrRUtkakJvV2xOcGJYZFpNekpuVFZkUk1VdDJkakUzSzNoellUaHJjblIyV1U1Sk4zZERTVUYwU2xGeGVYUkVaMWxwUm1wUFUwMTZTV1JRTVZaeVJqTllRUXAxUmtReUwySkRMMlZMZVVWRWRsVnhUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlhMEZOUjFsRFRWRkRjSGhRZGpsTVNEVjFhalJuVHk5M1JYUlpPVU5yQ21KalpteFdMMUFyYTB0VGNHZGhTVlZrWkdNeVZGRnlWemgwU2s1TWNtVndNelYyUm1RelZqWnNZMGxEVFZGRGFYZFVVWHBzVUZvNVNGWTVlSEV5VVVvS01rVmhUMlp3Y25Nd2NHaGtabUZ0U25GeFlqZDBkQ3RMVUZaRFR5OU9lWFpUVjBORE5VTTNOMFZVWVc0cksyTTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666837346,
          "logIndex": 5949325,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "22e1d36655a8e1f81389aab27fca2d337d42da5f",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3334013281",
      "sha": "22e1d36655a8e1f81389aab27fca2d337d42da5f"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

