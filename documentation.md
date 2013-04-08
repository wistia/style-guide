# Documenting Software Projects

This document covers what documentation should be maintained for all Wistia
projects, regardless of the language or framework.

## README.md

All project-level documentation should be kept in a README.md file, written in
markdown. This makes the document visible on the Github project page, and
prevents people from needing to sift through several files to find a particular
piece of information.

The README should contain the sections listed below.

### Overview

The overview is a statement of what the project does and, if not obvious, a
statement about why it is built the way it's built. For example, when Alyce
builds the blog, she might add a statement about why we are building a Rails app
for it instead of using Wordpress as is more typical.

### 10,000-foot View

The 10,000-foot view is a language-agnostic explanation of how your project
works. Imagine you are the architect of the project, and you need to explain
your vision of it to the programmer who is going to implement it. Omit
framework-specific instructions. This section will be short in apps that rely on
framework conventions, and long in apps that buck trends or do not use
frameworks.

### Development

The development section contains *everything* a developer needs to know to run
the project locally. This includes:

* libraries that need to be installed
* environment variables that need to be set
* YAML files that need to be constructed
* rake tasks that need to be run
* console commands that need to be executed

This section is the most important and unfortunately the easiest to fall out of
date.

### Deployment

This section documents how your application is deployed.

### References

List any ancillary readings or tutorials - things that should be kept in mind
but whose scope is beyond the README. For example, the Bakery might contain a
link to the ffmpeg docs.

