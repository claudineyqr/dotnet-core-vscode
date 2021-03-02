# Configuração Visual Studio Code (.NET Core)

## Instalação .NET Core

### Download SDK

> [https://dotnet.microsoft.com/download/visual-studio-sdks](https://dotnet.microsoft.com/download/visual-studio-sdks)

## Ferramentas CLI

### LibMan CLI

[Docs](https://docs.microsoft.com/pt-br/aspnet/core/client-side/libman/libman-cli)

``dotnet tool install --global Microsoft.Web.LibraryManager.Cli``

### Entity Framework Core-CLI

[Docs](https://docs.microsoft.com/pt-br/ef/core/cli/dotnet)

``dotnet tool install --global dotnet-ef``

``dotnet tool update --global dotnet-ef``

### WCF dotnet-svcutil tool for .NET Core

[Docs](https://docs.microsoft.com/pt-br/dotnet/core/additional-tools/dotnet-svcutil-guide?tabs=dotnetsvcutil2x)

``dotnet tool install --global dotnet-svcutil``

``dotnet add package System.ServiceModel.Http``

## Visual Studio Code

### Download

> [https://code.visualstudio.com](https://code.visualstudio.com)

### Plugins

- [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
- [.NET Core User Secrets](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.user-secrets)
- [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher)
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [C# Namespace Autocompletion](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.namespace)
- [C# Format Usings](https://marketplace.visualstudio.com/items?itemName=gaoshan0621.csharp-format-usings)
- [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
- [C# Workspace](https://marketplace.visualstudio.com/items?itemName=qp.csharp-workspace)
- [dotnet](https://marketplace.visualstudio.com/items?itemName=leo-labs.dotnet)
- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
- [LibMan Tools](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.libman)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [NuGet Gallery](https://marketplace.visualstudio.com/items?itemName=patcx.vscode-nuget-gallery)
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [ResXpress](https://marketplace.visualstudio.com/items?itemName=PrateekMahendrakar.resxpress)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- [Snippets Creator](https://marketplace.visualstudio.com/items?itemName=claudineyqr.snippets-creator)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [Visual Studio Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vs-keybindings)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [VZ DotNet File Templates](https://marketplace.visualstudio.com/items?itemName=VisualZoran.vz-dotnet-file-templates)
- [VZ File Templates](https://marketplace.visualstudio.com/items?itemName=VisualZoran.vz-file-templates)
- [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

### Configurações

[settings.json](settings.json)

## Projeto

### Pacotes [Nuget](https://www.nuget.org/)

Para o funcionamento do Scafolding e EF Migrations, é necessário instalar os seguintes pacotes no projeto.

- [Microsoft.Composition](https://www.nuget.org/packages/Microsoft.Composition/)
- [System.Composition](https://www.nuget.org/packages/System.Composition/)
- [Microsoft.VisualStudio.Web.CodeGeneration.Design](https://www.nuget.org/packages/Microsoft.VisualStudio.Web.CodeGeneration.Design/)
- [Microsoft.EntityFrameworkCore.Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools/)
- [Microsoft.EntityFrameworkCore.Design](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/)
