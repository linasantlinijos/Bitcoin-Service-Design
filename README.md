# **Bitcoin Payments Service Design**

**How to design bitcoin payments across competing environments, and which levers move different user types.**

## **The Challenge and the Idea**

Bitcoin has made enormous progress as wallets have become easier to use, Lightning infrastructure has matured, payment integrations have expanded, and Bitcoin is now recognized globally.

Yet one question remains persistent: Why is bitcoin payment adoption seemingly lagging behind this progress, and the majority of people who already hold BTC still relatively rarely use it to pay?

Most Bitcoin team efforts to address payment adoption focus on improving individual touchpoints: onboarding flows, wallet experiences, checkout interactions, transaction speed, or payment rails. These improvements are important and continue to move the ecosystem forward.

But we wondered whether the biggest challenge is the broader service and ecosystem challenge.

Most of what our respondents revealed is somewhat already known in the Bitcoin community. That is the point. These constraints are often understood, sometimes obvious,  and they still rarely shape how products get built. Teams keep improving the payment flow, while the conditions that decide whether a payment happens at all sit outside it and stay unaddressed. The contribution here is not the findings. It is showing that they persist, that products keep getting designed around them instead of for them, and giving builders a method to catch this before they spend in the wrong place.

This is how we (service designer [Egle Karaliune-Jonzon](http://linkedin.com/in/egleobcarskaite) and Bitcoiner [Linas Kmieliauskas](https://www.linkedin.com/in/linas-kmieliauskas-82a4534/)) started our research, applying Service Design tools to bitcoin payments. The idea was to test what new perspectives and opportunities this methodology can bring for Bitcoin builders as they strive to reach as wide an audience as possible and build a strong and expanding user base. Using all available tools has now become crucial for Bitcoin teams as competition with other payment rails increases and new frontiers emerge, such as the agentic economy.

## **Why Service Design, and How It's Different From UX**

UX design helps optimize interaction, while service design explores whether those interactions happen at all.

It examines the broader system surrounding a product or a service: motivations, habits, environments, incentives, social contexts, competing alternatives, and the roles a product plays within people's lives.

In the context of bitcoin payments, this means asking questions that sit beyond the wallet interface:

* What role does bitcoin play in a person's life?  
* What problem is it solving?  
* What "job to be done" does it fulfill?  
* What conditions need to exist before spending becomes a natural choice?  
* What happens before and after the payment itself?

Rather than viewing bitcoin payments as isolated transactions, we wanted to understand them as part of a wider service ecosystem.

## **Our Approach**

At a glance:

* Service design as the method, with bitcoin payments as the brief.  
* Ten semi-structured interviews with Lithuanian BTC users.  
* Behavioral analysis through COM-B, Jobs-To-Be-Done, journey mapping, service blueprinting, and personas.  
* Three lenses: the competitive landscape, behavioral barriers, and cultural shifts.  
* Two phases.

We approached Bitcoin itself as the client with a clear brief: increase the adoption of BTC payments among bitcoin holders. As they've already been onboarded to bitcoin, mostly as an investment, we call the transition from investor to an active payment user the "second onboarding."

To explore this challenge, we conducted ten semi-structured interviews with bitcoin users ranging from long-term holders and active Lightning users to entrepreneurs, merchants, and former spenders who had stopped using bitcoin for payments.

For the purposes of this research, we focused on Lithuanian BTC users. Familiarity with the local context allowed us to move quickly while still capturing a diverse range of experiences and perspectives.

We analyzed the findings using a combination of service design and behavioral research tools, including journey mapping, service blueprinting, Jobs-To-Be-Done, persona development, and the COM-B behavioral framework.

Rather than focusing on whether people could spend bitcoin, we were interested in understanding when spending felt natural, when it did not, and why.

Therefore, we investigated this across three intertwined dimensions: the competitive landscape bitcoin payments operate in, the behavioral barriers that prevent holders from spending, and the cultural shifts needed to make BTC payments feel routine rather than mostly ideological.

Our research is divided into two phases. You'll find more details about the Phase 1 findings in the chapter below, while Phase 2 is briefly discussed in the *What's Next* chapter.

## **What We Found**

**Contextual Note:** *These findings are specific to our Bitcoin research, noting that the service design ecosystem might differ for each individual product and service.*

### **Spending Environment Is the Key Constraint**

An important pattern emerged: in most cases, the challenge was not the payment itself, but the broader spending environment.

Many participants expressed openness to paying with bitcoin and could easily imagine situations in which they would do so. Yet those situations rarely appeared in their everyday lives. Even motivated users often defaulted to fiat simply because bitcoin payments were not embedded within their existing routines, merchant networks, or consumption habits.

Therefore, if users rarely encounter situations where bitcoin feels like a *natural* payment option, improvements to the payment experience alone may have limited impact. As one of the participants put it, 

***"If I could pay at my local Spar, that might be the threshold where it actually makes sense to start thinking in BTC fully."***

### **Good Enough Is the Real Competitor**

The interviews also highlighted the strength of existing payment behaviors.

Participants did not necessarily express strong loyalty toward traditional payment systems. Rather, they described them as familiar, frictionless, and widely accepted. Cards, bank transfers, mobile payments, and increasingly stablecoins are already integrated into daily routines and require very little conscious thought. In contrast, bitcoin is still too much of an idea and not enough of a neutral service in the payment context. It's not bad *per se*, and is possibly even necessary in the early years of BTC adoption. The question is: are there enough ideologically motivated BTC spenders out there, and what exactly counts as 'enough'?

In either case, Bitcoin is competing against both alternative payment rails and established habits. This may help explain why ideological preference for bitcoin does not automatically translate into payment behavior, even among users who strongly support its underlying principles. As one of our respondents, a self-described "Bitcoin maxi," admitted, 

***"I use stablecoins more – more people around me use them, transactions are cheaper. People find stablecoins more intuitive."***

### **Bitcoin's Role Shapes Behavior**

As we all know, people do not relate to Bitcoin and bitcoin in a single way. Our respondents confirmed this. For some, BTC represented long-term savings and future security. Others saw it as a monetary tool that could be used in specific situations. Some viewed it as participation in an alternative financial system, while others approached it primarily through experimentation, investment, or technological curiosity.

What became increasingly clear was that these opinions shaped behavior. Understanding and valuing Bitcoin/bitcoin did not automatically translate into wanting to use it for payments.

### **Bitcoin Performs Different Jobs**

As we analyzed the interviews, we found it useful to think about bitcoin through the lens of Jobs-To-Be-Done. These different jobs created different relationships with spending. Participants who primarily relied on bitcoin as a long-term store of value often described a certain discomfort around using it for purchases. Even when the payment experience itself was straightforward, spending could feel like reducing something that was meant to be preserved. For other respondents, bitcoin, as a payment method, removed friction in their daily lives, for example, when paying artists, participating in poker tournaments, or paying salaries. In these cases, discomfort with paying in BTC correlated with the size of the transaction.

### **Earning and Spending Are Connected**

Another relevant pattern emerged among participants who earned bitcoin directly or regularly replenished spent BTC through DCA or other strategies.

These users were significantly more comfortable spending bitcoin than participants who primarily accumulated it. Rather than experiencing payments as a reduction of savings, they tended to see bitcoin as something circulating through a broader economic system in which they were already participating.

This suggests that acquisition and spending may be more closely connected than they are often treated in product development. The path to increased payment adoption may therefore involve not only improving spending experiences, but also understanding how users acquire and replenish bitcoin in the first place.

## **Artifacts**

One of the main outputs of the project was a behavioral framework for understanding bitcoin users (built specifically for our research, so it might look different for other products and services).

Rather than segmenting users by demographics, transaction volume, or technical expertise, we developed personas based on mental models, motivations, and the role bitcoin plays within people's broader financial lives. These personas represent different relationships with bitcoin and different barriers to payment adoption.

The framework helped us move beyond the idea of a single "bitcoin user" and instead understand how different users may require different adoption strategies depending on what BTC is doing for them and what they are trying to achieve.


<img width="928" height="1130" alt="image_3" src="https://github.com/user-attachments/assets/af05f526-a6d2-4c95-9ace-87fbcd407636" />



### **BTC Persona Framework**

The purpose of this framework is to help Bitcoin teams make better design and product decisions about payment adoption. 

Rather than assuming a single "bitcoin user," the framework highlights how different users relate to bitcoin in fundamentally different ways. These differences influence whether they see bitcoin as something to hold, something to spend, or something that serves both functions.

The framework can be used to identify which user groups a product serves today, which groups it aims to serve in the future, and which interventions are most likely to influence payment behavior. It is intended to support product strategy, feature prioritization, messaging, ecosystem development, and research by helping teams focus on the barriers and opportunities that matter most for each user type.

#### **How to read the framework**

Each persona represents a distinct relationship with bitcoin, defined by three interconnected elements: the mental model of what bitcoin is, the primary job bitcoin is hired to perform, and the resulting payment behavior.

<img width="1471" height="1010" alt="bitcoin_payment_behaviour_v3" src="https://github.com/user-attachments/assets/daeb32eb-07df-4214-8c51-328961cba3ea" />



__________________________________________



### **BTC Personas**

The personas should not be understood as rigid categories. Instead, they represent recurring behavioral patterns observed across users. Individuals may move between personas over time as their understanding of bitcoin evolves, their circumstances change, or they become more deeply embedded in the bitcoin ecosystem.

<img width="2880" height="1620" alt="holder" src="https://github.com/user-attachments/assets/39e2f75a-4ec8-4ad9-af9b-2fffd1463e3c" />


__________________________________________


<img width="2880" height="1620" alt="pragmatist" src="https://github.com/user-attachments/assets/0bfeedea-93a6-4adf-99ed-5d1777789d9e" />


__________________________________________


<img width="2880" height="1620" alt="native" src="https://github.com/user-attachments/assets/9bd43d62-6c08-43b3-89ba-0a3180b2ec45" />


__________________________________________


<img width="2880" height="1620" alt="curious" src="https://github.com/user-attachments/assets/7a0e252c-6b0f-4501-988e-ca5b082fe05e" />



__________________________________________



### **Barriers & Levers by Persona** 

Opportunity binds three of the four personas. Most of the addressable problem is environmental rather than interface-level. Each lever must match its gate; otherwise, the spend doesn't happen.

<img width="1600" height="2623" alt="barriers_levers" src="https://github.com/user-attachments/assets/b207579e-8622-4caf-8701-594bbcaf305a" />



## **Suggestions to Bitcoin Builders**

* When building bitcoin payment products, understand and design for the wider system that shapes whether BTC transactions happen at all.  
* Think about the interaction between bitcoin mental models, jobs-to-be-done, and the wider service ecosystem surrounding payments.  
* Understand the full user journey: where they are coming from, their daily lives, what their relationship with bitcoin is, etc.  
* Learn where you can actually move the needle and where you'd waste your resources.

The lesson is not that we found something really new. Most of it is already known in the Bitcoin community. The lesson is that this knowledge rarely reaches the design stage – and a service design method is what brings it there: it shows which constraint binds your users, and where effort actually moves them.

Therefore, focusing on designing the wider service conditions in which BTC payments become meaningful, available, and habitual – and doing it with a clear understanding of the BTC user, their behavior, and the competitive landscape – is possibly the most efficient way to accelerate BTC payment adoption.

This means builders need to understand the whole user journey – where users are coming from, where they stand, how they obtain BTC, what role bitcoin currently plays in a user's life, and what mental and physical obstacles are preventing them from trying your product and continuing to use it.

Say you find that the biggest constraint on spending from your local region-focused wallet is that there's nowhere to spend. Improving your checkout flow won't buy traction – but knowing that is what lets you allocate your resources more efficiently. For example, by shifting effort to the merchant side.

In short, you get to know which lever – **capability**, **opportunity**, or **motivation** – actually moves each persona to use your product, and which doesn't.

Also, with agentic payments, a new spending environment is being built as we speak. While this emergent ecosystem and infrastructure are changing fast, service design questions related to how an agent chooses payment rails, consent, delegation, recovery, and accountability will be relevant no matter what shape the agentic economy takes. This is also going to be one of our Phase 2 research topics.

To summarize, when building Bitcoin products – for humans, AI, or both – teams need to understand that their challenge sits somewhere between infrastructure, behavior, incentives, culture, and everyday life. While the idea of Bitcoin is powerful, BTC payments are shaped by whether they become embedded in the systems, contexts, and routines where payment behavior actually takes place.

## **What's Next**

In Phase 2, we aim to build on the Phase 1 outputs, deepen the research, and create practical open-source tools for Bitcoin product teams.

The exact scope and timeline are still being defined.

## **Acknowledgements**

We thank [**Christoph Ono**](https://gbks.substack.com/) of the [Bitcoin Design Foundation](https://bitcoindesignfoundation.org/) and [**Conor Okus**](https://x.com/conorokus) of [Spiral](https://spiral.xyz/) for helping shape our research, providing valuable insights, and steering us toward Phase 2 of this project. This work would also be less valuable without the 2021 Spiral-funded [Bitcoin UX research](https://patestevao.com/work/bitcoin-ux-research/) conducted by [**Patrícia Estevão**](https://patestevao.com/).  
