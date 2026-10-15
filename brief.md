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

5G network slicing allows a physical network to be divided into multiple virtual networks, each designed for specific requirements. A dedicated slice can provide emergency responders with more reliable connectivity and prioritize critical communications during peak periods. This helps responders share essential information even when many users are connected. However, network slicing alone cannot guarantee service availability during every network outage or cyberattack.

Resource: Network Slicing - https://www.3gpp.org/technologies/network-slicing

## Cybersecurity

The incident response lifecycle offers a systematic method for managing cybersecurity incidents. It includes preparation, detection and analysis, containment, eradication, recovery, and lessons learned. During an attack, the security team detects suspicious activity, assesses its impact, and limits the damage. The team then removes the threat, restores affected systems, and reviews the incident to improve future security. An effective response process reduces disruptions and protects essential services used by emergency responders.

Resource: Computer Security Incident Handling Guide - https://csrc.nist.gov/pubs/sp/800/61/r2/final

## Data

A star schema organizes data around a central fact table connected directly to dimension tables, simplifying reporting queries. A snowflake schema divides dimensions into additional related tables, reducing data redundancy but requiring more joins. For daily 5G usage reports by region, a star schema can be a practical choice because it simplifies queries and helps analysts summarize usage efficiently. The best design depends on data complexity and reporting requirements.

Resource: Star schema - https://learn.microsoft.com/en-us/power-bi/guidance/star-schema

## My Track: Misconception

## Open Question
