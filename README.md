# config-files

[Elektra](https://www.libelektra.org) serves as a universal and secure framework to access configuration parameters in a global, hierarchical key database. 

Its new three-way merge should be able to merge three versions of a configuration file that occur during a package upgrade:
The default version from before the upgrade, the one with all modifications (such as changed values or additional comments) and the new default from the upgraded package.
This way the required amount of manual interaction is reduced.

To develop the new tool we rely on test cases.
Apart from many synthetic tests we try to gather real-world data.
Real-world data helps us identifying which parts are important and that those important parts work properly.
You can help us build a reliable merge tool by submitting your configuration files to this repository or by sending an email to e1634025@student.tuwien.ac.at
