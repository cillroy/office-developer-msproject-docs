﻿---
title: UserDef Element
TOCTitle: UserDef Element
ms:assetid: b2c8d091-91e3-4720-a04d-9a6a051cbd73
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Bb968649(v=office.12)
ms:contentKeyID: 13188340
ms.date: 05/05/2014
mtps_version: v=office.12
f1_keywords:
- UserDef element
dev_langs:
- xml
---

# UserDef Element

This content is outdated and is no longer being maintained. It is provided as a courtesy for individuals who are still using these technologies. This page may contain URLs that were valid when originally published, but now link to sites or pages that no longer exist.

Indicates whether the custom field is user defined.

    <UserDef>
      BooleanValue
    </UserDef>

## Parent Elements

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="bb968669(v=office.12).md">ExtendedAttribute</a></p></td>
</tr>
</tbody>
</table>

## Occurrences

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum: 0</p>
<p>Maximum: 1</p></td>
</tr>
</tbody>
</table>

## Text Value

A text value of type boolean is required.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0</p></td>
<td><p>False</p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>True</p></td>
</tr>
</tbody>
</table>

## Example

In the following example, the UserDef element indicates that the Health enterprise custom field is user-defined.

``` xml
<ExtendedAttribute>
  <FieldID>188776449</FieldID>
  <FieldName>Health</FieldName>
  <CFType>7</CFType>
  <Guid>0000E8D9-65F1-4769-9BD2-819D38036FCC</Guid>
  <ElemType>20</ElemType>
  <MaxMultiValues>1</MaxMultiValues>
  <UserDef>1</UserDef>
  <SecondaryPID>255885314</SecondaryPID>
  <DefaultGuid>000079D2-4A43-41FC-B264-98D23FADD84B</DefaultGuid>
</ExtendedAttribute>
```

## See Also

#### Concepts

[ExtendedAttribute Elements and XML Structure](bb968579\(v=office.12\).md)

[XML Schema for the ExtendedAttributes Element](bb968705\(v=office.12\).md)
