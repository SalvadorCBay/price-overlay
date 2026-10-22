# Price Overlay — Privacy Policy

Last updated: October 22, 2026

Price Overlay is a browser extension that recognizes monetary amounts displayed on web pages and shows approximate conversions into a currency selected by the user.

## Information processed

- **Web page text:** Price Overlay examines rendered page text locally in your browser to find prices and their currencies. It does not transmit web page text, browsing history, or product information to our servers or to the exchange-rate provider.
- **Settings:** Your chosen currencies, display mode, domain-specific preferences, custom exchange rate, and optional fee are saved using Chrome's extension storage. Some settings use `chrome.storage.sync`, which may be synchronized by Chrome according to your browser settings.
- **Currency requests:** To retrieve current exchange rates, the extension requests currency-rate data from `https://open.er-api.com/`. These requests include the source currency code (e.g., PEN); the provider may automatically receive standard connection metadata such as your IP address. See that provider's own privacy practices. No page contents or shopping items are included in those requests.
- **Selected text:** When you explicitly use the right-click conversion command, the selected text is processed locally to detect monetary amounts.

## Collection, sale, sharing, retention

The extension has no developer-operated account system, analytics, advertising, or telemetry endpoint. We do not sell personal information. Local cached exchange rates are retained in extension storage for reuse; stored preferences remain until you reset them or remove the extension (subject to Chrome sync behavior). Other than exchange-rate requests described above and Chrome's optional settings synchronization, the extension does not send your page data to third parties.

## Permissions

`storage` is used for settings and cached rates; `contextMenus` adds the explicit selected-text conversion command; `activeTab` enables interaction with the currently active tab for popup functions; access to HTTP/HTTPS pages allows price detection and rendering; host access to `open.er-api.com` is used only to retrieve exchange rates.

## Changes and contact

This policy may change if the extension's behavior changes. Material new data practices should be disclosed in the product and listing before implementation. For privacy questions, use the support contact shown on the Chrome Web Store listing.

*Before publication: add and verify an actual support email or URL. Publish this policy on a publicly accessible HTTPS webpage, such as GitHub Pages, and supply its URL in the Chrome Web Store dashboard.*
