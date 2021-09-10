<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [HTTPRequest](./puppeteer.httprequest.md) &gt; [enqueueInterceptAction](./puppeteer.httprequest.enqueueinterceptaction.md)

## HTTPRequest.enqueueInterceptAction() method

Adds an async request handler to the processing queue. Deferred handlers are not guaranteed to execute in any particular order, but they are guarnateed to resolve before the request interception is finalized.

<b>Signature:</b>

```typescript
enqueueInterceptAction(pendingHandler: () => void | PromiseLike<unknown>): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  pendingHandler | () =&gt; void \| PromiseLike&lt;unknown&gt; |  |

<b>Returns:</b>

void
