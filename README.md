# Yammer User Analysis

Data analytics on the users and events of Yammer.
**Yammer** is a social network for communicating with coworkers. It’s owned by Microsoft. 

Goal of our Data analytics is to investigate **why there is a drop in user engagement**.

**Dataset:** it is provided by Yammer's Data analytics team. The data is gatheres in two diffrent parts **tutorial.yammer_users** and **tutorial .yammer_events**. The detail will be explained in the next part.

For this project we used Mode. **Mode** gives us the oppertunity to access the data base and explore the data. It is also possible for a workspace members to export and share a report of their work.

The first loop of the project has been done in 5 weeks from the middle of April. The folowing steps would be a detail report on our work:

## 1. Setting up a dashboard in Mode
First of all, we made a WORKSPACE on mode and invited the members:

![Workspace](https://github.com/AsiMrz/yammer-events-users/blob/main/Workplace-Creation.jpg)


## 2. Getting an Overview of the datasets
Because the Dataset was available on the Mode, we could access the Data easily by this code:
### A. Yammer Events

![Events Table](https://github.com/AsiMrz/yammer-events-users/blob/main/Yammer_first_10_events%20table.png)

As it is shown the table contains the information about the **User_id**, the time that event **occured_at**, the user's **loction**, **device**, and the two **event-type** : sign-up and engagment with the platform which is detailed in **event_name**.

### B. Yammer Users

![Events Table](https://github.com/AsiMrz/yammer-events-users/blob/main/Yammer_first_10_users_table%20(2).png)

The table contains the information about the **User_id**, the first time the ID is **created_at** the user's **state**, and if s/he is active, when s/he **activated_at**and also information about the **company_id**and his/her **language**.
