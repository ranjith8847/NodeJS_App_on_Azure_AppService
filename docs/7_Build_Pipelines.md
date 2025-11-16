## 7. BUILD PIPELINES

Go to ADO and open the project repository.  
Navigate to: **Pipelines → Create Pipeline (or New Pipeline) → Use the Classic Editor**

![Enter image alt description](../Images/TCU_Image_38.png)

---

Start with **Empty Job**.

![Enter image alt description](../Images/k8X_Image_39.png)

Click “+” on **Agent job 1**.

Search for **Command Line**, select it, and click **Add**.

![Enter image alt description](../Images/lNC_Image_40.png)
![Enter image alt description](../Images/5SL_Image_41.png)

---

Again click “+” on **Agent job 1**.

Search for **Publish Build Artifacts** and click **Add**.

![Enter image alt description](../Images/988_Image_42.png)
![Enter image alt description](../Images/xSf_Image_43.png)

---

Finally, click on the pipeline name at the top and select the **Agent Pool**  
(the self-hosted agent pool created in the previous step).

![Enter image alt description](../Images/Avc_Image_44.png)

Click **Save and Queue**, then click **Run**.

Now you can see your build pipeline executing.

---

### **Note**
Since this demo builds a Node.js application, the self-hosted VM must have **Node.js** and **npm** installed.

Install them by SSH-ing into the VM and running:

```
sudo apt update
sudo apt install nodejs
sudo apt install npm
```
