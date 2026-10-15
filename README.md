# AQA A-level Biology Study Hub (7402)

Topic summaries, 22-question quiz pools and all 12 required practicals for Years 1 and 2.

- `index.html` — the whole site (self-contained, no build needed to host)
- `src/content/*.yaml` — topic content and questions
- `src/build.py` — rebuilds `index.html` from the content

To rebuild after editing content:

    cd src && pip install pyyaml && python3 build.py
