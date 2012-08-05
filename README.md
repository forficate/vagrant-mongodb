vagrant-mongodb
===============

Barebones mongodb development box. Uses vagrant / puppet for provisioning

To use this you need a ubuntu 12.04 base box named 'ubuntu-precise-64' .
To get this follow the instructions at
https://github.com/cal/vagrant-ubuntu-precise-64 .

If you are using OSX using the above instructions you will need to
update your version of tar using:

```
brew install
https://raw.github.com/oschrenk/homebrew-dupes/edbc2b464d0bf4420508297418481178299f420a/libarchive.rb
```

This is because of https://github.com/cal/vagrant-ubuntu-precise-64/issues/7 . With a updated version of bsdtar everything works. Installing the ubuntu 12.04 base image is a one time process, after the image is installed you can delete the vagrant-ubuntu-precise-64 project.
