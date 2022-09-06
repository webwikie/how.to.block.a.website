# How to Block a Website

[![How to Block a Website](redd.png)](https://github.com/webwikie/how.to.block.a.website/)

1. Open Windows Explorer and navigate to C:WindowsSystem32driversetc. (If Windows is not installed on C:, substitute the appropriate drive letter.)

2. Double-click hosts, and select Notepad when Windows prompts you to choose a program. If you don’t get the prompt, or if the hosts file opens in another program, open Notepad (Start, All Programs, Accessories, Notepad), and then navigate to hosts by clicking File, Open within Notepad.

3. Place the cursor at the end of the last line, which will say something such as “127.0.0.1 localhost” or “::1 localhost”. Press Enter to create a new line.

4. Type 127.0.0.1, tap the spacebar once, and then type the address of a website you want to block. For example, to block all traffic from YouTube, type 127.0.0.1 www.youtube.com on this line.

5. Continue to add the websites you wish to block, each prefaced with 127.0.0.1 and a space.

6. Click File, Save to commit to your changes. Dismiss any warnings from antimalware software, which may be triggered by your editing of the hosts file.

7. Close any open browser windows, and then reopen a browser to test your edits. The blocked sites should not display in any browser.
