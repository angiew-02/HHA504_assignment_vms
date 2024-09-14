# HHA504_assignment_vms
The objective of this assignment is to provide hands-on experience with managing Virtual Machines (VMs) in both Azure and Google Cloud Platform (GCP). You will learn how to start, stop, and monitor the costs associated with running VMs on these cloud platforms.
# 1. Start and Stop a Virtual Machine
### *Azure*
Was not able to create a VM for Azure due to not being able to select a size. According to the lecture, to delete azure VM we must first stop the machine using the stop icon first and then use the delete icon to delete. Make sure to delete everything by selecting the OS disk, network interfaces, and the public IP addresses. 

![Azure vm](https://github.com/user-attachments/assets/88f44c28-315c-40e4-8c89-1f18e2c66d9c)
### *GCP*
To create a VM naviate to compute engine and select create instance. Select the VM instance that you want to create and select create. It should take approximately 1 min for the VM to create. 

![GCP vm](https://github.com/user-attachments/assets/77338b2b-dfe8-4f1a-b702-6a10196bd775)

To stop the VM, select the hamburger like button on the top left and navigate to the stop icon. Once you confirm to stop the VM it should take approximately 1 min for it to stop. You will know that the VM is stopped when the status under basic information turns from running to stopped. Then to delete the VM selected the delete icon that is also located in the hamburger like button on the top left and confirm to delete. This should also take approximately 1 min to delete. Once it is deleted, the VM would no longer be in your VM instances. 

![GCP stop/delete](https://github.com/user-attachments/assets/6bc169e6-066d-4a09-9213-79fe4bdf1d81)

# 2. Monitor VM Costs
### *Azure*
Was not able to create a vm for Azure due to not being able to select a size therefore was not able to monitor the vm costs. If I want to view the cost of the VM, I would navigate to cost management + billing to see any cost. 
### *GCP*
It does not look like the VM that I created incurred any cost. This might be because I did not run it long enough before I deleted the vm as I had only ran the VM for approximately 8 minutes. 

![GCP vm cost](https://github.com/user-attachments/assets/d4a14a70-b42b-4d83-988e-96ef2a3e2c6b)
# 3. Compare and Reflect
#### Compare the costs of running a VM in Azure versus GCP. Consider factors such as the configuration used, the duration for which the VM was active, and any differences in cost visibility between the platforms.
I was unable to ran the VM in Azure due to my subscription not being able to select a size; however, after watching the lecture on how to make a VM on Azure, I have some information to make a conclusion on both platforms. I found that the cheapest option for both the Azure and GCP VMs are about similar pricing per month with Azure being slightly more expensive at $7.20 a month and GCP at $7.11 a month. 
#### Reflect on the ease of starting, stopping, and monitoring VMs on each platform. Which platform did you find more intuitive or user-friendly? Why?
The ease of starting, stopping, and monitoring VMs on Azure and GCP are similar in both platforms as they are both easy to navigate around. There is some slight differences however. For example to stop the VM machine on GCP, it requires more time then to stop the VM on Azure. In Azure when you go to delete the VM you would have to make sure to delete everything including the OS disk, network interfaces, and the public IP addresses by selecting on each one. This may be benefical to those that may want to keep some parts of the VM. On the other hand, in GCP when you delete, it deletes everything. The platform that I find to be more user-friendly is the Azure VM as it provides a quicker method of starting and stopping the VM. Another function that I believe makes Azure VM more user-friendly is the auto-shutdown option which allows indivduals to set a time for automatic shutdown of the VM which can save cost. 








