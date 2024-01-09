AREX is a testing platform by recording the live traffic from online environment and replaying it to the test environment for regression testing.

With AREX, you can accelerate your testing processes and identify defects and errors earlier in the development cycle, which can ultimately save time and resources. As an open source tool, AREX is constantly evolving and improving thanks to contributions from its community of users.

## Features

- **Code no-invasion based data collection and automation Mock**: mock most components such as Dubbo, Http, Redis, persistence layer framework, configuration center;

- **Support a variety of complex business scenarios of verification**: including multi-threaded concurrency, asynchronous callbacks, write operations and so on;

- **Rapid reproduction of production bugs**: directly use the production recorded data in the local environment.

In summary, AREX is a powerful and flexible automation testing tool that can help you streamline your testing efforts and improve the overall quality of your software applications.

The technical architecture of AREX:

![image](https://github.com/arextest/.github/assets/118187476/878dcc46-130a-4694-9d66-34b6ada35d7f)


| **Model Name**                                               | **Description**                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Schedule Service](https://github.com/arextest/arex-replay-schedule) | Provides replay of all responses sent and retrieved for comparison |
| [API Service](https://github.com/arextest/arex-report) | Provides difference summaries and display detailed difference results after comparing the responses. |
| [Storage Service](https://github.com/arextest/arex-storage)  | Save recordings and get responses as Mock data for [Agent Hook Service](https://github.com/arextest/arex-agent-java) |
| [AREX UI](https://github.com/arextest/arex)                                                      | Front-end presentation module for AREX                       |
| MongoDB                                                      | Data storage and configuration management database           |
| Redis                                                        | High-speed replay cache                                      |

## Getting started

Get started with the [AREX Docs](https://doc.arextest.com/docs/intro/).

## Join the AREX Community

- QQ Group - 656108079
- Follow us on [Twitter](https://twitter.com/AREX_Test)
- [Join the Mailing List](https://groups.google.com/g/arex-test)
- [Join AREX Slack](https://arexcommunity.slack.com/ssb/redirect)
- [Join AREX Discord](https://discord.gg/wy3CZHnV9K)

## Known Users

AREX is trusted by many known users. Welcome to register the company name in this issue: [#370](https://github.com/arextest/arex-agent-java/issues/370)

<img src="https://github.com/arextest/.github/assets/118187476/111cbd04-d0fd-46c4-91aa-50941edeed3a" alt="Trip" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/8c896278-9811-4d82-b103-692b716c610d" alt="xyb2b" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/484b600a-2cda-4471-888c-865edeee55d1" alt="yeahka" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/53f799c5-64cb-4669-b5d7-3b2a62786c11" alt="yeahka" width="200" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/390ad455-5ed2-443e-a1cd-d5de1496821b" alt="yeahka" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/5c152539-bb2d-42bc-92a9-d471f719ea52" alt="yeahka" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/2e31d7b4-7ea3-4930-ae3a-5197e6ca4e22" alt="yeahka" width="250" height=""/>
