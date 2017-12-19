# devtest-jar-builder
Creates a single, master JAR file for compiling DevTest custom extensions

**Author:** Mike Gavaghan - **Email:** mike@gavaghan.org

## Description ##
One of the challenges building a custom extension using the DevTest SDK is determining all of the appropriate dependencies to including in your build path.  Not only must you include the DevTest-specific jars, you must also reference the proper version of various open source libraries that DevTest relies upon.

The [devtest-maven-plugin](https://github.com/mgavaghan/devtest-maven-plugin "Devtest Maven Plugin") project simplifies your Maven dependencies on DevTest by converting all of the installed DevTest libraries into a single jar.

This project is simply an example `pom.xml` you can use to install the master DevTest artifact into your local repository.  It can be expanded to deploy to a remote repository.

Note that you'll need to explicitly set the DevTest version information to your version of DevTest.
