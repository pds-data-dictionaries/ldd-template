# LDD Source Directory

This directory should contain one IngestLDD for the LDD being built.

**The auto-generation script does not currently support multiple versions of an LDD being maintained.**

## Implement

See the [tutorial on updating and building an IngestLDD](https://pds-data-dictionaries.github.io/support/tutorials.html#ldd-update-and-build-tutorial) and the [LDD Update Process](https://pds-data-dictionaries.github.io/development/ldd-update.html) for more details.

## Contribute

### Propose Updates
See the [LDD Update Process](https://pds-data-dictionaries.github.io/development/ldd-update.html)

### Contribute
Have a bug or feature request? Create one in the [PDS4 Issue Repo](https://github.com/pds-data-dictionaries/PDS4-LDD-Issue-Repo/issues/new/choose).

### Support
See the [PDS Data Dictionaries Support page](https://pds-data-dictionaries.github.io/support/contribute.html) for more Support information.

### Notes
Each build is auto-generated using Github Actions, PDS4 LDDTool, and Validate Tool.

You can manually run [LDDTool](https://nasa-pds.github.io/pds4-information-model/model-lddtool/index.html) on the IngestLDD using the following command:

```
lddtool -lpsnJ MY_IngestLDD.xml
```
