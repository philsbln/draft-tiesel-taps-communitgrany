---
title: Communication Units Granularity Considerations for using Transport Diversity or Multiple Paths
abbrev: CommUnitGrany
docname: draft-tiesel-taps-communitgrany-latest
date: 2017-06-01
category: info

ipr: trust200902
area: Transport
workgroup: TAPS Working Group
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: P. S. Tiesel
    name: Philipp S. Tiesel
    organization: Berlin Institute of Technology
    street: Marchstr. 23
    city: Berlin
    country: Germany
    email: philipp@inet.tu-berlin.de
 -
    ins: T. Enghardt
    name: Theresa Enghardt
    organization: Berlin Institute of Technology
    street: Marchstr. 23
    city: Berlin
    country: Germany
    email: theresa@inet.tu-berlin.de

normative:
  RFC2119:

informative:
  RFC7556:

--- abstract

Lorem Ipsum

--- middle

Introduction        {#intro}
============

Today's Internet architecture faces protocol designers and application
developers with an overwhelmingly set of choices. When it comes to 
designing a system that takes advantage of multiple paths, it is not
sufficient to choose a transport protocol but it becomes necessary to
take the various path layer technologies into account that may
interfere with the transport layer.


This document provides an abstract framework to reason about the
composition of multi-path aware systems based on different kinds of
communication units. It discusses the basic building blocks that are
used to compose up a multi-path system in a layering independent
fashion.


Conventions and Definitions
===========================

The words "MUST", "MUST NOT", "SHALL", "SHALL NOT", "SHOULD", and
"MAY" are used in this document. It's not shouting; when these
words are capitalized, they have a special meaning as defined
in {{RFC2119}}.


Abstract Hierarchy of Communication Units
=========================================




Building Blocks of Multi-Path Systems
======================================


Paths vs. Provisioning Domains
==============================

TODO: Discuss difference between Multiple Provisioning Domains {{RFC7556}} or multiple access networks within the same provisioning domain.


Security Considerations {#sec}
=======================



IANA Considerations {#iana}
===================

None





--- back



