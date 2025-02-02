### Advanced Bug Bounty Tool (Pentester Edition)

#### Requirements:
1. **Python 3.x**
2. **Python Libraries**: `requests`, `bs4`, `argparse`, `threading`, `socket`, `subprocess`, `tkinter`, `webbrowser`
3. **External Tools**: `nmap`, `nikto`, `sqlmap`, `wpscan` (must be installed on the system).
4. **APIs**: You’ll need a SecurityTrails API key (free for basic usage).

---

### Install Dependencies

```bash
pip install requests beautifulsoup4
```

### Run the Tool

Save the script as `bugbounty_pentester.py` and run it:

```bash
python bugbounty_pentester.py
```

---

### Key Features:
1. **Professional Tool Integration**: Nmap, Nikto, sqlmap, and wpscan.
2. **Subdomain Enumeration**: Uses SecurityTrails API for automated subdomain discovery.
3. **Graphical Interface**: Easy-to-use interface for URL, domain, and port inputs.
4. **HTML Reports**: Generates a professional and visual report.
5. **Multi-threading**: Scans multiple targets in parallel for efficiency.
