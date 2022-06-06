# S84-tags
A veritable potpourri of Luminate Online / TeamRaiser reusable tag logic. Make your LO email, teamraiser events, and pagebuilder content simpler and more bulletproof by swapping out long-form code and complicated conditionals with single reusable tags. The utility ranges from 

## What is this collection?
- **Reverse Polish Notation:** JavaScript isn't possible everywhere, and even when it *is* available, the number crunching is always faster when done by the Luminate server. S130 lets you do math and string manipulation before returning an answer, letting you reformat tag responses, combine results, have more sophisticated conditionals, and return processed data in places it usually isn't possible (e.g. Email subject lines).
- **Conditionals:** Whether you've got a simple if/else statement and just want to make it easier to read, or have brackets within brackets within brackets, you can put it into a reusable tag and make life easier. This collection has everything from a very complicated URL rewriter, to simple "fall back to this data if that's missing" conditionals that can make your site a bit more typo-proofed.
- **Email:** Edit using human-readable elements that transform into the deeply verbose code that ensures consistency and graceful degradation in older email clients.
- **"Roll Your Own" API:** [Content API's getTagInfo method](https://developer.blackbaud.com/lo-api/loapi/content/getTagInfo) is great, but it didn't always exist (and still returns one answer for one request). This technique lets you combine S-tags, conditionals, RPN, etc. and make a custom RESTful endpoint that returns the exact data in the exact format you need.

## How do I implement it?
`[[S51:____________]]` -- Fill in the blank with the name of a published PageBuilder page. Note that LO ignores the page library's directory names, so be sure your page name is unique across your instance.
`[[S84:___/___/____]]` -- FTP to your LO instance and upload your file to a subfolder. Note that anyone who knows the URL of your file will be able to view it in plaintext.