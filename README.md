# Metrics

https://github.com/kubernetes/cloud-provider-openstack/blob/master/docs/metrics.md

# Support cinder csi features :

https://github.com/kubernetes/cloud-provider-openstack/blob/master/docs/cinder-csi-plugin/using-cinder-csi-plugin.md#supported-features


# git subtree



``

`export version=v1.22.0`

## charts/cinder-csi-plugin -> helm/cloud-provider-openstack-app/charts/cinder-csi-plugin



```
git fetch upstream-copy
git checkout $version
git subtree split -P charts/cinder-csi-plugin/ -b temp-split-branch
git checkout master
git subtree merge --squash -P helm/cloud-provider-openstack-app/charts/cinder-csi-plugin temp-split-branch
git push
git branch -D temp-split-branch
```

## charts/openstack-cloud-controller-manager -> helm/cloud-provider-openstack-app/charts/openstack-cloud-controller-manager


```
git fetch upstream-copy
git checkout $version
git subtree split -P charts/openstack-cloud-controller-manager -b temp-split-branch
git checkout master
git subtree merge --squash -P helm/cloud-provider-openstack-app/charts/openstack-cloud-controller-manager temp-split-branch
git push
git branch -D temp-split-branch
```

