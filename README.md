# Cloudpak
Cloudpak installation
Get a login account for ibmcloud.com with ibm email.
request a paid account so that it goes to the manager (Diether) to be approved.
Once approved install "Red Hat Openshift Cluster" from the Catalog with following configuration:
Location: for ease use Single Zone, Select Geography(preferably select nearest to you), Metro and Worker Zone (for lower cost selct one zone only), for Flavor use 8vCPUs 32GB RAM, for worker nodes use 2 nodes.
Create Cluster
once cluster is installed go to catalog and select "Cloud Paks" on left navigation pane.
click on Cloud Pak for Application
On the Create link on the top:
For Red Hat Openshift cluser select the one created above
Enter a project name
Click on Run Script button at the bottom
Once the Preinstaaltion script runms successfully check the license agreement on the right pane.
Click on install
This will install the cloud Pak for APplication on the Red Hat openshift Cluster.
