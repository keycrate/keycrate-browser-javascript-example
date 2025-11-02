# Keycrate SDK - Browser Examples

Simple and full examples for the Keycrate license authentication SDK in browser JavaScript.

| all examples : | [python](https://github.com/keycrate/keycrate-python-example) | [Node.js](https://github.com/keycrate/keycrate-nodejs-example) | [rust](https://github.com/keycrate/keycrate-rust-example) | [c#](https://github.com/keycrate/keycrate-cs-example) | [java](https://github.com/keycrate/keycrate-java-example) | [go](https://github.com/keycrate/keycrate-go-example) | [browser](https://github.com/keycrate/keycrate-browser-javascript-example) |
| -------------- | ------------------------------------------------------------- | -------------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------------------------------- |

## Prerequisites

-   Any modern web browser (Chrome, Firefox, Safari, Edge)
-   No build tools or dependencies needed

## Examples

-   **Simple Example** - Tab-based UI with authentication via license key or username/password, plus registration
-   **Full Example** - Includes browser-based HWID detection, login menu, post-login registration, and logout

## Configuration

Update the app ID in the HTML file:

```javascript
const APP_ID = "YOUR_APP_ID";
```

## Used HWID Detection

Browser HWID is generated from:

-   User agent
-   Browser language
-   Timezone offset
-   Screen resolution

This creates a unique fingerprint for the device.
