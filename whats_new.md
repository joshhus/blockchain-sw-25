---

copyright:
  years: 2017, 2020
lastupdated: "2021-04-07"

keywords: IBM Blockchain Platform, release, new features, multicloud

subcollection: blockchain-sw-25

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
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
 
{:note: .note}
{:important: .important}
{:tip: .tip}
{:external: target="_blank" .external}


# What's new
{: #whats-new}

<div style="background-color: #6fdc8c; padding-left: 20px; padding-right: 20px; border-bottom: 4px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 20px;">
    <strong>Important: You are not looking at the latest product documentation.  Make sure you are reading the documentation that matches the version of the software that you are using. Switch to product version </strong>
    <a href="/docs/blockchain-sw?topic=blockchain-sw-whats-new">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-whats-new">2.1.3</a>, 2.5,
    <a href="/docs/blockchain-sw-251?topic=blockchain-sw-251-whats-new">2.5.1</a>,
    <a href="/docs/blockchain-sw-252?topic=blockchain-sw-252-whats-new">2.5.2 (latest)</a>
    </p>
</div>

## March 29, 2021
{: #whats-new-03-29-2021}
{{site.data.keyword.blockchainfull_notm}} Platform 2.5.2 is now available with support for:

- For customers who want to use openCryptoki Hardware Security Module (HSM) on s390x, the platform now supports configuration of HSM with a daemon. For more information, see [Configure an HSM daemon](https://cloud.ibm.com/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-adv-deployment#ibp-console-adv-deployment-hsm-daemon).

## October 30, 2020
{: #whats-new-10-20-2020}

{{site.data.keyword.blockchainfull}} Platform 2.5.1 is now available.

{{site.data.keyword.blockchainfull_notm}} Platform 2.5.1 now supports the Fabric v2.x smart contract lifecycle that allows for decentralized governance of smart contract definitions on a channel. The platform has been updated to support Kubernetes v1.16-v1.18 and OpenShift container Platform 4.5.

**Support for Fabric v2.x lifecycle**

The series of processes around installing, managing, and using smart contracts, collectively known as the "lifecycle" of the smart contract, has been updated. This new lifecycle allows organizations to collaborate in the channel-level decision making process regarding smart contracts, eliminate the need for smart contract fingerprint matches, and allow smart contracts to be written with only the code relevant to an organization's business role.

The {{site.data.keyword.IBM_notm}} Developer tooling has been updated to support generation of Fabric v2.x smart contract packages as well as testing smart contracts by using the new lifecycle process. Learn more about how to [deploy a smart contract using Fabric v2.x](/docs/blockchain-sw-251?topic=blockchain-sw-251-ibp-console-smart-contracts-v2) and [how to write powerful smart contracts](/docs/blockchain-sw-251?topic=blockchain-sw-251-write-powerful-smart-contracts) that leverage the new governance.

**New process for enabling Hardware Security Module (HSM) support**

A new process for configuring an HSM to work with your blockchain nodes is available and offers faster performance over the use of the existing HSM PKCS #11 proxy which is now deprecated. Current customers who are using the PKCS #11 proxy should check out the new process in the [Advanced deployment](/docs/blockchain-sw-251?topic=blockchain-sw-251-ibp-console-adv-deployment#ibp-console-adv-deployment-hsm-build-docker) options.

**Ability to upgrade existing nodes and channel application capability to Fabric v2.x**

You continue to have the option to select the Fabric v1.4 or v2.x image when creating your CAs, peers, and ordering nodes. However, you now have the ability to upgrade your existing nodes that are running Fabric v1.4.x to the Fabric v2.x image. If you have peers using the Fabric v1.4.x image, you must upgrade your nodes and update your channel capabilities to take advantage of the new smart contract lifecycle.

For information about upgrading nodes, check out [Upgrading to a new version of Fabric](/docs/blockchain-sw-251?topic=blockchain-sw-251-ibp-console-govern-components#ibp-console-govern-components-upgrade). For information about updating the capabilities of your channels, check out [Capabilities](/docs/blockchain-sw-251?topic=blockchain-sw-251-ibp-console-govern#ibp-console-govern-capabilities).

**Enhancements to the certificate renewal process**

Because all actions on a blockchain network depend on the existence of valid and verifiable certificates, renewing certificate is vital to avoiding network outages. To streamline the certificate renewal process, the console now allows you to renew your CA TLS certificate, and peer and ordering node enrollment and TLS certificates. While it is preferable to renew certificates before they expire, it is possible to restore components whose certificates have already expired in many cases. Learn more about the new options in [Certificate management](/docs/blockchain-sw-251?topic=blockchain-sw-251-cert-mgmt#cert-mgmt-cert-types).

If you have an existing {{site.data.keyword.blockchainfull_notm}} Platform v2.1.x or 2.5.0 deployment and are interested in upgrading to {{site.data.keyword.blockchainfull_notm}} Platform 2.5.1, see the following topics:
- [Upgrading your console and components on the OpenShift Container Platform](/docs/blockchain-sw-251?topic=blockchain-sw-251-upgrade-ocp)
- [Upgrading your console and components on Kubernetes](/docs/blockchain-sw-251?topic=blockchain-sw-251-upgrade-k8)
- [Upgrading the {{site.data.keyword.blockchainfull_notm}} images](/docs/blockchain-sw-251?topic=blockchain-sw-251-blockchain-images#blockchain-images-upgrade)

See the [Release notes](/docs/blockchain-sw-251?topic=blockchain-sw-251-release-notes-saas-20#10-20-2020) for more details on the new features that are included in this release.

## August 27, 2020
{: #whats-new-08-19-2020}

The {{site.data.keyword.blockchainfull_notm}} Platform can now be deployed onto OpenShift clusters from the Red Hat Marketplace, an open cloud catalog that makes it easier to discover and access certified software. Red Hat certified {{site.data.keyword.blockchainfull_notm}} Platform operator images are available in the marketplace and accessible from your OpenShift web console. This new deployment option is immediately available to deploy on any Red Hat OpenShift 4.3+ cluster, and provides a fast, integrated experience for deploying the blockchain console that can be used to create Certificate Authorities (CAs), peers, and ordering nodes, in the public cloud. See [Deploying {{site.data.keyword.blockchainfull_notm}} 2.5 from Red Hat Marketplace](/docs/blockchain-sw-25?topic=blockchain-sw-25-deploy-ocp-rhm) for more information about this streamlined deployment option that is provided as an alternative to the existing [manual deployment](/docs/blockchain-sw-25?topic=blockchain-sw-25-deploy-ocp) steps.


## June 18, 2020
{: #whats-new-06-18-2020}


{{site.data.keyword.blockchainfull}} Platform 2.5 is now available.


{{site.data.keyword.blockchainfull_notm}} Platform 2.5 provides tighter integration with Red Hat solutions, including additional integration with Red Hat OpenShift 4.3 and support for Red Hat CodeReady Workspaces. This latest release also makes available a set of Ansible Content Collections to help accelerate the deployment of blockchain solutions.

**IBM Blockchain Platform Ansible Playbooks**  

The {{site.data.keyword.blockchainfull_notm}} Platform 2.5 improvements are designed to enable enterprises to launch production blockchain networks faster. This release helps organizations accelerate deployment through support of Ansible, an open source tool that automates provisioning, configuration management, and application deployment. **Ansible Content Collections** are packages of modules, plug-ins, and other Ansible content that automate these processes. The platform has published a set of Ansible Content Collections to help organizations deploy blockchain components and networks with greater speed. See [Getting started with Ansible playbooks on the {{site.data.keyword.blockchainfull_notm}} Platform](/docs/blockchain-sw-25?topic=blockchain-sw-25-ansible) to learn more.

**Red Hat CodeReady Workspaces**  

The platform expands its developer tool ecosystem with **Red Hat CodeReady Workspaces**, that help organizations speed up and simplify the setup of blockchain development environments. Red Hat CodeReady Workspaces provide a preconfigured and shared runtime environment that enables cloud-native blockchain development to be performed across teams. Red Hat CodeReady Workspaces offer strong security and adhere to enterprise-grade compliance for cloud-native development. Read about the [benefits of CodeReady Workspaces](/docs/blockchain-sw-25?topic=blockchain-sw-25-develop-vscode#develop-vscode-crw-why) to learn more.

**Hyperledger Fabric 2.0 images**

This release also includes improved usability and security by using **Hyperledger Fabric v2** and introduces the capability to deploy new peer and ordering nodes based on either Hyperledger Fabric v1.4.7 or v2.1.1. While all of the new Fabric v2 capabilities are not yet available on the platform, when you deploy a peer based on the Fabric v2.1.1 image, smart contracts are deployed into their own pod rather than inside a container on the peer pod, eliminating the dependency on the Docker daemon. Deploying peer and ordering nodes with the Fabric v2.x images is recommended to ensure that going forward you have access to the latest Fabric fixes and features. It is not currently possible to migrate existing nodes to Fabric 2.1.1 images.  The ordering service requires that all ordering nodes be running either Fabric v1.4.x or Fabric 2.x. Mixing ordering nodes with these different Fabric versions can introduce problems when attempting to update the consenter set. Peers, on the other hand can coexist on a channel even when they run different Fabric levels, as long as the channel application capability is not higher than the lowest peer Fabric version.


If you have an existing {{site.data.keyword.blockchainfull_notm}} Platform v2.1.x deployment and are interested in upgrading to {{site.data.keyword.blockchainfull_notm}} Platform 2.5, see the following topics:
- [Upgrading your console and components on the OpenShift Container Platform](/docs/blockchain-sw-25?topic=blockchain-sw-25-upgrade-ocp)
- [Upgrading your console and components on Kubernetes](/docs/blockchain-sw-25?topic=blockchain-sw-25-upgrade-k8)
- [Upgrading the {{site.data.keyword.blockchainfull_notm}} images](/docs/blockchain-sw-25?topic=blockchain-sw-25-blockchain-images#blockchain-images-upgrade)



See the [Release notes](/docs/blockchain-sw-25?topic=blockchain-sw-25-release-notes-saas-20#06-18-2020) for more details on the new features that are included in this release.
