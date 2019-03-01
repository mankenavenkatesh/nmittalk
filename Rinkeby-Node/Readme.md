Installation
Install Binary Distribution
Mac OS with Homebrew
Prerequisites
Homebrew
Install Using Homebrew
$ brew tap pegasyseng/pantheon
$ brew install pantheon


Display Pantheon command line help to confirm installation:
$ pantheon --help


Windows with Chocolatey
Prerequisites
Chocolatey
Note
Close and reopen the terminal after installing Chocolatey.
Install Using Chocolatey
To install from Chocolatey package:
choco install pantheon
Display Pantheon command line help to confirm installation:
pantheon --help


Linux / Unix / Windows without Chocolatey
Prerequisites
Java JDK
Attention
Pantheon requires Java 8+ to compile; earlier versions are not supported. Pantheon is currently supported only on 64-bit versions of Windows, and requires a 64-bit version of JDK/JRE. We recommend that you also remove any 32-bit JDK/JRE installations.
Linux Open File Limit
If synchronizing to MainNet on Linux or other chains with large data requirements, increase the maximum number of open files allowed using ulimit. If the open files limit is not high enough, a Too many open files RocksDB exception occurs.
Install from Packaged Binaries
Download the Pantheon packaged binaries.
Unpack the downloaded files and change into the pantheon-<release> directory.
Display Pantheon command line help to confirm installation:
Linux/macOS
$ bin/pantheon --help

