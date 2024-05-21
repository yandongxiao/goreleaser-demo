最终结论：可以使用 gh 来创建 release && 上传 artifacts, 使用 git-chglog 来自动化地生成 relase Note.

GoReleaser is a release automation tool for Go projects.
Its goal is to simplify the build, release and publish steps while providing variant customization options for all steps.

GoReleaser is built for CI tools, you only need to download and execute it in your build script. Of course, you can also install it locally if you wish.

You can customize your entire release process through a single .goreleaser.yaml file.

Check out our website for more information, examples and documentation: https://goreleaser.com

Usage:
  goreleaser [command]

Available Commands:
  build             Builds the current project
  check             Checks if configuration is valid
  completion        Generate the autocompletion script for the specified shell
  healthcheck       Checks if needed tools are installed
  help              Help about any command
  init              Generates a .goreleaser.yaml file
  jsonschema        outputs goreleaser's JSON schema
  release           Releases the current project

Flags:
      --debug     Enable verbose mode
  -h, --help      help for goreleaser
      --verbose   Enable verbose mode
  -v, --version   version for goreleaser

Use "goreleaser [command] --help" for more information about a command.
