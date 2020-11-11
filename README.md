# Configuração ambiente desenvolvimento .NET Core com VS Code

## Instalação .NET Core

#### Download SDK
- [https://dotnet.microsoft.com/download/visual-studio-sdks](https://dotnet.microsoft.com/download/visual-studio-sdks)

#### Ferramentas CLI

**LibMan CLI**
``dotnet tool install --global Microsoft.Web.LibraryManager.Cli``

**Entity Framework Core-CLI**
``dotnet tool install --global dotnet-ef``

## Visual Studio Code

#### Download
- [https://code.visualstudio.com](https://code.visualstudio.com)

#### Plugins

- [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
- [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [C# Sort Usings](https://marketplace.visualstudio.com/items?itemName=jongrant.csharpsortusings)
- [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
- [LibMan Tools](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.libman)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [NuGet Package Manager](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [ResXpress](https://marketplace.visualstudio.com/items?itemName=PrateekMahendrakar.resxpress)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)

#### Configurações

[settings.json](settings.json)

## Projeto

#### Pacotes [Nuget](https://www.nuget.org/)

Para o funcionamento do Scafolding e Migrations instalar os seguintes pacotes no projeto

- [Microsoft.Composition](https://www.nuget.org/packages/Microsoft.Composition/)
- [System.Composition](https://www.nuget.org/packages/System.Composition/)
- [Microsoft.VisualStudio.Web.CodeGeneration.Design](https://www.nuget.org/packages/Microsoft.VisualStudio.Web.CodeGeneration.Design/)
- [Microsoft.EntityFrameworkCore.Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools/)
- [Microsoft.EntityFrameworkCore.Design](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/)
