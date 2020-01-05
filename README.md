# Deploy Forge [wip]

### Config

```
{
  "all": {
    "hosts": {
      "my.hosts.domain": null
    }
  },
  "_meta": {
    "hosts": {
      "my.hosts.domain": {
        "forge": {
          "name": "brick-alley"
        },
        "ansible_ssh_private_key_file": "~/.ssh/id_ed25519"
      }
    }
  }
}
```
