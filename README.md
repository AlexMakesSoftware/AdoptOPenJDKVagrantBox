Creates an Ubuntu virtual machine with AdoptOPenJDK Java for testing purposes.

Create with

<code>
Vagrant up
</code>

Connect with
<code>
Vagrant ssh
</code>

Confirm Java version installed with
<code>
Java -version
</code>

Please note that this will likely stop working if AdoptOPenJDK cease supporting this version of Java. If that happens, modify bootstrap.sh with the installation instructions contained at https://adoptopenjdk.net/installation.html?variant=openjdk16&jvmVariant=hotspot#linux-pkg (or similar).
