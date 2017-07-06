Role Name
========

This role takes care of setting up AWS metrics on a machine and reporting the
stats to CloudWatch (where we can then have alerts).

Role Variables
--------------

vars/main.yml:
- `required_apt_packages`: packages that must be installed through apt-get (for Debian-based OSes)
- `required_yum_packages`: packages that must be installed through yum (for RedHat-based OSes)
- `aws_monitor_scripts_path`: path where the `aws-scripts-mon` folder should
                              end up
