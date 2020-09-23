<div align="center">

## byte\[\] to Image


</div>

### Description

Converts a byte array to image. usefull for converting blob images from database to an image that can be displayed in a picture box.
 
### More Info
 
image byte array

Image

Don&#8217;t know what side effects. Surprisingly this does not eat up much memory that I can tell.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Rolland](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/rolland.md)
**Level**          |Intermediate
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |C\#
**Category**       |[Databases](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/databases__10-5.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/rolland-byte-to-image__10-4382/archive/master.zip)





### Source Code

```
private System.Drawing.Image createImage(byte[] image_data)
{
return System.Drawing.Image.FromStream(new System.IO.MemoryStream(image_data));
}
```

