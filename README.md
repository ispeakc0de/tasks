# tasks

- [x] openebs pool container failure with mysql - 22- 23 mins
- [x] openebs pool container failure with busybox - 27-28 mins
- [x] openebs pool pod failure with busybox - 11 mins
- [x] openebs pool pod failure with mysql - 11 mins
- [x] openebs target pod failure cstor/mysql - 10 mins
- [x] openebs target pod failure jiva/busybox - 10 mins
- [ ] openebs target pod failure containerd
- [x] openebs target container failure cstor/myql - 15 mins
- [x] openebs target container failure jiva/busybox - 11 mins
- [ ] openebs target container failure containerd
- [ ] openebs nw delay failure jiva
- [ ] openebs nw delay failure cstor
- [ ] openebs nw loss failure jiva
- [ ] openebs nw loss failure cstor

-disk fill container not found

fatal: [127.0.0.1]: FAILED! => {"changed": true, "cmd": "kubectl exec -it disk-fill-7b8zs -n shubham -- sh -c \"cd /diskfill && cd 1dc0135fbad688a708aacab9f45bb4bf9edbcfde2cc50ec542a7bdab7145b4f1 && du -k |tail -n1 | awk '{print $1}'\"", "delta": "0:00:01.063373", "end": "2019-12-21 09:43:56.408357", "msg": "non-zero return code", "rc": 1, "start": "2019-12-21 09:43:55.344984", "stderr": "Unable to use a TTY - input is not a terminal or the right kind of file\nerror: unable to upgrade connection: container not found (\"disk-fill\")", "stderr_lines": ["Unable to use a TTY - input is not a terminal or the right kind of file", "error: unable to upgrade connection: container not found (\"disk-fill\")"], "stdout": "", "stdout_lines": []}

- cpu hog - "platform any"
