[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# redshift-blocklet

A simple script for redshift integration in i3blocks. It indicates whether or
not redshift is currently running and a click on the blocklet
activates/deactivates redshift.

## dependencies

- redshift
- `Material Design Icons` Font (or change the icon in the script accordingly)

## i3-blocks config

```
[redshift]
command=~/.config/i3blocks/redshift_status
interval=1
```

