# Slack - How To

Slack on our OSU enterprise Workspaces is a FERPA-approved, online chat and videoconferencing tool that is ideal for our synchronous student interaction needs. Think of it as a much-more-interactive chat client.  A Slack Workspace is essentially a membership subset specific to some THING (like a course section, for instance).

Slack is a fantastic tool for you to communicate with your students and encourage their learning in what feels like a much more in-person way. We've decided to incorporate it as a standard tool in our courses, and encourage you to employ it as much as possible.  This can take the form of office hours for yourself and your TAs, and tele-/video-conferencing at-a-click.  It can also be a place for you to talk about course-related and program-related materials in a more personal and approachable setting.  We will also use it for intra-departmental communication.

There are multiple methods to connect to Slack.  We recommend using the desktop application and mobile app. You can find links to download these at our [Departmental Slack Info Site](https://it.engineering.oregonstate.edu/slack). Alternately, entering the slack Workspace URL in your web browser will allow you to log on without downloading an application, but notifications don't work as well using this method.

NOTE: You can also view a [Demo](https://slackdemo.com/) which Slack has put out which shows many of its capabilities in use, and our [Departmental Slack Info Site](https://it.engineering.oregonstate.edu/slack) has some useful information as well.

## Connecting to our Departmental Workspace

After you've downloaded Slack, when you boot it up you should arrive at a login similar to the following.

![Slack Homepage](images/SlackWorkspaceConnection.png "Slack Homepage")

Please connect to the Workspace [**_oregonstate.enterprise.slack.com_**](oregonstate.enterprise.slack.com) - this is the central connection point for all OSU-oriented slack workspaces. You should then select the "Sign in with ONID" and be able to connect. Now you're in!

Here's how we use the Departmental Slack:

- pb-instructors (request an invite if you're not already in!)  
  Ad-hoc discussions for all of our online instructors. Clarification of policies, requests for assistance/information, etc)
- random  
  Random chat among department personnel (you!)
- general  
  Department-wide notes

## Starting a new Class Workspace

Now that you're set up and ready to go, it's time to create a Workspace for your students to connect to!  Fortunately our ENGR IT department has setup a fairly simple method to do this for us:

1. Sign on to [TEACH](https://teach.engr.oregonstate.edu/) using your department login.  The login info is the same as your ONID login, but this requires an ENGR account. If you don't have one yet, please [contact support](https://it.engineering.oregonstate.edu/webform/email-support-engineering-it) to have one set up for you.
2. Select Class Administration from the TEACH navigation bar  
![Teach Navigation Bar](images/TeachClassAdministration.png "Teach Navigation Bar")
3. Select "Class Slack Workspace" and "Add a new class slack workspace".
4. Select your new course from the Course List menu, add your TAs' ONID usernames to the "Special list members (TA's, etc):", separated by commas, and hit SUBMIT!  
*Hint: For help locating your TA usernames, you can use the search window at the bottom of this same page.*

That's it! Your students will be automatically added and you'll be the Workspace Administrator, which means you're responsible for managing all public channels.  Your students and TAs can create their own private channels for their own conversations, and everyone can Direct Message each other.

## Configuring your Class Workspace

Now that you have a Slack Workspace for your class, it's time to get it properly setup for use.  There are a few required setup procedures which follow here. To get started on setting these up, go to your class Workspace and get into the Workspace settings by clicking the Workspace dropdown, then selecting Workspace settings (under the "Administration" heading)

![Slack Workspace Settings](images/SlackWorkplaceSettings.png "Slack Workspace Settings")

- Change Workspace Info
  - In the Workspace Settings, under the "Settings" tab find "Workspace Name, Description, and URL."
  - Alter the Name and Description to be more intuitive for the students, but don't touch the URL  
  ![Slack Change Workspace Info](images/SlackChangeWorkspaceInfo.png "Slack Change Workspace Info")
- Update Workspace Icon
  - In the Workspace Settings, under the "Settings" tab find "Workspace Icon"
  - Download your class' Slack Workspace Icon from [HERE](https://drive.google.com/drive/folders/1RKscY825h54A9blY-hL6_dQesOgg6TG9) and upload it as the Workspace Icon. This will make it easier to navigate to the correct class' workspace for students and yourself.
- Set up landing channel
  - It is important for the landing channel to be a neutral environment for our students.  Slack gives us two channels by default (#general and #random) but we can only easily restrict contribution permissions for #general so we will use it as an entry point.  First we'll have to rename it to #announcements.
  - Back in your Slack app in your class Workspace, enter the #general channel and select the Settings wheel for it...  
  ![Slack Channel Settings Gear](images/SlackChannelSettingsWheel.png "Slack Channel Settings Gear")
  - Choose "Additional Options" then "Rename this Channel" and rename the channel to "announcements"
  - Back in your Workspace Settings (not the Slack App) under the "Permissions" tab, expand "Messaging", and then set "People who can post to #announcements" to "Workspace Owners and Admins only".  This will lock down the channel so only you and your TAs can post here. Mission Accomplished!
- Set up new **__#general__** channel  
  Every student who joins your workspace will now land in *#announcements* but be unable to post there.  This makes it a good place to post announcements, but we've now robbed ourselves of a *#general* channel. We'll have to make a new one and provide a link for students to "opt in" to that channel, and then we can use it for office hours and other synchronous communications.
  - To create a new channel, within the Slack application's navigation bar, next to the "Channels" heading there should be a ⊕. Click this button to create a new #general channel and define it's purpose.
  - A "channel purpose" is displayed to all who join that channel - you can set this one for however you intend to use it, but we'll need the purpose for the #announcements channel for something special.
- Provide students a link to your new **__#general__** channel.
  - Since Slack doesn't allow students the anonymity which Piazza does, we need to let our students 'opt in' to our class-oriented Slack channel.  We now have all the channels we need, but the students don't have any way to see the #general channel. Let's give them a link.
  - Back in your #announcements channel, go back to the channel settings (See "Set up landing channel" image for help)
  - Select "Additional Options" and "Set the channel purpose"
  - Set the purpose to something like the following. The purpose will be visible until the posts of the channel push it off the screen.  
  "This channel is for class-wide communication and announcements. All members are in this channel by default, but only Instructors/TAs may post. For class discussion and office hours, please use the #general channel."
  - At the top of the channel there is a spot to set the channel topic. Set the topic to "Join #general for office hours and class discussion" or something along those lines.
  - You may also elect to keep a link to *#general* in the body of the most recent message in the channel.
  - The point here is to always provide a visible link to *#general* for students 'just now' joining your workspace or viewing it for the first time.
  
## Recommended Channels

Some additional channels you may elect to use:

- *#administration* (private)  
Used to communicate with your TAs.
- *#ta_discussion* (private to your TAs)  
Used among your TAs to discuss their duties.  We recommend you are not a member of this channel.
- *#random* (a default channel)  
Off-topic discussions within your course.

## Encouraging Use of Slack

One hurdle you may face is getting your students on-board and engaged. One significant way to boost usage is to hold all office hours (yours and your TAs') on Slack, but of course you need to give the students the information they need to get it up and running! I've taken the liberty of creating [\*\*\*this page\*\*\*](TBD which you can paste into your courses (don't forget to snag the image as well!). I recommend putting this in the first Module the students see, or in the Tools syllabus page subsection.

\*\*\* Intro Activity Placeholder\*\*\*

## Other Slack Information

Your Workspace won't be the only one your students have.  Here is some information about how the student Slack experience is configured.
\*\*\* Info Placeholder\*\*\*
