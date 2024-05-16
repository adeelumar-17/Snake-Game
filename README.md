# Snake-Game
Snake game using 8086(x86-16) assembly language
## Introduction to 8086 Assembly Language

8086 Assembly Language is the low-level programming language used to write programs for the Intel 8086 microprocessor. It is a type of assembly language specific to the Intel x86 architecture, which was widely used in personal computers during the 1980s and early 1990s.

Assembly language programs for the 8086 processor consist of instructions that directly manipulate the CPU registers, memory, and other hardware components. Each register is of 2 bytes(16-bit) and each assembly language instruction corresponds to one machine language instruction, making it a close representation of the underlying hardware.
If you want to learn assembly language programming, 8086 is an easier option due to its simplicity as compared to modern x64 architecture assembly.
## Requirements
To play this game you need to have following installed on your system:<br>
1.[DOSBox](https://www.dosbox.com/download.php?main=1)<br>
After downloading DOSBox, just run the installer and follow on-screen instructions.<br>
2.[NASM](https://www.nasm.us/pub/nasm/releasebuilds/2.16.03/dos/)<br>
Download the nasm-2.16.03-dos.zip file, unzip it then copy the folder to root of any partition preferably in "C:\".
## Installation
Clone this repository using the following command:<br>
`git clone https://github.com/adeelumar-17/Snake-Game.git`<br>
To run the above command you should have git installed.<br>
Now copy the snake.asm file from the cloned repository to nasm folder that you had copied to partition of your choice.

## How to play?
RUN DOSBox.<br>
Mount the nasm folder.<br>
Syntax: mount DRIVE_LETTER: <path_to_nasm><br>
` mount C: C:\nasm `<br>
Now switch to the DRIVE_LETTER you chose, in this case "C".<br>
` C: `<br>
Generate raw binary file using following command:<br>
` nasm snake.asm -o snake.com `<br>

Run the binary file<br>
` snake `
## Controls
Use arrow keys to move.<br>
Avoid obstacles to survive.

## 🌟 Why learn Assembly Language? ##

Welcome to the realm of assembly language, where the raw power of computing meets elegant simplicity. In a world dominated by high-level languages, you might wonder: Why bother with assembly?

Here's why:

- **Unmatched Performance**: Assembly language allows for fine-grained control over hardware, enabling developers to squeeze every ounce of performance out of a system. In performance-critical applications like gaming, real-time systems, and device drivers, assembly language shines.

- **Deep Understanding of Computing**: Learning assembly language is akin to peering under the hood of a car and understanding how every gear and piston works together. It provides a profound understanding of computer architecture and how software interacts with hardware, making you a better programmer overall.

- **Legacy Systems and Optimization**: While newer languages abound, assembly remains indispensable in certain domains. Many legacy systems still rely on assembly for critical components, and in embedded systems programming, where resources are scarce, assembly's efficiency is unmatched.

- **Security and Reverse Engineering**: Assembly language is the language of choice for security professionals and reverse engineers. By understanding assembly, you can dissect and analyze software at the lowest level, uncovering vulnerabilities and crafting exploits.

- **Nostalgia and Craftsmanship**: There's an undeniable charm in crafting code at the bare metal level, reminiscent of a bygone era when programmers wielded absolute control over their machines. Writing assembly is as much an art form as it is a technical skill.

So, why assembly? Because it's not just a language; it's a journey into the heart of computing itself, where every instruction tells a story of power, efficiency, and elegance.
## 🐍 Contribute to Our 8086 Assembly Snake Game! 🐍 ##
**🛠️ How to Contribute:**
- **Bug Fixes:** Spot a bug? Feel free to squash it and submit a pull request.
- **Enhancements:** Have ideas for new features or improvements? We'd love to hear them!
- **Optimizations:** Help optimize the code to make the game run smoother or use fewer resources.
- **Documentation:** Improve the README, add comments, or write documentation to make it easier for others to understand and contribute.
