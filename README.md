# VirusTotal Scan Script

This script allows you to perform a scan on a file or a MD5 hash using the VirusTotal API. It returns the scan results showing if the file or hash is malicious or not.

## Requirements

- Bash
- curl
- jq
- A VirusTotal API key

## Installation

1. Clone the repository to your local machine:

     git clone https://github.com/cfpandrade/virus-total-scan.git

2. Navigate to the project directory:

     cd virus-total-scan

3. Edit the script and replace the `VIRUSTOTAL_API_KEY` variable with your VirusTotal API key.

4. Make the script executable:

     chmod +x virustotal

5. Move the script to the `/usr/bin` directory:

     sudo mv virustotal /usr/bin/

## Usage

  To scan a file, run:

     virustotal /path/to/file

  To scan a MD5 hash, run:

     virustotal <MD5 hash>

## License

This project is licensed under the MIT License - see the LICENSE file for details.


