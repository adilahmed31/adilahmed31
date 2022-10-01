### Hi there 👋

<!--
**adilahmed31/adilahmed31** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
I'm a Security Engineer and current grad student at UW-Madison working on issues relating to security and privacy online. I'm currently interested in exploring computer systems-  including operating systems, networking and distributed systems.

An incomplete guide to following along my messy github page and finding the repo you're interested in is below. Please reach out if you would like to contribute or make use of them in any way.

Some selected projects:

My own:
1. *leveldb-kv-store*: Implemented a scalable, distributed cloud-native version of levelDB in C++ on AWS. Used Elastic File System (EFS), Zookeeper and Docker containers to deploy the system and gRPC for communication. See slide.pdf and report.pdf for a 10,000 feet non-technical glance.

2. *APK-Analysis*: The web crawling and ML-classification pipeline i built for my research on stalkerware analysis in this paper: https://petsymposium.org/popets/2022/popets-2022-0102.php.

3. *Safe Exit for Sensitive Websites*: Developed a simple website for Madison Tech Clinic - an initiative to provide technical assistance to victims of Intimate Partner Surveillance. Developed a Safe Exit mechanism that allows the site to be closed quickly, disabling the back button and not leaving a trace in history. Website link: https://techclinic.cs.wisc.edu (Try out the safe exit mechanism, and let me know in case of any comments!)

4. *IdIoT* - Identify IoT devies. Pipeline to parse raw traffic (pcap files) from IoT devices using PyShark. extract key characteristics and train an ml-classifier (using scikitlearn) to recognize the traffic.

5. *SCRUBS*: Strongly-consistent Redundancy-based Utilitarian Block Store. This is an implementation of a distributed highly-available file system in C++ using a variety of innovative techniques - piggybacking, handshake protocol etc. to achieve strong consistency with high performance. See slide.pdf and report.pdf!

6. *739-p2c*: A file-system built on FUSE that allows a user to pick multiple modes with different performance and consistency guarantees.

7. *cs537-Discussion-su22*: My detailed discussion notes and code samples I used as a Teaching Assistant for Operating Systems. Note that the work builds on contributions by past TAs and isn't entirely my own. 

As a code contributor: 

1. *isdi* - IPV Spyware Discovery Tool. Contributed code changes to a tool we deploy in our tech clinic for survivors of Intimate Partner Violence / Surveillance (IPS /IPV). The tool can scan any android / iOS phone and detect installed apps that could be abused for stalking.
