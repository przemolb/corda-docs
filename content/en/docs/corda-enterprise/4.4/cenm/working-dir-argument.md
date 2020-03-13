---
aliases:
- /releases/4.4/cenm/working-dir-argument.html
date: '2020-01-08T09:59:25Z'
menu: []
tags:
- working
- dir
- argument
title: working-dir-argument
---

Optional parameter:

```bash
--working-directory=<DIR>
```

This will set the working directory to the specified folder. The service will look for files in that folder. This means
certificates, config files etc. should be under the working directory.
If not specified it will default to the current working directory (the directory from which the service has been started).
