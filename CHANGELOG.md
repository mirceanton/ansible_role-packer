# Changelog

## v3.0.2

* Specify exact versions for dependencies.

## v3.0.1

* Migrate from `incude_role` to `import_role` to fix variables not getting passed through.

## v3.0.0

**💣 Breaking changes**:

* Changed from configuring the apt repos to downloading precompiled binaries for multi-arch support. This means that there are now required variables to be set!

## v2.0.0

**💣 Breaking changes**:

* Changed variable names so that all of them are prefixed by `packer_`

**🔧 Workflow changes**:

* Migrated grom `geerlingguy/` images to custom `antonmircea/` images
* Added testing support for more platforms

## v1.0.0

* Initial release of the `mirceanton.packer` role 🚀
