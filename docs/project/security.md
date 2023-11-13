# Security

Security is a central concern in the whole XCP-ng project.

We are using Xen as our core hypervisor engine, which is a huge collaboration project with security as core value. On top of that, we are closely monitoring all security releases from Citrix Hypervisor to be able to provide critical patches very fast too.

Because XCP-ng is made of a lot of various components, we are relying on multiple sources to improve the security and fixing flaws.

## 🐼 Xen Project security

XCP-ng project is member of the Xen Predisclosure list since 2018, which is including a lot of huge cloud players, but also companies working in critical IT security, industries and so on. The whole list is public and [available here](https://xenproject.org/developers/security-policy/#organizations-on-the-pre-disclosure-list), where you can see our name.

<div style={{textAlign: 'center'}}>
![](../../assets/img/xen_logo.png)
</div>

We strongly suggest that you go read the [Xen Security Policy](https://xenproject.org/developers/security-policy/) web page. At this time, it's one of the best Open Source security processes, with very clear documentation and actions to make. **This is one of the big reasons Xen is trusted in the IT security world**.

You can also see the change history with dates of each organization added into it.

A quick recap of the key steps involved in this security process:

* **Reporting**: Vulnerabilities in Xen Project software should be reported via email to security@xenproject.org.
* **Notification and Negotiation**: The Hypervisor team, upon becoming aware of a problem, notifies the security team. If the vulnerability isn't public, an embargo date and disclosure schedule are negotiated with the discoverer.
* **CVE Number and Advisory Preparation**: A CVE number is acquired and an advisory is prepared, including determining affected systems and the vulnerability's impact.
* **Advisory Pre-Release**: If the issue is under embargo, an advisory, including patches, is sent to the Xen security pre-disclosure list.
* **Public Release**: On the embargo date, the advisory is published, and updates are pushed to public revision control trees.
* **Updates and Amendments**: If new information or patches are available, an amended advisory may be issued.
* **Post-Embargo Transparency**: Decisions made during the embargo period are disclosed post-embargo for transparency and future guidance

### XSA

XSAs are "Xen Security Advisory". They are -in general- linked to a CVE. You can see the list of all XSAs at this place: [https://xenbits.xen.org/xsa/](https://xenbits.xen.org/xsa/)

<div style={{textAlign: 'center'}}>
![](../../assets/img/xenpanda.png)
</div>

## 🚀 Platform security

XCP-ng code base is close to Citrix Hypervisor, and for that reason, we are integrating Citrix security patches very quickly into XCP-ng. We are also posting very often updates and explanation on each security patches available. You can see this list at this place: [https://xcp-ng.org/blog/tag/security/](https://xcp-ng.org/blog/tag/security/)

However, it's more and more plausible that flaws might be discovered first on XCP-ng instead of Citrix Hypervisor. In that case, please see below.

## 🔒 Report a security flaw

To ensure an efficient security process for XCP-ng, we are open to security reports with our dedicated email: security at this domain name.