<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [Transport](./sip.js.transport.md) &gt; [connect](./sip.js.transport.connect.md)

## Transport.connect() method

Returns the promise designated by the child layer then emits a connected event. Automatically emits an event upon resolution, unless overrideEvent is set. If you override the event in this fashion, you should emit it in your implementation of connectPromise

<b>Signature:</b>

```typescript
connect(options?: any): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | <code>any</code> | Options bucket. |

<b>Returns:</b>

`Promise<void>`

