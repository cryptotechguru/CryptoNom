# Cryptonomicon

1. The name of the [game](./Nomicon/) is Cryptonomicon
1. The goal of the game is to Decentralize the Singularity
1. The players of the game are the members of the [players team](https://github.com/orgs/cryptotechguru/teams/players/members)
1. All rules should be logically self-consistent 
1. The source for the rules are kept in the [website repository](https://github.com/cryptotechguru/Cryptonomicon)
1. The rules are published on the [website](https://cryptotechguru.github.io/Cryptonomicon/)

## Jurisdiction

1. Only [Ulex 1.1](https://github.com/proftomwbell/Ulex/tree/master/versions/1.1) governs any claim or question arising under or related to this agreement, including the proper forum for resolving disputes, all rules applied therein, and the form and effect of any judgement.

## Conventions

1. The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in these rules are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

## Process

1. All players must unanimously agree to all rule changes #virtual
1. All changes to the game MUST be submitted through a pull request (PR)
1. All changes to the game SHOULD be vetted by submitting a CIP or delta [issue](https://github.com/cryptotechguru/Cryptonomicon/issues).
    1. A CIP is a Cryptonomicon Improvement Proposal (analogous to a BIP in Bitcoin Core). 
    1. A delta is an inconsistency between a specification and an observation (analogous to a bug in software). 
    1. If any player breaks the rules or witnesses another player breaking the rules, they SHOULD file a delta report.
    1. Deltas SHOULD be reviewed by the Operators to determine whether the rule should be changed or the player should be sanctioned.

### Multi-votes
1. If a proposal offers a choice between two or more options an Operator should call a multi-vote.
1. Each option is voted on with a +1 (acceptable), a -1 (not acceptable) or 0 (neutral).
1. Abstentions are counted as 0 (neutral).
1. Each option is assigned a score equal to the sum of votes.
1. If at least one option gets a positive score the multi-vote succeeds in choosing the one with the highest score, otherwise the proposal is defeated.
1. If there is a tie for high score among the options, the sponsor of the proposal may choose a winner among them, otherwise the proposal is defeated.
1. A multi-vote SHOULD have a single sponsor responsible for collecting and publishing options.
1. A multi-vote SHOULD have a specified deadline.
1. A multi-vote MAY be conducted on the game wiki.
1. An option MAY be added to the multi-vote by the sponsor during the vote but options MAY NOT be removed once the vote starts.
1. Voters MAY update their votes at any time before the vote ends but MUST NOT update anyone else's votes.
1. A multi-vote MAY be resolved early only if all eligible voters have voted on all options.

## [Projects](Projects/)

1. A project is a sub-game that inherits from the base rule set of Cryptonomicon
1. A project MUST have a unique name
1. A project MAY be located in a sub-folder of Cryptonomicon named after the project
1. A project MAY override a rule in the base game unless the rule is tagged as #final
1. A project MAY have its own set of players 
1. A project SHOULD have a charter document that defines that goals of the project
1. A project SHOULD be a collaborative game played between two teams, typically the Gatekeepers and Keymasters
    1. The Gatekeepers (representing the project customers) SHOULD be responsible for acceptance criteria for project deliverables
    1. The Keymasters (representing the project vendors) SHOULD be responsible for developing the project deliverables 

## Roles

1. A role is a function performed by a player (or their delegate) that comes with special rights and responsibilities.
1. Only players may fill roles.
1. For a role nomination proposal to pass, the player nominated MUST give their explicit approval. (No voluntelling!)

### Operator

1. The Operator role has the responsibility to carry out the provisions of the rules that are not yet automated.
1. The Operators of the game are specified in the [CODEOWNERS](https://github.com/cryptotechguru/Cryptonomicon/CODEOWNERS) file.
