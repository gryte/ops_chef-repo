# ops_chef-repo
Operations-based items for Chef Servers such as environment and role files

# directory structure

```bash
<chef server>
|  --> <organization>
|    --> <environment>
```

# commands

*create file from existing environment*

```bash
knife environment show <environment> -F json >> <path>/<environment>.json
```

*create/update environment from file*

```bash
knife environment from file <path>/<environment>.json
```

# citations

- docs.chef.io - [knife environment](https://docs.chef.io/knife_environment.html#from-file)
