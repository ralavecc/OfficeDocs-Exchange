---
title: 'Reset Password role: Exchange 2013 Help'
TOCTitle: Reset Password role
ms:assetid: d80101f1-7e3d-4a61-b93a-23da23e95e93
ms:mtpsurl: https://technet.microsoft.com/library/JJ657499(v=EXCHG.150)
ms:contentKeyID: 49289428
ms.reviewer: 
manager: serdars
ms.author: serdars
author: msdmaguire
ms.topic: article
description: The Reset Password management role enables users to reset their passwords, and administrators to reset user passwords.
f1.keywords:
- NOCSH
mtps_version: v=EXCHG.150
---

# Reset Password role

_**Applies to:** Exchange Server 2013_

The Reset Password management role enables individual users to reset their own passwords and administrators to reset users' passwords in an organization.

## Default management role assignments

This role has role assignments to one or more role assignees. The following table indicates whether the role assignment is regular or delegating, and also indicates the management scopes applied to each assignment. The following list describes each column:

  - **Regular assignment**: Regular role assignments enable the role assignee to access the permissions provided by the management role entries on this role.

  - **Delegating assignment**: Delegating role assignments give the role assignee the ability to assign this role to role groups, users, or USGs.

  - **Recipient read scope**: The recipient read scope determines what recipient objects the role assignee is allowed to read from Active Directory.

  - **Recipient write scope**: The recipient write scope determines what recipient objects the role assignee is allowed to modify in Active Directory.

  - **Configuration read scope**: The configuration read scope determines what configuration and server objects the role assignee is allowed to read from Active Directory.

  - **Configuration write scope**: The configuration write scope determines what organizational and server objects the role assignee is allowed to modify in Active Directory.

### Default management role assignments for this role

<table >
<colgroup>
<col  />
<col  />
<col  />
<col  />
<col  />
<col  />
<col  />
</colgroup>
<thead>
<tr class="header">
<th>Role group</th>
<th>Regular assignment</th>
<th>Delegating assignment</th>
<th>Recipient read scope</th>
<th>Recipient write scope</th>
<th>Configuration read scope</th>
<th>Configuration write scope</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="organization-management-exchange-2013-help.md">Organization Management</a></p></td>
<td><p> </p></td>
<td><p>X</p></td>
<td><p><code>Organization</code></p></td>
<td><p><code>Organization</code></p></td>
<td><p><code>OrganizationConfig</code></p></td>
<td><p><code>OrganizationConfig</code></p></td>
</tr>
</tbody>
</table>
