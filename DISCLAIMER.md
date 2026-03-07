# Disclaimer

## Nature of the Software

OpenRelay is a **local network proxy tool** intended for personal learning, research, and development purposes. It runs entirely on your own machine and is functionally equivalent to well-known local proxy tools such as Charles Proxy, Fiddler, mitmproxy, and Surge — it intercepts and forwards network requests on localhost.

OpenRelay is **not** an AI service provider. It does not generate, host, or distribute any AI content. It is a local utility that translates and forwards API requests between tools you already use.

## What OpenRelay Does

- Reads **your own** locally stored authentication credentials (cookies, tokens, API keys) from AI desktop applications **you have already installed and logged into**
- Exposes a unified HTTP proxy on your local machine
- Translates between API formats (Anthropic Messages API, OpenAI Chat Completions API) so that different AI clients can connect to different AI backends through a single endpoint

## What OpenRelay Does NOT Do

- **Does not generate AI content** — it only relays requests and responses between your tools and AI backends
- **Does not bypass paywalls or access controls** — it only uses credentials you already possess
- **Does not share accounts** — all credentials stay on your local machine
- **Does not transmit credentials externally** — authentication data never leaves your device
- **Does not modify or redistribute any third-party software**
- **Does not intercept traffic from other users or devices** (unless you explicitly configure LAN access)

## No Affiliation

OpenRelay is an independent project. It is **not** affiliated with, endorsed by, or associated with Anthropic, Amazon (AWS), Google, Microsoft, Cursor, Codeium (Windsurf), or any other AI service provider mentioned in this project.

All product names, trademarks, and registered trademarks are the property of their respective owners.

## User Responsibility

This software is provided for **learning, research, and personal development use**. By using OpenRelay, you acknowledge and agree that:

1. **You bear full responsibility** for all consequences arising from your use of this software
2. You are responsible for complying with the Terms of Service of all AI services you access through this tool
3. You must only use credentials for accounts you own or are authorized to use
4. You must comply with all applicable laws and regulations in your jurisdiction
5. The authors and contributors of OpenRelay assume **no liability** for any direct, indirect, incidental, or consequential damages resulting from the use or misuse of this software
6. This software is provided "as is" without warranty of any kind, express or implied

## Legal Notice

Local proxy tools that read the user's own credentials from their own machine operate in a well-established category of developer utilities. Users should independently evaluate the legal implications of using such tools in their specific jurisdiction and context.

For questions or concerns, please open an issue on GitHub.
