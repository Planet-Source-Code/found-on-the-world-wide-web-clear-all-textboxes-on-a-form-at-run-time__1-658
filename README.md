<div align="center">

## Clear all textboxes on a form at run\-time


</div>

### Description

handy code for clearing all text box controls at run-time

so you don't have to bother doing it at design time.

http://137.56.41.168:2080/VisualBasicSource/vbworkingwithtextbox.txt
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the World Wide Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-world-wide-web.md)
**Level**          |Unknown
**User Rating**    |5.0 (20 globes from 4 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-world-wide-web-clear-all-textboxes-on-a-form-at-run-time__1-658/archive/master.zip)





### Source Code

```
'make a new form; put some textboxen on it with some text in it
'make a commandbutton
'put the next code under the Command_Click event
  	Dim Control
  	For Each Control In Form1.Controls
    	If TypeOf Control Is TextBox Then Control.Text = ""
  	Next Control
```

