# IT-FreeLancer
IT sohasini o'rgantuvchi onlayn ta'lim platformasi.

https://go.microsoft.com/fwlink/?linkid=2108834&amp;Channel=Stable&amp;language=en-gb


https://telegram.org/dl/desktop/win64_portable

https://nodejs.org/dist/v14.18.1/node-v14.18.1-x64.msi

https://www.iis.net/downloads/microsoft/url-rewrite

https://github.com/azure/iisnode/releases/download/v0.2.21/iisnode-full-v0.2.21-x64.msi


mongodb+srv://kuldashev:<password>@cluster0.o7vq6.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
  
  
  
  
  mongodb+srv://kuldashev:mO5JzQd3x8annG8z@cluster0.r6vwn.mongodb.net/maktab?retryWrites=true&w=majority

  
  123zxcqaws!78553vef
  
  
  0ta0na0'g'li$#)
  
  
  <configuration>
<system.webServer>
<handlers>
  <add name="iisnode" path="WebAPI.js" verb="*" modules="iisnode" />
</handlers>

<rewrite>
  <rules>
    <rule name="nodejs">
      <match url="(.*)" />
      <conditions>
        <add input="{REQUEST_FILENAME}" matchType="IsFile" negate="true" />
      </conditions>
      <action type="Rewrite" url="/WebAPI.js" />
    </rule>
  </rules>
</rewrite> 

<security>
  <requestFiltering>
    <hiddenSegments>
      <add segment="node_modules" />
      <add segment="iisnode" />
    </hiddenSegments>
  </requestFiltering>
</security>
</system.webServer>
 </configuration>

