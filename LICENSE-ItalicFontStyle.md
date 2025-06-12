# Italic Font Style Got Overlap on Exported PDF

This ticket was opened by the Middleware Team to support Justine Donovan, the Application Developer who is the main developer of the CKEditor application, that are opened on 18th March 2025, with a concern on the export of italic font styles to PDF within CKEditor. The problem is that "whenever we export the italic font style into PDF some of those italic word(s) was got overlap because of the margin or spacing on CSS that we implement". Our team also noted that this overlap issue also tried on CKEditor demo web and also got overlap, suggesting it might be a widespread problem.

Aldona Cupial-Wozniak, a Customer Engagement Coordinator from CKSource, responded confirming that they had reported the issue and passed it over to the CKEditor developers. Conveying urgency from our customer who wanted the exact time when will this issue got fixed in the future, our team followed up this issue in the ticket. Justine Donovan and Namirah Anwar reiterated this urgency whilst asking an estimated timeline for whent this might be addresed and furthermore asking for a rough timeframe for our planning.

Approximately two months after the initial report, Aldona provided an update with a note that "This issue might be challenging due to the impact it might have on other clients and their content" and she also said that it would require more research in the future. While permanent fix was not immediately available, Aldona offered a workaround to patch this problem. The proposed solution involves including a stylesheet in the export to PDF plugin configuration with the following CSS rule:

.ck-content { 
  padding: 1px; 
  }

Aldona explained that this simple addition will prevent the text from being cut-off without affecting the rest of the document in a major way". Despite the additional workaround, the ticket status was subsequently marked as "Solved" and closed for comments.
