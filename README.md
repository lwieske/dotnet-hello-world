# Hello World in .NET

![.NET
Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Microsoft_.NET_logo.svg/240px-Microsoft_.NET_logo.svg.png)

This is a trivial 'Hello World' to check availability and configuration of the
dotnet toolchain.

## Setup

Mit *dotnet new console ...* wurde der funktionale Inhalt im Repo generiert.  

```bash
% dotnet new console -o dotnet-hello-world -f net6.0
Die Vorlage "Konsolen-App" wurde erfolgreich erstellt.

Aktionen nach der Erstellung werden verarbeitet...
"dotnet restore" wird auf /Users/lothar/GitHub/dotnet-hello-world/dotnet-hello-world.csproj ausgeführt...
  Wiederherzustellende Projekte werden ermittelt...
  "/Users/lothar/GitHub/dotnet-hello-world/dotnet-hello-world.csproj" wiederhergestellt (in "40 ms").
Wiederherstellung erfolgreich.


%
```

```bash
git clone https://github.com/lwieske/dotnet-hello-world
cd dotnet-hello-world
```

## Build

```bash
dotnet build
```

## Run

```bash
dotnet run
```

## Example

```bash
% dotnet --info
.NET SDK (gemäß "global.json"):
 Version:   6.0.302
 Commit:    c857713418

Laufzeitumgebung:
 OS Name:     Mac OS X
 OS Version:  12.5
 OS Platform: Darwin
 RID:         osx.12-arm64
 Base Path:   /usr/local/share/dotnet/sdk/6.0.302/

global.json file:
  Not found

Host:
  Version:      6.0.7
  Architecture: arm64
  Commit:       0ec02c8c96

.NET SDKs installed:
  6.0.302 [/usr/local/share/dotnet/sdk]

.NET runtimes installed:
  Microsoft.AspNetCore.App 6.0.7 [/usr/local/share/dotnet/shared/Microsoft.AspNetCore.App]
  Microsoft.NETCore.App 6.0.7 [/usr/local/share/dotnet/shared/Microsoft.NETCore.App]

Download .NET:
  https://aka.ms/dotnet-download

Learn about .NET Runtimes and SDKs:
  https://aka.ms/dotnet/runtimes-sdk-info
(base) lothar@deep GitHub %
Session Contents Restored on 2. Aug 2022 at 09:53
Last login: Tue Aug  2 09:53:21 on console
 
% dotnet build
Microsoft (R)-Build-Engine, Version 17.2.0+41abc5629 für .NET
Copyright (C) Microsoft Corporation. Alle Rechte vorbehalten.

  Wiederherzustellende Projekte werden ermittelt...
  Alle Projekte sind für die Wiederherstellung auf dem neuesten Stand.
  dotnet-hello-world -> /Users/lothar/GitHub/dotnet-hello-world/bin/Debug/net6.0/dotnet-hello-world.dll

Der Buildvorgang wurde erfolgreich ausgeführt.
    0 Warnung(en)
    0 Fehler

Verstrichene Zeit 00:00:01.31
% dotnet run
Hello, World!
%
```
