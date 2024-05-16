# Snake-Game
Snake game using 8086(x86-16) assembly language
## Requirements
To play this game you need to have following installed on your system:
1.[DOSBox](https://www.dosbox.com/download.php?main=1)
After downloading DOSBox, just run the installer and follow on-screen instructions.
2.[NASM](https://www.nasm.us/pub/nasm/releasebuilds/2.16.03/dos/)
Download the nasm-2.16.03-dos.zip file, unzip it then copy the folder to root of any partition preferably in C:\.
## Installation
Clone this repository using the following command:
```git clone https://github.com/adeelumar-17/Snake-Game.git```
To run the above command you should have git installed.

Now copy the snake.asm file from the cloned repository to nasm folder that you had copied to partition of your choice.

## How to play?
RUN DOSBox.
Mount the nasm folder.
Syntax: mount DRIVE_LETTER: <path_to_nasm>
``` mount C: C:\nasm ```
Now switch to the DRIVE_LETTER you chose, in this case "C".
``` C: ```
Generate raw binary file using following command:
``` nasm snake.asm -o snake.com ```

Run the binary file
``` snake ```
## Controls
Use arrow keys to move.
Avoid obstacles to survive.


## 🐍 Contribute to Our 8086 Assembly Snake Game! 🐍 ##

**🌟 Why Assembly?**

Welcome to the realm of assembly language, where the raw power of computing meets elegant simplicity. In a world dominated by high-level languages, you might wonder: Why bother with assembly?

Here's why:

- **Unmatched Performance**: Assembly language allows for fine-grained control over hardware, enabling developers to squeeze every ounce of performance out of a system. In performance-critical applications like gaming, real-time systems, and device drivers, assembly language shines.

- **Deep Understanding of Computing**: Learning assembly language is akin to peering under the hood of a car and understanding how every gear and piston works together. It provides a profound understanding of computer architecture and how software interacts with hardware, making you a better programmer overall.

- **Legacy Systems and Optimization**: While newer languages abound, assembly remains indispensable in certain domains. Many legacy systems still rely on assembly for critical components, and in embedded systems programming, where resources are scarce, assembly's efficiency is unmatched.

- **Security and Reverse Engineering**: Assembly language is the language of choice for security professionals and reverse engineers. By understanding assembly, you can dissect and analyze software at the lowest level, uncovering vulnerabilities and crafting exploits.

- **Nostalgia and Craftsmanship**: There's an undeniable charm in crafting code at the bare metal level, reminiscent of a bygone era when programmers wielded absolute control over their machines. Writing assembly is as much an art form as it is a technical skill.

So, why assembly? Because it's not just a language; it's a journey into the heart of computing itself, where every instruction tells a story of power, efficiency, and elegance.

**🛠️ How to Contribute:**
- **Bug Fixes:** Spot a bug? Feel free to squash it and submit a pull request.
- **Enhancements:** Have ideas for new features or improvements? We'd love to hear them!
- **Optimizations:** Help optimize the code to make the game run smoother or use fewer resources.
- **Documentation:** Improve the README, add comments, or write documentation to make it easier for others to understand and contribute.
