---
title: रोल-बेस्ड एक्सेस कण्ट्रोल (RBAC)
id: rbac
date: 2018-04-12
full_link: /docs/reference/access-authn-authz/rbac/
short_description: >
  यह प्राधिकरण निर्णयों का प्रबंधन करता है और ऑपरेटरों को कुबेरनेट्स API के माध्यम से व्यवस्थापक को प्रवेश नीतियों को गतिशील रूप से कॉन्फ़िगर करने की अनुमति मिलती है।
aka:
tags:
  - security
  - fundamental
---

प्राधिकरण निर्णयों का प्रबंधन करता है और ऑपरेटरों को {{< glossary_tooltip text="कुबेरनेट्स API" term_id="kubernetes-api" >}} के माध्यम से व्यवस्थापक को प्रवेश नीतियों को गतिशील रूप से कॉन्फ़िगर करने की अनुमति मिलती है।

<!--more-->

RBAC _roles_ का उपयोग करते हैं, जिसमें अनुमति नियम शामिल हैं, और _role bindings_, जो उपयोगकर्ताओं के एक समूह को भूमिका में परिभाषित अनुमतियाँ प्रदान करते हैं।