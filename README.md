# varnish-helper

The ultimate utility for troubleshooting ["Backend Fetch Failed"](https://www.getpagespeed.com/troubleshooting/varnish-backend-fetch-failed) in Varnish faster.
Makes your life easier by telling you what's wrong with the backend, or whether Varnish itself needs to be reconfigured.

This utility allows troubleshooting by looking at existing log in memory, e.g. `varnishlog -d`.
Additionally, you can hunt down log using specific vxid.

# NOT FUNCTIONAL. WORK IN PROGRESS

```console
#$ varnish-helper
#$ # reports found problem
```

```console
varnish-helper why <VXID from browser error message>
#$ If problem is known, report it, otherwise dump found varnishlog for VXID
```