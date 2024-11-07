<style>
  .highlight-remove {
    background-color: rgba(255, 0, 0, 0.1); /* Red with 30% opacity */
  }
  .highlight-add {
    background-color: rgba(0, 255, 0, 0.1); /* Green with 30% opacity */
  }
</style>

<h2>Abstract</h2>
<p>
This BRC proposes an extensible format for including zero-knowledge proofs (ZKPs) in specific key linkage revelations as defined in <a href="https://example.com/BRC-69">BRC-69 Method 2</a>. While <a href="https://example.com/BRC-94">BRC-94</a> addresses limitations of BRC-69 Method 1 through a Schnorr-based ZKP, there is currently no standardized method for provable specific key linkage claims in Method 2. Given the rapid evolution of ZKP technologies, this specification introduces a <span class="highlight-add">proof-type</span> <span class="highlight-remove">proof type</span> enumeration scheme to accommodate future proof mechanisms. By defining a flexible <span class="highlight-add">proof-type</span> <span class="highlight-remove">proof type</span> field, wallets and applications can adopt and support <span class="highlight-add">new</span> ZKP schemes as they become available, eventually converging on standardized formats.
</p>

<h3>Changed line:</h3>
<p>
By defining a flexible <span class="highlight-add">proof-type</span> <span class="highlight-remove">proof type</span> field, wallets and applications can adopt and support <span class="highlight-add">new</span> ZKP schemes as they become available, eventually converging on standardized formats.
</p>

<h3>Reason:</h3>
<p>
This rewording clarifies that wallets and applications are the adopters and emphasizes the goal of eventual standardization.
</p>
