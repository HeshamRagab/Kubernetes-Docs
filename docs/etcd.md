# ETCD
## What is etcd ?
A distributed reliable key-value `(JSON)` store,
  That is simple, secure, fast and reliable.

## how to install and run it from binary ?

```diff

! Download the binary compressed etcd
+ curl -L https://github.com/etcd-io/etcd/releases/download/v3.3.11/etcd-v3.3.11-linux-amd64.tar.gz -o etcd-v3.3.11-linux-amd64.tar.gz
  
! Extract The compressed tarball 
+ tar xvf etcd-v3.3.11-linux-amd64.tar.gz

! Enter the directory of extracted etcd
+ cd etcd-v3.3.11-linux-amd64/
  
! Run etcd binary
+ ./etcd

```