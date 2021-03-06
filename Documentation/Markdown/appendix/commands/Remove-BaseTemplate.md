# Remove-BaseTemplate 
 

Remove-BaseTemplate -Item <Item> -TemplateItem <TemplateItem[]> [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-BaseTemplate -Item <Item> -Template <string> [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-BaseTemplate -Path <string> -TemplateItem <TemplateItem[]> [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-BaseTemplate -Path <string> -Template <string> [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-BaseTemplate -Id <string> -TemplateItem <TemplateItem[]> [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-BaseTemplate -Id <string> -Template <string> [-WhatIf] [-Confirm] [<CommonParameters>]

Remove-BaseTemplate [-Database <string>] [-WhatIf] [-Confirm] [<CommonParameters>]
 
 
## Syntax 
 
Remove-BaseTemplate -Item &lt;Item&gt; -TemplateItem &lt;TemplateItem[]&gt; [-WhatIf] [-Confirm] 
 
Remove-BaseTemplate -Item &lt;Item&gt; -Template &lt;string&gt; [-WhatIf] [-Confirm] 
 
Remove-BaseTemplate -Path &lt;string&gt; -TemplateItem &lt;TemplateItem[]&gt; [-WhatIf] [-Confirm] 
 
Remove-BaseTemplate -Path &lt;string&gt; -Template &lt;string&gt; [-WhatIf] [-Confirm] 
 
Remove-BaseTemplate -Id &lt;string&gt; -TemplateItem &lt;TemplateItem[]&gt; [-WhatIf] [-Confirm] 
 
Remove-BaseTemplate -Id &lt;string&gt; -Template &lt;string&gt; [-WhatIf] [-Confirm] 
 
Remove-BaseTemplate [-Database &lt;string&gt;] [-WhatIf] [-Confirm] 
 
 
## Parameters 
 
### -Confirm&nbsp; &lt;switch&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>cf</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -Database&nbsp; &lt;string&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -Id&nbsp; &lt;string&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>true</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -Item&nbsp; &lt;Item&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>true</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>true (ByValue)</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -Path&nbsp; &lt;string&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>FullName, FileName</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>true</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -Template&nbsp; &lt;string&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>true</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -TemplateItem&nbsp; &lt;TemplateItem[]&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>true</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
### -WhatIf&nbsp; &lt;switch&gt; 
 
 
 
<table>
    <thead></thead>
    <tbody>
        <tr>
            <td>Aliases</td>
            <td>wi</td>
        </tr>
        <tr>
            <td>Required?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Position?</td>
            <td>Named</td>
        </tr>
        <tr>
            <td>Default Value</td>
            <td></td>
        </tr>
        <tr>
            <td>Accept Pipeline Input?</td>
            <td>false</td>
        </tr>
        <tr>
            <td>Accept Wildcard Characters?</td>
            <td></td>
        </tr>
    </tbody>
</table> 
 
## Inputs 
 
The input type is the type of the objects that you can pipe to the cmdlet. 
 
* Sitecore.Data.Items.Item 
 
## Outputs 
 
The output type is the type of the objects that the cmdlet emits. 
 
* System.Object 
 

