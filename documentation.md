---
title: Documentation
layout: page
permalink: /documentation.html
---
# Project Documentation 
## Overview

**Remembering Old Roblox: A Digital Archive of Discontinued Platform Features** is a digital archive that documents features, systems, and interfaces that have disappeared or transformed over time on the Roblox platform.

While Roblox is often understood as a game, this project approaches it as a layered digital infrastructure composed of interconnected systems: economy, identity, communication, access, interface design, and membership structures.

The archive preserves traces of earlier platform versions through screenshots, archived webpages, wiki documentation, community discussions, and official announcements. Rather than recreating “Old Roblox,” it focuses on documenting how the platform functioned at different historical moments and what is lost when systems are removed or redesigned.

---
# Significance of the Project 

Digital platforms often present themselves as stable and continuous systems. In reality, they are constantly changing. Features disappear, interfaces are redesigned, communities migrate, and forms of participation become impossible. As these changes occur, important aspects of platform history can be lost or become difficult to access.

By documenting discontinued Roblox systems, this archive demonstrates how platforms are not fixed technologies but evolving infrastructures shaped by governance decisions, economic systems, and interface design.

The project also highlights the importance of preserving everyday digital experiences. Features such as Tix, guest accounts, forums, and Builders Club memberships may seem minor when viewed individually, but they shaped how users participated in the platform, formed communities, and understood their identities online.

More broadly, the archive demonstrates how digital humanities methods can be used to study platform history through archival practices, metadata creation, and the preservation of digital traces that might otherwise disappear.

--- 

## Relationship to the Landing Page

The landing page presents Roblox as a collection of five interconnected systems:

- Tix (Economy)
- Guest Accounts (Access & Identity)
- Forums (Communication)
- Interface History (Navigation & UI)
- Builders Club (Membership & Status)

Each section acts as an entry point into a broader system of platform infrastructure.

This documentation page expands that structure by explaining how those systems were selected, interpreted, and organized, as well as the conceptual and technical decisions behind the archive.

Together, the landing page and documentation form a two-layer structure:

- The landing page = interface for exploration and navigation  
- This documentation = explanation of design logic, methods, and conceptual framing  

---

# Conceptual Framework

This archive is informed by platform studies and digital archival thinking, treating Roblox not as a single game but as a layered system of infrastructure.

The five categories used in the landing page are not arbitrary topics, but interpretive systems:

Tix = virtual economy and currency structures

Guest Accounts = identity and access systems

Forums = communication infrastructures

Interface History = UI and navigation evolution

Builders Club = monetization and status systems

These systems represent different dimensions of how users experienced the platform at different historical moments.

--- 
## Theoretical Influence

This project was influenced by Benjamin Bratton’s concept of layered infrastructure in *The Stack*. Bratton’s model helped shape how I understand platforms as multi-layered systems rather than single technologies. During the workshop I attended at DH@Guelph, "Dead Media, Living Data: Hacking the Archive" we discussed Bratton's idea that digital technologies are built from multiple interconnected layers rather than existing as single systems. That idea changed how I thought about Roblox.

Instead of treating artifacts as isolated features, I structured metadata so that each item connects to broader infrastructural layers such as economy, communication, identity, governance, and interface.

For example:
- A Tix artifact is tagged not only as “Tix” but also as Economy and Currency
- Forum artifacts connect to Communication and Governance
- Guest account materials connect to Identity and Access

This structure allows users to move between layers and understand Roblox as an interconnected system rather than a linear history.

---

## Major Features of the Archive
The archive is organized around five systems that represent different parts of Roblox's platform history.

### Tix
This section documents Roblox’s discontinued and evolving virtual economy systems, including Tickets (Tix), Robux exchange structures, and monetization changes.

Subjects include:
- Tix  
- Economy
- Currency
- Interface 
- Early Roblox 

---

### Guest Accounts 
This section focuses on how users entered and existed within the platform, including guest accounts and avatar systems.

Subjects include:
- Guest Accounts  
- User onboarding  
- Identity
- Safe chat  
- User restrictions  

---

### Forums 
This section documents Roblox forums and early community discussion spaces that shaped participation and feedback.

Subjects include:
- Forums  
- Communication 
- Community Discussion
- Governance  

---

### Interface 
This section focuses on how Roblox’s website and navigation systems changed over time.

Subjects include:
- Interface history  
- Homepage
- Navigation 
- User experience  

---

### Builders Club
This section documents Builders Club and its tiers as systems of monetization, identity, and status.

Subjects include:
- Builders Club 
- Digital status  
- Monetization  
- Membership Systems 

---

## Metadata Choices

