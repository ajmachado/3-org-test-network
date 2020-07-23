# A Three-Org Setup for Testing System Channel and Application Channel

The initial configuration is a two-org consortium (Org1 and Org2), and a channel mychannel is created and joined by the two orgs.

Our objective is to add Org3 into mychannel, and observe ledger is updated.

Meanwhile, we cannot create a new channel for Org1-Org3, as Org3 is not yet in consortium (not yet in system channel).

After adding Org3 back to system channel, we can create new channel Org1-Org3.

All the crypto material (for all the three orgs, and configtx.yaml is updated).

Use one terminal
```
cd fabric-samples/
git clone https://github.com/kctam/3-org-test-network
cd 3-org-test-network
```

Then open two terminals,

Terminal for Org1
```
cd fabric-samples/3-org-test-network
source terminalorg1
```

Terminal for Org2
```
cd fabric-samples/3-org-test-network
source terminalorg2
```
