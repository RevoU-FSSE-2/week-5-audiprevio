![NDJ header (1)](https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/13379789-87c6-4678-96e6-69c1e62e4a3f)

**next.Jobs:** where you learn your dream job's salary before you apply. We believe in transparency and the future of remote work.

# Development and Deployment flow of next.Jobs (Next Dot Jobs) - version 2.0

Hello, friend! 👋


In this Readme.MD  I will tell you how I developed and deployed my project website next.Jobs. You can refer to this overview below as the executive summary of the development and deployment process:

![NDJ Deployment Workflow](https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/f7c7c484-1f18-48d8-b56d-f0edf5dbeb12)


Note: for the currently Known Issues & Possible Bugs please refer to Section 2 - Known Issues.

# Section 1 Breakdown of Development and Deployment


## Step 1 UI/UX Review, Code Review & Product Management: 
Previously I have developed another version of next.Jobs at this repo: https://github.com/RevoU-FSSE-2/week-4-audiprevio (let's call it the version 1.0). You can refer to the readme.MD of that repo to read how I deploy the site to the custom domain: nextdotjobs.site. 

As for the development of this iteration, I started by reviewing codes, design, and the fundamental product feature of that website - basically gathering requirements for version 2.0. Of course, this process is also coupled with gathering requirement from the Module 1 Assignment document.


## Step 2 Product Management: 
After doing step 1, I gather all the design and code issues as `tickets` in my **Development Task Sheet** for this Sprint. You can access the sheet here:https://docs.google.com/spreadsheets/d/1zhW0W4uAFYqPuB8KTxJV0fKYyem0EGjmO235iWNHS3U/edit#gid=0
<img width="594" alt="image" src="https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/bd1aa577-8d65-4b50-9a57-1180aaeabb4f">


The sheet helps me: keep track of what I must do (ticket) and in what order I must do them (priority ranking) so that I don't waste my time because of scope creep.

## Step 3 UI/UX Design & Front-end Works:
In step 3, I basically start the dirty work - create the necessary design for front-end requirements and code for front-end requirements. How do I determine when I need design material? Well, basically, that's already covered in Step 2's Development Task. You can see the elements and raw design process here at NDJ's Garage: https://www.figma.com/file/vxFZDuUWxGxxgThpHseOhH/NDJ's-Garage?type=design&mode=design&t=sbO0bTKKl84dZWkW-1
<img width="960" alt="image" src="https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/05f8e3e9-0340-4154-aaac-dffd8fc426cf">


## Step 4 Create Staging and Do Testing at Staging:
In the spirit of `don't release something that's broken because that's bad for user experience`, I set up a staging website at **staging-ndj.netlify.app**, to make sure that i can catch all issues beyond using local live server. And this proves to be very helpful. I managed to catch bugs and design issues that occur in IOS devices.
<img width="959" alt="image" src="https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/40fdd8c7-cbde-4cc3-bd21-56b76ed25779">


## Step 5 UI/UX Design & Front-end Rework:
After catching bugs and issues in step 4, I redesign and recode the elements that are causing bugs and issues until they are resolved locally. Afterwards, I try to deploy to staging again to see how they perform. If issues - tickets - are resolved, then I move to the next ticket. If all tickets are solved, then we are ready to go live.


<img width="543" alt="image" src="https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/4ff298c8-bf75-40cd-9311-99d1b1821843">


## Step 6 Deployment to Live Website: nextdotjobs.site:
Once the staging testing is finished and all rework is done, I deploy the new codes and materials to next.Jobs' main website. But there was a catch. The nextdotjobs.site was connected to the previous repo, so I had to disconnect the previous repo in the netlify and connect this one instead.
<img width="959" alt="image" src="https://github.com/RevoU-FSSE-2/week-5-audiprevio/assets/126348614/a0a8d618-9814-453d-a461-6ac94f65f6ca">


And with that the **next.Jobs Landing Page 2.0** is successfully deployed!

# Section 2 Known Issues
There are technical issues that I note down during the development process that, while not destructive to the user experience, is worthy of nothing down. Chief among them are: 

(1) Navbar & menu items are not anchored to any pages (scope beyond this sprint), 

(2) form width still looks improper in a certain breakpoint, but remains fine on other. 

These issues and some others remain, because the lack of available time left in the sprint. I am planning to address them in the next sprint.

# Section 3 Credits
This project was made possible with the help of these amazing parties:

- **Dion Maulana Williawarma - Team Lead of Section 4 at RevoU**: Help shape the idea, explain codes, and put out fires for various issues in next.Jobs development process.
- **ChatGPT Plus**: providing copywwriting and aid in code reading as well as brainstorming concepts.
- **Vlada Karpovich @ Pexels**: Providing HQ photo and video.
- UI/UX Design: Audi Previo
- Code: Audi Previo + various sources

# Section 4 Closing Remarks
If you believe in the vision and mission of next.Jobs and have ideas on how to build a better next.Jobs for everyone, feel free to use this repo and drop a hello

Regardless, thanks for reading and happy hacking!
