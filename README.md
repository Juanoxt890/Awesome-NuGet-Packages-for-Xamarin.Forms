<a href="https://github.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/packages">
<img src="https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/img_main.png?token=ADLXRJNSDSBZT573K5XD2CC676NSO"/>
</a>

# Awesome NuGet Packages for Xamarin.Forms

## Preamble

This repository collects all MIT Licensed Xamarin.Forms Open Source Projects that are ideal for creating a `NuGet Package`.

To see all the content click [HERE](https://github.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/packages).

## NuGet Package Projects

- [Xamarin.Forms.TabView](https://github.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/packages/287345) by Javier Suárez Ruiz.

## Installation in Visual Studio 2019

### Installing Chocolatey with cmd.exe

Run the following command with Administrator Privileges:

```sh
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command " [System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```
### Installing Chocolatey with PowerShell.exe

Run the following command with Administrator Privileges:

```sh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

### Installing NuGet.CommandLine

To avoid generating `nuget.exe`, the following command will install the environment paths in Windows, so "nuget" will always be available.

In cmd.exe or PowerShell.exe, paste the following command with Administrator Privileges:

```sh
cinst Nuget.CommandLine
```

### Add Package Sources to Visual Studio 2019

In cmd.exe or PowerShell.exe, paste the following command:

```sh
nuget source Add -Name "GitHubPackage" -Source "https://nuget.pkg.github.com/danielmonettelli/index.json" -UserName danielmonettelli -Password f3df17d5829c5c8809c0e2fd9ea8b40c6c1436b1
```

With this you will have it directly in the `NuGet Package Manager`.

![md-links](https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/NuGet_Package_Manager.png?token=ADLXRJJWCKB5FRMZXJOSZ3K673MRC)

## About the Authors' Mentions

All mentions, including the name of the owner and the original project, are implemented in the `.nuspec` of each NuGet Package.

## Credits

This project would not have been possible without all the authors collaborating with the Xamarin Community. Thank you very much for making this possible.
