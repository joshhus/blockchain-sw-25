---

copyright:
  years: 2019, 2020
lastupdated: "2021-04-07"


keywords: release note, latest changes, Hyperledger Fabric, multicloud

subcollection: blockchain-sw-25

---

{:note: .note}
{:important: .important}
{:tip: .tip}
{:shortdesc: .shortdesc}
{:DomainName: data-hd-keyref="APPDomain"}
{:DomainName: data-hd-keyref="DomainName"}
{:android: data-hd-operatingsystem="android"}
{:api: .ph data-hd-interface='api'}
{:apikey: data-credential-placeholder='apikey'}
{:app_key: data-hd-keyref="app_key"}
{:app_name: data-hd-keyref="app_name"}
{:app_secret: data-hd-keyref="app_secret"}
{:app_url: data-hd-keyref="app_url"}
{:authenticated-content: .authenticated-content}
{:beta: .beta}
{:c#: data-hd-programlang="c#"}
{:cli: .ph data-hd-interface='cli'}
{:codeblock: .codeblock}
{:curl: .ph data-hd-programlang='curl'}
{:deprecated: .deprecated}
{:dotnet-standard: .ph data-hd-programlang='dotnet-standard'}
{:download: .download}
{:external: target="_blank" .external}
{:faq: data-hd-content-type='faq'}
{:fuzzybunny: .ph data-hd-programlang='fuzzybunny'}
{:generic: data-hd-operatingsystem="generic"}
{:generic: data-hd-programlang="generic"}
{:gif: data-image-type='gif'}
{:go: .ph data-hd-programlang='go'}
{:help: data-hd-content-type='help'}
{:hide-dashboard: .hide-dashboard}
{:hide-in-docs: .hide-in-docs}
{:important: .important}
{:ios: data-hd-operatingsystem="ios"}
{:java: .ph data-hd-programlang='java'}
{:java: data-hd-programlang="java"}
{:javascript: .ph data-hd-programlang='javascript'}
{:javascript: data-hd-programlang="javascript"}
{:new_window: target="_blank"}
{:note .note}
{:note: .note}
{:objectc data-hd-programlang="objectc"}
{:org_name: data-hd-keyref="org_name"}
{:php: data-hd-programlang="php"}
{:pre: .pre}
{:preview: .preview}
{:python: .ph data-hd-programlang='python'}
{:python: data-hd-programlang="python"}
{:route: data-hd-keyref="route"}
{:row-headers: .row-headers}
{:ruby: .ph data-hd-programlang='ruby'}
{:ruby: data-hd-programlang="ruby"}
{:runtime: architecture="runtime"}
{:runtimeIcon: .runtimeIcon}
{:runtimeIconList: .runtimeIconList}
{:runtimeLink: .runtimeLink}
{:runtimeTitle: .runtimeTitle}
{:screen: .screen}
{:script: data-hd-video='script'}
{:service: architecture="service"}
{:service_instance_name: data-hd-keyref="service_instance_name"}
{:service_name: data-hd-keyref="service_name"}
{:shortdesc: .shortdesc}
{:space_name: data-hd-keyref="space_name"}
{:step: data-tutorial-type='step'}
{:subsection: outputclass="subsection"}
{:support: data-reuse='support'}
{:swift: .ph data-hd-programlang='swift'}
{:swift: data-hd-programlang="swift"}
{:table: .aria-labeledby="caption"}
{:term: .term}
{:tip: .tip}
{:tooling-url: data-tooling-url-placeholder='tooling-url'}
{:troubleshoot: data-hd-content-type='troubleshoot'}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:tsSymptoms: .tsSymptoms}
{:tutorial: data-hd-content-type='tutorial'}
{:ui: .ph data-hd-interface='ui'}
{:unity: .ph data-hd-programlang='unity'}
{:url: data-credential-placeholder='url'}
{:user_ID: data-hd-keyref="user_ID"}
{:vbnet: .ph data-hd-programlang='vb.net'}
{:video: .video}
 
{:external: target="_blank" .external}

