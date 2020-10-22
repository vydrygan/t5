# Server Monitor

## What is it?
**Server Monitor** — a Java-based application for aggregation, processing and visualization of data from the Linux server monitoring agent.

## Installation 
1. Clone repository
    ```sh
    git clone https://tss2020.repositoryhosting.com/git/tss2020/t4.git
    ```
    or download archive:
    - [zip](https://tss2020.repositoryhosting.com/git/tss2020/t4.git/snapshot/HEAD.zip?js=1)
    - [tar.gz](https://tss2020.repositoryhosting.com/git/tss2020/t4.git/snapshot/HEAD.tar.gz?js=1)
    - [tar.bz2](https://tss2020.repositoryhosting.com/git/tss2020/t4.git/snapshot/HEAD.tar.bz2?js=1)


2. Execute the command:

    ```sh
    mvn install
    ```

    and run:
   
    ```sh
    mvn exec:java -Dexec.mainClass=com.team4.app.ServerMonitor
    ```

## Created with
- JDK 14.0.2 [![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)][1]

- Javalin [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)][2]

- Maven [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)][2]

- Node.js [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)][3]

- React [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)][3]

## Created by
Team 4:
1. Artem Koplyk
2. Alexandra Zakirova
3. Gromenko Daria
4. Vladyslav Vydryhan
5. Vatsenko Andrii
6. Holodnyi Vladyslav
7. Kolomoitsev Maksym

## Licensing
Please see the file [LICENSE.md](./LICENSE)

[1]:https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html
[2]:https://opensource.org/licenses/Apache-2.0
[3]:https://opensource.org/licenses/MIT
