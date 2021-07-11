# occ_helm
## For Debug
helm install --dry-run --debug shop ./occ_helm
## For deoloyment
helm install shop ./occ_helm
helm install payment ./occ_helm
helm install cart ./occ_helm
helm install checkout ./occ_helm
## For uninstall
helm uninstall shop 
