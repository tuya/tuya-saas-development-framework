# Tuya SaaS Development Framework

A submodule repository for distributing Tuya SaaS Development framework source code. Use 'git clone --recurse-submodules git@github.com:tuya/tuya-saas-framework.git' to also clone all submodules.

## What is SaaS Development Framework?

Based on Tuya OpenAPI, the SaaS Development Framework is integrated with a variety of IoT SaaS features and provides a full set of frontend and backend solution code. You can leverage the framework to quickly build SaaS applications suitable for multiple industries and substantially improve the delivery efficiency and price performance.

Currently, the framework integrates basic functional modules such as user login, role permissions, device management, device control, and data dashboard. Also, it provides a React frontend user interface by using Ant Design. After development simply based on the source code, your product will be good to go.

## Quick start

To get started, please read through the following topics.

Backend: [Run SaaS Development Framework Backend Project in Local Mode](https://developer.tuya.com/en/docs/iot/SaaSDevelopmentFramework_backend?id=Kaqcx9hwc9i62)

Frontend: [Run SaaS Development Framework Frontend Project in Local Mode](https://developer.tuya.com/en/docs/iot/SaaSDevelopmentFramework_ftontend?id=Kaqcwpn4p8guu)

If you want to quickly experience the functionality, or if you do not need further development and customization, local private deployment can be implemented with the `Docker` image.

- [Docker image address](https://hub.docker.com/r/iotportal/iot-suite)
- [Run SaaS Development Framework Docker](https://developer.tuya.com/en/docs/iot/SaaSDevelopmentFramework_Image?id=Kapsg7pttb8f2)


## Aggregated repositories

#### iot-suite-server
`Iot Server` is a backend service application for the unified management console that implements industry capabilities in the cloud. It can help you flexibly integrate and extend the IoT functionality as needed.

#### tuya-connector
`tuya-connector` helps you efficiently create cloud development projects regarding the OpenAPI or message subscription capabilities. You can put all the focus on business logic without taking care of server-side programming nor relational databases.

#### connector
The `connector` framework maps cloud APIs with local APIs based on simple configurations and flexible extension mechanisms. You can subscribe to the distribution of cloud messages as local events. You only need to focus on business logic. The OpenAPI or message subscription process is simplified, so the development efficiency is promoted with the service logic put at the center.

#### iot-suite-portal
IoT Portal is a frontend project of the SaaS Development Framework based on the `qiankun` framework. Following the Ant Design specification, IoT Portal has been developed with a standard React user interface, so you can directly use the out-of-the-box user interface.

## Issue and feedback

You can use `GitHub Issue` to give us feedback on any problems and we are ready to help you out.

## Technical support

You can get technical support from Tuya in the following services:

* [Help Center](https://support.tuya.com/en/help)

* [Service & Support](https://service.console.tuya.com)





