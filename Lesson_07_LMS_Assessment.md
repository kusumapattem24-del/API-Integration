# Lesson 7 Assessment
# Working with Webhooks and Event-Driven APIs

## 1. Assessment Overview

This assessment evaluates your ability to design, configure, test, and validate event-driven workflows using n8n Webhook nodes. You will implement webhook triggers, expose a local n8n instance using ngrok, process incoming payloads, validate webhook security, and test end-to-end webhook execution. The assessment is based on the provided Requirement Document and Implementation Guide.

## 2. Assessment Objective

Demonstrate your ability to build secure, production-ready webhook workflows by configuring Webhook Trigger nodes, using Test and Production URLs, validating HMAC signatures, parsing webhook payloads, and testing workflows with Postman.

## 3. Prerequisites

- Review the Requirement Document before starting the project.
- Review the Implementation Guide for workflow setup.
- Complete Topics 1 through Topic 6.
- Have an active n8n instance.
- Install ngrok (if self-hosting locally) and Postman.

## 4. Assessment Tasks

**Exercise 1 – Configure a Webhook Trigger**
Create and configure a Webhook node with POST method and custom endpoint.

**Exercise 2 – Test Webhook Events**
Use the Test Webhook URL and Postman to send a JSON payload and verify captured headers, query parameters, and body.

**Exercise 3 – Configure Production Webhook**
Activate the workflow and validate the Production Webhook URL.

**Exercise 4 – Implement Webhook Security**
Configure Header Authentication or HMAC signature verification.

**Exercise 5 – Validate Complete Workflow and Prepare Deliverables**
Verify the complete workflow and prepare all required submission artifacts.

## 5. Practical Assessment Checklist

☐ Webhook Trigger node configured
☐ Test Webhook URL validated
☐ Production Webhook activated
☐ ngrok tunnel configured (if applicable)
☐ Payload headers, query parameters, and JSON body captured
☐ Webhook authentication/HMAC configured
☐ Workflow tested successfully
☐ Documentation completed

## 6. Assessment Success Criteria

- Configure Webhook Trigger nodes correctly.
- Differentiate Test and Production Webhook URLs.
- Expose local workflows using ngrok.
- Process incoming webhook payloads.
- Implement webhook security.
- Submit all required deliverables.

## 7. Required Deliverables

| Deliverable | Required |
|---|---|
| Loom/YouTube Demo Video | Mandatory |
| Exported n8n Workflow (.json) or GitHub Repository | Mandatory |
| Description / Additional Comments | Recommended |
| Supporting Documents (PDF/DOCX if applicable) | Optional |

## 8. Submission Guidelines

- A Loom or YouTube video demonstrating webhook configuration, Test and Production URLs, payload capture, security validation, and workflow execution.
- An exported n8n workflow (.json) or a public GitHub repository containing the workflow.
- In the Description field, mention challenges faced, assumptions, limitations, and additional enhancements.

## 9. Final Submission Checklist

☐ Completed all assessment exercises
☐ Verified webhook workflow execution
☐ Exported latest workflow/source code
☐ Uploaded Loom/YouTube demonstration video
☐ Added assessor comments
☐ Reviewed all deliverables before submission

## 10. Important Note

- Before clicking Submit in the LMS, ensure you have provided:
1. A Loom or YouTube video demonstrating the completed webhook workflow.
2. An exported n8n workflow (.json) or public GitHub repository.
3. Additional comments describing challenges, assumptions, limitations, or extra features.
- Submissions without the required demonstration video and source code may be considered incomplete and may not be evaluated.
