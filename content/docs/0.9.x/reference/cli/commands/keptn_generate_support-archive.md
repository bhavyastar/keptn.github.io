---
date: "2021-06-16T14:50:20+02:00"
title: "keptn generate support-archive"
slug: keptn_generate_support-archive
---
## keptn generate support-archive

Generates a support archive containing all logs

### Synopsis

Generates a support archive containing information of the Keptn installation and logs from the services

```
keptn generate support-archive [flags]
```

### Examples

```
keptn generate support-archive
keptn generate support-archive --dir=/some/directory
```

### Options

```
      --dir string   directory where the docs should be written to (default "./support-archive")
```

### Options inherited from parent commands

```
  -h, --help               help
      --mock               Disables communication to a Keptn endpoint
  -n, --namespace string   Specify the namespace where Keptn should be installed, used and uninstalled in (default "keptn")
  -q, --quiet              Suppresses debug and info messages
  -v, --verbose            Enables verbose logging to print debug messages
  -y, --yes                Assume yes for all user prompts
```

### SEE ALSO

* [keptn generate](../keptn_generate/)	 - Generates the markdown CLI documentation or a support archive

###### Auto generated by spf13/cobra on 16-Jun-2021