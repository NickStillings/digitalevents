[Digital Events Overview](https://github.com/NickStillings/digitalevents/) | [Digital Event Planning](https://github.com/NickStillings/digitalevents/wiki/Digital-Event-Planning) | [Digital Event Venue](https://github.com/NickStillings/digitalevents/wiki/Digital-Event-Venue) | [Speaker Readiness](https://github.com/NickStillings/digitalevents/wiki/Speaker-Readiness) | [Webinars in Teams](https://github.com/NickStillings/digitalevents/wiki/Webinars-in-Teams) | [M365 Live Events](https://github.com/NickStillings/digitalevents/wiki/M365-Live-Events) | [Digital Event Toolkit](https://github.com/NickStillings/digitalevents/tree/main/Digital%20Toolkit)
---|---|---|---|---|---|---

***
## 04.30 | MN 365 User Group Admin Workshop Day Follow-up
Thanks for joining the session at the MN 365 Admin Workshop Day! below are the questions from chat that I wasn't able to answer during the session:

#### Virtual Event Ask Us Anything
Join us for a Microsoft Teams ‘Ask Microsoft Anything’ (AMA) for Virtual Events.  This AMA gives you the opportunity to connect with members of the product engineering team who will be on hand to answer your questions and listen to feedback.

- **Date: Wednesday, May 5, 2021**
- **Time**: 11:00 a.m. to 12:00 p.m. Central Time
- **Location**: [Microsoft Teams AMA Space](https://techcommunity.microsoft.com/t5/microsoft-teams-ama/bd-p/MicrosoftTeamsAMA)
- **Details**: [Virtual Event Tech Community Announcement](https://techcommunity.microsoft.com/t5/virtual-events-and-webinars/announcing-a-microsoft-teams-ama-for-virtual-evets-in-microsoft/m-p/2295175)

#### What solutions are there for users in a Low Bandwith situation (e.g. VPN) - Jessica H
Great question, most of the answer is "it depends" because there are multiple things impacting bandwith.
- We are rolling out "Low bandwidth mode", launched in March 2021, that will cap the data used in a Teams call. [Roadmap Details.](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=&searchterms=70786 "Roadmap Details.")
- There is a loooong list of considerations to optimize a corporate network for Teams. [Take a look at the this page](https://docs.microsoft.com/en-us/microsoftteams/prepare-network#bandwidth-requirements "Take a look at the this page") in docs.
- Turn off Incoming Video - An individual user can go to More Options > Turn Off Incoming Video in a meeting on a meeting-by-meeting basis
- You should enable [split-tunneling in your VPN](https://docs.microsoft.com/en-us/microsoft-365/enterprise/microsoft-365-vpn-split-tunnel?view=o365-worldwide "split-tunneling in your VPN") to optimize the connection from the remote user to the Office 365 service. This can have a huge impact on M365 services.

#### Do live captions work for everyone (guests, people joining in web client, etc)? We had some issues in the past with guests being able to enable live captiosn. - Tark S
- [Live Captions](https://support.microsoft.com/en-us/office/use-live-captions-in-a-teams-meeting-4be2d304-f675-4b57-8347-cbd000a21260 "Live Captions") today are available in the Desktop (PC and Mac) and Mobile Clients. They have not released in the Mobile Clients in the Government Cloud. If you have a user with a Microsoft 365 GCC subscription they won't have live captions. It's also possible [they are turned off in the attendees tenan](https://docs.microsoft.com/en-us/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps "they are turned off in the attendees tenant"). So If a user is joing from a meeting with live captions turned in their meetings policy, they can't use them. Otherwise Tark they should "just work" :-)

#### What is the Attendee experience for View-Only Overview in regards to their identity - if they are anonymous users, guest users, etc. does that impact how the View-Only experience works? - Tim 
- The attendees Join the meeting, then placed into View Only. So Tim they'd have to complete the meeting join experience (permissions, lobby experience) before getting to where Teams says "oh, meeting is full, here's view-only". So if you schedule a meeting, don't allow forwarding of the invite, and turn on meeting lobby: Attendee 1001 would need to be on the invite list, and admitted thru the lobby, then would get view only.  

#### What's the link to that View-Only PowerShell comment? - Multiple people
- Check out https://docs.microsoft.com/en-us/microsoftteams/view-only-meeting-experience.
- Note that View Only is still rolling out for GCC, and hasn't released for the DoD tenant (if you're doing a webinar with Federal employees)

#### Is there a way to send an email to Schedule a Meeting - Jason H
- Yes, a lot of us Microsoft folks use https://findtime.microsoft.com. You need an Office 365 subscription to schedule it, but attendee don't to reply. 
- If you want a non-O365 dependant service for private life, take a look at doodle.com. 

#### Can we "lock" a meeting and prevent new attendees from joining - Brian C
- It's on the roadmap! (the perpetual cry of the cloud vendor!!)
- Check here Brian: https://www.microsoft.com/en-in/microsoft-365/roadmap?featureid=80669 Good to see you, thanks for the shout out!


***

## Adoption Resources for Digital Events
Please bookmark these resources on the Microsoft 365 Adoption site. Sponsored by the Microsoft Teams Customer Advocacy Group, these resources compliment our technical documentation with guidance and best practices for adoption and usage of Microsoft Teams. 

**[Meetings and Webinars in Microsoft Teams](https://adoption.microsoft.com/meetings-and-webinars-in-microsoft-teams/) (Main Site)**
* [Meetings in Teams](https://adoption.microsoft.com/meetings-and-webinars-in-microsoft-teams/meetings/)
* [Webinars in Microsoft Teams](https://adoption.microsoft.com/meetings-and-webinars-in-microsoft-teams/webinars/)
* [Live Events in Microsoft Teams](https://adoption.microsoft.com/virtual-event-guidance/)

**[Meetings and Virtual Event Tech Community ](https://techcommunity.microsoft.com/t5/virtual-events-and-webinars/bd-p/TeamsVirtualEvents) (Tech Community forum for IT Pros)**


***

## Digital Events Overview
Large events and conferences are still valuable for employee and external engagement, but the format has changed with COVID-19. Digital events in Microsoft Teams can be a single webinar, a large interactive meeting, an all-hands broadcast, or a multi-session, multi-track digital experience.  Microsoft Teams includes built-in capabilities for interactive meetings, large group meetings, and webinars. In this session we'll see how these capabilities come together with out-of-the-box Microsoft 365 solutions. 

![A continuum of types of digital events](https://github.com/NickStillings/digitalevents/blob/main/Wiki%20Images/wiki.digitalevents.2.continuum.jpg)

- **Meetings and Calls** - Personal, engaging interaction meeting virtually, face-to-face.
- **Interactive Group Meetings** - Outcome-focused meetings to align on work, deliverables, status and next steps. Often scoped to a team, project, or specific stakeholders.
- **Town Halls** - Large, communication-focused meetings for internal or external communications, typically with some form of attendee moderation and a very curated list of speakers and topics.
- **Webinars** - External meetings with external participants, emphasizing attendance management and engagement, often with a specific call to action.
- **Broadcast Events** - Content delivered as a scalable media stream to a very large digital audience, often leveraging professional production tools and roles on the event team.
- **Virtual Conference** - Multi session, multi delivery channel event, often running over several days with a unifying theme and a complex planning and execution process.



***


## Case Study: Microsoft MVP/RD Summit and Build

The COVID-19 pandemic quarantine went into place just a few weeks before Microsoft&#39;s annual Most Valuable Professional (MVP)/Regional Director (RD) Summit, planned for March 2020. This event brings together Microsoft executives, product leaders and developers with our Most Valuable Professional (MVP) and Regional Director (RD) communities and serves all Microsoft product areas including Azure, Microsoft 365 and Business Applications Groups. With planning horizon of only a few weeks, we shifted to summit to a Digital Event, producing the event with Microsoft Teams and hosting the Summit in a Microsoft Team in Microsoft&#39;s production environment.

![Quotes from the Microsoft MVP Summit](https://github.com/NickStillings/digitalevents/blob/main/Wiki%20Images/wiki.digitalevents.1.mvp.jpg)

In the late spring of 2020, Microsoft hosted their annual Build conference as a completely digital event. Watch Microsoft CVP of global events, Bob Bejan, in a behind-the-scenes look at how Microsoft transitioned its flagship developer conference into a fully virtual event experience.

[![IMAGE ALT TEXT](https://github.com/NickStillings/digitalevents/blob/main/Wiki%20Images/wiki.digitalevents.4.build.jpg)](https://youtu.be/lSTzqk8strk "Video Title")
[Building Build: a behind-the-scenes look at #MSBuild](https://youtu.be/Vsi8ubQeXNIk)


***


## Digital Events Key Learnings

We learned four critical things from a year of shifting all our flagship conferences and events to a digital experience:

**1. Don&#39;t Translate, Remake**
- Don&#39;t attempting to deliver a traditional in-person event virtually by assuming the only change will be to shift from conference center breakout rooms to online meetings.
- Because the space between presenter and attendee has compressed from venue hall to laptop distance, digital events are more intimate, more authentic, and require a different approach to ensure success.

**2. Re-think your runway**
- With a virtual event, there are no travel and entertainment costs for attendees, and as a result no &quot;cost&quot; to attending the event early. 
- The attendee experience and engagement begins before the actual digital event begins, and continues after. Your digital event platform should include a toolset that allows engagement outside the timeframe of your actual event.
![Diagram of a digital event planning cycle](https://github.com/NickStillings/digitalevents/blob/main/Wiki%20Images/wiki.digitalevents.5.runway.jpg)

**3. Earn attention, Keep attention**
- As we learned in the COVID-19 pandemic, back-to-back online meetings create real fatigue and impact wellness. 
- Shorter content sessions with frequent are better. Downloadable deep-dive content and reference information for follow-up after the event can offset the shorter sessions.

**4. Connect with your audience**
- Leverage interstitial content and a &quot;hero stream&quot; to anchor the attendee experience can ensure a connection throughout the event, while social media, in-session chat and event communities can drive ongoing connection with the audience.
![Examples of Hero Stream and Interstitial Content](https://github.com/NickStillings/digitalevents/blob/main/Wiki%20Images/wiki.digitalevents.3.hero.jpg)
