# sh-orbit-20

A small Bash tool that computes text statistics for orbit.

## Objective
- Provide quick text metrics for orbit documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate orbit drafts for repeated terms before review.
- Summarize orbit notes when preparing reports.

## Usage
bash main.sh data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
