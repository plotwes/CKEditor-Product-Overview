# CKEditor-Product-Overview
![CKEditor 5](https://ckeditor.com/blog/CKEditor-5-v10.0.0-the-future-of-rich-text-editing-looks-stable/feature.jpg)


## Overview
CKEditor is a modern JavaScript-based text editor which was written from scratch in TypeScript and support custom configurations or plug-ins. This product is currently going through a constant development staging phase, starting from their Q1 - Q4 timeline of development at the start of the year 2025.

![Features of CKEditor 5](https://raw.githubusercontent.com/ckeditor/ckeditor5/master/docs/assets/img/CKEditor-5.png)

CKEditor was referred by InfraCom Tech. to Bank Indonesia because it's flexibility that can support many feature request, such as custom formatting, advanced content editing, document conversion, etc. (Ref. to: [CKEditor 5 features overview | CKEditor 5 Documentation](https://ckeditor.com/docs/ckeditor5/latest/features/index.html))


## InfraCom Tech. Middleware Team
In its development, ICT acts as the main party that implements the development of CKEditor application in accordance with the direction of Bank Indonesia, until the end when the application is finished and implemented on Bank Indonesia's internal server. On behalf of this ongoing text editor product development, ICT consists of different divisions, one of which is the Middleware Team that are assigned as the Technical Consultant for the development stages.

Several members of the Middleware Team who are in charge and responsible for supporting the development of this text editor application, includes:
- **Namirah Anwar** - Middleware Engineer (PIC)
- **Gregorio Manoeroe** - Middleware Engineer

The assigned Middleware team has the main task to perform daily monitoring on the **Argo CD** for the application's pipeline health check, and checking the containers log on **Red Hat OpenShift** to track the root of the problem if there was a warning within the Cluster, which is Nodes, Pods, Storage Classes, and the Cluster's Recent Event (at the DRC, DC1, and DC2 evironments). This activities is held regularly to see how the application changes before and also after the development staging is held regularly, which is useful for minimizing failures by analyzing the logs regularly which will help the Root Cause Analysis (RCA) process if there is problems or issues that suddenly appears and also helped maintaining system stability.

In addition, the Middleware team is also tasked with assisting the activities of the Application Dev team to resolve issues that are being faced, for instance in assisting the deployment process, checking for bugs and debugging, following-up on issues found to the CKEditor Support Team in charge as the principal by opening tickets (Ref. to: [CKEditor Ecosystem Help Center](https://support.ckeditor.com/hc/en-us)), and conducting performance with product testing after the code deployment process takes place.


## CKEditor's Support Ticket - Middleware Team
Throughout the development staging, our team have submitted a numerous amount of support for other division, especially Application Dev team. Because the product of CKEditor is still under the development within the 2025 timeline at staging phase, there is still a lot of problem that are circling within the CKEditor Ecosystem. In order to submit an advanced needs such as support around the CKEditor integration, our team have to **submit a support ticket** so that we can get access to CKEditor core developers through Assistance Package or Custom Development services. (Ref. to: [How do I submit a support request? – CKEditor Ecosystem Help Center](https://support.ckeditor.com/hc/en-us/articles/115002476745-How-do-I-submit-a-support-request))

![CKEditor's Problem](https://ckeditor.com/assets/images/illustration/ck4-support-banner.png)

For the detailed explanation of the Middleware team's role in assisting the development of CKEditor application, there are several tickets that are the *Point of Focus* in this stage, includes:
- [[Issue With PDF Preview - Page Break Incorrect]]
- [[Ruler Plugin Issue]]
- [[Issue With Numbered List Not Changing Font Size in CKEditor]]
- [[Follow-up on Bug - Overflow Image Issue While Exporting PDF]]
- [[Inquiry Regarding Image Insert Behavior and Automatic Sizing]]
- [[Italic Font Style Got Overlap on Exported PDF]]
