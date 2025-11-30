# Shopee Negative Reviews Topic Analysis

This project analyzes negative reviews of the Shopee app to identify recurring issues, trends across versions, and potential areas for improvement. The analysis uses topic modeling and trend tracking to uncover stable themes and version-specific spikes.

## Summary of Topics

| Topic | Dominant Keywords | Trend | Interpretation | Notes |
|-------|-----------------|-------|----------------|-------|
| 0 | pengiriman, lama, barang, paket, kurir | Stable, fluctuates | Shipping issues | Operational; no strong correlation with app versions |
| 1 | aplikasi, buka, video, iklan, makin | Upward trend; dominant | App/UX issues | Main pain point for users; persistent across versions |
| 2 | lama, lemot, iklan, lambat, sangat | Persistent, minor | Technical performance | Low-level but consistent; relevant for long-term optimization |

**Key Observations:**

- **Topic 1 (App/UX issues)** is the fastest-growing and most dominant concern across versions 3.40–3.62. Users report freezing, inability to open the app, lag, and intrusive ads.
- **Topic 0 (Shipping issues)** remains significant but fluctuates without a clear upward trend. Indicates operational challenges rather than technical updates.
- **Topic 2 (Technical performance)** persists across all versions but is always minor compared to other topics. Likely linked to device compatibility, caching, or network performance.
- **Major spikes** occurred in versions 3.59.41, 3.60.30–3.61.28, where all topics rose simultaneously, suggesting systemic factors such as large app updates or increased user activity.

## Visual Summary

- **Line chart:** Shows topic counts per version, highlighting upward trends and spikes.
- **Cosine similarity plot:** Tracks the stability of each topic across consecutive versions.
- **JS divergence plot:** Identifies versions with potential topic drift, though no significant drift was detected.

## Conclusion

The topic modeling successfully separates shipping, UX, and performance issues into distinct clusters. The insights can guide prioritization for app improvements, with UX and app functionality issues being the highest priority. Shipping remains an operational concern, and technical performance is consistent but less urgent.

## Notes

- Topics remain semantically stable across versions; no significant topic drift was detected.
- Cosine similarity between consecutive version keywords confirms topic stability.

