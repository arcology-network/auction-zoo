# Parallelized Auction

This project is forked from a16z/auction-zoo. The focus here is to demonstate how to eliminate contention from the original contracts so they can executed in full parallel on Arcology. For more info about the original implementation please [check out here.](https://github.com/a16z/auction-zoo)

>:bell: Please note: this is only a demo.


## Goal

The goal is to identify and eliminate all the contention from the original implementation using the tools provided by Arcology's [concurrency APIs](https://docs.arcology.network/arcology-concurrent-programming-guide/). A contention can be loosely defined as a shared variable that isn't read-only. A variable like this will cause executed transactions to be reverted and then re-executed.

## Statue (In progress)
