# Architecture Documentation

## Overview
This Tool-Use implements Vaccination Scheduler for Radiology for Healthcare & Life Sciences use cases.

## Components
1. **Case Intake**: Collect, validate and normalize eligibility files from Care Management; attach a runId and timestamp for traceability.
2. **API Discovery**: Execute api discovery phase for the Tool-Use pattern: persist interim state, enforce guardrails, and emit structured JSON results.
3. **Tool Execution**: Execute tool execution phase for the Tool-Use pattern: persist interim state, enforce guardrails, and emit structured JSON results.
4. **Triage**: Triage across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
5. **Intervention**: Intervention across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
6. **Eligibility Match**: Eligibility Match across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
7. **Optimization**: Optimization across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
8. **Documentation**: Documentation across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
9. **Orchestration**: Assemble final payload with status, artifacts, KPIs and audit trail; store to PACS; return response JSON for the client.

## Data Flow
- Input: Case Intake
- Processing: 9 sequential steps
- Output: Orchestration
