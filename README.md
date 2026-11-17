# Septem exam timetable

This repository holds one data file, `timetable.json`: the dates of the IB Diploma Programme written exams, used by the Septem study app to fill in a student's exam dates.

**Not affiliated with or endorsed by the IB. Always confirm your dates with your IB coordinator.**

## Where the dates come from

Each session comes from the examination schedule of the International Baccalaureate (IB). Usually that's the PDF on the IB's website (ibo.org, "DP and CP exam schedule"). When the IB has sent its final schedule to schools but not yet put it on its website, the dates are copied from that schedule and checked paper by paper against independent copies. Each session's `source` field says exactly where its dates come from.

The file only lists facts from the schedule: subject, level, paper, date, and whether it's a morning or afternoon session in exam zones A, B and C. Nothing is guessed. If a session is missing, its schedule isn't out yet.

## Versions

Every change gets a higher `version` number and a one-line `note` saying what changed. The commit history shows each version.
