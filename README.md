# Diagaku

[Website](https://digidaigaku.com/)


Excerpts from website backend

```js
Us(o.auth.signatureUrl, {
                method: 'POST',
                headers: {
                  'Content-Type': 'application/json'
                },
                body: JSON.stringify({
                  hcaptcha_response: o.auth.hcaptchaKey,
                  wallet_address: Xr(o.auth.walletAddress),
                  domain: {
                    verifying_contract_address: o.auth.contractAddress,
                    name: o.auth.contractName,
                    chain_id: o.auth.chainId,
                    version: '1'
                  }
                })
              });
```

```json
{
 "signatureUrl": "https://backend.digidaigaku.com/validatemint",
 "contractName": "DigiDaigaku",
 "chainId": 1,
 "contractAddress": "0xd1258DB6Ac08eB0e625B75b371C023dA478E94A9",
 "contractAbi": "...",
}
```

Digi Diagaku deployer address: [0x382b5a835895f59f755CC8ef002dC96FD5514c0C](https://etherscan.io/address/0x382b5a835895f59f755cc8ef002dc96fd5514c0c)

**Linked Addresses**

- ENS Holder (was an input to create proxy tx as well): [0xE4C97dfEB967fDB3496C69BaEb26402EE7C83914](https://etherscan.io/address/0xe4c97dfeb967fdb3496c69baeb26402ee7c83914)

- Test Contract Creator [0x4Dc110eD84eEc95A8A27c3d8b8b5f4F3bEc08BaD](https://etherscan.io/address/0x4dc110ed84eec95a8a27c3d8b8b5f4f3bec08bad)

- Deployer: Transferred 0.03 to [0x75eA062F2ba508D96a55eDbDA12Ad87cD437a311](https://etherscan.io/address/0x75ea062f2ba508d96a55edbda12ad87cd437a311)

    - other interacted addresses
    - [0x5200C40E330Ac3Fa6cAD844ea5f549708D75567E](https://etherscan.io/address/0x5200c40e330ac3fa6cad844ea5f549708d75567e)
    - [0xfF03B5EA8f62263beCa1Ca5774BcF26421261BA3](https://etherscan.io/address/0xff03b5ea8f62263beca1ca5774bcf26421261ba3)
    - [0x1f9bCEAB144F2de5EE7dCCB1cfAfBd08d08d41B4](https://etherscan.io/address/0x1f9bceab144f2de5ee7dccb1cfafbd08d08d41b4)
    - [0xdB6006e5E0E04cC62d60E1c45F3A08A2D2b1fbfc](https://etherscan.io/address/0xdb6006e5e0e04cc62d60e1c45f3a08a2d2b1fbfc)

**Transactions and Proxy Contracts**

- Deployer: Create Proxy 1 [Tx](https://etherscan.io/tx/0xb1a57d20e521200ba66f0b34a7b3564c7e95127ced2d78cb15852cbe51303029)
    - Proxy Contract: [0x7ecb02e6c5eEB9765aC1dc9E9F9512a23D6D4Fc6](https://etherscan.io/address/0x7ecb02e6c5eeb9765ac1dc9e9f9512a23d6d4fc6)

- Deployer: Create Proxy 2 [Tx](https://etherscan.io/tx/0xab6639a665cf44d21002bdcfbbbfd7358daf2693b900b4e14d895d9332f16ca6)
    - Proxy Contract: [0x5a8cf09274938a0967d95908d9bfa0ba49b3586d](https://etherscan.io/address/0x5a8cf09274938a0967d95908d9bfa0ba49b3586d)

- Deployer: Create Proxy 3 [Tx](https://etherscan.io/tx/0x55c33fefc143738192c2b43129750ef6071c2fed92d8bbaf429da4030f9e38ee)
    - Proxy Contract: [0x40443ddfcaaadb9de1b8b96cc21304ad8c1c4b14](https://etherscan.io/address/0x40443ddfcaaadb9de1b8b96cc21304ad8c1c4b14)

- Test Contracts LELA
    - [0x29bC60144a7413A5Bf36598d298E2cAc5cc54a19](https://etherscan.io/address/0x29bc60144a7413a5bf36598d298e2cac5cc54a19)
