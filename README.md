# in-place_migrations

Here you will find some tested templates for SUSE Manager in-place migrations.  Please provide feedback if you encounter issues or would like to contribute more of them.

When doing an upgrade with SUSE Manager, you should have these entries in the Kernel Options box on the Profile Details page:
```
autoupgrade=1 insecure=1 useonlinerepo=1
```
For further info on SUSE Manager in-place migrations - see this project wiki for docs in progress
https://github.com/dvosburg/in-place_migrations/wiki

And the official SUMA documentation on Provisioning:
https://documentation.suse.com/suma/4.3/en/suse-manager/reference/systems/system-details/sd-provisioning.html
