<div align="center">

## Allow Numbers


</div>

### Description

Allow only numbers along with one deciaml.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Javed Jabbar](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/javed-jabbar.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/javed-jabbar-allow-numbers__1-22020/archive/master.zip)





### Source Code

```
'***********************************************************
' This code only allows numbers along with one decimal
' point in text box named txtNumber. Also allow backspace.
'***********************************************************
  If KeyAscii > 47 And KeyAscii < 58 Or KeyAscii = 8 Or KeyAscii = 46 Then
    If KeyAscii = 46 Then
      If InStr(txtNumber.Text, ".") Then
        KeyAscii = 0
        Exit Sub
      Else
        txtNumber.Text = txtNumber.Text
      End If
    Else
    End If
  Else
    KeyAscii = 0
  End If
```

