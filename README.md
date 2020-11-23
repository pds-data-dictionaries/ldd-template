# {LDD Name} Local Data Dictionary (LDD)

The {LDD Name} dictionary [enter description here]

LDD Steward: [enter steward node here]

## Releases

![LDD Automation with PDSEN CI Bot](https://github.com/pds-data-dictionaries/ldd-template/workflows/LDD%20Automation%20with%20PDSEN%20CI%20Bot/badge.svg) [TODO - replace with this repo badge]

* **Stable Release** (the latest released LDDs) - https://pds.nasa.gov/datastandards/dictionaries/
* **Unstable Release** (the latest working, unstable build) - See the `build/development` 

# Documentation

* **User Guide:** TBD
* **Other PDS Data Dictionaries Documentation:** https://pds-data-dictionaries.github.io/

## Propose Updates

See the [LDD Update Process](https://pds-data-dictionaries.github.io/development/ldd-update.html)

## Implement

To implement changes the LDD, simply update the IngestLDD under the `src/` directory, commit to a branch, push the branch to Github, and create a Pull Request. The [Github Action CI/CD](https://pds-data-dictionaries.github.io/development/ldd-build.html) will take care of the auto-generation of the schemas and schematrons.

For more information see the [LDD Build Process](https://pds-data-dictionaries.github.io/development/ldd-build.html)

## Notes

Each build is auto-generated using Github Actions, PDS4 LDDTool, and Validate Tool.


You can manually run [LDDTool](https://nasa-pds.github.io/pds4-information-model/model-lddtool/index.html) on the IngestLDD using the following command:
```
lddtool -lpsnJ src/MY_IngestLDD.xml
```

# Contribute

* Have a bug or feature request? Create one in the [PDS4 Issue Repo](https://github.com/pds-data-dictionaries/PDS4-LDD-Issue-Repo/issues/new/choose).


# Support

See the [PDS Data Dictionaries Support page](https://pds-data-dictionaries.github.io/support/) for more Support information.



# Contribute

Have a bug or feature request? Create one in the [PDS4 Issue Repo](https://github.com/pds-data-dictionaries/PDS4-LDD-Issue-Repo/issues/new/choose).


# Support

See the [PDS Data Dictionaries Support page](https://pds-data-dictionaries.github.io/support/contribute.html) for more Support information.
