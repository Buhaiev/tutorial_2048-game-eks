# Notes made during project implementation
**During every tutorial project, I make notes on what differed from the tutorial set. These notes are stored here.**

1) The full EKS creation process looks differently now. VPC security group is created/selected outside of the EKS creation. There is also no prompt to set CNI, CoreDNS or kube-proxy versions, only the Kubernetes one.
2) The names of IAM role policy sets have changed slightly. Also, cluster roles have additional default policies.
3) 