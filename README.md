# potential_norms
This research was presented at the National Council of Teachers of Mathematics Research Conference in 2022. The research was conducted by Anthony Matranga at California State University San Marcos and Jason Silverman at Drexel University. The presentation slides can be accessed at the following link:
https://csusm-my.sharepoint.com/:p:/g/personal/amatranga_csusm_edu/Ee8unAI6DkxNvXvVPjcfn4QBfDCTZ7Wd4MvP35JBbUQb8A?e=O2pGYs

Data description:
The data for this project includes interactional data (edges) and participant/discourse feature data (nodes). The edges are associations between participants and occasions of using a distinct discourse feature on a discussion forum. The nodes are participants (mode 1) and discourse features (mode 2).
The raw data imported into r for this research had the following structure.
edge data:
4 columns: "Participant id", "Particpant psuedonymn", "Topic", "Topic id"
node data:
7 columns: "Participant/topic id", "Node description"" (participant pseudonymn/discourse feature), "topic_number","Node Type"(core/periphery/potential norm), "topic_time" (discussion forum),"position_lab" (coded for igraph), "mode"

Using this code:
Please note that you will likely have to update aspects of this code according to your data set.




