# Gracious Doctrine Timestamp
An extension to add timestamps on doctrine events

## Installation
```text
composer require gracious/doctrine-timestamp
```

## Setup
Extend Timestamps extension to the entity and add
```text
@ORM\HasLifecycleCallbacks()
```
in the annotation of the entity