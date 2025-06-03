# ARCHIVED
This action has been archived and will no longer be maintained.
Please create your own fork.

# itchio-butler-upload
Simple Github Action using shell scripts to upload game to itch.io using butler.  
If you are facing problems with the action or this README feels not complete, pull requests are welcome or open an issue.

## Table of contents
- [itchio-butler-upload](#itchio-butler-upload)
  - [Table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Parameters](#parameters)
  - [Working examples](#working-examples)
  - [License](#license)

## Requirements
 - Godot Project

## Parameters
| key | required | default | description |
| ----|----------|---------|-------------|
| working-directory | false | . | Path to project.godot file |
| api-key | true | / | Generate a key here https://itch.io/user/settings/api-keys |
| user | true | / | itch.io user name |
| game | true | / | itch.io game name |
| channel | true | / | itch.io channel name. More infos at https://itch.io/docs/butler/pushing.html#channel-names |


## Working examples
You an find a working examples here:  
https://github.com/dulvui/ball2box/blob/main/.github/workflows/upload-itchio.yml

## License
This software is licensed under the [MIT license](LICENSE).
