# The Containerized Belenios

This recipe supports the following belenios versions :
* `1.13`

* In (a shell session and in) an empty directory, run :

```bash
export BELENIOS_OCI_LIBRARY=git@github.com:pegasus-io/belenios-containers.git

git clone ${BELENIOS_OCI_LIBRARY} .

docker build -t $(whoami)/belenios:0.0.1 .
```
