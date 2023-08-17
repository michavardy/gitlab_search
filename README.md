# Gitlab-Search
---
## Overview

Gitlab-Search is an internal CLI and web application tool designed to search through gitlab projects and subgroups for keywords and regular expressions (regex) . This tool helps streamline the process of searching and analyzing codebases, enabling developers to efficiently locate specific patterns or function calls across projects and subgroups.

## Features

- Search for regex patterns within project files and subgroups.
- Search for specific function names used across projects.
- CLI and web-based interfaces for flexible usage.
- Detailed search results and pattern matches.
- Intuitive configuration for project paths and search criteria.
---
## Installation

### CLI Installation


---
## Usage

### CLI Usage

```bash

search  <search-prompt> [ARGUMENTS]
    
    #ARGUMENTS
    --branch <branch-name>: Specify the branch (default: development)
    --script_name_black_list <keyword>": Filter search results by providing a list of script names to remove from results (space delimited).

```

## Note

<span style="color:red;">Current Version doesn't support web application</span>

---
## Configuration

Edit the .env file to specify default settings, such as token and group

```env
GROUP= <gitlab-group-id>
TOKEN=xxxxxxxxxx
RESULTS_PER_PAGE=100
```
---
## Contributing


Contributions are welcome! If you encounter any issues or have ideas for enhancements, please feel free to create a pull request or submit an issue.

---
## License

This project is licensed under the MIT License.

---

## useful


```bash
. ~/AppData/local/pypoetry/Cache/virtualenvs/gitlab-search-JOGwssJF-py3.10/Scripts/activate
```