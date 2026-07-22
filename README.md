# Implement-and-test-a-conditional-access-policy
My organization needs to be able to limit user access to its internal applications. You must deploy an Microsoft Entra conditional access 


h2> walk-through:</h2>

<p align="center">
Launch the Microsoft Entra admin center: <br/>
  In the left navigation, under Entra ID, select Conditional access.
  On the Overview, select + Create new policy.
<img src=https://i.imgur.com/VVtIIJt.png/>
<br />
<br />
  In the Name box, enter Block APP1 for DebraB.


  <br/>
<img src=https://i.imgur.com/oC5xyUo.png/>
<br />
<br />
Select users and groups, then select the Users and groups check box.





 <br/>
<img src=https://i.imgur.com/IgAR8u9.png/>
<br />
<br />
In the Select users and groups pane, select Debra account and then select Select:  <br/>
<img src=https://i.imgur.com/ytdzRN9.png/>
<br />
<br />
Select Target Resources - No target resources selected.

Within the Include make sure Select resources is selected, then in the Select specific resources select None: <br/>
<img src=https://i.imgur.com/U4CfHIA.png/>
<br />
<br />
In the Session pane, select Sign-in frequency.

In the value box, enter 30.

Select the units dropdown, then select Days.

Select Select.

  <br/>
<img src=https://i.imgur.com/VdXIQaM.png/>
<br />
<br />
Under Enable policy, select Report-only, and then select Create:  <br/>
<img src=https://i.imgur.com/7ZwykbY.png/>
</p>

  In this exercise, i configured session controls to require users to reauthenticate at a defined frequency, in report-only mode. This exercise showed how session controls reduce risk for long-lived sessions.<br/>
<!--
In this exercise, you configured session controls to require users to reauthenticate at a defined frequency, in report-only mode. This exercise showed how session controls reduce risk for long-lived sessions.
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
