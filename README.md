# FC3er | CVE-2022-0591 - Formcraft3
Automatic Mass Tool for checking vulnerability in CVE-2022-0591 - Formcraft3 < 3.8.28 - Unauthenticated SSRF<br>Using GNU Parallel. You must have parallel for running this tool.<br>
- <b>If you found error like "$'\r': command not found" just do "dos2unix fc3er.sh"</b>
# Install Parallel
- Linux : <br>
<b>command</b> <br># <code>apt-get install parallel -y</code><br>
- Windows : <br>
You can install WSL (windows subsystem linux) then do install like linux<br>if you want use windows, install <a href="https://git-scm.com/download/win">GitBash</a><br>
<b>command</b> <br># <code>curl pi.dk/3/ > install.sh </code><br># <code>sha1sum install.sh | grep 12345678 </code><br># <code>md5sum install.sh </code><br># <code>sha512sum install.sh </code><br># <code>bash install.sh</code><br>
# Install JQ 
- Linux : <br>
<b>command</b> <br># <code>apt-get install jq -y</code><br>
- Windows : <br>
For WSL just do install like linux, For gitbash you can do this command<br>
<b>command</b> <br># <code>curl -L -o C:/Program\ Files/Git/usr/bin/jq.exe https://github.com/stedolan/jq/releases/latest/download/jq-win64.exe</code>
# How To Use
- [#] <code>bash fc3er.sh yourlist.txt thread</code>
# Reference
- https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-0591
- https://wpscan.com/vulnerability/b5303e63-d640-4178-9237-d0f524b13d47
- https://github.com/projectdiscovery/nuclei-templates/issues/4260
