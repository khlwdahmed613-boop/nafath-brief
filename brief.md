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
IPv4 and IPv6 are Internet Protocol versions used to identify devices and support communication across networks. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses, providing a much larger address space. For the government AI assistant, IPv6 can help support a growing number of citizens’ devices and connected services without relying as heavily on address sharing. However, the agency must still ensure that its networks and servers support IPv6 correctly.

Resource: RFC 8200 – Internet Protocol, Version 6 (IPv6) Specification – https://www.rfc-editor.org/rfc/rfc8200.html

## Cybersecurity
Prompt injection is a security risk for the government AI assistant because attackers may try to manipulate its responses. Direct prompt injection occurs when an attacker sends malicious instructions directly to the assistant. Indirect prompt injection occurs when harmful instructions are hidden in external content that the assistant reads. Two important mitigations are limiting the assistant’s permissions through least-privilege access and validating its outputs before they are used in sensitive operations.

Resource: OWASP – LLM01:2025 Prompt Injection – https://genai.owasp.org/llmrisk/llm01-prompt-injection/

## Data
Anonymization and pseudonymization are two methods used to protect personal data. Anonymization removes identifying information so that individuals cannot reasonably be identified again. Pseudonymization replaces identifying details with codes or other identifiers, but individuals may still be identified using additional information. For the government AI assistant, properly anonymized conversation data can fall outside the scope of the GDPR, while pseudonymized data remains personal data because re-identification is still possible.

Resource: GDPR – Recital 26: Not Applicable to Anonymous Data – https://gdpr-info.eu/recitals/no-26/

## Misconception in My Track

## Open Question
