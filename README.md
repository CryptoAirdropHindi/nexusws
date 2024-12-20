# How To Run Nexus CLI

### Step 1: Register and Get Prover ID
1. Go to the web: [beta.nexus.xyz](https://beta.nexus.xyz).
2. Register using your email in the profile section.
3. Inspect the website to get the prover ID:
   - Open the browser's Developer Tools (F12 or right-click and select "Inspect").
   - Go to the "Console" tab and run the following command:
     ```javascript
     localStorage.getItem('flutter.proverId');
     ```
4. Copy the `flutter.proverId` value.

---

### Step 2: Run Nexus

1. **Clone Repository**
   ```bash
    git clone https://github.com/CryptoAirdropHindi/nexusws.git
    cd nexusws

2. Process On Screen
   ```
   screen -S nexus
   ```
3. Change File Permissions
   ```
   chmod +x run.sh
   ```
4. Run Script
   ```
   ./run.sh
   ```
5. Save On Screen
   CTRL A+D
---
<br>

#Old user use this command line by line
```
screen -r nexus

cd

cd .nexus

ls

nano prover-id
```
ctrl+x+y enter Save the prover-id
```
cd

cd nexus

curl https://cli.nexus.xyz/ | sh
```
<br>
