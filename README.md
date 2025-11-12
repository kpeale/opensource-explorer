# opensource-explorer README

Open Source Explorer is a powerful VS Code extension that brings the GitHub ecosystem into your editor. Search for repositories, star your favorites, view issues, and explore trending projects—all without leaving your development environment.

## Features

Repository Search: Search through millions of GitHub repositories with advanced filters:

* Filter by programming language
* Sort by stars, recent updates, or forks
* Search by keywords or topics
* View repository details, README files, and statistics

 GitHub Integration :Seamlessly interact with GitHub:

* Login with GitHub - Authenticate to unlock 5000 API requests/hour
* Star/Unstar repositories directly from VS Code
* Fork repositories with one click
* Clone repositories to your local machine
* View real-time rate limits

 Bookmark Management: Save and organize your favorite projects:

* Bookmark repositories for quick access
* View all saved repositories in one place
* Remove bookmarks when you're done
* Export/import bookmark collections

 Issue Browser: Explore and track issues:

* View open issues for any repository
* Filter issues by labels and status
* Find "Good First Issue" tasks perfect for beginners
* Open issues directly in your browser

Trending Repositories: Stay updated with what's hot:
* Discover trending projects this week
* Filter trending repos by language
* See what the open-source community is building

 My Repositories: Quick access to your own projects:

* View all your GitHub repositories
* See your private and public repos
* Clone your own projects instantly.


## Usage
Searching for Repositories

1.Open the Explorer view
2.Enter your search query (e.g., "react", "machine learning")
3.Select a programming language (optional)
4.Choose sort order (Stars, Recently Updated, Forks)
5. Click Search

Viewing Repository Details

1. Click on any repository from search results
2. View the Details panel to see:

* Repository description and statistics
* README file (rendered markdown)
* Star, Fork, Clone, and Save buttons


3. Click buttons to interact with the repository

Managing Bookmarks

1.Click the 💾 Save button on any repository
2.View saved repositories in the Saved tab
3.Click × to remove a bookmark
4. Click Clear All to remove all bookmarks

Finding Good First Issues

1.Navigate to the Issues tab
2.Click Good First Issues
3.Optionally filter by language
4.Click any issue to open it in GitHub

Viewing Your Repositories

1.Login to GitHub (required)
2.Navigate to the My Repositories tab
3.See all your public and private repositories
4.Click to view details or clone

## Requirements

Have a github account, does not support gitlab yet

## Getting Started

## Installation

1 Open VS Code
2 Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
3 Search for "Open Source Explorer"
4 Click Install

## First Use

1 Click the Open Source Explorer icon in the Activity Bar (left sidebar)
2 (Optional but recommended) Click Login to authenticate with GitHub

* Unauthenticated: 60 API requests/hour
* Authenticated: 5000 API requests/hour 🚀


Start exploring! Search for repositories or browse trending projects

## Extension Settings
This extension contributes the following settings:

opensourceExplorer.resultsPerPage: Number of repositories to fetch per page (10-100). Default: 30
opensourceExplorer.defaultLanguage: Default programming language filter. Default: "" (All languages)
opensourceExplorer.defaultSort: Default sort order for repository search. Options: stars, updated, forks. Default: stars
opensourceExplorer.showRateLimitWarning: Show warning when API rate limit is low. Default: true


### 1.0.0

Initial release of Open source Explorer...



---

## Following extension guidelines

Ensure that you've read through the extensions guidelines and follow the best practices for creating your extension.

* [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.



**Enjoy!**
