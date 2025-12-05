# Galactic Bounty Hunter Registry API
**v1.0 – Void-Warrant Certified** ⚡

> “The only thing more dangerous than the hunters in this registry… is trying to read it without proper clearance.”  
> — Imperial Senate Decree 66-Δ

This is the **official** REST API for the Intergalactic Bounty Hunter Registry (IBHR).  
All licensed Hunters are registered here. The purpose of this register is to make sure each and every one of these professionals are operating legally.

## Concept, Ideas, Reasoning

The purpose of this API design is strictly portfolio. This is to showcase my ability to design API specifications with the use of yaml in a docs-as-code approach.
The "Intergalactic" theme is meant to draw your attention, as I like to think I'm a creative and capable Technical Writer.

I decided to use the components object so that schemas, properties etc. are reusable.

## Base URLs

| Environment   | URL                                                  | Notes                                    |
|---------------|------------------------------------------------------|------------------------------------------|
| Production    |   https://virtserver.swaggerhub.com/BOUNTY-HUNTER/IntergalacticBountyHunterAPI/1.0.0   | Core Worlds – Coruscant primary node     |


## Authentication

You need a valid **Imperial-issued API token** with at least `bounty:read` scope.  
Unauthorized requests are met with immediate orbital bombardment.

