


dotnet --help
.NET SDK (6.0.202)
Usage: dotnet [runtime-options] [path-to-application] [arguments]

Execute a .NET application.

runtime-options:
  --additionalprobingpath <path>   Path containing probing policy and assemblies to probe for.
  --additional-deps <path>         Path to additional deps.json file.
  --depsfile                       Path to <application>.deps.json file.
  --fx-version <version>           Version of the installed Shared Framework to use to run the application.
  --roll-forward <setting>         Roll forward to framework version  (LatestPatch, Minor, LatestMinor, Major, LatestMajor, Disable).
  --runtimeconfig                  Path to <application>.runtimeconfig.json file.

path-to-application:
  The path to an application .dll file to execute.

Usage: dotnet [sdk-options] [command] [command-options] [arguments]

Execute a .NET SDK command.

sdk-options:
  -d|--diagnostics  Enable diagnostic output.
  -h|--help         Show command line help.
  --info            Display .NET information.
  --list-runtimes   Display the installed runtimes.
  --list-sdks       Display the installed SDKs.
  --version         Display .NET SDK version in use.

SDK commands:
  add               Add a package or reference to a .NET project.
  build             Build a .NET project.
  build-server      Interact with servers started by a build.
  clean             Clean build outputs of a .NET project.
  format            Apply style preferences to a project or solution.
  help              Show command line help.
  list              List project references of a .NET project.
  msbuild           Run Microsoft Build Engine (MSBuild) commands.
  new               Create a new .NET project or file.
  nuget             Provides additional NuGet commands.
  pack              Create a NuGet package.
  publish           Publish a .NET project for deployment.
  remove            Remove a package or reference from a .NET project.
  restore           Restore dependencies specified in a .NET project.
  run               Build and run a .NET project output.
  sdk               Manage .NET SDK installation.
  store             Store the specified assemblies in the runtime package store.
  test              Run unit tests using the test runner specified in a .NET project.
  tool              Install or manage tools that extend the .NET experience.
  vstest            Run Microsoft Test Engine (VSTest) commands.
  workload          Manage optional workloads.

Additional commands from bundled tools:
  fsi               Start F# Interactive / execute F# scripts.
  sql-cache         SQL Server cache command-line tools.
  user-secrets      Manage development user secrets.
  watch             Start a file watcher that runs a command when files change.

Run 'dotnet [command] --help' for more information on a command.
PS F:\Practice\DotNetCore> dotnet new dotnetcorewithDS
No templates found matching: 'dotnetcorewithDS'.

To list installed templates, run:
   dotnet new --list
To search for the templates on NuGet.org, run:
   dotnet new dotnetcorewithDS --search

PS F:\Practice\DotNetCore> dotnet new --list
These templates matched your input: 

