# Threat Hunters - A Threat modelling RPG Board game
##### The goal is to take turns attacking and defending the system.

[Full Article on Confluence](https://medium.com/@harjitsandhu)

## Introducing AcmeCorp
> AcmeCorp is an online retailor. They provide direct to door delivery of Acme related memorabilia and Acmes to people of all ages. Their CEO Acme Ackleson is very concerned about Cyber Security and has committed to invested in the correct places. Luckily the brand-new security team, has the best threat hunters in the world! *That’s you!*

### How to play
**Game set up.** Split in to 4–6 teams of varying ability and experiences, of any size. I personally recommend 3–4 per team, to ensure everyone can be involved in the discussions. Ensure each team has a notepad, a nominated spokesperson and a nominated scribe.
Place the attack cards on the board, in a place where everyone can see and access the cards. Sometimes it helps to have a copy of the board on the screen for visibility to the teams.
The game consists of rounds, each broken down into different parts and taking approximately one hour to complete. 

**Each round.** At the beginning of a round, a member from each team takes an attack card from the deck, keeping it secret from the rest of the team for a short while. Simultaneously, all teams are then given three-five minutes to discuss how they will attack. Once the team is satisfied with the attack, the scribe needs to note it down - this will serve as evidence in the event that two teams have the attack. You will ultimately need to present it to the defending teams, including talking about the assets you are targeting, and how your attack will spread into the system. Have fun with this, you have one minute to present!

**Presenting the attack.** Each round involves a number of further rounds of attack. The first team presents the attack to the other teams. It is important to note here, that the attack has not yet happened, but is imminent. And the company has time to react. The whole point of being a threat hunter, is that you were able to find out using contacts on the dark web, intimate details of an imminent attack. The attack needs to reference high value assets that are either on the board, or whose existence is implied by the presence of an icon on the board. An example is an SMTP service, or the security at the entrance of the distribution centre.

**Defending.** Once the attack team is satisfied that everyone understands their attack, the defending teams have three–five minutes to work out which one thing they would change on the infrastructure on the board to mitigate this attack. We don’t have to be too prescriptive, as the architecture on the board is only a reference. If a team has a defence using a system that is either implied by the attacker, or implied by the board, this is also fine. As previously mentioned, some examples include an SMTP service, or the security at the entrance of the distribution centre.

**Success in a round.** Success in an attack round is defined as an undefended attack. That means if the attack team and defence team agree that the attack has not been defended by the mitigation.
Success in a defence round is when a defence successfully mitigates the attack. As in an attack round, this needs to be agreed by both the attack, and defence teams.
In the event of a deadlock, where teams can’t agree, the other defending teams are allowed to offer their opinion. If there are still no concessions, we resort to the very scientific method of rock, paper, scissors.
Don’t forget this is a co-op game! So play together! *We all win as a team!*

### Example Round
**Attack card:** Careless employee

We will email a virus to a developer who’s details we got from Instagram. And who’s email we guessed based on business email naming conventions. The virus will send us a copy of his git repository’s ssh key, and we will make a commit on his behalf injecting a vulnerability, that will allow me to make purchases for free. I will ship these to a drop mail box once a week until the exploit is patched.

**Defences**
 - **Defence 1:** Will vet all emails to all staff to ensure there are no malicious payloads
 - **Defence 2:** Will implement code reviews across the business to ensure change can’t go live
 - **Defence 3:** Black list the attacker’s customer account

*Which would you choose?*

For more information about how we learn threat modeling by playing this game, visit our blog post on [medium](https://medium.com/asos-techblog) which will be available mid january 2019.