Metadata forms the organizational structure of the archive and allows artifacts to be searched, grouped, and interpreted.Rather than functioning only as descriptive labels, the metadata provides historical context and reveals relationships between different parts of Roblox's platform history.

The archive uses CollectionBuilder's CSV metadata framework. Each artifact includes the following fields:

Title = identifies the artifact.

Date = records when the documented feature, webpage, or system existed or was published.

Description = summarizes the artifact's historical significance and explains what it documents.

Subject = categorizes the artifact within broader platform systems.

Source = identifies the original webpage or archive from which the artifact was obtained.

Format = identifies the media type (such as webpage, screenshot, forum post, or image).

Rights = records the rights statement associated with the artifact.

The Subject field became the most significant metadata element in this project. Rather than simply assigning keywords, subjects were designed to connect individual artifacts to larger infrastructural systems within Roblox. Each artifact is assigned one primary subject representing its main category, alongside several broader subjects that connect it to related themes across the archive.

For example:
- Tix artifacts connect to Economy and Currency.
- Guest Account artifacts connect to Identity and Access.
- Forum artifacts connect to Communication and Governance.

This approach allows users to discover artifacts through multiple conceptual pathways rather than a single category, emphasizing the relationships between systems that shaped the Roblox platform.

These metadata choices were informed by the needs of a digital archive rather than a chronological collection. Because the project documents platform history, the metadata needed to support both discovery and interpretation. Instead of only describing what an artifact is, the metadata explains how it fits within the broader history of Roblox's evolving infrastructure.

---

# Data and Sources

The archive is built from 45 artifacts gathered from publicly available historical materials:
- Roblox Wiki documentation   
- Archived webpages  
- Historical Screenshots 
- Community forums   
- Reddit posts  
- Blog posts  
- Roblox announcements  
- User-created documentation  

The archive is not comprehensive. It is a curated collection focused on significant transitions in platform infrastructure and user experience.

Many original materials no longer exist, so screenshots and archived traces become essential forms of evidence.

---

# Tools

The project was developed using:

- CollectionBuilder-GH
- GitHub Pages
- GitHub
- CSV Metadata spreadsheets 
- Archived web materials
- Historical screenshots

---
# Process and Changes in Approach 

The project developed through a multi-stage workflow that combined archival research, metadata design, and web-based implementation.

The first stage involved defining the scope of the archive by identifying discontinued Roblox systems that would form the structure of the project. Although Roblox has many historical changes, I narrowed the focus to five key systems, (Economy (Tix), Guest Accounts, Forums, Interface History, and Builders Club) because they best represented shifts in platform infrastructure, identity, and participation.

The second stage involved locating and collecting historical materials. This included archived Roblox webpages, wiki documentation, screenshots of early interfaces, Reddit discussions, official blog posts, and community-generated archives. This stage was ongoing rather than linear, as new sources often changed how I understood or categorized existing materials.

The third stage focused on metadata creation using CollectionBuilder’s CSV-based system. Each artifact was entered manually and assigned structured fields such as title, date, description, subject, source, format, and rights. During this stage, I repeatedly revised subject categories as relationships between artifacts became clearer. What initially appeared as separate features often overlapped across broader systems such as economy, identity, and governance, which led to refinements in how metadata was structured. 

The fourth stage involved implementing the archive through GitHub Pages and connecting metadata records to uploaded media files. This stage also included testing navigation, adjusting layout decisions, and refining how users move between categories. 

The project did not follow a strictly linear workflow. Instead, research, design, metadata creation, and interface development influenced each other continuously. Decisions made in one part of the project often required adjustments elsewhere, especially when refining how systems were grouped and how users would experience the archive.

A significant change in approach occurred in how I understood Roblox itself. At the beginning of the project, I primarily understood Roblox as a game platform. However, through research and engagement with platform studies concepts, I began to see it as a layered infrastructure composed of interconnected systems. This shift directly influenced how the archive was structured, moving away from chronological organization toward system-based categorization.

Another major shift involved moving from a more static idea of “collection building” to a more interpretive understanding of metadata. Instead of treating metadata as purely descriptive, I began to see it as a curatorial tool that shapes how relationships between artifacts are constructed and interpreted by users. 

---

# How to Use the Archive

Visitors can explore the archive through the landing page, which introduces five interconnected systems of Roblox history: Economy (Tix), Guest Accounts, Forums, Interface History, and Builders Club.

Each section of the archive functions as an entry point into a broader infrastructural layer of the platform. Users are not required to follow a linear path and can move between categories freely depending on their interests.

However, a suggested short walkthrough (approximately 10 minutes) is: 

