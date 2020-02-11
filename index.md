---
title: Welcome to the Maker Event Playbook
keywords: homepage
tags: [getting_started]
sidebar: home_sidebar
permalink: index.html
summary: This guide will help you plan a maker event and to learn from the experience of other maker event producers.
---

## Maker Event Guides
Maker events come in all shapes & sizes - so we've separated this playbook into three guides by event type to help you learn from other events that are similar in scope to your planned event.

### Maker Socials
[Social events](makers_socializing.html) are not specifically about making things, but serve as a way to build and strengthen the Maker Community. Often it’s about connecting and sharing with other makers in a social setting. These may be networing events, or considered gatherings or relationship building.

* Socials (includes parties)
* Meetups / Maker Meetups
* Festivals
* Game Night
* Birthday Party
* Field Trips (visiting other places)
* Event (that someone else is putting on)
* Maker Conference (Speakers/Presentations/Ignite/BarCamp)
    * Seeing a Show / Talk (Mythbusters Live, TEDx Talk, etc.)

---

###  Makers in the Community
Bringing the passion for [making out into the world and sharing it](makers_going_into_community.html) with others is an important aspect of the Maker Community. This might include making or sharing at an event that someone else is organizing and hosting but you are just taking part in.

* Outreach (Going to do hands-on activities at other events)
* Building Competitions
* PPPRS Event
* Maker Camps (kid-based)
* Workshops for kids
* Make and Takes
* Maker Meetups (including meetups around Faires like Bring-a-Hack)
* Community Build (Magic Wheelchair/Art/Shared Project)
* All of these have a supply list or physical things?

---

### Hosting a Maker Event
A [Maker Event](makers_hosting_making.html) would include hands-on making or sharing of things people have made where you are organizing and producing the event and responsible for all that hosting entails.

* Build Competitions
* Maker Camps (kid based)
* Workshops for kids
* Make and Takes
* Fundraisers (Build to Bid)
* Meeting Location/Meetups (for other groups)
* Get Stuff Done - Working on the makerspace itself
* Makerspace/Hackerspace/Bullshit classes
* Maker Faire and Maker Fests (show and tells)
* Maker Markets/(M)Swap Meet (think selling)
* Maker Conference (Speakers/Presentations/Ignite/BarCamp)
* Maker Meetups (including meetups around Faires like Bring-a-Hack)
* Community Build (Magic Wheelchair/Art/Shared Project)
* Make-A-Thon/Hackathon/Game Jam
* Maker Art Gallery (Maker takeover of art gallery)
* Recovery/Support location (think after hurricanes)
* Makerspace open house / open night / open make ?

---

## Learn More & Get Involved
This playbook is a project created and maintained by the maker event producers that are part of the (Nation of Makers)[http://www.nationofmakers.us] community. We need your contributions to extend it to be a world-class resource for maker event producers!

### Contribute to the Maker Event Playbook
Want to contribute to the overall playbook? - [learn how to contribute](contributing.html)

### Create a Playbook for your Maker Event
You can easily create a playbook for your event - [learn how to create your own playbook](document_your_event.html)

### Why GitHub?
Wondering why this isn't a Wiki or a Google Doc? Someone should create a page to explain this!


## Maker Events

<div class="maker-events">
    <ul class="listing">
        {% assign events = site.events | sort: 'name' %}
        {% for event in events %}
        <li>
            <h2><a href="{{ event.url | prepend: site.baseurl }}">{{ event.name }}</a></h2>
            {{ event.content }}
        </li>
        {% endfor %}
    </ul>
</div>

Last change: {{ site.time }}


