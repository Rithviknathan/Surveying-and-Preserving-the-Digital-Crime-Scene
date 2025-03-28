# Surveying and Preserving the Digital Crime Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![a1](https://github.com/user-attachments/assets/d2744b84-3e1a-4309-9877-61c9e15d29ac)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  
![a2](https://github.com/user-attachments/assets/6c0c0a60-c877-4b92-9417-f0b8d9f06ca5)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
![a3](https://github.com/user-attachments/assets/af7aac56-d4da-41f7-89e9-fdf624fe93ad)



- Select **Local Disk** → **next** 

![a4](https://github.com/user-attachments/assets/988fc712-fead-44b0-907d-e83388667005)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![a5](https://github.com/user-attachments/assets/798e205b-f483-4ee4-9213-ae3074d310eb)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
![a6](https://github.com/user-attachments/assets/9aed67b8-ae66-4241-8084-6d15fc57bac4)

![a7](https://github.com/user-attachments/assets/4ba9f111-fe61-4012-b11a-3b6e7b54f7e9)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![a8](https://github.com/user-attachments/assets/079df0a2-6fd8-430f-ad72-e2eb4d86e533)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![f1](https://github.com/user-attachments/assets/63f64f94-9526-40b7-b24a-37dcd80c65df)


### Folder after deleting the files
![a9](https://github.com/user-attachments/assets/e8ff8aba-417c-478b-b296-9e0264763dcb)


### Folder after extracting the deleted images using autopsy
![a10](https://github.com/user-attachments/assets/57a30a0e-fe04-4a00-bbb1-9fc29a133a69)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
