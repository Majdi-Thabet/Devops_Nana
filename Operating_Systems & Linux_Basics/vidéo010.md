## Title : Shell Scripting part 2

**Variables**
```
file_name = config.yaml
config_files = $(ls config)  // Liste tous les fichiers présents dans le répertoire config and stocke Le résultat de cette commande  dans la variable config_files.
echo "using file $file_name to configure something"
echo "here are all configuration files: $config_files"
``` 

return to teminal and tape : ./setup.sh to run your file 

after that tape : vim setup.sh to rechange the content of your file.

---

```
#!/bin/bash

echo "Setup and configure server"

file_name=config.yaml

if [ -d "config" ]
then
    echo "Reading config directory contents"
    config_files=$(find config -type f)
else
    echo "Config directory not found. Creating one..."
    mkdir config
    config_files=""
fi

echo "Using file $file_name to configure something"
```

---
