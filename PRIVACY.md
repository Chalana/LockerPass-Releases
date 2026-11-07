# LockerPass browser extension: privacy policy

_Last updated: 6 November 2026_

The LockerPass browser extension fills your passwords, one-time codes, cards and addresses into websites, and saves new logins, from your LockerPass vault. This policy explains what it does with your information.

## In short

- The extension collects no data about you and sends nothing to us or anyone else.
- It has no analytics, no tracking and no advertising.
- It doesn't store your vault. Your passwords stay in the LockerPass desktop app on your computer.

## How it works

The extension only talks to the LockerPass desktop app on the same computer, through your browser's native messaging. It makes no internet connections of its own. When you fill a login, the extension asks the desktop app for it. The desktop app answers only while it's unlocked with your master password, and only the LockerPass extension can connect to it.

## What it handles

- **The page you're on.** To offer and fill the right logins, the extension reads the address of the current tab and finds the sign-in and other form fields on the page. It doesn't record your browsing or send it anywhere.
- **Logins you choose to save.** When you sign in or sign up on a website, the extension can offer to save the login to LockerPass. Until you choose to save it or dismiss the offer, it's kept in your browser's temporary session storage, which is cleared when the browser closes. When you save it, it goes to the desktop app, which encrypts it in your vault.
- **Passkeys.** When a website asks for a passkey, the extension passes the request to the desktop app, which creates or uses the passkey in your vault.

## The LockerPass desktop app

The desktop app encrypts your vault with your master password and Secret Key before it's stored or synced, so it can't be read by us, by our cloud provider (Google Firebase) or by anyone without them. The extension doesn't change this.

## Permissions

- **Native messaging:** to talk to the LockerPass desktop app.
- **Access to websites:** to find form fields and fill them on the sites you use.
- **Active tab and scripting:** to fill the page you're on when you ask, including pages opened before the extension was installed.
- **Storage:** for the temporary session storage described above.

## Changes

If this policy changes, the new version will be published here with a new date.

## Contact

Questions about this policy: chalanamg@gmail.com.
