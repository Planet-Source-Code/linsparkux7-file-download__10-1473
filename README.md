<div align="center">

## File Download


</div>

### Description

This shows how to download a file in VB.NET and C# in only 2 lines of code! This is meant for BEGINNERS, but all are welcome to see it. I know this isn't much code, in fact, not event much of anything at all, but I was desperately trying to find a way to download a file with nonprintable characters (such as EXE's or DLL's), but when I tried using streams, it wouldn't come out quite right. Finally, I found a way to do this, so I am sharing it with everybody else in case someone need it also.
 
### More Info
 
Platforms: Windows 98, Windows NT 4.0, Windows Millennium Edition, Windows 2000, Windows XP Home Edition, Windows XP Professional, Windows .NET Server family


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[LinSparkUx7](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/linsparkux7.md)
**Level**          |Beginner
**User Rating**    |4.1 (33 globes from 8 users)
**Compatibility**  |C\#, VB\.NET
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__10-9.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/linsparkux7-file-download__10-1473/archive/master.zip)





### Source Code

```
'[Visual Basic]
'<ComVisible(True)>
'Public Sub DownloadFile( _
' ByVal address As String, _
' ByVal fileName As String _
')
Dim myWebClient As New System.Net.WebClient()
myWebClient.DownloadFile("http://www.google.com/images/logo.gif", "C:\GoogleLogo.gif")
'The code above downloads the google logo into the root directory of the C drive.
'[C#]
'[ComVisible(true)]
'public void DownloadFile(
' string address,
' string fileName
');
System.Net.WebClient myWebClient = new System.Net.WebClient();
myWebClient.DownloadFile("http://www.google.com/images/logo.gif","C:\GoogleLogo.gif");
'The code above downloads the google logo into the root directory of the C drive.
```

