# August 07, 2024 Release Notes - 2.0.3
## Updates
1. This Orchestrator repository has been moved to a new OCI Landing Zones GitHug organization and renamed. It's new location is now  https://github.com/oci-landing-zones/terraform-oci-modules-orchestrator
2. The following supporting Landing Zone repositories have also been moved and renamed:

Repository       | Old Location                                                                      | New Location                                                            
-----------------|-----------------------------------------------------------------------------------|-------------------------------------------------------------------------
Networking       | https://github.com/oracle-quickstart/terraform-oci-cis-landing-zone-networking    | https://github.com/oci-landing-zones/terraform-oci-modules-networking   
Security         | https://github.com/oracle-quickstart/terraform-oci-cis-landing-zone-security      | https://github.com/oci-landing-zones/terraform-oci-modules-security     
Observability    | https://github.com/oracle-quickstart/terraform-oci-cis-landing-zone-observability | https://github.com/oci-landing-zones/terraform-oci-modules-observability
Governance       | https://github.com/oracle-quickstart/terraform-oci-cis-landing-zone-governance    | https://github.com/oci-landing-zones/terraform-oci-modules-governance   
Secure Workloads | https://github.com/oracle-quickstart/terraform-oci-secure-workloads               | https://github.com/oci-landing-zones/terraform-oci-modules-workloads    


# July 26, 2024 Release Notes - 2.0.2
## Updates    
1. Aligned README.md structure to Oracle's GitHub organizations requirements.


# May 24, 2024 Release Notes - 2.0.1
### Updates
1. Now supporting saving outputs when configuration files are obtained from plain public URLs. The outputs can be saved to private Git Hub repositories or private OCI buckets. The UI has been re-organized.


# April 18, 2024 Release Notes - 2.0.0
### New
1. New OCI Landing Zones Orchestrator version, supporting remote JSON, YAML documents or HCL objects as inputs. The documents can be pulled from private Git Hub repositories, private OCI buckets or any reachable plain URLs.