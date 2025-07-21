# Phase 3 – EventBridge to SNS Alerting

This phase implements real-time alerting by connecting GuardDuty findings to SNS via EventBridge.

## 🔁 Workflow

1. EventBridge rule matches GuardDuty findings
2. Rule triggers an SNS topic
3. SNS sends alert to subscribed email

## ✅ Outcome

Real-time detection and alerting pipeline tested and verified successfully.