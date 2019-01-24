# EEG-brain-network-study-during-resting-states
This project focuses on understanding brain signal and connectivity patterns related to the eye states

Abstract:
This project focuses on understanding brain signal and connectivity patterns related
to the eye states. More specifically, we analyzed brain Signals recorded by EEG for two
different Eye states i.e. Eye open(EO) and Eye close(EC) respectively. We analyzed the
64-channel EEG signals from a single subject(S004) with eyes-open and eyes-closed
baseline conditions. We did 4 types of analysis namely connectivity graphs, graph theory
indices, motif analysis and community detection. More on this in their respective sections.
At each stage of analysis, we emphasized arising differences between EO and EC states,
accordingly concluded main identifiers of each state. To do this we focused on
understanding the difference between the brain connectivity estimated with the MVAR
estimation approaches like Partial directed coherence (PDC) and Direct Transfer Function
(DTF) (the second one tends to give connectivity value little bit bigger than the first one).
We also performed motif analysis using the tool mfinder and considering 3-node and 4-
node motif configuration. We were able to obtain motifs and anti-motifs for the
configuration with 3 and 4 nodes. We also to carried out specific analysis about
information about the connection involved in a specific community detection configuration
(modularity-based vs information theory-based approaches). Finally, after our
observations while computing the community detection, we highlighted the weaknesses of
Louvain’s’ algorithm in recognizing small communities compared to Info map



