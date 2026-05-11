# observability-deep-dives

A small collection of notes on metrics systems, focused on Prometheus and PromQL fundamentals. Originally written as personal learning notes; sharing publicly in case they help someone else.

## Contents

- [**Prometheus metric types**](prometheus-metric-types.md) — counter, gauge, histogram, summary, and native histograms. What each one is, when to use it, and how they actually serialise on the wire.
- [**PromQL time vs space aggregations**](promql-time-space-aggregations.md) — the two directions a PromQL query collapses data, with simple visual examples. Why `sum(rate(...))` is the canonical pattern.
- [**Cardinality control patterns**](cardinality-control-patterns.md) — what cardinality means, why high-cardinality metrics get expensive, and the design patterns metrics systems use to control it without losing the metric.

## License

MIT — see [LICENSE](LICENSE). All content is written from public-knowledge Prometheus/PromQL fundamentals.
