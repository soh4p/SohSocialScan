SohSocialScan
Username Availability Scanner — Scan social media platforms for available usernames by length.

⚠️ For educational and legitimate use only. Only queries publicly available profile pages. Respect each platform's Terms of Service.

Requirements
Python 3.8+ (optimised and tested for Python 3.14)

requests library

(Optional) pyenchant — only needed for dictionary word filtering

Install Dependencies
bash
pip install requests
pip install pyenchant   # optional
How to Run
bash
python SohSocialScan.py
No GUI. Navigate entirely with number inputs.

Step-by-Step Usage
Step 1 — Select Platform
Choose which social media platform to scan:

Option	Platform
1	Discord
2	TikTok
3	Instagram
4	X (Twitter)
Step 2 — Username Length
Choose how many characters the usernames should be:

`` 3 characters

`` 4 characters

`` 5 characters

`` 6 characters

Step 3 — Filters
Include numbers (0–9)? Yes or No

Include special characters ( _ . )? Yes or No

Dictionary words only? Only returns real English words (requires /usr/share/dict/words or pyenchant)

Step 4 — Scan Limits
How many usernames to scan? Enter any number (e.g. 100, 1000)

Concurrent checks? How many usernames to check at the same time

Recommended concurrent limits per platform:

Platform	Max Recommended
Discord	3
TikTok	2
Instagram	1
X (Twitter)	2
Exceeding these increases rate-limiting risk.

Step 5 — Scan Runs
Live progress bar with █ fill

Real-time ETA countdown

Colour-coded results: 🟢 Available / 🔴 Taken / 🟡 Unknown

Output / Results
Results are automatically saved after every scan into:

----------------------------

Each .txt file contains:

Scan settings (platform, length, filters)

Date and time

Scan duration

Full list of Available, Taken, and Unknown usernames
