# Active Directory Common Tasks
# Active Directory Common Tasks

These are the most frequent Active Directory tasks in Tier 1 Help Desk / IT Support roles.  
Steps assume Active Directory Users and Computers (ADUC) or similar tools. Adjust tool names if you practice in a lab (e.g., Azure AD / Entra ID).

## 1. Create a New User Account
1. Open Active Directory Users and Computers.
2. Navigate to the correct Organizational Unit (OU).
3. Right-click → New → User.
4. Enter first name, last name, and logon name.
5. Set a temporary password and check “User must change password at next logon”.
6. Add the user to any required security groups.
7. Click Finish and verify the account appears in the OU.

## 2. Reset a User Password
1. Locate the user account.
2. Right-click the user → Reset Password.
3. Enter a temporary password.
4. Check “User must change password at next logon”.
5. Click OK and confirm the change.

## 3. Unlock a Locked Account
1. Locate the user account.
2. Right-click → Properties.
3. On the Account tab, uncheck “Unlock account” if it is checked.
4. Click Apply → OK.
5. Confirm with the user that they can now log in.

## 4. Add or Remove a User from a Group
1. Locate the user or the group.
2. Open Properties → Member Of (or Members) tab.
3. Click Add or Remove as needed.
4. Apply changes and verify membership.

## 5. Disable an Account (Leaver Process)
1. Locate the user account.
2. Right-click → Disable Account.
3. Optionally move the account to a Disabled Users OU.
4. Document the action in the ticket.
