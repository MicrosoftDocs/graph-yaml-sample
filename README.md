`DriveItem-docs-update.yaml` is YAML proposals for resource type `DriveItem.yaml`.

- Add `uid`, `name` and `YamlMime` to identify the YAML.
  - `GraphOperation` and `GraphResource` are 2 types of YamlMime to be defined in YAML, docs team need it to identify which template we use.
- Add `source_url` for edit button.
- `Heading` isn't required, template could use the yaml key to identify the header by mapping.
- Update `methods` sections from `intro` to `table`.
- Open questions:
  - How to understand `outro` in `properties`? Is there both `intro` and `outro`?
    - Yes, `intro` and `outro` are relative。
  - For the `section` which means `unknown` sections, currently we cannot handle since we need a standardized data structure, need Adam's suggestion.
    - By Daron's suggestion, we could use `outro` to append.
  - Could Daron share the latest API doctor code? We checked the repo and found not yet checked in new code.
    - Daron could share with us in specific branch, withouting adding third party dependency.
- To-do: fix cross reference to @uid format.
