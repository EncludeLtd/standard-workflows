# Cumulus Suite GitHub Actions
This repository is a clone of [Cumulus Suite GitHub Actions](https://github.com/cumulus-actions/standard-workflows)

## Running Standard Workflows in a Project
- Follow the Steps outlined in the ["Run CumulusCI from GitHub Actions" Documentation](https://cumulusci.readthedocs.io/en/latest/github-actions.html), skipping the step to clone their standard repository (This has already been done, you're looking at the repo.)
- Create the example workflows as outlined in the documentation, replacing any references to the Cumulus Suite's repos with Enclude's:
  > ~~uses: cumulus-actions/standard-workflows/.github/workflows/{workflow-name}.yml@main~~

  > uses: **EncludeLtd**/standard-workflows/.github/workflows/{workflow-name}.yml@main
