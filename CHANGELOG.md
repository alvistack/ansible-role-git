# Ansible Role for GIT

## 2.1.0 - TBC

### Major Changes

  - CI with ansible-lint and galaxy-lint-rules
  - Use shell only when shell functionality is required
  - Replace tests from Docker to LXD

## 2.0.0 - 2018-10-25

### Major Changes

  - Upgrade Ansible support to 2.6 or higher
  - Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
  - Install GIT on CentOS 6/7 from IUS
  - Keep APT/YUM cache as-is
  - Update Travis CI test plan

## 1.1.0 - 2017-11-23

### Major Changes

  - Install Git on Ubuntu 16.04/14.04 from PPA
  - Install Git on CentOS 7/6 from stock package
  - Update test cases

## 1.0.0 - 2017-09-25

  - Ininitial release for Ansible 2.4
  - Support both Ubuntu 16.04/14.04 or RHEL/CentOS 7/6