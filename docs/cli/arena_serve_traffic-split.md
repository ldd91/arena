## arena serve traffic-split

Adjust traffic routing dynamically for tfserving jobs

### Synopsis

Adjust traffic routing dynamically for tfserving jobs

```
arena serve traffic-split [flags]
```

### Options

```
  -h, --help                     help for traffic-split
      --name string              the serving name
  -v, --version-weight strings   set the version and weight,format is: version:weight, e.g. --version-weight version1:20 --version-weight version2:40
```

### Options inherited from parent commands

```
      --arena-namespace string   The namespace of arena system service, like tf-operator (default "arena-system")
      --config string            Path to a kube config. Only required if out-of-cluster
      --loglevel string          Set the logging level. One of: debug|info|warn|error (default "info")
  -n, --namespace string         the namespace of the job
      --pprof                    enable cpu profile
      --trace                    enable trace
```

### SEE ALSO

* [arena serve](arena_serve.md)	 - Serve a job.

###### Auto generated by spf13/cobra on 5-Mar-2021