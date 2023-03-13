# seedwing-golang-example

Example Golang project integrating with Seedwing.

This example consists the following:

* A Golang server application.
* A [GitHub Actions Workflow](.github/workflows/ci.yaml) that creates builds and creates in-toto attestations for the artifact.
* A [set of policies](policies/) that are applied to verify the attestations.
