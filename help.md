tanzu apps workload create demo-app -n dev-space \
--local-path /home/berinle/workspace/demo-app \
--source-image tanzu01.azurecr.io/tap-wkld/demo-app-source \
--type web \
--label apps.tanzu.vmware.com/has-tests=true \
--label app.kubernetes.io/part-of=demo-app \
--yes