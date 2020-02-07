---
title: The Internet is for End Users
docname: draft-iab-for-the-users-latest
date: {DATE}
category: info
workgroup: Internet Architecture Board (IAB)

ipr: trust200902
submissionType: IAB
keyword: constituent
keyword: constituency
keyword: relevant parties
keyword: end users
keyword: endpoint
keyword: stakeholder

stand_alone: yes
pi: [toc, tocindent, sortrefs, symrefs, strict, compact, comments, inline]

author:
 -
    ins: M. Nottingham
    name: Mark Nottingham
    organization:
    email: mnot@mnot.net
    uri: https://www.mnot.net/

informative:
  TUSSLE:
    target: http://groups.csail.mit.edu/ana/Publications/PubPDFs/Tussle2002.pdf
    title: "Tussle in Cyberspace: Defining Tomorrow's Internet"
    author:
      -
        ins: D. Clark
        name: David D. Clark
        organization: MIT Lab for Computer Science
      -
        ins: K. Sollins
        name: Karen R. Sollins
        organization: MIT Lab for Computer Science
      -
        ins: J. Wroclawski
        name: John Wroclawski
        organization: MIT Lab for Computer Science
      -
        ins: R. Braden
        name: Robert Braden
        organization: USC Information Sciences Institute
    date: 2002


--- abstract

This document explains why the IAB believes the IETF should consider end users as its highest priority concern, and how that can be done.


--- note_Note_to_Readers

The issues list for this draft can be found at <https://github.com/intarchboard/for-the-users/issues>.

The most recent (often, unpublished) draft is at <https://intarchboard.github.io/for-the-users/>.

Recent changes are listed at <https://github.com/intarchboard/for-the-users/commits/master>.

See also the draft's current status in the IETF datatracker, at
<https://datatracker.ietf.org/doc/draft-iab-for-the-users/>.

--- middle

# Introduction

Many who participate in the IETF are most comfortable making what we believe to be purely technical decisions; our process is defined to favor technical merit, through our well-known mantra of "rough consensus and running code."

Nevertheless, the running code that results from our process (when things work well) inevitably has an impact beyond technical considerations, because the underlying decisions afford some uses while discouraging others. While we believe we are making only technical decisions, in reality, we are defining (in some degree) what is possible on the Internet itself.

This impact has become significant. As the Internet increasingly mediates essential functions in societies, it has unavoidably become profoundly political; it has helped people overthrow governments and revolutionize social orders, swing elections, control populations, collect data about individuals, and reveal secrets. It has created wealth for some individuals and companies while destroying others'.

All of this raises the question: For whom do we go through the pain of gathering rough consensus and writing running code?

After all, there are a variety of parties that standards can benefit, such as (but not limited to) end users, network operators, schools, equipment vendors, specification authors, specification implementers, content owners, governments, non-governmental organisations, social movements, employers, and parents.

Successful specifications will provide some benefit to all of the relevant parties because standards do not represent a zero-sum game. However, there are sometimes situations where there is a need to balance the benefits of a decision between two (or more) parties.

In these situations, when one of those parties is an "end user" of the Internet -- for example, a person using a Web browser, mail client, or another agent that connects to the Internet -- the Internet Architecture Board argues that the IETF should favor their interests over those of other parties.

{{who}} explains what is meant by "end users"; {{why}} outlines why IETF work should prioritise them, and {{how}} describes how we can do that.


# Who Are "End Users"? {#who}

In this document, "end users," means non-technical users whose activities IETF standards are designed to support, sometimes indirectly. Thus, the end user of a protocol to manage routers is not a router administrator; it is the people using the network that the router operates within.

End users are not necessarily a homogenous group; they might have different views of how the Internet should work, and might occupy several roles, such as a seller, buyer, publisher, reader, service provider and consumer. An end user might be browsing the Web, monitoring remote equipment, playing a game, video conferencing with colleagues, sending messages to friends, or performing an operation in a remote surgery theatre. They might be "at the keyboard", or represented by software indirectly (e.g., as a daemon).

Likewise, an individual end user might have many interests (e.g., privacy, security, flexibility, reachability) that are sometimes in tension.

A person whose interests we need to consider might not directly be using a specific system connected to the Internet. For example, if a child is using a browser, the interests of that child's parents or guardians may be relevant. A person pictured in a photograph may have an interest in systems that process that photograph; a person entering a room with sensors that send data to the Internet has interests that may be involved in our deliberations about how those sensor readings are handled.

