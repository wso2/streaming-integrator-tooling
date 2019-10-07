<!--
  ~ /*
  ~ * Copyright (c) 2019, WSO2 Inc. (http://www.wso2.org) All Rights Reserved.
  ~ *
  ~ * Licensed under the Apache License, Version 2.0 (the "License");
  ~ * you may not use this file except in compliance with the License.
  ~ * You may obtain a copy of the License at
  ~ *
  ~ * http://www.apache.org/licenses/LICENSE-2.0
  ~ *
  ~ * Unless required by applicable law or agreed to in writing, software
  ~ * distributed under the License is distributed on an "AS IS" BASIS,
  ~ * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  ~ * See the License for the specific language governing permissions and
  ~ * limitations under the License.
  ~ */
  -->
  
# Streaming Integrator Tooling

[![Jenkins Build Status](https://wso2.org/jenkins/view/wso2-dependencies/job/products/job/streaming-integrator-tooling/badge/icon)](https://wso2.org/jenkins/view/wso2-dependencies/job/products/job/streaming-integrator-tooling/)
  [![GitHub Release](https://img.shields.io/github/release-pre/wso2/streaming-integrator-tooling.svg)](https://github.com/wso2/streaming-integrator-tooling/releases/)
  [![GitHub Release Date](https://img.shields.io/github/release-date-pre/wso2/streaming-integrator-tooling.svg)](https://github.com/wso2/streaming-integrator-tooling/releases)
  [![GitHub Open Issues](https://img.shields.io/github/issues-raw/wso2/streaming-integrator-tooling.svg)](https://github.com/wso2/streaming-integrator-tooling/commits/master)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/wso2/streaming-integrator-tooling.svg)](https://github.com/wso2/streaming-integrator-tooling/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Introduction

WSO2 Streaming Integrator Tooling is an open source developer environment for [Streaming Integrator](https://github.com/wso2/streaming-integrator). 

## Streaming Integrator tooling profiles?

WSO2 Streaming Integration Tooling consists with 3 profiles

* Editor runtime.

    This runs the developer environment where the following can be carried out:

   * Creating Siddhi applications/Siddhi application templates and deploy siddhi apps in to streaming integrator runtimes.
   * Testing and debugging Siddhi applications to  determine whether they are ready to be used in a production environment.

* Business Rules Runtime

  In streaming integrator, there are use cases for analyzing statistics that involve operations such as calculating the average, minimum, maximum etc., for different endpoints. The Business Rules Manager allows you to define templates and generate business rules from them for different scenarios with common requirements.

* Template Editor Runtime

  Template editor runtime will provide the support to create template which will be used to create business rules in business rules runtime. 
  

![Streaming Integrator Tooling/ Workflow](docs/images/editor_screen.png)

## Download

The Streaming Integrator Tooling is currently on development stage so please follow the [How to build]() section to build the streaming integrator from the source.
<!-- Please download the latest WSO2 Streaming Integrator Tooling release from [here]()  -->

## Building from the Source

Please follow the steps mentioned below to build the WSO2 Streaming Integrator Tooling from source.

1. Clone or download the source code from this repository.
2. Run the `mvn clean install` from the root directory of the repository
3. The generated Streaming Integrator Tooling distribution can be found at `streaming-integrator-tooling/modules/distribution/target/wso2si-tooling-<version>.zip`

## Getting Started

Get started with Streaming integrator in a few minutes by following [Streaming Integrator Quick Start Guide](https://docs.wso2.com/display/SP4xx/Quick+Start+Guide)

## Support

We are committed to ensuring that your enterprise middleware deployment is completely supported from evaluation to production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology.

For more details and to take advantage of this unique opportunity please visit our [support site](http://wso2.com/support).


## Reporting Issues

We encourage you to report issues, documentation faults and feature requests regarding WSO2 Streaming integrator through the [WSO2 SI Issue Tracker](https://github.com/wso2/streaming-integrator/issues).

When reporting security issues, please report them to [security@wso2.com](mailto:security@wso2.com), and make sure that you adhere to [WSO2 Security Vulnerability Reporting Guidelines](https://docs.wso2.com/display/Security/WSO2+Security+Vulnerability+Reporting+Guidelines).
