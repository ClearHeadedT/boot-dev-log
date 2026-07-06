# Learn Retrieval Augmented Generation

- Fixed normalize() min/max swap bug in hybrid_search.py
- Fixed normalize() TypeError from iterating len(scores) instead of range
- Fixed normalize() division formula using max-min as the denominator
- Added early return for the equal-scores normalization case
- Fixed CLI argparse type=list bug, switched to nargs="*" for score lists
