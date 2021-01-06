<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Worker](./bullmq.worker.md)

## Worker class

<b>Signature:</b>

```typescript
export declare class Worker<T = any, R = any, N extends string = string> extends QueueBase 
```
<b>Extends:</b> [QueueBase](./bullmq.queuebase.md)

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(name, processor, opts)](./bullmq.worker._constructor_.md) |  | Constructs a new instance of the <code>Worker</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [opts](./bullmq.worker.opts.md) |  | [WorkerOptions](./bullmq.workeroptions.md) |  |
|  [repeat](./bullmq.worker.repeat.md) |  | Promise&lt;[Repeat](./bullmq.repeat.md)<!-- -->&gt; |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [close(force)](./bullmq.worker.close.md) |  |  |
|  [getNextJob(token)](./bullmq.worker.getnextjob.md) |  | Returns a promise that resolves to the next job in queue. |
|  [isPaused()](./bullmq.worker.ispaused.md) |  |  |
|  [pause(doNotWaitActive)](./bullmq.worker.pause.md) |  | Pauses the processing of this queue only for this worker. |
|  [processJob(job, token)](./bullmq.worker.processjob.md) |  |  |
|  [resume()](./bullmq.worker.resume.md) |  |  |
|  [waitUntilReady()](./bullmq.worker.waituntilready.md) |  |  |
