<style>
    .highlight-remove {
        background-color: rgba(255, 0, 0, 0.1); /* Red with 10% opacity */
    }
    .highlight-add {
        background-color: rgba(0, 255, 0, 0.1); /* Green with 10% opacity */
    }
</style>

<h1>proofread v3</h1>

<h2>Abstract</h2>
<p>
This BRC proposes an extensible format for including zero-knowledge proofs (ZKPs) in specific key linkage revelations as per 
<a href="../key-derivation/0069.md">BRC-69</a> Method 2. While 
<a href="../key-derivation/0094.md">BRC-94</a> addresses limitations of 
<a href="../key-derivation/0069.md">BRC-69</a> Method 1 through a Schnorr-based ZKP, there is currently no standardized method for provable specific key linkage claims in Method 2. Given the rapid evolution of ZKP technologies, this specification introduces a 
<b>proof type</b> enumeration scheme to accommodate future proof mechanisms. 
<b>By defining a flexible <span class="highlight-remove">proof type</span> 
<span class="highlight-add">proof-type</span> field, 
<span class="highlight-remove">we allow for the inclusion of various ZKP schemes as they become available, ensuring that wallets and applications can adopt and support them over time,</span> 
<span class="highlight-add">wallets and applications can adopt and support new ZKP schemes as they become available,</span> 
eventually converging on standardized formats.</b>
</p>

<u><i>Changed:</i></u>
<p>
By defining a flexible <span class="highlight-add">proof-type</span> field, wallets and applications can adopt and support <span class="highlight-add">new</span> ZKP schemes as they become available, eventually converging on standardized formats.
</p>

<u><i>Reason:</i></u>
<p>
This rewording clarifies that wallets and applications are the adopters and emphasizes the goal of eventual standardization.
</p>

<u><i>Changed:</i></u>
<p>
<b>proof-type</b>
</p>

<u><i>Reason:</i></u>
<p>
Corrected grammar.
</p>
