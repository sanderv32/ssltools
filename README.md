## SSL Tools

| Tool     | Description     |
| :------------- | :------------- |
| ssl-pem-show | Shows all certificates in a combined PEM file |
| ssl-combine | Combine cert/intermediates/CA into one PEM file in the right order|

In both tools use --help to show all the options which are available.

### History
| Version | Description |
|:-|:-|
| 1.0 | First commit which is ready for production |
| 1.1 | Fixed the issue that the root CA was added multiple times.<br>Added -pfx switch to support Windows machines|
