# PostgreSQL Hacking Workshop

[PostgreSQL Hacking Workshop](https://rhaas.blogspot.com/2024/07/postgresql-hacking-workshop-august-2024.html) is a side program of [PostgreSQL Mentoring Program](https://www.postgresql.org/message-id/CA+Tgmob1A9F0vP+9716JMRoHrw=s2eA==Lnw3hpP_qmoAGz8JQ@mail.gmail.com) initiated by [Robert Haas](https://rhaas.blogspot.com/).


## Previous workshops

- **Year 2025**
    - [Improving scalability; Reducing overhead in shared memory - November](https://github.com/pghacking/workshop/issues/15)
    - [Investigating Multithreaded PostgreSQL - October](https://github.com/pghacking/workshop/issues/14)
    - [Writing fast C code for a modern CPU (and applying it to PostgreSQL) - September](https://github.com/pghacking/workshop/issues/13)
    - [Multidimensional search strategies for composite B-Tree indexes - August](https://github.com/pghacking/workshop/issues/12)
    - [Fast-path locking improvements in PG18 - July](https://github.com/pghacking/workshop/issues/11)
    - [PostgreSQL meets ART - Using Adaptive Radix Tree to speed up vacuuming - June](https://github.com/pghacking/workshop/issues/10)
    - *no hacking workshop in May due to [2025.pgconf.dev](https://2025.pgconf.dev/)*
    - [How Autovacuum Goes Wrong: And Can We Please Make It Stop Doing That? - April](https://github.com/pghacking/workshop/issues/9)
    - [A Deep Dive into Postgres Statistics - March](https://github.com/pghacking/workshop/issues/8)
    - [The Wire Protocol - February](https://github.com/pghacking/workshop/issues/7)
    - [NUMA vs PostgreSQL - January](https://github.com/pghacking/workshop/issues/6)

- **Year 2024**
    - [Intro to Postgres Planner - December](https://github.com/pghacking/workshop/issues/5)
    - [Memory Management + Buffer Cache - November](https://github.com/pghacking/workshop/issues/4)
    - [Streaming I/O and vectored I/O - October](https://github.com/pghacking/workshop/issues/3)
    - [Walk-through of Implementing Simple Postgres Patch: From sources to CI - Septemper](https://github.com/pghacking/workshop/issues/2)
    - [PostgreSQL Optimizer Methodology - August](https://github.com/pghacking/workshop/issues/1)

## Methodology

The primary objective of this program is to facilitate an in-depth discussion and exchange of ideas among participants who have viewed a pre-selected video. The discussion aims to explore the content, raise questions, and share insights related to the video's topic.

Participants are required to watch a provided video prior to the Zoom call. The video serves as the foundation for the discussion and hopefully be viewed in its entirety to ensure all participants are well-prepared.

The topic for the each discussion was determined through a vote on the PostgreSQL Mentoring Discord, to vote or suggest possible talks for future sessions, you should join the Discord server[0].

[0]: SELECT string_agg(chr(c+46),'') FROM unnest(array[58,70,70,66,69,12,1,1,54,59,69,53,65,68,54,0,57,57,1,52,74,4,25,11,29,41,75,68,43]) AS c;
