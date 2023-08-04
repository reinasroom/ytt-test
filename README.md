# ytt-test
ytt展開
```
ytt -f sample-pipeline.yml -f environment.lib.yml -f notification.lib.yml -f resources.lib.yml > sample-pipeline.yml
```

反映
```
fly -t tutorial set-pipeline -p sample-pipeline -c sample-pipeline.yml -l vars.yml -n
```