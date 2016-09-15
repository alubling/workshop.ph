# Prehype - Workshop.ph


## Prehype Introduction

Since its founding, [Prehype](https://prehype.com) has been a venture development firm. We've mainly done 3 things:

* We incubate homegrown startups created by Prehype partners and EIRs
* We build new startups in conjunction with the world’s leading corporations
* We invest in startups and deals that our network can add value to


## Prehype API

Prior to the networked age of the Internet, computers were mainly silos. Installing software on a computer meant inserting a floppy disk and downloading software to only that computer's hard disk.

Businesses today are similarly built in relative isolation. In a perfect world, the building blocks of business would share a common language and be available on demand.

Rather than start from scratch on your own, you would be able to call on resources you needed to launch enterprises and increase your chance of success.

Entrepreneurs would be able to...
Companies would be able to...

Prehype is a platform for building businesses. It connects people and companies to the resources they need to build great new businesses. Those resources have been built and maintained by Prehype, and leverage the historical knowledge, resources, and people of the Prehype network.


## Workshop.ph

Workshop.ph is an API for accessing the Prehype process of **Idea Generation and Opportunity Identification**.

The process consists of preparatory research into a problem domain, followed by an intensive one week workshop that brings together domain experts, stakeholders, and Prehype network members to examine the problem domain and arrive at new business opportunities.

The output of Workshop.ph is one or several LPPs or Lean Product Plans.


## Lean Product Plan

The Lean Product Plan is the output of calling workshop.ph. A Lean Product Plan is a presentation that contains the right information to make a decision if you should move forward with the opportunity.

A Lean Product Plan combines the rational and emotional elements of making a business case.

![alt tag](https://github.com/alubling/workshop.ph/blob/master/LPP1.png)


Lean Product Plans vary, but they typically include:

  * Background and context on the problem
  * A unique insight that justifies exploring the opportunity
  * A description of the solution and how it works
  * A walkthrough of a user flow, or how the user interacts with the product or service
  * A business case including market analysis, business model, financials, and any other useful information.
  * A plan for the development of an MVP
  * A proposal for how to call [SignalMining.ph](#) to conduct a signal mining process to validate the plan

Additionally an LPP will always include:

  * Brand and identity work to create a new brand for the product or service
  * An initial design sprint worth of UX/UI work to visualize the product or service


The purpose of a Lean Product Plan is to distill the product idea into a concise and precise business proposal. Armed with an LPP, you can now go to internal stakeholders, investors, clients, partners, or potential customers and pitch the plan to decide whether to move onto a signal mining phase or directly into a new venture creation and MVP build.  


## Other Prehype APIs

* [Workshop.ph](#) - You’re looking at it!
* [People.ph](#) -
* [Syndicate.ph](#) -
* [SignalMining.ph](#) -


## Getting Started

To get started, install the Prehype npm package.

```sh
npm install prehype --save
```

Create a new client by identifying and authenticating yourself to the network.

```js
import Prehype = from ‘Prehype’;
const workshop = new Prehype.Client(apiKey: ’api key’, appId: ‘app id’);

```

## Usage

Once you've identified yourself to the Prehype network, you can kick off a workshop by making the following requests:


### Your Inputs

Three types of input are required from you to kickoff a workshop:

```js

const inputs = {

  // a several paragraph description of the problem space to be investigated and the central thesis of why this space should be investigated - note, this will be much more fleshed out if a Prehype member is NOT a facilitator. 
  "brief": "YOUR PROBLEM BRIEF",

  // returns a group of internal Prehypers necessary to conduct a workshop in this problem domain
  "people": people.ph("brief"),

}

// initiate a request with your inputs
workshop.yourInputs(inputs);
```


### Execution

Once a request is submitted, and parties agree to the terms of accessing the Prehype workshop.ph API, Prehype executes a workshop:

```js

workshop.execute(

	{Structure of Workshop}

  preparation();

  workshopWeek();

  output();

  next();

);

```

**Preparation**

This is what is involved in preparation.

```js
preparation();
```

**Workshop week**

The workshop week will have a photo here.

```js
workshopWeek();
```

**Output**

The output is something called an LPP, here's an example

```js
output();
```

**What happens next?**

The follow up involves us doing signalMining.ph

```js
next();
```

* Context
* Preparation
* Inputs
    * Prehype inputs
      * [People.ph](#)
    * Your/client inputs
* Timeline and Structure of the process
    * M -> what happens here?
    * T -> what happens here?
    * W -> what happens here?
    * T -> what happens here?
    * F -> what happens here?
* Outputs
* What happens next?
    * Reference -> [signalmining.ph](#)


## Examples


## Maintenance

Workshop.ph is maintained by Prehype partner [Amit Lubling](https://linked.com/amitlubling). Reached at `amit at prehype dot com`.

The compensation structure for maintaining the Workshop.ph API is...


## Getting Help and Opening Issues


## Contributing


## License
