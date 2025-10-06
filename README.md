## GitHub Insights for TRMNL

<img width="976" height="656" alt="image" src="https://github.com/user-attachments/assets/615fe133-0efd-48df-90c6-614f8b8724cb" />

## Configuration

This plugin requires the following configuration fields:

- **GitHub Repository** (`github_repo`): Enter the GitHub repository in the format 'owner/repo' (e.g., 'usetrmnl/byos_laravel')
- **Secondary View** (`custom_view`): Select the view to display in the secondary column
  - **Changelog** (`changelog`): Shows the latest release changelog/notes
  - **Latest Issue** (`latest_issue`): Shows the most recent open issue

## Data Displayed

The plugin displays comprehensive GitHub repository insights across different layout formats:

### Repository Statistics

- **Stars**: Number of users who have starred the repository
- **Forks**: Number of repository forks
- **Watchers**: Number of repository subscribers
- **Issues**: Count of open issues
- **Open PRs**: Count of open pull requests
- **Latest Version**: Tag name of the most recent release
- **Published at**: Release date of the latest version (MM/DD format)

### Secondary Column Content

Depending on the `custom_view` configuration:

#### Changelog View
- Displays the HTML-formatted release notes/changelog from the latest release

#### Latest Issue View  
- Shows the title and HTML-formatted body of the most recent open issue

### Development
Can be served via [trmnlp](https://github.com/usetrmnl/trmnlp). Install trmnlp and run
```
trmnlp serve
```
