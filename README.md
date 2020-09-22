<div align="center">

## GUI Design Tips v2\.0


</div>

### Description

I am very surprised to see the lack of information in the area of Graphical User Interface (GUI) Design on this web site. Here are some tips to get you seriously thinking about how people use your software.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Daniel Cassar](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/daniel-cassar.md)
**Level**          |Beginner
**User Rating**    |4.7 (93 globes from 20 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VBA MS Access
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/daniel-cassar-gui-design-tips-v2-0__1-44924/archive/master.zip)





### Source Code

<B><FONT SIZE=2><P>User Interface Design</P>
</B><P>Version 2</P>
<P>I am very surprised to see the lack of information in the area of Graphical User Interfaces (GUI) on this web site. The useability of your software will largely affect peoples impressions. Here is some information that will hopefully get you thinking more seriously about how you design your software.</P>
<B><P>1. Applying Psychology to Design</P>
</B>
<B><P>1.1 Sensation &amp; Perception</P>
</B><P>Don’t rely on a visual notification alone to let the user know a process has started or finished. Processes that can take a while may be helped by using audition to let the user know the task has been started or completed. At the same time be weary of sensory overkill, the user doesn’t want the system beeping at them every 5 seconds or to have a message box popping up interrupting them from the task they are performing. </P>
<I><P>Tip: Avoid actions that could stress/frustrate sensory systems.</P>
</I>
<B><P>1.1.1 Feedback</P>
</B><P>Provide feedback for users actions. Good feedback helps confirm that the software is responding to input and communicates details that distinguish the nature of the action. Effective feedback is timely and is presented as close to the point of the user's interaction as possible. Even when the computer is processing a particular task, provide the user with information about the state of the process and how to cancel the process if that is an option. Nothing is more disconcerting to users than a "dead" screen that is unresponsive to input. A typical user will tolerate only a few seconds of an unresponsive interface.</P>
<I><P>Tip: You can communicate simple information through mouse pointer changes, sounds or a status bar message; for more complex feedback, you may need to display a progress control or message box.</P>
</I>
<B><P>1.2 Attention &amp; Performance</P>
<P>1.2.1 Decision Automation</P>
</B><P>The operational assumption is that the user - not the computer or software - initiates actions. The user plays an active rather than reactive role. You can automate tasks, but implement the automation in a way that allows the user to choose or control it.</P>
<I><P>Tip: Do not automatically get your program to run on start up or place icons on the desktop.</P>
</I><B>
<P>1.2.2 Design for Learning</P>
</B><P>Initial performance by new users is slow and may require attention and guidance, however once a task has been learnt continually guiding a user through the task is both slow and frustrating, the option to better automate the task needs to be available to the user.</P>
<I><P>Tip: Make use of program preferences to turn on/off help aids.</P>
<P>Tip: Have multiple ways of executing common tasks such as menu options, icon bars, shortcut-keys and dropdown menus.</P>
<P>Tip: Make menu bars and tool bars more customable.</P>
</I>
<B><P>1.2.3 Design for Error</P>
</B><P>Don’t just capture boundary conditions. Take into account mistakes of intention and action slips of commission. Users like to explore an interface and often learn by trial and error.</P>
<I><P>Tip: Make use of message boxes to warn, notify users about potential situations where they could damage the system or data, or better, makes actions reversible or recoverable.</P>
</I>
<B><P>1.3 Human Memory</P>
</B><P>Use existing knowledge when possible. Assist learning by analogy and use recognition over recall.</P>
<P>Don’t overload short-term memory, remember an average person has a limit of 7+/-2 ‘chunks’ for about 15 seconds. Auditory rehearsal, primacy &amp; recency effects are also a focus of short-term memory. Maintain an external memory for the user where possible.</P>
<P>Design for consistency to avoid interference: Avoid pro-active and retroactive interference</P>
<B><P>1.4 User Neiching</P>
</B><P>Who are the people using your software and how often do they use it. You need to take into account their industry background, age, frequency of use and general computer knowledge.</P>
<I><P>Tip: Be careful who evaluates your software, are they the types of people who will be using it?</P>
</I>
<B><P>2. Design Principles/Goals</P>
</B><P>Simplicity – Simple tasks should be easy to do</P>
<P>Generalisability – One set of conventions should apply to many tasks</P>
<P>Consistency – Follow established / own conventions</P>
<P>Redundancy – Provide multiple means to accomplish tasks</P>
<P>Documentability – Systems should be easy to document</P>
<P>Accuracy – Online help and documents should reflect actual function</P>
<P>Learnability – Terms/icons/syntax/operations should be memorable/discriminable</P>
<P>Flexibility – Systems should adapt to individual/different users</P>
<P>Recoverability – Systems should allow recovery from errors</P>
<P>Security/Privacy – Systems should not sacrifice privacy/security for ease of use</P>
<P>Stress/fun systems should not be stressful; they should be fun</P>
<B><P>3. Tradeoffs of Design Principles/Issues</P>
</B><P>Specificity/Generality: General Systems may not be particularly good at specific tasks</P>
<P>Internal / External: Internally consistent systems may violate external conventions</P>
<P>Learnability / Usability: Easy-to-learn does not imply easy-to-use</P>
<P>Speed/Accuracy: The faster people try to go, the more they will make errors</P>
<P>Information Depth / Breadth: The more breadth provided, the less depth is covered</P>
<P>Batch / Interactive: Systems should support interactive access, with programmability</P>
<P>Passive/Active: Experts may use commands, novices menus, so provide both</P>
<P>Brevity/Verbosity: Amount of information must adapt to user needs</P>
<P>Graphical/Textual: Intuitive graphical interfaces may not be programmable</P>
<B><P>4. Style Guide</P>
</B>
<B><P>4.1 Controls</P>
</B><P>Instructional text is generally placed above the control in question, additional information below. Don’t forget to properly set the tab index’s for the controls in a coherent manner and they have tool tip text if applicable.</P>
<B><P>4.1.2 Button Labels</P>
</B><P>Button labels should describe the buttons action and follow book-title capitalisation.</P>
<P>You can use the button label to reflect other information about the button's operation. For example, if the action represented by the button requires additional information, include an ellipsis (…). If the button expands the window to display additional information, include (&gt;&gt;).</P>
<B><P>4.1.3 Option Buttons &amp; Check Boxes</P>
</B><P>Limit to a small number, typically seven or fewer. If you need more choices, consider using a different type of control, such as a single-selection list box or a drop-down list box.</P>
<P>Use sentence-style capitalisation with no ending punctuation. Write parallel labels of approximately equal length for related check boxes. If a check box label also acts as the label for the control that follows it, end the label with a colon</P>
<B><P>4.1.4 List Boxes</P>
</B><P>List box controls do not include their own labels. However, you should include a label using a static text field; the label enables you to provide a description of the control and keyboard access to the control. Use sentence-style capitalisation for a list box label and end the label with a colon</P>
<P>Use sentence-style capitalisation for items in the list. The width of the list box should be sufficient to display the average width of an entry in the list.</P>
<B><P>4.2 Menu Items </P>
</B><P>If the menu is a verb use a noun or noun phrase</P>
<I><P>Eg. On the <B>Insert</B> menu: <B>Text</B>, <B>Table</B>, <B>Picture</P>
</B></I>
<P>If the menu is a noun use a verb or verb phrase</P>
<I><P>Eg. On the <B>Table</B> menu: <B>Insert Table, Select Row, Insert Column</P>
</B></I>
<B><P>4.3 Shortcut Keys</P>
</B><P>Use the following guidelines for designing shortcut keys: </P>
<UL>
<LI>Assign simple and consistent key combinations. </LI>
<LI>Make shortcut keys customizable. </LI>
<LI>Use a shortcut with the CTRL key for actions that represent a large-scale effect, such as CTRL+S for save current document. </LI>
<LI>Use the SHIFT+ <I>key</I> combination for actions that extend or complement the actions of the standard shortcut key. For example, the ALT+TAB shortcut key displays the primary window of a running application. Alternatively, the SHIFT+ALT+TAB key combination allows you to navigate backward through currently running applications that have been previously accessed. </LI>
<LI>Use the SPACEBAR key as the default action of a control, such as for pressing a button control or toggling the status of a check box control. This is similar to clicking the left or primary mouse button. </LI>
<LI>Use the ENTER key for the default action of a dialog box, if available. </LI>
<LI>Use the ESC key to stop or cancel an operation. </LI>
<LI>Avoid modified or case-sensitive letters for shortcuts. </LI>
<LI>Avoid using the following characters for shortcut keys: @ £ $ {} [] \ ~ | ^ ' &lt; &gt; </LI>
<LI>Avoid ALT+ <I>letter</I> combinations because they may conflict with access keys. In addition, the system uses many specific key combinations for specialized input; for example, ALT+~ invokes an input editor for the Japanese language. </LI>
<LI>Avoid CTRL+ALT combinations because the system interprets this combination in some language versions as an ALTGR key, which generates alphanumeric characters. </LI>
<LI>Avoid assigning combinations that are reserved or defined by the system or are commonly used by other applications. </LI>
<LI>Do not use the Windows logo key as a modifier key for non-system-level functions. </LI></UL>
<UL>
<I><LI>Common shortcuts: New - Ctrl-N; Open – Ctrl-O; Save – Ctrl-S; Print – Ctrl-P; Undo – Ctrl-Z; Cut – Ctrl-X; Copy – Ctrl-C; Paste – Ctrl-V; Select All – Ctrl-A; Find – Ctrl-F; Goto – Ctrl-G.</LI></UL>
</I></FONT>