While such less-direct interactions between people and the Internet may be harder to evaluate, this document's concept of end-user nonetheless includes such people.


# Why The IETF Should Prioritise End Users {#why}

Even before the IETF was established, the Internet technical community has focused on user needs since at least {{?RFC0001}}, which stated that "One of our goals must be to stimulate the immediate and easy use by a wide class of users."

And, while we specialise in technical matters, the IETF is not neutral about the purpose of its work in developing the Internet; in "A Mission Statement for the IETF" {{?RFC3935}}, the definitions include:

> The IETF community wants the Internet to succeed because we believe that the existence of the Internet, and its influence on economics, communication, and education, will help us to build a better human society.

Later in Section 2.1, "The Scope of the Internet" it says:

> The Internet isn't value-neutral, and neither is the IETF. We want the Internet to be useful for communities that share our commitment to openness and fairness. We embrace technical concepts such as decentralized control, edge-user empowerment and sharing of resources, because those concepts resonate with the core values of the IETF community. These concepts have little to do with the technology that's possible, and much to do with the technology that we choose to create.

In other words, the IETF is concerned with developing and maintaining the Internet to promote the social good, and the society that the IETF is attempting to enhance is composed of end users, along with groups of them forming businesses, governments, clubs, civil society organizations, and other institutions.

Merely advancing the measurable success of the Internet (e.g., deployment size, bandwidth, latency, number of users) is not an adequate goal; doing so ignores how technology is so often used as a lever to assert power over users, rather than empower them.

Beyond fulfilling the IETF's mission, prioritising end users also helps to ensure the long-term health of the Internet and the IETF's relevance to it. Perceptions of capture by vendors or other providers harm both; the IETF's work will (deservedly) lose end users' trust if it prioritises (or is perceived to prioritise) others' interests over them.

Ultimately, the Internet will succeed or fail based upon the actions of its end users, because they are the driving force behind its growth to date. Not prioritising them jeopardizes the network effect which the Internet relies upon to provide so much value.


# How The IETF Can Prioritise End Users {#how}

There are a few ways that the IAB believes the IETF community can prioritise end users, based upon our observations. By its nature, this is not a complete list.

## Engaging the Internet Community

The IETF community does not have any unique insight into what is "good for end users," and it is not uncommon for us to be at a further disadvantage because of our close understanding of some -- but not all -- aspects of the Internet.

At the same time, we do have a culture of considerable deference to a broader "Internet community" in our decision-making processes. Mere deference, however, is not adequate; even with the best intentions, we cannot assume that our experiences of the Internet are those of all of its end users, or that our decisions have a positive impact upon them.

Therefore, we have not only a responsibility to analyse and consider the impacts of the IETF's work, but also a responsibility to consult with that greater Internet community. We should enter into a dialogue about not only the technical concerns that are well-represented in the IETF but also the political, social and economic concerns that it engenders, and that are better represented elsewhere.

The IETF community faces significant hurdles in doing so. Our work is specialised and often esoteric, and processes for developing standards often involve very long timescales. Affected parties are rarely technical experts, and their experience of the Internet is often based upon incomplete (and sometimes inaccurate) models. Often, even when we try to engage a broader audience, their participation is minimal -- until a change affects someone in a way they don't like. Surprising the Internet community is rarely a good outcome.

Government-sponsored individuals sometimes participate in the IETF community. While this is welcome, it should not be taken as automatically representative of end users elsewhere, or even all end users in the relevant jurisdiction. Furthermore, what is desirable in one jurisdiction (or at least to its administrators) might be detrimental in others (see {{conflict}}).

While some civil society organisations specialise in technology and Internet policy, they typically do not have the capacity to participate broadly, nor are they necessarily representative of the larger Internet community. Nevertheless, their understanding of end user needs is often profound, and they are in many ways the best informed advocates for end user concerns; they should be considered a primary channel for engaging the broader Internet community.

A promising approach to help fill these gaps is to identify and engage with specifically affected communities; for example, one or more industry associations, user groups, or a set of individuals, though we can't of course formally ensure that they are appropriately representative.

In doing so, we should not require them to  "come to us"; unless a stakeholder community is already engaged in the IETF process effectively, the IETF community should explore how to meet with them on their terms -- taking the initiative to contact them, explain our work, and solicit their feedback.

In particular, while IAB workshops, BoFs and Bar BoFs can be an effective mechanism to gather input within our community, they often do not have the visibility in other communities that is required to solicit input, much less effective participation.

