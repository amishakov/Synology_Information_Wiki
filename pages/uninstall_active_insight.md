To automatically uninstall Active Insight after a DSM update re-installs it: 

1. Open Task Scheduler.
2. Click "Task > Triggered Task > User-defined script".
3. Set the Task name to "Uninstall Active Insight".
4. Set User to "root".
5. Set Event to "Boot-up".
6. Make sure it's Enabled.
7. Click the "Task Settings" tab and in the "User-defined script" box enter: 
    ```
    /usr/syno/bin/synopkg uninstall ActiveInsight
    ```
8. Click OK.

</br>

Step 2

<img width="337" height="124" alt="image" src="https://github.com/user-attachments/assets/26eac2b7-ef33-4a13-861c-a79a96c94044" /></br>

Steps 3 to 6

<img width="474" height="311" alt="image" src="https://github.com/user-attachments/assets/c09c9475-37c1-4151-a9ab-50757484f6e0" /></br>

Step 7

<img width="523" height="380" alt="image" src="https://github.com/user-attachments/assets/b31ad5d6-9ed5-4504-8d40-6b334fbb38b6" />

