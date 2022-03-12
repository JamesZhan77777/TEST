# TEST
TEST
DOS Command

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 135" 
Dir=In Action=Block Protocol=TCP Localport=135

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 135" 
Dir=In Action=Block Protocol=UDP Localport=135

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 137" 
Dir=In Action=Block Protocol=TCP Localport=137

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 137" 
Dir=In Action=Block Protocol=UDP Localport=137

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 138" 
Dir=In Action=Block Protocol=TCP Localport=138

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 138" 
Dir=In Action=Block Protocol=UDP Localport=138

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 139" 
Dir=In Action=Block Protocol=TCP Localport=139

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 139" 
Dir=In Action=Block Protocol=UDP Localport=139

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 445" 
Dir=In Action=Block Protocol=TCP Localport=445

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 445" 
Dir=In Action=Block Protocol=UDP Localport=445

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 593" 
Dir=In Action=Block Protocol=TCP Localport=593

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 593" 
Dir=In Action=Block Protocol=UDP Localport=593

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 1025" 
Dir=In Action=Block Protocol=TCP Localport=1025

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 1025" 
Dir=In Action=Block Protocol=UDP Localport=1025

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 3389" 
Dir=In Action=Block Protocol=TCP Localport=3389

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 3389" 
Dir=In Action=Block Protocol=UDP Localport=3389

OR

Netsh Advfirewall Firewall Add Rule Name="Disable TCP Port 135,137,138,139,445,593,1025,3389" 
Dir=In Action=Block Protocol=TCP Localport=135,137,138,139,445,593,1025,3389

Netsh Advfirewall Firewall Add Rule Name="Disable UDP Port 135,137,138,139,445,593,1025,3389" 
Dir=In Action=Block Protocol=UDP Localport=135,137,138,139,445,593,1025,3389

PowerShell Command

New-NetFirewallRule -DisplayName "Disable TCP Port 135" 
-Direction Inbound -LocalPort 135 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 135" 
-Direction Inbound -LocalPort 135 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 137" 
-Direction Inbound -LocalPort 137 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 137" 
-Direction Inbound -LocalPort 137 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 138" 
-Direction Inbound -LocalPort 138 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 138" 
-Direction Inbound -LocalPort 138 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 139" 
-Direction Inbound -LocalPort 139 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 139" 
-Direction Inbound -LocalPort 139 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 445" 
-Direction Inbound -LocalPort 445 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 445" 
-Direction Inbound -LocalPort 445 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 593" 
-Direction Inbound -LocalPort 593 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 593" 
-Direction Inbound -LocalPort 593 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 1025" 
-Direction Inbound -LocalPort 1025 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 1025" 
-Direction Inbound -LocalPort 1025 -Protocol UDP -Action Block

New-NetFirewallRule -DisplayName "Disable TCP Port 3389" 
-Direction Inbound -LocalPort 3389 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 3389" 
-Direction Inbound -LocalPort 3389 -Protocol UDP -Action Block

OR

New-NetFirewallRule -DisplayName "Disable TCP Port 135,137,138,139,445,593,1025,3389" 
-Direction Inbound -LocalPort 135,137,138,139,445,593,1025,3389 -Protocol TCP -Action Block

New-NetFirewallRule -DisplayName "Disable UDP Port 135,137,138,139,445,593,1025,3389" 
-Direction Inbound -LocalPort 135,137,138,139,445,593,1025,3389 -Protocol UDP -Action Block
