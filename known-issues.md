---

copyright:
  years: 2019, 2020
lastupdated: "2020-10-30"

keywords: catalina, chrome, external CA, TLS, orderer, error, multicloud

subcollection: blockchain-sw-25

---

{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:note: .note}
{:important: .important}
{:tip: .tip}
{:pre: .pre}

# Known issues
{: #sw-known-issues}

This page describes known issues that you might encounter when you use {{site.data.keyword.blockchainfull_notm}} Platform 2.5.
{:shortdesc}

<div style="background-color: #6fdc8c; padding-left: 20px; padding-right: 20px; border-bottom: 4px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 20px;">
    <strong>Important: You are not looking at the latest product documentation.  Make sure you are reading the documentation that matches the version of the software that you are using. Switch to product version </strong>
    <a href="/docs/blockchain-sw?topic=blockchain-sw-sw-known-issues">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-sw-known-issues">2.1.3</a>,
    <a href="/docs/blockchain-sw-251?topic=blockchain-sw-251-sw-known-issues">2.5.1 (latest)</a>
    </p>
</div>




## Smart contract instantiation timeout
{: #sw-known-issues-instantiation-timeout}

When running the {{site.data.keyword.blockchainfull}} Platform on s390x architecture, it is possible that Node.js smart contract instantiation can fail. Customers should wait for five minutes after the failure occurs and then retry the instantiation again. It will then work successfully on the subsequent attempt.
