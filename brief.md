Version: NAFATH-V1
Your track: Cybersecurity
## Overview

A national digital login service allows citizens to access multiple government services using one account. Building this service requires cooperation between software, artificial intelligence, mobile development, networking, cybersecurity, and data protection. Software standards help verify user identity and manage access. AI can help identify suspicious login activity, while mobile security protects users on their devices. Networking technologies help protect communication, and Cybersecurity controls reduce risks such as phishing and account theft. Data protection practices help ensure citizens’ personal information is handled responsibly. My chosen track is Cybersecurity, which focuses on protecting accounts, authentication processes, and sensitive information.

## Software

OAuth 2.0 and OpenID Connect have different roles in a national digital login service. OpenID Connect helps applications verify a user’s identity during login. OAuth 2.0 allows applications to access protected resources with permission. OpenID Connect is built on OAuth 2.0 and adds identity information. Both protocols can work together to support a digital login system.

Resource: OpenID Connect Core 1.0 - https://openid.net/specs/openid-connect-core-1_0.html

## AI

efore deploying an AI model to detect suspicious logins, the authority should manage risks using the NIST AI Risk Management Framework (AI RMF 1.0). Key risks include false alerts, missed threats, privacy violations, biased decisions, and attacks against the model. The authority should test the model’s accuracy and fairness, protect citizens’ data, document decisions, and monitor performance after deployment. NIST’s four core functions are Govern, Map, Measure, and Manage.

Resource: NIST, AI Risk Management Framework (AI RMF 1.0), 2023: https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf

## Mobile

Android’s runtime permission model restricts access to sensitive data and device features. Apps must declare required permissions, and for dangerous permissions, request the user’s approval at runtime on Android versions that require it. The request should occur when the app needs the feature. Users can deny or revoke permissions, so the login app should work without unnecessary access.

Resource: Android Developers, Request runtime permissions: https://developer.android.com/training/permissions/requesting

## Networking
## Cybersecurity
## Data
## Misconception in My Track
## Open Question
