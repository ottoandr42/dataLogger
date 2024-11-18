# dataLogger

A set of libraries and a VI package that contains classes and an actor for data logging in an actor framework based project.

Use the VIP file in the builds folder to install this package on your system. The palette provides send vi's to reference in your project as well as a "new logger" sub VI to pull the data logger actor into your project's dependencies.

There is an interface with reply messages that a calling actor can inherit to get state updates from the data logger actor.

The default implementation of the data logger actor uses TDMS files.
