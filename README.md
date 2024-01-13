# debugging for vscode-jest

```
024-01-13 11:22:13.614 [error] TypeError: Cannot read properties of undefined (reading 'uri')
	at o.getItemWorkspace (/home/node/.vscode-server/extensions/orta.vscode-jest-5.2.3/out/extension.js:2:514865)
	at /home/node/.vscode-server/extensions/orta.vscode-jest-5.2.3/out/extension.js:2:515733
	at d.h (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:141:140094)
	at d.$executeContributedCommand (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:141:140954)
	at u.S (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:150:10829)
	at u.Q (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:150:10595)
	at u.M (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:150:9685)
	at u.L (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:150:8764)
	at f.value (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:150:7567)
	at n.y (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:1902)
	at n.fire (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:2119)
	at o.fire (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:103:14039)
	at f.value (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:171:7903)
	at n.y (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:1902)
	at n.fire (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:2119)
	at o.fire (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:103:14039)
	at d.z (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:103:17104)
	at f.value (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:103:15556)
	at n.y (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:1902)
	at n.fire (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:2119)
	at f.acceptChunk (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:103:11813)
	at f.value (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:103:11100)
	at n.y (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:1902)
	at n.fire (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:80:2119)
	at n.z (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:168:19527)
	at n.acceptFrame (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:168:19333)
	at i.n (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:168:17832)
	at /vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:168:15052
	at Socket.E (/vscode/vscode-server/bin/linux-x64/0ee08df0cf4527e40edc9aa28f4b5bd38bbff2b2/out/vs/workbench/api/node/extensionHostProcess.js:168:12957)
	at Socket.emit (node:events:513:28)
	at addChunk (node:internal/streams/readable:324:12)
	at readableAddChunk (node:internal/streams/readable:297:9)
	at Readable.push (node:internal/streams/readable:234:10)
	at TCP.onStreamRead (node:internal/stream_base_commons:190:23) io.orta.jest.test-item.coverage.toggle-on {"value":"Orta.vscode-jest","_lower":"orta.vscode-jest"}
2024-01-13 11:22:43.575 [info] ExtensionService#_doActivateExtension vscode.markdown-language-features, startup: false, activationEvent: 'onLanguage:markdown'
2024-01-13 11:22:44.233 [info] ExtensionService#_doActivateExtension vscode.markdown-math, startup: false, activationEvent: 'api', root cause: vscode.markdown-language-features

```