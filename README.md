# Phone Number Grader

A browser-based tool for analyzing and grading UK phone numbers based on their memorability patterns. Perfect for telecoms professionals, number traders, and anyone working with premium phone numbers.

## What it does

The grader analyzes phone numbers and assigns them one of five grades:

- **Taxi** - Ultra-premium numbers (e.g., 777777777)
- **Platinum** - High-value memorable patterns  
- **Gold** - Strong memorable qualities
- **Silver** - Moderately memorable
- **Standard** - Regular numbers

## Features

- **Multiple input methods**: Upload CSV files or paste numbers directly
- **Pattern detection**: Identifies repeating digits, runs, palindromes, and other memorable patterns
- **Visual results**: Interactive charts and sortable tables
- **Export functionality**: Download results as CSV
- **Local storage**: Previous results saved in browser (nothing sent to servers)
- **Mobile responsive**: Works on phones and tablets

## Usage

1. Either upload a CSV file with phone numbers or paste them into the text area
2. Hit process and wait for analysis
3. View results sorted by grade, with patterns highlighted
4. Export or save results for later

### Input formats supported

- UK numbers with or without country code: `+447123456789`, `447123456789`, `07123456789`
- Line-separated or comma-separated lists
- CSV files (any format - numbers extracted automatically)

## Grading algorithm

Based on telecoms industry standards for premium number valuation:

- Repeated digits (more = higher grade)
- Consecutive number runs (123456, 987654)
- Repeating patterns (123123, 789789)
- Palindromes and symmetrical patterns
- Special endings (00, etc.)

## Tech specs

- Pure HTML/CSS/JavaScript - no server required
- Bootstrap 5 for UI
- Chart.js for visualizations
- DataTables for sorting/filtering
- All processing happens client-side

## Running locally

Just open `index.html` in any modern browser. No build process or dependencies needed, or head over to [https://grader.telco.tools](https://grader.telco.tools).

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0).

**What this means:**
- You can use, modify, and distribute this software freely
- If you run this on a server or offer it as a web service, you must make your source code available
- Any modifications must also be released under AGPL-3.0
- Commercial use is allowed, but source code disclosure requirements still apply

See the [LICENSE](LICENSE) file for the full legal text, or visit https://www.gnu.org/licenses/agpl-3.0.html

**TL;DR**: Free to use and modify, but if you host it publicly, share your code too.

© 2025 Telco.Tools
---

*Note: This tool is for analysis purposes only. Actual commercial value of phone numbers depends on many factors beyond memorability patterns.*
