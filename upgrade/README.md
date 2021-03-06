# PPS cluster Simple Revitalization Plan
 
This document describes the "simple revitalization plan" developed by
John Zekos (JZ), John Blischak (JB) and Peter Carbonetto (PC) for
upgrading the PPS cluster (`pps-gateway.uchicago.edu`). So far, we
have sketched out [Phase 1 of this plan](phase-1.md), and we are
currently working through this phase.

### What does "revitalization" mean?

+ Upgrading the operating system (Red Hat Enterprise Linux, or RHEL)
so that it is reasonably up-to-date and supports most current
software.

+ Installing up-to-date versions of only the most essential software
(e.g., R, RStudio, python, samtools) and libraries (e.g., atlas, gsl)
for our research.

+ Upgrading the networking file system (gluster) in an effort to
optimize peformance.

+ Cleaning up old or unused files to (1) improve file system
performance, and (2) make space available for others to use.

### Why "simple"?

+ JZ, JB and PC don't have much time.

• The PPS cluster is getting old.

+ The long-term future of the PPS cluster is unclear.

+ Still, the PPS cluster remains a valuable computing resource, so we
should make effective use of it. We are taking simple steps to improve
the computing environment as much as possible within our constraints.
