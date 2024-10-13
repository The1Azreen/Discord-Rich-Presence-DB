# Discord-Rich-Presence-DB

## TUTORIAL
**Importing the Project**
Due to Unity's project size exceeding GitHub's file size limit, we have compressed the project into a Unity package. You can import it into another Unity project to see how the code works.

**Video Tutorial**

**Step-by-Step Instructions**

### 1. Download and Install Unity
[Unity](https://unity.com/)

### 2. Create a New Unity Project
Create a new Unity project with Unity Editor 2022.3.47f1.

### 3. Import the Unity Package
Import the `INF2003unity.package` via the **Assets** tab -> **Import Package** -> **Custom Package**.

### 4. Select and Import Dependencies
Select all the dependencies and import them.

### 5. Resolve Newtonsoft Error
Once imported, you will notice a Newtonsoft error. To resolve this, head to the **Window** tab and find **Package Manager**.

### 6. Add Newtonsoft Package from Git URL
Click the **+** sign and choose **Add Package from Git URL**. Enter the following link: `https://github.com/jilleJr/Newtonsoft.Json-for-Unity.git#upm`.

### 7. Click Import and Download
Click **Import** and **Download**, and the project is now ready for use.

### 8. Review the Code
Our code can be found under the **Scripts** folder for review.

**Using the Discord Plugin**

**Video Tutorial**

To use the Discord plugin, follow these steps:

### 1. Create a Discord Application
Head to the [Discord Development Portal](https://discord.com/developers/applications) and log in with a Discord account.

### 2. Create a New Application
Click **Create New Application**, choose a name, and find the **Application ID**. Copy the ID, as it will be used to display your Discord status.

### 3. Enable Developer Mode
Head to your Discord app, go to **Settings**, type "advanced", and enable **Developer Mode**.

### 4. Login with Discord ID
Head to the project app, log in with your Discord ID, and paste the Client ID.

### 5. Choose a Game and Display Status
Choose a game you want to display in your curated list and click **Display Status**. You should see the status updated on Discord.

**Installing Dependencies One by One**

If you want to install each dependency one by one, follow these steps:

### 1. Download SQLite Binaries
Download the precompiled binaries for Windows 64-bit DLL from [SQLite](https://www.sqlite.org/download.html).

### 2. Extract and Add to Plugins Folder
Extract the `.def` and `.dll` files and drag them into the **Plugins** folder under **Assets** in your Unity project.

### 3. Add Mono.Data.Sqlite.dll
Go to `\Editor\Data\MonoBleedingEdge\lib\mono\unityjit-win32` (Unity Editor path) and copy `Mono.Data.Sqlite.dll` into the **Plugins** folder.

**Video Tutorial**: https://www.youtube.com/watch?v=8bpYHCKdZno&ab_channel=Digestible
