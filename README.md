<p align="center">
  <h1 align="center">Getting To Know Microsoft Azure</h1>
</p>

<h2>TLDR: Exploring Microsoft Azure Essentials</h2>

- <p><b>Azure Portal Home Page: </b>Your cloud command center.</p> 
- <p><b>All Resources: </b>Organize and manage all your digital assets.</p> 
- <p><b>Resource Groups: </b>Group resources together for easier management.</p> 
- <p><b>Virtual Network: </b>Build your own digital network.</p> 
- <p><b>Virtual Machine: </b>Create and control your virtual computer.</p> 
- <p><b>Network Security Group: </b>Guard your network with added security.</p> 
- <p><b>Users: </b>Manage who accesses your cloud space.</p> 
- <p><b>Storage Accounts: </b>Store and manage your digital belongings.</p> 
- <p><b>Cost Management: </b>Keep track of your spending and budget wisely.</p> 

<h2>How to read each section (in this order)</h2>

<b>Section-Intro</b> 

- <p><b>Objectives: </b>Each section begins with a description, outlining the goals and key questions to set expectations.</p> 

<b>Image</b> 

- <p><b>Numbering: </b>Within the images are sequential numbers, with corresponding text explanations directly below each image.</p> 
- <p><b>Yellow highlights: </b>Yellow highlights are navigation aids to help identify your current section in the Azure portal.</p> 

<b>Text numbers</b> 

- <p><b>Descriptions: </b>Each number provides a brief explanation of the image directly above it.
</p> 

<h2>Introduction</h2>

<p>&nbsp;&nbsp;&nbsp;&nbsp;Welcome! This guide is designed to arm you with the knowledge and exposure necessary to navigate the complexities of Azure with ease. Through a strategic emphasis on repetition and hands-on exploration of pivotal Azure portal features, you'll embark on a journey of discovery into the realm of cloud technologies. We will explore the most essential and frequently used sections of the Azure portal. Please note that while the platform's interface may change over time, the core services remain consistent. As of May 2024, this guide reflects the current state of the Azure portal, although there may be some updates to the frontend in the future.
</p>

<h2>Azure Portal's Homepage Section</h2>

<p><b>Description: </b>The Azure Portal homepage is like the main screen on your computer or tablet where you see all your important apps and shortcuts. It has a dashboard that you can customize by adding and arranging tiles for your favorite and most-used tools. On the left side, there's a menu that lets you quickly access different Azure services like virtual machines and databases. At the top, there's a search bar to help you find anything you need in Azure. Plus, it shows you important alerts and updates about your cloud resources to keep you informed.</p>

<p><b>Goal: </b>Get acquainted with the Azure Portal's Homepage.</p>

- <p>How do we access Azure Portal's Homepage?</p>
- <p>How can we confirm we are in the Azure Portal's Homepage?</p>
- <p>What buttons are available in the Azure Portal's Homepage?</p>
- <p>What sections are present in the Azure Portal's Homepage?</p>

