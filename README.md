# MOLECULE  
create and testing ansible role using molecule and serverspec

## Dependency
- virtualbox
- vagrant
- ansible
- serverspec

## Setup Machine OS
add this in molecule.yml file for setup machine  
```
platforms:
    - name: debian/jessie64
      box: debian/jessie64
      box_url: https://vagrantcloud.com/debian/boxes/jessie64/versions/8.7.0/providers/virtualbox.box
```
