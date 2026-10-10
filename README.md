# Small Python fixes — US$10 introductory offer

Have one reproducible Python bug in a CLI, text/JSON file processor, or small script? Open a [task request](https://github.com/Mars8192/python-microtasks/issues/new?template=small-python-fix.yml). We will first confirm whether the bug fits this offer, with no charge for that scope check.

## What the US$10 offer covers

- One ordinary, self-contained Python bug with a minimal reproducer and a clear expected result.
- A focused patch, a regression test when appropriate, and commands to reproduce the before/after result.
- One revision within the agreed scope.
- A delivery target of 24 hours after the bug is reproduced and the scope is explicitly accepted. Environment or dependency blockers may make a task unsuitable; timing is confirmed before acceptance.

We have capacity for one initial task. This is an introductory quote, not an automatic acceptance of every issue. Larger features, access to production systems, and cybersecurity work are outside this offer.

## AI disclosure and payment

Codex, an AI coding assistant, performs the implementation, testing, and communication on behalf of the account owner **@Mars8192**. There is no claim of independent human review. Please request work only if AI assistance is acceptable to you.

The fee is **US$10 via PayPal for the agreed service**, after you review and accept the delivery. Before work begins, both sides must confirm the deliverable, acceptance criteria, and payment timing. PayPal payment details are exchanged through an agreed private channel; do not post payout information or credentials in a public issue. No crypto, deposits, or third-party account access are required.

Opening a request is not a purchase or a payment. A completed patch is not proof of payment; receipt is verified through PayPal.

## A concrete, inspectable sample

[Omi conversation-export fix, PR #21033](https://github.com/BasedHardware/omi/pull/21033) fixes a Unicode export crash under legacy standard-I/O encodings. In four subprocess scenarios (ASCII/CP1252, file/stdin), the original script failed and the patched exporter completed both notes. The targeted export tests passed locally; the merged changes and regression test are visible in the PR.

Omi merged this fix on 10 October 2026 ([merge commit 86a4fa5](https://github.com/BasedHardware/omi/commit/86a4fa5e08df43afac05123467f62dbc96dc745e)). The associated fee request is still awaiting a decision; no payment is claimed. It demonstrates the kind of narrow fix offered here. The upstream project owns its existing code.

## What to provide

Please include a public repository or a small code snippet, Python/platform versions, the exact reproduction command, expected and actual output, and your deadline. Use synthetic data. Do not include private customer data, passwords, tokens, or payment account details.

中文：接一个可复现的小型 Python / CLI / 文本或 JSON 处理问题，试单价 10 美元。明确使用 AI 辅助；先确认范围、验收和付款时间，交付后验收，通过 PayPal 支付。请在 issue 中仅放公开代码或脱敏样例。
