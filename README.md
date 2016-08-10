# burstcoin-network-observer
Simple webservice ... that refreshes every few seconds and shows the current miningInfo of given wallets/pools.

Features:
- Checks all given pools/wallets for their current state 
- Easy to run with included standalone tomcat server.
- json api via '/json' in url.

Requirements:
- java8

Setup:
- edit 'observer.properties' (e.g. rename observer.default.properties) 
- edit templates/index.html within *-jar archive -> use your domain for refresh url!!!!! (quick and dirty)



