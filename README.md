# windows_netfilter_socks5_proxy
This program utilizes Netfilter SDK to force a specific program use a SOCKS5 proxy.

# NOTE
1. **I do NOT own this program nor the drivers**.
2. This is shared from a private group. I do NOT have the source code, therefore I cannot gurantee the safety of using this closed-source software.
2. This should NOT be used for commercial purposes.

# Advantages
1. Light-weight
2. Does not conflict with LSP proxying softwares.

# Usage
1. Install the Netfilter network hooking driver, which is provided in the repo. Follow this guide: https://netfiltersdk.com/help/nfsdk2/nfapi_installation.htm
2. `redirector.exe -r proxy_ip_addr:proxy_port [-p "<Process 1>, <Process 2>..."] [-username <proxy username>] [-password <proxy password>]`
