<style>
  .highlight-remove {
    background-color: rgba(255, 0, 0, 0.1); /* Red with 10% opacity */
  }
  .highlight-add {
    background-color: rgba(0, 255, 0, 0.1); /* Green with 10% opacity */
  }
</style>

<h1>proofread v4</h1>

<h2>Abstract</h2>

<p>
This BRC proposes an extensible format for including zero-knowledge proofs (ZKPs) in specific key linkage revelations as per <a href="../key-derivation/0069.md">BRC-69</a> Method 2. While <a href="../key-derivation/0094.md">BRC-94</a> addresses limitations of <a href="../key-derivation/0069.md">BRC-69</a> Method 1 through a Schnorr-based ZKP, there is currently no standardized method for provable specific key linkage claims in Method 2. Given the rapid evolution of ZKP technologies, this specification introduces a <b>proof type</b> enumeration scheme to accommodate future proof mechanisms. <b>By defining a flexible <span class="highlight-remove">proof type</span><span class="highlight-add">proof-type</span> field, <span class="highlight-remove">we allow for the inclusion of various ZKP schemes as they become available, ensuring that wallets and applications can adopt and support them over time,</span> wallets and applications can adopt and support <span class="highlight-add">new</span> ZKP schemes as they become available, eventually converging on standardized formats.</b>
</p>

<h3><u><i>Changed:</i></u></h3>

<p><b><span class="highlight-remove">proof type</span><span class="highlight-add">proof-type</span></b></p>

<h3><u><i>Reason:</i></u></h3>

<p>Corrected grammar.</p>

<h3><u><i>Changed:</i></u></h3>

<p><b>By defining a flexible proof-type field, <span class="highlight-remove">we allow for the inclusion of various ZKP schemes as they become available, ensuring that wallets and applications can adopt and support them over time,</span> wallets and applications can adopt and support <span class="highlight-add">new</span> ZKP schemes as they become available, eventually converging on standardized formats.</b></p>

<h3><u><i>Reason:</i></u></h3>

<p>This rewording clarifies that wallets and applications are the adopters and emphasizes the goal of eventual standardization.</p>
