## Connections Vs. Queues

### Connections

`config/queue.php`中定義Amazon SQS、Beanstalk 或 Redis等對列

### Prerequisites

`QUEUE_CONNECTION=database`,MySQL、Redis


## Job

`app/Jobs`

## ShouldBeUnique
唯一實例

## Unique Job Locks
作業完成、重試多次失敗，釋放鎖uniqueId key

## ShouldBeEncrypted
加密

## dispatch、dispatchIf、dispatchUnless