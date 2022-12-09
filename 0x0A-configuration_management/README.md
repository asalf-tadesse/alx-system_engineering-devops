Configuration Management
This project contains tasks for learning about configuration management using Puppet (the Ruby gem).

Tasks To Complete
 0. Create a file
0-create_a_file.pp creates a file in /tmp using Puppet.

Requirements:
File path is /tmp/school.
File permission is 0744.
File owner is www-data.
File group is www-data.
File contains I love Puppet.
 1. Install a package
1-install_a_package.pp installs puppet-lint using Puppet.

Requirements:
Install puppet-lint.
Version must be 2.5.0.
 2. Execute a command
2-execute_a_command.pp creates a manifest that kills a process named killmenow using Puppet.

Requirements:
Must use the exec Puppet resource.
Must use pkill.
