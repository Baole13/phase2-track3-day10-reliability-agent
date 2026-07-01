# Day 10 Reliability Final Report

## Metrics Summary

| Metric | Value |
|---|---:|
| total_requests | 300 |
| availability | 1.0 |
| error_rate | 0.0 |
| latency_p50_ms | 272.83 |
| latency_p95_ms | 315.23 |
| latency_p99_ms | 320.76 |
| fallback_success_rate | 1.0 |
| cache_hit_rate | 0.62 |
| circuit_open_count | 9 |
| recovery_time_ms | 2272.207021713257 |
| estimated_cost | 0.047062 |
| estimated_cost_saved | 0.186 |

## Chaos Scenarios

| Scenario | Status |
|---|---|
| primary_timeout_100 | pass |
| primary_flaky_50 | pass |
| all_healthy | pass |

## Analysis TODO(student)

Explain what failed, why the fallback path worked or did not work, and what you would change before production.