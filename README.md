**Automated Regulatory Document Compliance Analysis**

  This project aims to create an automated system that helps check regulatory documents for compliance in medical device and pharmaceutical development. The system uses Python to process data, fill missing information, calculate compliance scores, and identify areas where documents may not meet regulations.

**Project Goals**

  1. *Automate Document Review:* Process large sets of regulatory documents quickly and accurately to check for compliance.

  2. *Handle Real-World Challenges:* Work with datasets that include missing information, text descriptions, and complex patterns like real-life regulatory data.

  3. *Generate Insights:* Identify non-compliant documents, determine possible root causes, and provide actionable recommendations.

  4. *Scalable and Flexible:* Build a system that can handle different types of regulatory documents and large volumes of data.

**Dataset**

  The dataset includes the following fields:
  1. *Document_ID:* Unique identifier for each document
  2. *Design_Input:* Description of the design input or reason for recall
  3. *Risk_Assessment:* Low / Medium / High risk level
  4. *Compliance_Score:* Initial numeric score (40–100)
  5. *Critical_Issues:* Count of issues like injury, defect, or contamination
  6. *Last_Reviewed:* Date of last review or event
  7. *Composite_Compliance_Score:* Combined score based on risk, compliance, and issues
