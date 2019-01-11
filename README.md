# kdd cup 99 Analysis Machine Learning Python

I got 99.94% accuracy by applying properly a simple Neural Network on the Dataset.

I got 94% accuracy by applying properly Naive Bayes Algorithm on the Dataset. 

You can download the dataset from it's offial website in here:

http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

I used this particular 10% dataset. You can easily download it from the link below:

http://kdd.ics.uci.edu/databases/kddcup99/kddcup.data_10_percent.gz

Extract it and use it like you want.

## PreProcessing :

I used the 10% dataset called kddcup.data_10_percent.gz, which has 494020 observation (rows), and it consists of 42 attributes (columns).

### The list of attributes is illustrated below:

1- Attribute Name: Types of Values
2- duration: continuous.
3- protocol_type: symbolic.
4- service: symbolic.
5- flag: symbolic.
6- src_bytes: continuous.
7- dst_bytes: continuous.
8- land: symbolic.
9- wrong_fragment: continuous.
10- urgent: continuous.
11- hot: continuous.
12- num_failed_logins: continuous.
13- logged_in: symbolic.
14- num_compromised: continuous.
15- root_shell: continuous.
16- su_attempted: continuous.
17- num_root: continuous.
18- num_file_creations: continuous.
19- num_shells: continuous.
20- num_access_files: continuous.
21- num_outbound_cmds: continuous.
22- is_host_login: symbolic
23- is_guest_login: symbolic
24- count: continuous.
25- srv_count: continuous.
26- serror_rate: continuous.
27- srv_serror_rate: continuous.
28- rerror_rate: continuous.
29- srv_rerror_rate: continuous.
30- same_srv_rate: continuous.
31- diff_srv_rate: continuous.
32- srv_diff_host_rate: continuous.
33- dst_host_count: continuous.
34- dst_host_srv_count: continuous.
35- dst_host_same_srv_rate: continuous.
36- dst_host_diff_srv_rate: continuous.
37- dst_host_same_src_port_rate: continuous.
38- dst_host_srv_diff_host_rate: continuous.
39- dst_host_serror_rate: continuous.
40- dst_host_srv_serror_rate: continuous.
41- dst_host_rerror_rate: continuous.
42- dst_host_srv_rerror_rate: continuous.
