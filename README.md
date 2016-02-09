# AD-Groups-in-Server-2008
PowerShell Syntax:
$List = Improt-CSV .\[FILENAME]
ForEach ($User in $List)
{Add-ADGroupMember -identity [GROUPNAME] -Member $User.samaccountname


GROUPS:

CompanyExecutives
SamAccountName
ahake001
mlefleur
jroma123
rxavier1
rxieng01
ralexand

Operations
SamAccountName
rxavier1
pmartina

HumanResources
SamAccountName
mhixon01
wbinder1

OPMarketing
SamAccountName
tharden1
cbeignet
