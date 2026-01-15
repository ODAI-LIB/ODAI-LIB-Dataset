# ODAI-LIB-Dataset
Dataset repository for the ODAI-LIB challenge at FSE/AIWare 2026

This repository contains the entire package lists from the Crates, Maven, PyPI, PHP, Go, NPM, and Ruby ecosystems.

# How to Use

Since the package list files are very large, we stored them using `git lfs`. Before you clone the repository, make sure `git lfs` has been installed on your machine. See [git lfs](https://git-lfs.com/) for more information.

After cloning, you will need to set up `git lfs` to view all the files properly. Run the following code commands in the cloned directory:

```bash
> git lfs install
> git lfs pull
```

## Package List

Contains the lists of packages for each ecosystem.

- **File Type:** `.csv`
- **Columns:** ID, Platform, Name, Homepage URL, Repository URL

| Ecosystem | Mining Date | Number of Packages |
|----------:|------------:|-------------------:|
| Crates    | 2025-12-01  | 207,981            |
| Go       | 2025-12-15  | 2,164,784          |
| Maven    | 2025-12-14  | 751,350            |
| NPM      | 2026-01-09  | 3,750,520          |
| PHP      | 2025-12-01  | 431,456            |
| PyPI     | 2025-11-30  | 705,908            |
