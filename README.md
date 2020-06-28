<a href="https://github.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/packages">
<img src="https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/img_main.png?token=ADLXRJNSDSBZT573K5XD2CC676NSO"/>
</a>

# Awesome NuGet Packages for Xamarin.Forms

## Preamble

This repository collects all MIT Licensed Xamarin.Forms Open Source Projects that are ideal for creating a `NuGet Package`.

To see all the content click [HERE](https://github.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/packages).

#### IMPORTANT: BEFORE INSTALLING A NUGET PACKAGE, YOU MUST TAKE INTO ACCOUNT THE DEPENDENCIES IT HAS, USE WITH CARE.

## NuGet Package Projects

<a href="https://github.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/packages/287345">
<img src="https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_NuGetPackages/CC_CR_Xamarin_Forms_TabView.png" />
</a>

## Installation in Visual Studio 2019 (For all developers)

In a folder of your choice, fork, then clone this branch repository called `NuGetLocalPackages`.

<img src="https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/Branch_and_Fork.png?token=ADLXRJPHYHY2L7NRZBPITL2677R7K" />

In the Package Sources located in `TOOLS / Options / NuGet Package Manager` implement the name and location of the repository, then click Update and OK.

<img src="https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/Add_Package_Source.png?token=ADLXRJP3ZHPTOGZBL5AXS6S677SOM" />

To use them select the name of the Package Source.

<img src="https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/Select_Package_Source.png?token=ADLXRJPAXIBOEJSECXLBZ4C677STE" />

#### IMPORTANT: "Do not change the location of the NuGet Packages as others will be incorporated".

## Installation in Visual Studio 2019 (Just for my team)

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
nuget source Add -Name "GitHubPackage" -Source "https://nuget.pkg.github.com/danielmonettelli/index.json" -UserName danielmonettelli -Password MY_TOKEN
```

With this you will have it directly in the `NuGet Package Manager`.

![md-links](https://raw.githubusercontent.com/danielmonettelli/Awesome-NuGet-Packages-for-Xamarin.Forms/master/Images_Readme/NuGet_Package_Manager.png?token=ADLXRJJWCKB5FRMZXJOSZ3K673MRC)

## About the Authors' Mentions

All mentions, including the name of the owner and the original project, are implemented in the `.nuspec` of each NuGet Package.

## Credits

This project would not have been possible without all the authors collaborating with the Xamarin Community. Thank you very much for making this possible.
