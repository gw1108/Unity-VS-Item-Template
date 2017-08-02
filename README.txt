Copy the .zip file and paste it in the user item template location.
------------------------------------------------------------------------------------------------------------------------------------------
2005:
C:\Program Files (x86)\Microsoft Visual Studio 8\Common7\IDE\ItemTemplates\CSharp\1033\Class.zip

2008:
C:\Program Files (x86)\Microsoft Visual Studio 9.0\Common7\IDE\ItemTemplates\CSharp\Code\1033\Class.zip

2010:
C:\Program Files (x86)\Microsoft Visual Studio 10.0\Common7\IDE\ItemTemplates\CSharp\Code\1033\Class.zip
-----------------------------------------------------------------------------------------------------------------------------------------
Starting with Visual Studio 2012, the templates are not zipped, so you can edit each .cs template in each applicable folder directly.
2012:
C:\Program Files (x86)\Microsoft Visual Studio 11.0\Common7\IDE\ItemTemplates\CSharp\Code\1033\Class\Class.cs

2013:
C:\Program Files (x86)\Microsoft Visual Studio 12.0\Common7\IDE\ItemTemplates\CSharp\Code\1033\Class\Class.cs

2015:
C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\IDE\ItemTemplates\CSharp\Code\1033\Class\Class.cs

2017:
ENTERPRISE
C:\Program Files (x86)\Microsoft Visual Studio\2017\Enterprise\Common7\IDE\ItemTemplates\CSharp\Code\1033\Class\Class.cs
-------------------------------------------------------------------------------------------------------------------------------------------
*Notes*
Express Editions

In Express Editions you will have to search in the subdirectory WDExpress inside the IDE folder, so e.g. for VS 2015 Express:

C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\IDE\WDExpress\ItemTemplates\CSharp\Code\1033\Class\Class.cs
*Other Languages*
If you don't use the English version of Visual Studio, the folder 1033 may not exist, but a different number representing your language. For example it is 1031 in a German installation.

In Windows Vista, the default directory is ..\Users\<username>\Documents\Visual Studio 2010\Templates\ItemTemplates\. 

For more information, see :
http://msdn.microsoft.com/en-us/library/vstudio/ms247113%28v=vs.100%29.aspx

Some restarting of Visual Studio may be required.