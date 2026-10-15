Version: NAFATH-V3
Track: Cybersecurity

## Overview
A government agency plans to launch an AI chat assistant in its mobile application to answer citizens’ questions about public services. Six IT fields must work together to make this assistant useful, reliable, and secure. Software engineering manages changes to the assistant’s public API through semantic versioning. Artificial intelligence uses Retrieval-Augmented Generation (RAG) to support answers with relevant information. Mobile development helps protect connections between the application and its servers through App Transport Security. Networking provides IP addressing so devices can communicate as the service grows. Cybersecurity protects the assistant against malicious instructions and other attacks. Data management helps the agency handle stored conversations while respecting privacy requirements. Together, these fields support a public service that is easier to maintain, safer to use, and more trustworthy for citizens.
## Software
For the government AI assistant, Semantic Versioning helps developers communicate changes to its public API. A MAJOR version increases when an API change is incompatible with existing applications. A MINOR version increases when new functionality is added without breaking compatibility. A PATCH version increases when developers fix bugs without changing existing functionality. For example, adding a compatible API feature requires MINOR, while removing an existing endpoint may require MAJOR.

Resource: Semantic Versioning 2.0.0 – https://semver.org/

## AI
Retrieval-Augmented Generation (RAG) helps the government AI assistant provide more accurate answers by retrieving relevant information from trusted sources before generating a response. For example, when a citizen asks about renewing an identification card, RAG can retrieve the latest official instructions and use them to support the answer. This reduces the risk of incorrect or outdated information, but it does not guarantee that every answer will be correct.

Resource: Microsoft Learn – Retrieval-Augmented Generation (RAG) – https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview

## Mobile
App Transport Security (ATS) helps protect communication between the government iOS application and its servers. By default, ATS requires secure network connections and can block requests to an endpoint that uses unencrypted HTTP instead of HTTPS. If the AI assistant’s server only supports HTTP, the application may fail to connect. Developers should configure the server to use HTTPS rather than weaken security by adding unnecessary ATS exceptions.

Resource: Apple Developer – App Transport Security – https://developer.apple.com/documentation/bundleresources/information-property-list/nsapptransportsecurity

## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
