# ELONgated email formatter / defrickifier
just a simple 80% email linter/formatter to strip identifying info that may have been inserted into *certain* emails sent by malicious non-state-but-wants-to-pretend-to-be-state billionaire muskrats.

try it here with github preview: https://html-preview.github.io/?url=https://raw.githubusercontent.com/shaneish/dissent_formatter/refs/heads/main/index.html

#### MAKE SURE YOU RUN THROUGH A SPELLCHECK AFTER!  THE EASIEST WAY TO BEAT THIS IS TO USE UNIQUE SPELLING ERRORS OR INTRODUCE NON-STANDARD CHARACTERS THAT INTRODUCE SPELLING ERRORS WHEN SKIPPED!

#### MAKE SURE YOU AREN'T EMAILING OUT IN PLAIN TEXT.  STORE IN A PASSWORD PROTECTED ZIP, ENCRYPT, OR CYPHER THE FORMATTED EMAIL BEFORE SENDING VIA EMAIL OR OTHER METHODS!

## notes
ideally, you'd run similar code locally in your terminal so you don't need to worry about escaping email traffic to strip the email.  don't trust that it isn't being monitored.  tomorrow i can throw a powershell, bash, and python script together to do the same thing, should be relatively straightforward.

this isn't perfect, but it's quick and easy to use.  it strips all non-standard characters, so if they try some funny business like inserting an "Ḥ" for "H" ("Ḥello there federal employees...") it will remove it completely -- SO MAKE SURE YOU RUN THE OUTPUT THROUGH A SPELLCHECK TO ENSURE ANY SUCH MALARKEY IS DETECTED.

the output of this formatter is super basic, essentially turning each sentence into a paragraph and stripping basically all punctuation.  it will be hard -- but not impossible -- to craft workarounds due to the sheer amount of information loss.  the easiest way they'd have to catch you is if you don't use a fricking spellcheck after it's been run through!  USE A SPELL CHECK!

also note, the code for the formatter is public, so they'll prolly be able to design something to work around it in the future.  tis the nature of these things, it's a cat and mouse game.  if i had time to make a full website with a database to log emails ran through it, i'd be able to analyze output diffs to figure out what they're trying -- but, until then, try to compare with other people you know.  anything that strips most punctuation, ignores non-standard characters, and collapses combinations of whitespace (spaces, newlines, weirdo newlines '\r', etc) should be good enough, SO LONG AS YOU SPELL CHECK AFTERWARDS!

don't email it out in plaintext either, either encode it somehow or put it in an encrypted zip folder before emailing out of your workspace.
