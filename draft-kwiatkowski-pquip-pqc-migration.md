---
title: Guidance for migration to Post-Quantum schemes
abbrev: PQUIP-MIGRATION
category: info

docname: draft-kwiatkowski-pquip-pqc-migration-latest
submissiontype: IETF
number:
date:
stand_alone: yes
consensus: true
v: 3
ipr: trust200902
area: "Security"
workgroup: "Post-Quantum Use In Protocols"
keyword:
 - post-quantum
venue:
  group: "Post-Quantum Use In Protocols"
  type: "Working Group"
  mail: "pquip@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/pqc/"

author:
  - ins: K. Kwiatkowski
    name: Kris Kwiatkowski
    email: kris@amongbytes.com

normative:
  rfc7748:

informative:
  tlsiana: I-D.ietf-tls-rfc8447bis

--- abstract

This document provides guidance for the migration to post-quantum cryptography (PQC) in internet protocols. It outlines the challenges and considerations that protocol designers and implementers should take into account when transitioning from classical cryptographic algorithms to PQC algorithms, which are designed to be secure against quantum computer attacks.

It is intended for cryptographic protocol designers within the IETF community, as well as technology developers and implementers responsible for deploying PQC standards.

--- middle

# Introduction

Advances in quantum computing pose a growing threat to systems that rely on widely deployed internet security protocols, which use cryptographic mechanisms to secure communications, verify authenticity, and protect sensitive data at rest and in transit. While a cryptographically relevant quantum computer (CRQC) capable of breaking these protections may still be years away, initiating the transition to post-quantum cryptography (PQC) now is essential to ensure adequate time for planning and implementation.

# Awarness



# Key exchange

# Digital signatures

# FIPS

# Infrastructure costs

# Anti-patterns

# Conventions and Definitions
{::boilerplate bcp14-tagged}

# Security Considerations

# IANA Considerations

--- back