![00_homePage](https://github.com/ImranHuhn/AzureIntro/assets/52342912/ab884483-2fe8-43d6-b9ed-5bfc1244b39c)

0.  <b>Access the Portal: </b>Visit portal.azure.com.
1.  <b>Search Bar: </b>Locate services that Azure offers.
2.  <b>Recent Services: </b>View the services you recently accessed.
3.  <b>All Services: </b>Access a comprehensive list of Azure services.
4.  <b>Recent Resources: </b>View the resources you last interacted with.

<h2>All Resources Section</h2>

<p><b>Description: </b>The "All Resources" section in Azure is like a giant library where you can find every book you own. This section lists all the different parts of your projects, like virtual machines, databases, and storage accounts, in one place. It makes it easy to search for, view, and manage any resource you have, no matter which project it belongs to. You can quickly see important details about each resource, like its status and location. It's like having a super-organized bookshelf where you can always find the exact book you need.</p>

<p><b>Goal: </b> Become familiar with "All resources."</p>

- <p>How do we navigate to "All resources"?</p>
- <p>How can we verify we are in "All resources"?</p>
- <p>What buttons are included in "All resources"?</p>
- <p>What sections are found in "All resources"?</p>

![01_allresources](https://github.com/ImranHuhn/AzureIntro/assets/52342912/6673754a-313d-4dd0-ad21-ad86466b2259)

1.  <b>Navigate: </b>Type "All resources" in the search bar and click the icon. Yellow-highlighted text confirms you are on the correct page.
2.  <b>Create Button: </b>Commonly used to add new resources.
3.  <b>Refresh Button: </b>Update the dashboard if new resources don’t appear immediately.
4.  <b>Create Button Alternative: </b>If "All Resources" is empty, an alternative create button will appear.
5.  <b>Bell Icon: </b>View notifications and build status.
6.  <b>Delete Button: </b>Remove existing resources.

<h2>Resource Groups Section</h2>

<p><b>Description: </b>The "Resource Groups" section in Azure is like having a folder for each of your school projects. Each folder (resource group) contains everything you need for a project, like documents, pictures, and notes, so you can easily find and manage them all in one place. This makes it simpler to set up, monitor, and maintain your projects. You can also control who has access to each folder, ensuring your work stays secure. Additionally, resource groups help you keep track of how much you're spending on each project, making it easier to manage your resources.</p>

<p><b>Goal: </b> Familiarize yourself with “Resource groups”.</p>

- <p>How do we navigate to “Resource groups”?</p>
- <p>How to identify if we are in “Resource groups”?</p>
- <p>What buttons does “Resource groups” contain?</p>
- <p>What sections exist in “Resource groups”?</p>

![02_resourcegroup](https://github.com/ImranHuhn/AzureIntro/assets/52342912/2b0d6cc4-97f2-45b8-9e6b-f99a194b5f78)

1.  <b>Navigate: </b>To find your way, enter "Resource groups" into the search bar and select the corresponding icon. Confirmation of being on the correct page is indicated by highlighted text in yellow.
2.  <b>Create Button: </b>Used to create a resource group for inter-service communication.
3.  <b>Refresh Button: </b>Updates the dashboard frontend.
4.  <b>Alternative Create Button: </b>Appears when the resource group list is empty.
5.  <b>Bell Icon: </b>Notifications for resource group creation status.
6.  <b>Delete Option: </b>Appears when clicking on individual resource groups to remove them.

<h2>Virtual Networks Section</h2>

<p><b>Description: </b>The "Virtual Networks" section in Azure is like setting up a private playground for your computer programs. Imagine having a fenced-off area where only your friends can come to play; that's what a virtual network does for your applications. It lets you connect different parts of your projects, like virtual machines and databases, securely so they can communicate with each other. You can control who gets to join this network and how they can interact. This setup helps keep your information safe and makes sure everything works smoothly together.</p>

<p><b>Goal: </b> Familiarize ourselves with “Virtual networks”.</p>

- <p>How do we navigate to “Virtual networks”?</p>
- <p>How to identify if we are in “Virtual networks”?</p>
- <p>What buttons does “Virtual networks” contain?</p>
- <p>What sections exist in “Virtual networks”?</p>

![03_virtualnetwork](https://github.com/ImranHuhn/AzureIntro/assets/52342912/278f905b-f3d2-4df0-a4c8-88d9ed8bea33)

1.  <b>Navigate: </b>Enter "Resource groups" into the search bar and click on the corresponding icon. Confirmation that you're on the right page will be shown with text highlighted in yellow.
2.  <b>Create Button: </b>Creates a new virtual network.
3.  <b>Refresh Button: </b>Updates the list of existing virtual networks.
4.  <b>Alternative Create Button: </b>Shows up when there are no items in the resource group list.
5.  <b>Notification Button: </b>Shows status of new virtual network creation.
6.  <b>Delete Option: </b>Appears when clicking on an individual virtual network to remove it.

<h2>Virtual Machines Section</h2>

<p><b>Description: </b>The "Virtual Machines" section in Azure is like having a collection of powerful computers that you can use from anywhere. These virtual machines (VMs) can run different programs and tasks just like your home computer, but they live in the cloud. You can easily create, configure, and manage these VMs to do things like hosting websites, running applications, or storing data. It’s like having a remote control for a bunch of supercomputers, letting you start, stop, and customize them whenever you need. Plus, you only pay for the time you use them, making it a flexible and cost-effective solution for your projects.</p>

<p><b>Goal: </b> Familiarize ourselves with “Virtual machines”. </p>

- <p>How do we navigate to “Virtual machines”?</p>
- <p>How to identify if we are in “Virtual machines”?</p>
- <p>What buttons does “Virtual machines” contain?</p>
- <p>What sections exist in “Virtual machines”?</p>

![04_virtualmachine](https://github.com/ImranHuhn/AzureIntro/assets/52342912/99935880-2890-4b53-97ad-d971892ce3c9)

1.  <b>Navigate: </b>Let's access virtual machines by entering it into the search bar.
2.  <b>Create Button: </b>This button initiates the creation of a new virtual machine (VM).
3.  <b>Switch View: </b>This option transitions to the classic view, which bears minimal visual contrast.
4.  <b>Refresh: </b>Use this button to update the VM list if a newly created one hasn't appeared yet.
5.  <b>Alternate Creation:</b> This method is available only when no VMs currently exist.
6.  <b>Notification Bell: </b>This icon provides updates on the status of the VM you've created.
7.  <b>Start: </b>Activate this button to power on a currently off VM.
8.  <b>Graceful Shutdown: </b>Use this function to smoothly power off and then on the VM.
9.  <b>Stop: </b>This option enables a graceful shutdown of the VM.
10. <b>Delete: </b>Choose this action to remove the VM from the list.

<h2>Network Security Groups Section</h2>

<p><b>Description: </b>The "Network Security Groups" section in Azure is like having a security guard for your house, but for your computer stuff. It's a way to set rules for what can come in and out of your virtual space, like your gaming world or your homework folder. You can decide who gets to visit and what they can do there, like allowing only your friends to play games with you or only letting certain websites load. These rules help keep your stuff safe from bad things that might try to sneak in. By using network security groups, you can control who can access your virtual world and make sure everything stays protected.</p>

<p><b>Goal: </b> Familiarize ourselves with “Network security groups”. </p>

- <p>How do we navigate to “Network security groups”?</p>
- <p>How to identify if we are in “Network security groups”?</p>
- <p>What buttons does “Network security groups” contain?</p>
- <p>What sections exist in “Network security groups”?</p>

![05_networksecuritygroup](https://github.com/ImranHuhn/AzureIntro/assets/52342912/96b14475-f222-4459-8a3d-0a1653a937a7)

1.  <b>Navigate: </b>Access Network security using the search bar.
2.  <b>Create Button: </b>This initiates the creation of a new network security group (NSG).
3.  <b>Update: </b>This refreshes the NSG list if the one you just created isn't visible.
4.  <b>Alternate Creation: </b>This is another method to create a new NSG, accessible only when the NSG list is empty.
5.  <b>Status Check: </b>This is to view the status of the NSG you just created.
6.  <b>Deletion: </b>A delete button will appear here when clicking on an NSG, allowing you to remove it.

<h2>Users Section</h2>

<p><b>Description: </b>The "Users" section in Azure is like your friend list in a video game. It's where you can see all the people who can access and use the game with you. Each user has their own username and password, just like in the game, so they can log in and play. You can control what each user can do, like if they can change settings or just play the game. It helps keep everything organized and makes sure only the right people can join in on the fun. Plus, if someone new wants to join, you can add them to the list so they can start playing too!</p>

<p><b>Goal: </b> Familiarize ourselves with “Users”. </p>

- <p>How do we navigate to “Users”?</p>
- <p>How to identify if we are in “Users”?</p>
- <p>What buttons does “Users” contain?</p>
- <p>What sections exist in “Users”?</p>

![06_users](https://github.com/ImranHuhn/AzureIntro/assets/52342912/6a270956-6431-41d2-9dd3-f52527326f8c)

1.  <b>Navigate: </b>Go to "Users" through the search bar.
2.  <b>New User: </b>This option is for creating a user.
3.  <b>Refresh: </b>Use this to update the list view after creating a new user.
4.  <b>Existing Users: </b>This area displays a list of current users.
5.  <b>Status Check: </b>This button allows you to view the status of the newly created user.
6.  <b>Delete: </b>This is the delete button to remove a user or multiple users.

<h2>Storage Accounts Section</h2>

<p><b>Description: </b>The "Storage Accounts" section in Azure is like having a big locker where you can store all your stuff online. Each locker (storage account) can hold different things like pictures, videos, and files, just like the compartments in your school locker. These storage accounts help you keep your things safe and organized, so you can easily find them when you need them. You can also decide who can access each locker, making sure only the right people can see your stuff. Plus, you can keep track of how much stuff you have stored and how much it's costing you, just like keeping track of your belongings in your locker at school.</p>

<p><b>Goal: </b> Familiarize ourselves with “Storage accounts”. </p>

- <p>How do we navigate to “Storage accounts”?</p>
- <p>How to identify if we are in “Storage accounts”?</p>
- <p>What buttons does “Storage accounts” contain?</p>
- <p>What sections exist in “Storage accounts”?</p>

![07_storage](https://github.com/ImranHuhn/AzureIntro/assets/52342912/141c736b-5a78-47b9-ad20-124d73ad457b)

1.  <b>Navigate: <b>Head to storage accounts.
2.  <b>Create Button: <b>Click here to make a new storage account.
3.  <b>Refresh: <b>Use this to update the list after creating a new storage account.
4.  <b>Alternate Creation: <b>This provides another method to create a new storage account when the list is empty.
5.  <b>Notification Bell: <b>This icon notifies if the storage account has been successfully created.
6.  <b>Delete: <b>Use this button to remove any storage account you choose.

<h2>Cost Management Section</h2>

<p><b>Description: </b>The "Cost Management" section in Azure is like having a piggy bank for your online activities. It helps you keep track of how much money you're spending on using different services, like video games or apps. You can see where your money is going and figure out ways to save by using only what you need. It also lets you set limits on how much you can spend, just like how your parents might give you an allowance. By understanding your spending habits, you can make smarter choices about what you use and how much it costs.</p>

<p><b>Goal: </b> Familiarize ourselves with “Cost management”.  </p>

- <p>How do we navigate to “Cost management”?</p>
- <p>How to identify if we are in “Cost management”?</p>
- <p>What buttons does “Cost management” contain?</p>
- <p>What sections exist in “Cost management”?</p>

![08_costmanagement](https://github.com/ImranHuhn/AzureIntro/assets/52342912/9a299df7-58a0-4439-8371-d0a607442aa6)

1.  <b>Navigate: </b>Go to cost management.
2.  <b>Left Panel: </b>Here are the options to either go to cost alerts or budgets.

    a. <b>Cost alerts: </b>These trigger when expenses surpass the budget.
    
    b. <b>Budget: </b>These activate when expenses fall below and are nearing the budget limit.
    
    c. We will be focusing on the budget only.

<h2>Conclusion</h2>

<p>&nbsp;&nbsp;&nbsp;&nbsp;In conclusion, this guide aims to empower you with the exposure and knowledge needed to navigate through Azure with less fear and hesitation. By emphasizing intentional repetition and exploration of key Azure portal features, you can now get some hands-on experience with cloud technologies. While the interface of the Azure portal may evolve over time, rest assured that the foundational services remain steadfast, providing a reliable framework for your cloud endeavors. Again, as of May 2024, this guide offers a comprehensive snapshot of the Azure portal's functionality, with updates to the frontend anticipated in the future. Embrace the journey ahead, harness the power of the cloud, and let this guide remove any fear and uncertainty you may have about the complexity of cloud technologies. Later!</p>
