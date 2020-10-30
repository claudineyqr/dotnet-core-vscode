# Configuração ambiente desenvolvimento .NET Core com VS Code

## Instalação .NET Core

#### Download SDK
- [https://dotnet.microsoft.com/download/visual-studio-sdks](https://dotnet.microsoft.com/download/visual-studio-sdks){:target="_blank"}

#### Ferramentas CLI

**LibMan CLI**
``dotnet tool install --global Microsoft.Web.LibraryManager.Cli``

**Entity Framework Core-CLI**
``dotnet tool install --global dotnet-ef``

## Visual Studio Code

#### Download
- [https://code.visualstudio.com](https://code.visualstudio.com){:target="_blank"}

#### Plugins

- [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer){:target="_blank"}
- [.NET Core Tools](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet){:target="_blank"}
- [ASP.NET Core Scaffolding](https://marketplace.visualstudio.com/items?itemName=firefox.scaffold)
- [ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=rahulsahay.Csharp-ASPNETCore){:target="_blank"}
- [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher){:target="_blank"}
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag){:target="_blank"}
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments){:target="_blank"}
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2){:target="_blank"}
- [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp){:target="_blank"}
- [C# Extensions](https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions){:target="_blank"}
- [C# Sort Usings](https://marketplace.visualstudio.com/items?itemName=jongrant.csharpsortusings){:target="_blank"}
- [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment){:target="_blank"}
- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula){:target="_blank"}
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory){:target="_blank"}
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens){:target="_blank"}
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion){:target="_blank"}
- [LibMan Tools](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.libman){:target="_blank"}
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare){:target="_blank"}
- [NuGet Package Manager](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager){:target="_blank"}
- [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype){:target="_blank"}
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense){:target="_blank"}
- [ResXpress](https://marketplace.visualstudio.com/items?itemName=PrateekMahendrakar.resxpress){:target="_blank"}
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode){:target="_blank"}
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons){:target="_blank"}
- [vscode-solution-explorer](https://marketplace.visualstudio.com/items?itemName=fernandoescolar.vscode-solution-explorer){:target="_blank"}
- [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml){:target="_blank"}

#### Configurações

[settings.json](settings.json)

## Projeto

#### Pacotes [Nuget](https://www.nuget.org/){:target="_blank"}

Para o funcinamento do Scafolding e Migrations instalar os seguintes pacotes no projeto

- [Microsoft.Composition](https://www.nuget.org/packages/Microsoft.Composition/){:target="_blank"}
- [System.Composition](https://www.nuget.org/packages/System.Composition/){:target="_blank"}
- [Microsoft.VisualStudio.Web.CodeGeneration.Design](https://www.nuget.org/packages/Microsoft.VisualStudio.Web.CodeGeneration.Design/){:target="_blank"}
- [Microsoft.EntityFrameworkCore.Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools/){:target="_blank"}
- [Microsoft.EntityFrameworkCore.Design](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/){:target="_blank"}
