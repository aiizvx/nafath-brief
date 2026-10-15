Version: NAFATH-V2

Track: Cybersecurity

## Overview

Emergency responders need a 5G service that is dependable in the face of network congestion, outages, and cyberattacks. Applications and services required to assist emergency operations are provided by software. Artificial intelligence can be used to anticipate network congestion and spot possible issues. Even in situations when connectivity is restricted, mobile applications enable rescuers to obtain crucial information in the field. Emergency services might have dedicated connectivity thanks to networking technologies like 5G network slicing. Cybersecurity helps the operator respond to security events and shields the service against attacks. Data systems facilitate daily reports, performance monitoring, and the organization of service information. Together, these six domains enhance decision-making, security, and availability. Understanding the incident response lifecycle is essential for protecting emergency communications and maintaining reliable 5G services during cyberattacks.

## Software

HTTP request methods signify the intent behind a request. Safe methods, including GET and HEAD, obtain data without altering the server's state. Idempotent methods consist of GET, HEAD, PUT, and DELETE, as repeating the identical request yields the same desired outcome. This matters when a client automatically retries a failed request. Repeating a POST request could result in multiple emergency reports if the initial request was successful but the response was not received.

Resource: HTTP request methods - https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods

## AI

Overfitting happens when a machine learning model fits the training data too closely, including noise, and struggles to perform well on new data. In the 5G service, this may cause the model to predict congestion accurately using historical data but fail to identify new congestion patterns. Cross-validation helps detect overfitting by training and evaluating the model on different subsets of data. If performance decreases significantly on validation data, the model may not generalize well.

Resource: Cross-validation: evaluating estimator performance - https://scikit-learn.org/stable/modules/cross_validation.html

## Mobile

The responder's mobile application must allow access to previously stored essential information when the network is unavailable. All new reports or updates should be saved locally until the connection is restored. When connectivity returns, the app should synchronize pending changes with the server and manage conflicts to prevent data loss or duplication. A clear synchronization status allows responders to determine whether their information has been uploaded successfully.

Resource: Offline-first architecture - https://developer.android.com/topic/architecture/data-layer/offline-first

## Networking

## Cybersecurity

## Data

## My Track: Misconception

## Open Question
