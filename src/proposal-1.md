# Proposal v1

![Proposal](img/1-hierarchy.svg)
[This picture can be zoomed in !](./img/1-hierarchy.svg)

## Explaining 


### The Teams system

This document proposes a hierarchy that is revolves around teams. All staff are separated into teams, and each team has specific tasks in mind. They are required to collaborate together but they work as independent entities.
A staff member is usually within exactly one team but this is open to discussion.

### Privilege surface

Preventing staff from being into all groups at once might seem counterintuitive. But it does reduce the *privilege surface* of a specific staff member. If applied correctly, this removes a staff member from being able to hide malicious actions such as hiding complaints, banning users labelled as opponents, and so on.    
This creates an environment known as _zero thrust_, allowing each staff member to use their permissions and nothing more.  

### Exclusive teams

Any user being part of more than one group might get sufficient privileges to act maliciously or beyond their permission. For that, this document proposes a system called _exclusive teams_. Members of an exclusive team are forbidden from joining any other team, even some time after their offboarding.

Suppose the HR team is an exclusive group, a staff member _A_ can be assigned to the HR team, but can no longer join any other team.

### Responsibility and transparency as a core value

The hierarchy system this document proposes tries to eliminate any action that can be censored or hidden. All staff members receive a set of permissions they can use, knowing this action will be logged and registered to their name.
Any data related to staff would be kept private, but available to their team's managers.

No one should be able to remove logs. The goal of this is to increase the responsibility of each action. **It is not to encourage punishment for mistakes**. We're human.


## Meet the teams

### Moderation Team 

The moderation team represents the in-game moderators. They : 

* Answer questions from players
* Host events
* Make sure the rules are followed

The moderation team is handled by one manager, that is responsible for the team in its entierty.

### Discord Team

The Discord team is a group of users responsible for the Discord chat. They :

* Make sure the Discord rules are followed
* Maintain the Discord server in its desired state

The Discord Team is an exclusive team.  
The Discord Team is handled by one manager, that is responsible for the team in its entierty.

### Development Team

The Development Team is responsible for the content game server in all its aspects. They :

* Make sure the server is up-to-date and in its desired state
* Work on PRs, issues and suggestions

The Development Team has contributors and maintainers.

#### Contributors

A contributor is anyone that is or has contributed to this server's game content at least once.  
Altough contributions are highly appreciated, they are not considered staff unless part of another team.

#### Maintainers 

A maintainer is simply a status that indicates regular contribution and a seniority in this regard.  
It gives privileges to the Git repository such as approving PRs.


The development team is managed by one manager, that is responsible for all maintainers.

### HR Team

The HR team is a group of users responsible for the staffing of the server. They handle :

* Hiring of all staff (except all managers)
* Firing of all staff (except all managers)
* Handle player disputes
* Provide inner guidelines for procedures such as banning, player requests, and so on.

This is an exclusive team.

The HR team is managed by one manager, that is responsible for all HR members.


### Central Committee

The Central Committee is a board made out of all teams. The Central Committee oversees the server. It does not make any decision made by teams presented previously. It handles :

* The hiring and firing of all management (including the Project Manager);
* The GitHub Organization containing the codebase (administrative actions);
* The ownership of the Discord Server;
* The ownership of the Game Server;
* Counseling and arbitration of all team disputes.

The central committee is made out of all managers.

#### A note on transparency

Ideally, the central committee would be made out of anyone willing to join. However, this adds a level of complexity that I'm not quite ready to get into (quorum, the fact that the Central Committee would be made of mostly passers-by, and so on).

To enforce transparency, all central committee meetings and decisions should be public and appealable, with staff attending to meetings allowed to have a voice within decisions.

#### A note on the central committee

I don't like the idea of this central committee too much. However, some decisions have to be escalated and taken by people representing a whole. I fear that, for instance, the development/HR/Moderation team might not have the complete perspective of the server in mind.
I don't like the idea of managers only running this show. I hate it, actually. Managers rarely have local knowledge of their departmentand therefore can make, as any human being, mistakes.
I'd like to make the central vote a bit like a town hall.

## Considerations

### Scaling down

The teams system should, on paper, work. If permissions are indeed hermetic, we should be able to prevent any malicious behaviour from staff.

However, it does require some significant staffing. The current proposal counts :

* 4 managers
* 1 Project manager

That is already 5 people. Not counting staff members working in those departments. It's a lot. Maybe we can reduce the headcount further, until we get more staff.

#### 1. Allowing the moderation team to be in the Discord team as well

That leaves admins with both banning permissions. To make sure all actions are logged forever, bots can be used. We could make a channel with only HR and the Central Committee, with the bot logging any person being banned IG or at least on Discord.
Then either HR or the Central Committee would occasionally audit bans.

#### 2. Development team

I suppose AI could help. I believe we can find people that have already devved things. But it could be the most complex task at hand.

#### 3. Down with the managers

Only the Project Manager would have a title including managers. All other staff members would all represent their team. Disputes would be handled by the Project Manager.

#### 4. Tentative - HR

HR is a really delicate department, as it should be a bit separated from the others for various reasons. I don't think it's a good idea to mix any other team with HR.

#### 5. A brief calculator stop

One project Manager, one HR representative. It's a bit like what @hiu said. When the time comes, we can put back the teams with their separation. In the meantime, we can work like this and learn.

### Voting

I believe all decisions should be put to a vote. No matter what. Decisions should be posted immediately to staff after they've been voted.

#### Quorum

The minimum of voting members is 3, as it's impossible to get a reliable vote result with less than that.