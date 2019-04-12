FsLexYacc
=======================

FsLex and FsYacc tools, originally part of the "F# PowerPack"

See https://fsprojects.github.io/FsLexYacc.

Build the project
-----------------

* Mono: Run *build.sh*  [![Travis build status](https://travis-ci.org/fsprojects/FsLexYacc.svg)](https://travis-ci.org/fsprojects/FsLexYacc)
* Windows: Run *build.cmd* [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/061nqkynrysnyiv7)](https://ci.appveyor.com/project/fsgit/fslexyacc)

* [![NuGet Badge](https://buildstats.info/nuget/FsLexYacc.Runtime)](https://www.nuget.org/packages/FsLexYacc.Runtime) - `FsLexYacc.Runtime`
* [![NuGet Badge](https://buildstats.info/nuget/FsLexYacc)](https://www.nuget.org/packages/FsLexYacc) - `FsLexYacc`

### Releasing

    set APIKEY=...
    ..\FSharp.TypeProviders.SDK\.nuget\nuget.exe push bin\FsLexYacc.Runtime.8.0.1.nupkg %APIKEY% -Source https://nuget.org
    ..\FSharp.TypeProviders.SDK\.nuget\nuget.exe push bin\FsLexYacc.8.0.1.nupkg %APIKEY% -Source https://nuget.org

### Maintainer(s)

- [@kkm000](https://github.com/kkm000)
- [@dsyme](https://github.com/dsyme)

The default maintainer account for projects under "fsprojects" is [@fsprojectsgit](https://github.com/fsprojectsgit) - F# Community Project Incubation Space (repo management)

