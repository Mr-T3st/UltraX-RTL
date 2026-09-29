# UltraX-RTL Privacy Policy

Effective date: 28 September 2026

UltraX-RTL is a local browser extension for Persian RTL presentation. It does not operate a backend service and does not sell, transmit, or use browsing data for advertising or analytics.

## Data processing

Page text and layout are examined locally in the active browser tab only when the user asks the extension to apply RTL, reset a page, or run the Developer Scanner. Page content and scan reports are not sent to the project owner or to a third party.

User preferences may be stored through the browser's `storage.sync` service when that service is available. Temporary tab state, domain rules, and a user-supplied font stay in local or session browser storage. A custom font is never uploaded by UltraX-RTL.

Scanner reports are created in memory and downloaded only when the user selects an export option. The user controls whether a report is later shared.

## Permissions

- `activeTab` grants temporary access after a direct user action.
- `scripting` loads the local RTL engine and stylesheet into the authorized tab.
- `storage` keeps user preferences and local extension state.

UltraX-RTL does not request a permanent host permission and does not load remote executable code.

## Retention and deletion

Settings remain in browser storage until they are reset, deleted by the user, or removed with the extension. Uninstalling the extension normally removes its local data according to browser behavior. Synced preferences may remain in the browser account until removed through that browser's sync controls.

## Contact

Privacy questions can be submitted through the [UltraX-RTL issue tracker](https://github.com/Mr-T3st/UltraX-RTL/issues) without including private browsing content, credentials, or exported page text.
