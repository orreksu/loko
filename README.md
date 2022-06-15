# loko - task scripting tool

- No YAML files!

### Easy to migrate
- `loko --migrate` will create a new Lokofile form your Makefile or Justfile

### Smart Targets
#### Help
`loko --help`

#### Subtargets
```
build:
  vm:
    bazel build //vm/...
  all:
    bazel build //...
```

#### Silent Targets
`_local-build: ...`


### Integratable
- Loko is already part of your ecosystem, we have close support of VSCode and IntelliJ
- Use [VSCode tasks](https://code.visualstudio.com/docs/editor/tasks)
- Autogenerate things for VSCode tasks

### Pretty
#### Pretty Errors

### Functions
#### Provided
- os()
- platform()
- distro()
- error()

### Plugin System
In progress ...

### Alternatives
- [make](https://www.gnu.org/software/make/)
- [just](https://github.com/casey/just)
- [task](https://github.com/go-task/task)
- [lets](https://lets-cli.org/docs/basic_usage)
- [robo](https://github.com/consolidation/robo)
- [doit](https://github.com/pydoit/doit)
- [gulp](https://github.com/gulpjs/gulp)
- [grunt](https://github.com/gruntjs/grunt)
- [jake](https://github.com/jakejs/jake)
- [rake](https://github.com/ruby/rake)
- [run](https://github.com/DannyBen/runfile)
- [universal run](https://github.com/brickpop/runner-cli)


### Makefile Cool Things
- [List targets](https://stackoverflow.com/questions/4219255/how-do-you-get-the-list-of-targets-in-a-makefile)