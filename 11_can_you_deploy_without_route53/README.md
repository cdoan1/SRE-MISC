# Route53 and private DNS Zone

"For convenience, you can configure your IBM Cloud Private cluster with a private DNS Zone so that the worker nodes can talk to the master as well as discover other ICP components. In AWS, you can use Amazon Route53 to create the DNS zone."

* Our terraform template leverage Route53 to create the DNS zone for the private subnet on which all the nodes are connected. AWS supports customers defining their own private domain and DNS server. As long as all hosts can be resolved, it does not matter to ICP.