# Release notes
{: #release-notes-saas-20}

<div style="background-color: #6fdc8c; padding-left: 20px; padding-right: 20px; border-bottom: 4px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 20px;">
    <strong>Important: You are not looking at the latest product documentation.  Make sure you are reading the documentation that matches the version of the software that you are using. Switch to product version </strong>
    <a href="/docs/blockchain-sw?topic=blockchain-sw-release-notes-saas-20">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-release-notes-saas-20">2.1.3</a>, 2.5, 
    <a href="/docs/blockchain-sw-251?topic=blockchain-sw-251-release-notes-saas-20">2.5.1</a>,
    <a href="/docs/blockchain-sw-252?topic=blockchain-sw-252-release-notes-saas-20">2.5.2 (latest)</a>
    </p>
</div>


Use these release notes that are grouped by date to learn about the latest changes to {{site.data.keyword.blockchainfull}} Platform 2.5.
{:shortdesc}

See [Installing patches](/docs/blockchain-sw-25?topic=blockchain-sw-25-console-icp-manage#ibp-console-manage-patch) for instructions on how to apply patches to your existing nodes. Patches are cumulative. This means that if multiple patches, for example `1.4.7-0` and `1.4.7-1`, are available for a node, you should always select the latest patch, `1.4.7-1` in this case, wherever possible because it includes the fixes from the previous patches as well.

## 1 Oct 2020
{: #10-01-2020}

**CA, Peer, and ordering node patch 1.4.7-3, 2.1.1-3**

Miscellaneous bug fixes and security patches.  

## 9 Sept 2020
{: #08-25-2020}

**CA, Peer, and ordering node patch 1.4.7-2, 2.1.1-2**

Miscellaneous bug fixes and security patches.  

Certificate expiration dates have been added throughout the component details, making it easier to monitor and track certificate expiration dates. See [Certificate Management](/docs/blockchain-sw-25?topic=blockchain-sw-25-cert-mgmt) to learn more about your responsibilities. In addition, it is now possible to enable Node OU support for your MSPs and channels through the console. Read more about [Node OU support](/docs/blockchain-sw-25?topic=blockchain-sw-25-cert-mgmt#cert-mgmt-nodeou), why this is important, and how to simplify certificate renewal for the MSPs on your network.


## 14 July 2020
{: #07-14-2020}

**CA, Peer, and ordering node patch 1.4.7-1, 2.1.1-1**  

Miscellaneous bug fixes and security patches.

Users who installed the {{site.data.keyword.blockchainfull_notm}} Platform 2.5 before July 14, 2020 should install the [2.5 fix pack](/docs/blockchain-sw-25?topic=blockchain-sw-25-install-fixpack#install-fixpack). If you install the {{site.data.keyword.blockchainfull_notm}} Platform 2.5 after July 14, 2020, the platform will contain all the bug fixes and improvements that are provided by the fix pack, and you do not need to apply the fix pack.


## 18 June 2020
{: #06-18-2020}

**Peer and ordering node patch 1.4.7-0**

**{{site.data.keyword.IBM_notm}} considers this a critical patch that you should apply at your nearest opportunity.** Not applying this patch risks being susceptible to a data integrity issue if you experience a CouchDB or underlying storage crash on your peer. This patch updates the CouchDB `delayed_commits` configuration property to false. The prior setting could cause the peer's CouchDB database to be in an inconsistent state in the event of a CouchDB or underlying storage system crash. The new setting ensures that a peer will recover from crashes in a consistent state. As always, it is recommended to utilize an endorsement policy that requires multiple peers to endorse a transaction, to avoid an inconsistency from a single peer from impacting the overall blockchain network state.  

**To be certain that your peers have no database corruption**, you should reprovision your peers.

Miscellaneous bug fixes and security patches.

### Fabric peer and ordering node images
{: #06-18-2020-images}

The platform introduces the capability to deploy new peer and ordering nodes based on either Hyperledger Fabric v1.4 or v2.x. Deploying peer and ordering nodes with the latest Fabric images is recommended to ensure that you have access to current Fabric fixes and features. It is not currently possible to migrate existing nodes to Fabric v2 images.

### Elimination of Docker daemon dependency
{: #06-18-2020-docker}

Leveraging the Fabric v2 **external chaincode launcher** capability, when you deploy a peer based on the Fabric v2.1.1 image, smart contracts are deployed into their own pod rather than inside a container on the peer pod.

### Multizone-capable storage
{: #06-18-2020-Multizone}

If your Kubernetes cluster is configured to use multizone-capable storage, new peer and ordering nodes can be deployed that leverage multizone storage, effectively extending their high availability across cluster zones.See [Multizone-capable Storage](/docs/blockchain-sw-25?topic=blockchain-sw-25-ibp-console-ha#ibp-console-ha-multi-zone-storage) for more information.

### Kubernetes version upgrade
{: #06-18-2020-k8s}

{{site.data.keyword.blockchainfull_notm}} Platform requires **Kubernetes v1.15 - v1.18**. If your existing Kubernetes cluster is running v1.14 or lower, you need to upgrade your cluster before you can update your existing blockchain components to this latest release.
