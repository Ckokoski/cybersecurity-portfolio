# Automated Attack Surface Management (ASM) Reconnaissance Script

This project is a simple Bash script that automates the initial phase of an ASM engagement. It takes a domain name and uses a chain of popular OSINT tools to discover and perform initial scanning on its subdomains.

## What It Does

1.  **Finds Subdomains:** Uses `Amass` to perform deep subdomain enumeration.
2.  **Identifies Live Hosts:** Pipes the subdomains into `httpx` to find which ones are active web servers.
3.  **Performs Basic Scans:** Uses `Nuclei` with its default templates to scan the live hosts for known vulnerabilities and misconfigurations.

## How to Use It

1.  Clone the repository.
2.  Make the script executable: `chmod +x asm_recon.sh`
3.  Run the script with a target domain: `./asm_recon.sh example.com`

## Example in Action

Here is a screenshot of the script running against Netflix's public infrastructure:

![Netflix ASM Results](images/Netflix%20ASM.png)
