# Gitlab-Search
---
## Overview

The Gitlab-Search is an internal CLI and web application tool designed to search through projects and subgroups for keywords and regular expressions (regex) . This tool helps streamline the process of searching and analyzing codebases, enabling developers to efficiently locate specific patterns or function calls across projects and subgroups.

## Features

- Search for regex patterns within project files and subgroups.
- Search for specific function names used across projects.
- CLI and web-based interfaces for flexible usage.
- Detailed search results and pattern matches.
- Intuitive configuration for project paths and search criteria.
---
## Installation

### CLI Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```
---
## Usage

### CLI Usage

```bash

python project_search.py --pattern <regex_pattern> --path <project_path>

    --pattern: The regular expression pattern to search for.
    --path: The path to the project or subgroup to search within.
```

## Note

<span style="color:red;">Current Version doesn't support web application</span>

---
## Configuration

Edit the .env file to specify default settings, such as token and group

```env
GROUP=8708408
TOKEN=xxxxxxxxxx
```
---
## Contributing


Contributions are welcome! If you encounter any issues or have ideas for enhancements, please feel free to create a pull request or submit an issue.

---
## License

This project is licensed under the MIT License.