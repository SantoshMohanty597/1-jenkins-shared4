This is file is for understanding the using the shared libraries in a project.

@Library('my-shared-lib') _

This name setup is important as it should be same as the name of the shared library in Jenkins configuration.
.
go to manage-jenkins -> configure system -> scroll down to Global Pipeline Libraries 
-> add a library with name "my-shared-lib" and set the source code management to git and 
    provide the repository URL where the shared library is located.