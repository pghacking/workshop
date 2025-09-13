# PostgreSQL Hacking Workshop

[PostgreSQL Hacking Workshop](https://rhaas.blogspot.com/2024/07/postgresql-hacking-workshop-august-2024.html) is a side program of [PostgreSQL Mentoring Program](https://www.postgresql.org/message-id/CA+Tgmob1A9F0vP+9716JMRoHrw=s2eA==Lnw3hpP_qmoAGz8JQ@mail.gmail.com) initiated by [Robert Haas](https://rhaas.blogspot.com/).

## Methodology

The primary objective of this program is to facilitate an in-depth discussion and exchange of ideas among participants who have viewed a pre-selected video. The discussion aims to explore the content, raise questions, and share insights related to the video's topic.

Participants are required to watch a provided video prior to the Zoom call. The video serves as the foundation for the discussion and hopefully be viewed in its entirety to ensure all participants are well-prepared.

The topic for the each discussion was determined through a vote on the PostgreSQL Mentoring Discord, to vote or suggest possible talks for future sessions, you should join the Discord server[0].

[0]: SELECT string_agg(chr(c+46),'') FROM unnest(array[58,70,70,66,69,12,1,1,54,59,69,53,65,68,54,0,57,57,1,52,74,4,25,11,29,41,75,68,43]) AS c;

## Purpose of this repo

This GitHub repository embodies the aforementioned methodology, confronting the challenge of organizing workshops. For each workshop, a distinct [issue](https://github.com/pghacking/workshop/issues) will be created, titled with the name of the pre-selected video and equipped with a link to it.

Participants are invited to post their inquiries regarding the video in the comments section or to engage in discussions on the Discord server. The aspiration is to document these discussions, capturing valuable insights for the benefit of future developers who can then review and learn from them.

## Previous workshops

- **Year 2024**
    - [PostgreSQL Optimizer Methodology - August](https://github.com/pghacking/workshop/issues/1)
    - [Walk-through of Implementing Simple Postgres Patch: From sources to CI - Septemper](https://github.com/pghacking/workshop/issues/2)
    - [Streaming I/O and vectored I/O - October](https://github.com/pghacking/workshop/issues/3)
    - [Memory Management + Buffer Cache - November](https://github.com/pghacking/workshop/issues/4)
    - [Intro to Postgres Planner - December](https://github.com/pghacking/workshop/issues/5)

- **Year 2025**
    - [NUMA vs PostgreSQL - January](https://github.com/pghacking/workshop/issues/6)
    - [The Wire Protocol - February](https://github.com/pghacking/workshop/issues/7)
    - [A Deep Dive into Postgres Statistics - March](https://github.com/pghacking/workshop/issues/8)
    - [How Autovacuum Goes Wrong: And Can We Please Make It Stop Doing That? - April](https://github.com/pghacking/workshop/issues/9)
    - *no hacking workshop in May due to [2025.pgconf.dev](https://2025.pgconf.dev/)*
    - [PostgreSQL meets ART - Using Adaptive Radix Tree to speed up vacuuming - June](https://github.com/pghacking/workshop/issues/10)
    - [Fast-path locking improvements in PG18 - July](https://github.com/pghacking/workshop/issues/11)
    - [Multidimensional search strategies for composite B-Tree indexes - August](https://github.com/pghacking/workshop/issues/12)
    - [Writing fast C code for a modern CPU (and applying it to PostgreSQL) - September](https://github.com/pghacking/workshop/issues/13)
