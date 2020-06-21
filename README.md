# Puppet
Practising Puppet.

You can run  a puppet file by using 'sudo puppet apply -v [filename.pp]' # no need to use [] used as a example.


* IaC goes hand in hand with continuous delivery.
* This means no node is irreplaceable and configuration is automated. 
* When a configuration or process doesn't depend on a human remembering to follow all the necessary steps, the result will always be the same.
* Because automation breeds consistency, when we know a particular process that has been automated works, we can count on it working every time as long as everything remains the same.
* A scalable system is a flexible system that can handle extra tasks or integrate extra resources easily.
* Chef is a configuration management system that treats configuration as code.
* Ansible is an open source IT Configuration Management, Deployment & Orchestration tool which aims to provide a wide variety of automation challenges with huge productivity gains.
* CFEngine is an open-source configuration management program that offers automated configuration and maintenance of large-scale computing networks, including centralized cloud, desktop, consumer and industrial application control, embedded networked applications, handheld smartphones, and tablet computers.
* We can write automation scripts ourselves or we can use some sort of configuration management software to make our network scalable by pushing changes from a control server.

* The Portage package manager used by Gentoo Linux is the provider called by the Puppet agent. 
* Grouping a collection of related resources into a single class simplifies configuration management by, for one example, allowing us to apply a single class to each host rather than having to specify every resource for each host separately and possibly missing some.
* Puppet assigns providers according to predefined rules for the resource type and data collected from the system such as the family of the underlying operating system.
* Puppet has many useful attributes. "Replace" set to True tells Puppet to replace files or symlinks that already exist on the local system but whose content doesn’t match what the source or content attribute specifies.

* In a declarative language, it's important to correctly define the end state we want to be in, without explicitly programming steps for how to achieve that state.
* All variable names are preceded by a dollar sign in Puppet's DSL.
* Stateless means there is no record of previous interactions, and each interaction request has to be handled based entirely on information that comes with it.
* By checking to see if a resource requires modification first, we can avoid wasting precious time.
* We specify the package contents inside the curly braces, placed after the package title.

* The catalog is the list of rules for each individual system generated once the server has evaluated all variables, conditionals, and functionals in the manifest and then compared them with facts for each system.
* New functions added after installing a new module can be found in the lib folder in the directory of the new module.
* Manifest files for Puppet will end in the extension .pp.
* Metadata is data about data, and in this case, often takes the form of installation and compatibility information.
* When defining resource types, we write them in lowercase, then capitalize them when referring to them from another resource attribute.
