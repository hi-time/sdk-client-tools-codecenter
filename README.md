# Black Duck Software CodeCenter SDK Libraries

The Black Duck Software CodeCenter SDK Libraries provide access to the SDK end-points available on Black Duck's CodeCenter product

## Building
The SDK libraries use [Gradle](https://gradle.org/) for build operations (specifically, the Gradle wrapper, invoked via `gradlew`). The main build target of the SDK libraries is `jar` - this will generate clients and perform compilation steps

### Importing into an IDE
Instead of using Gradle's plug-ins to generate IDE-specific files, it is assumed that the IDE's Gradle plug-in will be used.

For example, [Eclipse's Gradle Plug-in](https://marketplace.eclipse.org/content/gradle-ide-pack) can be used to import the projects into an Eclipse environment

## Contributions
Contributions are pull request based. Contributors should fork the repository and create pull requests based on the `master` branch

* These libraries are based on Java 7 - all changes should be compatible with this language version
* Changes to APIs must be backwards compatible
* Changes in pull requests should be documented
* If any significant features are added, add tests where possible

## Branches
The repository contains a `master` branch which contains tags for each release and any changes contributed. Releases will be based on what has been merged into the `master` branch 

## Release Pattern
This project does **not** follow semantic versioning - version numbers are kept matching to the minimum compatible product version

New releases of the SDK libraries are created when a version of CodeCenter is released. The version number of the client/utility libraries is generally the minimum version of the associated product that release supports.