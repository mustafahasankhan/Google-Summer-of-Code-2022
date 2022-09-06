<div align="center">
    <a href="https://summerofcode.withgoogle.com/programs/2022/projects/tN7gvf0E"><img src="https://assets-global.website-files.com/611a19ba853b746b32f6b402/62444b257d9d86ad941fba00_image%20(10).png" width="650" alt="google-summer-of-code-2022"></a>
    <br>
    <b> 
        <p>
          <a href="https://clickup.com/">ClickUp App</a> for <a href="https://rocket.chat/">Rocket.Chat</a>
        </p>
    </b>
</div>

<p align="center">
    <code> 
        <a href="#-project-abstract">Project Abstract</a>&nbsp;&nbsp;&nbsp;
        <a href="#-deliverables">Deliverables</a>&nbsp;&nbsp;&nbsp;
        <a href="#-demo">Demo</a>&nbsp;&nbsp;&nbsp;
        <a href="#-blog">Blog</a>&nbsp;&nbsp;&nbsp;
        <a href="#-mentors">Mentors</a>&nbsp;&nbsp;&nbsp;
        <a href="#-links">Links</a>
    </code>
</p>

ClickUp is #1 cloud based task/project management platform, I got the chance to make its app for Rocket.Chat (The world's largest open source communications platform)

From not having used much of Typescript before, to getting hands dirty with it and building an entire App completely in Typescript - that's how the next 3 months of Google Summer of Code will be for me.

I intend to maintain this repository as a work progress/final report summary of my GSoC work and a quick guide for all future GSoC aspirants.

## ⭐ Project Abstract

Teams collaborate on Rocket.Chat, using ClickUp is the go-to app for teams and channel members of any Rocket.Chat room for a their project/team management, even the core Rocket.Chat team uses ClickUp. This project aims to completely synchronize ClickUp workspaces and tasks with members on Rocket.Chat using features like task notifications and team management.

## 🚢 Deliverables

The following are the deliverables of this project:
- Allowing workspace admins to import their workspaces and link the ClickUp workspace members with their respective Rocket.Chat usernames.
- Allowing users to manage their workspaces, spaces, folders, lists and tasks. (as per ClickUp's hierarchy)
- Allowing users to create/get/change their tasks.
- Allowing users to subscribe to notifications for their tasks. (when any parameter on the task updates)
- Enabling users to create room of task assignees and updating tasks right in Rocket.Chat.

**All of the above deliverables were completed within the GSoC period. Yay! 🎉**

## 📺 Demo
- Importing workspaces from ClickUp:

https://user-images.githubusercontent.com/65130881/188577159-6e870764-abb0-48cb-91e5-71834dde1f58.mp4


- Managing workspaces, spaces, folders, lists and tasks:

https://user-images.githubusercontent.com/65130881/188577494-030f42e9-ef9d-4297-a33b-2d014a777bfb.mp4


- Task management:

https://user-images.githubusercontent.com/65130881/188577922-3642b389-1a8d-43bb-a869-6b5fb19a9102.mp4


- Task subscription and notifications:

https://user-images.githubusercontent.com/65130881/188579386-91fd0041-bc88-4262-9d8f-3e5e7fa5325a.mp4


- Creating task with assignees and optionally creating a room for them on Rocket.Chat:

https://user-images.githubusercontent.com/65130881/188579102-34749565-5b20-4bc7-8441-2a5eb7d73dcf.mp4

## 🚀 Contributions

### PRs

<div align="center">

| PR Link   | Description  | Status | 
| :-----------: | :------------------------------------:| :------:|
| [PR #3](https://github.com/RocketChat/Apps.ClickUp/pull/3) | App initialization. <br><br> <div align="left"> Highlights include:<ul><li>Initialized the RC app.</li><li>Implemented OAuth login flow.</li><div> | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #4](https://github.com/RocketChat/Apps.ClickUp/pull/4) | Added slash command for authentication. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #5](https://github.com/RocketChat/Apps.ClickUp/pull/5) | Setup Modals. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #6](https://github.com/RocketChat/Apps.ClickUp/pull/6) | Implemented create task feature. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #7](https://github.com/RocketChat/Apps.ClickUp/pull/7) | Implemented Get, Update & Delete tasks feature. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40>
| [PR #8](https://github.com/RocketChat/Apps.ClickUp/pull/8) | Added Room assignee feature. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #10](https://github.com/RocketChat/Apps.ClickUp/pull/10) | Implemented Subscriptions and Progressive Workflow. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #11](https://github.com/RocketChat/Apps.ClickUp/pull/11) | Refactored code and finalized app. | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
</div>

## 😎 Blog
    
I have not writen blogs regarding each stage of GSoC, but you'll find these two interesting and insightful.
    
<div align="center">
    
| **GSoC Phase** | Blog |
|:--------------------|:-------------------|
| Selection | [Journey to Google Summer of Code 2022](https://mustafahasankhan.com/blog/gsoc-2022) |
| GSoC Period | [What all I did in Google Summer of Code 2022](https://mustafahasankhan.com/blog/work-at-gsoc-2022) |
    
</div>

## 🎓 Mentors

A big big thank you to my mentors for their guidance before and throughout GSoC. 🙏 
I learned beyond GSoC from them and am forever grateful to be mentored by them.

**“One of the greatest values of mentors is the ability to see ahead what others cannot see and to help them navigate a course to their destination.”** *— John C. Maxwell*

*At the end of my GSoC journey, I 100% agree with the above quote.* 

- **Douglas Gubert** - [Github](https://github.com/d-gubert) [LinkedIn](https://www.linkedin.com/in/douglas-gubert-66798127)
- **Allan Rebeiro** - [GitHub](https://github.com/AllanPazRibeiro) [LinkedIn](https://www.linkedin.com/in/allan-ribeiro-2977998b)


## 🔗 Links
    
- Check the app on Rocket.Chat marketplace [here](#).
- Check my presentation on Rocket.Chat demo day [here](#).


## ❤️ Support
Learned something new today? Reciprocate the love. ⭐ this repo for good. (Do good and good will come to you)
    
## 💬 Connect With Me    
Want to discuss about GSoC / Rocket.Chat / Open-source / Blockchain / Crypto? Let's connect!
<div align="center">

| **Student** | Mustafa Hasan Khan |
|:--------------------|:-------------------|
| **Organization** | [Rocket.Chat](https://rocket.chat/) |
| **Project** | [ClickUp App for Rocket.Chat](https://summerofcode.withgoogle.com/programs/2022/projects/tN7gvf0E) |
| **GitHub** | [@mustafahasankhan](https://github.com/mustafahasankhan) |
| **LinkedIn** | [mustafahasankhan](https://www.linkedin.com/in/mustafahasankhan) |
| **Twitter** | [mustafahasankhan](https://www.twitter.com/mustafahkhan) |
| **Medium** | [mustafahasankhan](https://mustafahasankhan.medium.com/) |
| **Website** | [mustafahasankhan.com](https://mustafahasankhan.com) |
| **Email** | <a href="mailto:mustafahasankhan@protonmail.com">mustafahasankhan@protonmail.com</a> |
| **Rocket.Chat** | [mustafa.hasan.khan](https://open.rocket.chat/direct/mustafa.hasan.khan) |
       
</div>
