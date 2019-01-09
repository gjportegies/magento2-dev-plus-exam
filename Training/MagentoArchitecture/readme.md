# Magento Architecture

## Covered Questions

TBD

## Questions to Cover

### 1.1 Determine advanced uses of the Magento configuration system

- Understand how to create a custom config file. Demonstrate an understanding of the Magento Configuration files
framework
- Understand how to create a custom config file with validation and a unique node that is overridden on merging
- Understand how to create a config file with a remote schema

### 1.2 Demonstrate an ability to design complex customizations using plugins and di.xml

- Plugins sort order, plugin on plugin scenario, plugin debugging techniques. Demonstrate an understanding of
virtual types, shared objects, object instantiation process, proxies, factories
- How does an around plugin modify the plugin execution order?
- How do you debug a plugin that is not executed?
- Demonstrate Plugin on Plugin examples
- Which classes are instantiated outside of the ObjectManager so they cannot be customizing using di.xml?
- Demonstrate a use case for a virtual type (different instances of a class with a different set of arguments)

### 1.3 Demonstrate understanding of Magento events processing

- Demonstrate an understanding of the events processing flow. Influence of Staging on the event processing
- What is a modification of the event processing mechanism introduced by the staging module?

### 1.4 Demonstrate an ability to use the Magento command-line interface

- Create a new CLI command, emulate different areas within it
- Create a new CLI-command, configure it in di.xml, add optional/required options/keys
- Environment specification using Area class
- Environment emulation for a section of code
