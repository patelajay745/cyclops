# cyctl update module
## cyctl update module

updates module values; takes module name as an argument with flags --key and --value

### Synopsis

updates module values; takes module name as an argument with flags --key and --value

```
cyctl update module [flags]
```

### Examples

```
# updates module values; takes module name as an argument with flags --key and --value
# to update replicas for a module named test 
cyctl update module test --key="scaling.replicas" --value=3
	
```

### Options

```
  -h, --help           help for module
  -k, --key string     the field to update
  -v, --value string   field value
```

### SEE ALSO

* [cyctl update](cyctl_update.md)	 - updates cyclops resources (currently supports only Modules)

###### Auto generated by spf13/cobra on 29-Jul-2024
