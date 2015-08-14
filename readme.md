
Check closest mirror "least latency"
https://launchpad.net/ubuntu/+archivemirrors

More help added from https://github.com/pablodav/linux-general-doc-wiki/wiki/apt-mirror

## main.yml considerations

Check file defaults/main.yml and:
    delete [arch=amd64,i386] if you want to sync all architectures!

It will install apache2 and link on html dir ubuntu, ppa and "mirrors dir"

## Keys section:

Check how to get more keys for keys dir:
https://github.com/pablodav/linux-general-doc-wiki/wiki/apt-mirror#keys

## Using these repos.

Consider this section:
https://github.com/pablodav/linux-general-doc-wiki/wiki/apt-mirror#uso-del-repositorio-offline

Note that you would need to remove some cache from already existing repos
