# Learn Retrieval Augmented Generation

- Fixed normalize() min/max swap bug in hybrid_search.py
- Fixed normalize() TypeError from iterating len(scores) instead of range
- Fixed normalize() division formula using max-min as the denominator
- Added early return for the equal-scores normalization case
- Fixed CLI argparse type=list bug, switched to nargs="*" for score lists
- Added per-score 4-decimal print formatting for the normalize command
- Implemented weighted_search combining BM25 and semantic scores with alpha blending
- Fixed a duplicate weighted_search method definition
- Split normalize() into a pure function plus a CLI-printing wrapper
