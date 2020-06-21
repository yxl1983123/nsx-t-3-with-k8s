# nsx-t-3-with-k8s
cluster = 

apiserver_host_ip =

apiserver_host_port = 6443

nsx_api_user = admin

nsx_api_password = VMware1!VMware1!

nsx_api_managers = 

insecure = True

overlay_tz = b9b8a3ed-6da6-4010-b57d-cf77431a1c77

container_ip_blocks = k8s-nat-pod-ipb

no_snat_ip_blocks = k8s-no-nat-ipb

external_ip_blocks = k8s-egress-ipb

top_tier_router = k8s-t1（设置T0的UUID)

external_ip_pools_lb  = k8s-ingress-ipp

external_ip_pools = k8s-egress-ipp

single_tier_topology = True

edge_cluster = 165b48b1-e822-4413-b07f-122da094efa2

enable_ncp_event = True

ovs_uplink_port = ens224
