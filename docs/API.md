# API Documentation

## Endpoints
### Case Intake
- **Description**: Collect, validate and normalize eligibility files from Care Management; attach a runId and timestamp for traceability.
- **Type**: Processing

### API Discovery
- **Description**: Execute api discovery phase for the Tool-Use pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: HTTP Request

### Tool Execution
- **Description**: Execute tool execution phase for the Tool-Use pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Triage
- **Description**: Triage across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Intervention
- **Description**: Intervention across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Eligibility Match
- **Description**: Eligibility Match across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Optimization
- **Description**: Optimization across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Documentation
- **Description**: Documentation across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Orchestration
- **Description**: Assemble final payload with status, artifacts, KPIs and audit trail; store to PACS; return response JSON for the client.
- **Type**: Processing
