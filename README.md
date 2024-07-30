# RazorCE-Angel-Island-Version
Optional Razor Client for Angel Island. Modified to ensure players are using an approved client scripting extension.

# How it works
 We define new packets to support a mild cryptographic handshake with Razor.</br>
 If Razor fails the handshake, and ForceGMNRZR is set, the user will get a dialog about 20 seconds after logging in informing them of the rule, and that they will be disconnected or warned.</br>
 This feature is optional and can be turned on/off server-side.</br>
 See Scripts\misc\RazorNegotiator.cs in the server for a complete explanation.