Template Name                                 Short Name           Language    Tags
--------------------------------------------  -------------------  ----------  -------------------------------------
ASP.NET Core Empty                            web                  [C#],F#     Web/Empty
ASP.NET Core gRPC Service                     grpc                 [C#]        Web/gRPC
ASP.NET Core Web API                          webapi               [C#],F#     Web/WebAPI
ASP.NET Core Web App                          razor,webapp         [C#]        Web/MVC/Razor Pages
ASP.NET Core Web App (Model-View-Controller)  mvc                  [C#],F#     Web/MVC
ASP.NET Core with Angular                     angular              [C#]        Web/MVC/SPA
ASP.NET Core with React.js                    react                [C#]        Web/MVC/SPA
ASP.NET Core with React.js and Redux          reactredux           [C#]        Web/MVC/SPA
Blazor Server App                             blazorserver         [C#]        Web/Blazor
Blazor WebAssembly App                        blazorwasm           [C#]        Web/Blazor/WebAssembly/PWA
Class Library                                 classlib             [C#],F#,VB  Common/Library
Console App                                   console              [C#],F#,VB  Common/Console
dotnet gitignore file                         gitignore                        Config
Dotnet local tool manifest file               tool-manifest                    Config
EditorConfig file                             editorconfig                     Config
global.json file                              globaljson                       Config
MSTest Test Project                           mstest               [C#],F#,VB  Test/MSTest
MVC ViewImports                               viewimports          [C#]        Web/ASP.NET
MVC ViewStart                                 viewstart            [C#]        Web/ASP.NET
NuGet Config                                  nugetconfig                      Config
NUnit 3 Test Item                             nunit-test           [C#],F#,VB  Test/NUnit
NUnit 3 Test Project                          nunit                [C#],F#,VB  Test/NUnit
Protocol Buffer File                          proto                            Web/gRPC
Razor Component                               razorcomponent       [C#]        Web/ASP.NET
Razor Page                                    page                 [C#]        Web/ASP.NET
Solution File                                 sln                              Solution
Web Config                                    webconfig                        Config
Windows Forms App                             winforms             [C#],VB     Common/WinForms
Windows Forms Class Library                   winformslib          [C#],VB     Common/WinForms
Windows Forms Control Library                 winformscontrollib   [C#],VB     Common/WinForms
Worker Service                                worker               [C#],F#     Common/Worker/Web
WPF Application                               wpf                  [C#],VB     Common/WPF
WPF Class library                             wpflib               [C#],VB     Common/WPF
WPF Custom Control Library                    wpfcustomcontrollib  [C#],VB     Common/WPF
WPF User Control Library                      wpfusercontrollib    [C#],VB     Common/WPF
xUnit Test Project                            xunit                [C#],F#,VB  Test/xUnit

Matches from template source: NuGet.org

PS F:\Practice\DotNetCore> dotnet new dotnetcorewithDS webapi
Error: Invalid option(s):
  webapi
For usage information, run:
   dotnet new -h
PS F:\Practice\DotNetCore> mkdir dotnetcorewithDS


    Directory: F:\Practice\DotNetCore

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:37 AM                dotnetcorewithDS


PS F:\Practice\DotNetCore> cd .\dotnetcorewithDS\
PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet new sln
PS F:\Practice\DotNetCore\dotnetcorewithDS> dir


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          5/4/2022   3:37 AM            442 dotnetcorewithDS.sln


The template "ASP.NET Core Web API" was created successfully.

Processing post-creation actions...
Running 'dotnet restore' on F:\Practice\DotNetCore\dotnetcorewithDS\dotnetcorewithDS\dotnetcorewithDS.csproj...
  Determining projects to restore...
  Restored F:\Practice\DotNetCore\dotnetcorewithDS\dotnetcorewithDS\dotnetcorewithDS.csproj (in 615 ms).
Restore succeeded.



    Directory: F:\Practice\DotNetCore\dotnetcorewithDS


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:38 AM                dotnetcorewithDS
-a----          5/4/2022   3:37 AM            442 dotnetcorewithDS.sln


PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet new classlib -n DNCDSApplication
The template "Class Library" was created successfully.

Processing post-creation actions...
Running 'dotnet restore' on F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSApplication\DNCDSApplication.csproj...
  Determining projects to restore...
  Restored F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSApplication\DNCDSApplication.csproj (in 121 ms).
Restore succeeded.

PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet new --help
Usage: new [options]

Options:
  -h, --help                     Displays help for this command.
  -l, --list <PARTIAL_NAME>      Lists templates containing the specified template name. If no name is specified, lists all templates.
  -n, --name                     The name for the output being created. If no name is specified, the name of the output directory is used.
  -i, --install                  Installs a source or a template package.
  -u, --uninstall                Uninstalls a source or a template package.
  --interactive                  Allows the internal dotnet restore command to stop and wait for user input or action (for example to complete authentication).
  --add-source, --nuget-source   Specifies a NuGet source to use during install.
  --type                         Filters templates based on available types. Predefined values are "project" and "item".
  --dry-run                      Displays a summary of what would happen if the given command line were run if it would result in a template creation.
  --force                        Forces content to be generated even if it would change existing files.
  -lang, --language              Filters templates based on language and specifies the language of the template to create.
  --update-apply                 Check the currently installed template packages for update, and install the updates.
  --search <PARTIAL_NAME>        Searches for the templates on NuGet.org.
  --author <AUTHOR>              Filters the templates based on the template author. Applicable only with --search or --list | -l option.
  --package <PACKAGE>            Filters the templates based on NuGet package ID. Applies to --search.
  --columns <COLUMNS_LIST>       Comma separated list of columns to display in --list and --search output.
                                 The supported columns are: language, tags, author, type.
  --columns-all                  Display all columns in --list and --search output.
  --tag <TAG>                    Filters the templates based on the tag. Applies to --search and --list.


PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet new classlib -n DNCDSDomain     
The template "Class Library" was created successfully.

Processing post-creation actions...
Running 'dotnet restore' on F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSDomain\DNCDSDomain.csproj...
  Determining projects to restore...
  Restored F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSDomain\DNCDSDomain.csproj (in 127 ms).
Restore succeeded.

PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet new classlib -n DNCDSPersistence
The template "Class Library" was created successfully.

Running 'dotnet restore' on F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence\DNCDSPersistence.csproj...
  Restored F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence\DNCDSPersistence.csproj (in 124 ms).


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:40 AM                DNCDSApplication
d-----          5/4/2022   3:38 AM                dotnetcorewithDS
-a----          5/4/2022   3:37 AM            442 dotnetcorewithDS.sln


PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet sln add .\dotnetcorewithDS\dotnetcorewithDS.csproj
Project `dotnetcorewithDS\dotnetcorewithDS.csproj` added to the solution.
PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet sln add .\DNCDSDomain\DNCDSDomain.csproj
Project `DNCDSDomain\DNCDSDomain.csproj` added to the solution.
PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet sln add .\DNCDSApplication\DNCDSApplication.csproj
Project `DNCDSApplication\DNCDSApplication.csproj` added to the solution.
PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet sln add .\DNCDSPersistence\DNCDSPersistence.csproj
Project `DNCDSPersistence\DNCDSPersistence.csproj` added to the solution.
PS F:\Practice\DotNetCore\dotnetcorewithDS> dotnet sln list
Project(s)
----------
dotnetcorewithDS\dotnetcorewithDS.csproj
DNCDSDomain\DNCDSDomain.csproj
DNCDSPersistence\DNCDSPersistence.csproj


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS\dotnetcorewithds


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:38 AM                Controllers
d-----          5/4/2022   3:38 AM                obj
d-----          5/4/2022   3:38 AM                Properties
-a----          5/4/2022   3:38 AM            127 appsettings.Development.json
-a----          5/4/2022   3:38 AM            151 appsettings.json
-a----          5/4/2022   3:38 AM            327 dotnetcorewithDS.csproj
-a----          5/4/2022   3:38 AM            557 Program.cs


PS F:\Practice\DotNetCore\dotnetcorewithDS\dotnetcorewithds> dotnet add reference ..\DNCDSApplication\
Reference `..\DNCDSApplication\DNCDSApplication.csproj` added to the project.
PS F:\Practice\DotNetCore\dotnetcorewithDS\dotnetcorewithds> CD..
PS F:\Practice\DotNetCore\dotnetcorewithDS> DIR



Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:40 AM                DNCDSApplication
d-----          5/4/2022   3:42 AM                DNCDSDomain
d-----          5/4/2022   3:42 AM                DNCDSPersistence
d-----          5/4/2022   3:38 AM                dotnetcorewithDS
-a----          5/4/2022   3:46 AM           2516 dotnetcorewithDS.sln


PS F:\Practice\DotNetCore\dotnetcorewithDS> CD CNCdsapplication
At line:1 char:1
    + CategoryInfo          : ObjectNotFound: (F:\Practice\Dot...NCdsapplication:String) [Set-Location], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand
 
PS F:\Practice\DotNetCore\dotnetcorewithDS> cd .\DNCDSApplication\
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSApplication> dir


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSApplication


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:40 AM                obj
-a----          5/4/2022   3:40 AM             61 Class1.cs

PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSApplication> dotnet add reference ..\DNCDSPersistence\DNCDSPersistence.csproj
Reference `..\DNCDSPersistence\DNCDSPersistence.csproj` added to the project.
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSApplication> cd.. 


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:40 AM                DNCDSApplication
d-----          5/4/2022   3:42 AM                DNCDSDomain
d-----          5/4/2022   3:42 AM                DNCDSPersistence
d-----          5/4/2022   3:38 AM                dotnetcorewithDS
-a----          5/4/2022   3:46 AM           2516 dotnetcorewithDS.sln

PS F:\Practice\DotNetCore\dotnetcorewithDS> cd .\DNCDSPersistence\
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence> dotnet new refernce ..\DNCDSDomain\DNCDSDomain.csproj
Error: Invalid option(s):
   dotnet new -h
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence> dir ..\DNCDSDomain\


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSDomain


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:42 AM                obj
-a----          5/4/2022   3:42 AM             56 Class1.cs
-a----          5/4/2022   3:42 AM            215 DNCDSDomain.csproj
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence> dotnet new refernce ..\DNCDSDomain\DNCDSDomain.csproj
Error: Invalid option(s):
  ..\DNCDSDomain\DNCDSDomain.csproj
For usage information, run:
   dotnet new -h
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence> dor
PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence> dir


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          5/4/2022   3:42 AM             61 Class1.cs
-a----          5/4/2022   3:42 AM            215 DNCDSPersistence.csproj


PS F:\Practice\DotNetCore\dotnetcorewithDS\DNCDSPersistence> cd..
PS F:\Practice\DotNetCore\dotnetcorewithDS> dir


    Directory: F:\Practice\DotNetCore\dotnetcorewithDS


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          5/4/2022   3:40 AM                DNCDSApplication
d-----          5/4/2022   3:42 AM                DNCDSDomain
d-----          5/4/2022   3:42 AM                DNCDSPersistence
d-----          5/4/2022   3:38 AM                dotnetcorewithDS
-a----          5/4/2022   3:46 AM           2516 dotnetcorewithDS.sln