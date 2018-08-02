`DriveItem-after.yaml` is our YAML proposals for resource type `DriveItem-before.yaml`.

- Add `uid`, `name` and `YamlMime` to identify the template.
- Add `source` for edit button.
- Rename `intro` to `summary` to align with other reference language.
- `Heading` isn't required, template could use the yaml key to identify the header by mapping.
- Update `methods` sections from `intro` to `table`.
- `Operation` and `resource` are 2 types of different schema to be defined.
- To-do: fix cross reference to @uid format.
- Open questions:
  - How to understand `outro` in `properties`? Is there both `intro` and `outro`?
  - For the `section` which means `unknown` sections, currently we cannot handle since we need a standardized data structure, need Adam's suggestion.
  - Could Daron share the latest API doctor code? We checked the repo and found not yet checked in new code.