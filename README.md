# Alpha Helix structural descriptors dataset
Dataset about alpha helix descriptors
These files contain the complete dataset of alpha helix descriptors. To read them, it's necessary to understand their format, as follow:
length: number of amino acids residues which compound the alpha helix
flag: indicate if the position is before (<), into (=) or after (>) the alpha helix
position: it was adopted 32 positions before and 32 after the alpha helix, and so, position indicates it
avg(descriptor): the average value in each position
std(descriptor): the standard deviation in each position
For example:
5,<,-32,53.4303472013109,47.7842183346976
means an alpha helix with 5 amino acids, position -32 before (<) the alpha helix, and the respective values of average and standard deviation in this position
