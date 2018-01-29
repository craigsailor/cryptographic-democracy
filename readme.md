## Cryptographic Democracy Vision
Create organizations and distributed entities secured by cryptography.

Manage organizations as a private blockchain; Notaries, lawyers and auditors are replaced by digital signatures, hashes and consensus algorithms.

### Why this is needed
Establishing an organization is difficult, cumbersome and expensive. If you wish to exist in more than one jurisdiction, the difficulty is compounded.

### How this works
We create a specification to describe organizations structure and bylaws, and tools to manage those organizations as private blockchains in a distributed, decentralized manner.




Further information can be found at <http://cryptographic-democracy.com>

**Components of Cryptographic Democracy:**

| Name | Description |
|---|---|
| Member | A member of the organization, identified via a private key. |
| Predicate | Essentially the rules for the organization. |
| Data | Data of the organization. |

## Directory Structure

```
Cryptographic Democracy Desktop
├── docs/ - Documentations.
├── resources/ - Resources which are used outside of the application codes, and original images of assets.
├── scripts/ - Helper scripts.
├── src/ - Application source code.
│   ├── assets/ - Assets which are loaded from the application codes.
│   ├── browser/ - Implementation of Electron's renderer process.
│   │   ├── components/ - React.js components.
│   │   ├── css/ - Stylesheets.
│   │   ├── js/ - Helper JavaScript modules.
│   │   └── webview/ - Injection code for Electron's <webview> tag.
│   ├── common/ - Common JavaScript modules for both Electron's processes.
│   └── main/ - Implementation of Electron's main process.
│       └── menus/ - Application menu.
└── test/ - Automated tests.
    ├── modules/ - Scripts which are commonly used in tests.
    └── specs/ - Test scripts.
```
