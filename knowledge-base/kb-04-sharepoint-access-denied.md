# KB 04 - SharePoint Access Denied

## Issue Summary

A user reports that they cannot access a SharePoint site, document library or file.

## Common Symptoms

- Access denied message
- SharePoint site cannot be opened
- Document library is not accessible
- User can access the site but not a particular document
- User has read-only access when editing is required

## Possible Causes

- User is not a member of the required group
- SharePoint permissions are incorrect
- Access is inherited from a parent site or library
- File or folder has unique permissions
- User is signed into the wrong account
- Sharing restrictions prevent access

## Troubleshooting Steps

1. Confirm the affected user and SharePoint URL.
2. Identify whether the issue affects the site, library, folder or file.
3. Open the SharePoint site using authorised administrator access.
4. Review Site permissions.
5. Check site owners, members and visitors.
6. Review Microsoft 365 group membership if the site is group-connected.
7. Check whether the affected library or file has unique permissions.
8. Review Manage access for the affected document.
9. Confirm the access level the user requires.
10. Make authorised permission changes or escalate to the site owner.
11. Ask the user to test access again.

## Important Permission Note

SharePoint permissions may be inherited from the site or assigned through Microsoft 365 groups.

Removing a direct sharing link does not necessarily remove access granted through group membership.

Avoid changing site-wide permissions to resolve an individual document access issue without first reviewing inheritance.

## Verification

Confirm that the user can access the required resource with the correct permissions.

## Resolution Documentation

Record the permission source, authorised changes and outcome of user testing.

## Skills Practised

- SharePoint Online support
- Site permissions
- Document library access
- Microsoft 365 group membership
- Permission troubleshooting
