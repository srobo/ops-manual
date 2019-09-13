# Miscellaneous

## Licensing

This work \(the operations manual\) is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). The authors of this work are: Rich Barlow, Diane Dowling. 

## Making Changes to this Document

The source of this document can be found here: [https://github.com/srobo/ops-manual](https://github.com/srobo/ops-manual). It is maintained by the Trustees of the charity. It is important to note that the information contained within the 'master' branch of the repository has not been released and therefore is not authoritative. New releases of the operations manual must be approved by the Trustees via one of the decision making procedures defined in clause 17 of the [constitution](https://github.com/srobo/ops-manual/tree/d76377192d4c94c4bd4298f0f3954f5d342af24b/resources/constitution.pdf).

Releases of the operations manual are denoted with both a tag and branch of the form 'v\#', where \# is a number. The latest release is the one with the largest number and will be set as the GitBook 'primary' version. The requirement for a branch as well as a tag with the same name is an unfortunate requirement of how the GitBook platform operates; if a tag and branch of the same name ever differ in terms of the commit that they refer to, the tag takes precedence \(if you happen to notice an anomaly of this form, please inform the [trustees](mailto:trustees@studentrobotics.org)\).

To make a release of this document the following steps must be taken:

1. Ensure that the [Change Log](change-log.md) is up to date with all modifications made since the previous release.
2. Ensure that the Trustees have approved the release of the new version and it has been recorded in the Trustees' decisions.
3. Set the version number and date for the new version in the Change Log.
4. Create a new version via the GitBook editing interface. This version must have a human-readable name of the form 'Version \#' and a 'path' of 'v\#' \(the 'path' setting in the GitBook interface is what becomes the branch name in the git repository\).
5. Set the newly created version as the primary version, such that it is the version presented to a reader when visiting [https://srobo.gitbook.io/ops-manual/](https://srobo.gitbook.io/ops-manual/).
6. Create a tag with the same name as the branch just created. This tag must point to the same commit as the current head of the branch. The tag can be created either using the normal git CLI tools or the GitHub web interface.

