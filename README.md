Compile Instructions

We are not planning on releasing binaries for Rubeus, so you will have to compile yourself :)

Rubeus has been built against .NET 3.5 and is compatible with Visual Studio 2019 Community Edition. Simply open up the project .sln, choose "Release", and build.
Targeting other .NET versions

Rubeus' default build configuration is for .NET 3.5, which will fail on systems without that version installed. To target Rubeus for .NET 4 or 4.5, open the .sln solution, go to Project -> Rubeus Properties and change the "Target framework" to another version.
