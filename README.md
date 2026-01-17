# sh-orbit-20

A small Bash tool that computes text statistics for orbit.

## Goal
- Provide quick text metrics for orbit documents.
- Report top word frequencies for fast inspection.

## Usage
bash main.sh data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
