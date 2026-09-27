# OU-MVLP

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FOU--MVLP-181717?logo=github)](https://github.com/biometric-community/OU-MVLP)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.am.sanken.osaka-u.ac.jp/BiometricDB/GaitMVLP.html)

**OU-MVLP** — tbiom catalog packaging for `ou-mvlp` (gait; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/OU-MVLP
- **Upstream source**: http://www.am.sanken.osaka-u.ac.jp/BiometricDB/GaitMVLP.html
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `ou-mvlp` |
| Category | `gait` |
| Access | `register` |
| Upstream homepage | http://www.am.sanken.osaka-u.ac.jp/BiometricDB/GaitMVLP.html |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Osaka University Multi-View Large Population Dataset.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/OU-MVLP.git
cd OU-MVLP
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_ou_mvlp.sh
```

Place licensed archives under `projects/datasets/ou-mvlp/` (gitignored).

## Dataset structure

```text
OU-MVLP/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.am.sanken.osaka-u.ac.jp/BiometricDB/GaitMVLP.html
- Packaging: https://github.com/biometric-community/OU-MVLP/issues
