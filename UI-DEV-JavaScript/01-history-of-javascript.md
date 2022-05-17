# The History of JavaScript:
JavaScript is a living language, which means new features and improvements are always being added into JavaScript. We will learn how a new feature gets added into JavaScript. For this we need to learn about three things which are: ECMA, ECMAScript, and the TC39.

In 1995, Websites were just a bunch of static texts not even closely related to the ones that we use today. Back then we used the Netscape Navigator as our primary web browser. At that time Netscape was the Google Chrome of web browsers having more than 805 of market share. The founder of Netscape, Mark Andreessen, He envisioned that the web should be more than just a simple way to share documents, he wanted to make client-server activity dynamic. He wanted a language which combines designers and developers together.

This is when Brendan Eich comes into the picture. Eich was hired by Netscape to embed the scheme programming language into the Netscape Navigator. But before he could do that Netscape partnered up with Sun Microsystems on their upcoming programming language called JAVA. Sun Microsystems wanted to make JAVA available on the browser.

If JAVA was perfect for a web browser? Why did Netscape Hired Eich? Its because they wanted to create a scripting language that was easy enough that even a designer or someone new can use and JAVA was not easy to learn. So Netscape made MOCA, which would later be called JavaScript. MOCA was for amateurs and designers while professionals used JAVA.

Because of the collaboration between Netscape and Sun Microsystems Netscape decided that MOCA should compliment JAVA and should have a similar syntax. Brendan Eich created the first version of MOCA in just about 10 days.(WOW!)

The first version of MOCA was a mix of functionality of scheme, it had the object orientation of small-talk, and the syntax of JAVA. The name MOCA changed to Live Script and then Live Script changed to JavaScript as a marketing measure to ride on the hype of JAVA.

Although JAVA was the professional tool for creating complex web components, and JavaScript was used by designers and amateurs. JavaScript changed how the users experienced websites, Microsoft at this point entered the game with Internet Explorer and their own implementation of JavaScript called JScript.

JavaScript and JScript were basically the same thing. But were from rivalling companies which led to more problems than solutions. JScript was exact same as JavaScript but had a slightly different way of implementing things. Which led to bigger problem than expected.

Websites built using JavaScript worked best on Netscape Navigator and Websites built with JScript worked best on Internet Explorer. Developers had to add a best viewed in IE/NN badges to their websites who couldn't build for both platforms.

Enter ECMA, ECMA international is an industry association founded in 1961, which is dedicated to standardize the communication and information systems. In November 1996 Netscape handed over JavaScript to ECMA to build a standard implementation of the language. This led to  other smaller implementors voicing their opinions on the evolution of the language and to keep every thing consistent with all browsers.

---

## ECMA and the TC39:
ECMA is governing body that standardizes JavaScript versions so that they are same across all web browsers. Each new specification comes with a standard and a committee.
JavaScript has the ECMA-262 standard and the committee which works on ECMA-262 is called TC39. Oracle owns the trademark for the name JavaScript, so to avoid any legal issues ECMA calls JavaScript ECMAScript. You will find this when search about the ECMA-262 standard.

The name ECMAScript is used for the official standard of the ECMA-262 while JavaScript is used while talking about the language in practice.  

TC39 stands for technical committee-39. Which consists of members who are generally browser vendors or companies who have invested highly into the language, such as Facebook(Meta) and PayPal.

Companies that are part of the TC39 send delegates who represents their companies at the TC39 meetings. These delegates are the ones who are responsible for creating, approving, or denying any feature that has been proposed to be added to the language.

Whenever a new proposal is created, it has to go through certain stages before it can be a part of the official language. 

### Stage 0:
Stage zero or the strawman stage proposals are that are planned to be presented to the committee or have not been rejected but do not meet the criteria to move to stage 1.

### Stage 1:
In order for any proposal to advance to stage one it must be presented by an official champion of the TC39 at the meeting who is responsible for the proposal and also define the problems it solves of the language and illustrative example along with a high level API example while also highlighting any potential concerns and implementation challenges.

### Stage 2:
At this point, the proposed feature could become a part of the official spec of the language. But to make it this far, the proposal should have an easy to read syntax and semantics of the feature in formal language. At stage 2 the feature should have a first version that will be written in the official language spec. Future changes can occur but they should only be minor and incremental changes.

### Stage 3:
Stage 3 is where the proposal is mostly finished and just requires feedback from the users and implementors, In order for a proposal to reach stage 3 the specifications of the proposal should be finished and implementations should be created.

### Stage 4:
At the final stage the proposal is ready to be included into the final spec of the language. But getting to stage 4 is not easy, You need to complete written test about the proposal, two or more spec implementation should pass through those tests, members have practical experience with the feature, and the ECMAScript editor must signoff on the spec text.

## Release schedule:
Since 2016 ECMAScript has been releasing new features that have passed the above criteria and adding them to the official spec. Each version is named with ES followed by the version number. ES6 was released in 2015 which added many new features to the language. Before 2015 the last update to ECMAScript was in 2011 which was called ES5.