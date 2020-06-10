---

copyright:
  years: 2018, 2020
lastupdated: "2020-06-10"

keywords: OpenShift, IBM Blockchain Platform console, deploy, resource requirements, storage, parameters

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

# Removing your deployment
{: #Removing-ocp}

<div style="background-color: #f4f4f4; padding-left: 20px; border-bottom: 2px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 10px;">
    <strong>Running a different version of IBM Blockchain Platform?</strong> Switch to version
    <a href="https://cloud.ibm.com/docs/blockchain-sw?topic=blockchain-sw-Removing-ocp">2.1.2</a>,
    <a href="https://cloud.ibm.com/docs/blockchain-sw-213?topic=blockchain-sw-213-Removing-ocp">2.1.3</a>
    </p>
</div>


The {{site.data.keyword.blockchainfull}} Platform operator automatically restarts your blockchain nodes or your console if they stop or crash. As a result, you cannot manually remove your blockchain components by manually deleting their pods. Use the following steps to remove the {{site.data.keyword.blockchainfull_notm}} Platform from your OpenShift cluster. You must follow these steps for each OpenShift project that you create.

If your organization is participating in an active blockchain network, you should remove your organization from the network before you remove your deployment. See [Removing an organization](/docs/blockchain-sw-25?topic=blockchain-sw-25-ibp-console-organizations#console-organizations-remove) for more details.
{: important}

## Step one: Use the console to delete your blockchain nodes
{: #Removing-ocp-step-one}

{[pg-delete-components-ocp.md]}

## Step two: Delete the {{site.data.keyword.blockchainfull_notm}} Platform operator
{: #Removing-ocp-step-two}

You can use the OpenShift CLI to remove the {{site.data.keyword.blockchainfull_notm}} Platform operator. When the operator is no longer running on your cluster, you can delete the console and any remaining nodes without them being restarted.

1. Log in to your cluster by using the OpenShift CLI. If you are using the OpenShift web console, you can log in to your cluster by clicking the dropdown menu in the upper right corner and then clicking **Copy Login Command**. Paste the copied command in your command terminal.

2. Use the CLI to switch to the OpenShift project that you created for your blockchain network:

  ```
  oc project <PROJECT_NAME>
  ```
  {:codeblock}

3. You can remove the operator deployment using the OpenShift CLI:

  ```
  kubectl delete deployment ibp-operator
  ```
  {:codeblock}

## Step Three: Delete the {{site.data.keyword.blockchainfull_notm}} Platform console
{: #Removing-ocp-step-three}

After you remove the operator, you can then delete the console without it being restarted. When you are logged in to your cluster and are operating from your project, you can delete the console by issuing the following command:

```
kubectl delete ibpconsole --all
```
{:codeblock}

## Step Four: Remove policies and secrets
{: #Removing-ocp-step-four}

If you are done working with the {{site.data.keyword.blockchainfull_notm}} Platform on your OpenShift cluster, you can delete your OpenShift project.

```
oc delete project <PROJECT_NAME>
```
{:codeblock}

This command deletes any remaining blockchain nodes that are running on the project, in addition to your console and the {{site.data.keyword.blockchainfull_notm}} Platform operator.
{:important}

Deleting the OpenShift project removes the {{site.data.keyword.blockchainfull_notm}} Platform Security Context Constraint, clusterRole, and ClusterRoleBinding that you applied. It deletes the secrets that you created. You cannot undo this action. As a result, deleting your project is not recommended unless you are not going to deploy another instance of the platform.
