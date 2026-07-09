
# Troubleshooting SheetMATE

test v2

??? note "Error: `PERMISSION_DENIED`"

    If you see this message while signing in or saving your SheetMATE environment:

    > Failed to save environment: We're sorry, a server error occurred while reading from storage. Error code PERMISSION_DENIED.

    <h3>What this means</h3>

    This error usually indicates a problem with browser authentication or account permissions when SheetMATE tries to store your session data.

    <h3>Try these fixes</h3>

    1. Sign out of other Google accounts
         - If multiple Google accounts are signed in, SheetMATE may choose the wrong account.
         - Sign out of all accounts, then sign back in with the account you want to use.

    2. Use a supported browser
         - Recommended: Chrome or Edge.
         - If you are already on one of these browsers, try opening a new private/incognito window.

    3. Clear browser cache and cookies
         - Clear Chrome/Edge cookies and cache for the SheetMATE site.
         - Then refresh the page and try again.

    4. Disable browser extensions temporarily
         - Some privacy or ad-blocking extensions can block authentication or storage access.
         - Disable any extensions affecting Google sign-in, then retry.

    5. Check your account permissions
         - Make sure the Google account you are using has access to the required SheetMATE resources.
         - If your organization has restricted permissions, contact your administrator.

    <h3>If the issue continues</h3>

    - Retry after closing and reopening your browser.
    - Try a different device if available.
    - If the problem persists, contact support or your SheetMATE administrator with the exact error message.
