# Ledger Connect

How to build on top of ledger devices

## Integrate within Ledger Live
Ledger live is the desktop and mobile app built by Ledger.

### Repos

- https://github.com/LedgerHQ/ledger-live-common
- https://github.com/LedgerHQ/ledger-live-desktop
- https://github.com/LedgerHQ/ledger-live-mobile

### Developer infos

- https://developers.ledger.com/

## Integrate within Ledger Web
Ledger web is a lightweight web and open platform built on top of Ledger devices that does not need an extension.

### Repos

- https://github.com/machard/ledger-web

### Developer infos

- https://www.npmjs.com/package/ledger-web-client
- https://www.npmjs.com/package/ledger-web-hw-transport (don't worry about device connectivity inside ledger web)
- https://www.npmjs.com/package/ledger-web-subprovider (ethereum/evm chains subprovider)

## Integrate within a standalone app
You can also build your own app outside of Ledger products.

### Developer infos

- https://www.npmjs.com/package/@ledgerhq/hw-transport-webusb
- https://www.npmjs.com/package/@ledgerhq/hw-transport-webhid
- https://www.npmjs.com/package/@ledgerhq/hw-transport-node-hid
- https://www.npmjs.com/package/@ledgerhq/hw-transport-web-ble
- https://www.npmjs.com/package/@ledgerhq/react-native-hw-transport-ble
- https://www.npmjs.com/package/0x-subproviders (eth / evm chain subproviders)
- https://www.npmjs.com/package/@web3-react/ledger-connector (ethereum/evm chains web3 react connector)
