---
layout: single
title: "Episodes 18–19: head and cat Commands"
collection: labs
---

## Objective
Understand and apply `head` and `cat` commands for quick log viewing and file management during investigations.

---

## Commands Practiced

### Episode 18 – head
- `head filename.log`
- `head -n 20 filename.log` – Display first 20 lines
- `head -c 100 filename.log` – Show first 100 bytes of a file
- Combined with pipes: `cat file.log | head -n 50`

### Episode 19 – cat
- `cat filename.log` – View file content
- `cat file1 file2 > combined.log` – Combine files
- `cat -n filename.log` – Number each line
- `cat file.log | grep "error"` – Use cat with grep for pattern search

---

## Key Takeaways
- `head` is useful for previewing logs before full review.
- `cat` is essential for quick file viewing, merging, or piping into filters like grep.
- Both commands are foundational for SOC log triage and scripting.

---

## Practical Use in SOC
SOC analysts use `head` to verify new log entries or check the start of alert files.
They use `cat` to merge evidence files or examine data collected from different sources.

---

## Next Step
Continue to **Episode 20: grep**, focusing on pattern-based log searching and filtering.
