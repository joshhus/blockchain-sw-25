---

copyright:
  years: 2019, 2020
lastupdated: "2020-06-18"


keywords: release note, latest changes, Hyperledger Fabric

subcollection: blockchain-sw-25

---

{:note: .note}
{:important: .important}
{:tip: .tip}
{:shortdesc: .shortdesc}
{:pre: .pre}
{:external: target="_blank" .external}

# Release notes
{: #release-notes-saas-20}

<div style="background-color: #f4f4f4; padding-left: 20px; border-bottom: 2px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 10px;">
    <strong>Running a different version of IBM Blockchain Platform?</strong> Switch to version
    <a href="https://cloud.ibm.com/docs/blockchain-sw?topic=blockchain-sw-release-notes-saas-20">2.1.2</a>,
    <a href="https://cloud.ibm.com/docs/blockchain-sw-213?topic=blockchain-sw-213-release-notes-saas-20">2.1.3</a>
    </p>
</div>


Use these release notes that are grouped by date to learn about the latest changes to {{site.data.keyword.blockchainfull}} Platform 2.5.
{:shortdesc}

See [Installing patches](/docs/blockchain-sw-25?topic=blockchain-sw-25-console-icp-manage#ibp-console-manage-patch) for instructions on how to apply patches to your existing nodes.

## 20 May 2020
{: #05-20-2020}

**CA, peer, and ordering node patch 1.4.6-2**

Miscellaneous bug fixes and security patches.



### Support for Intermediate Certificate Authorities (CAs)
{: #05-20-2020-ICA}

You now have the option to configure an intermediate CA using the console or APIs to override the default CA settings. See the tutorial on [Creating an intermediate Certificate Authority](/docs/blockchain-sw-25?topic=blockchain-sw-25-ibp-ica) to learn more.

### Updated connection profile
{: #05-20-2020-connx-profile}

The generated connection profile that client applications use to connect to the network has been streamlined and is now downloadable from the **Organizations** tab. See [Downloading a connection profile](/docs/blockchain-sw-25?topic=blockchain-sw-25-ibp-console-organizations#ibp-console-organizations-connx-profile) to learn how.

Users who installed the {{site.data.keyword.blockchainfull_notm}} Platform v2.1.3 before May 20, 2020 should install the [v2.1.3 Fix Pack](/docs/blockchain-sw-25?topic=blockchain-sw-25-install-fixpack#install-fixpack). If you installed the {{site.data.keyword.blockchainfull_notm}} Platform v2.1.3 after May 20, 2020, the platform will contain all the bug fixes and improvements that are provided by the Fix Pack, and you do not need to apply the Fix Pack.

