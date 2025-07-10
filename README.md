# 36162

## Current behavior

The renovate run *adds* a `bin/.jq-1.7.1.pkg` file (exact version may vary over time, it should be whatever the latest jq version is).

## Expected behavior

The renovate run *renames* the existing `bin/.jq-1.5.pkg` file to `bin/.jq-1.7.1.pkg` (or otherwise does an add/delete that is equivalent).

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/36162
