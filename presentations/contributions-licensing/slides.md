---
theme: unicorn
colorSchema: 'light'

defaults:
    website: ''
    handle: ''
    logoHeader: ''

layout: intro
introImage: ''
---

# Contributing, CLAs, and Licensing

### Name

Job title/company/other details


<!-- 
Hi, I am name.

I'm here to talk about the logistics of contributing to open source, especially CLAs and licensing

I'm not a lawyer, so always consult a professional if you have legal questions, this is to just share
knowledge needed by developers when it comes to signing contributor license agreements (CLAs) and checking
the license agreements for Open Source code.

When I talk about contributions in this session, I mean contributions to the code or other files hosted inside the project. Raising issues or using discussion forums does not need you to comply with a CLA or obey a license (but you are expected to be nice and helpful).
-->

---
layout: table-contents
gradientColors: ['#8EC5FC', '#E0C3FC']
---

# Overview

<div v-click="1">

- 🧑‍💻 **Contributing to open source**

</div>

<div v-click="2">

- 🧑‍⚖️ **CLAs (Contributor Licensing Agreements)**

</div>

<div v-click="3">

- ⚖️ **Open Source Licensing**

</div>

<div v-click="4">

- 🔒 **Accounts - Personal vs Company**

</div>

<div v-click="5">

- 🧑‍💻 **Ways to Contribute**

</div>

<div v-click="6">

- 🎉 **Extra tips**

</div>


<!--

Note: Each bullet will animate in on pressing space or the right arrow key

This session will cover the following topics:

A quick overview of contributing to open source any why licenses are important

Contributor license agreements

Open source licensing

Accounts - using your personal account or a company account

Ways you can contribute

And some extra tips

-->

---
layout: center
---

# Disclaimer - This is not legal advice

Although we will be talking about legal issues, I am not a lawyer.
If you are ever unsure, consult a software lawyer.

<!--
As already mentioned, I am not a lawyer. If you are ever unsure about anything, consult a lawyer who specializes in open source ad software law.
-->

---

# Contributing to open source

Open source involves making potentially anonymous contributions to code, documentation, UI/UX and other components of a project.

**These projects are often maintained by a small team of volunteers working for free in their spare time.**

The project needs to protect itself against legal issues, and ensure the code is only used in the way intended.

<!--
When you make a contribution to an open source project, you can be to all intents and purposes anonymous.
The project team is usually a small team of volunteers working for free, so they need to protect both themselves and the code they write.
-->

---

# CLAs - Contributor Licensing Agreements

These are an agreement between an open source project and it's contributor.

<div v-click="1">

CLAs define:

</div>

<div v-click="2">

- Ownership

</div>

<div v-click="3">

- Protection

</div>

<!--
A CLA is an agreement between the open source project and all it's contributors. These are designed to protect the open source project from any claims of copyright infringement, license breaches or other legal issues.

CLAs define ownership of the code, and the protections in place for the open source project
-->

---

# Ownership

When you submit code to an open source project, who owns the code?

<!--
When you submit code to an open source project, who actually owns the code?

Do you own it - is it your unique intellectual property?

Is it owned by your employer? If you wrote this code on company time then your employer owns it.

Is it owned by another project and covered by a license that does not allow for re-use?

If you submit code that is owned by someone else to an open source project, you are potentially making them liable for any claims that could be made against them - for example being sued by your employer for intellectual property theft.

-->

---

# Ownership

Part of a CLA is declaring that you have ownership of the code and are allowed to submit it to the open source repository.

<!--

When you sign a CLA you state that all the code you are submitting is code you are allowed to submit - either you own it, or your employer does and allows you to submit this code. You are also stating that it is not covered by a license that does not allow you to submit the code to the open source project.

-->

---

# Transfer of ownership

Once you submit the code, you transfer ownership to the open source project

<!--
The CLA also defines what happens when you submit the code.

Once the code is submitted, it becomes the property of the open source project and you grant a perpetual worldwide irrevocable license to the code.

This means the open source project owns it forever.
-->

---

# Protection

The CLA protects the open source project


<!--
Th CLA protects the project.

If you submit code that you are not allowed to submit then you are to blame, not the project and you can be sued, not them.

If your code infringes on any patents, you are liable, not the project.

Once submitted you can't revoke any license and stop the project from using your code.

Remember - most open source is run by volunteers in their spare time with minimal funding. The CLAs protect them.

-->

---
layout: image-center
image: https://imgs.xkcd.com/comics/dependency.png
imageWidth: '250'
imageHeight: '318'
---

<!--

Does anyone remember left pad? The owner of the left-pad JavaScript NPM package deleted it from NPM and most of the internet broke.

Imagine if a contributor to a massively used project like Linux decided they were going to revoke the license to their code and it had to be removed. The CLA stops this happening.

