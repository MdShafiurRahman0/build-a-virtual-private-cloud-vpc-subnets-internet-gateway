### Cloud Networking - Build a Virtual Private Cloud



You'll dive into the core of AWS networking by creating your very own Virtual Private Cloud (VPC).

Setting up and managing a VPC is a vital skill for anyone looking to master cloud infrastructure. Today, you'll learn how to set up and configure a VPC from scratch.

Let's get ready to:

☁️ Create an Amazon VPC.
🥅 Create a public subnet.
🚪 Create an internet gateway.



![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/a35fc200-2d72-483c-9483-b1ab10745524)



### Step 1: Create a VPC

![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/37a46847-dfde-440e-a730-57a89bae0a83)



![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/8f676f85-61c4-4bdc-8232-f7f8122202ad)


1. Choose VPC Only.

2. Name tag: NextWork VPC

3. IPv4 CIDR: 10.0.0.0/16



![2024-07-10_21h47_12](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/88732109-efbb-4a94-844c-25cc2997a063)


![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/53eb1f71-c83e-4724-8db5-ef876a80b4ac)



### Step 2: Create Subnets

1. Subnets are subdivisions within your VPC where you can launch AWS resources.

2. In the VPC Dashboard, under Virtual Private Cloud, choose Subnets


![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/1c839838-6ac3-4559-a7a3-5b5849ee04e9)




![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/a490919d-66a2-40f9-b59f-33c037079847)




### Configure your subnet settings:

1. **VPC ID:** NextWork VPC
2. **Subnet name:** Public 1
3. **Availability Zone:** Select the first Availability Zone in the list.
4. **IPv4 VPC CIDR block:** 10.0.0.0/16
5. **IPv4 subnet CIDR block:** 10.0.0.0/24



![2024-07-10_22h18_13](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/ed73b5f2-11df-4734-bc38-3ff5d5a55afe)



### High Level Overview of CIDR block and Public Subnet IP

![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/b6828d44-eb1d-4be3-b0d8-c018b37fb371)



1. Select the checkbox next to Public 1.

2. In the Actions menu, select Edit subnet settings.


![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/c7bed66f-80b0-43f9-9b19-9fe0ad1689fa)



### Check the box next to Enable auto-assign public IPv4 address.

![2024-07-10_22h20_32](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/e5ff8272-6367-414e-be6f-0b178afd99fc)





### Step 2: Create an Internet Gateway

1. VPC done!

2. Subnet done!

3. Time for the last step to connect our VPC to the internet... an Internet Gateway. Here's what the architecture diagram looks like:

   

![image](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/3cbe64ce-d2b0-4aa7-883e-e282a297e829)



![2024-07-10_22h39_27](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/f082fd22-a99c-4306-ae27-d1debfed2f2d)



### Select your newly created internet gateway and choose Actions, then Attach to VPC.



![2024-07-10_22h40_16](https://github.com/MdShafiurRahman0/build-a-virtual-private-cloud-vpc-subnets-internet-gateway/assets/113176437/0713d891-2f48-4bbf-98cb-3d1a8d02276b)
