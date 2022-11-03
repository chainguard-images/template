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
| `latest` | `sha256:61bf14622f4d6f3acb808f770d0cf367be55a4d22d45f43108a2ed5aa9c33dbd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:61bf14622f4d6f3acb808f770d0cf367be55a4d22d45f43108a2ed5aa9c33dbd) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:61bf14622f4d6f3acb808f770d0cf367be55a4d22d45f43108a2ed5aa9c33dbd"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "d5fe5115b463bc79e4703d0c8b61d1dd74194a02",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQD5CLGMfRr2CboAi2JLx8xmmWynVLeaCyruJIG4Vrou/QIhAOjWQhXidPBISCMwQw3ZsSkVsJMeHgl1R/W3wo3MK6IP",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJkMjQzNjgzN2M1NGJiNWI1ZGI0MDYxZTQzZDEyYmI2NTU5ZjQyMWI0YmRiNDYzZDc0MWExZWRhZmRlZmFjNzQ3In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FUUNJQmNjTTBLYXhrRVFMQWdnUHZTcEFuZnJ3YjhPMkJLQlpMN1FOajkxWnY3aUFpQjhma0N6bmtlYzg1bzZPM1VNNEdhK29Kekdya1lLSWQ2MXJnOE1laXJUQ1E9PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlVXaG9WR1ZIYlhJdlN6bEJOV3AyWlcxeVNsaDBjRTlQUTFsQmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVhwTlJFbDRUVlJOTTFkb1kwNU5ha2w0VFZSQmVrMUVTWGxOVkUwelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVV4U3pKaWVqVXlOaXR5Y0VWalVtOVdkbkZFT0c4MlkwOHlaekpxWmxkM2VXNDFWSG9LVlRsS1NVUk5Zbk5DUVdOSlJXTmlRU3RMYWpObFZtbGxPRkFyUmxjd1dtWTBNWGQwVVZCMVZWVmFabU40VTNObk5tRlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZ1Um0wckNtd3lMelZhZEZaMFJuaFlOWGxaVEdaSlUwSmtjM0paZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd0T1YxcHNUbFJGZUU1WFNUQk9hazVwV1hwak5WcFVVVE5OUkU1clRVZE5ORmxxV1hoYVJFWnJDbHBFWXpCTlZHc3dXVlJCZVUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaEVkRU5HTTAxQlFVRlJSRUZGV1hkU1FVbG5VbFozT1cxRk5XRUtUVkZVUTB0RFNHMDBVbWRxZVRVeVpFSXdhVFJsWmpRMVdFbDBOU3RuSzFGRlRITkRTVWhtY0VKeVFURm5NVTlZUVhkd1JHTnFVWFUzTUhCQlZWWjZPUXBKWVhkUVQwUlBRa3QwVDFaNWIwbHVUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRWRkVZV2g1VFhaa1ptVldORUUyVjJSclIwSlVjbVJaQ2t4WFVWb3haRUpUVURCdmNUQjJRbWQzV0V4UWRqRjZaalpJVEN0elQzZEZVMFk1WkZGM09YWklRVGhEVFVZd1J5dFJNWEpGVGxSck1sRjRibUpVVkZBS1ltOTVjMlZQZFRoWWVHUnNRM1ExTm1wdFYzRlFMMHdyUzFSbWNVeHhiVFpOWW1oT04zb3llakp0YVhSblp6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1667441518,
          "logIndex": 6395891,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "d5fe5115b463bc79e4703d0c8b61d1dd74194a02",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3382519291",
      "sha": "d5fe5115b463bc79e4703d0c8b61d1dd74194a02"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

