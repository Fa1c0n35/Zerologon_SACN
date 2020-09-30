 
# Zerologon (CVE-2020-1472)
This script is made for bulk checking your domain controllers for the Zerologon vulnerability.

# Arguments
  --ip&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ip address for check on CVE-2020-1472  
  --file&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;File path with IP addresses  
  --threads&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Number of threads  
  --name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NetBIOS computer name, use with --ip flag  

# Exampels
  python3 check_cve-2020-1472.py ---ip &lt;IP>  
  python3 check_cve-2020-1472.py ---ip &lt;IP> ---name &lt;NetBIOS computer name>  
  python3 check_cve-2020-1472.py ---file &lt;Path to file with ip addresses>  

# Note
  Zerologon vulnerabilities are dangerous for your domain controller, dont use the exploit on production servers.  

![Альтернативный текст](https://github.com/WiIs0n/Zerologon_CVE-2020-1472/blob/master/img/scrin.png)
