# ISEC6000_Assignment1
Building and Securing a Microservices E-commerce Application
Task 1: Set Up initial Infrastructure
1. Create a Kubernetes Cluster on GKE (or equivalent tool)
a. Log in to your Google Cloud Console.
![9a52091125e1719ce6eb0302e8d3c1d](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/6cf433b0-291a-4058-8018-7db1cd338154)

b. Navigate to the Kubernetes Engine section and click "Create Cluster."
![fc0dd11497fc871110dcbf9ebcd69d1](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/b075e0ba-5e28-4b21-b90d-c80d55eae81b)
![63a62cdb824b58b2fd1cd954bb72cc2](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/4e674b75-a7b4-484a-b2df-660bff601dd6)

c. Configure your cluster settings, such as the cluster name, location, and node pool
configuration.
![1513b16269525ed606b40a798a13f27](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/454a47bb-9461-4374-9cef-41c8ba7fb52a)

d. Choose the desired Kubernetes version.
![ec0872e45ff47f6f555f59be517fb38](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/a76e00c7-319d-473b-9048-79b932158939)

e. Click "Create" to provision your GKE cluster.
![d4fd75d80775ffcb09dfed3221b5060](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/b8968f0c-e5fd-4fbc-9450-a53465ffbb3b)


2. Install and configure kubectl to manage your Kubernetes cluster.
a. After creating the GKE cluster, you will need to configure your local environment
to use kubectl to interact with this cluster.
![142a0117d534279c980a7a6db208fca](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/d2796243-c189-43ce-a18d-3b6852280b0f)
In the first step, I have download the kubectl

![11b06674bb8102b71d0922d00a22369](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/e9ec866a-b9c8-48fd-a9ad-4f17204e6cad)
This picture above show that I have successfully install kubectl

![863a435d7a136e627cd3c9095f03a41](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/322d17eb-3b53-4dd5-a627-fbb23dfa5cd3)
This for install google cloud CLI, so I can use gcloud command

![03e7b334a5654ed32b27c6b1c3a3ccf](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/3d8b37ca-f018-4562-b017-844eaaf8a1fc)
Successfully installed

![2f8817e199127adcb4b2e1960f93132](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/f209aef4-e293-42ef-993f-efcd7419ea18)
Configuration of gcloud

![31077bf9cf1819275a379952bedaf3a](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/7ffb339f-1c06-4707-a252-1e4990f1b591)
After I installed the google cloud cli, I find out there's some problem with using gcloud command so I decided to verify I was succeed in installing. This for finding the gcloud's location

![c2c02cb930ae3f33416d099fe39856a](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/aef87736-6466-495e-bca0-d2bb482cc15b)
After I found the gcloud's location, I can add it to my PATH

![6051cc45dee3c10c243ddc3e45906d3](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/b68f8e21-69d6-4029-8f2d-af1e382ef1ac)
gcloud could works, but there's another issue that I have discovered with configure local environment to interact with my GKE

![5f802165b83d5f79fe1832477649e05](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/40564a60-ce02-45d6-9d31-e1d26766425b)
Install the components that I fix the problem required above

![a04e74a6ccfcd71a9739a6f89d5a617](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/bb0f6892-cf9f-41aa-ae1e-6920c2c4404b)
SUCCESSFULLY interact with this cluster in my local environment


b. In the Google Cloud Console, navigate to the "Kubernetes Engine" > "Clusters"
section and click the "Connect" button next to your cluster.
![fc88c1328f457c4857de7432988711c](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/efa14c26-9a87-42d4-a289-babe1ca9653c)

![ddb6b6b4f068783143ca998967546d4](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/fc299383-bf17-4c8d-a67b-a161efc72088)

c. Follow the instructions to authenticate kubectl with your GKE cluster
![605c526d8c1438bdd3f83a03a561ac9](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/f82ebbeb-b6a9-4981-90ee-769f3e719c0e)

![6dd672889e2d4b005c7c76da4baca7f](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/d674f6a6-6bf0-4d06-9998-e7053efe785b)

![9e554a0f38dbbf47059c1dbc0ca8b72](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/e3a5d12b-ccbe-468a-8e35-1cb4f23a8c85)

![5a3a843bdb3f10601471a26e4609682](https://github.com/MilloooSy/ISEC6000_Assignment1/assets/143394742/e5c91dcd-a98d-4116-8924-722c1494d65e)
