# dxydata
dataset for the project dxy

We prepare two datasets to form the graph to be analyzed. The first dataset with the filename ”nodes.csv”, 
the first column of which is username, the following are node attributes; the second dataset with the filename ”edges.csv”, 
the first two columns depict the direction, ”from” as the sender, ”to” as the receiver, the last one is the edge attribute. 
Variables in the dataset show as follows.

DATASET 1: nodes.csv

•name, the user who participates in the post.

•totaltimes, speaking times of a user in all posts.

•label1, the department of the replier belonging to.

•label2, the rank of the replier, e.g. medical student, specialist, practicing physician.

•Postnum, number of posts one user initiate in the whole forum.

•Integral, integral that a user has.

•Essence, number of posts that evaluated essential by the forum administrators.

•Votenum, number of votes one user get.

•Date1, date of the earliest post.

•Date2, date of the latest post.

DATASET 2: edges.csv

•from, the sender in an interaction.

•to, the receiver in an interaction.

•singletimes, speaking times of a user in one post. 

Also, the freq.csv provides the frequency words appear in the topics.
