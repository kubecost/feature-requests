# Issue Guidelines

Issues filed in this repository are specific to the **Kubecost application stack only**. If your issue pertains to the Kubecost Helm chart and not the application, please see the [cost-analyzer-helm-chart repository](https://github.com/kubecost/cost-analyzer-helm-chart).

To help route you to the best location, see some examples of feature requests and bug reports [below](#examples-of-application-requests).

## Examples of Application Requests

Find a couple examples of valid application feature and bug requests below.

### Application Feature Requests

In this feature request, the user is requesting an enhancement in the UI which is provided by the Kubecost application stack. This feature would need to be implemented in the application code and not in any of the packaging or distribution formats.

**Problem Statement**

"It's difficult to understand the breakdown of idle for each ns, workloads, etc when sharing it by cluster and by node."

**Solution Description**

"When sharing idle by cluster or node provide a breakdown of the costs for the ns, workload, etc."

### Examples of Application Bug Reports

The below problem is with the Kubecost API which is a function of the application. This is an example of a valid bug which can be filed in this repository as it is packaging agnostic.

**Problem Statement**

"When i do a request against the Allocation API or simply use the kubecost UI and create a report with a fixed time frame, i dont get consistent values when retrying with the same time frame."

**Expected Behavior**

"I would expect a consistent response."

## Finding the Kubecost version

When reporting a bug with Kubecost, it is imperative to know the version of Kubecost involved. To identify the version, please follow the below steps.

1. Access the Kubecost UI in your browser. You will be taken to the Overview page.
2. Click on the Settings icon in the bottom left side of the screen.
3. The version of Kubecost will be displayed under the **Kubecost info** section of the Settings page. In most cases, the API version and UI version will be identical. This is the version which should be used in a bug report.
