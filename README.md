<style>
  .highlight-remove {
    background-color: rgba(255, 0, 0, 0.1); /* Red with 10% opacity */
  }
  .highlight-add {
    background-color: rgba(0, 255, 0, 0.1); /* Green with 10% opacity */
  }
</style>

## Abstract

This BRC proposes an extensible format for including zero-knowledge proofs (ZKPs) in specific key linkage revelations as per [BRC-69](../key-derivation/0069.md) Method 2. While [BRC-94](../key-derivation/0094.md) addresses limitations of [BRC-69](../key-derivation/0069.md) Method 1 through a Schnorr-based ZKP, there is currently no standardized method for provable specific key linkage claims in Method 2. Given the rapid evolution of ZKP technologies, this specification introduces a **<span class="highlight-remove">proof type</span>** enumeration scheme to accommodate future proof mechanisms. **By defining a flexible <span class="highlight-remove">proof type</span> field, <span class="highlight-remove">we allow for the inclusion of various ZKP schemes as they become available</span>, ensuring that wallets and applications can adopt and support them over time, eventually converging on standardized formats.**

<u><i>Changed:</i></u>  
**proof-type**  

<u><i>Reason:</i></u>  
Corrected grammar.

<u><i>Changed:</i></u>  
**By defining a flexible proof-type field, wallets and applications can adopt and support <span class="highlight-add">new</span> ZKP schemes as they become available, eventually converging on standardized formats.**

<u><i>Reason:</i></u>  
This rewording clarifies that wallets and applications are the adopters and emphasizes the goal of eventual standardization.
