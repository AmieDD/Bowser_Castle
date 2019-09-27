# Dotnet in the Bowser Castle
```
#   ▄▀▀█▄▄   ▄▀▀▀▀▄   ▄▀▀▄    ▄▀▀▄  ▄▀▀▀▀▄  ▄▀▀█▄▄▄▄  ▄▀▀▄▀▀▀▄      ▄▀▄▄▄▄   ▄▀▀█▄   ▄▀▀▀▀▄  ▄▀▀▀█▀▀▄  ▄▀▀▀▀▄     ▄▀▀█▄▄▄▄ 
#  ▐ ▄▀   █ █      █ █   █    ▐  █ █ █   ▐ ▐  ▄▀   ▐ █   █   █     █ █    ▌ ▐ ▄▀ ▀▄ █ █   ▐ █    █  ▐ █    █     ▐  ▄▀   ▐ 
#    █▄▄▄▀  █      █ ▐  █        █    ▀▄     █▄▄▄▄▄  ▐  █▀▀█▀      ▐ █        █▄▄▄█    ▀▄   ▐   █     ▐    █       █▄▄▄▄▄  
#    █   █  ▀▄    ▄▀   █   ▄    █  ▀▄   █    █    ▌   ▄▀    █        █       ▄▀   █ ▀▄   █     █          █        █    ▌  
#   ▄▀▄▄▄▀    ▀▀▀▀      ▀▄▀ ▀▄ ▄▀   █▀▀▀    ▄▀▄▄▄▄   █     █        ▄▀▄▄▄▄▀ █   ▄▀   █▀▀▀    ▄▀         ▄▀▄▄▄▄▄▄▀ ▄▀▄▄▄▄   
#  █    ▐                     ▀     ▐       █    ▐   ▐     ▐       █     ▐  ▐   ▐    ▐      █           █         █    ▐   
#  ▐   
       
  / \               / \
 /   \             /   \
(_____)           (_____)
 |   |  _   _   _  |   |
 | O |_| |_| |_| |_| O |
 |-  |          _  | - |
 |   |   - _^_     |   |
 |  _|    //|\\  - |   |
 |   |   ///|\\\   |  -|
 |-  |_  |||||||   |   |
 |   |   |||||||   |-  |
 |___|___|||||||___|___|
         (      (
          \      \
           )      )
           |      |
           (      (
            \      \
```

dotnet try Bowser Castle for .NET Core 3.0 and C# 8.0
Interactive markdown files documentation for .NET Core to use for code tutorials on my [webpage](https://www.amiedd.com)

This project is based off [Try .NET ](https://github.com/dotnet/try)

**Project Webpage**
https://amiedd.github.io/dotnet_Bowser_Castle/

## IDE
Either one of the the below editors is compatible
- Visual Studio 2019 (2017 isn't comptaible I found out the hard way on that one)
- Visual Studio Code

## Downloads
- [dotnet sdk 3.0](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-3.0.100-windows-x64-installer)
- [dotnet try global tool ](https://www.nuget.org/packages/dotnet-try/)
```dotnet
dotnet tool install --global dotnet-try --version 1.0.19317.5
```
### Updating the dotnet global tool
```dotnet
dotnet tool update -g dotnet-try
```

Verify dotnet try global tool with the command below
```dotnet
dotnet try -h you will see a list of commands:
```

Command	| Purpose |
----- | ----- | 
demo |	Try .NET content with an interactive demo |
verify	|Verify Markdown files  |

## Troubleshooting :confused:
1. I've downloaded .NET Core 3.0, but when I open my project I get a Error "Error	NETSDK1045	The current .NET SDK does not support targeting .NET Core 3.0.  Either target .NET Core 2.2 or lower, or use a version of the .NET SDK that supports .NET Core 3.0."
![.NET 3 Troubleshooting](https://github.com/AmieDD/dotnet_Bowser_Castle/blob/master/Images/dotnet3_missing.PNG)
 *Solution* If you've already installed .NET 3.0 SDK try to restart Visual Studio 2019 and your computer

### Change Log
Name  | Version | Date | Change Description
-------------- | ------------- | ------ | -----
Amie Dansby|	0.0.1	|9/27/2019|	 dotnet try bowser castle project created



