# gcp-sgw-terraform
A set of terraform modules for deploying Google Cloud Secure Gateway with a new GCP project &amp; VPC network and an e2-micro vm with nginx + docker + gethomepage.dev  &amp; leveraging Google Cloud DNS for private hostname resolution

# GoChrome Secure Gateway Demo - Homepage Dashboard

**Project**: `gochrome-496112`  
**Hostname**: `homepage.gochro.me`  
**Region/Zone**: europe-west2 / europe-west2-a

---

## Step 1: Terraform Deployment

1. Place these files in your directory:
   - `main.tf`, `variables.tf`, `network.tf`, `compute.tf`, `dns.tf`, `firewall.tf`, `storage.tf`, `outputs.tf`
   - `pac.js` (PAC file)

2. Run:

```bash
terraform init
terraform apply