Imagine if the person creating a small but important part of the modern digital stack got sued and their project was deleted?

-->

---
layout: image-center
image: https://raw.githubusercontent.com/open-source-bootcamp/bootcamp-guide/main/presentations/contributions-licensing/ms-github-cla-bot.png
imageWidth: '600'
imageHeight: '277'
---

# Signing CLAs

Any project that requires you to sign a CLA will have a bot set up when you first raise a pull request.

<!--

When you first raise a PR against a repo that has a CLA, a bot will make you sign it, and you will not be able to have your code merged until you sign this.

Once signed once, you don't need to sign it again.

This is an example of a Microsoft bot where you 'sign' with a specific comment that includes your employer if necessary.

-->

---


# How do I get started with a CLA?

[cla-assistant.io](https://cla-assistant.io/)


<!--

If you want to add a CLA to your projects, the CLA assistant can help! Register your repo at cla-assistant.io and it will set everything up including a CLA and a bot to check PR submitters.

-->

---

# An example CLA

[opensource.microsoft.com/pdf/microsoft-contribution-license-agreement.pdf](https://opensource.microsoft.com/pdf/microsoft-contribution-license-agreement.pdf)

3. Originality	of	Work.	You	represent	that	each	of	Your	Submissions	is	entirely	Your	original	work.	
Should	You	wish	to	Submit	materials	that	are	not	Your	original	work,	You	may	Submit	them	separately	
to	the	Project if	You	(a ) retain	all	copyright	and	license	information	that	was	in	the	materials	as	You	
received	them,	(b ) in	the	description	accompanying	Your	Submission,	include	the	phrase	“Submission	
containing	materials	of	a	third	party:”	followed	by	the	names	of	the	third	party	and	any	licenses	or	other	
restrictions	of	which	You	are	aware,	and	(c ) follow	any	other	instructions	in	the	Project’s	written	
guidelines	concerning Submissions.

<!--
Here is an example from the Microsoft CLA.

You	represent	that	each	of	Your	Submissions	is	entirely	Your	original	work

This means you are stating that the code is your own work and you own the copyright or license.
It also has a clause that if they are not your original work, then you have to share all the details and licenses for the code you submit to prove you are allowed to submit it.
-->

---

# An example CLA

[opensource.microsoft.com/pdf/microsoft-contribution-license-agreement.pdf](https://opensource.microsoft.com/pdf/microsoft-contribution-license-agreement.pdf)

5.	Licenses.	
a.	Copyright	License.	You	grant	Microsoft,	and	those	who	receive	the	Submission directly	or	
indirectly	from	Microsoft,	a	perpetual,	worldwide,	non-exclusive,	royalty-free,	irrevocable	license	in	the	
Submission	to	reproduce,	prepare	derivative	works	of,	publicly	display,	publicly	perform,	and	distribute	
the	Submission	and	such	derivative	works,	and	to	sublicense	any	or	all	of	the	foregoing	rights	to	third	
parties.


<!--
Here is an example from the Microsoft CLA.

You	grant	Microsoft a	perpetual,	worldwide,	non-exclusive,	royalty-free,	irrevocable	license to do whatever they like with the code.
Royalty free so you can't ask Microsoft for money for your code at any point.
-->

---

# Licenses


<div v-click="1">

- MIT

</div>

<div v-click="2">

- Apache 2.0

</div>

<div v-click="3">

- GNU GPL v3.0

</div>

<!--
We are now looking at licenses. These are the legal agreements by which an open source company will make their code available.
These define what you can do with the code, and what warranties and protections come with the code.

There are many licenses, but the most popular are:

MIT

Apache 2.0

GNU GPL v3.0

Let's look at these one by one
-->

---

# MIT License

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.

<div class="grid grid-cols-3 gap-4">
<div>

**Permissions**

🟢 Commercial use<br>
🟢 Distribution<br>
🟢 Modification<br>
🟢 Private use<br>

</div>
<div>

**Conditions**

🔵 License and copyright notice<br>

</div>
<div>

**Limitations**

🔴 Liability<br>
🔴 Warranty<br>

</div>
</div>

<!--

The MIT license is a very permissive license.

You can do whatever you want with the code - use it for free, use it for commercial use, whatever you want. The only requirements are you preserve the copyright of the original code.

The code is copyright the project, but anyone can do anything with it. You can publish it yourself under a different license, or as compiled code.

The project also has no liability for anything that goes wrong with the code, and you have no warranty. If the code doesn't do what it says, or breaks your billion dollar business, th project is not liable and you can't sue them.

You also cannot claim a patent on a derivative work - so if you use MIT code on a product that you try to patent, you can't.

-->

---

# Apache License 2.0

A permissive license whose main conditions require preservation of copyright and license notices. Contributors provide an express grant of patent rights. Licensed works, modifications, and larger works may be distributed under different terms and without source code.

<div class="grid grid-cols-3 gap-4">
<div>

**Permissions**

🟢 Commercial use<br>
🟢 Distribution<br>
🟢 Modification<br>
🟢 Patent use<br>
🟢 Private use<br>

</div>
<div>

**Conditions**

🔵 License and copyright notice<br>
🔵 State changes<br>

</div>
<div>

**Limitations**

🔴 Liability<br>
🔴 Warranty<br>

</div>
</div>

<!--

The Apache license is a very permissive license, similar to the MIT license.

Like MIT, you can do whatever you want with the code - use it for free, use it for commercial use, whatever you want. The only requirements are you preserve the copyright of the original code.

Also like MIT, the code is copyright the project, but anyone can do anything with it. You can publish it yourself under a different license, or as compiled code.

Again, like MIT, the project also has no liability for anything that goes wrong with the code, and you have no warranty.

The big difference between MIT and Apache is that the Apache license grants you the right to file patents on derivative works. This means if you use Apache licensed code in your product, you are able to apply for a patent if your idea is novel enough. The Apache license grants this, whereas there is nothing in the MIT license that allows for patents on derivate works.

-->

---

# GNU General Public License v3.0

Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

<div class="grid grid-cols-3 gap-4">
<div>

**Permissions**

🟢 Commercial use<br>
🟢 Distribution<br>
🟢 Modification<br>
🟢 Patent use<br>
🟢 Private use<br>

</div>
<div>

**Conditions**

🔵 Disclose source<br>
🔵 License and copyright notice<br>
🔵 Network use is distribution<br>
🔵 Same license<br>
🔵 State changes<br>

</div>
<div>

**Limitations**

🔴 Liability<br>
🔴 Warranty<br>

</div>
</div>

<!--

GPL is a copyleft license. Copy left means granting freedoms to those who use your work, but making those who use it also grant the same freedoms to others.

Essentially you can use GPL licensed code as you see fit, you can even sell products that use GPL code. But you MUST distribute the full source code of your product so that the purchaser is able to modify and distribute as they see fit.

For in-house products that are not released to the public, you don't need to release the source

-->

---

# Downside of the GPL

Anything you build to distribute (for free or paid), has to come with source code under the same license.

<!--

Although GPL makes code free and simple to use, it restricts the ability for folks to use your code in a commercial product as they may not want to distribute the source code as that may contain corporate secrets. Most companies ban the use of GPL licensed code in their products.

Some workarounds are to build separate programs as components that call each other. That way you only need to release the code of components of the system. For example - Linux is free but you pay for enterprise versions with tools built on top that are not covered by the GPL.

-->

---

# Software BoMs (bills of materials)

There is a big push for software BoMs, to track the components that do into software used commercially. This means tracking all the open source projects and code used.

This can help ensure license compliance by not using GPL code in a commercial product.

<!--

Software bills of materials are a big thing - some governments insist on them when buying software.

Partly corporations use these to monitor for supply chain attacks by knowing what goes into their software so they can monitor for security vulnerabilities.

Partly this is to ensure license compliance.

There is a problem when component A is released under the GPL, then used by component B that is then used by component C. Under the GPL all these components must be released under the GPL. This is hard to track with deep hierarchies of dependencies.

-->

---

# No license

What if there is no license? Simple - don't use the code.

<!--

If code doesn't have a license, then you have no rights to use it. So don't.

-->

---

# Changing a license

What happens if code is released as one license and you then want to change?

<!--

Changing licenses is hard. To change from a less permissive to more permissive is fine.

You cant change from GPL.

Once code has been released under one license, if you change to a less permissive license, then the previous version of the code are covered by the old license.

Check with a lawyer! Mozilla relicensed and it took years to get every contributor to agree.

-->

---

# Contributing

If you start an open source project, choose the license wisely. If you contribute, make sure you are happy with the license.

<!--

If you start an open source project, you must choose a license if you want folks to contribute to your code to they know what requirements there are on the end users of their contributions. Choose wisely - GPL may reduce the chance of your code being used.

If you contribute, make sure you are happy with the license that has been chosen.

-->

---

# Confused?

There are many other licenses. Essentially you can use MIT and Apache 2.0 licensed code in commercial products, but not GPL.

Always check with a lawyer for corporate use of open-source code.

More info: [choosealicense.com](https://choosealicense.com/)

<!--

For commercial use, always check with a lawyer. As a general rule you can use MIT and Apache licensed code, but be wary of others.

You can find more details and see a license comparison at choosealicense.com

-->

---
layout: image-center
image: https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/contributions-licensing/coding.png?raw=true
imageWidth: '800'
imageHeight: '400'
---

# Personal vs Company

<!--

When you make contributions, is there a difference between doing it on your own time or company time?

Yes and no - depends on the company.

-->

---

# Company contributions

When contributing as a employee of a company you must sign the CLA as that company and have company permission to contribute.

<!--

When you contribute as a representative of your employer you have to act as that employer.

When you sign the CLA you have to do so as an employee of your employer, and have their permission to do so. You don't want to be considered to be stealing intellectual property from your employer. This puts the open source project in a difficult position and can cost you your job or worse.

Some roles require you to contribute. Some roles don't but if you use open source projects it's nice to give back with bug fixes. Make sure first that you are allowed to.

Check with your corporate legal team before making any contributions if it is not a part of your role.

-->

---

# Personal contributions

Be warned - your employer may contractually own everything you do. The certainly own everything you do using company resources.

<!--

Some employment contracts state that your employer owns any intellectual property (IP) you create even outside of working hours. Therefor any open source contribution you make will be subject to their rules. Check your employment contract and company lawyers before making personal open source contributions.

If your employment contract does not give your employer rights to your own IP then make sure to not use company resources to make the contribution. Contributing in your own time on a corporate laptop means it could be seen as corporate IP.  Again - check with your corporate lawyers.

When looking for a job - make sure to ask these questions. Some companies have different rules for different internal organizations. Always ask, and get it in writing!

-->

---

# Personal vs work GitHub accounts

Should you keep your personal and work GitHub accounts separate?

<!--

This leads on to the question of should you have a separate GitHub account for work stuff and personal stuff.

This depends - some folks prefer it to keep good separation. Others just use one. Again - check with your companies legal team.

One upside of sharing an account especially if you work on open source as part of your job is to be able to publicly show your contributions to both personal and work projects. f you have separate accounts and you change jobs, your work account will be deleted and you will lose the ability to demonstrate your contributions.

One downside is you may have SSH keys or other access tokens on non-company hardware. If this gets breached, then hackers could get access to corporate IP. If you have keys or other access tokens on a personal device your employer may require you to have certain protections installed to mitigate this.

-->

---
layout: table-contents
gradientColors: ['#E0C3FC', '#8EC5FC']
---

# How To Contribute?


<div v-click="1">

- 📖 Documentation

</div>

<div v-click="2">

- 📈 Governance

</div>

<div v-click="3">

- ✏️ Design

</div>

<div v-click="4">

- ✏️ UI/UX

</div>

<div v-click="5">

- 📣 Advocacy and more!

</div>

<!--

We've looked at the legal side of contributing, now lets take a moment to look at the different ways you can contribute.

It's not all just writing code! There are so many other ways you can help with contributing to code.

You can write documentation.

You can help manage the project. Open source projects need governance to help run the project, define the road map, manage projects and contributors

You can help with design of graphics, assets, diagrams for documentation

You can help with the user interface design, or the user experience

You can advocate for the project by writing blog posts, giving talks about it, recording videos, or creating sample projects to use it.

I'm not going to focus on all these areas, just one: documentation

-->

---

# Contributing to docs

## Why?

<div v-click="1">

- It's the other 50% of the project.

</div>

<div v-click="2">

- It's a great way for you to understand how the project works.

</div>

<div v-click="3">

- You put a smile on someones face.

</div>

<!--

Documentation is the easiest way to have the biggest impact on a project. You don't need to understand how the code is written, just how to use the tool.

It's the other 50% of the project. Without documentation a project is useless. Most contributors prefer to write code than docs, so project docs are often lacking.
Docs include quickstarts, API docs, code walk-throughs, code tours, example projects and more!

The best way to learn anything is to teach it. By writing docs you have to know the project well enough to explain the concepts, and by explaining the concepts you will make mental leaps in your understanding.

Every developer gets frustrated by poor documentation. It can turn a great open source project into something unusable if an end user can't discover how to solve a problem or get something working. By creating great docs you make happy users.

-->

---

# Extra tips

<div v-click="1">

- Have fun!

</div>

<div v-click="2">

- Protect you and your work!

</div>

<div v-click="3">

- Be kind!

</div>

<!--

Some extra tips!

Firstly have fun. If you are giving up your time to contribute you want to enjoy doing it. Engage with the community around the project and have fun.

Secondly, protect you and your work. Check the license, check the requirements from your employer and check the CLAs

Finally, and most importantly - be kind. Everyone else using and contributing to these projects is a real person with real feelings, and often contributes in their own time for no reward. Be kind and realize others could be going through challenges, or not be able to communicate as well in the same language as you.

And if you are not kind, word may get around!

-->

---
layout: center
---

# Remember - Be kind

<!--

I can't hammer this home enough, be kind.

-->

---
layout: center
---

# Thank you

<!--

Thank you all for listening!

-->