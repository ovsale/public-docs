# YourAmigo Browser — Privacy Policy

*Last updated: October 12, 2026*

YourAmigo Browser is a Chrome extension that lets your YourAmigo agent (a personal AI assistant in Telegram) work in one tab of your browser, with your permission, while you watch.

## What the extension does

- It keeps a connection to the YourAmigo server you connected it to (the address is part of the connection code you pasted).
- When your agent asks for a tab, the extension shows you a page asking to allow it. Nothing opens without your click.
- After you allow a tab, the agent controls that tab through Chrome's debugging interface: it navigates, clicks, types and reads the page. It works only while that tab is active in its window and stops when you close the tab or press Cancel on Chrome's debugging bar.
- The extension never reads, changes or reports your other tabs.

## Data the extension handles

- **Content of the allowed tab.** Page content, page screenshots and the results of the agent's actions in the tab you allowed are sent to your YourAmigo server, so your agent can read the page and act on it. This can include personal information shown on the pages you asked the agent to use. The extension does not send anything from tabs you did not allow.
- **Connection code.** The server address and the token from the code you pasted are stored in the extension's local storage and sent to that server to identify your own agent. The token can be replaced at any time by requesting a new one in the chat (`/browser`); the old one stops working.

The extension collects nothing else: no browsing history, no cookies of other sites, no analytics.

## Where the data goes

Only to the YourAmigo server named in your connection code — the server that runs your agent. What the agent reads in the tab becomes part of its work for you (its working files and conversation history on that server, under your account), the same as any other page the agent reads. No data is sent to third parties by the extension, and it is never sold or used for advertising.

## Your control

- Allow or deny every tab request.
- Close the tab, press Cancel on Chrome's debugging bar, or press Disconnect in the extension to stop the agent at once.
- Request a new connection code in the chat to invalidate the old token.
- Uninstall the extension to remove the stored connection code.

## Contact

Questions about this policy: alexander.ovsov@gmail.com.
