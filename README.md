<p align="center">
<img src="https://azure.microsoft.com/svghandler/azure-icon.svg" alt="Azure Logo">
</p>

<h1>Microsoft Azure Subscription Tutorial</h1>
In this tutorial, we will be signing up for a free 30 day ($200 credit) subscription to Microsoft Azure. Azure is a cloud computing platform with over 200+ set of services offered by Microsoft. It provides companies and individuals with a range of cloud based solutions such as virtual machines, storage, data bases, networking, and analytics. Users can run their apps, store their data, and host their websites within the platform. It also includes tools for developers to build, test, and deploy apps across a variety of programming languages and frameworks.<br />


<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for $200 free Azure credits for 30 days, then it's a pay as you go subscription. You will only get charged for what you use)

<h2>Operating Systems Used </h2>

- Windows 10

<h2>Actions and Observations</h2>

This is a mental preview of the structure of what we will be creating once everything has been set up. When we first set up our free account, the platform will create what is called a "Tenant" which is essentially a representation of your organization. Once that is created, we will create a subscription. You can create multiple ones if you like. For instance, if you have different departments with their own budget, you can create a subscripton to segregate costs but in this tutorial we will be creating one. Inside of the subscription, you can have one or more resource groups which act like folders to hold resources that you create such as virtual machines, databases, and storage accounts. Inside our resource group, we will be creating an Azure Storage Account. Think of it as a Google Drive or a Dropbox with more capabilities.
</p>
<p>
<img src="https://i.imgur.com/tYpKbcl.png"> 
</p
<p>

<h2>Steps</h2>

- Go to **https://azure.microsoft.com/en-in/free** and click on **Start Free** and create an account. You'll then be recieving a code and have to solve a set of puzzles to verify your account. Next, enter your personal and credit card information to received your $200 free credits and click **Sign up**. You then should see a page that says **You are ready to start with Azure**. Click on **Go to Azure portal**. You're now all set!
</p>
<p>
<img src="https://i.imgur.com/78VTOJX.png"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/uPXAhmx.png"/>
</p>
<p>  

- Next we will be creating a **Resource Group**. From the **Home** screen you will want to either do a :mag:, look next to **Azure Services**, or under **Navigate**, and click **Resource Groups**.

<img src="https://i.imgur.com/SZh3dZH.png"/> 
</p>
<p>

Click **+ Create**  

<p>
<img src="https://i.imgur.com/B2Ncz9S.png"/>
</p>
<p> 

For **Subscription**, just leave it alone since we are just creating one in this tutorial. **Resource group** will be named *RG-Lab-01* in this exmaple, but you can name it whatever you like. For **Region**, you can choose the one that you're currently living in. Click **Next**. We don't have to specify **Tags** if you don't want to. Used for organizations to keep track of certian resources. Click **Review + create**
  
<p>
<img src="https://i.imgur.com/F5xLtEq.png"/>
</p>
<p>

Verify **Validation passed** and Click **Create**

<p>
<img src="https://i.imgur.com/MTollLG.png"/>
</p>
<p>

Congrats! 🎉 You have just created a Resourse Group.

<p>
<img src="https://i.imgur.com/omtNtxd.png"/>
</p>
<p>  

- Next we will be creating a **Storage Account**. Just like **Resource groups**, from the **Home** screen you will want to either do a :mag:, or look next to **Azure Services** and click **Storage accounts**. 

<p>
<img src="https://i.imgur.com/Su6reQB.png"/>
</p>
<p>

Click **+ Create**

<p>
<img src="https://i.imgur.com/1CF3GKp.png"/>
</p>
<p>

For **Subscription**, we'll just leave it alone. **Resource group** will be named *RG-Lab-01*. **Storage account name** should be a unique name ie (*juliantutoriallab01*). For **Region**, you can choose the one that you're currently living in. For **Redundancy**, we will choose *GRS*, however, you can research and choose what best suits you if needed. Click **Review** and then click **Create**, and then click on **Got to Resource** and verify your created storage account.

<p>
<img src="https://i.imgur.com/r15koDd.png"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/Nch9b2G.png"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/ow9XUs9.png"/>
</p>
<p> 

Congrats! 🎉 You have just created a Storage Account.

- Next we will be creating a **Container**. Within our **Storage Account** that we just finished creating, click on **Containers**.

<p>
<img src="https://i.imgur.com/plJH8mg.png"/>
</p>
<p>
  
  Click on **+ Container**
  
<p>
<img src="https://i.imgur.com/LKmrEoF.png"/>
</p>
<p>  
  
Give your **New container** a name. For this tutorial we will leave **Public access level** as *Private (no anonymous access)* and then click **Create**.

<p>
<img src="https://i.imgur.com/RlVQPSS.png"/>
</p>
<p>  

Click on your new created container. 
  
<p>
<img src="https://i.imgur.com/rzvgpkE.png"/>
</p>
<p>   

Now from your computer, open up Notepad and just create a unique message and save it to your Desktop. 
  
<p>
<img src="https://i.imgur.com/BzbS0NL.png"/>
</p>
<p> 

Now within you container, upload your new .txt file.

<p>
<img src="https://i.imgur.com/lI2j3zv.png"/>
</p>
<p>  

Congrats! 🎉 You have just created a **Container** file in your Storage Account.

</p>
<br />

- Now we will be cleaning up our resources so that you don't eat up all your free credits. From the **Home Screen**, click on **Resouce groups** 

<p>
<img src="https://i.imgur.com/F6pji0T.png"/>
</p>
<p>

Click on your resource group.
  
<p>
<img src="https://i.imgur.com/g6vNCf5.png"/>
</p>
<p>  

Click on **Delete resource group** and copy or type in your resource group in the *Enter resource group name to confirm deletion* and click **Delete**. Make sure that when you clean up and delete your resources that they are actually deleted. This may take a few minutes to complete but you can verify by clicking on **Resource groups** and you should see that there is nothing to display.

<p>
<img src="https://i.imgur.com/yr9mY7K.png"/>
</p>
<p> 

<p>
<img src="https://i.imgur.com/5pN2Idx.png"/>
</p>
<p>
  
Congrats! 🎉 If you made it this far, you have just created your Azure account, learn how to create a resource group, a storage account with a container file within it. 
