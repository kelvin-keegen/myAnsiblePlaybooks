# Instructions

### Single playbook (All-in-one)

`packageUpdater.yml`

`serverSetup.yml` -> for Ubuntu servers

`removeDefaultUser.yml` -> Default user cleanup

### For a newly installed system, run the playbooks in the following order:

*corePackageInstaller.yml*

*userAddition.yml*

*configure_SSH_user.yml*

*sshd_Modification.yml*

*removeDefaultUser.yml*

*packageUpdater.yml*

### docker installer below

*dockerInstaller.yml*
