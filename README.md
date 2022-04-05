# Team-Plan
### Team plan for 301 Final project 2022

**Team:** Benjamin Carter, Ella Svete, Cole Gibbs, Nathan Waters, Michelle Salazar

**Team Name:** Weapons of Mass Instruction
**PLANNING** https://docs.google.com/document/d/1gWDWaOkg9wdeZN5Gf8zxi0XcddPqQAOciX2DQOaxkEQ/edit?usp=sharing

**Presentation Deck:**  https://docs.google.com/presentation/d/1qe0qWSu7goDzDZBs9QYW1cnLVjtWwQPzViyAv2L_DGo/edit?usp=sharing

**GitHUb:** https://github.com/Weapons-of-Mass-Instruction

**Trello:** https://trello.com/invite/b/p0SqkahH/f28164591858ac162ede0453bc6ee707/301-project-board

**WWRC:** https://lucid.app/lucidchart/b930d44d-175c-4bc7-8f47-36d714277456/edit?beaconFlowId=9FD67CB08D40C961&invitationId=inv_b8be2d60-3126-4600-8721-2d8dcd99c737&page=0_0#

**WireFrame:** https://lucid.app/lucidchart/0ca30a4d-ce06-439b-8b3e-29afab262edc/edit?beaconFlowId=769BE4944FE87C4E&invitationId=inv_f2f7fbbd-3a97-4963-bc5a-3a181e817f0d&page=0_0#

## Deployed Links:

Front End Deployed (main): https://snazzy-daifuku-c6ced4.netlify.app/

Back End Deployed (main): https://bands-like-this-be.herokuapp.com/


## Cooperation Plan

Every person on your team is an asset. This is your chance to discover the hidden strengths and areas for growth for each team member.
Describe at least:

• What are the key strengths of each person on the team?

	
| Ben | Backend, comfortable with all, no styling, bootstrap |
| Cole | Frontend, comfortable with all, bootstrap |
| Ella | Frontend, good with styling |
| Nathan | Anywhere, not styling |
| Michelle | Backend, comfortable with styling |

	
• How can you best utilize these strengths in the execution of your project?

Consult with team experts when we get stuck. assign people in areas they're comfortable in. 

• In which professional competencies do you each want to develop greater strength?

verbal communication, not suffer in silence, confidence in what youre doing, organization. growth mindset

• Knowing that every person in your team needs to understand all aspects of the project, how do you plan to approach the day-to-day work?

Standups daily-MVP for sections of day. 3 daily, morning, after lunch, EOD

NOTE: Undoing, Redoing, Replacing, or otherwise steamrolling the project as an individual is considered to be unacceptable. Account for the inevitable divergence of ideas, execution tasks, and assignments of duties here.

## Conflict Plan

Your team should agree on a process for handing disagreements, should they arise. It is better to have a plan in place ahead of time so you can all refer back to it when necessary.

Describe at least:

• What will be your group’s process to resolve conflict, when it arises?
The code not the person. Addressing with whole team and not singling anyone out.

• What will your team do if one person is taking over the project and not letting the other members contribute?
Address with whole team of how we envision working together and ask for tasks to be more evenly divided.

• How will you approach each other and the challenges of the project knowing that it is impossible for all members to be at the exact same place in understanding and skill level?
After you finish any block of code share with team where you are at during standups and any blocks that you may have.

• How will you raise concerns to members who are not adequately contributing?
Attempt to have an intervention between the team, if this does not work, ask for an instructor's/TA advice on next steps.

• How and when will you escalate the conflict if your resolution attempts are unsuccessful?
See above. **Quickly our timeline for this project is short.**

## Communication Plan

Before beginning to tackle the project, determine how your group will communicate with each other. This is not an individual effort. Make sure everyone feels comfortable with the identified methods of speaking up.

Describe at least:

• What hours will you be available to communicate?

Hours 9-6
Ben	Anytime
Cole	Frontend, comfortable with all, bootstrap
Ella	any hours except weekend
Nathan	Anywhere, not styling
Michelle	Anytime

• What platforms will you use to communicate (ie. Slack, phone …)?

Slack- expectation is that we are not expecting an immediate answer if its outside of our meet hours.

• How often will you take breaks?

Hour or Hour an half. Reality as needed.
Lunch will be taken as a team.

• What is your plan if you start to fall behind?

Regroup and create realistic MVP's . Seek advice from instructor on what can be accomplished at that time.

• How will you communicate after hours and on the weekend?

Slack but not expecting immediate response 

• What is your strategy for ensuring everyone’s voice is heard?

Standups, check in ask everyone to participate and share their thoughts on the status of the project and overall team dynamic.

• How will you ensure that you are creating a safe environment where everyone feels comfortable speaking up?

Dont dismiss any ideas, or concerns. 

## Work Plan
Explain your work plan to track whether everyone is contributing equally to all parts of the project, and that each person is working on “meaty” problems. This should prevent “lone wolf” efforts and “siloed” efforts.

NOTE: While researching and experimentation is always encouraged, writing and/or committing code to the project on your own during non-working hours or over the weekend is never acceptable. This puts the entire project at risk. Be explicit in calling out your work hours and the distribution of tasks.

Describe at least:

• How you will identify tasks, assign tasks, know when they are complete, and manage work in general?

We will write out whole project in pseudo code.

• What project management tool will be used?

Trello

## Git Process

Plan out what your team’s Git workflow looks like for coding tasks.

Describe at least:

• What components of your project will live on GitHub?

All of it except DB

• How will you share the repository with your teammates?

create an org

• What is your Git flow?

Create a sub main branch, require at least 2 approvers. New features should have new branch. Commit often. Merge during meetups.

• Will you be using a PR review workflow? If so, consider:

• How many people must review a PR? 2 approvers

• Who merges PRs? whole team

• How often will you merge? 3 times a day, during standups.

• How will you communicate that it’s time to merge? during standups.

**WWRC**
![Weapons of Mass Instruction WWRC](https://user-images.githubusercontent.com/61945783/161603996-56c3b715-731d-492d-847c-3957ab4a5a65.jpeg)

**WireFrame**
![Weapons of Mass Instruction Wireframe-Homepage](https://user-images.githubusercontent.com/61945783/161626390-c1d006b2-41b2-46ac-91cb-e661a0318e09.jpeg)

![Weapons of Mass Instruction Wireframe-AboutUs js](https://user-images.githubusercontent.com/61945783/161626378-18c695a6-6377-4c42-89a4-0b6693ccf0ee.jpeg)

![Weapons of Mass Instruction Wireframe-MusicPage](https://user-images.githubusercontent.com/61945783/161632655-9817772f-af60-4634-bcd1-b20b60c55194.jpeg)

## Schema

User{
	Search{
		band Name: "", (str)
		song Name: "",(str)*Stretch Goals
		genre: "", (str)*Stretch Goals
	}
	Results{
		recommendedArtists: "",  (str) * 10 objects
		favorite:"", (boolean)
		playlist:"", (str)*Stretch Goals
	}
	Favorites{  
		playlist Name: "", (str)
		individual bands:"", (str)
		favorite:"", (boolean)
	}
}

![image](https://user-images.githubusercontent.com/61945783/161636574-55f5b958-ae4f-4329-8262-39377d81398c.png)

![Front end React Map](https://user-images.githubusercontent.com/61945783/161646059-86fa5d71-c91a-45c2-881f-e0912998aa55.jpeg)

