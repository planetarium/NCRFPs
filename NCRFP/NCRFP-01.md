---
NCRFP: 01
Title: Developing Nine Chronicles Browser Version
Status: Draft
Type: Core
Author: Yujeong Nam <yujeong@planetariumhq.com>, Boram Bae <boram@planetariumhq.com>, Sangmi Sun <caesty@planetariumhq.com>, Swen Mun <swen@planetariumhq.com>, Jaeho Lee <jaeho@planentariumhq.com>, et al.
Created: 2023-06-16
---

# Proposal
- Develop and provide a browser version of Nine Chronicles for players to enjoy the game directly from a web browser.

# Motivation
- Bridging the gap between PC and mobile devices. Provide support for players in network-restricted environments to be able to enjoy Nine Chronicles.
- The relatively high difficulty of modding the Unity client. There is a need for a game client that is easier to modify.
- A lightweight client that allows for easy gameplay or quick consumption of action points or tickets when desired.

# Impact
- Secure a platform for lightweight gameplay without installation and increase opportunities for client modding.
- Although the Nine Chronicles team made the design proposal, this proposal will open the gateway for community development teams to develop directly instead of the Nine Chronicles team, providing opportunities for community participation and modding.

# Specification

## Proposed Design
https://www.figma.com/file/0whMmBxZptImEbSFC54Qxs/Nine-Chronicles_Browser-client_Draft?type=design&node-id=1-3&t=iuZCp3ilamGR24aG-0

- Vertical-oriented browser design
- Designed based on Android Large (360x800) resolution
- Adjusts to a fixed aspect ratio based on the width of the browser
- Lightweight client focused on minimal transitions and resources

## Resources
- Most resources can be downloaded from Figma.
- Other resources, such as item icons, can be downloaded from the existing Nine Chronicles public repository: https://github.com/planetarium/NineChronicles/tree/development/nekoyume/Assets/Resources/UI/Icons/Item

# Compliance Requirements

## Licensing
- [Must] The final codes must abide AGPL requirements & code must be open-source.

## Web Client
- [Must] Utilize standard web technologies to ensure browser compatibility.
  - The web client must behave consistently across Google Chrome, Safari, and Firefox on iOS, Android, Windows, and macOS.
- [Must] Adhere to the prototype of the proposed design.
- [Optional] Achieve a Lighthouse performance score of 80 or higher.

## Game Action Functionality
- [Must] Operate solely using the RPC (GraphQL) of the mainnet without the need for additional client implementation.
- [Must] Core functionalities (adventure, item crafting, enhancement, grinding, item trading, arena) should be operational.
- [Optional] Implement additional in-game features (world bosses, various notifications).

# What kind of development team are we looking for?
- It would be preferable for the team to have experience playing Nine Chronicles.
- Proficiency in web frontend development is required.

# How do I apply?
- Please fill out the survey link provided below.
  - Team introduction, team member introduction, bidding price, and development schedule (including the completion date).
- [Nine Chronicles Software Grant Program](https://docs.google.com/forms/d/e/1FAIpQLSf-6EXf4EkLRPHc5a2UutAHhS_pN4IpYAZyUnJeP7Xe4_TzvQ/viewform)
