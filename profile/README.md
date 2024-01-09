AREX is a testing platform by recording the live traffic from online environment and replaying it to the test environment for regression testing.

With AREX, you can accelerate your testing processes and identify defects and errors earlier in the development cycle, which can ultimately save time and resources. As an open source tool, AREX is constantly evolving and improving thanks to contributions from its community of users.

## Features

- **No need to write or maintain a regression suite**: builds integration tests by capturing real-world scenarios from production and run them when a new feature or change is expected to be tested.

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

<p align="">
  <a href="http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=vTXYPzuu4zL4Oie28eo7YNT96MPHfU42&authKey=2PIypXqgLE66yP3W3umu9X21zLxDj1sFIatAKkuXCd6AmXRpmtKPtHqX9x6n38Fh&noverify=0&group_code=656108079" target="_blank"><img src="https://img.shields.io/badge/QQGroup-0085CA?style=for-the-badge&logo=tencentqq&logoColor=white"></a>
  &nbsp;
  <a href="https://github.com/arextest/.github/assets/118187476/32a444d1-a559-47c2-a724-b64d5bc97716" target="_blank"><img src="https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white"></a>
  	&nbsp;
  <a href="https://twitter.com/AREX_Test" target="_blank"><img src="https://img.shields.io/badge/Twitter-1D9BF0.svg?style=for-the-badge&logo=Twitter&logoColor=white"></a>
  	&nbsp;
   <a href="https://dev.to/arex_test" target="_blank"><img src="https://img.shields.io/badge/dev.to-0A0A0A.svg?style=for-the-badge&logo=devdotto&logoColor=white"></a>
  	&nbsp;
   <a href="https://arexcommunity.slack.com/ssb/redirect" target="_blank"><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"></a>
  	&nbsp;
   <a href="https://arexcommunity.slack.com/ssb/redirect" target="_blank"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>
  	&nbsp;
</p>

## Known Users

AREX is trusted by many known users. Welcome to register the company name in this issue: [#370](https://github.com/arextest/arex-agent-java/issues/370)

<img src="https://github.com/arextest/.github/assets/118187476/111cbd04-d0fd-46c4-91aa-50941edeed3a" alt="Trip" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/8c896278-9811-4d82-b103-692b716c610d" alt="xyb2b" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/484b600a-2cda-4471-888c-865edeee55d1" alt="yeahka" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/53f799c5-64cb-4669-b5d7-3b2a62786c11" alt="yeahka" width="200" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/390ad455-5ed2-443e-a1cd-d5de1496821b" alt="yeahka" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/5c152539-bb2d-42bc-92a9-d471f719ea52" alt="yeahka" width="250" height=""/>
<img src="https://github.com/arextest/.github/assets/118187476/e7a5b008-0280-4837-95e2-8184186cff35" alt="yeahka" width="300" height=""/>
