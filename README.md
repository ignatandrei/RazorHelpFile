RazorHelpFile
=============

This file generates help view files for each view in an ASP.NET MVC project.

Imagine you have a MVC site and you want to generated help for each view. This file generates for you the structure for having a view help file for each view that you have in the project.
More, if the help file already exists in the project, it will be not overwritten.

The template can be customized:
-the folder name:
//change here the location folder where the help files will be generated
static string HelperFolderName="Help";
-the content of the file
//change here the default content of the file
string TextFile = "<html><body>This is the help file for the view {0}</body></html>";


License:

Developer shall not be responsible for, and shall not pay, any amount of incidental, consequential or other indirect damages, whether based on lost revenue or otherwise, regardless of whether Developer was advised of the possibility of such losses in advance. In no event shall Developer's liability hereunder exceed the amount of license fees paid by Licensee, regardless of whether Licensee's claim is based on contract, tort, strict liability, product liability or otherwise. 

See demo at http://youtu.be/ZGsNHyFA9yw
See blog post a http://msprogrammer.serviciipeweb.ro/
Use: 
Download .tt file
Put this in index.cshtml file: 
a href='@Url.Content("~/Help/Views/Home/Index.cshtml")' target="_blank">Index Help /a

