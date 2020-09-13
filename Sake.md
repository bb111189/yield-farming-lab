# Crop ID: Sake 

## Social media
Website: https://sashimi.cool/  
Twitter: https://twitter.com/SASHIMISASHIMI5

## Contract

### Token contract
Token contract name: `SakeToken`  
Token contract: [0x066798d9ef0833ccc719076dab77199ecbd178b0](https://etherscan.io/address/0x066798d9ef0833ccc719076dab77199ecbd178b0#code) 

Conclusion of `SakeToken`: 
- No significant change from the original SushiToken contract
- A near identical fork of `SushiToken`

__Owner__  
Contract owner: [0x1daed74ed1dd7c9dabbe51361ac90a69d851234d](https://etherscan.io/address/0x1daed74ed1dd7c9dabbe51361ac90a69d851234d#code)  
Contract owner type: Fork of `MasterChef` contract, `SakeMaster`

### SakeMaster contract
Token contract name: `SakeMaster`  
Contract: [0x0ec1f1573f3a2db0ad396c843e6a079e2a53e557 ](https://etherscan.io/address/0x0ec1f1573f3a2db0ad396c843e6a079e2a53e557#code)  

Conclusion of SakeMaster: 
- Has a new function `handoverSakeMintage` which is callable by owner
- Dev reward is 6.667%
- Fancy math calculation. __You should check the correctness!__
- No significant change from the original MasterChef contract

__Owner__  
Contract owner: [0x2ba614b6ca210fa4961c923dcf7910413b0f93be ](https://etherscan.io/address/0x2ba614b6ca210fa4961c923dcf7910413b0f93be)  
Contract owner type: Fork of `Timelock` 

### Fork of Timelock
Contract: [0x2ba614b6ca210fa4961c923dcf7910413b0f93be ](https://etherscan.io/address/0x2ba614b6ca210fa4961c923dcf7910413b0f93be)

Conclusion of `Timelock`: 
- No significant change from the original `Timelock` contract
- IMINIMUM_DELAY = 2 days

## Conclusion
- No significant or notable change. 
- Primary analysis that Sake is not beer! Cheers~