<div align="center">

## Program with Command Line inputs


</div>

### Description

Make your application run from command lines or the run dialog with arguements. ie: myapp.exe -m

No need to vote for this code because it is really basic.
 
### More Info
 
You have to put this code in a module. Set the startup for your app to Sub Main(). Add a label to form1 (Label1)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Armen Shimoon](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/armen-shimoon.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/armen-shimoon-program-with-command-line-inputs__1-23210/archive/master.zip)





### Source Code

```
Sub Main()
If Command = "" Then
  Form1.Label1.Caption = "No arguement."
  Form1.Show
ElseIf Command = "-m" Then
  Form1.Show
  Form1.WindowState = 1
  Form1.Label1.Caption = "Arguement: " & Command
Else
  Form1.Label1.Caption = "Arguement: " & Command
  Form1.Show
End If
End Sub
```

