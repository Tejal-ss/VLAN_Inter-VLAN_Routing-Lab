# VLAN_Inter-VLAN_Routing-Lab|Cisco Packet Tracer
<br>
📌 Project overview <br>
This project is a revision of my networking fundamentals, where I configured VLANs and implemented Inter-VLAN Routing using the Router-on-a-Stick method in Cisco Packet Tracer.<br>
<br>
The goal was to segment the network into multiple VLANs and allow communication between them through routing.<br>
<br>
🎯 Objectives<br>
<br>
✅ Create VLANs for network segmentation<br>
✅ Assign switch ports to respective VLANs (Access ports) <br>
✅ Configure trunking (802.1Q) between Switch and Router <br>
✅ Configure Router subinterfaces for Inter-VLAN Routing <br>
✅ Verify connectivity using ping and show commands <br>
<br>
🧩 Network Topology <br>
<br>
PCs connected to Switch (Access ports) <br>
Switch connected to Router (Trunk link) <br>
Router performs routing between VLANs using subinterfaces <br>
<br>
✅ Result <br>
<br>
PCs from different VLANs can communicate successfully after routing configuration. <br>
<br>
🔍 Verification Commands <br>
Switch:<br>
show vlan brief<br>
show interfaces trunk<br>
Router:<br>
show ip interface brief<br>
<br>
🚀 Next Step<br>
<br>
Implement ACLs to restrict traffic between VLANs
