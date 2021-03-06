---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: brianlic
author: brianlic-msft
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: Microsoft.IdentityServer.Management.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 12/20/2016
ms.prod: w10
ms.technology: powershell-windows
ms.topic: reference
online version: 
schema: 2.0.0
title: Get-AdfsSslCertificate
ms.assetid: A4B2792E-EDC0-493F-96E0-1E96C3E83EC9
---

# Get-AdfsSslCertificate

## SYNOPSIS
Gets the host name, port, and certificate hash for SSL bindings configured for AD FS and the device registration service.

## SYNTAX

```
Get-AdfsSslCertificate [<CommonParameters>]
```

## DESCRIPTION
The **Get-AdfsSslCertificate** cmdlet gets the host name, port, and certificate hash for all SSL bindings configured for Active Directory Federation Services (AD FS) and, if enabled, the device registration service.

## EXAMPLES

### Example 1: Get information for SSL bindings
```
PS C:\> Get-AdfsSslCertificate
HostName                           PortNumber  CertificateHash
--------                           ----------  ---------------
sts.contoso100.com                    443      4195EE03C2721F7478B67E94BD83BB373FE22D98
localhost                             443      4195EE03C2721F7478B67E94BD83BB373FE22D98
sts.contoso100.com                   49443     4195EE03C2721F7478B67E94BD83BB373FE22D98
EnterpriseRegistration.contoso...     443      4195EE03C2721F7478B67E94BD83BB373FE22D98
```

This command gets the host names, ports, and certificate hashes for all configured SSL bindings.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Set-AdfsSslCertificate](./Set-AdfsSslCertificate.md)

