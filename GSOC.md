# GSoC 2026 Organization Explorer for Linux Contributors

This tool helps GSoC 2026 contributors easily browse, search, and filter mentoring organizations directly from the terminal.

## Prerequisites
Ensure you have Python 3 installed. The tool uses `rich`, `click`, and `requests` which are usually available or can be installed via:
```bash
python3 -m pip install -r requirements.txt
```

## Features
- **Fast:** Caches organization data locally for instant access.
- **Search:** Search by name, technology, or tagline.
- **Filter:** Filter by specific technologies or categories.
- **Detailed:** View full organization descriptions, ideas links, and contact information.

## Usage Examples

### 1. List all organizations
```bash
./gsoc-2026 list
```

### 2. Search for organizations (e.g., Python)
```bash
./gsoc-2026 search python
```

### 3. Filter by technology
```bash
./gsoc-2026 list --tech javascript
```

### 4. Get detailed info for an organization
```bash
./gsoc-2026 info <slug-of-org>
# Example:
./gsoc-2026 info openmrs
```

### 5. Refresh the local cache
```bash
./gsoc-2026 refresh
```

## Organization Data Source
Data is fetched from the official GSoC API:
`https://summerofcode.withgoogle.com/api/program/2026/organizations/`
