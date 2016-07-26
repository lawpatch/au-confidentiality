# Confidentiality (Australia)

### Purpose
The language describes how confidential information received by one or both parties to an agreement must be treated.

### Simple confidentiality obligations with LawPatch
Dealing with confidential information is a technical area, but most confidentiality clauses are pretty similar. This LawPatch confidentiality cluase covers the main issues that come up in most confidentiality clauses. That means you can streamline your agreement, by extracting that fairly standard technical languag and leaving the job to LawPatch.

### Obligations can go both ways or one way
This repo is designed so that it can be used to capture both:
- a scenario where *only one* party is receiving confidential information; and
- a sceneario where *both parties* are disclosing confidential information to each other.

The importing provision simply needs to state either that:
- (if only one party is receiving confidential information) who owes confidentiality obligations to whom; or
- both parties owe confidentiality obligations to each other.

### Parameters 
The language in this repo is *not* language that you can import wholesale with a simple incorporation by reference - it assumes that you have included certain information in the clause that imports it.

The parameters that you *must* include are: 
- `Disclosing Party` - The party or parties who are disclosing confidential information. Note it can be either party, or it can be both parties.
- `Recipient` - The party or parties who are receiving confidential information. Note it can be either party, or it can be both parties.
- `Purpose` - The purpose that the recipient of confidential information is allowed to use it for. The recipient can't use it for any other purpose, so it's important to be accurate here.

The parameters that are *optional* to include are:
- `Confidential Information` - An alternative definition of confidential information, if the definition in the repo is not right for you.
- `Exception` - Any areas of exception where confidentiality obligations don't apply.

### Examples

Here's an example of using Lawpatch to impose confidentiality obligations on only one party, where confidential information may only be used to provide.  

> Contractor <a href="https://github.com/lawpatch/au-confidentiality/[INSERT REMAINDER HERE]" target="_blank">owes confidentiality obligations</a> to Customer. Contractor may only use information to which those obligations apply for the purpose of providing the services.

Here's an example where both parties owe confidentiality obligations, where the information can only be used for setting up a joint venture, but the confidential information is limited to prospectuses they have given to each other. The pu This requires Confidential Information to be defined in the Agreement.

> Both parties <a href="https://github.com/lawpatch/au-confidentiality/[INSERT REMAINDER HERE]" target="_blank">owe confidentiality obligations</a> to each other in respect of the Confidential Information. The parties may use the Confidential Information for the purpose of discussing, considering and entering into a joint venture.

> Confidential Information means information contained in a prospectus provided by one party to the other.

### Not Legal Advice

This is not legal advice.  Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances.  Speak to your lawyer to make sure that the language is well aligned with your circumstances.

### Licence

The confidentiality language is released under the license in `license.md`.
