Applicaiton by Daniel Standage:
https://gist.githubusercontent.com/standage/29f41ba8779fb1dc7df4ecb628a5ae52/raw/72cf4e95d1460d65aa3cb3b3f9f7ad0be10d4265/jetstream-training-allocation-proposal-2016.md

This proposal requests computing resources on the IU/TACC Jetstream platform in support of training and outreach efforts in the Lab for Data Intensive Biology at UC Davis.
Through our lab's research collaborations, workshops, rotation student mentoring, and informal weekly "meet and analyze data" sessions, we frequently encounter scientists faced with bioinformatics computing problems beyond what their training has prepared them for.
Accordingly, along with our research software tools we have published several protocols for analysis of genome-scale data (http://khmer-protocols.readthedocs.org/).
These protocols are now one of our go-to resources for on-boarding new students, collaborators, and colleagues.

However, one lingering obstacle in these training efforts is that the laptop and desktop computers most scientists have access to are insufficient even for these basic introductory protocols, and much more so for their ongoing computing needs.
The immediate goal of this allocation is to address the need for compute resources in these training and outreach activities.
As a secondary result we hope and expect that experience with these resources will help our colleagues become more independent, empowered to write their own research allocation proposals and utilize the diversity of cyberinfrastructure resources at their disposal.

------

We are requesting capacity for training 12 students / collaborators / colleagues (hereafter "students") on "Medium" VMs (6 vCPU, 16 GB RAM, 60 GB storage) over the course of the next year.
In our experience, new students require approximately 10-14 days to complete one of the protocols.
These protocols include some long-running jobs (transcriptome assemblies with Trinity, sequence similarity searches with BLAST, etc) which can run for a day or more.
But this also includes a lot of idle time, and with judicious use of block storage and suspension of idle VMs, actual compute time consumed should be considerably less.
However, to account for time for troubleshooting and accidental idle time, we are requesting a full 14 days of compute time per student.
This brings the total request to 25,000 SUs.

- 14 days
- 24 hours / day
- 6 vCPUs
- 12 students

```
14 * 24 * 6 * 12 = 24192 SUs
```

We also request 1 block storage device per student at 200 GB per device, for a total of 2400 GB.
