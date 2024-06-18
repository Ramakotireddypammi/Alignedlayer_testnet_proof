# Alignedlayer_testnet_proof
# ALIGNEDLAYER PUBLIC PROOF TASK  

<img width="924" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/b0eba04c-c83b-430e-9860-86be6306fa95">


## Getting Srtarted 

```
sudo apt update -y
sudo apt upgrade -y
```

### Install curl 
```
sudo apt-get install curl -y
```

### Download ALignedProof 
<img width="814" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/2b195af0-6d12-4e40-a09e-f89619edeadd">

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```

```
source /root/.bashrc
```


### Download an example SP1 proof file with it's ELF file 
<img width="812" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/18d676f8-bd78-4c20-af40-ef5f56998c8c">


```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```


### Sending proof 

![Uploading Screenshot 2024-06-18 132950.png…]()


```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

Use the explorer link in CMD to check if verified and you'll also see below image. 




-------------
----------------------
### Tweet exactly as screenshot and Submit Proof in Dscord 

![image](https://github.com/mztacat/Alignedlayer-Testnet-Proof-/assets/31314340/91eb3840-5a65-4bf5-b617-b2b4b3c56e72)



--------------------------
### Submit in Discord 
![image](https://github.com/mztacat/Alignedlayer-Testnet-Proof-/assets/31314340/222ac207-1ad8-49e1-b079-b384c7e7a8ae)


# JOIN DISCORD FROM PROFILE 
https://linktr.ee/AlignedLayer





