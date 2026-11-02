# College Timetable Studio

A Python scheduling system for academic timetables. It models teachers, rooms, subjects, sections, workloads, and placement constraints, then generates schedules and exports them to CSV, Excel, and PDF.

## Run locally

Install `requirements.txt` and run `python -m app.web.server`. The web interface expects your own master data in `Data/master/`; see the loader and validators for the required workbook fields. Run `python -m pytest tests` for the included tests.

This is a fresh source release. The original repository's institution data, timetables, exports, office files, binaries, and Git history are excluded. Some integration tests require local sample master workbooks and are skipped or fail until those fixtures are supplied.