1. Begin with the Tix Economy section to understand Roblox’s former virtual currency system and how value circulated within the platform.
2. Explore Guest Accounts to examine how identity and access shaped early user participation.
3. Move to Forums to see how communication and community discussion functioned before their closure.
4. Compare different versions of the Interface History to understand how navigation and user experience evolved over time.
5. Finish with Builders Club to examine systems of membership, status, and monetization.

Following this sequence helps reveal how each system connects to broader platform infrastructures, moving from economy and access to communication, interface design, and membership structures.

Each artifact includes metadata such as title, date, description, subject tags, source information, and rights information. These fields allow users to understand both the historical context of each item and how it connects to other parts of the archive.

Rather than functioning as a fixed narrative, the archive is designed to support exploration through connected systems. Users can follow their own paths through the collection depending on which aspects of Roblox history they want to investigate.

---

# Ethical Considerations

This project is built using publicly available historical materials, including archived webpages, screenshots, Roblox Wiki documentation, official Roblox announcements, Reddit discussions, and community-created resources.

Many of these materials were originally created for purposes other than academic research. Although they are publicly accessible, they often include usernames, forum posts, or other forms of user-generated content. To address this, the archive focuses on documenting Roblox's systems and platform history rather than individual users or personal identities. User-generated materials are included only when they provide important historical context for understanding discontinued platform features.

Another ethical consideration involves the preservation of digital history itself. Much of Roblox's earlier history has survived only through community efforts, archived webpages, screenshots, and unofficial documentation. As a result, the archive depends on sources that may be incomplete or reflect the perspectives of those who chose to preserve them. This means that the archive cannot present a complete or perfectly objective history of the platform. 

The project also recognizes that creating a digital archive involves interpretation. Decisions about which artifacts to include, how they are described, how metadata is assigned, and how materials are organized all influence how visitors understand Roblox's history. Rather than presenting a definitive record, the archive represents one curated interpretation based on the historical evidence that remains available.

Where possible, original sources are identified and credited so visitors can understand the provenance of each artifact and consult the original material when available.

---

# Limitations and Future Development

This archive represents only one interpretation of Roblox's history and is limited by both the availability of historical materials and the scope of the project.

One of the biggest limitations was the availability of sources. Many original Roblox webpages, interfaces, and systems have been removed or are no longer publicly accessible. As a result, the archive often relies on archived webpages, screenshots, community documentation, and secondary sources rather than original platform materials. This reflects one of the challenges of documenting digital history, where platforms continuously change and older versions are not always preserved.

As a curated project, different design choices could have expanded or altered the scope of the collection. Every decision about which artifacts to include, how they are described, and how they are categorized reflects my own interpretation of Roblox's history. While metadata helps connect artifacts across the collection, different organizational choices could produce different ways of understanding the platform.

If I were to continue developing this project, I would expand both the collection and its functionality. I would include additional artifacts covering later platform changes, strengthen relationships between metadata records, and create more connections between related systems throughout the archive. I would also like to incorporate additional archival materials, such as preserved videos, archived developer blogs, or interactive timelines, where appropriate.

---

# Reflection
One of the biggest methodological lessons from this project was realizing that building a digital archive is much more than collecting historical material. Throughout the project, I found myself constantly moving between research, metadata creation, website design, and testing. Each stage influenced the others. For example, while creating metadata I often realized that categories I had originally planned no longer reflected how the artifacts related to one another, which led me to rethink both the organization of the archive and the navigation of the website. 

Another important lesson was understanding how much interpretation is involved in archival work. Choosing which artifacts to include, deciding how to describe them, and assigning subject metadata were not neutral decisions. Every choice affected how visitors would discover the collection and understand Roblox's history. This made me think more critically about the role of the archivist as someone who actively shapes how history is presented rather than simply preserving it.  

The iterative nature of the project also became clear as the archive developed. Early versions of the site were organized more like a collection of independent pages. Through feedback and continued testing, I redesigned the homepage into a landing page that introduces the five major systems before directing users into the collection. I also simplified the browse page by reducing the number of subject labels and introducing a dropdown menu so navigation would be more consistent and easier to understand. These changes reinforced that user experience and archival organization are closely connected; changes to metadata often required changes to the interface, and vice versa.

Looking back, I also realized how differently I think about Roblox now compared to when I started the project. I initially approached it as a nostalgic game from my childhood, but through researching discontinued features and reading about platform studies, I began to see it as an evolving digital infrastructure composed of economic, social, technical, and governance systems. That shift ultimately shaped every aspect of the archive, from the categories I selected to the metadata structure and the overall design of the website.  This project has shown me that digital archives are never truly complete. Like the platforms they document, they remain works in progress that can continue to grow as new materials and perspectives emerge.
