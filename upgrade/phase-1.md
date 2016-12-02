# Phase 1 of PPS cluster Simple Revitalization Plan


This is the plan so far for Phase 1 of this effort:

+ JZ is working on a new PPS cluster node image with RHEL 7.3
(released Nov. 3, 2016).

+ This Linux kernel does not support lustre. Therefore, we will: (1)
retain a few compute nodes with the old image (RHEL 5.5, released
March 30, 2010), which can also be used to transfer files, and (2)
encourage all users to transfer their files and home directory
from `/mnt/lustre` to `/mnt/gluster`.

+ We will maintain an image with only the most essential software and
libraries. This is because (1) maintaining up-to-date software is a
  burden on us, (2) without too much effort, users can install most
  software themselves either in their home directories, or in
  /data/tools.

• We will poll current lab members to help decide on the "most essential software" list.

• Install RStudio and RStudio Server (rserver) on one or more nodes.

• JZ will also look into updating gluster.

• Question: should we do some tests to assess and improve file system performance? John Blischak says that  "ls" and tab completion is very slow for directories with large numbers of files.


• PC will run this plan by Matthew and others to see if they have any questions/concerns.

• We will communicate this plan to all PPS cluster users, and make sure that all (reasonable) needs are addressed.

• We will write a few scripts that simulate a few basic tasks (e.g., building R from source, building samtools from source, running RStudio). The idea is to run a few sanity checks to make sure that the new setup works for these basic tasks—it isn't intended to be comprehensive.

• Additionally, we will get some volunteers to test out the new image (e.g., test whether optimization libraries such as Rmosek can be successfully installed). Importantly, this includes testing the gluster file system.

• After completing the Phase 1 updates, PC will brief the lab (e.g., at an NHS meeting) on the updates, and give a quick tour of the "revitalized" PPS cluster.

• We will update the message that appears on the console when you log
  in to spudhead.
