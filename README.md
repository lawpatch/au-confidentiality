# Confidentiality (Australia)

### Purpose
The language describes how confidential information received by one or both parties to an agreement must be treated.

### Simple confidentiality obligations with LawPatch
Confidential information is a technical area, but most contractual arrangements about confidentiality are pretty similar. This LawPatch language covers the main issues that come up when dealing with confidentiality, so you can streamline your agreement.

### Obligations can go both ways or one way
The LawPatch confidentiality language is designed so that it can be used to capture both:
- a scenario where *only one* party is receiving confidential information; and
- a sceneario where *both parties* are disclosing confidential information to each other.

The importing provision simply needs to state either:
- (if only one party is receiving confidential information) who owes confidentiality duties to whom; or
- that each party owes confidentiality obligations to the other.

### Parameters 
The LawPatch confidentiality language is *not* language that you can import wholesale with a simple incorporation by reference - it assumes that you have included certain information in the clause that imports it.

The parameters that you *must* include are: 
- `Recipient` - The party or parties who are receiving confidential information. Note it can be either party, or it can be both parties.
- `Disclosing Party` - The party or parties who are disclosing confidential information. Note it can be either party, or it can be both parties.
- `Purpose` - The purpose for which the recipient is allowed to use the confidential information. The recipient can't use it for any other purpose, so it's important to be accurate here.

The parameters that are *optional* to include are:
- `Subject` - What kind of information is confidential. If you include a subject, for example 'in relation to the Services' then confidentiality obligations only apply to confidential information about the services, instead of applying to anything that might be considered confidential. 
- `Exception` - Any areas of exception where confidentiality obligations don't apply.

### Examples

Here's an example of how to use the LawPatch confidentiality language, where:
- the parties want to keep the customer's business model confidential; and
- a contractor is only allowed to use information about the business model to provide services.

> Contractor will [secret any confidential information] (https://github.com/lawpatch/au-confidentiality/blob/master/confidentiality_terms.md) of the Customer about the Customer's business model and use it only to provide the Services.

Here's an example of how to use the LawPatch confidentiality language where:
- both parties want the other to keep their information confidential; 
- both parties want the other party only to use it in order to arrange a joint venture;
- there will be an exception that allows the parties to publicise the fact that they are in negoatiations.

> Each party will [keep secret any confidential information] (https://github.com/lawpatch/au-confidentiality/blob/master/confidentiality_terms.md) of the other party and only use it for the purpose of discussing, considering and entering into a joint venture with the other party. The parties are, however, allowed to disclose the fact that they are in negotiations.

### Structure of incorporating clause

As the examples above show, the parameters fit into a clause like this (parameters are indicated with {{curly brackets}}): 

> {{Recipient}} will [keep secret any confidential information] (https://github.com/lawpatch/au-confidentiality/blob/master/confidentiality_terms.md) of {{Disclosing Party}} about {{subject}} and use it only {{purpose}}. {{Exception}}. 

OR like this: 

> Each party will [keep secret any confidential information] (https://github.com/lawpatch/au-confidentiality/blob/master/confidentiality_terms.md) of the other party about {{subject}} and use it only for {{purpose}}. {{Exception}}.

OR like this if there is no subject or exception applicable:

> {{Recipient}} will [keep secret any confidential information] (https://github.com/lawpatch/au-confidentiality/blob/master/confidentiality_terms.md) of {{Disclosing Party}} and use it only {{purpose}}.

### Not Legal Advice

This is not legal advice.  Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances.  Speak to your lawyer to make sure that the language is well aligned with your circumstances.

### Licence

The confidentiality language is released under the license in `license.md`.
