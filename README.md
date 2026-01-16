As a beginner network engineer trainee, I designed this self-initiated project to model a global enterprise network connecting branches in India, USA, and Russia. Each branch includes its own servers, manager rooms, and departments while operating as part of a single organization. The network supports seamless communication, data access, and daily business operations across all locations.

🌟The networking Devices Used to Built🌟

🎯 Cisco ISR 2911 (ISP routers), ISR 4331 (enterprise routers)

🎯 multilayer switches 3560-24PS

🎯 Layer 2 switches 2950-24PS

🎯 End Devices: Servers, PCs, laptops, printers, and IP phones.

🌟Routing and Redundancy🌟

EIGRP is used as the primary routing protocol for WAN and intra-network communication, providing fast convergence and optimized routes.

HSRP is configured at key points to ensure gateway redundancy and high availability.

🌟Switching and Segmentation🌟

VLANs divide each branch network into departments like IT, Software, and Marketing,

Inter-VLAN routing enabling communication between them.

EtherChannel with PAgP bundles multiple links between core switches for load balancing and higher bandwidth.

🌟IP Management🌟

The 203.0.113.0/29 network is subnetted to efficiently allocate IPs across branches and departments.

Private IP addressing secures internal communication, while DHCP simplifies dynamic IP assignment for end devices.

This architecture demonstrates a scalable, multi-branch enterprise network with departmental segmentation, centralized services, and reliable connectivity for workflow efficiency across international locations.

🎒This design may have some limitations, as it was created purely from my understanding as a beginner network engineer trainee without real-time industry experience.📚
