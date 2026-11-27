# I-WORKS v4.4 — SARISA portfolio sync

Static multilingual website for I-WORKS, with no build step. The SARISA presentation is synchronized to the public SARISA-AI-PLATFORM `main` branch as of 27 November 2026.

## SARISA information shown on the site
- Android and Windows builds succeeded for the latest main commit, `2797136d9261c2b11918e95265a355bbe3be09ea`.
- Offline YOLOX-Nano object analysis: Android camera frames and selected local images on Windows.
- SAR target appearance search: up to eight reference photos, clothing/color similarity, and explicit operator confirmation for temporary session-only samples. This is not face recognition, identity confirmation, or model-weight training.
- Map-based mission planning: draw a search boundary, generate sweep tracks, and save the route with the mission.
- The SARISA panel is labeled as an illustrative workflow preview, without a live camera, mission, or drone connection.

## Linked source and CI
- SARISA repository: https://github.com/totalmarketing2025-alt/SARISA-AI-PLATFORM
- Latest main commit: https://github.com/totalmarketing2025-alt/SARISA-AI-PLATFORM/commit/2797136d9261c2b11918e95265a355bbe3be09ea
- Android Actions: https://github.com/totalmarketing2025-alt/SARISA-AI-PLATFORM/actions/runs/45915833156
- Windows Actions: https://github.com/totalmarketing2025-alt/SARISA-AI-PLATFORM/actions/runs/45915833225

## Existing site limitations
- The page remains a static showcase without a backend or working contact form.
- The StellarECC interface is an illustrative source-based reconstruction, not an app screenshot.
- HAVOC GUARD camera activity remains fictional demonstration data.
- SARISA has no physical drone connection or flight commands.

## Preview
`python -m http.server 8084 --bind 127.0.0.1`
