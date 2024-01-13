<p align="center">

![Microsoft_Azure-Logo wine](https://github.com/JoshuaMoorecc/Creating-VM/assets/154629831/dbdfa8a2-56bb-4c32-8e21-4300c5bd5be8)


</p>

<h1> Creating a VPN with Azure </h1>
This tutorial outlines the implementation of Creating a VPN within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>Deployment and Configuration Steps</h2>




![Screenshot (225)](https://github.com/JoshuaMoorecc/VPN/assets/154629831/ab1bc7b2-37ba-404e-b875-c7dc5acbd80b)


The first step is to create a VM inside of Azure -> Copy the public Ip address -> then open ip remote desktop.


![20 238 8 182 - Remote Desktop Connection 1_12_2024 3_43_14 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/6fb64082-7ba1-4c86-9053-17d1c1d95f93)


Once inside of the remote desktop open up a browser -> search  whatismyip address


![20 238 8 182 - Remote Desktop Connection 1_12_2024 3_43_14 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/e08a8f07-809d-4eb7-8143-34e439b51cc3)



Once you confirm your VM ip address -> Go back to your home computer screen -> Go to Proton VPN.com -> resitar and sign up on your home computer (personal comupter)


![Screenshot (226)](https://github.com/JoshuaMoorecc/VPN/assets/154629831/f779c886-6336-4ea8-bc63-8597659a398c)


After signing up couy the download URL  -> then got back to the remote desktop and past the url in the browser -> hit enter



![20 238 8 182 - Remote Desktop Connection 1_12_2024 3_49_32 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/ebbdf066-1e9c-4794-8e17-51b23c17a4c5)


 Download and sign in to the windows client of Proton VPN inside VM (remote desktop)


![20 238 8 182 - Remote Desktop Connection 1_12_2024 3_51_44 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/731777cb-023e-423c-9696-e926324db4e9)


Once the file is downloaded, sign in to proton VPN -> Once Proton VPN opens up select connect to VPN and wait for the connection to finish.


![20 238 8 182 - Remote Desktop Connection 1_12_2024 6_00_46 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/8f1aeaec-0924-4071-8f56-3236d55f3edc)


Once the VPN connection is established -> Open up a new browser window in the VM and search for a what is my ip addresss.


![20 238 8 182 - Remote Desktop Connection 1_12_2024 6_07_16 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/bcc856cb-5ad7-4bf6-9154-dc42a59afe96)


The new Ip address should be in Japan if done correctly


![20 238 8 182 - Remote Desktop Connection 1_12_2024 6_37_00 PM](https://github.com/JoshuaMoorecc/VPN/assets/154629831/c1aebdbc-e9ff-422e-b66f-37a0efebd974)


Open up a new browser tan and search for a popular website, I chose Netflix, and it should be Netflix Japan

If you followed the steps correctly, Congratulations you have created a VPN!!







