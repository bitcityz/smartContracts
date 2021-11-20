# smartContracts

####
Our system has 2 types of tokens: BTCZ - max supply: 200 million and BTCY - max supply 5 billion tokens

- BTCZ: https://bscscan.com/token/0xf1177c04d7da80cb97a5c02511bbc9e076de13ab
- BTCY: https://bscscan.com/token/0x53b384151607c2c7c56a8884621b0ee494556c3c
## Token allocation

- BTCZ will be divided into addresses with different holding rate and unlocking time
- Tokenomics Contract: https://bscscan.com/address/0xc3b4956df110217e09e6f5dd32b26f29ac80a449
- Check BTCZ init minters: 
```
initMinters = ['angel', 'seed', 'private', 'public', 'boundty', 'reward', 'marketing', 'liquidity', 'ecosystem', 'team', 'partner'];
```

```
initMintersPercent = [2.5%, 5%, 11%, 0.7%, 0.1%, 18.1%, 9%, 20%, 13.6%, 15%, 5%];
```
```
  minterAddress['angel'] = 0x866f54Da75BBA49FD50eF5b19D364038998f64E0;
  minterAddress['seed'] = 0x2CA08cb2AF27098d4756AEA05cf5C8E010F05858;
  minterAddress['private'] = 0xa1f69442905f6c6A940c157EA02E8aa1e1AD056F;
  minterAddress['public'] = 0x1a6fd4B1487f38d847b45A8Ca2198D25fbBA7977;
  minterAddress['boundty'] = 0x1226592A0C9eDa29DF2b044cB6C2DF5ac8b7b9ab;
  minterAddress['reward'] = 0x8d4F0A10132bD9bdC8f8B0080AAdDa3ca32203ef;
  minterAddress['marketing'] = 0x8A6c91350e93C39fb6407a8d4539989cCbeC7C70;
  minterAddress['liquidity'] = 0x011AE7654601b4Be8448BcdE223A872eCB52213e;
  minterAddress['ecosystem'] = 0x01252C690236eC406526C74c11B1ba8ee6E9260F;
  minterAddress['team'] = 0xC6A8CFA24e56EB441c35dEb5BF6e3E321088De7B;
  minterAddress['partner'] = 0x74AeCdFC840B3d187b55a0831996062Fa444bd72;
```
  
  
  
