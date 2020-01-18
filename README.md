# Credulous

The repository stores a dataset of human-operated Twitter accounts, with
the characteristics of having many bots amongst their friends.

Two terms of usage apply:

- The appropriate papers are cited in any research product whose
findings are based on this dataset;
- The usage of this dataset is for research purposes only.

Papers to be cited:

1) Alessandro Balestrucci, Rocco De Nicola, Omar Inverso, Catia
Trubiani:
Identification of credulous users on Twitter. SAC 2019: 2096-2103
<pre><code>
bibtex entry:  
@inproceedings{DBLP:conf/sac/BalestrucciNIT19,  
   author    = {Alessandro Balestrucci and
                Rocco {De Nicola} and
                Omar Inverso and
                Catia Trubiani},  
   title     = {Identification of credulous users on {Twitter}},  
   booktitle = {Proceedings of the 34th {ACM/SIGAPP} Symposium on Applied
Computing,
                {SAC} 2019, Limassol, Cyprus, April 8-12, 2019},  
   pages     = {2096--2103},  
   year      = {2019},  
   url       = {https://doi.org/10.1145/3297280.3297486},  
   doi       = {10.1145/3297280.3297486}  
}  
</code></pre>

2) Alessandro Balestrucci, Rocco De Nicola, Marinella Petrocchi, Catia Trubiani:  
Do you really follow them? Automatic Detection of Credulous Twitter Users. In 20th International Conference on Intelligent Data Engineering and Automated Learning (IDEAL), LNCS Springer, 2019 (in press)
<pre><code>
bibtex entry:  
@inproceedings{balestrucci2019you,
  title={Do you really follow them? Automatic detection of credulous Twitter users},
  author={Balestrucci, Alessandro and De Nicola, Rocco and Petrocchi, Marinella and Trubiani, Catia},
  booktitle={International Conference on Intelligent Data Engineering and Automated Learning},
  pages={402--410},
  year={2019},
  organization={Springer}
}
</code></pre>
3) Alessandro Balestrucci, “How many bots are you following?”, in Proceedings of the 4th Italian Conference on Cyber Security, ITASEC2020 - in press. Available: https://arxiv.org/abs/2001.05222
<pre><code>
bibtex entry:
@inproceedings{aless2020bots,
  title={How many bots are you following?},
    author={Alessandro Balestrucci},
    year={2020},
    eprint={2001.05222},
    archivePrefix={arXiv},
    primaryClass={cs.SI}
  booktitle={in Proceedings of the 4th Italian Conference on Cyber Security, ITASEC2020 - in press},
  year={2020}
}
</code></pre>

This git project is structured in the following way:  
- Credulous (folder)
- Credulous_2.0 (folder): 316 credulous users
- Credulous_Regrgession_tasks (folder): human-operated Twitter accounts with associated number of followees and, among them, the number of bot-followees
- Humans2Considered.txt (The Twitter ID of certified HUMAN users)


The structure is this:  
Credulous (GitProj)   
├── Credulous   
│   ├── Humans2Considered.txt   
│   ├── All Rules   
│   │   └── R1234   
│   │       ├── R1234_cut100_19.txt   
│   │       ├── R1234_cut150_37.txt   
│   │       └── R1234_cut200_63.txt   
│   ├── Impact of Normalization   
│   │   ├── R13   
│   │   │   ├── R13_cut100_71.txt   
│   │   │   ├── R13_cut150_114.txt   
│   │   │   └── R13_cut200_152.txt   
│   │   └── R24   
│   │       ├── R24_cut100_82.txt   
│   │       ├── R24_cut150_125.txt   
│   │       └── R24_cut200_174.txt   
│   ├── Impact of Seniority   
│   │   ├── R12   
│   │   │   ├── R12_cut100_36.txt   
│   │   │   ├── R12_cut150_66.txt   
│   │   │   └── R12_cut200_101.txt   
│   │   └── R34   
│   │       ├── R34_cut100_23.txt   
│   │       ├── R34_cut150_42.txt   
│   │       └── R34_cut200_67.txt   
│   └── RulesInIsolation   
│       ├── R1   
│       │   ├── R1_100.txt   
│       │   ├── R1_150.txt   
│       │   └── R1_200.txt   
│       ├── R2   
│       │   ├── R2_100.txt   
│       │   ├── R2_150.txt   
│       │   └── R2_200.txt   
│       ├── R3   
│       │   ├── R3_100.txt   
│       │   ├── R3_150.txt   
│       │   └── R3_200.txt   
│       └── R4   
│           ├── R4_100.txt   
│           ├── R4_150.txt   
│           └── R4_200.txt   
└── Credulous_2.0   
│   └── Credulous_v2.0.csv   
└── Credulous_Regression_tasks  
      └── data.csv   


##### For further information, please send an e-mail to: alessandro.balestrucci@gssi.it
