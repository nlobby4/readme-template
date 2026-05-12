# Architecture

This document describes the high-level architecture of the project. For a more
detailed discussion on the design and implementation, see the
[reference article](https://matklad.github.io/2021/02/06/ARCHITECTURE.md.html).

## File Structure

The project is organized into the following directories:

- `/`: Contains tooling and configuration files
- `meta/`: Contains meta-level assets like images, diagrams, and other media
- `project/`: Contains project relevant files

## Git Ignore Rules

The root of the repository contains a `.gitignore` that is based on a whitelist
pattern, this avoids auto-generated files from being accidentally committed to
the repository unless explicitly added.

The `project/` directory can contain `.gitignore` files that are based on a
classic blacklist pattern, this allows the use of a standard ignore templates
for various languages and tools. This is separates concerns in monorepos with
multiple projects.

<!-- TODO: Add a high-level overview of the architecture -->
