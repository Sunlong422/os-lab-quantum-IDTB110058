# os-lab-quantum-IDTB110058
# My First Markdown File

Hello, this is a Markdown file.

# Level 2: Audit Trails - Add logging capabilities to buy_widget to track successful transactions.

![alt text](<level 2.png>)

# Level 3: The Exploit (TOC-TOU) - Create the bot_swarm script to simulate a concurrent attack and document the resulting race condition.
Run 1 final inventory: 82<br>
Run 2 final inventory: 80<br>
Run 3 final inventory: 82<br>
Run 4 final inventory: 66<br>
Run 5 final inventory: 72<br>

Explanation:
The final inventory changes because many processes run at the same time and access inventory.txt concurrently. Several bots may read the same inventory
value before another bot writes the updated value back, so the final result depends on how the operating system schedules the processes.

# Level 4: The Patch (Mutex) - Secure the buy_widget script using OS-level file locking (flock) to prevent the exploit.
![alt text](<level 4.png>)

# Level 5: Red Team vs. Blue Team - Pair up with a classmate, configure cross-user permissions, and test your mutex against their bot swarm.
![alt text](<level 5.png>)

# Level 6: Secure Drop Zone (PoLP) - Build the dropzone script to provision a secure folder where classmates can upload files but cannot delete yours.
![alt text](<level 6.png>)

# Level 7: Forensic Cleanup - Build the cleanup script to automatically organize generated log and dump files by their extension.
![alt text](<level 7.png>)