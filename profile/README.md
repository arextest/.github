<p align="center">
  <img src="https://github.com/arextest/arex/assets/118187476/434bfe81-e2f3-40f5-a6cd-bbf84fb8003e" alt="Arex Icon" width="350" height=""/>

AREX is a testing platform by recording the live traffic from online environment and replaying it to the test environment for regression testing.

With AREX, you can accelerate your testing processes and identify defects and errors earlier in the development cycle, which can ultimately save time and resources. As an open source tool, AREX is constantly evolving and improving thanks to contributions from its community of users.

## Features

- **Code no-invasion based data collection and automation Mock**: mock most components such as Dubbo, Http, Redis, persistence layer framework, configuration center;

- **Support a variety of complex business scenarios of verification**: including multi-threaded concurrency, asynchronous callbacks, write operations and so on;

- **Rapid reproduction of production bugs**: directly use the production recorded data in the local environment.

In summary, AREX is a powerful and flexible automation testing tool that can help you streamline your testing efforts and improve the overall quality of your software applications.

The technical architecture of AREX:

![architecture](https://github.com/arextest/.github/assets/118187476/3e976f19-07fa-4734-bbe7-3a2284607203)

| **Model Name**                                               | **Description**                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Schedule Service](https://github.com/arextest/arex-replay-schedule) | Provides replay of all responses sent and retrieved for comparison |
| [API Service](https://github.com/arextest/arex-report) | Provides difference summaries and display detailed difference results after comparing the responses. |
| [Storage Service](https://github.com/arextest/arex-storage)  | Save recordings and get responses as Mock data for [Agent Hook Service](https://github.com/arextest/arex-agent-java) |
| [AREX UI](https://github.com/arextest/arex)                                                      | Front-end presentation module for AREX                       |
| MongoDB                                                      | Data storage and configuration management database           |
| Redis                                                        | High-speed replay cache                                      |

## Getting started

Get started with the [AREX Docs](http://arextest.com/docs/intro).

## Join the AREX Community

- QQ Group - 656108079
- Follow us on [Twitter](https://twitter.com/AREX_Test)
- [Join the Mailing List](https://groups.google.com/g/arex-test)
- [Join AREX Slack](https://arexcommunity.slack.com/ssb/redirect)
- [Join AREX Discord](https://discord.gg/tqESG2Jp)
