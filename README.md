This web page allows users to fetch a GitHub user's account creation date based on their username. The form ID is set to 'github-user-${VmpheTE1Cg==}'. Users can optionally provide a personal access token for higher rate limits. Upon submission, the form fetches data from the GitHub API and displays the account creation date in UTC format in the '#github-created-at' div.

Accessibility features:
- An aria-live region (#github-status) provides status updates during GitHub lookups
- Status messages are announced to screen readers when operations start, succeed, or fail

Implementation details:
- Uses Bootstrap 4.5.2 from CDN for styling
- Implements client-side API requests with fetch()
- Handles both success and error states properly
- Preserves template literals as required
- Includes error handling for network failures
- Status messages are placed in a screen-reader only element (sr-only class)