# StreamCatcher
.NetCore library to save streams into a file.

You can get the entire source code for adding your own business logic making a donation to my PayPal Account (<ilya_pirozhenko@outlook.com>). Send me a copy of the email message referencing the payment of USD 380 and I'll send you the source code. Feel free to ask for a trial version of the code.

Follow the following steps to setup your development/production enviroment and run the library.

## What is .NET Core?

.NET Core is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub](https://github.com/dotnet/core). It is cross-platform, supporting Windows, macOS and Linux, and can be used in device, cloud, and embedded/IoT scenarios.

.NET has several capabilities that make development easier, including automatic memory management, (runtime) generic types, reflection, asynchrony, concurrency, and native interop. Millions of developers take advantage of these capabilities to efficiently build high-quality applications.

You can use C# to write .NET Core apps. C# is simple, powerful, type-safe, and object-oriented while retaining the expressiveness and elegance of C-style languages. Anyone familiar with C and similar languages will find it straightforward to write in C#.

[.NET Core](https://github.com/dotnet/core) is open source (MIT and Apache 2 licenses) and was contributed to the [.NET Foundation](http://dotnetfoundation.org) by Microsoft in 2014. It can be freely adopted by individuals and companies, including for personal, academic or commercial purposes. Multiple companies use .NET Core as part of apps, tools, new platforms and hosting services.

> https://docs.microsoft.com/dotnet/core/

![logo](https://avatars0.githubusercontent.com/u/9141961?v=3&amp;s=100)

# Installation of .NET Core 1.1.4

.NET Core 1.1.4 is comprised of:

* .NET Core Runtime 1.1.4
* .NET Core SDK 1.1.4

|         | SDK Installer                                         | SDK Binaries                                                         | Runtime Installer                                                  | Runtime Binaries                                                   |
| ------- | :---------------------------------------------------: | :-------------------------------------------------------------------:| :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| Windows                 | [32-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-win-x86.1.1.4.exe) / [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-win-x64.1.1.4.exe)  | [32-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-win-x86.1.1.4.zip) / [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-win-x64.1.1.4.zip) | [32-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-win-x86.1.1.4.exe) / [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-win-x64.1.1.4.exe) | [32-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-win-x86.1.1.4.zip) / [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-win-x64.1.1.4.zip) |
| macOS                   | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-osx-x64.1.1.4.pkg)  | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-osx-x64.1.1.4.tar.gz)                          | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-osx-x64.1.1.4.pkg) | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-osx-x64.1.1.4.tar.gz) |
| CentOS 7.1              | -                                                         | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-centos-x64.1.1.4.tar.gz)                          | - | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-centos-x64.1.1.4.tar.gz) |
| Debian 8                | -                                                         | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-debian-x64.1.1.4.tar.gz)                          | - | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-debian-x64.1.1.4.tar.gz) |
| Ubuntu 14.04            |[64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-sdk-ubuntu-x64.1.1.4.deb)   | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-ubuntu-x64.1.1.4.tar.gz)                          |[64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-sharedframework-ubuntu-x64.1.1.4.deb) | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-ubuntu-x64.1.1.4.tar.gz) |
| Ubuntu 16.04            |[64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-sdk-ubuntu.16.04-x64.1.1.4.deb)   | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-ubuntu.16.04-x64.1.1.4.tar.gz)                          |[64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-sharedframework-ubuntu.16.04-x64.1.1.4.deb) | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-ubuntu.16.04-x64.1.1.4.tar.gz) |
| RHEL 7                  | -                                                         | [64-bit](https://download.microsoft.com/download/F/4/F/F4FCB6EC-5F05-4DF8-822C-FF013DF1B17F/dotnet-dev-rhel-x64.1.1.4.tar.gz)                          | - | [64-bit](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/dotnet-rhel-x64.1.1.4.tar.gz) |

**Checksum** files to verify downloads are available as follows:
* [Checksums_Runtime](https://dotnetcli.blob.core.windows.net/dotnet/checksums/1.1.4-runtime-sha.txt)
* [Checksums_SDK](https://dotnetcli.blob.core.windows.net/dotnet/checksums/1.1.4-sdk-sha.txt)

**Debug Symbols**
* [Shared Framework](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/corefx-1.1.4-symbols.zip)
* [Runtime](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/coreclr-1.1.4-symbols.zip)

## Docker

Images for .NET Core 1.1.4 are available on [Docker](https://hub.docker.com/r/microsoft/dotnet/).

## Installing .NET Core on Linux

### Ubuntu and Debian based systems

Register the Microsoft key, the product repository for your distro and install required system dependencies with the following scripts.

#### Ubuntu 16.04 and Linux Mint 18

```bash
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg
sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-xenial-prod xenial main" > /etc/apt/sources.list.d/dotnetdev.list'
```

#### Ubuntu 14.04 and Linux Mint 17

```bash
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg
sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-trusty-prod trusty main" > /etc/apt/sources.list.d/dotnetdev.list'
```

#### Update package cache and install .NET Core

```bash
sudo apt-get update
sudo apt-get install dotnet-dev-1.1.4
```

## Installation from a binary archive

Installing from the packages detailed above is recommended and you can also install from binary archive. When using binary archives to install, the contents must be extracted to a user location such as `$HOME/dotnet` and a symbolic link created for `dotnet`. This is a change from previous versions of .NET Core.

```bash
mkdir -p $HOME/dotnet && tar zxf dotnet.tar.gz -C $HOME/dotnet
export PATH=$PATH:$HOME/dotnet
```

## Windows Server Hosting

If you are looking to host stand-alone apps on Windows Servers, the ASP.NET Core Module for IIS can be installed separately on servers without installing .NET Core runtime. You can download the Windows (Server Hosting) installer and run the following command from an Administrator command prompt:

[DotNetCore.1.0.7_1.1.4-WindowsHosting.exe](https://download.microsoft.com/download/6/F/B/6FB4F9D2-699B-4A40-A674-B7FF41E0E4D2/DotNetCore.1.0.7_1.1.4-WindowsHosting.exe)
