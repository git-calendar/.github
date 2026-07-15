## Git Calendar - try now: [git-calendar.firu.dev](https://git-calendar.firu.dev)

### Key Features
- **Git-powered**: Your calendar data lives in a standard Git repository (with full version history).
- **Decentralized**: Data isn't tied to a single server or cloud provider. Users can host their calendar on their own infrastructure or a public provider (e.g., GitHub, GitLab, Codeberg). Switching providers is as simple as changing the remote.
- **No backend**: No calendar server to run or maintain; just your client talking directly to a Git remote. One less middleman.
- **Offline First**: Edit your calendars locally without an internet connection. Changes sync automatically when the connection is restored.
- **End-to-End Encrypted**: Keep your events private even on untrusted hosts.
- **Open Source**: Core library in Go + modern web client in Vue.js.

### Components
- [core](https://github.com/git-calendar/core): Shared Go library handling Git operations, encryption, and calendar logic.
- [web-client](https://github.com/git-calendar/web-client): Responsive Vue-based web client.
- [documentation](https://git-calendar.github.io/documentation): Project docs.
- [demo-calendar](https://github.com/git-calendar/demo-calendar): Sample repository you can clone to see how it works.

Perfect for privacy-conscious users and developers who want full ownership of their data. Your calendar is stored as plain Git data, so every change is versioned, you can fork, branch, clone, or migrate it anywhere, and you’re never locked into a single service.

Completely independent of any centralized platform — host it on GitHub, GitLab, a private server, or even run it entirely offline. Combined with strong end-to-end encryption, your events remain private and secure even if you use untrusted hosting providers.
