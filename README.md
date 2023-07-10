# Thin CSharp EditorConfig
This project uses [editorconfig](https://editorconfig.org) to provide a thin but opinionated implemetation of rules for consistent coding in teams. Most of the rules are based of [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers/blob/main/.editorconfig) rules and diverged to be more relevant.

The project utilises nuget `contentFiles` and MSBuild `targets` to copy the `.editorconfig` into the root folder of the project (as opposed to the bin folder). 

## Installation
After installing the nuget package, upon first local build the target file copies the [.editorconfig](EditorConfig/.editorconfig) into the same folder  as `./csproj` file.

## References
- [Code Quality Rules](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/)
- [Code-style rules](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/)