Instead, an event like a workshop may be more effective if co-located with -- and ideally hosted or co-hosted by -- a forum that's familiar to that stakeholder community. We should also take the opportunity to raise the visibility of IETF work (or potential IETF work) in such fora through conference talks, panels, newsletter articles, etc.

When we engage with the Internet community, we should also clearly identify tailored feedback mechanisms (e.g., subscribing to a mailing list may not be appropriate), and assure that they are well-known in those communities.

Finally, we should remember that the RFC series are Requests For Comments; if there are serious implications of our work, we should document them and ask for feedback from the Internet Community.


## Creating User-Focused Systems

We should pay particular attention to the kinds of architectures we create, and whether they encourage or discourage an Internet that works for end users.

For example, one of the most successful Internet applications is the Web. One of its key implementation roles is that of the Web browser -- called the User Agent in {{?RFC7230}} and other specifications. Because there are multiple interoperable implementations, end users can switch with relatively low costs, and as a result there is a natural tendency to more carefully consider the user's needs as an agent. This leads to Web browsers' interests being better aligned with those of their end users, creating an ecosystem that is more user-focused (even if there are imbalances of power between implementations and barriers to entry for new implementations).

In contrast, the Internet of Things (IoT) has not yet seen the emergence of a natural role that reflects the needs of the end user. Perhaps as a result of this, that ecosystem and its end users face serious challenges.

We should also create explicit roles for end users in our protocols where appropriate, and respect them.


## Identifying Negative End User Impact

At its best, our work will unambiguously promote the collective social good. In some cases, we will consciously decide to be neutral and open-ended, allowing the "tussle" among stakeholders to produce a range of results (see {{TUSSLE}} for further discussion).

At the very least, however, we must examine our work for negative impact on end users, and take steps to mitigate it where encountered. In particular, when we've identified a conflict between the interests of end users and other stakeholders, we should err on the side of protecting end users.

Note that "negative impact on end users" is not defined in this document; that is something that the relevant body (e.g., Working Group) needs to discuss and come to consensus on. Merely asserting that something is harmful is not adequate. The converse is also true, though; it's not good practice to avoid identifying harms, nor is it acceptable to ignore them when brought to our attention.

The IAB and IETF have already established a body of guidance for situations where this sort of conflict is common, including (but not limited to) {{?RFC7754}} on filtering, {{?RFC7258}} and {{?RFC7624}} on pervasive surveillance, {{?RFC7288}} on host firewalls, and {{?RFC6973}} regarding privacy considerations.

Much of that advice has focused on maintaining the end-to-end properties of a connection {{?RFC3724}}. This does not mean that our responsibility to end users stops there; decisions might affect them in other ways. For example, data collection by various applications even inside otherwise secure connections is a major problem on the Internet today. Also, inappropriate concentration of power on the Internet has become a concerning phenomenon -- one that protocol design might have some influence upon.


## Handling Conflicting End User Needs {#conflict}

When the needs of different end users conflict (for example, two sets of end users both have reasonable desires) we again should try to minimise negative impact.

For example, when a decision improves the Internet for end users in one jurisdiction, but at the cost of potential harm to others elsewhere, that is not a good tradeoff. As such, we effectively design the Internet for the pessimal environment; if a user can be harmed, they probably will be, somewhere.

There may be cases where genuine technical need requires compromise. However, such tradeoffs are carefully examined and avoided when there are alternate means of achieving the desired goals. If they cannot be, these choices and reasoning ought to be thoroughly documented.


## Deprioritising Internal Needs

There are a number of needs that are very visible to us as specification authors, but should explicitly not be prioritised over the needs of end users.

These include: convenience for document editors, IETF process matters, and "architectural purity" for its own sake.


# IANA Considerations

This document does not require action by IANA.

# Security Considerations

This document does not have any direct security impact; however, failing to prioritise end users might well affect their security negatively in the long term.


--- back

# Acknowledgements

This document was influenced by many discussions, both inside and outside of the IETF and IAB. In particular, Edward Snowden's comments regarding the priority of end users at IETF 93 and the HTML5 Priority of Constituencies were both influential.

Many people gave feedback and input, including Harald Alvestrand, Mohamed Boucadair, Stephen Farrell, Joe Hildebrand, Lee Howard, Russ Housley, Niels ten Oever, Mando Rachovitsa, Martin Thomson, Brian Trammell, John Klensin, Eliot Lear, Ted Hardie, and Jari Arkko.
