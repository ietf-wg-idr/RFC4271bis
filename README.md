# Welcome!

This repo contains the IDR working group's effort to produce a Full Standard document for BGP, replacing RFC4271. [John Scudder](mailto:jgs@hpe.com) is the current editor for the project.

## Goals, Background, WG Discussion

- [Presentation at IETF-123](https://datatracker.ietf.org/meeting/123/materials/slides-123-idr-making-bgp-an-internet-standard-rfc4271bis-00)
- [Presentation at IETF-124](https://datatracker.ietf.org/meeting/124/materials/slides-124-idr-rfc4271bis-update-00)
- [Presentation at IETF-126](https://datatracker.ietf.org/meeting/126/materials/slides-126-idr-revised-slides-for-rfc4271bis-01-00)

The slides and other WG materials provide full context, but at a high level our goal is to meet the requirements from BCP 9 for Full Standard (see the IETF-123 slides), with as little scope creep as we can manage. That having been said, some creep has been hard to avoid. Major factors include:

- It's not possible to get approval for a Full Standard that doesn't include IPv6 support. This means either advancing (at minimum) RFCs 2545, 4760, and 5492 as independent documents too, or merging them into the base spec. 
- It's at least highly desirable, if not mandatory, to update the finite state machine to incorporate the various state machine updates that have been done in other RFCs, such as 4724.

## How to Help

We are currently managing our work through the Issues. Ways to contribute:

### Suggest

- Is something missing? Open an issue!
  
### Contribute 

- Claim an issue to work on. Use the "assign yourself" link to claim it. Please also add a comment indicating you're claiming it. If possible, include a guesstimate for your timeline.
- Please use one pull request per issue.

### Review

- Review the issues and comment as needed. Some of the issues need more WG input to move forward.
- If you aren't able to contribute a PR, but are willing to be a reviewer, add a comment volunteering as a reviewer. 

### Advise

- If you have suggestions about how I can manage our GitHub based workflow better, contact me at [jgs@hpe.com](mailto:jgs@hpe.com).
