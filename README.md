# Jfrog Downloader

## Overview

Jfrog Downloader is a Python library for interacting with Jfrog to downloading Artifacts. This library provides keywords for set user, download file and download folder.

## Installation

```bash
pip install jfrog-downloader
```

## Documentation

For detailed documentation of each keyword and usage examples, refer to the documentation in the below link,

https://github.com/abi-sheak/Jfrog_Downloader

## Usage

```python

from JFROGDownloader import JFROGDownloader

# Object Creation with Base URL and Repo name.
jfrog_obj = JFROGDownloader(<Base-URL>, <Repo>)

# Signing with User ID and API key
jfrog_obj.set_user(<User-ID>, <API-Key>)

# For download file from JFROG. Need to pass with file path and Output local path.
jfrog_obj.download_file(<File-Path>, <Output-Path>) 

# For download folder from JFROG. Need to pass with folder path and Output local path.
# Optional arguments for Neglat file  or with patterns in list format.
jfrog_obj.download_folder(<Folder-Path>, <Output-Path>, <Neglate_Files>, <Neglate_Patterns>) 

```

## Contributors

- Abisheak Kumarasamy ([@abi-sheak](https://github.com/abi-sheak))

## License

- See the `LICENSE` file for details.
