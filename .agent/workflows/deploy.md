---
description: Deploy the website to Surge.sh (Free Static Hosting)
---

# Deploy to Surge.sh

1. Open a terminal in the project root (`e:\jjys_impex_website`).
2. Run the following command:
   ```powershell
   npx surge
   ```
3. **Authentication**:
   - If this is your first time, type your **email** and create a **password** when prompted.
   - If you have an account, login with your credentials.
4. **Configuration**:
   - **Project**: Press Enter to accept the current directory.
   - **Domain**: Press Enter to accept the random domain (e.g., `silly-name.surge.sh`) OR type a custom one (e.g., `jjys-impex.surge.sh`).
5. **Success**:
   - Wait for the upload to finish.
   - Copy the `http://...surge.sh` URL shown in the terminal.
   - Share the URL with the team!
