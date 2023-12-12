# 5GNR-mptcp-simulation-setup
Git repo for simulating MPTCP-enabled 5G NR devices with dual gNB connections.

## MPTUNE, A Priority-based MPTCP Scheduler for 5G and Beyond Heterogeneous Links

Modern cellular devices often have dual interfaces
for providing high-speed data transfer. This dual-interface design
enhances versatility and user convenience. Dual interface tech-
nology allows 5G NR devices to connect to the 5G core using two
separate base stations. One base station operates in the mmWave
frequency range, and the other operates in the sub-6 GHz
frequency range. However, millimeter-wave (mmWave) signals
face challenges in terms of limited penetration through obstacles,
such as buildings, and susceptibility to atmospheric absorption,
leading to reduced coverage and potential signal degradation
in adverse weather conditions. On the other hand, sub-6 GHz
waves offer better penetration through obstacles and a broader
scope compared to mmWave, making them suitable for providing
reliable and expansive wireless connectivity in urban and indoor
environments. Both mmWave and sub-6 GHz frequencies have
distinct advantages and limitations; mmWave provides high data
rates but has limited coverage, while sub-6 GHz offers a broader
range but at lower data rates. However, in a heavy data transfer
scenario, frequent loss in the mmWave link while transmitting
packets can lead to packet drops (wireless medium), reducing the
congestion window size and increasing the flow completion time.
To mitigate this, we propose to use analytical hierarchy process
(AHP) and grey rational analysis (GRA) based priority allocation
mechanism to schedule packets on the most reliable link, thereby
reducing the packet drops and flow completion time.