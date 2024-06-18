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


![Screenshot 2024-06-18 132950](https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/e86d3e62-1971-4091-bfd3-16d686d3553d)



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

<img width="806" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/825b635e-4ed3-423d-b82a-d3eebdc02e3a">


<img width="944" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/a0684e48-d350-4c9d-b94d-8d40a6e48eb2">

-------------
----------------------
### Tweet exactly as screenshot and Submit Proof in Dscord 

<img width="466" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/e5b0f4dd-caf7-4614-b096-59409b4e4b8b">



--------------------------
### Submit in Discord 
<img width="854" alt="image" src="https://github.com/Ramakotireddypammi/Alignedlayer_testnet_proof/assets/136354890/b170de67-ed31-45b1-a98c-e36ef6f1906f">


# JOIN DISCORD FROM PROFILE 
https://linktr.ee/AlignedLayer





