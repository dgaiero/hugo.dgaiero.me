---
title: "Fault Identification and Removal Proof-of-Concept"
date: 2020-09-15T11:30:03+00:00
weight: 1
aliases: ['/fault-id']
tags: ['simulink', 'fault identification']
author: "Me"
showToc: true
TocOpen: false
draft: true
hidemeta: false
disableShare: false
cover:
  image: '/images/fault-tolerance/simulink.png'
  alt: 'Simulink Block Diagram'
  caption: 'Fault Identification and Removal Proof of Concept'
  relative: false
comments: false
---

> Certain portions of the background were co-authored by Nicholas Serres.

## Overview

Faults in image sensors can lead to a large drop in image reliability and quality. Image sensors are one of the most susceptible components to faults, and is one of the most critical components in a camera system. This paper explores fault detection and correction of an image sensor by analyzing a sequence of frames from the camera to identify permanent faults and correct both permanent and transient faults. This paper is focused on applications in extreme environments, but applies to wider fields.

## Introduction

In this paper the effectiveness of detecting and correcting radiation-induced errors in an image sensor is explored. This provides an alternative on past methods by correcting and detecting faults in the image processing module, rather than a hardware level redesign. While using software to mitigate the effects of radiation on sensors is not a permanent solution, the benefits of significant reduced costs and development make this solution  appealing for non-critical applications. This project targets uses in control cameras at a radiation plants or other radiation intensive conditions where fault mitigation is desired. This will allow systems that use cameras in these conditions to operate with higher reliability and provide higher fidelity imagery despite the operating conditions of the cameras. Additionally, this solution provides enhanced reporting to the end user, unlike traditional image processing techniques.

[Click here to interact with the Simulink Model](/fault-id-simulink/webview.html)

<!-- I have more [^1] to say.

[^1]: Footnote example. -->
