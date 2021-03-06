<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Audits](./puppeteer.protocol.audits.md) &gt; [BlockedByResponseReason](./puppeteer.protocol.audits.blockedbyresponsereason.md)

## Protocol.Audits.BlockedByResponseReason type

Enum indicating the reason a response has been blocked. These reasons are refinements of the net error BLOCKED\_BY\_RESPONSE.

<b>Signature:</b>

```typescript
export type BlockedByResponseReason = ('CoepFrameResourceNeedsCoepHeader' | 'CoopSandboxedIFrameCannotNavigateToCoopPage' | 'CorpNotSameOrigin' | 'CorpNotSameOriginAfterDefaultedToSameOriginByCoep' | 'CorpNotSameSite');
```
