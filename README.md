eLabFTW is an electronic solution to the classic lab notebook and offers many additional practical features (schedular, collaborative working, lab equipment management, etc.). It is an open source solution that is already in use at many research institutions worldwide.

The page is intended to provide support for the use of eLabFTW. You will find manuals for users and admins of teams in eLabFTW. You will also find a list of frequently asked questions. If you have a question or request about eLabFTW (e.g. create a team or add a user) please contact the SysAdmin.

## Table of contents
1. [Manuals](#manuals)
2. [API Tutorial](#api_tutorial)
3. [Overview of permissions management in eLabFTW](#overview_permissions)
4. [Tip: Leaving a team/group or the tool](#leaving_user)
5. [Backup options for users](#backup_user)
6. [Contact](#contact)

## Manuals <a name="manuals"></a>

1. [User Guide](https://github.com/alexgu2008/elabftw_support_unigraz/raw/main/eLabFTW_BioHealth_Guide_User_en.pdf)
2. [Team Admin Guide](https://github.com/alexgu2008/elabftw_support_unigraz/raw/main/eLabFTW_Biohealth_Guide_TeamAdmin_en.pdf)

## API Tutorial <a name="api_tutorial"></a>

[eLabFTW API Support Page](https://alexgu2008.github.io/elabftw_api_support_unigraz/)

## FAQ

> **Who is allowed to use eLabFTW?**
> 
> The eLabFTW ELN was established at Uni Graz by an initiative from the Field of Excellence BioHealth. Currently all Uni Graz staff and students having an active Uni Graz e-mail address are allowed to use the instance. If you are also interested in using it as part of a cooperation, please contact your cooperation partner at UNI Graz.

> **How can I join a specific team?**
> 
> You can select the team you want when you register. If you want to change teams afterwards, please contact the team admin or the SysAdmin.

> **Can I have diffenrnet roles (User, Admin) in different teams?**
> 
> No, the role in eLabFTW is system-wide. This means that you are a user or admin in all teams to which you belong.

> **Do I need additional software on my device?**
> 
> Not really, but you need a browser like Chrome or Firefox or similar and an active internet connection.

> **Do I need a VPN connection?**
> 
> No, you do not have to be directly in the UNI Graz network to use the e-lab notebook.

> **Why is the upload limit for attachments 100 MB?**
> 
> At UNI Graz, eLabFTW is not a data repository for large amounts of data. The e-lab notebook is used to document all imaginable metadata that are part of the research. These are usually smaller than 100 MB.

> **Where is the data located and is it secure?**
> 
> The data is stored on the servers of the IT services of UNI Graz and is protected by their security measures.

## Overview of permissions management in eLabFTW <a name="overview_permissions"></a>

Configuration options are identical for viewing and writing permissions. Entries always have permission settings that are anchored in the base settings. these are taken from the personal default settings or from template settings, but can be changed. Adding one or more teams, team groups or individual users is optional and can, but does not have to be done. Exception: Admin has forced the use of certain permission settings in the team settings.
![](permissions_user.png)

## Tip: Leaving a team/group or the tool <a name="leaving_user"></a>

![](User_Exit.png)
When a user leaves a team, a group or the entire tool, it makes sense to have an offboarding strategy in place beforehand. In the three cases mentioned above, there are a few important points to consider when dealing with eLabFTW. As a user, it is important to remember which entries do not belong to you but you want to keep the information. As an admin or other user of the team, it is also important to think about this point in relation to the entries of the departing user. Entries can be duplicated for further use or exported for external archiving. If you leave the tool as a user, you should always export relevant entries, as you will lose access to them. If you are also the owner of database entries, transfer ownership to the admin of your team. Please remember, if you copy other people's entries, to ask the owner for permission first, as it is the intellectual property of the person concerned. 

## Backup options for users <a name="backup_user"></a>

If you want to save your entries from eLabFTW externally, i.e. on your computer or on another storage medium, this is possible in different ways. We distinguish here between entries in experiments and in the database.

* **Experiments**

  * You can select one or more entries via the web interface and export them directly. Several formats are        available, which can be selected depending on the application. The entry itself remains after the export.     You can also export an entry via the view of an individual entry. Depending on the view, you have             different formats available for export. First check which one you need before exporting the entry(s).
  * You can export all your experiments in one go via your "Profile". This is possible in different formats.      However, only experiments for which you are the owner can be exported.

  * *Option for admins: As an admin, you can perform all experiments of a user in different formats via the       Admin Panel. You can also export database objects and bookings in the calendar here.*

  * *Option via API: Coming soon (only timestamped entries)*

* **Database**

  * You can select one or more entries via the web interface and export them directly. Again, several formats     are available, which can be selected depending on the application. The entry itself remains after the         export. You can also export an entry via the view of an individual entry. Depending on the view, you have     different formats available for export. First check which one you need before exporting the entry(s).

## Contact <a name="contact"></a>

*SysAdmin:* *Alexander* *Bardel*<br>
<alexander.bardel@tugraz.at>
