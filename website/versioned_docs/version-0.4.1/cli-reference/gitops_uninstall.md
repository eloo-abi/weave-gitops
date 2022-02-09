## gitops uninstall

Uninstall GitOps

### Synopsis

The uninstall command removes GitOps components from the cluster.

```
gitops uninstall [flags]
```

### Examples

```
  # Uninstall GitOps from the wego-system namespace
  gitops uninstall
```

### Options

```
      --dry-run   Outputs all the manifests that would be uninstalled
  -h, --help      help for uninstall
```

### Options inherited from parent commands

```
  -e, --endpoint string    The Weave GitOps Enterprise HTTP API endpoint
      --namespace string   Weave GitOps runtime namespace (default "wego-system")
  -v, --verbose            Enable verbose output
```

### SEE ALSO

* [gitops](gitops.md)	 - Weave GitOps

###### Auto generated by spf13/cobra on 3-Nov-2021