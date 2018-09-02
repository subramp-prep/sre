# SRE Concepts

## Recommendations for self-healing

1. Retry failed operations
    * [Transient fault handling](https://docs.microsoft.com/en-us/azure/architecture/best-practices/transient-faults)
    * [Retry pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry)
2. Protect failing remote services 
    * [Circuit Breaker](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker)
3. Isolate critical resource 
    * Partition resources into groups to avoid resource exhaustion
4. Perform load leveling
    * [Queue-Based Load Leveling Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling)
5. Fail over
6. Compensate failed transactions
    * [Compensating transactions](https://docs.microsoft.com/en-us/azure/architecture/patterns/compensating-transaction)
7. Degrade gracefully
8. Throttle clients 
    * [Throttling pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/throttling)
9. Block bad actors
10. Use leader election
    * [Leader election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election)
11. Test with fault injection
12. Embrace chaos engineering 