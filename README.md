#NGINX Openshift Image

## Running on OpenShift

`oc new-app https://github.com/bobbydeveaux/nginx-openshift --name nginx-example`

`oc expose svc/nginx-example`

## Notes

Based on image from @torstenwalter + additions by @bobbydeveaux